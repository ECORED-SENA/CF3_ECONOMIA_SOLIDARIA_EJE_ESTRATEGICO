<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span(style="color: white")
          i.fas.fa-info
      h1 Introducción
    
    .containe-color-bg-text.mb-5
      img(src="@/assets/curso/introduccion/decorador_point.svg" style="max-width: 10px; position: relative; z-index: 1").mx-3.pt-2
      div(style="z-index: 1; position: relative").pe-0.pe-md-4
        p.mb-4.mb-md-0 Un aspecto principal en el normal desarrollo de las actividades empresariales es el cumplimiento de la normativa, el cual se da a través de su forma jurídica. El siguiente video presenta la importancia de la constitución formal:
        img(src="@/assets/curso/introduccion/decorador.svg" style="max-height: 10px; max-width: 84px").ms-auto

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.containe-color-bg-text
  position: relative
  display: flex
  align-items: start
  &::after
    position: absolute
    content: ''
    top: 0
    left: 0
    width: 40%
    height: 100%
    background-color: #DDF6C0
    z-index: 0
</style>
