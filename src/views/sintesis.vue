<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .d-flex
      img(src="@/assets/curso/introduccion/decorador_point.svg" style="max-width: 10px").me-3
      p.fw-bold.mb-0 Figura 4
    .d-flex.justify-content-between.align-items-start.position-relative.mb-5
      p.mb-0.ps-4 <em>Síntesis</em>
      img(src="@/assets/curso/introduccion/decorador.svg" style="max-width: 84px; max-height: 10px").my-auto

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="alt")

    .col-12.mb-5
      .cajon.color-acento-contenido.p-4.mb-4.bg-text-sintesis
        p Es de resaltar que, además, de los pasos para la constitución, se requiere cumplir con los trámites solicitados ante los entes de control vistos anteriormente y que se pueden realizar en línea a través del Portal Único del Estado Colombiano, que en su mayoría no tiene costo alguno, facilitando la eficiencia en la gestión de estas diligencias; así mismo, se requiere de una vigilancia permanente de los cambios, ajustes o actualizaciones a la normativa que regulan las organizaciones de economía solidaria que permita proteger el capital de los asociados y por ende sus contribuciones al crecimiento de la economía de un país o una región.
</template>

<script>
export default {
  name: 'Sintesis',
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
.bg-text-sintesis.cajon.color-acento-contenido
  background-color: #DFF6C3 !important
  &::before
    background-color: #A6E65A
</style>
