<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 7
      h1 Expresiones contables en compra de productos - <em>That’s very expensive!</em>

    .bgr_34.mb-5.p-5
      .row
        .col-12.col-md-4
          figure
            img(src='@/assets/curso/tema7/t7-1.png', alt='Texto que describa la imagen')
        .col-12.col-md-8
          p Las expresiones contables en productos permiten calificar las cosas o productos que se encuentran en el mercado, los cuales los comerciantes o vendedores ponen a la venta y a los cuales asignan un precio determinado, y las personas que ellos denominan clientes o usuarios compran por ese precio establecido, calificando generalmente ese producto de acuerdo con la relación precio o valor que aprecia en su presentación como cantidad, calidad, que en inglés sería:
          .row.d-flex.justify-content-center
            .col-12.col-md-10
              .row.bgr_3.p-5.d-flex.justify-content-center.align-items-center
                .col-12.col-md-2
                  figure
                    img(src='@/assets/curso/tema7/t7-2.svg', alt='Texto que describa la imagen')
                .col-12.col-md-5
                  p.mb-0 <em><b>Cheap</b></em>: barato 
                  p.mb-0 <em><b>Affordable</b></em>: asequible 
                .col-12.col-md-5
                  p.mb-0 <em><b>Reasonable</b></em>: razonable
                  p.mb-0 <em><b>Expensive</b></em>:   caro 

    h4 Buying groceries

    p.mb-5 En el mercado, supermercado o en tiendas, pueden comprarse alimentos, vegetales, carnes, frutas y otros productos para cubrir nuestras necesidades. Algunas veces nos gustan los precios y decimos que son razonables o están baratos, pero, en otras ocasiones, el precio del producto lo consideramos o es muy alto, por eso decimos que está caro. En ese orden de ideas, revise algunos ejemplos:

    .row.d-flex.justify-content-center
      .col-12.col-md-10
        PasosA.color-primario.mb-5.pst_7(tipo="n")
          .row
            .col-md-8.mb-4.mb-md-0
              TarjetaAudio.color-acento-contenido.bgr_20.my-3(
              texto="<i><span1>Customer: How much are the bananas? <br>Seller: The bananas are $25.<br>Customer: That’s very expensive! </span1></i>"
                :audio="require('@/assets/curso/audios/7/1.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
            .col-md-4(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/tema7/t7-3.svg', alt='Texto que describa la imagen')
          .row
            .col-md-4(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/tema7/t7-4.svg', alt='Texto que describa la imagen')
            .col-md-8.mb-4.mb-md-0
              TarjetaAudio.color-acento-contenido.bgr_20.my-3(
              texto="<i><span1>Customer: How much is the chicken? <br>Seller: The kilogram of chicken is only $5. <br>Customer: That’s reasonable! I’ll take it.</span1></i>"
                :audio="require('@/assets/curso/audios/7/2.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
          .row
            .col-md-8.mb-4.mb-md-0
              TarjetaAudio.color-acento-contenido.bgr_20.my-3(
              texto="<i><span1> Customer: How much are the strawberries? <br>Seller: The strawberries are on sale, they’re only $4. <br>Customer: That’s affordable for me.</span1></i>"
                :audio="require('@/assets/curso/audios/7/3.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
            .col-md-4(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/tema7/t7-5.svg', alt='Texto que describa la imagen')
          .row
            .col-md-4(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/tema7/t7-6.svg', alt='Texto que describa la imagen')
            .col-md-8.mb-4.mb-md-0
              TarjetaAudio.color-acento-contenido.bgr_20.my-3(
              texto="<i><span1> Customer: How much are the apples? <br>Seller: The apples are $1 each one. <br>Customer: That’s very cheap! I’ll take six apples.</span1></i>"
                :audio="require('@/assets/curso/audios/7/4.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          .row
            .col-md-8.mb-4.mb-md-0
              TarjetaAudio.color-acento-contenido.bgr_20.my-3(
              texto="<i><span1> Customer: How much is the pineapple? <br>Seller: The pineapple is $18. <br>Customer: That’s expensive!</span1></i>"
                :audio="require('@/assets/curso/audios/7/5.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
            .col-md-4(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/tema7/t7-7.svg', alt='Texto que describa la imagen')
            
    
   
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
