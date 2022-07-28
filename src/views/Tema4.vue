<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 4
      h1 Plural de sustantivos regulares e irregulares

    .row.mb-5.d-flex.align-items-center
      .col-12.col-md-3.bgr_24.p-4
        figure
          img(src='@/assets/curso/tema4/t4-1.svg', alt='Texto que describa la imagen')  
      .col-12.col-md-9.bg_grad-13.p-5
        p En el idioma inglés, los sustantivos pueden presentarse en singular o en plural. Cuando se refieren a una sola cosa, persona u objeto, se dice que está en número singular. Si hay dos o más objetos, personas o cosas, se dice que el sustantivo está en número plural.
        p.mb-0 Con base en lo planteado, se establece una clasificación para los nombres o sustantivos en: sustantivos regulares y sustantivos irregulares.

    separador

    #t_4_1.titulo-segundo.color-acento-contenido
      h2 4.1 Plural de sustantivos regulares
    
    P.mb-5 Existe una gran cantidad de nombres o sustantivos que se clasifican como regulares en el idioma inglés, porque forman el plural añadiendo simplemente una <b>S</b> al final de la palabra. Por ejemplo:

    .bg_grad-15
      .row.mb-5
        .col-12.col-md-4.mb-3.mb-md-0
          .bgr_26.pst_4.d-flex.justify-content-end
            .bgr_27.p-4
              div
                Audio.color-acento-contenido.pst_5(
                  :audio="require('@/assets/curso/audios/4.1/1.mp3')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.colr_2.text-bold.text-center <em>House - Houses</em>
                p.mb-0.text-center Casa - Casas
        .col-12.col-md-4.mb-3.mb-md-0
          .bgr_28.pst_4.d-flex.justify-content-end
            .bgr_27.p-4
              div
                Audio.color-acento-contenido.pst_5(
                  :audio="require('@/assets/curso/audios/4.1/2.mp3')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.colr_2.text-bold.text-center <em>Flower - Flowers</em>
                p.mb-0.text-center Flor - Flores
        .col-12.col-md-4
          .bgr_29.pst_4.d-flex.justify-content-end
            .bgr_27.p-4
              div
                Audio.color-acento-contenido.pst_6(
                  :audio="require('@/assets/curso/audios/4.1/3.mp3')"
                  @audio-hover="mostrarIndicadorAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorAudio")
                p.mb-0.colr_2.text-bold.text-center <em>Cat - Cats</em>
                p.mb-0.text-center Gato - Gatos
    
      p.mb-5 Esta estructura gramatical, referida al plural de los sustantivos regulares, es muy sencilla y depende de la terminación del sustantivo, que puede ser una vocal o una consonante:

      .row.d-flex.justify-content-center.mb-5
        .col-12.col-md-7
          .titulo-sexto.color-acento-contenido
            h5 Tabla 3
            span Formación del plural de sustantivos regulares

          .tabla1.color-acento-botones.mb-lg-0
            table.text-center.w-100
              tbody
                tr.bgt1header
                  td.t1br Sustantivo regular
                  td.t1br + s
                  td.t1br Plural
                  td.td1bd Traducción
                tr
                  td.tb1bd.tb2bd <em>Table</em>
                  td(rowspan=6).tb1bd + s
                  td.tb1bd <em>Tables</em>
                  td.tb1bd Mesas
                tr
                  td.tb1bd.tb2bd <em>Chair</em>
                  td.tb1bd <em>Chairs</em>
                  td.tb1bd Sillas
                tr
                  td.tb1bd.tb2bd <em>Office</em>
                  td.tb1bd <em>Offices</em>
                  td.tb1bd Oficinas
                tr
                  td.tb1bd.tb2bd <em>Book</em>
                  td.tb1bd <em>Books</em>
                  td.tb1bd Libros
                tr
                  td.tb1bd.tb2bd <em>Dog</em>
                  td.tb1bd <em>Dogs</em>
                  td.tb1bd Perros
                tr
                  td.tb1bd.tb2bd <em>Skirt</em>
                  td.tb1bd <em>Skirts</em>
                  td.tb1bd Faldas
                
          .bgr.p-4
            .d-flex.justify-content-center
              Audio.color-acento-contenido.mx-3(
                :audio="require('@/assets/curso/audios/4.1/4.mp3')"
                @audio-hover="mostrarIndicadorAudio = false"
              )
                .indicador--click(v-if="mostrarIndicadorAudio")     

      p.mb-5.text-center Al formar una oración con el plural de estos sustantivos, se tiene: 

      .row.mb-5
        .col-12.col-md-6.d-flex.align-items-center.mb-3.mb-md-0(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema4/t4-5.jpg', alt='Texto que describa la imagen')
        .col-12.col-md-6
          .bgr_30.p-5
            SlyderE.bg_grad-16(indicadores="derecha")
              .row.d-flex.align-items-center
                .col-md-8.mb-4.mb-md-0.px-5
                  TarjetaAudio.color-acento-contenido.bgr_31.my-3(
                    texto="<i><span1>The tables are green.</span1></i>"
                      :audio="require('@/assets/curso/audios/4.1/5.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )                    
                  p.mb-0 Las mesas son verdes.  
                .col-md-4
                  figure
                    img.d-none.d-md-flex(src='@/assets/curso/tema4/t4-6.svg', alt='Texto que describa la imagen')
              .row.d-flex.align-items-center
                .col-md-8.mb-4.mb-md-0.px-5
                  TarjetaAudio.color-acento-contenido.bgr_31.my-3(
                    texto="<i><span1>The dogs walk in the park.</span1></i>"
                      :audio="require('@/assets/curso/audios/4.1/6.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )                    
                  p.mb-0 Los perros caminan en el parque.
                .col-md-4
                  figure
                    img.d-none.d-md-flex(src='@/assets/curso/tema4/t4-6.svg', alt='Texto que describa la imagen')
              .row.d-flex.align-items-center
                .col-md-8.mb-4.mb-md-0.px-5
                  TarjetaAudio.color-acento-contenido.bgr_31.my-3(
                    texto="<i><span1>The offices are comfortable.</span1></i>"
                      :audio="require('@/assets/curso/audios/4.1/7.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )                    
                  p.mb-0 Las oficinas son cómodas.
                .col-md-4
                  figure
                    img.d-none.d-md-flex(src='@/assets/curso/tema4/t4-6.svg', alt='Texto que describa la imagen')
              .row.d-flex.align-items-center
                .col-md-8.mb-4.mb-md-0.px-5
                  TarjetaAudio.color-acento-contenido.bgr_31.my-3(
                    texto="<i><span1>Those books are interesting.</span1></i>"
                      :audio="require('@/assets/curso/audios/4.1/8.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )                    
                  p.mb-0 Esos libros son interesantes.
                .col-md-4
                  figure
                    img.d-none.d-md-flex(src='@/assets/curso/tema4/t4-6.svg', alt='Texto que describa la imagen')
    
    separador

    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2 Plural de sustantivos irregulares

    p En inglés, cuando un sustantivo es irregular, significa que el plural se forma de diversas maneras, lo que va a depender de la letra final de ese sustantivo.
    p.mb-5 Por lo anterior, revise las condiciones que se dan de acuerdo con su terminación y forma: 

    .row
      .col-12.col-md-8  
        .bgr_32.p-3.p-md-5
          SlyderA.bgr_3.p-3.p-md-5.pst_9(tipo="b")
            div
              p Cuando el sustantivo termina en <b>ch, s, sh, x</b> o en <b>z</b>, para formar el plural, se le añade al final  <b><em>“es”</em></b>. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br <em>+es</em>
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Lunch</em>
                      td(rowspan=7).tb1bd <em>+es</em>
                      td.tb1bd <em>Lunches</em>
                      td.tb1bd Almuerzos
                    tr
                      td.tb1bd.tb2bd <em>Dress</em>
                      td.tb1bd <em>Dresses</em>
                      td.tb1bd Vestidos
                    tr
                      td.tb1bd.tb2bd <em>Watch</em>
                      td.tb1bd <em>Watches</em>
                      td.tb1bd Relojes
                    tr
                      td.tb1bd.tb2bd <em>Box</em>
                      td.tb1bd <em>Boxes</em>
                      td.tb1bd Cajas
                    tr
                      td.tb1bd.tb2bd <em>Brush</em>
                      td.tb1bd <em>Brushes</em>
                      td.tb1bd Cepillos
                    tr
                      td.tb1bd.tb2bd <em>Quiz</em>
                      td.tb1bd <em>Quizzes</em>
                      td.tb1bd Cuestionarios
                    tr
                      td.tb1bd.tb2bd <em>Tomato</em>
                      td.tb1bd <em>Tomatoes</em>
                      td.tb1bd Tomates
                    
              .bgr.p-4
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/1.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio")
            div
              p Cuando el sustantivo termina en consonante seguida de la letra “y”, para formar el plural, se le añade al final  <b><em>“ies”</em></b>.  Es decir, se cambia la <b>“y”</b> por <b>“i”</b> y se añade es. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br <em>+ies</em>
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Baby</em>
                      td(rowspan=5).tb1bd <em>+ies</em>
                      td.tb1bd <em>Babies</em>
                      td.tb1bd Bebés
                    tr
                      td.tb1bd.tb2bd <em>Body</em>
                      td.tb1bd <em>Bodies</em>
                      td.tb1bd Cuerpos
                    tr
                      td.tb1bd.tb2bd <em>Fly</em>
                      td.tb1bd <em>Flies</em>
                      td.tb1bd Moscas
                    tr
                      td.tb1bd.tb2bd <em>Lady</em>
                      td.tb1bd <em>Ladies</em>
                      td.tb1bd Damas
                    tr
                      td.tb1bd.tb2bd <em>Laundry</em>
                      td.tb1bd <em>Laundries</em>
                      td.tb1bd Lavanderías
              .bgr.p-4
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/2.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio") 
            div
              p Cuando el sustantivo termina en <b><em>“sis”</em></b>,  para formar el plural, se le añade al final <b><em>“ses”</em></b>.  Es decir, se cambia la <b><em>“sis”</em></b> por <b><em>“ses”</em></b>. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br <em>+ses</em>
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Basis</em>
                      td(rowspan=4).tb1bd <em>+ses</em>
                      td.tb1bd <em>Bases</em>
                      td.tb1bd Bases
                    tr
                      td.tb1bd.tb2bd <em>Crisis</em>
                      td.tb1bd <em>Crises</em>
                      td.tb1bd Crisis
                    tr
                      td.tb1bd.tb2bd <em>Axis</em>
                      td.tb1bd <em>Axes</em>
                      td.tb1bd Ejes
                    tr
                      td.tb1bd.tb2bd <em>Oasis</em>
                      td.tb1bd <em>Oases</em>
                      td.tb1bd Oasis
              .bgr.p-4
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/3.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio") 
            div
              p Cuando el sustantivo termina en consonante <b><em>“f”</em></b> o en <b><em>“fe”</em></b>, para formar el plural, se le añade al final <b><em>“ves”</em></b>.  Es decir, se cambia la <b><em>“f”</em></b> por <b><em>“v”</em></b> y se añade <b><em>“es”</em></b>. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br <em>+ves</em>
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Life</em>
                      td(rowspan=5).tb1bd <em>+ves</em>
                      td.tb1bd <em>Lives</em>
                      td.tb1bd Vidas
                    tr
                      td.tb1bd.tb2bd <em>Wife</em>
                      td.tb1bd <em>Wives</em>
                      td.tb1bd Esposas
                    tr
                      td.tb1bd.tb2bd <em>Wolf</em>
                      td.tb1bd <em>Wolves</em>
                      td.tb1bd Lobos
                    tr
                      td.tb1bd.tb2bd <em>Knife</em>
                      td.tb1bd <em>Knives</em>
                      td.tb1bd Cuchillos
                    tr
                      td.tb1bd.tb2bd <em>Thief</em>
                      td.tb1bd <em>Thieves</em>
                      td.tb1bd Ladrones
              .bgr.p-4.mb-3
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/4.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio") 
              p Debe indicarse que no todas las palabras que tienen la terminación <b><em>f</em></b> o <b><em>fe</em></b> siguen esta regla, existen algunos sustantivos con estas terminaciones que forman el plural de manera regular. Por ejemplo:
              .row  
                .col-12.col-md-4.text-center
                  p.mb-0 <b><em>Chef - Chefs</em></b>
                  p Cocinero - Cocineros
                .col-12.col-md-4.text-center
                  p.mb-0 <b><em>Giraffe - Giraffes</em></b>
                  p Jirafa - Jirafas
                .col-12.col-md-4.text-center
                  p.mb-0 <b><em>Gulf - Gulfs</em></b>
                  p Golfo - Golfos
            div
              p Cuando el sustantivo termina en <b>“o”</b>, para formar el plural, se le añade al final <b><em>“es”</em></b>. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br <em>+oes</em>
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Potato</em>
                      td(rowspan=5).tb1bd <em>+oes</em>
                      td.tb1bd <em>Potatoes</em>
                      td.tb1bd Papas
                    tr
                      td.tb1bd.tb2bd <em>Echo</em>
                      td.tb1bd <em>Echoes</em>
                      td.tb1bd Ecos
                    tr
                      td.tb1bd.tb2bd <em>Hero</em>
                      td.tb1bd <em>Heroes</em>
                      td.tb1bd Héroes
                    tr
                      td.tb1bd.tb2bd <em>Domino</em>
                      td.tb1bd <em>Dominoes</em>
                      td.tb1bd Dominós
                    tr
                      td.tb1bd.tb2bd <em>Zero</em>
                      td.tb1bd <em>Zeroes</em>
                      td.tb1bd Ceros
              .bgr.p-4.mb-3
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/5.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio")
            div
              p Algunas palabras en idioma inglés presentan la misma forma tanto en singular como en plural, es decir, permanecen iguales, y muchas de estas palabras están referidas a animales. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br +
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Deer</em>
                      td(rowspan=5).tb1bd -
                      td.tb1bd <em>Deer</em>
                      td.tb1bd Ciervo/ciervos
                    tr
                      td.tb1bd.tb2bd <em>Moose</em>
                      td.tb1bd <em>Moose</em>
                      td.tb1bd Alce/alces
                    tr
                      td.tb1bd.tb2bd <em>Sheep</em>
                      td.tb1bd <em>Sheep</em>
                      td.tb1bd Oveja/ovejas
                    tr
                      td.tb1bd.tb2bd <em>Fish</em>
                      td.tb1bd <em>Fish</em>
                      td.tb1bd Pez/peces
                    tr
                      td.tb1bd.tb2bd <em>Swine</em>
                      td.tb1bd <em>Swine</em>
                      td.tb1bd Cerdo/cerdos
              .bgr.p-4.mb-3
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/6.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio")
            div
              p Por otra parte, hay algunas palabras en idioma inglés que tienen un plural irregular, es decir, que cambian por completo cuando están en plural. Por ejemplo:
              .tabla1.color-acento-botones.mb-lg-0
                table.text-center.w-100
                  tbody
                    tr.bgt1header
                      td.t1br Sustantivo regular
                      td.t1br +
                      td.t1br Plural
                      td.td1bd Traducción
                    tr
                      td.tb1bd.tb2bd <em>Man</em>
                      td(rowspan=9).tb1bd -
                      td.tb1bd <em>Men</em>
                      td.tb1bd Hombres
                    tr
                      td.tb1bd.tb2bd <em>Woman</em>
                      td.tb1bd <em>Women</em>
                      td.tb1bd Mujeres
                    tr
                      td.tb1bd.tb2bd <em>Foot</em>
                      td.tb1bd <em>Feet</em>
                      td.tb1bd Pies
                    tr
                      td.tb1bd.tb2bd <em>Mouse</em>
                      td.tb1bd <em>Mice</em>
                      td.tb1bd Ratones
                    tr
                      td.tb1bd.tb2bd <em>Tooth</em>
                      td.tb1bd <em>Teeth</em>
                      td.tb1bd Dientes
                    tr
                      td.tb1bd.tb2bd <em>Louse</em>
                      td.tb1bd <em>Lice</em>
                      td.tb1bd Piojos
                    tr
                      td.tb1bd.tb2bd <em>Person</em>
                      td.tb1bd <em>People</em>
                      td.tb1bd Personas
                    tr
                      td.tb1bd.tb2bd <em>Die</em>
                      td.tb1bd <em>Dice</em>
                      td.tb1bd Dados
                    tr
                      td.tb1bd.tb2bd <em>Child</em>
                      td.tb1bd <em>Children</em>
                      td.tb1bd Niños

              .bgr.p-4.mb-3
                .d-flex.justify-content-center
                  Audio.color-acento-contenido.mx-3(
                    :audio="require('@/assets/curso/audios/4.2/7.mp3')"
                    @audio-hover="mostrarIndicadorAudio = false"
                  )
                    .indicador--click(v-if="mostrarIndicadorAudio")

      .col-12.col-md-4(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/tema4/t4-7.svg', alt='Texto que describa la imagen') 



              
                 





    
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
