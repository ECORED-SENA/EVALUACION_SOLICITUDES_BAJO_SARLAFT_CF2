<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Normatividad
    .row.mt-5
      .col-10.offset-1
        figure.px-4
          img(src="@/assets/template/tema-1-1.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-11
        p La normatividad es el conjunto que contiene leyes que dirigen conductas y procedimientos de una entidad u organización privada o pública, esto a su vez indica en qué aspecto están reglamentadas las empresas. La normatividad suele plasmarse formal o informalmente por escrito y allí se rigen todos los derechos y obligaciones que tiene la institución.
        p.mt-3 Existen diferentes tipos de normatividad, estos son: 
      .col-1.px-0
        figure
          img(src="@/assets/template/tema-1-3.svg", alt="Texto que describa la imagen").floating
    .row.mt-5.px-4
      .col-6.position-relative.px-0(@mouseover="mostrarIndicador = false")
        .indicador--click(v-if="mostrarIndicador")
        figure.px-2
          img(src="@/assets/template/tema-1-2-1.png", alt="Texto que describa la imagen")
        .row.image-cover.mx-0
          figure.px-2
            img(src="@/assets/template/tema-1-2-2.svg", alt="Texto que describa la imagen")
          .col-12(style="margin-top: -65%").px-4
            .row.text-center
              .col-12
                figure
                  img(src="@/assets/template/tema-1-5.svg", alt="Imagen descriptiva").w-10.margin-0-auto
            .h4.text-center.mt-4 Normatividad Jurídica
            p.mt-3.ml-5 En estas se incluyen las siguientes:
            ul.lista-ul.ml-5.pt-3
              li 
                i.fas.fa-angle-right.secundario
                | Normatividad Ambiental
              li 
                i.fas.fa-angle-right.secundario
                | Normatividad Educacional
              li 
                i.fas.fa-angle-right.secundario
                | Normatividad Informática
              li 
                i.fas.fa-angle-right.secundario
                | Normatividad Tributaria
              li 
                i.fas.fa-angle-right.secundario
                | Normatividad Laboral
      .col-6.position-relative.px-0
        figure.px-2(@mouseover="mostrarIndicador = false")
          .indicador--click(v-if="mostrarIndicador")
          img(src="@/assets/template/tema-1-4-1.png", alt="Texto que describa la imagen")
        .row.image-cover.mx-0
          figure.px-2
            img(src="@/assets/template/tema-1-4-2.svg", alt="Texto que describa la imagen")
          .col-12(style="margin-top: -65%").px-4
            .row.text-center
              .col-12
                figure
                  img(src="@/assets/template/tema-1-6.svg", alt="Imagen descriptiva").w-10.margin-0-auto
            .h4.text-center.mt-4 Normatividad No Jurídica
            p.mt-3.ml-5 En estas se incluyen las siguientes:
            ul.lista-ul.ml-5.pt-3
              li 
                i.fas.fa-angle-right.secundario
                | Moral
              li 
                i.fas.fa-angle-right.secundario
                | Religiosa
              li 
                i.fas.fa-angle-right.secundario
                | Técnica
              li 
                i.fas.fa-angle-right.secundario
                | Social
    separador.mt-3

    p Las normativas tienen como función:
    p.mt-2 Regular todas las actividades cotidianas de las personas como por ejemplo regular los regímenes matrimoniales, el derecho sucesorio, los delitos y sus penas, entre otros.

    .titulo-segundo.mt-5
      #t_1_1.h2 1.1  Normatividad vigente - SARLAFT
    .row.mt-5
      .col-8.offset-2
        .bloque-texto-a.color-primario.p-4.p-md-4.mb-5 
          .row.m-0.align-items-center.justify-content-between.zoom-in
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p Las normas contra el lavado de activos y la financiación del terrorismo se han actualizado para todas las entidades de la Superintendencia Financiera estableciendo los lineamientos que las organizaciones deben establecer y así obtener un enfoque basado en riesgos.
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src="@/assets/template/tema-1-7.png", alt="Logo de la normatividad")
    p.mt-5 El Sistema de Administración del Riesgo de eventos, de Lavado de Activos y Financiación del Terrorismo, está fundamentado en los contenidos normativos de carácter general y especial previstos en la constitución, la ley, decretos y actos administrativos emitidos por los entes de vigilancia y control. (COMPLIANCE - Sistema de Información, 2018)
    .row.mt-4
        .col-10.offset-1.mt-5
          .titulo-sexto.color-acento-contenido
            h5.text-small Tabla 1
            p.text-small Aspectos legales
    .row.mt-5
      .col-8.offset-2
        .tabla-a.color-acento-contenido.mb-5 
          table.text-center
            thead.bg-secundario
              tr
                th ASPECTOS LEGALES
            tbody.text-small
              tr
                td.py-3 Artículos 6, 123, 333 inciso 5 y 335 de la Constitución Política de Colombia.
              tr
                td.py-3 Ley 365 de Febrero 21 de 1997.
              tr
                td.py-3 Ley 526 de Agosto 12 de 1999.
              tr
                td.py-3 Ley 1581 de 2011.
              tr
                td.py-3 Código Penal Artículos: 29, 30, 65, 319, 320, 321, 326, 327, 365, 376, 377, 382 y 412.
              tr
                td.py-3 En general aquellas enunciadas en el Código de Procedimiento Penal.
              tr
                td.py-3 Ley 1126 de 2006 sobre Financiación del Terrorismo, modificó la Ley 526 de 1999.
              tr
                td.py-3.px-5 Decreto 1537 de 2001. “Por el cual se reglamenta parcialmente la Ley 87 de 1993 en cuanto a elementos técnicos y administrativos que fortalezcan el Sistema de Control Interno en las entidades y organismos del Estado”.
              tr
                td.py-3.px-5 Decreto 4110 de 2004. “Por el cual se reglamenta la Ley 872 de 2003 y se adopta la Norma Técnica de Calidad en la Gestión Pública”.
              tr
                td.py-3.px-5 Decreto 1599 de 2005. “Por medio del cual se adopta el Modelo Estándar de Control Interno para el Estado colombiano”. MECI 1000:2005.
              tr
                td.py-3.px-5 Norma Técnica Colombiana NTC 5254 de 2006 “Gestión de Riesgo”.
              tr
                td.py-3.px-5 Guía Administración del Riesgo del DAFP 2006.
              tr
                td.py-3.px-5 Guía de Diseño de Implementación del Sistema de Gestión de la Calidad bajo la Norma Técnica de Calidad para la Gestión Pública NTCGP 1000:2004 de 2007 Numeral 3.
              tr
                td.py-3.px-5 La ley 1249 de 2008, decretada por el Congreso y sancionada por el presidente de la república faculta a los Administradores Policiales a realizar asesorías, investigación y consultorías en procesos y procedimientos de seguridad, teniendo el aval del Gobierno Nacional para evaluar, coordinar, siendo este un procedimiento que se ajusta al marco legal.
    p.mt-5 La anterior normativa vigente puede ser consultada en:
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center.py-3
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-1-8.svg").w-50.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 NORMATIVA VIGENTE
                  p.text-small   
                .col-sm-auto
                  a.boton.color-acento-contenido(href="https://www.uiaf.gov.co/sistema_nacional_ala_cft/normatividad_sistema_documentos_28" target="_blank")
                    span.text-sistema Enlace
                    i.fas.fa-link.text-sistema
    separador.mt-3

    .titulo-segundo.mt-5
      #t_1_2.h2 1.2  SARLAFT 4.0

    .row.mt-5
      .col-1.px-0
        figure
          img(src="@/assets/template/tema-1-9.svg", alt="Texto que describa la imagen").floating

      .col-11.align-self-center
        p Todas las entidades deben obtener políticas y procedimientos que faciliten la identificación, verificación, y confirmación de la identidad del posible cliente; la Superintendencia Financiera ha presentado el SARLAFT 4.0 que sería la versión más actualizada en donde se tuvo en cuenta la recomendación del Grupo de Acción Financiera Internacional – GAFI. Se hizo la expedición de la Circular Externa 027 del 2020 donde se establecen los puntos que se deben fortalecer: 
    .row.mt-5
      .col-6
        .cajon.color-primario
          .row.p-4
            ul.lista-ul.ml-2.pt-3
              li 
                i.fas.fa-angle-right.acento-contenido
                | La debida diligencia del beneficiario final.
              li 
                i.fas.fa-angle-right.acento-contenido
                | La aplicación de contramedidas en países de mayor riesgo.  
              li 
                i.fas.fa-angle-right.acento-contenido
                | El requerimiento de información en las transferencias Internacionales y Nacionales.
              li 
                i.fas.fa-angle-right.acento-contenido
                | La debida diligencia en personas expuestas políticamente y la supervisión en la corresponsalía transnacional.

        p.mt-5 La Superintendencia Financiera debido a muchos factores decidió hacerle ciertos cambios al Sistema de Administración de Riesgos de Lavado de Activos y Financiación del Terrorismo – SARLAFT, y así dio a conocer la Circular Externa 027 la cual fue modificada, en este nuevo sistema se establece los lineamientos que las entidades vigiladas deberán proceder y darlo a conocer al cliente basándose en un enfoque de riesgos, además deberán solicitar la información oportuna analizándolo cuidadosa y oportunamente.  
      .col-6
        figure
          img(src="@/assets/template/tema-1-10.png", alt="Imagen descriptiva")      
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center.py-3
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-1-11.svg").w-50.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 CIRCULAR EXTERNA 027 de 2020
                  p.text-small Para conocer a fondo la circular, puede visualizar el documento para facilitar su consulta.
                  p.font-weight-bold Anexo 1. Circular Externa 027 de 2020 
                .col-sm-auto
                  a.boton.color-acento-contenido(:href="obtenerLink('/downloads/Anexo_1_Circular_027_de_2.020.pdf')" target="_blank")
                    span.text-sistema Descargar
                    i.fas.fa-file-download.text-sistema
    p.mt-5 En la actual versión de SARLAFT, se puede apreciar:
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mt-5.rounded-20.bg-amarillo-claro.p-5.zoom-in
      .col-5
        p Datos que se deben obtener en la Actividad Económica:
        .cajon.color-acento-contenido.text-center.mt-3.bg-verde-60
          .h4.mb-0.py-4 CARACTERÍSTICAS 
        .cajon.color-acento-contenido.text-center.mt-3.bg-verde-40
          .h4.mb-0.py-4 MONTOS
        .cajon.color-acento-contenido.text-center.mt-3.bg-verde-20
          .h4.mb-0.py-4 PROCEDENCIA DE INGRESOS Y EGRESOS
        .cajon.color-acento-contenido.text-center.mt-3.bg-verde-10
          .h4.mb-0.py-4 DOMICILIO
        p.mt-3 Datos que se deben obtener para las #[strong  Personas Jurídicas]: 
        p Los datos de identificación del representante legal y los miembros de la Junta Directiva.
      .col-7.px-5
        figure
          img(src="@/assets/template/tema-1-12.svg", alt="Imagen descriptiva")
    p.mt-5 Dentro de la normatividad del SARLAFT se incluyen las siguientes leyes, decretos y resoluciones que apoyan a la ejecución de este sistema: 
    .row.mt-5
      .col-10.offset-1.px-0
        .cajon.color-acento-contenido.mt-3.bg-verde-40.p-4
          .h4.mb-0 Ley 1941 de 2018:
          p.mt-1 Por medio de la Ley 1941 del 18 de diciembre de 2018, se prorrogó la Ley 418 de 1997, la cual consagró los instrumentos para la búsqueda de la convivencia, la eficacia de la justicia y se creó el Centro de Coordinación Contra las Finanzas de Organizaciones de Delito Transnacional y Terrorismo, del cual la UIAF ejerce la Secretaría Técnica y tiene como función, fortalecer los canales de comunicación, intercambio y análisis conjunto de información, con el propósito de generar sinergia y sincronización tanto estratégica como de ejecución entre los organismos que llevan a cabo actividades de inteligencia y las autoridades judiciales.
    .row.scroll-x-tabla
      .col-10.offset-1
        .row.justify-content-around.align-items-center.py-3.bg-secundario
          .col-3.col-sm-2.col-lg-2.offset-5.d-none-mov
            img(src="@/assets/template/tema-1-13.svg").w-50.margin-0-auto
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0.align-self-center
                h3.mb-0 Ver Ley 1941 de 2018
              .col-sm-auto
                a.boton.color-acento-contenido(href="https://www.uiaf.gov.co/sistema_nacional_ala_cft/normatividad_sistema/leyes/ley_1941_2018" target="_blank")
                  span.text-sistema Enlace
                  i.fas.fa-link.text-sistema
    .row.mt-4
      .col-10.offset-1.px-0
        .cajon.color-acento-contenido.mt-3.bg-verde-40.p-4
          .h4.mb-0 Ley 1908 de 2018:
          p.mt-1 Por medio de la cual se fortalece la investigación y judicialización de organizaciones criminales, se adoptan medidas para su sujeción a la justicia y se dictan otras disposiciones.
    .row
      .col-10.offset-1
        .row.justify-content-around.align-items-center.py-3.bg-secundario
          .col-3.col-sm-2.col-lg-2.offset-5.d-none-mov
            img(src="@/assets/template/tema-1-13.svg").w-50.margin-0-auto
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0.align-self-center
                h3.mb-0 Ley 1908 de 2018
              .col-sm-auto
                a.boton.color-acento-contenido(href="https://www.uiaf.gov.co/sistema_nacional_ala_cft/normatividad_sistema_documentos_28/leyes/ley_1908_2018" target="_blank")
                  span.text-sistema Enlace
                  i.fas.fa-link.text-sistema
    .row.mt-4
      .col-10.offset-1.px-0
        .cajon.color-acento-contenido.mt-3.bg-verde-20.p-4
          .h4.mb-0 Ley 1762 de 2015:
          p.mt-1 Por medio de la cual se adoptan instrumentos para prevenir, controlar y sancionar el contrabando, el lavado de activos y la evasión fiscal.
    .row
      .col-10.offset-1
        .row.justify-content-around.align-items-center.py-3.bg-secundario
          .col-3.col-sm-2.col-lg-2.offset-5.d-none-mov
            img(src="@/assets/template/tema-1-13.svg").w-50.margin-0-auto
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0.align-self-center
                h3.mb-0 Ver Ley 1762 de 2015:
              .col-sm-auto
                a.boton.color-acento-contenido(href="https://www.uiaf.gov.co/sistema_nacional_ala_cft/normatividad_sistema/leyes/ley_1762_2015" target="_blank")
                  span.text-sistema Enlace
                  i.fas.fa-link.text-sistema
    p.mt-5 Para ampliar mayor información, sobre normativa vigente relacionada con SARLAFT, esta puede ser consultada en el siguiente sitio web:
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center.py-3
            .col-3.col-sm-2.col-lg-3
              img(src="@/assets/template/tema-1-14.svg").w-75.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Decretos
                  p.text-small En el presente enlace, encontrará los decretos vigentes, relacionados con el lavado de activos y financiación del terrorismo, dispuesto por la Unidad de Información y Análisis Financiero, para su consulta.
                  h3.mt-3 Resoluciones
                  p.text-small En el presente enlace, encontrará las resoluciones vigentes, relacionadas con el lavado de activos y financiación del terrorismo, dispuesto por la Unidad de Información y Análisis Financiero, para su consulta. 
                .col-sm-auto.pr-5
                  .row
                    a.boton.color-acento-contenido(href="https://www.uiaf.gov.co/sistema_nacional_ala_cft/normatividad_sistema_documentos_28/decretos" target="_blank")
                      span.text-sistema Enlace
                      i.fas.fa-link.text-sistema
                  .row.mt-3
                    a.boton.color-acento-contenido(href="https://www.uiaf.gov.co/sistema_nacional_ala_cft/normatividad_sistema_documentos_28/resoluciones" target="_blank").mt-4 
                      span.text-sistema Enlace
                      i.fas.fa-link.text-sistema
    separador.mt-3

    .titulo-segundo.mt-5
      #t_1_3.h2 1.3  Otros sistemas de prevención
    .row.mt-5
      .col-10.offset-1
        figure
          img(src="@/assets/template/tema-1-15.png", alt="Imagen descriptiva")
    .row.mt-5
      .col-8.offset-2
        .bloque-texto-a.color-primario.p-4.p-md-4.mb-5 
          .row.m-0.align-items-center.justify-content-between.zoom-in
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p Dentro de la normatividad vigente existen otros sistemas que complementan al Sistema de Administración de Riesgo de Lavado de Activos y Financiación del Terrorismo los cuales son los siguientes: 
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src="@/assets/template/tema-1-16.svg", alt="Logo de la normatividad").w-75.margin-0-auto
    .row.justify-content-center(data-aos="fade-down").mt-4
      .col-lg-4
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.rounded-15.box-shadow.px-0
            figure
              img(src="@/assets/template/tema-1-17.png", alt="Texto que describa la imagen")
            .text.p-lg-3.p-4
              .row.text-center.px-1.pt-1
                figure
                  img(src="@/assets/template/tema-1-20.svg", alt="Texto que describa la imagen").w-25.margin-0-auto
                .h4.small-text SIPLAFT
                p.mt-5.small-text Sistema Integral para la Prevención y Control del Lavado de Activos y Financiación del Terrorismo.
                
      .col-lg-4
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.rounded-15.box-shadow.px-0
            figure
              img(src="@/assets/template/tema-1-18.png", alt="Texto que describa la imagen")
            .text.p-lg-3.p-4
              .row.text-center.px-1.pt-1
                figure
                  img(src="@/assets/template/tema-1-21.svg", alt="Texto que describa la imagen").w-25.margin-0-auto
                .h4.small-text SAGRLAFT
                p.mt-5.small-text  Sistema de Autocontrol y Gestión del Riesgo del Lavado de Activos y Financiación del Terrorismo.
      .col-lg-4
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.rounded-15.box-shadow.px-0
            figure
              img(src="@/assets/template/tema-1-19.png", alt="Texto que describa la imagen")
            .text.p-lg-3.p-4
              .row.text-center.px-1.pt-1
                figure
                  img(src="@/assets/template/tema-1-22.svg", alt="Texto que describa la imagen").w-25.margin-0-auto
                .h4.small-text UIAF
                p.mt-5.small-text Unidad de Información y Análisis Financiero.
    p.mt-5 A estas entidades pertenecen distintos sectores en donde se aplican los diferentes sistemas expuestos, a continuación, se presenta la siguiente tabla:
    .row.mt-3
      .col-10.offset-1.mt-5
        .titulo-sexto.color-acento-contenido
          h5.text-small Tabla 2
          p.text-small  Sectores y sistemas a aplicar
    .row.mt-5
      .col-10.offset-1
        .tabla-a.color-acento-contenido.mb-5 
          table
            caption.mt-3 Nota. https://www.uiaf.gov.co/sala_prensa/publicaciones/guia_normatividad_ala_cf
            thead.bg-secundario.text-center
              tr
                th SECTOR
                th SISTEMA A APLICAR
            tbody.text-small
              tr
                td.py-3.pl-5 Sector vigilado por Coldeportes.
                td.py-3.font-weight-bold.text-center SIPLAFT 
              tr
                td.py-3.pl-5  Sector vigilado por la Superintendencia de Notariado y Registro.
                td.py-3.font-weight-bold.text-center SIPLAFT - FPADM
              tr
                td.py-3.pl-5 Sector vigilado por el Consejo Nacional de Juegos de Suerte y Azar - CNJSA.
                td.py-3.font-weight-bold.text-center SIPLAFT
              tr
                td.py-3.pl-5  Sector vigilado por Coljuegos
                td.py-3.font-weight-bold.text-center SIPLAFT
              tr
                td.py-3.pl-5 Sector vigilado por la Superintendencia de Sociedades - Oro
                td.py-3.font-weight-bold.text-center UIAF - SAGRLAFT
              tr
                td.py-3.pl-5 Sector vigilado por la Superintendencia de Puertos y Transportes
                td.py-3.font-weight-bold.text-center SIPLAFT
              tr
                td.py-3.pl-5 Sector vigilado por la Junta Central de Contadores – Revisores Fiscales
                td.py-3.font-weight-bold.text-center UIAF
              tr
                td.py-3.pl-5 Sector vigilado por la Superintendencia de Sociedades – Concesionarios de Vehículos Automotores nuevos y Usados
                td.py-3.font-weight-bold.text-center UIAF - SAGRLAFT
              tr
                td.py-3.pl-5 Sector vigilado por la Dirección de Impuestos y Aduanas Nacionales – DIAN – Operadores de Comercio Exterior
                td.py-3.font-weight-bold.text-center SARLAFT - FPADM






</template>

<script>
import PestanasA from '../components/PestanasA'
export default {
  name: 'Tema1',
  components: {
    PestanasA,
  },
  data: () => ({
    mostrarIndicador: true,
    indicadorTarjetaFlip: true,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>
