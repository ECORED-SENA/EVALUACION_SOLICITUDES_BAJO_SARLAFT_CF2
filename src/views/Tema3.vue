<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 3
      h1 Procedimientos 
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .titulo-segundo.mt-5
      #t_3_1.h2 3.1  Conocimiento del cliente: verificación de información
    .row.mt-5.rounded-20.bg-amarillo-claro.p-5.zoom-in
      .col-6
        p.mt-5 Teniendo en cuenta lo anterior, las entidades financieras están obligadas a verificar la información suministrada por sus clientes, de igual manera sus correspondientes soportes.
        p.mt-3 Es por ello, que este procedimientos debe estar incluido dentro del manual de procedimientos SARLAFT de la entidad.
        p.mt-3 Asimismo, la Superintendencia Financiera de Colombia, a través del concepto 2011013139-003 del 6 de abril de 2011, indicó que los procedimientos de conocimiento del cliente se encuentran compuestos de dos partes:
        p.mt-3 Datos que se deben obtener para las Personas Jurídicas: 
      .col-6.px-5
        figure
          img(src="@/assets/template/tema-3-1.svg", alt="Imagen descriptiva")
    .tabla-a.color-acento-contenido.mt-5 
      table
        thead
          tr.text-center
            th.py-3 Los componentes de inserción o THT 
            th Los componentes de superficie o SMD 
        tbody
          tr
            td.p-0.position-relative 
              figure
                img(src="@/assets/template/tema-3-2.png", alt="Texto que describa la imagen")
              figure.image-cover
                img(src="@/assets/template/tema-3-2-1.svg", alt="Texto que describa la imagen")
            td.p-0.position-relative 
              figure
                img(src="@/assets/template/tema-3-3.png", alt="Texto que describa la imagen")
              figure.image-cover
                img(src="@/assets/template/tema-3-3-1.svg", alt="Texto que describa la imagen")
          tr.text-small
            td.p-4 Son todos aquellos componentes cuyos terminales o pines atraviesan físicamente la placa de circuito impreso (Sustrato o Aislante) para ser sujetados mecánicamente a través de la soldadura blanda. 
            td.p-4 La relacionada con la verificación “de la información contenida en el formulario y de los soportes de la misma, soportes que el potencial debe exhibir o entregar, si la entidad así lo determina”.
    .titulo-segundo.mt-5
      #t_3_2.h2 3.2  Importancia del manual SARLAFT dentro de los sistemas
    .row.mt-5
      .col-1.align-self-center
        figure
          img(src="@/assets/template/tema-3-4.svg", alt="Imagen descriptiva").floating
      .col-11
        p La superintendencia Financiera de Colombia busca que todas las entidades vigiladas implementen un manual del SARLAFT, con el fin de prevenir los riesgos que pueden causar, si llegan ser utilizados para dar una apariencia de legalidad pero que son actos provenientes de actividades ilícitas o de actividades de índole terrorista, por esta razón en la siguiente gráfica se muestra la importancia de la implementación de este manual:
    .row.mt-5
      .col-10.offset-1.mt-5
        .titulo-sexto.color-acento-contenido
          h5.text-small Figura 2
          p.text-small.italic Importancia del manual SARLAFT
    .row.mt-4
      .col-6.pr-4
        .row.rounded-20.borde-gris-4
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-5.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Auditan las
            .h4 autoridades.
        .row.rounded-20.borde-gris-4.mt-3
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-6.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Es el estandar de la debida diligencia 
            .h4 para efectos penales.
        .row.rounded-20.borde-gris-4.mt-3
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-7.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Compromete a la
            .h4 Junta Directiva.
        .row.rounded-20.borde-gris-4.mt-3
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-8.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Es la piedra angular del Sistema de
            .h4 prevención de la LA/FT
      .col-6.pr-4.align-self-center
        .row.rounded-20.borde-gris-4
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-9.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Es el medio de comunicación
            .h4 con los empleados.
        .row.rounded-20.borde-gris-4.mt-3
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-10.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Establece obligaciones 
            .h4 exigibles y sancionables
        .row.rounded-20.borde-gris-4.mt-3
          .col-3.align-self-center
            figure
              img(src="@/assets/template/tema-3-11.svg", alt="Texto que describa la imagen").py-3.w-75.margin-0-auto
          .col-9.text-center.align-self-center
            .h4 Se documenta todo
            .h4 para prevenir LA/FT
    .row.mt-5
      .col-6
        p Se deben tener en cuenta unos lineamientos esenciales en donde se recomienda la redacción del documento teniendo en cuenta los lineamientos importantes que la entidad debe tener en cuenta para la prevención y control del Lavado de Activos y Financiación del Terrorismo.
        .cajon.color-primario.mt-4
          .row.p-4
            p Según INFOLAT estos serían los lineamientos esenciales:
            ul.lista-ul.ml-2.pt-3
              li 
                i.fas.fa-angle-right.acento-contenido
                | Temas obligatorios y Normativos cuyo contenido no debe ser modificado.
              li 
                i.fas.fa-angle-right.acento-contenido
                | Temas obligatorios y normativos por la regulación interna, donde su contenido debe ser modificado por la entidad de acuerdo a su actividad.
              li 
                i.fas.fa-angle-right.acento-contenido
                | Temas extralegales de debida diligencia que pueden ser incluidos a cada entidad de acuerdo a su nivel de riesgo.
      .col-6.align-self-center
        figure
          img(src="@/assets/template/tema-3-12.png", alt="Imagen descriptiva")
    .row.mt-5.text-center
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1.text-center
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3             
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-13.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-3 ETAPA 1: 
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 1: 
                p.mt-3.text-small.px-3 Definir el tipo de manual SARLAFT (por procesos, controles, areas, etc. ).
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1.text-center
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-14.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4.pt-2 ETAPA 2:  
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 2: 
                p.mt-3.text-small Determinar el contenido del manual (minimo legal, mejores practicas, etc.).
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-15.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4 ETAPA 3:   
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 3:  
                p.mt-3.text-small Recolectar la información  necesaria para elaborar el manual.
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center  
                figure.pt-0
                  img(src="@/assets/template/tema-3-16.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4 ETAPA 4: 
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 4: 
                p.mt-3.text-small Revisar la documentacion verificando si esta completa o en caso contrario solicitar lo faltante.
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-17.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4 ETAPA 5: 
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 5: 
                p.mt-3.text-small Elaborar la tabla de contenido.
    .row.mt-3.text-center
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1.text-center
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3             
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-18.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-3 ETAPA 6: 
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 6: 
                p.mt-3.text-small.px-3 Elaborar la primera versión del manual SARLAFT.
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1.text-center
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-19.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4.pt-2 ETAPA 7:  
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 7: 
                p.mt-3.text-small Presentar el manual SARLAFT a las áreas interesadas para comentarios y observaciones.
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-20.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4.pt-3 ETAPA 8:   
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 8:  
                p.mt-3.text-small Realizar ajustes y correcciones.
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center  
                figure.pt-0
                  img(src="@/assets/template/tema-3-21.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-3 ETAPA 9: 
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 9: 
                p.mt-3.text-small Preparar la version final.
      .col-sm-6.col-lg-2.tarjeta-flip-tema-2.p-1
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false").box-shadow
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-3            
              .row.align-self-center   
                figure.pt-0
                  img(src="@/assets/template/tema-3-22.svg", alt="Texto que describa la imagen").w-50.margin-0-auto.px-xl-3
                .h4.mt-4 ETAPA 10: 
            .tarjeta-flip__contenido.p-3.bg-verde
              .row.pt-4    
                .h4.pt-2 ETAPA 10: 
                p.mt-3.text-small Presentar al organo competente el manual definitivo para la aprobación.
    figcaption.mt-3 Nota. https://www.infolaft.com/recomendaciones-para-hacer-un-buen-manual/




</template>

<script>
import Botones from '../components/Botones.vue'
export default {
  name: 'Tema3',
  components: {
    Botones,
  },
  data: () => ({
    // variables de vue
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
