<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-primario
      .titulo-principal__numero
        span(style="color: white") 2
      h1 Pasos para la constitución

    .d-flex.mb-5
      img(src="@/assets/curso/tema2/decorador.svg" data-aos="fade-right" style="max-width: 36px").mx-3.mx-md-4
      .text-bg-middle-color
        p Tal y como se ha comentado anteriormente, las cámaras de comercio son las organizaciones responsables de llevar el registro de las personas jurídicas y naturales que se crean en todo el territorio colombiano y de acuerdo con el domicilio de la nueva empresa, este registro se realiza según corresponda a su jurisdicción geográfica. Un ejemplo claro, es si la nueva empresa va a tener como domicilio principal la ciudad de Bogotá, entonces el registro se realiza en la Cámara de Comercio de Bogotá que pertenece a esta jurisdicción.

    .d-flex.flex-wrap.mb-5
      .col-12.col-md-6.mb-4.my-md-auto
        img(src="@/assets/curso/tema2/decorador1.svg" data-aos="fade-right" style="max-width: 272px").mb-4.ms-3
        div(style="background-color: #DDF6C0").p-3.p-md-4.m-0.mx-md-3
          p.mb-0 El Decreto Ley 2150 de 1995, en el cual se suprimen y reforman regulaciones, procedimientos o trámites innecesarios existentes en la administración pública, en el artículo 143, menciona que:
        img(src="@/assets/curso/tema2/decorador-5.svg" data-aos="fade-left" style="max-width: 84px").mt-4.mt-md-5.ms-3
      .col-12.col-md-6.container-text-comillas.px-0.ps-md-3.pe-md-4
        .bloque-texto-c.color-secundario.p-4
          i.fas.fa-quote-right(style="color: #EA3065")
          p.px-3.px-4(data-aos="fade-up") “Las entidades de naturaleza cooperativa, los fondos de empleados y las asociaciones mutuales, así como sus organismos de integración y las instituciones auxiliares del cooperativismo son entidades sin ánimo de lucro y se constituirán por escritura pública o documento privado, el cual deberá ser suscrito por todos los asociados fundadores y contener constancia acerca de la aprobación de los estatutos de la empresa asociativa”.
    
    .d-flex.mb-5
      img(src="@/assets/curso/introduccion/decorador_point.svg" style="max-width: 10px").me-3
      p.mb-0 El siguiente video expone brevemente los pasos a seguir para la constitución de una organización.
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Q0qthRiYOU0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p.mb-5 Una vez se ha conocido en qué consiste el proceso, ahora se profundizará en cada paso explicado a través del siguiente recurso interactivo:
  
    .d-flex.mb-5
      img(src="@/assets/curso/tema2/decorador2.svg" style="max-width: 10px").me-3
      span(style="background-color: #C9EFF5").py-1.px-2.fw-bold Pasos para la constitución de una empresa

    img(src="@/assets/curso/tema2/img_t_2-1.png").mb-5.pb-5

    .container_link.position-relative.col-12.col-md-11.mx-auto.d-flex.flex-wrap.flex-md-nowrap.mb-5
      img(src="@/assets/curso/tema2/img_t_2-2.png" data-aos="zoom-in" style="max-width: 419px; margin-top: -2.5rem")
      .my-auto.position-relative.w-100
        p(style="color: white").pe-0.pe-md-5.pb-4 Estimado aprendiz, para profundizar sobre el tema, te invitamos a <br> descargar el siguiente PDF:
        .w-100.d-flex.justify-content-center.pe-0.pe-md-5.mt-5
          .mx-auto.text-center
            p.fw-bold(style="color: white") "Pasos para la constitución de una empresa"
            a.boton.color-acento-contenido(:href="obtenerLink('/downloads/PasosParaLaConstitucionDeUnaEmpresa.pdf')" target="_blank" style="background-color: #FFD947")
              span(style="color: black") Descargar
              i.fas.fa-file-download(style="color: black")
          img(src="@/assets/curso/tema2/decorador3.svg" data-aos="fade-left" style="max-width: 36px; margin-right: 3rem")
      img(src="@/assets/curso/tema2/img_t_2-3.png" data-aos="zoom-in" style="max-width: 72px; position: absolute; right: 0; top: 50%; transform: translateY(-50%);")
    
    .d-flex.justify-content-between.mb-5
      img(src="@/assets/curso/tema2/decorador4.svg" data-aos="flip-right" style="max-width: 35px").mx-3
      .cajon.color-acento-contenido.p-4.cajon-color-1.col-md-10.col-lg-8.d-flex.flex-wrap.flex-md-nowrap
        div(style="min-width: 155px; min-height: 72px").position-relative
          img(src="@/assets/curso/tema2/img_t_2-4.png" style="position: absolute; top: -50%")
        p.mb-0 Los pasos para la constitución de las organizaciones de economía solidaria son los mismos, indistintamente de la forma jurídica seleccionada.
      img(src="@/assets/curso/tema2/decorador4.svg" data-aos="flip-left" style="max-width: 35px").mx-3.d-none.d-lg-flex
    
</template>

<script>
export default {
  name: 'Tema2',
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

<style lang="sass">
.text-bg-middle-color
  position: relative
  p
    position: relative
    z-index: 0
    margin-bottom: 0
  &::before
    z-index: 0
    position: absolute
    content: ''
    right: 0
    bottom: 0
    height: 50%
    width: 40%
    background-color: #DDF6C0
.container-text-comillas
  .bloque-texto-c.color-secundario
    background-color: #E1E1E1
  .bloque-texto-c
    &::after
      background-color: #EA3065
.container_link
  background-color: #491079
  border-radius: 20px
  display: flex
  flex-wrap: wrap
.cajon-color-1
  background-color: #E1E1E1 !important
</style>
