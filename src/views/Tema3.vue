<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 3
      h1 Sustantivos contables e incontables

    .bg_grad-10.mb-5
      .row
        .col-12.col-md-2(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema3/t3-1.svg', alt='recuadros con letras')
        .col-12.col-md-10.d-flex.align-items-center
          p.mb-0 Los sustantivos, en general, pueden ser contables e incontables. Algunos pueden contarse utilizando los números, como, por ejemplo, limón: un limón, dos limones; mientras que otros sustantivos, los incontables, no utilizan números, debido a que no pueden contarse, como cuando se habla de un líquido como el agua o la leche.
    
    separador

    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Sustantivos contables
    
    p.mb-5 Los sustantivos contables son cosas que pueden ser contadas una por una y se caracterizan porque tienen forma singular y plural. Por ejemplo: <em>apple, potato, book, shoe, pears, trees, bag, car,</em> entre otros.

    .bg_grad-11
      p Algunas características de los nombres o sustantivos contables son:
      .row.mb-5
        .col-12.col-md-8
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bgr_21")
            div(titulo="<em>Some</em> y <em>Any</em>").p-4
              .bgr_19.p-4
                p Se pueden utilizar <b><em>some</em> y <em>any</em></b> con estos sustantivos.
                p <b><em>For example:</em></b>
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo1")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo2")
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo3")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo4")
                .row
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo5")
            div(titulo="<em>A/An</em>").p-4
              .bgr_19.p-4
                p Se puede utilizar el artículo indefinido <em><b>a/an</b></em> con los sustantivos contables. 
                p <b><em>For example:</em></b>
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo6")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo7")
            div(titulo="<em>Few</em> y <em>Many</em>").p-4
              .bgr_19.p-4
                p Se pueden utilizar <b><em>a few</em> y <em>many</em></b> con los nombres contables.  
                p <b><em>For example:</em></b>
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo8")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo9")
      
        .col-12.col-md-4
          figure
            img(src='@/assets/curso/tema3/t3-2.jpg', alt='hombre con una idea')

      .row.mb-5
        .col-12.col-md-4
          figure
            img(src='@/assets/curso/tema3/t3-3.jpg', alt='hombre con una idea')
        .col-12.col-md-8
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bgr_22")
            div(titulo="Nombres contables ").p-4
              .bgr_19.p-4
                p Los nombres contables pueden ser singulares o plurales.
                p <b><em>For example:</em></b>
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo10")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo11")
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo12")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo13")
            div(titulo="Nombre solo").p-4
              .bgr_19.p-4
                p Cuando un nombre contable es plural, se usa solo.
                p <b><em>For example:</em></b>
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo14")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo15")
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo16")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo17")
            div(titulo="Nombre singular").p-4
              .bgr_19.p-4
                p Cuando un nombre contable es singular, se puede utilizar una palabra como: <em><b>a, the, my, this.</b></em> 
                p <b><em>For example:</em></b>
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo18")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo19")
                .row.mb-3
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo20")
                  .col-12.col-md-6
                    TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo21")

    Separador

    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Sustantivos incontables 

    .bg_grad-12.mb-5
      .row
        .col-12.col-md-2(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema3/t3-4.svg', alt='recuadros con letras')
        .col-12.col-md-10.d-flex.align-items-center
          p.mb-0 Los sustantivos no contables son cosas que no pueden ser contadas una por una y se caracterizan porque no tienen forma plural. Por ejemplo, no pueden contarse jugos o leche, pero si botellas o litros de jugo o de leche. Algunos nombres o sustantivos incontables son: amor, arte, azúcar, aceite, café, felicidad, entre otros. 
    
    p.mb-5 Algunas características de los nombres o sustantivos incontables son:

    TabsC.color-acento-contenido
      .py-3.py-md-4.bgr_23(titulo="Verbo en singular")
        .row.pt-0.pt-md-4.d-flex.justify-content-center
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/t3-5.jpg', alt='Texto que describa la imagen')
          .col-md-6.mb-4.mb-md-0
            h4.mb-4.colr_2 Verbo en singular
            p.mb-4 Después de un nombre incontable, se usa el <b>verbo en singular.</b> 
            p.mb-4.colr_2.text-bold <em>For example:</em>
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo22")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo23")
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo24")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo25")
      .py-3.py-md-4.bgr_23(titulo="<em>Any</em> y <em>some</em>")
        .row.pt-0.pt-md-4.d-flex.justify-content-center
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/t3-6.jpg', alt='Texto que describa la imagen')
          .col-md-6.mb-4.mb-md-0
            h4.mb-4.colr_2 <em>Any</em> y <em>some</em> 
            p.mb-4 Se pueden utilizar <b><em>any</em> y <em>some</em></b> con nombres incontables 
            p.mb-4.colr_2.text-bold <em>For example:</em>
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo26")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo27")
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo28")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo29")
      .py-3.py-md-4.bgr_23(titulo="<em>Little</em> y <em>much </em>")
        .row.pt-0.pt-md-4.d-flex.justify-content-center
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/t3-7.jpg', alt='Texto que describa la imagen')
          .col-md-6.mb-4.mb-md-0
            h4.mb-4.colr_2 <em>Little</em> y <em>much</em>  
            p.mb-4  Se pueden usar <b><em>a little</em> y <em>much</em></b> con nombres incontables.  
            p.mb-4.colr_2.text-bold <em>For example:</em>
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo30")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo31")
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo32")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo33")
      .py-3.py-md-4.bgr_23(titulo="Nombres incontables")
        .row.pt-0.pt-md-4.d-flex.justify-content-center
          .col-md-4
            figure
              img(src='@/assets/curso/tema3/t3-8.jpg', alt='Texto que describa la imagen')
          .col-md-6.mb-4.mb-md-0
            h4.mb-4.colr_2 Nombres incontables  
            p.mb-4  Con nombres incontables, no se utiliza el artículo indefinido <em><b>a o an</b></em>, pero se pueden usar algunas palabras de medidas, como a…of.   
            p.mb-4.colr_2.text-bold <em>For example:</em>
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo34")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo35")
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo36")
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo37")
            .row.mb-3
              .col-12.col-md-6
                TraduccionAudio.color-acento-contenido.bgr_20(:dialogo="dialogo38")

   
</template>

<script>
import TraduccionAudio from '../components/TraduccionAudio.vue'
export default {
  name: 'Tema3',
  components: {
    TraduccionAudio,
  },
  data: () => ({
    dialogo1: [
      {
        textoIng: 'You have some dollars.',
        textoEsp: 'Tú tienes algunos dólares.',
        audio: require('@/assets/curso/audios/3.1/1.mp3'),
      },
    ],
    dialogo2: [
      {
        textoIng: 'Susy has some books at home.',
        textoEsp: 'Susy tiene algunos libros en la casa.',
        audio: require('@/assets/curso/audios/3.1/2.mp3'),
      },
    ],
    dialogo3: [
      {
        textoIng: 'Do you want some cookies?',
        textoEsp: '¿Quieres algunas galletas?',
        audio: require('@/assets/curso/audios/3.1/3.mp3'),
      },
    ],
    dialogo4: [
      {
        textoIng: 'Do you have any pencils?',
        textoEsp: '¿Tienes algunos lápices?',
        audio: require('@/assets/curso/audios/3.1/4.mp3'),
      },
    ],
    dialogo5: [
      {
        textoIng: 'Jhon doesn’t have any hats.',
        textoEsp: 'Jhon no tiene ningún sombrero.',
        audio: require('@/assets/curso/audios/3.1/5.mp3'),
      },
    ],
    dialogo6: [
      {
        textoIng: 'Mary wants a pear.',
        textoEsp: 'Mary quiere una pera.',
        audio: require('@/assets/curso/audios/3.1/6.mp3'),
      },
    ],
    dialogo7: [
      {
        textoIng: 'An eagle is big and beautiful.',
        textoEsp: 'Un águila es grande y hermosa.',
        audio: require('@/assets/curso/audios/3.1/7.mp3'),
      },
    ],
    dialogo8: [
      {
        textoIng: 'Charles has a few dollars.',
        textoEsp: 'Charles tiene unos pocos dólares',
        audio: require('@/assets/curso/audios/3.1/8.mp3'),
      },
    ],
    dialogo9: [
      {
        textoIng: 'Mary has many things to do.',
        textoEsp: 'Mary tiene muchas cosas que hacer.',
        audio: require('@/assets/curso/audios/3.1/9.mp3'),
      },
    ],
    dialogo10: [
      {
        textoIng: 'The house is comfortable.',
        textoEsp: 'La casa es cómoda.',
        audio: require('@/assets/curso/audios/3.1/10.mp3'),
      },
    ],
    dialogo11: [
      {
        textoIng: 'The houses are comfortable.',
        textoEsp: 'Las casas son cómodas.',
        audio: require('@/assets/curso/audios/3.1/11.mp3'),
      },
    ],
    dialogo12: [
      {
        textoIng: ' My blouse is new.',
        textoEsp: 'Mi blusa es nueva.',
        audio: require('@/assets/curso/audios/3.1/12.mp3'),
      },
    ],
    dialogo13: [
      {
        textoIng: ' My blouses are new.',
        textoEsp: 'Mis blusas son nuevas.',
        audio: require('@/assets/curso/audios/3.1/13.mp3'),
      },
    ],
    dialogo14: [
      {
        textoIng: 'Carol likes apples.',
        textoEsp: 'A Carol le gustan las manzanas.',
        audio: require('@/assets/curso/audios/3.1/14.mp3'),
      },
    ],
    dialogo15: [
      {
        textoIng: 'Mike loves dogs.',
        textoEsp: 'Mike ama a los perros.',
        audio: require('@/assets/curso/audios/3.1/15.mp3'),
      },
    ],
    dialogo16: [
      {
        textoIng: 'Birds can sing.',
        textoEsp: 'Los pájaros cantan.',
        audio: require('@/assets/curso/audios/3.1/16.mp3'),
      },
    ],
    dialogo17: [
      {
        textoIng: 'Diamonds are her favourites.',
        textoEsp: 'Los diamantes son sus favoritos.',
        audio: require('@/assets/curso/audios/3.1/17.mp3'),
      },
    ],
    dialogo18: [
      {
        textoIng: 'You want an apple.',
        textoEsp: 'Tú quieres una manzana.',
        audio: require('@/assets/curso/audios/3.1/18.mp3'),
      },
    ],
    dialogo19: [
      {
        textoIng: 'Where is my pencil?',
        textoEsp: '¿Dónde está mi lápiz?',
        audio: require('@/assets/curso/audios/3.1/19.mp3'),
      },
    ],
    dialogo20: [
      {
        textoIng: 'When is the football game?',
        textoEsp: '¿Cuándo es el juego de fútbol?',
        audio: require('@/assets/curso/audios/3.1/20.mp3'),
      },
    ],
    dialogo21: [
      {
        textoIng: 'Jim wants this pen.',
        textoEsp: 'Jim quiere esta pluma.',
        audio: require('@/assets/curso/audios/3.1/21.mp3'),
      },
    ],
    dialogo22: [
      {
        textoIng: 'The juice is not enough.',
        textoEsp: 'El jugo no es suficiente.',
        audio: require('@/assets/curso/audios/3.2/1.mp3'),
      },
    ],
    dialogo23: [
      {
        textoIng: 'The air looks very polluted.',
        textoEsp: 'El aire luce muy contaminado.',
        audio: require('@/assets/curso/audios/3.2/2.mp3'),
      },
    ],
    dialogo24: [
      {
        textoIng: 'This news is very sad.',
        textoEsp: 'Esta noticia es muy triste.',
        audio: require('@/assets/curso/audios/3.2/3.mp3'),
      },
    ],
    dialogo25: [
      {
        textoIng: 'Your mind is strong.',
        textoEsp: 'Tu mente es fuerte.',
        audio: require('@/assets/curso/audios/3.2/4.mp3'),
      },
    ],
    dialogo26: [
      {
        textoIng: 'He has some money.',
        textoEsp: 'Él tiene algo de dinero.',
        audio: require('@/assets/curso/audios/3.2/5.mp3'),
      },
    ],
    dialogo27: [
      {
        textoIng: 'Do you have any rice?',
        textoEsp: '¿Tienes arroz?',
        audio: require('@/assets/curso/audios/3.2/6.mp3'),
      },
    ],
    dialogo28: [
      {
        textoIng: 'We want some peace.',
        textoEsp: 'Nosotros queremos algo de paz.',
        audio: require('@/assets/curso/audios/3.2/7.mp3'),
      },
    ],
    dialogo29: [
      {
        textoIng: 'They don’t have any time.',
        textoEsp: 'Ellos no tienen tiempo.',
        audio: require('@/assets/curso/audios/3.2/8.mp3'),
      },
    ],
    dialogo30: [
      {
        textoIng: 'Peter has a little money.',
        textoEsp: 'Peter tiene un poco de dinero.',
        audio: require('@/assets/curso/audios/3.2/9.mp3'),
      },
    ],
    dialogo31: [
      {
        textoIng: 'She wants a little space in the room.',
        textoEsp: 'Ella quiere un poco de espacio en la habitación.',
        audio: require('@/assets/curso/audios/3.2/10.mp3'),
      },
    ],
    dialogo32: [
      {
        textoIng: 'Carol needs much sugar for that cake.',
        textoEsp: 'Carol necesita mucha azúcar para ese pastel.',
        audio: require('@/assets/curso/audios/3.2/11.mp3'),
      },
    ],
    dialogo33: [
      {
        textoIng: 'You don’t have much patience.',
        textoEsp: 'Tú no tienes mucha paciencia.',
        audio: require('@/assets/curso/audios/3.2/12.mp3'),
      },
    ],
    dialogo34: [
      {
        textoIng: ' Luis reads a piece of news.',
        textoEsp: 'Luis lee una noticia.',
        audio: require('@/assets/curso/audios/3.2/13.mp3'),
      },
    ],
    dialogo35: [
      {
        textoIng: ' Kim has a bottle of water.',
        textoEsp: 'Kim tiene una botella de agua.',
        audio: require('@/assets/curso/audios/3.2/14.mp3'),
      },
    ],
    dialogo36: [
      {
        textoIng: ' The child planted a grain of rice.',
        textoEsp: 'El niño plantó un grano de arroz.',
        audio: require('@/assets/curso/audios/3.2/15.mp3'),
      },
    ],
    dialogo37: [
      {
        textoIng: ' I need a lot of information.',
        textoEsp: 'Necesito mucha información.',
        audio: require('@/assets/curso/audios/3.2/16.mp3'),
      },
    ],
    dialogo38: [
      {
        textoIng: ' You buy a bar of soap in the market.',
        textoEsp: 'Tú compras una barra de jabón en el mercado.',
        audio: require('@/assets/curso/audios/3.2/17.mp3'),
      },
    ],
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
