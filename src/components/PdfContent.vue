<template>
  <section class="pdf-content">
    <!--intro page-->
    <section class="pdf-item">
      <div id="home-page-nom">
        <div class="container">
          <div class="row">
            <div class="col-lg">
              <div class="home-head">
                <div class="home-head-tit">{{ tituloEncuesta }}</div>
                <div class="home-head-sub">{{ subtituloEncuesta }}</div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg">
              <div class="home-page-body">
                <div class="home-body-logo"></div>
                <div class="home-body-partner">{{ socioEncuesta }}</div>
                <div class="home-body-date">{{ fechaHoy }}</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--Intro page-->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-lg">
              <div class="cont-page-tit">
                <h1>Introducción</h1>
              </div>
              <div class="cont-page-paragraph">
                <p>{{ saludoUsuario }}</p>
              </div>
              <div class="cont-page-paragraph-note">
                <p>
                  LIVE 13.5 te acompaña en la aplicación de las encuestas en la
                  NOM-035-STPS a todos los colaboradores dentro de la
                  organización, con la finalidad de identificar, analizar y
                  prevenir los factores de riesgo psicosocial para que
                  posteriormente se pueda promover un entorno organizacional
                  favorable en los centros de trabajo.
                </p>
              </div>
              <div class="cont-page-content">
                <p>
                  La NOM-035-STPS es una ley formada por un conjunto de Normas
                  Oficiales Mexicanas emitidas por la Secretaría del Trabajo y
                  Previsión Social, que establece las condiciones básicas y
                  necesarias de trabajo en los apartados de seguridad, medio
                  ambiente y salud. A su vez, trata de fomentar un entorno
                  organizacional favorable en las compañías.
                </p>
                <p>
                  Los Factores de Riesgo Psicosocial en el trabajo son los
                  aspectos psicológicos y sociales que pueden afectar
                  negativamente a los trabajadores dentro de una organización.
                  Pueden ser, por ejemplo, estrés grave, ansiedad o trastornos
                  del sueño de acuerdo al tipo de puesto, tipo de jornada
                  laboral o a la exposición a eventos traumáticos severos.
                </p>
                <p>
                  La evaluación que realizamos contribuye a ser más conscientes
                  sobre el entorno laboral que existe en la organización y así,
                  se puede actuar con antelación si existen riesgos
                  psicosociales dentro de la organización. Al cumplir con la
                  NOM-035-STPS estamos desarrollando una nueva cultura de
                  bienestar laboral y creando programas de salud que beneficien
                  a los empleados y te permitirá redireccionar los esfuerzos que
                  impactarán directamente en la satisfacción de tus empleados, y
                  en los resultados de toda la empresa.
                </p>
                <p>
                  Tanto para la compañía como para el empleado es importante que
                  el personal se sienta libre de expresar sus opiniones y
                  consideraciones. Éste reporte incluye la evaluación para
                  identificar a los trabajadores que estuvieron expuestos a un
                  acontecimiento traumático, así como los niveles de riesgo de
                  cada categoría, dominio y dimensión correspondiente. En LIVE
                  13.5 queremos caminar a tu lado y apoyarte en todo aquello que
                  necesites, es por ello que si requieres apoyo de un consultor
                  LIVE, con gusto estaremos a tu disposición.
                </p>
              </div>
              <div class="cont-sign">
                <p>
                  Atentamente
                  <br />
                  <span>La familia amarilla</span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--Introduccion analisis pagina 3 -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-lg">
              <div class="cont-page-tit">
                <h1>Introducción</h1>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg">
              <div class="cont-page-tit">
                <p>
                  El precepto de este reporte toma en cuenta la guía de
                  referencia I, II y III (Depende las guías implementadas), este
                  documento es el resultado del análisis de las guías de
                  referencia implementadas al centro de trabajo, las personas
                  encargadas de la elaboración de este proceso son los actuarios
                  que se encargan del estudio de los riesgos con el objetivo de
                  valorar las probabilidades de riesgos o éxito que hay en las
                  decisiones que se tomen en la empresa.
                </p>
                <p class="strong">
                  Se determinan y delimitan las dimensiones de análisis que
                  fueron identificadas con cada encuesta de acuerdo a la
                  NOM-035-STPS
                </p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg">
              <div class="text-center">
                <h2>Dimensiones del análisis</h2>
              </div>
            </div>
          </div>
          <div class="sidebar-page">
            <div class="row">
              <div class="col-4">
                <h3>Guía de referencia I</h3>
                <p>
                  La guia de referencia I permite identificar a los trabajadores
                  que han sido sujetos a acontecimientos traumárticos severos y
                  que requieren valoración clínica.
                </p>

                <table class="table table-1col">
                  <thead>
                    <tr>
                      <th scope="col" class="table-head">
                        Cuestionario para identificar a los trabajadores que
                        fueron sujetos a acontecimientos traumáticos severos.
                      </th>
                    </tr>
                    <tr>
                      <th scope="col" class="table-subhead">Sección</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">I- Acontecimiento traumático severo</th>
                    </tr>
                    <tr>
                      <th scope="row">
                        II- Recuerdos persistentes sobre el acontecimiento
                        (último mes)
                      </th>
                    </tr>
                    <tr>
                      <th scope="row">
                        III- Esfuerzo por evitar circunstancias parecidas o
                        asociadas al contecimiento (último mes)
                      </th>
                    </tr>
                    <tr>
                      <th scope="row">III- IV- Afectación (último mes)</th>
                    </tr>
                  </tbody>
                </table>
              </div>
              <div class="col-8">
                <div id="table-3col">
                  <div class="row th-aqua">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-3">
                          <p>Categoría</p>
                        </div>
                        <div class="col-3">
                          <p>Dominio</p>
                        </div>
                        <div class="col-6">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-12">
                      <div class="row purple-txt">
                        <div class="col-3">
                          <p>Categoría</p>
                        </div>
                        <div class="col-3">
                          <p>Dominio</p>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Condiciones peligrosas e inseguras</p>
                            </div>
                            <div class="col-12">
                              <p>Condiciones peligrosas e inseguras</p>
                            </div>
                            <div class="col-12">
                              <p>Trabajos peligrosos</p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="row aqua-txt">
                        <div class="col-3">
                          <p>Ambiente de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p class="hhalf">Carga de trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Falta de control sobre el trabajo</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Cargas cuantitativas</p>
                            </div>
                            <div class="col-12">
                              <p>Ritmos de trabajo acelerados</p>
                            </div>
                            <div class="col-12">
                              <p>Carga mental</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas psicológicas emocionales</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas de alta responsabilidad</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas contradictorias o inconalventes</p>
                            </div>
                            <div class="col-12">
                              <p>Falta de control y autonomía sobre el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Limitada o inexistente capacitación</p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="row blue-txt">
                        <div class="col-3">
                          <p>Organización del tiempo de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p>Jornadas de trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Interferencia en la relación trabajo-familia</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Jornadas de trabajo extensas</p>
                            </div>
                            <div class="col-12">
                              <p>Influencia del trabajo fuera del centro laboral</p>
                            </div>
                            <div class="col-12">
                              <p>Influencia de las responsabilidades familiares</p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="row">
                        <div class="col-3">
                          <p>Liderazgo y relaciones en el trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p class="hthirth">Liderazgo</p>
                            </div>
                            <div class="col-12">
                              <p class="hthirth2">Relaciones en el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Violencia</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Escasa claridad de funciones</p>
                            </div>
                            <div class="col-12">
                              <p>Características de liderazgo</p>
                            </div>
                            <div class="col-12">
                              <p>Relaciones sociales en el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>
                                Deficiente relación con los colaboradores que
                                supervisas
                              </p>
                            </div>
                            <div class="col-12">
                              <p>Violencia familiar</p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--pagina 4 demograficos  -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col">
              <div class="cont-page-tit">
                <h1>DATOS SOCIODEMOGRÁFICOS</h1>
              </div>
              <div class="cont-page-tit">
                <p class="strong">Total de colaboradores que participaron en la encuesta</p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <div id="chart-demograficos-circle">
                <apexchart
                  type="radialBar"
                  height="200"
                  :options="demograficos.chartOptions"
                  :series="demograficos.series"
                ></apexchart>
              </div>
            </div>
            <div class="col-6 mt40">
              <div id="total-contestaron">
                <span class="blue-txt-color">
                  {{ personasPartiparon }}
                  <br />
                </span>
                contestaron un total
                <br />de
                <span class="blue-txt-color">{{ colaboradoresTotal }}</span>
              </div>
            </div>
          </div>
          <!--table demograficos-->
          <div id="table-demog">
            <div class="row th-gray">
              <div class="col-6 text-left">
                <p>Centro de trabajo</p>
              </div>
              <div class="col-6">
                <div class="row">
                  <div class="col-4">
                    <p>Participó</p>
                  </div>
                  <div class="col-4">
                    <p>No participó</p>
                  </div>
                  <div class="col-4">
                    <p>Total</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-6 text-left">
                <p>Dirección planta</p>
              </div>
              <div class="col-6">
                <div class="row">
                  <div class="col-2">
                    <p>{{ direccionPlanta[0] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[1] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[2] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[3] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[4] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[5] }}%</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-6 text-left">
                <p>Dirección de operaciones</p>
              </div>
              <div class="col-6">
                <div class="row">
                  <div class="col-2">
                    <p>{{ direccionPlanta[0] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[1] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[2] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[3] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[4] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[5] }}%</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-6 text-left">
                <p>Dirección de administración y finanzas</p>
              </div>
              <div class="col-6">
                <div class="row">
                  <div class="col-2">
                    <p>{{ direccionPlanta[0] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[1] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[2] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[3] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[4] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[5] }}%</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-6 text-left">
                <p>Dirección general</p>
              </div>
              <div class="col-6">
                <div class="row">
                  <div class="col-2">
                    <p>{{ direccionPlanta[0] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[1] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[2] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[3] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[4] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[5] }}%</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row tf-blue">
              <div class="col-6">
                <p>TOtal</p>
              </div>
              <div class="col-6">
                <div class="row">
                  <div class="col-2">
                    <p>{{ direccionPlanta[0] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[1] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[2] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[3] }}%</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[4] }}</p>
                  </div>
                  <div class="col-2">
                    <p>{{ direccionPlanta[5] }}%</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!--info personas participantes-->
          <div class="row">
            <div class="col-12">
              <h4 class>Información de las personas que participaron</h4>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <h5 class>Sexo</h5>
              <apexchart
                type="radialBar"
                height="200"
                :options="participantesSexo.chartOptions"
                :series="participantesSexo.series"
              ></apexchart>
            </div>
            <div class="col-6">
              <h5 class>Escolaridad</h5>
              <apexchart
                type="bar"
                height="200"
                :options="participantesEscolaridad.chartOptions"
                :series="participantesEscolaridad.series"
              ></apexchart>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <h5 class>Edad</h5>
              <apexchart
                type="bar"
                height="200"
                :options="participantesEdad.chartOptions"
                :series="participantesEdad.series"
              ></apexchart>
            </div>
            <div class="col-6">
              <h5 class>Antigüedad</h5>
              <apexchart
                type="pie"
                width="301"
                :options="participantesAntiguedad.chartOptions"
                :series="participantesAntiguedad.series"
              ></apexchart>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!-- pagina 5 guia1 seccion 1 -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-lg">
              <div class="cont-page-tit">
                <h1>Guía de Referencia I</h1>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg">
              <div class="cont-page-tit">
                <h3 class="aqua-txt">
                  Identificar a los trabajadores que fueron sujetos a
                  acontecimientos traumáticos severos
                </h3>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <p>
                Es conveniente señalar, que la Guía de referencia I que se
                aplicó, no identifica una enfermedad o transtorno, al aplicar
                esta Guía sólo se puede percibir la necesidad de que un
                trabajador sea canalizado para que reciba la atención médica que
                corresponde. En case de que el trabajador necesite atención,
                ésta se debe prestar a través de la institución de seguridad
                social, médico del centro de trabajo o de la empresa.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <h5>Sección I</h5>
            </div>
            <div class="col-12">
              <h3 class="blue-txt">Acontecimientos Traumáticos Severos</h3>
            </div>
            <div class="col-12">
              <p>
                <span class="strong">En esta sección solamente viene la siguiente pregunta:</span>
                <br />¿Ha presenciado o sufrido alguna vez, durante o con motivo del
                trabajo un acontecimiento como los siguientes?
                <br />
                <span class="strong"></span>
                Total de Respuestas
                {{ respuestasTotalTraumatico }}
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <!--Chart traumatico Severo-->
              <apexchart
                type="bar"
                height="200"
                :options="traumaticoSevero.chartOptions"
                :series="traumaticoSevero.series"
              ></apexchart>
            </div>
            <div class="col-6">
              <p class="bq-blue">
                <span></span>Accidente que tenga como consecuencia la muerte, la
                pérdida de un miembro o una lesión grave
              </p>
              <p class="bq-aqua">
                <span></span>Amenazas
              </p>
              <p class="bq-green">
                <span></span>Asaltos
              </p>
              <p class="bq-purple">
                <span></span>Cualquier otro que ponga en riesgo su vida o salud,
                y/o la de otras personas
              </p>
              <p class="bq-violet">
                <span></span>Ninguna de las anteriores
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <h5>Sección II</h5>
            </div>
            <div class="col-12">
              <h3 class="blue-txt">
                Recuerdos persistentes sobre el acontecimiento (durante el
                último mes)
              </h3>
            </div>
            <div class="col-12">
              <p>
                <span class="strong">
                  En esta sección, las respuestas están por arriba del 60% con
                  “No”, que es favorable a los resultados
                </span>
              </p>
            </div>
          </div>

          <div class="row">
            <div class="col-6">
              <p>
                Durante el último mes ¿ha tenido recuerdos recurrentes sobre el
                acontecimiento que le provocan malestares?
              </p>
              <div class="row">
                <div class="col-10">
                  <!--Chart si no 1 recuerdos-->
                  <apexchart
                    type="bar"
                    height="200"
                    :options="sino1.chartOptions"
                    :series="sino1.series"
                  ></apexchart>
                </div>
                <div class="col-2">
                  <p class="bq-blue">
                    <span></span>No
                  </p>
                  <p class="bq-pink">
                    <span></span>Si
                  </p>
                </div>
              </div>
            </div>

            <div class="col-6">
              <p>
                Durante el último mes ¿ha tenido sueños de caracter recurrente
                sobre el acontecimiento que le producen malestar?
              </p>
              <div class="row">
                <div class="col-10">
                  <!--Chart si no 1 recuerdos-->
                  <apexchart
                    type="bar"
                    height="200"
                    :options="sino2.chartOptions"
                    :series="sino2.series"
                  ></apexchart>
                </div>
                <div class="col-2">
                  <p class="bq-blue">
                    <span></span>No
                  </p>
                  <p class="bq-pink">
                    <span></span>Si
                  </p>
                </div>
              </div>
            </div>
          </div>
  
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--página 7 seccion 3 page -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
            <div class="row">
              <div class="col-12">
                <h5>Sección III</h5>
              </div>
              <div class="col-12">
                <h4 class="blue-txt mt-0">
                  Esfuerzo por evitar circunstancias parecidas o asociadas al
                  acontecimiento (durante el último mes)
                </h4>
              </div>
              <div class="col-12">
                <p>
                  <span class="strong">
                    En esta sección que consta de 7 preguntas, las respuestas
                    están por arriba del 70% con “No” que es favorable a los
                    resultados
                  </span>
                </p>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha disminuido su interés en sus
                  actividades cotidianas?
                </p>
                <!--Chart-->
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino3.chartOptions"
                      :series="sino3.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha notado que tiene dificultad para
                  expresar sus sentimientos?
                </p>
                <!--Chart-->
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino4.chartOptions"
                      :series="sino4.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>
                  Durante el último mes ¿tenido dificultad para recordad alguna
                  parte importante del evento?
                </p>
                <!--Chart-->
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino5.chartOptions"
                      :series="sino5.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha tenido la impresión de que su vida
                  se va a acortar, que va a morir antes que otras personas o que
                  tiene un futuro limitado?
                </p>
                <!--Chart-->
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino6.chartOptions"
                      :series="sino6.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>
                  Durante el último mes ¿se ha esforzado por evitar todo tipo de
                  actividades, lugares o personas que motivan recuerdos del
                  acontecimiento?
                </p>
                <!--Chart-->
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino7.chartOptions"
                      :series="sino7.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha tenido sueños de caracter recurrente
                  sobre el acontecimiento que le producen malestar?
                </p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino8.chartOptions"
                      :series="sino8.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>
                  Durante el último mes ¿se ha sentido usted alejado de los
                  demás?
                </p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="170"
                      :options="sino9.chartOptions"
                      :series="sino9.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--pagina 7 seccion 4 -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div id="tablassino">
            <div class="row">
              <div class="col-12">
                <h5>Sección IV</h5>
              </div>
              <div class="col-12">
                <h4 class="blue-txt">Afectación (durante el último mes)</h4>
              </div>
              <div class="col-12">
                <p>
                  <span class="strong">
                    En esta sección , las respuestas en promedio están por
                    arriba de la media con “No” que es favorable a los
                    resultados
                  </span>
                </p>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha estado nervioso o en constante
                  alerta?
                </p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="200"
                      :options="sino10.chartOptions"
                      :series="sino10.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha estado particularmente irritable o
                  le han dado arranques de coraje?
                </p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="200"
                      :options="sino11.chartOptions"
                      :series="sino11.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>Durante el último mes ¿ha tenido dificultad para concentrarse?</p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="200"
                      :options="sino12.chartOptions"
                      :series="sino12.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
              <div class="col-6">
                <p>
                  Durante el último mes ¿ha tenidousted dificultades para
                  orinar?
                </p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="200"
                      :options="sino13.chartOptions"
                      :series="sino13.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="line-divider"></div>
            <div class="row">
              <div class="col-6">
                <p>
                  Durante el último mes ¿se ha sobresaltado fácilmente por
                  cualquier cosa?
                </p>
                <div class="row">
                  <div class="col-10">
                    <!--Chart si no 1 recuerdos-->
                    <apexchart
                      type="bar"
                      height="200"
                      :options="sino14.chartOptions"
                      :series="sino14.series"
                    ></apexchart>
                  </div>
                  <div class="col-2">
                    <p class="bq-blue">
                      <span></span>No
                    </p>
                    <p class="bq-pink">
                      <span></span>Si
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--página 8 seccion IV afectacion 2 page -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div id="tablassino2">
            <div class="row">
              <div class="col-12">
                <h5>Sección IV</h5>
              </div>
              <div class="col-12">
                <h4 class="blue-txt">Afectación (durante el último mes)</h4>
              </div>
              <div class="col-12">
                <p>
                  <span class="strong">
                    De acuerdo a las condiciones de la NOM-035-STPS se
                    considera que el trabajador requerirá atención clínica en
                    cualquiera de los casos siguientes:
                  </span>
                </p>
              </div>
              <div class="col-12">
                <ol>
                  <li>
                    Cuando responda
                    <strong>“Si”</strong> en
                    <strong>alguna</strong> de las preguntas de la
                    <strong>Sección II Recuerdos persistentes sobre acontecimiento</strong>
                  </li>
                  <li>
                    Cuando responda
                    <strong>“Si”</strong> en
                    <strong>tres o más</strong> de las preguntas de la
                    <strong>
                      Sección III Esfuerzo por evitar circunstancias parecidas o
                      asociadas al acontecimiento
                    </strong>
                  </li>
                  <li>
                    Cuando responda
                    <strong>“Si”</strong> en
                    <strong>dos o más</strong> de las preguntas de la
                    <strong>Sección IV Afectación</strong>
                  </li>
                </ol>
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <div id="table-afectacion">
                  <div class="row th-aqua">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-2">
                          <p>No.</p>
                        </div>
                        <div class="col-4">
                          <p>Colaborador</p>
                        </div>
                        <div class="col-6">
                          <p>Sección</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>1</p>
                    </div>
                    <div class="col-4">
                      <p>{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>2</p>
                    </div>
                    <div class="col-4">
                      <p>{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>3</p>
                    </div>
                    <div class="col-4">
                      <p class="red-txt">{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>4</p>
                    </div>
                    <div class="col-4">
                      <p>{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>5</p>
                    </div>
                    <div class="col-4">
                      <p>{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>6</p>
                    </div>
                    <div class="col-4">
                      <p>{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-2">
                      <p>7</p>
                    </div>
                    <div class="col-4">
                      <p class="red-txt">{{ NombreApellido }}</p>
                    </div>
                    <div class="col-6">
                      <p>{{ referenciaSeccion }}</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row mt-3">
              <div class="col-12">
                <p class="red-txt strong">
                  *2 colaboradores resaltaron en color rojo ya que de acuerdo a
                  las condiciones sus respuestas se posicionaron en 3 de 4
                  secciones de la guía de referencia I.
                </p>
              </div>
            </div>
          </div>
         
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--pagina 9 Guía de referencia II-->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h1>Guía de referencia ii</h1>
              </div>
            </div>
            <div class="col-12">
              <h2>
                Identificar los factores de riesgo psicosocial en los centros de
                trabajo
              </h2>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <p class="strong">Se analizan factores que pueden provocar:</p>
              <ul>
                <li>El ambiente de trabajo y sus condiciones</li>
                <li>Transtornos de ansiedad, no orgánicos del ciclo sueña-vigilia</li>
                <li>
                  Estrés de adaptación, derivado de la naturaleza de las
                  funciona del puesto de trabajo
                </li>
                <li>
                  Tipo de jornada de trabajo y actos de violencia laboral al
                  trabajados, por el tabajo desarrollado Liderazgo
                </li>
              </ul>
            </div>
            <div class="col-6">
              <p class="strong">Criterios para la toma de acciones</p>
              <div class="row">
                <div class="col-6">
                  <p>
                    Las gráficas generales y de dominio corresponden al análisis
                    total de las encuestas y dependiendo el color se deberá
                    determinar y analizar el nivel de riesgo, así como las
                    acciones que se deberán ap¡doptar para el control de los
                    factores de riesgo piscosocial.
                  </p>
                </div>
                <div class="col-6">
                  <ul class="semaforo">
                    <li class="a5">Nivel de riesgo</li>
                    <li class="a4">Muy</li>
                    <li class="a3">Alto</li>
                    <li class="a2">Medio</li>
                    <li class="a1">Bajo</li>
                    <li class="a0">Nulo</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div id="table-3col">
            <div class="row th-aqua2 mt-1">
              <div class="col-12">
                <div class="row">
                  <div class="col-3">
                    <p>Categoría</p>
                  </div>
                  <div class="col-3">
                    <p>Dominio</p>
                  </div>
                  <div class="col-6">
                    <p>Dimensión</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <div class="row purple-txt">
                  <div class="col-3">
                    <p>Categoría</p>
                  </div>
                  <div class="col-3">
                    <p>Dominio</p>
                  </div>
                  <div class="col-6">
                    <div class="row">
                      <div class="col-12">
                        <p>Condiciones peligrosas e inseguras</p>
                      </div>
                      <div class="col-12">
                        <p>Condiciones peligrosas e inseguras</p>
                      </div>
                      <div class="col-12">
                        <p>Trabajos peligrosos</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row aqua-txt">
                  <div class="col-3">
                    <p>Ambiente de trabajo</p>
                  </div>
                  <div class="col-3">
                    <div class="row">
                      <div class="col-12">
                        <p class="hhalf">Carga de trabajo</p>
                      </div>
                      <div class="col-12">
                        <p>Falta de control sobre el trabajo</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-6">
                    <div class="row">
                      <div class="col-12">
                        <p>Cargas cuantitativas</p>
                      </div>
                      <div class="col-12">
                        <p>Ritmos de trabajo acelerados</p>
                      </div>
                      <div class="col-12">
                        <p>Carga mental</p>
                      </div>
                      <div class="col-12">
                        <p>Cargas psicológicas emocionales</p>
                      </div>
                      <div class="col-12">
                        <p>Cargas de alta responsabilidad</p>
                      </div>
                      <div class="col-12">
                        <p>Cargas contradictorias o inconalventes</p>
                      </div>
                      <div class="col-12">
                        <p>Falta de control y autonomía sobre el trabajo</p>
                      </div>
                      <div class="col-12">
                        <p>Limitada o inexistente capacitación</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row blue-txt">
                  <div class="col-3">
                    <p>Organización del tiempo de trabajo</p>
                  </div>
                  <div class="col-3">
                    <div class="row">
                      <div class="col-12">
                        <p>Jornadas de trabajo</p>
                      </div>
                      <div class="col-12">
                        <p>Interferencia en la relación trabajo-familia</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-6">
                    <div class="row">
                      <div class="col-12">
                        <p>Jornadas de trabajo extensas</p>
                      </div>
                      <div class="col-12">
                        <p>Influencia del trabajo fuera del centro laboral</p>
                      </div>
                      <div class="col-12">
                        <p>Influencia de las responsabilidades familiares</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-3">
                    <p>Liderazgo y relaciones en el trabajo</p>
                  </div>
                  <div class="col-3">
                    <div class="row">
                      <div class="col-12">
                        <p class="hthirth">Liderazgo</p>
                      </div>
                      <div class="col-12">
                        <p class="hthirth2">Relaciones en el trabajo</p>
                      </div>
                      <div class="col-12">
                        <p>Violencia</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-6">
                    <div class="row">
                      <div class="col-12">
                        <p>Escasa claridad de funciones</p>
                      </div>
                      <div class="col-12">
                        <p>Características de liderazgo</p>
                      </div>
                      <div class="col-12">
                        <p>Relaciones sociales en el trabajo</p>
                      </div>
                      <div class="col-12">
                        <p>
                          Deficiente relación con los colaboradores que
                          supervisas
                        </p>
                      </div>
                      <div class="col-12 lasty">
                        <p>Violencia familiar</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col text-right">
              <img src="../img/comex-thumb.png" style="width: 60px;" />
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--pagina 10 ambiente de trabajo -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Ambiente de trabajo / Condiciones en el ambiente de trabajo</h4>
                <p class="strong">Gráfica general de la categoría y dominio</p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <apexchart
                type="bar"
                height="199"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
            </div>
            <div class="col-5">
              <h5>{{ resumenAmbienteTrabajo }}</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua3">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>CATEGORÍA</p>
                      </div>
                      <div class="col-3">
                        <p>DOMINIO</p>
                      </div>
                      <div class="col-6">
                        <p>DIMENSION</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-12">
                    <div class="row purple-txt">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <div class="row">
                          <div class="col-12">
                            <p>Condiciones peligrosas e inseguras</p>
                          </div>
                          <div class="col-12">
                            <p>Condiciones peligrosas e inseguras</p>
                          </div>
                          <div class="col-12">
                            <p>Trabajos peligrosos</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <h5>Gráfica de dimensiones</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-3">
              <p> Muestreo de las dimensiones que indican el resultado general del dominio y la categoría</p>
              <p class="bq-pink">
                <span></span>Algunas veces
              </p>
              <p class="bq-aqua">
                <span></span>Casi nunca
              </p>
              <p class="bq-lime">
                <span></span>Casi siempre
              </p>
              <p class="bq-blue">
                <span></span>Siempre
              </p>
              <p class="bq-purple">
                <span></span>Casi siempre
              </p>
            </div>
            <div class="col-3 p-0">
              <apexchart
                type="bar"
                height="200"
                :options="ambiente2.chartOptions"
                :series="ambiente2.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <apexchart
                type="bar"
                height="200"
                :options="ambiente3.chartOptions"
                :series="ambiente3.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <apexchart
                type="bar"
                height="200"
                :options="ambiente4.chartOptions"
                :series="ambiente4.series"
              ></apexchart>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="blue-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
     <!--pagina 10 ambiente de trabajo -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Ambiente de trabajo / Condiciones en el ambiente de trabajo</h4>
                <p class="strong">Gráfica general de la categoría y dominio</p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-6">
              <apexchart
                type="bar"
                height="200"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
            </div>
            <div class="col-5">
              <h5>{{ resumenAmbienteTrabajo }}</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <p>Dimensión</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row aqua-txt">
                        <div class="col-3">
                          <p>Ambiente de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p class="hhalf">Carga de trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Falta de control sobre el trabajo</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Cargas cuantitativas</p>
                            </div>
                            <div class="col-12">
                              <p>Ritmos de trabajo acelerados</p>
                            </div>
                            <div class="col-12">
                              <p>Carga mental</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas psicológicas emocionales</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas de alta responsabilidad</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas contradictorias o inconalventes</p>
                            </div>
                            <div class="col-12">
                              <p>Falta de control y autonomía sobre el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Limitada o inexistente capacitación</p>
                            </div>
                          </div>
                        </div>
                      </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12 mt40">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="orange-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--pagina 11 factores propios de la actividad -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Factores propios de la actividad</h4>
                <p>En esta categoría se analizaron los dominios respecto a la carga de trabajo a la falta del control del trabajo a los que el trabajador se ve sometido a lo largo de la jornada laboral.</p>
                <p>Se realizó una valoración a las dimensiones a las cuales el colaborador siempre tiene de frente al realizar sus actividades y esos resultados generan el resultado total para poder dar un resultado general de la situación actual dentro del centro de trabajo.</p>              
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <p class="strong">Gráfica general de la categoría y dominio</p>
            </div>
            <div class="col-6">
              <apexchart
                type="bar"
                height="200"
                :options="factores2.chartOptions"
                :series="factores2.series"
              ></apexchart>
            </div>
            <div class="col-5">
              <h5>{{ resumenFactoresPropios2 }}</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <p>Dimensión</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row aqua-txt">
                        <div class="col-3">
                          <p>Ambiente de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p class="hhalf">Carga de trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Falta de control sobre el trabajo</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Cargas cuantitativas</p>
                            </div>
                            <div class="col-12">
                              <p>Ritmos de trabajo acelerados</p>
                            </div>
                            <div class="col-12">
                              <p>Carga mental</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas psicológicas emocionales</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas de alta responsabilidad</p>
                            </div>
                            <div class="col-12">
                              <p>Cargas contradictorias o inconalventes</p>
                            </div>
                            <div class="col-12">
                              <p>Falta de control y autonomía sobre el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Limitada o inexistente capacitación</p>
                            </div>
                          </div>
                        </div>
                      </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <h5>Gráfica de dimensiones</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-3">
              <p> Muestreo de las dimensiones que indican el resultado general del dominio y la categoría</p>
              <p class="bq-pink">
                <span></span>Algunas veces
              </p>
              <p class="bq-aqua">
                <span></span>Casi nunca
              </p>
              <p class="bq-lime">
                <span></span>Casi siempre
              </p>
              <p class="bq-blue">
                <span></span>Siempre
              </p>
              <p class="bq-purple">
                <span></span>Casi siempre
              </p>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Carga mental</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente2.chartOptions"
                :series="ambiente2.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Cargas contradictorias o inconsistentes</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente3.chartOptions"
                :series="ambiente3.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Cargas cuantitativas</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente4.chartOptions"
                :series="ambiente4.series"
              ></apexchart>
            </div>
          </div>
          <div class="row">
            <div class="col-3">
              <p></p>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Cargas de alta responsabilidad</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente2.chartOptions"
                :series="ambiente2.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Cargas psicológicas emocionales</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente3.chartOptions"
                :series="ambiente3.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Ritmos de trabajo acelerado</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente4.chartOptions"
                :series="ambiente4.series"
              ></apexchart>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="blue-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
<!--pagina 11 factores propios de la actividad -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Factores propios de la actividad</h4>
                <h5>Dominio: Falta de control sobre el trabajo</h5>              
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <p class="strong">Gráfica general de la categoría y dominio</p>
            </div>
            <div class="col-6">
              <apexchart
                type="bar"
                height="200"
                :options="factores2.chartOptions"
                :series="factores2.series"
              ></apexchart>
            </div>
            <div class="col-5">
              <h5>{{ resumenFactoresPropios3 }}</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <p>Dimensión</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row blue-txt">
                        <div class="col-3">
                          <p>Organización del tiempo de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p>Jornadas de trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Interferencia en la relación trabajo-familia</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Jornadas de trabajo extensas</p>
                            </div>
                            <div class="col-12">
                              <p>Influencia del trabajo fuera del centro laboral</p>
                            </div>
                            <div class="col-12">
                              <p>Influencia de las responsabilidades familiares</p>
                            </div>
                          </div>
                        </div>
                      </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <h5>Gráfica de dimensiones</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-3">
              <p> Muestreo de las dimensiones que indican el resultado general del dominio y la categoría</p>
              <p class="bq-pink">
                <span></span>Algunas veces
              </p>
              <p class="bq-aqua">
                <span></span>Casi nunca
              </p>
              <p class="bq-lime">
                <span></span>Casi siempre
              </p>
              <p class="bq-blue">
                <span></span>Siempre
              </p>
              <p class="bq-purple">
                <span></span>Casi siempre
              </p>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Falta de control y autonomía sobre el trabajo</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente2.chartOptions"
                :series="ambiente2.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Limitada o inexistente capacitación</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente3.chartOptions"
                :series="ambiente3.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Limitada o nula posibilidad de desarrollo</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente4.chartOptions"
                :series="ambiente4.series"
              ></apexchart>
            </div>
          </div>
         
          <div class="row">
            <div class="col-12">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="blue-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
   <div class="html2pdf__page-break" />
     <!--pagina 13 ambiente de trabajo -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Organización del tiempo libre de trabajo</h4>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-4">
              <h5 class="strong text-center">Gráfica general de la categoría y dominio</h5>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
            <div class="col-4">
              <h5 class="strong text-center">Gráfica de dominio: Jornadas de trabajo</h5>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
            <div class="col-4">
              <h5 class="strong text-center">Gráfica de dominio: Interferencia en la relación trabajo familia</h5>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
            <div class="col-5">
              <h5>{{ resumenAmbienteTrabajo }}</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <p>Dimensión</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row aqua-txt">
                        <div class="col-3">
                          <p>Organización del tiempo de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p class="hhalf">Jornadas de trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Interferencia en la relación trabajo-familia</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Jornadas de trabajo extensas</p>
                            </div>
                            <div class="col-12">
                              <p>Influencia del trabajo fuera del centro laboral</p>
                            </div>
                            <div class="col-12">
                              <p>Influencia de las responsabilidades familiares</p>
                            </div>
                          </div>
                        </div>
                      </div>
              </div>
            </div> 
          </div>
          <div class="row">
            <div class="col-12 mt40">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="orange-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
<!--pagina 14 factores propios de la actividad -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Organización del tiempo libre </h4>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <p>Dimensión</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row purple-txt">
                        <div class="col-3">
                          <p>Ambiente de trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p>Jornadas de trabajo</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>JCondiciones peligrosas e inseguras</p>
                            </div>
                            <div class="col-12">
                              <p>Condiciones peligrosas e inseguras</p>
                            </div>
                            <div class="col-12">
                              <p>Trabajos peligrosos</p>
                            </div>
                          </div>
                        </div>
                      </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <h5>Gráfica de dimensiones</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-3">
              <p> Muestreo de las dimensiones que indican el resultado general del dominio y la categoría</p>
              <p class="bq-pink">
                <span></span>Algunas veces
              </p>
              <p class="bq-aqua">
                <span></span>Casi nunca
              </p>
              <p class="bq-lime">
                <span></span>Casi siempre
              </p>
              <p class="bq-blue">
                <span></span>Siempre
              </p>
              <p class="bq-purple">
                <span></span>Casi siempre
              </p>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Influencia de las responabilidades familiares</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente2.chartOptions"
                :series="ambiente2.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Influencia del trabajo fuera del centro laboral</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente3.chartOptions"
                :series="ambiente3.series"
              ></apexchart>
            </div>
            <div class="col-3 p-0">
              <p class="strong text-center">Jornadas de trabajo extensas</p>
              <apexchart
                type="bar"
                height="200"
                :options="ambiente4.chartOptions"
                :series="ambiente4.series"
              ></apexchart>
            </div>
          </div>
         
          <div class="row">
            <div class="col-12">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="blue-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />

     <!--pagina 15 ambiente de trabajo -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h3>Categoría</h3>
                <h4>Liderazgo y relaciones de trabajo</h4>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-4">
              <p class="strong text-center">Gráfica general de la categoría</p>
              <apexchart
                type="bar"
                height="199"
                :options="ambiente8.chartOptions"
                :series="ambiente8.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
            <div class="col-4">
              <p class="strong text-center">Gráfica de dominio: Liderazgo</p>
              <apexchart
                type="bar"
                height="199"
                :options="ambiente7.chartOptions"
                :series="ambiente7.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
            <div class="col-4">
              <p class="strong text-center">Gráfica de dominio: Relaciones en el trabajo</p>
              <apexchart
                type="bar"
                height="199"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
            <div class="col-4">
              <p class="strong text-center">Gráfica de dominio: Violencia</p>
              <apexchart
                type="bar"
                height="199"
                :options="ambiente1.chartOptions"
                :series="ambiente1.series"
              ></apexchart>
              <p>
                Muestreo general de los resultados de los dominios y las dimensiones, presentando un nivel de riesgo “medio”
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <div id="table-3col">
                <div class="row th-aqua">
                  <div class="col-12">
                    <div class="row">
                      <div class="col-3">
                        <p>Categoría</p>
                      </div>
                      <div class="col-3">
                        <p>Dominio</p>
                      </div>
                      <div class="col-6">
                        <p>Dimensión</p>
                      </div>
                    </div>
                  </div>
                </div>
                 <div class="row black-txt">
                        <div class="col-3">
                          <p>Liderazgo y relaciones en el trabajo</p>
                        </div>
                        <div class="col-3">
                          <div class="row">
                            <div class="col-12">
                              <p class="hthirth">Liderazgo</p>
                            </div>
                            <div class="col-12">
                              <p class="hthirth2">Relaciones en el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>Violencia</p>
                            </div>
                          </div>
                        </div>
                        <div class="col-6">
                          <div class="row">
                            <div class="col-12">
                              <p>Escasa claridad de funciones</p>
                            </div>
                            <div class="col-12">
                              <p>Características de liderazgo</p>
                            </div>
                            <div class="col-12">
                              <p>Relaciones sociales en el trabajo</p>
                            </div>
                            <div class="col-12">
                              <p>
                                Deficiente relación con los colaboradores que
                                supervisas
                              </p>
                            </div>
                            <div class="col-12">
                              <p>Violencia familiar</p>
                            </div>
                          </div>
                        </div>
                    </div>
              </div>
            </div> 
          </div>
          <div class="row">
            <div class="col-12 mt40">
              <div id="table-2col">
                  <div class="row th-gray">
                    <div class="col-12">
                      <div class="row">
                        <div class="col-4">
                          <p>Categoría</p>
                        </div>
                        <div class="col-8">
                          <p>Dimensión</p>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-4">
                      <p class="orange-txt">
                        {{ ambienteTrabajoNivel}}
                      </p>
                    </div>
                    <div class="col-8">
                      <p>{{ ambienteTrabajoTip }}</p>
                    </div>
                  </div>
                </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
    <div class="html2pdf__page-break" />
    <!--pagina 16 recomendaciones -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h1 class="blue-txt">recomendaciones</h1>
                <div class="line-divider"></div>
              </div>
            </div>
          </div>
          <div class="row mt20">
            <div class="col-12">
              <p></p>
            </div>
          </div>
          <div class="row mt20">
            <div class="col-12">
               <h1 class="blue-txt">Plan de acción</h1>
               <div class="line-divider"></div>
            </div>
          </div>
          <div class="row mt20">
            <div class="col-12">
              <p></p>
            </div>
          </div>
          
        </div>
      </div>
    </section>
  <div class="html2pdf__page-break" />
    <!-- pagina 17 recomendaciones -->
    <section class="pdf-item">
      <div id="cont-page">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="cont-page-tit">
                <h1 class="">Marco legal</h1>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-12">
              <p>LIVE 13.5 da fe y legalidad de los datos proporcionados del proceso de aplicación de Guías de Referencia I y II de la NOM-035-STPS, hacia la empresa “Nombre de la empresa”. Con estas evidaencias presentadas se cumplen los numerales 5.2, 5.5, 5.7 incisos d), e) y f), 5.8 incisos a), c), 7.2, 7.3, 7.4, 7.7 de acuerdo a las condiciones y la metodología de la NOM-035.stps, las actividades y personas encargadas de llevar a cabo el proceso fueron</p>
            </div>
          </div>
          <div class="row mt20">
            <div class="col-6">
               <h3 class="blue-txt">Contacto con cliente, seguimiento de proyecto e implementación:</h3>
               <div class="line-divider"></div>
               <p></p>
            </div>
            <div class="col-6">
               <h3 class="blue-txt">Analista de información, montaje y entrega de resultados acorde a las condiciones de la NOM-035-STPS</h3>
               <div class="line-divider"></div>
               <p></p>
            </div>
          </div>
          <div class="row mt20">
            <div class="col-6">
               <h3 class="blue-txt">Datos de identificación de empresa que prestó el servicio:</h3>
               <div class="line-divider"></div>
               <p></p>
            </div>
            <div class="col-6">
               <h3 class="blue-txt">Datos de identificación de empresa a quién se dió este servicio:</h3>
               <div class="line-divider"></div>
               <p></p>
            </div>
          </div>
          <div class="row mt20 contacto">
            <div class="col-12">
              <p><a href="https://live135.mx">live135.mx</a> | <a href="mailto:hola@live135.mx">hola@live135.mx</a> | <a href="tel:5535668628" >+52(55) 3566 8628</a></p>
            </div>
          </div>
        </div>
      </div>
    </section>
 <div class="html2pdf__page-break" />
    <!--pagina 18 recomendaciones -->
    <section class="pdf-item">
      <div id="end-page-nom">
      </div>
    </section>
  </section>
</template>

<script>
import boot from "../css/bootstrap.css";
import styles from "../css/front.css";

export default {
  data() {
    return {
      //inicio
      saludoUsuario: "Hola Ro",
      tituloEncuesta: "NOM 035",
      subtituloEncuesta: "Resumen ejecutivo",
      socioEncuesta: "Jhonson & Jhonson",
      fechaHoy: new Date().toLocaleString().slice(0, 4),
      // pagina 3 colaboradores participantes
      colaboradoresTotal: "350 personas",
      personasPartiparon: "430 colaboradores",
      colaboradoresTotal: "350 personas",
      personasPartiparon: "430 colaboradores",
      //grafica demograficos
      message: "",
      demograficos: {
        series: [75], // total
        chartOptions: {
          chart: {
            type: "radialBar",
            toolbar: {
              show: false,
            },
          },
          plotOptions: {
            radialBar: {
              startAngle: -135,
              endAngle: 225,
              hollow: {
                margin: 0,
                size: "70%",
                background: "#fff",
                image: undefined,
                imageOffsetX: 0,
                imageOffsetY: 0,
                position: "front",
                dropShadow: {
                  enabled: false,
                  top: 3,
                  left: 0,
                  blur: 4,
                  opacity: 0.24,
                },
              },
              track: {
                background: "#fff",
                strokeWidth: "100%",
                margin: 0, // margin is in pixels
                dropShadow: {
                  enabled: false,
                  top: -3,
                  left: 0,
                  blur: 4,
                  opacity: 0.35,
                },
              },
              dataLabels: {
                show: true,
                name: {
                  offsetY: -10,
                  show: false,
                  color: "#888",
                  fontSize: "20px",
                },
                value: {
                  formatter: function (val) {
                    return parseInt(val) + "%";
                  },
                  color: "#111",
                  fontSize: "30px",
                  show: true,
                },
              },
            },
          },
          fill: {
            type: "gradient",
            gradient: {
              shade: "dark",
              type: "horizontal",
              shadeIntensity: 0.5,
              gradientToColors: ["#ABE5A1"],
              inverseColors: true,
              opacityFrom: 1,
              opacityTo: 1,
              stops: [0, 100],
            },
          },
          stroke: {
            lineCap: "round",
          },
          labels: ["%"],
        },
      },
      //pagina 3 TABLA participantes areas
      direccionPlanta: [50, 44, 55, 66, 66, 25],
      //pagina 3 GRAFICA participantes sexo
      participantesSexo: {
        series: [76, 67, 11],
        chartOptions: {
          chart: {
            type: "radialBar",
          },
          plotOptions: {
            radialBar: {
              offsetY: 0,
              startAngle: 0,
              endAngle: 270,
              hollow: {
                margin: 5,
                size: "20%",
                background: "transparent",
                image: undefined,
              },
              dataLabels: {
                name: {
                  show: false,
                },
                value: {
                  show: false,
                },
              },
            },
          },
          colors: ["#01C1D1", "#008FFB", "#9E5CD5"],
          labels: ["Femenino", "Masculino", "Transgenero"],
          legend: {
            show: true,
            floating: true,
            fontSize: "12px",
            position: "left",
            offsetX: 0,
            offsetY: 0,
            labels: {
              useSeriesColors: true,
            },
            markers: {
              size: 0,
            },
            formatter: function (seriesName, opts) {
              return (
                seriesName + ":  " + opts.w.globals.series[opts.seriesIndex]
              );
            },
            itemMargin: {
              vertical: 3,
            },
          },
          responsive: [
            {
              breakpoint: 480,
              options: {
                legend: {
                  show: false,
                },
              },
            },
          ],
        },
      },
      //pagina 3 GRAFICA participantes escolaridad
      participantesEscolaridad: {
        series: [
          {
            data: [400, 430, 448, 470, 540, 580, 690, 1100],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
          },
          plotOptions: {
            bar: {
              horizontal: true,
            },
          },
          colors: ["#01C1D1"],
          dataLabels: {
            enabled: false,
          },
          xaxis: {
            categories: [
              "Sin respuesta",
              "Primaria",
              "Secundaria",
              "Bachillerato/Preparatoria",
              "Carrera profesional",
              "Especialidad/Diplomado",
              "Doctorado",
              "Otro",
            ],
          },
        },
      },
      //pagina 3 GRAFICA participantes edad
      participantesEdad: {
        series: [
          {
            data: [21, 22, 10, 28, 16, 21, 13, 30],
          },
        ],
        chartOptions: {
          chart: {
            height: 200,
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          plotOptions: {
            bar: {
              columnWidth: "60%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          colors: [
            "#008FFB",
            "#01C1D1",
            "#00A0B3",
            "#4E78C3",
            "#0063BE",
            "#0B96BB",
            "#646EC0",
            "#9E5CD5",
          ],
          xaxis: {
            categories: [
              ["Sin respuesta"],
              ["18 a 22 años"],
              ["23 a 29 años"],
              ["30 a 35 años"],
              ["36 a 40 años"],
              ["41 a 50 años"],
              ["50 a 60 años"],
              ["60 +"],
            ],
            labels: {
              style: {
                fontSize: "8px",
              },
            },
          },
        },
      },
      //pagina 3 Grafica participantes antiguedad
      participantesAntiguedad: {
        series: [44, 55, 13, 43, 22, 13, 43, 22],
        chartOptions: {
          chart: {
            type: "pie",
          },
          legend: {
            fontSize: "6px",
          },
          plotOptions: {
            pie: {
              dataLabels: {
                offset: -5,
              },
            },
          },
          colors: [
            "#008FFB",
            "#01C1D1",
            "#00A0B3",
            "#4E78C3",
            "#0063BE",
            "#0B96BB",
            "#646EC0",
            "#9E5CD5",
          ],
          labels: [
            "Sin respuesta",
            "18 a 22 años",
            "23 a 29 años",
            "30 a 35 años",
            "36 a 40 años",
            "41 a 50 años",
            "50 a 60 años",
            "60 +",
          ],
        },
      },
      // Pagina 4 RESPUESTA total traumatico severo
      respuestasTotalTraumatico: "120",
      // Pagina 4 GRAFICA guia referencia 1 acontecimientos traumaticos severos
      traumaticoSevero: {
        series: [
          {
            data: [21, 22, 10, 28, 16],
          },
        ],
        chartOptions: {
          chart: {
            height: 350,
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#01C1D1", "#00A0B3", "#646EC0", "#9E5CD5"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"], ["40%"], ["90%"], ["89%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      //pagina 4 GRAFICA si no preguntas 1
      sino1: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      //pagina 4 GRAFICA si no preguntas 2
      sino2: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      //pagina 4 GRAFICA si no preguntas 3
      sino3: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino4: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino5: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino6: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino7: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino8: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino9: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino10: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino11: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino12: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino13: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      sino14: {
        series: [
          {
            data: [21, 82],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#c574b1"],
          plotOptions: {
            bar: {
              columnWidth: "99%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: false,
          },
          xaxis: {
            //labels para las barras
            categories: [["55%"], ["20%"]],
            labels: {
              style: {
                fontSize: "12px",
              },
            },
          },
        },
      },
      //tabla nombre y referencia
      NombreApellido: "Rodrigo Suárez",
      referenciaSeccion: "Referencia de la sección",
      ambiente1: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#01C1D1", "#FFC700", "#EB8145", "#E0285F"],
          plotOptions: {
            bar: {
              columnWidth: "79%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: true,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["Muy bajo"],
              ["Bajo"],
              ["Medio"],
              ["Alto"],
              ["Muy alto"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      ambiente7: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#01C1D1", "#FFC700", "#EB8145", "#E0285F"],
          plotOptions: {
            bar: {
              columnWidth: "79%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: true,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["Muy bajo"],
              ["Bajo"],
              ["Medio"],
              ["Alto"],
              ["Muy alto"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      ambiente8: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#01C1D1", "#FFC700", "#EB8145", "#E0285F"],
          plotOptions: {
            bar: {
              columnWidth: "79%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: true,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["Muy bajo"],
              ["Bajo"],
              ["Medio"],
              ["Alto"],
              ["Muy alto"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      resumenAmbienteTrabajo:
        "El nivel de riesgo en el ambiente laboral y sus condiciones se presenta muy bajo",
        ambiente2: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#c574b1", "#01C1D1", "#6ca36c", "#2E9DF3", "#646EC0"],
          plotOptions: {
            bar: {
              columnWidth: "95%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["20%"],
              ["40%"],
              ["10%"],
              ["70%"],
              ["27%"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      ambiente3: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#c574b1", "#01C1D1", "#6ca36c", "#2E9DF3", "#646EC0"],
          plotOptions: {
            bar: {
              columnWidth: "95%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["20%"],
              ["40%"],
              ["10%"],
              ["70%"],
              ["27%"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      ambiente4: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#c574b1", "#01C1D1", "#6ca36c", "#2E9DF3", "#646EC0"],
          plotOptions: {
            bar: {
              columnWidth: "95%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["20%"],
              ["40%"],
              ["10%"],
              ["70%"],
              ["27%"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      ambiente5: {
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#c574b1", "#01C1D1", "#6ca36c", "#2E9DF3", "#646EC0"],
          plotOptions: {
            bar: {
              columnWidth: "95%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: false,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["20%"],
              ["40%"],
              ["10%"],
              ["70%"],
              ["27%"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
      },
      // ambiente trabajo nivel
      ambienteTrabajoNivel :'Nulo',
      // ambiente trabajo tip
      ambienteTrabajoTip : 'El riesgo es nulo por lo que no se requiere medidas o acciones adicionales por el momento',
      // page 11 factores 2
      factores2 :{
        series: [
          {
            data: [21, 82, 34, 12, 44],
          },
        ],
        chartOptions: {
          chart: {
            type: "bar",
            toolbar: {
              show: false,
            },
            events: {
              click: function (chart, w, e) {
                // console.log(chart, w, e)
              },
            },
          },
          colors: ["#008FFB", "#01C1D1", "#FFC700", "#EB8145", "#E0285F"],
          plotOptions: {
            bar: {
              columnWidth: "79%",
              distributed: true,
            },
          },
          dataLabels: {
            enabled: true,
          },
          legend: {
            show: true,
          },
          xaxis: {
            //labels para las barras
            categories: [
              ["Muy bajo"],
              ["Bajo"],
              ["Medio"],
              ["Alto"],
              ["Muy alto"],
            ],
            labels: {
              style: {
                fontSize: "10px",
              },
            },
          },
        },
    
      },
      resumenFactoresPropios2 : 
        'El nivel de riesgo en el ambiente se presenta muy alto referente a la carga de trabajo',
      resumenFactoresPropios3 :
       'El nivel de riesgo en la carga de trabajo se presenta “medio” referente a la falta de control sobre el trabajo, este resultado se promedia de las respuestas de las dimensiones',
      resumenFactoresPropios4 :
       'El nivel de riesgo en la carga de trabajo se presenta “medio” referente a la falta de control sobre el trabajo, este resultado se promedia de las respuestas de las dimensiones',
      //fin charts
    };
  },

  mounted() {
    this.$nextTick(() => {
      setTimeout(() => {
        this.$emit("domRendered");
      }, 1000);
    });
  },
};
</script>

<style lang="scss" scoped>
.pdf-content {
  width: 100%;
  background: #fff;

  .report-info {
    display: flex;
    padding: 20px;
    padding-bottom: 0px;

    .image-container {
      width: 75px;
      height: 75px;
      border-radius: 50%;
      overflow: hidden;
      position: relative;
      margin-right: 25px;
      border: 1px solid #dadada;

      .user-image {
        height: 100%;
        min-width: 100%;
        margin-left: 50%;
        transform: translateX(-50%);
      }
    }

    .user-details {
      display: flex;
      flex-direction: column;
      flex-shrink: 0;

      .user-name {
        margin-bottom: 10px;
        flex-shrink: 0;
      }

      .detail-container {
        font-size: 13px;
        flex-shrink: 0;

        &:not(:last-child) {
          margin-bottom: 10px;
        }

        .detail-label {
          font-weight: 600;
          margin-right: 5px;
          font-size: 13px;
        }
      }
    }
  }

  .chart-container {
    width: 100%;
    height: 320px;
    padding: 20px;
    pointer-events: none;

    &:not(:last-child) {
      margin-bottom: 15px;
    }
  }
}
</style>
