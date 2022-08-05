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
        .col-12.col-md-4.mb-3.mb-md-0(data-aos="zoom-in")
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
            span <em>Food and amounts</em> / Alimentos y cantidades

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
          p.text-bold.mb-3.mb-md-5.colr_2 <em>Ingredients needed</em>  / Ingredientes necesarios:
          .row.mb-3.mb-md-5 
            .col-12.col-md-6.mb-3.mb-md-0
              p.mb-0 <b><em>English</em> / Inglés</b>
              p.mb-0 ●	<em>1/4 kilo of flour</em> 
              p.mb-0 ●	<em>120 grams of butter</em>
              p.mb-0 ●	<em>Two fresh eggs</em>
              p.mb-0 ●	<em>125 ml of milk</em>
              p.mb-0 ●	<em>230 grams of sugar</em>
              p.mb-0 ●	<em>1 teaspoon of essence of vanilla</em>
              p.mb-0 ●	<em>2 teaspoons of yeast</em>
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
        iframe(width="560" height="315" src="https://www.youtube.com/embed/UeAg1HDMYrg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    p.d-flex.justify-content-center Luego, escuche y complete: 

    Dialogo.color-primario(:dialogo="dialogo")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Completa la conversación.
      template(#descripcion-actividad) Arrastra y suelta cada una de las palabras en el orden correcto.
    
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
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-6.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Bakery
            br
            | (Panadería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-7.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Bookstores
            br
            | (Librerías)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-8.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Candy store
            br
            | (Dulcería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-9.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Clothing stores
            br
            | (Tiendas de ropa)
      .tarjeta.p-3.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-10.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Department stores
            br
            | (Tiendas por departamentos)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-11.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Drugstores
            br
            | (Farmacias)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-12.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Electronic stores
            br
            | (Tiendas de electrónicos)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-13.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Furniture store
            br
            | (Mueblerías)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-14.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Ice cream shop
            br
            | (Heladería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-15.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Jewelry store
            br
            | (Tiendas de bisutería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-16.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Laundry
            br
            | (Lavandería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-17.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Lingerie stores
            br
            | (Tiendas de lencería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-18.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-2.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Minimarket
            br
            | (Minimercado)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-19.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Music stores
            br
            | (Tiendas de música)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-20.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Shoe store
            br
            | (Zapatería)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-21.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-2.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Supermarket
            br
            | (Supermercado)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-22.png')})`}" style='height: 394px')
        .tarjeta.bg-white.p-3.w-100.text-small
          p.mb-0.text-center
            span.colr_2.r-3.fst-italic.fw-bold Toy stores
            br
            | (Jugueterías)
      .tarjeta.p-4.d-flex.align-items-end.tarjeta-bg.pst_8(:style="{'background-image': `url(${require('@/assets/curso/tema1/t1-23.png')})`}" style='height: 394px')
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
            .tarjeta.bgr_2.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo1")
            .tarjeta.bgr_4.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo2")
            .tarjeta.bgr_5.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo3")
            .tarjeta.bgr_6.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo4")
            .tarjeta.bgr_7.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo5")
            .tarjeta.bgr_8.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo6")
            .tarjeta.bgr_9.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo7")
            .tarjeta.bgr_10.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo8")
            .tarjeta.bgr_11.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo9")
            .tarjeta.bgr_12.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo10")
            .tarjeta.bgr_13.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo11")
            .tarjeta.bgr_14.p-3.p-md-5
              .bgr_3.pst_2
                TraduccionAudio.color-acento-contenido.colr_3(:dialogo="dialogo12")
          



</template>

<script>
import Traduccion from '../components/Traduccion.vue'
import TraduccionAudio from '../components/TraduccionAudio.vue'
export default {
  name: 'Tema1',
  components: {
    Traduccion,
    TraduccionAudio,
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
          audio: require('@/assets/curso/audios/1.1/2.mp3'),
          palabra: 'restaurant',
        },
        {
          personaje: 'Paula',
          textoIng: 'Question 2: What does Luis want to eat at the restaurant?',
          textoEsp: 'Pregunta 2: ¿Qué quiere comer Luis en el restaurante?',
          audio: require('@/assets/curso/audios/1.1/3.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'He wants to eat *** and a side order of fries.',
          textoEsp: 'Quiere comer *** y una guarnición de papas fritas.',
          audio: require('@/assets/curso/audios/1.1/4.mp3'),
          palabra: 'grilled steak',
        },
        {
          personaje: 'Paula',
          textoIng:
            'Question 3: What does Merly want to eat at the restaurant? ',
          textoEsp: 'Pregunta 3: ¿Qué quiere comer Merly en el restaurante?',
          audio: require('@/assets/curso/audios/1.1/5.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'Merly wants to eat grilled steak too and a ***',
          textoEsp:
            'Merly también quiere comer un bistec a la parrilla y una ***',
          audio: require('@/assets/curso/audios/1.1/6.mp3'),
          palabra: 'salad',
        },
        {
          personaje: 'Paula',
          textoIng: 'Question 4: What do they drink at the restaurant?',
          textoEsp: 'Pregunta 4: ¿Qué beben en el restaurante?',
          audio: require('@/assets/curso/audios/1.1/7.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'Merly and Luis drink a *** of red wine.',
          textoEsp: 'Merly y Luis beben una *** de vino tinto',
          audio: require('@/assets/curso/audios/1.1/8.mp3'),
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
    dialogo1: [
      {
        textoIng:
          '<em>Susan wants to buy a</em> <i>pair of sandals.</i> <em>Answer: She goes to a</em> <b>shoe store.</b>',
        textoEsp:
          'Susan quiere comprar un par de sandalias. Respuesta: Ella va a una zapatería.',
        audio: require('@/assets/curso/audios/1.2/2.mp3'),
      },
    ],
    dialogo2: [
      {
        textoIng:
          '<em>Peter needs</em> <i>a black jacket.</i> <em>Answer: He visits the</em> <b>clothing store.</b>',
        textoEsp:
          'Peter necesita una chaqueta negra. Respuesta: Él visita la tienda de ropa. ',
        audio: require('@/assets/curso/audios/1.2/3.mp3'),
      },
    ],
    dialogo3: [
      {
        textoIng:
          '<em>Milly needs a</em> <i>Chemistry book.</i> <em>Answer: She goes to the </em> <b>library.</b>',
        textoEsp:
          'Milly necesita un libro de Química. Respuesta: Ella va a la biblioteca.',
        audio: require('@/assets/curso/audios/1.2/4.mp3'),
      },
    ],
    dialogo4: [
      {
        textoIng:
          '<em>Lia wants to buy a</em> <i>cake.</i> <em>Answer: She goes to the</em> <b>bakery</b>',
        textoEsp:
          'Lia quiere comprar una torta. Respuesta: Ella va a la panadería.',
        audio: require('@/assets/curso/audios/1.2/5.mp3'),
      },
    ],
    dialogo5: [
      {
        textoIng:
          '<em>I want to eat an</em> <i>ice cream.</i> <em>Answer: I go to the</em> <b>ice cream shop.</b>',
        textoEsp:
          'Yo quiero comer un helado. Respuesta: Yo voy a la heladería.',
        audio: require('@/assets/curso/audios/1.2/6.mp3'),
      },
    ],
    dialogo6: [
      {
        textoIng:
          '<em>Tom wants to buy an</em> <i>iPhone.</i> <em>Answer: He goes to the</em> <b>electronic store.</b>',
        textoEsp:
          'Tom quiere comprar un Iphone. Respuesta: Él va a la tienda de electrónicos.',
        audio: require('@/assets/curso/audios/1.2/7.mp3'),
      },
    ],
    dialogo7: [
      {
        textoIng:
          '<em>Sam needs to buy a</em> <i>chair.</i> <em>Answer: He goes to the </em> <b>furniture store.</b>',
        textoEsp:
          'Sam necesita comprar una silla. Respuesta: Él va a la mueblería.',
        audio: require('@/assets/curso/audios/1.2/8.mp3'),
      },
    ],
    dialogo8: [
      {
        textoIng:
          '<em>Lisa has to buy 200</em> <i>grams of cheese.</i> <em>Answer: She goes to the</em> <b>supermarket.</b>',
        textoEsp:
          'Lisa tiene que comprar 200 gramos de queso. Respuesta: Ella va al supermercado.',
        audio: require('@/assets/curso/audios/1.2/9.mp3'),
      },
    ],
    dialogo9: [
      {
        textoIng:
          '<em>George wants to buy a</em> <i>CD by Karol G.</i> <em>Answer: He goes to the</em> <b>music store.</b>',
        textoEsp:
          'George quiere comprar un CD de Karol G. Respuesta: Él va a la tienda de música',
        audio: require('@/assets/curso/audios/1.2/10.mp3'),
      },
    ],
    dialogo10: [
      {
        textoIng:
          '<em>Laura needs to buy a</em> <i>doll.</i> <em>Answer: She goes to the</em> <b>toy store.</b>',
        textoEsp:
          'Laura necesita comprar una muñeca. Respuesta: Ella va a la tienda de juguetes.',
        audio: require('@/assets/curso/audios/1.2/11.mp3'),
      },
    ],
    dialogo11: [
      {
        textoIng:
          '<em>They want to buy an engagement</em> <i>ring.</i> <em>Answer: They go to the </em> <b>jewelry.</b>',
        textoEsp:
          'Ellos quieren comprar un anillo de compromiso. Respuesta: Ellos van a la joyería.',
        audio: require('@/assets/curso/audios/1.2/12.mp3'),
      },
    ],
    dialogo12: [
      {
        textoIng:
          '<em>Marty wants to see a</em> <i>movie with his friends.</i> <em>Answer: He goes to the</em> <b>movie theater.</b>',
        textoEsp:
          'Marty quiere ver una película con sus amigos. Respuesta: Él va al cine.',
        audio: require('@/assets/curso/audios/1.2/13.mp3'),
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
