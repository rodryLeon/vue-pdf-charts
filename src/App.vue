<template>
	<div id="app">

		<controls-container
			:progress="progress"
			@generateReport="downloadPdf()"
		/>

		<vue-html2pdf
			:show-layout="controlValue.showLayout"
			:enable-download="controlValue.enableDownload"
			:preview-modal="controlValue.previewModal"
			:filename="controlValue.filename"
			:paginate-elements-by-height="controlValue.paginateElementsByHeight"
			:pdf-quality="controlValue.pdfQuality"
			:pdf-format="controlValue.pdfFormat"
			:pdf-orientation="controlValue.pdfOrientation"
			:pdf-content-width="controlValue.pdfContentWidth"
			:manual-pagination="controlValue.manualPagination"
			:html-to-pdf-options="htmlToPdfOptions"

			@progress="onProgress($event)"
			@hasStartedGeneration="hasStartedGeneration()"
			@hasGenerated="hasGenerated($event)"
			ref="html2Pdf"
		>
			<pdf-content
				@domRendered="domRendered()"
				slot="pdf-content"
			/>
		</vue-html2pdf>
	</div>
</template>

<script>
import PdfContent from '@/components/PdfContent'
// import VueHtml2pdf from '@/components/VueHtml2pdf'
import ControlsContainer from '@/components/ControlsContainer'
import VueHtml2pdf from 'vue-html2pdf'
// import VueHtml2pdf from 'vue-html2pdf-test'
import { mapFields } from 'vuex-map-fields'

export default {
	name: 'app',

	data () {
		return {
			contentRendered: false,
			progress: 0,
			generatingPdf: false,
			pdfDownloaded: false,
		}
	},

	computed: {
        ...mapFields([
            'controlValue'
		]),
		
		htmlToPdfOptions () {
			return {
				margin: 0,

				filename: 'reporte.pdf',

				image: {
					type: 'jpeg', 
					quality: 0.98
				},

				enableLinks: true,

				html2canvas: {
					scale: this.controlValue.pdfQuality,
					useCORS: true
				},

				jsPDF: {
					unit: 'in',
					format: this.controlValue.pdfFormat,
					orientation: this.controlValue.pdfOrientation
				}
			}
		}
    },

	methods: {
		async downloadPdf () {
			if (!await this.validateControlValue()) return

			this.$refs.html2Pdf.generatePdf()
		},

		validateControlValue () {
			if (this.controlValue.pdfQuality > 2) {
				alert('pdf-quality value should only be 0 - 2')
				this.controlValue.pdfQuality = 2

				return false
			}

			if (!this.controlValue.paginateElementsByHeight) {
				alert('paginate-elements-by-height value cannot be empty')
				this.controlValue.paginateElementsByHeight = 1400
				
				return false
			}

			const paperSizes = [
				'a0', 'a1', 'a2', 'a3',
				'a4', 'letter', 'legal', 'a5', 'a6', 'a7',
				'a8', 'a9', 'a10'
			]

			if (!paperSizes.includes(this.controlValue.pdfFormat)) {
				alert(`pdf-format value should only be ${paperSizes}`)
				this.controlValue.pdfFormat = 'a4'

				return false
			}

			if (!this.controlValue.pdfOrientation) {
				alert('pdf-orientation value cannot be empty')
				this.controlValue.pdfOrientation = 'portrait'
				
				return false
			}

			if (!this.controlValue.pdfContentWidth) {
				alert('pdf-content-width value cannot be empty')
				this.controlValue.pdfContentWidth = '800px'
				
				return false
			}

			return true
		},

		onProgress (progress) {
			this.progress = progress
			console.log(`PDF generation progress: ${progress}%`)
		},

		hasStartedGeneration () {
			console.log(`PDF has started generation`)
		},

		hasGenerated (blobPdf) {
			this.pdfDownloaded = true
			console.log(`PDF has downloaded yehey`)
			console.log(blobPdf)
		},

		domRendered () {
			console.log('Dom Has Rendered')
			this.contentRendered = true
		},

		onBlobGenerate (blob) {
			console.log(blob)
		}
	},

	components: {
		VueHtml2pdf,
		PdfContent,
		ControlsContainer
	},
}
</script>

<style lang="scss">
html, body {
	width: 100%;
	padding: 0;
	margin: 0;
}


</style>
