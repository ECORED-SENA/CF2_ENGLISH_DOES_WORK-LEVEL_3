<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 6
      h1 Pronunciación de sonidos <em>s - es - Like a bee!</em>
    
    .bg_grad-09.mb-5
      .row
        .col-12.col-md-2(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema6/t6-1.svg', alt='recuadros con letras')
        .col-12.col-md-10.d-flex.align-items-center
          div
            span.mb-0 En la comunicación, es importante tener una buena pronunciación, por ello, es importante revisarla desde los sonidos de la 
            span.colr_2 S 
            | al inicio y al final. A continuación, puede verificar algunas reglas importantes para que su proceso de hablar en inglés tenga las competencias esenciales: 
    
    figure.mb-5.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Tema3',
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

<style lang="sass"></style>
