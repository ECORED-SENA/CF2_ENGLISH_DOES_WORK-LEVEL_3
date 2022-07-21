<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 1
      h1 Alimentos y cantidades - <em>I like it!</em>

    .bg_grad-01.mb-5
      .row
        .col-12.col-md-4(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema1/t1-1.png', alt='hombre con una idea')
        .col-12.col-md-8.d-flex.align-items-center
          p.mb-0 Los alimentos son importantes para los seres humanos, porque las personas deben ingerir alimentos para vivir. Existen infinidad de alimentos de origen animal y de origen vegetal. Cuando queremos comprar alimentos, vamos a un mercado, a un supermercado o a una tienda. Algunos alimentos son líquidos, como la leche y el jugo, por ello, cuando vamos a comprarlos, pedimos un litro de leche o un litro de jugo. Otros son alimentos sólidos, como la carne, el pollo y granos, y los compramos por kilo. Las frutas y otros alimentos similares los solicitamos por cantidades, por ejemplo: cuatro peras, dos piñas, seis plátanos, entre otros.

    .bg_grad-02.mb-5
      p.mb-5 A continuación, se mencionan algunos alimentos y la forma en que se presentan para su uso o cuando deben comprarse y/o venderse en los sitios destinados a ello:
    
      .row.d-flex.justify-content-center.mb-3
        .col-12.col-md-7
          .titulo-sexto.color-acento-contenido
            h5 Tabla 1
            span <em>Food and amounts</em> / Alimentos y cantidade

          .tabla1.color-acento-botones.mb-lg-0
            table.text-center.w-100
              tbody
                tr.bgt1header
                  td.t1br <em>Amount</em> / Cantidad
                  td.t1br Traducción
                  td.td1bd <em>To</em> / Para
                tr
                  td.tb1bd.tb2bd <em>Teaspoon</em>
                  td.tb1bd Cucharita
                  td.tb1bd <em>Spices</em> / Especias
                tr
                  td.tb1bd.tb2bd <em>Tablespoon</em>
                  td.tb1bd Cuchara
                  td.tb1bd <em>Sugar</em> / Azúcar
                tr
                  td.tb1bd.tb2bd <em>Cup</em>
                  td.tb1bd Taza
                  td.tb1bd <em>Grains (rice, corn)</em> / Granos (arroz, maíz)
                tr
                  td.tb1bd.tb2bd <em>Pinch</em>
                  td.tb1bd Pizca
                  td.tb1bd <em>Salt, pepper</em> / Sal, pimienta
                tr
                  td.tb1bd.tb2bd <em>Ounces and grams</em>
                  td.tb1bd Onzas y gramos
                  td.tb1bd <em>Flour, sugar</em> / Harina, azúcar
                tr
                  td.tb1bd.tb2bd <em>Kilogram</em>
                  td.tb1bd Kilogramo
                  td.tb1bd <em>Flour, tomatoes</em> / Harina, tomates
                tr
                  td.tb1bd.tb2bd <em>Cloves</em>
                  td.tb1bd Dientes
                  td.tb1bd <em>Garlic</em>/ Ajo
                tr
                  td.tb1bd.tb2bd <em>Liter</em>
                  td.tb1bd Litro
                  td.tb1bd <em>Drinks</em> / Bebidas
                tr
                  td.tb1bd.tb2bd <em>Gallon</em>
                  td.tb1bd Galón
                  td.tb1bd <em>Drinks</em> / Bebidas
                tr
                  td.tb1bd.tb2bd <em>Sack</em>
                  td.tb1bd Saco
                  td.tb1bd <em>Flour, corn</em> / Harina, maíz
                tr
                  td.tb1bd.tb2bd <em>Unit</em>
                  td.tb1bd Unidad
                  td.tb1bd <em>Fruits, vegetables</em> / Frutas, vegetales
                tr
                  td.tb1bd.tb2bd <em>Milliliters</em>
                  td.tb1bd Mililitros
                  td.tb1bd <em>Drinks</em> / Bebidas
          .bgr.p-4
            .d-flex.justify-content-center
              Audio.color-acento-contenido.mx-3(
                :audio="require('@/assets/curso/audios/1/1.mp3')"
                @audio-hover="mostrarIndicadorAudio = false"
              )
                .indicador--click(v-if="mostrarIndicadorAudio")      

      .row.d-flex.justify-content-center.align-items-end.pst_1
        .col-12.col-md-4.mb-3.mb-md-0(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema1/t1-2.png', alt='hombre con una idea y un computador')    
        .col-12.col-md-4
          p Para verificar el significado y pronunciación del vocabulario dispuesto, puede hacer uso de herramientas en línea, como
          .row
            .col-12.col-md-6
              a.anexo.pst.mb-4.mb-lg-0(href="https://www.linguee.es/" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  p Linguee
            .col-12.col-md-6
              a.anexo.pst.mb-4.mb-lg-0(href="https://www.wordreference.com/" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  p Wordreference
          p.mb-0 que le permiten escuchar, definir y apropiar vocabulario en inglés.	

    p Un ejemplo donde se emplean las medidas o cantidades de un producto o alimento son las recetas de cocina, en las cuales se especifica la cantidad de cada ingrediente a utilizar. Por ejemplo, para hacer  ponquecitos <em>(cupcakes)</em>:

    .bg_grad-03
      .row.p-5.d-flex.justify-content-center.align-items-center
        .col-12.col-md-6.mb-3.mb-md-0
          p.text-bold.mb-3.mb-md-5.colr_2 Ingredients needed  / Ingredientes necesarios:
          .row.mb-3.mb-md-5 
            .col-12.col-md-6.mb-3.mb-md-0
              p.mb-0 <b><em>English</em> / Inglés</b>
              p.mb-0 ●	1/4 kilo of flour 
              p.mb-0 ●	120 grams of butter
              p.mb-0 ●	Two fresh eggs
              p.mb-0 ●	125 ml of milk
              p.mb-0 ●	230 grams of sugar
              p.mb-0 ●	1 teaspoon of essence of vanilla
              p.mb-0 ●	2 teaspoons of yeast
            .col-12.col-md-6
              p.mb-0 <b><em>Spanish</em> / Español</b>
              p.mb-0 ●	1/4 kilo de harina
              p.mb-0 ●	120 gramos de mantequilla 
              p.mb-0 ●	Dos huevos frescos
              p.mb-0 ●	125 ml de leche
              p.mb-0 ●	230 gramos de azúcar
              p.mb-0 ●	1 cucharadita de esencia de vainilla
              p.mb-0 ●	2 cucharaditas de levadura
          .d-flex
            Audio.color-acento-contenido.mx-3(
              :audio="require('@/assets/curso/audios/1/2.mp3')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio") 
            p.d-flex.align-items-center.text-bold.mb-0.colr_2 <em>Cupcakes recipe</em>  / Receta de ponquecitos
        .col-12.col-md-4
          figure
            img(src='@/assets/curso/tema1/t1-3.png', alt='Cupcake rosado')

    separador

    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1  <em>In the restaurant</em> / En el restaurante 

    p Observe con atención el siguiente diálogo:

    figure.mb-5.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    p.d-flex.justify-content-center Luego, escuche y complete: 

    Dialogo.color-primario(:dialogo="dialogo")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Titulo de actividad - Completa la conversación.
      template(#descripcion-actividad) Arrastra y suelta el cada una de las palabras en el orden correcto.
    
    separador

    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2  <em>At the mall</em> / En el centro comercial

    p.mb-5 Ahora, revise el vocabulario que se puede encontrar en un centro comercial:

    .row.d-flex.justify-content-end
      .col-12.col-md-11
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2
          span <em>There are many stores in a mall.</em> / Hay muchas tiendas en un centro comercial.

    SlyderF.slyder-arrows.mb-5(columnas="col-lg-6 col-xl-2")(data-aos="fade-left")
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-6.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Bakery
            br
            | (Panadería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-7.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Bookstores
            br
            | (Librerías)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-8.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Candy store
            br
            | (Dulcería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-9.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Clothing stores
            br
            | (Tiendas de ropa)
      .tarjeta.p-3.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-10.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Department stores
            br
            | (Tiendas por departamentos)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-11.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Drugstores
            br
            | (Farmacias)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-6.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Electronic stores
            br
            | (Tiendas de electrónicos)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-13.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Furniture store
            br
            | (Mueblerías)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-14.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Ice cream shop
            br
            | (Heladería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-6.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Jewelry store
            br
            | (Tiendas de bisutería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-16.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Laundry
            br
            | (Lavandería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-17.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Lingerie stores
            br
            | (Tiendas de lencería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-18.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-2.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Minimarket
            br
            | (Minimercado)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-19.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Music stores
            br
            | (Tiendas de música)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-20.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Shoe store
            br
            | (Zapatería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-21.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-2.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Supermarket
            br
            | (Supermercado)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-22.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Toy stores
            br
            | (Jugueterías)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-23.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold <em>Movie theater</em> / cinema
            br
            | (Cine)

    .row.d-flex.justify-content-center.mb-5
      .col-12.col-md-10.bgr_1.p-4
        .d-flex
          Audio.color-acento-contenido.mx-3(
            :audio="require('@/assets/curso/audios/1.2/1.mp3')"
            @audio-hover="mostrarIndicadorAudio = false"
          )
            .indicador--click(v-if="mostrarIndicadorAudio") 
          p.d-flex.align-items-center.mb-0 Listen and repeat 

    .bg_grad-04
      .row.p-5.d-flex.justify-content-center
        .col-12.col-md-5.d-flex.align-items-center
          p.mb-0 Seguidamente, se presentan una serie de situaciones a las cuales puede dar respuesta de acuerdo con el vocabulario señalado anteriormente:
        .col-12.col-md-5
          SlyderF.mb-5(columnas="col-lg-12 col-xl-12")
            .tarjeta.bgr_2.p-4
              .bgr_3
                Traduccion.color-primario(:dialogo="traduccion")

          



</template>

<script>
import Traduccion from '../components/Traduccion.vue'
export default {
  name: 'Tema1',
  components: {
    Traduccion,
  },
  data: () => ({
    mostrarIndicadorAudio: true,
    dialogo: {
      personajes: [
        {
          nombre: 'Paula',
          img: require('@/assets/curso/tema1/t1-4.svg'),
        },
        {
          nombre: 'Matthew',
          img: require('@/assets/curso/tema1/t1-5.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Paula',
          textoIng: 'Question 1: Where are Merly and Luis?',
          textoEsp: 'Pregunta 1: ¿Dónde están Merly y Luis?',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'they are in a ***',
          textoEsp: 'estan en un ***',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
          palabra: 'restaurant',
        },
        {
          personaje: 'Paula',
          textoIng: 'Question 2: What does Luis want to eat at the restaurant?',
          textoEsp: 'Pregunta 2: ¿Qué quiere comer Luis en el restaurante?',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'He wants to eat *** and a side order of fries.',
          textoEsp: 'Quiere comer *** y una guarnición de papas fritas.',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
          palabra: 'grilled steak',
        },
        {
          personaje: 'Paula',
          textoIng: 'Question 3: What does Luis want to eat at the restaurant?',
          textoEsp: 'Pregunta 3: ¿Qué quiere comer Merly en el restaurante?',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'Merly wants to eat grilled steak too and a ***',
          textoEsp:
            'Merly también quiere comer un bistec a la parrilla y una ***',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
          palabra: 'salad',
        },
        {
          personaje: 'Paula',
          textoIng: 'Question 4: What do they drink at the restaurant?',
          textoEsp: 'Pregunta 4: ¿Qué beben en el restaurante?',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'Merly and Luis drink a *** of red wine.',
          textoEsp: 'Merly y Luis beben una *** de vino tinto',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
          palabra: 'glass',
        },
      ],
    },
    traduccion: {
      dialogo: [
        {
          textoIng:
            'Susan wants to buy a pair of sandals. Answer: She goes to a    shoe store.',
          textoEsp:
            'Susan quiere comprar un par de sandalias. Respuesta: Ella va a una zapatería.',
          audio: require('@/assets/curso/audios/1.1/1.mp3'),
        },
      ],
    },
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
