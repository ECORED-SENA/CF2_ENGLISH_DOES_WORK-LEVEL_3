<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span
          i.fas.fa-info
      h1 Introducción
    
    span.mb-5 Bienvenido al componente formativo 
    span.colr_1 <b>A shopping day!</b>  
    span <b> / Un día de compras</b>. En el siguiente video, podrá encontrar, de forma general, la temática que estudiará:

    figure.mb-5.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/s_tiO44CEUg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
   
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
