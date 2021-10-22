<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 5
      h1 Normas de Seguridad y Salud en el Trabajo SST
    .row.mt-5
      .col-3.align-self-center
        figure
          img(src="@/assets/template/tema-5-1.svg", alt="Texto que describa la imagen").floating
      .col-9
        p Según el Ministerio del Trabajo el Sistema de Gestión de Seguridad y Salud en el Trabajo (SG-SST) debe ser implementado por todos los empleadores y consiste en el desarrollo de un proceso lógico y por etapas, basado en la mejora continua, lo cual incluye la política, la organización, la planificación, la aplicación, la evaluación, la auditoría y las acciones de mejora con el objetivo de anticipar, reconocer, evaluar y controlar los riesgos que puedan afectar la seguridad y la salud en los espacios laborales.
        p.mt-3 Es importante que cada persona, estudiante, trabajador en su puesto de trabajo tengan presente la normatividad presente frente al Sistema de Gestión de salud y seguridad en el trabajo, ya que esto nos ayuda a cumplir con normas y a su vez mejorar nuestro clima organizacional. y laboral.
    .row.mt-5
      .col-8
        p Si se tiene un buen equipo de trabajo, armonizado con buen clima organizacional, se cumplen mejor las funciones de la empresa y podemos desarrollar mejor las actividades, como es el caso de la implementacion adecuada del Sistema de Administracciondel Riesgo lavados de activos y financiacion del terrorismo - SARLAFT. 
        p.mt-3 Son dos procesos que aunque se diseñan de manera independiente por personal especializado de cada área organizacional, los funcionarios deben implementarlos para garantizar los objetivos generales y específicos de la entidad.
        p.mt-3 A continuación, podrá ampliar información relacionada con la normativa SG-SST.
      .col-4.align-self-center
        figure
          img(src="@/assets/template/tema-5-2.svg", alt="Texto que describa la imagen").floating
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-secundario.p-3.mb-5
          .row.justify-content-around.align-items-center.py-3
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-5-3.svg").w-75.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 DECRETO NORMATIVO SG-SST
                  p.text-small En el presente documento se encuentra todo lo referente a la implementación del Sistema de Gestión de Seguridad y Salud en el Trabajo.
                  .h4 Anexo 4. Decreto SG-SST 1443 de 2014.
                .col-sm-auto
                  a.boton.color-acento-contenido(:href="obtenerLink('/downloads/Anexo_4.Decreto_SG-SST _1443_de_2014.pdf')" target="_blank")
                    span.text-sistema Descargar
                    i.fas.fa-file-download.text-sistema

</template>

<script>
export default {
  name: 'Tema5',
  components: {},
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
