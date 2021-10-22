<template lang="pug">
.tarjeta.color-primario__claro.p-4
  .row.justify-content-center
    .col-md-6.mb-4.mb-md-0
      .botones.mb-5
        img(src='@/assets/template/botones-fondo.svg', alt='Texto que describa la imagen')
        .botones__item(
          v-for="(boton, index) in botones"
        )
          .botones__btn(
            :style="getStyles(boton, index)"
            @mouseover="hover = index"
            @mouseleave="hover = null"
            @click="selected = index"
          )
            .indicador--click(v-if="index === 1 && indicador")
            
    .col-md-6
      .tarjeta.tarjeta-botones.px-5.pt-5.pb-0.pb-xl-5(v-if="selected === 0").bg-blanco.borde-rojo-4
        h4 Riesgos estratégicos
        p.mb-3.mb-xl-5 Ocasionados por el establecimiento erróneo de planes, estructuras y programas o por una distribución inadecuada de los recursos, una baja adaptación a los cambios o un errado direccionamiento estratégico. 
      .tarjeta.tarjeta-botones.px-5.pt-5.pb-0.pb-xl-5(v-else-if="selected === 1").bg-blanco.borde-rojo-4
        h4 Riesgos operativos
        p.mb-3.mb-xl-5 Por la inadecuada gestión de los procedimientos y las actividades o la errada realización de las etapas de un proceso, generando pérdidas con ello

      .tarjeta.tarjeta-botones.px-5.pt-5.pb-0.pb-xl-5(v-else-if="selected === 2").bg-blanco.borde-rojo-4
        h4 Riesgos financieros
        p.mb-3.mb-xl-5 Por no poseer los suficientes flujos de caja para cubrir los compromisos a corto plazo, lo que se encuentra relacionado con la cantidad de pasivo que se posee para financiar la operatividad. 
      .tarjeta.tarjeta-botones.px-5.pt-5.pb-0.pb-xl-5(v-else-if="selected === 3").bg-blanco.borde-rojo-4
        h4 Riesgo empresarial
        p.mb-3.mb-xl-5 En el plano corporativo, el riesgo se define como la incertidumbre que surge durante la consecución de un objetivo. Se trata, en esencia, de circunstancias, sucesos o eventos adversos, que impiden el normal desarrollo de las actividades de una empresa y que, en general, tienen repercusiones económicas para sus responsables.

</template>

<script>
export default {
  name: 'Botones',
  data: () => ({
    indicador: true,
    selected: 0,
    hover: null,
    size: '21%',
    botones: [
      {
        img: require('@/assets/template/botones-ico-01-a.svg'),
        img_h: require('@/assets/template/botones-ico-01-b.svg'),
        pos_x: '105%',
        pos_y: '88%',
      },
      {
        img: require('@/assets/template/botones-ico-02-a.svg'),
        img_h: require('@/assets/template/botones-ico-02-b.svg'),
        pos_x: '130%',
        pos_y: '88%',
      },
      {
        img: require('@/assets/template/botones-ico-03-a.svg'),
        img_h: require('@/assets/template/botones-ico-03-b.svg'),
        pos_x: '155%',
        pos_y: '88%',
      },
      {
        img: require('@/assets/template/botones-ico-04-a.svg'),
        img_h: require('@/assets/template/botones-ico-04-b.svg'),
        pos_x: '180%',
        pos_y: '88%',
      },
    ],
  }),
  watch: {
    selected() {
      this.indicador = false
    },
    hover() {
      this.indicador = false
    },
  },
  methods: {
    getStyles(boton, index) {
      const image =
        this.hover === index || this.selected === index
          ? boton.img_h
          : boton.img
      return {
        'background-image': `url(${image})`,
        top: boton.pos_y,
        left: boton.pos_x,
        width: this.size,
        'padding-top': this.size,
      }
    },
  },
}
</script>

<style lang="sass" scoped>
.botones
  position: relative
.botones__btn
  background-size: cover
  position: absolute
  cursor: pointer
  border-radius: 50%
  transition: background-image 0.2s ease-in-out
</style>
