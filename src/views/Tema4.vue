<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 4
      h1 Formatos y datos 
    .row.mt-5
      .col-10.offset-1
        figure
          img(src="@/assets/template/tema-4-1.png", alt="Imagen descriptiva")
    .row.mt-5
      .col-10
        p El sistema SARLAFT requiere del uso de diferentes formatos, estos dependen de la normativa nacional, de los procesos propios de cada entidad y del sistema de gestión que cada equipo especializado considere pertinente. Los formatos pueden ser de prevención, formato de vinculación o actualización, formato de exoneración, formato matriz, mapa de riesgos, etc.
        p.mt-3 El siguiente formato se utiliza cuando se requiere modificar, aprobar o eliminar información del manual de SARLAFT, es importante aclarar, que los datos y la organización de cada formato pueden variar según el Sistema de Gestión de cada entidad.
      .col-2.px-4.align-self-center
        figure
          img(src="@/assets/template/tema-4-2.svg", alt="Texto que describa la imagen").floating
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center.py-3
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-4-3.svg").w-75.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 FORMATO MODIFICACIÓN MANUAL SARLAFT
                  p.text-small Este formato es un ejemplo de un procedimiento para  realizar una modificación del Manual SARLAFT.
                  .h4 Anexo 3. Formato acta de aprobación. 
                .col-sm-auto
                  a.boton.color-acento-contenido(:href="obtenerLink('/downloads/Anexo_3.Acta_de_aprobacion_Manual_Sarlaft.pdf')" target="_blank")
                    span.text-sistema Descargar
                    i.fas.fa-file-download.text-sistema
    p.mt-5 Para la creación de formatos es importante tener en cuenta que al realizar este proceso existen errores frecuentes como, por ejemplo:
    .row.mt-5
      .col-6
        .cajon.color-primario.mt-4
          .row.p-4            
            ul.lista-ul.ml-2.pt-3
              li 
                i.fas.fa-angle-right.acento-contenido
                | Se tienen en cuenta datos adicionales que no son requeridos en la normativa.
              li 
                i.fas.fa-angle-right.acento-contenido
                | La inclusión de políticas incompletas.
              li 
                i.fas.fa-angle-right.acento-contenido
                | Hacer un inadecuado desarrollo de los procedimientos.
              li 
                i.fas.fa-angle-right.acento-contenido
                | Colocar dentro del manual SARLAFT controles que no se cumplen en la entidad. 
        .row.mt-4
          .col-4.align-self-center
            figure
              img(src="@/assets/template/tema-4-4.svg", alt="Texto que describa la imagen").px-3.floating
          .col-8
            p Se debe tener en cuenta la verificación del manual cerciorándose del cumplimiento del protocolo y así poder obtener la aprobación del manual y todos los documentos complementarios que lo componen, por parte del órgano competente y una vez cumplido este proceso se debe proceder a su divulgación.
      .col-6.align-self-center
        figure
          img(src="@/assets/template/tema-4-5.png", alt="Imagen descriptiva")



</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
    modal3: false,
    modal4: false,
    modal5: false,
    modal6: false,
    modal7: false,
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
