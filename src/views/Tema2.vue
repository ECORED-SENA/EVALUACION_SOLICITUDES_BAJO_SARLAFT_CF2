<template lang="pug">
.curso-main-container.pb-3(style="overflow: hidden")
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(style="overflow: hidden")
    
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Políticas
    .row.mt-5
      .col-10.offset-1
        figure
          img(src="@/assets/template/tema-2-1.png", alt="Imagen descriptiva")
    .row.mt-4
      .col-3.px-0.align-self-center
        figure
          img(src="@/assets/template/tema-2-2.png", alt="Imagen descriptiva")
      .col-8.px-0
        p El Sistema Financiero es utilizado como un mecanismo para ocultar los bienes y servicios que tengan orígenes ilícitos o por consiguiente orígenes legales, que se puedan utilizar para actos terroristas, por este motivo la Superintendencia Financiera de Colombia promueve la cultura de Administración de Riesgos entre diferentes organizaciones las cuales son sometidas a inspección y vigilancia esto se realiza a través de la Administración de Riesgos de Lavado de Activos y Financiación del Terrorismo – SARLAFT. 
    .bloque-texto-a.color-primario.p-4.p-md-4.mt-5 
      .row.m-0.align-items-center.justify-content-between.zoom-in
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p En este sistema existen unas políticas establecidas que deben regir las diferentes entidades vigiladas como:
            p.mt-3 FIDUCOLDEX - Fiduciaria Colombiana de Comercio Exterior S.A, la cual es una entidad que apoya el sector empresarial en el crecimiento de sus negocios y contribuyendo al negocio del país. Es así como FIDUCOLDEX adoptó las siguientes políticas para brindar un adecuado manejo del SARLAFT en las diferentes etapas y elementos de este sistema.
        .col-lg-4.mb-4.mb-lg-0
          figure
            img(src="@/assets/template/tema-2-3.png", alt="Logo de la normatividad") 
    p.mt-5 A continuación, algunas políticas vigentes:
    LineaTiempoD.color-secundario.mt-5
      .row(numero="1" titulo="Políticas para la etapa de identificación")
        .col-4
          figure
            img(src="@/assets/template/tema-2-4.png", alt="Imagen descriptiva")
        .col-8
          p En esta etapa de identificación de riesgos se debe surtir y buscar factores que puedan afectar a la entidad, es decir, se debe buscar previamente el lanzamiento de cualquier producto o modificaciones que quieran ser realizadas, estar pendiente a las aperturas de nuevas operaciones o en los canales de distribución. Cabe aclarar que productos que sean desarrollados en la Fiduciaria no es necesario realizar la debida identificación al ingresar a nuevas jurisdicciones.
          p.mt-2 Cuando existan productos que involucre operaciones comprometiendo a fondo actividades relacionadas con el Lavado de Activos y Financiación del Terrorismo, este producto debe ser analizado inmediatamente por el ente de control.

      .row(numero="2" titulo="Políticas para la etapa de monitoreo")
        .col-4
          figure
            img(src="@/assets/template/tema-2-5.png", alt="Imagen descriptiva")
        .col-8
          p En esta etapa es importante la realización de las siguientes actividades:
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Mantener un monitoreo constante en todos los factores de riesgo encontrados apoyándose en las herramientas tecnológicas que permiten verificar los clientes en las listas restrictivas; además, debe detectar las operaciones que hayan sido realizadas dentro de los parámetros oficiales de cumplimiento en las transacciones usuales.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Establecer por parte del oficial encargado los controles más estrictos que adviertan el perfil del riesgo de LA/FT si supera los niveles de tolerancia establecidos por la Fiduciaria.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Establecer los indicadores descriptivos y prospectivos que evidencian las potenciales fuentes de riesgos.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Asegurar que los riesgos residuales se encuentren en los niveles de aceptación que son establecidos por la entidad.
            li 
              i.fas.fa-angle-right.acento-contenido
              | La fiduciaria se abstendrá de tener relación con clientes o contrapartes domiciliados en países no cooperantes o sancionados, según el FATF/GAFI.
      .row(numero="3" titulo="Política para etapa de control")
        .col-4
          figure
            img(src="@/assets/template/tema-2-6.png", alt="Imagen descriptiva")
        .col-8
          p Para esta etapa es importante realizar los reportes, para dar cumplimiento con el control permanente de la administración del riesgo como:
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Se debe reportar cualquier hecho o situación inusual o sospechosa que haga suponer que puede estarse presentando un intento de lavado de activos o financiación del terrorismo a través de la Fiduciaria.
      .row(numero="4" titulo="Políticas sobre consultas de Listas restrictivas")
        .col-4
          figure
            img(src="@/assets/template/tema-2-7.png", alt="Imagen descriptiva")
        .col-8
          p Hace referencia a la verificación que hace parte del procedimiento de conocimiento del cliente y vinculación, y de los procesos de debida diligencia. Se deben realizar las siguientes acciones:
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Se debe efectuar las consultas y los cruces de información de la lista que facilita la ONU y la denominada lista OFAC así se determinara junto con las otras bases de datos la prevención del lavado de activos y financiación del terrorismo.
            li 
              i.fas.fa-angle-right.acento-contenido
              | La Fiduciaria debe incorporar los contratos que celebren mecanismos de prevención de Lavado de Activos y Financiación del Terrorismo.
      .row(numero="5" titulo="Políticas de exoneración de clientes para los reportes de transacciones en efectivo ")
        .col-4
          figure
            img(src="@/assets/template/tema-2-8.png", alt="Imagen descriptiva")
        .col-8
          p Para la exoneración de asociados o clientes, es importante conocer los casos en que la normativa legal lo determine, para la realización de estas acciones.
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Se buscará realizar los negocios fiduciarios que no impliquen las operaciones habituales en efectivo de FIDUCOLDEX, de esta manera se hará la estructuración del negocio y se establecerá los recaudos y pagos que se deben hacer en la red bancaria o en el cheque.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Solo un oficial de cumplimiento puede exonerar a un cliente de diligenciar el formato de identificación individual de transacciones en efectivo, conforme a lo que permite la regulación de la Superintendencia Financiera.
      .row(numero="6" titulo="Políticas sobre desarrollo tecnológicos ")
        .col-4
          figure
            img(src="@/assets/template/tema-2-9.png", alt="Imagen descriptiva")
        .col-8
          p El desarrollo tecnológico debe facilitar la debida identificación de los clientes y usuarios y la actualización de sus datos. 
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | La organización se debe apoyar en desarrollos tecnológicos que permitan verificar los clientes en las listas o por lo menos contra las listas OFAC Y ONU y otras bases de datos que se puedan incorporar.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Se aplicará la segmentación de mercado, el monitoreo de operaciones y la consolidación electrónica de las mismas.
      .row(numero="7" titulo="Políticas sobre conservación de documentos")
        .col-4
          figure
            img(src="@/assets/template/tema-2-10.png", alt="Imagen descriptiva")
        .col-8
          p Se recomienda para la organización, manejo, conservación y guarda de todos los documentos originados en la actividad de prevención.  
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Los documentos y registros relacionados con el cumplimiento de las normas sobre prevención de LA/FT se debe conservar dentro del archivo del área de SARLAFT durante un año, luego del cual se conservarán en el archivo general durante 10 años, pasado este tiempo y si no se ha efectuado ningún requerimiento al respecto por autoridad competente, podrá ser microfilmado.
      .row(numero="8" titulo="Políticas para la etapa de monitoreo ")
        .col-4
          figure
            img(src="@/assets/template/tema-2-11.png", alt="Imagen descriptiva")
        .col-8
          p En esta etapa es importante la realización de las siguientes actividades: 
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Mantener un monitoreo constante en todos los factores de riesgo encontrados apoyándose en las herramientas tecnológicas que permiten verificar los clientes en las listas restrictivas; además, debe detectar las operaciones que hayan sido realizadas dentro de los parámetros oficiales de cumplimiento en las transacciones usuales.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Establecer por parte del oficial encargado los controles más estrictos que adviertan el perfil del riesgo de LA/FT si supera los niveles de tolerancia establecidos por la Fiduciaria.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Establecer los indicadores descriptivos y prospectivos que evidencian las potenciales fuentes de riesgos.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Asegurar que los riesgos residuales se encuentren en los niveles de aceptación que son establecidos por la entidad.
            li 
              i.fas.fa-angle-right.acento-contenido
              | La fiduciaria se abstendrá de tener relación con clientes o contrapartes domiciliados en países no cooperantes o sancionados, según el FATF/GAFI.
      .row(numero="9" titulo="Políticas de vinculación")
        .col-4
          figure
            img(src="@/assets/template/tema-2-12.png", alt="Imagen descriptiva")
        .col-8
          p Estas entidades son sometidas a la inspección y vigilancia a cargo de la SFC, a las cuales se le solicita el certificado de implementación del Sistema de Administración de Riesgos de Lavado de Activos y Financiación del Terrorismo – SARLAFT firmado por el representante legal además deben anexar los siguientes soportes:
          ul.lista-ul.mt-3
            li 
              i.fas.fa-angle-right.acento-contenido
              | Fotocopia del documento de identidad del Representante Legal.
            li 
              i.fas.fa-angle-right.acento-contenido
              | RUT.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Certificado de Existencia y Representación Legal.
            li 
              i.fas.fa-angle-right.acento-contenido
              | Formato FTAR14 Autodeclaración instituciones financieras NO estadounidenses o el diligenciamiento del formato W8-BEN-E.


</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    modalP: false,
    modalH: false,
    modalA1: false,
    modalV: false,
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
