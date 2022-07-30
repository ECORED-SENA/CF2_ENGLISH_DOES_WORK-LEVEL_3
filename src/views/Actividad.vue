<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-tasks" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/arrastrar.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 <em>Buying at the mall</em> / Comprando en el centro comercial
        p.mb-4 Identificar las tiendas en el centro comercial.
        .tarjeta.bgr_35.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Arrastar y soltar.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/01/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/falso-verdadero.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 <em>Asking for prices</em>/ Preguntando precios
        p.mb-4 Indicar si la respuesta dada a la pregunta realizada es verdadera o falsa.
        .tarjeta.bgr_35.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Falso y verdadero.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/02/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/completar-espacios.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 <em>Do you want some cookies?</em>/ ¿Quieres unas galletas?
        p.mb-4 Reconocer los sustantivos contables y los incontables en idioma inglés.
        .tarjeta.bgr_35.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Completar.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/03/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/completar-espacios.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 <em>Selecting the best option!</em>/ Seleccionando la mejor opción.
        p.mb-4 Aplicar las normas para la formación del plural de los sustantivos regulares e irregulares.
        .tarjeta.bgr_35.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Completar.
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/04/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    
</template>

<script>
export default {
  name: 'Actividad',
}
</script>

<style lang="sass"></style>
