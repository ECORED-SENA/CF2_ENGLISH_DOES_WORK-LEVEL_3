<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 5
      h1 Expresiones de cantidad - <em>I want a bit of cake!</em> 
    
    .bg_grad-12.mb-5
      .row
        .col-12.col-md-2.mb-3.mb-md-0(data-aos="zoom-in")
          figure.d-flex.justify-content-center
            img.img140(src='@/assets/curso/tema5/t5-1.svg', alt='recuadros con letras')
        .col-12.col-md-10.d-flex.align-items-center
          p.mb-0 Para indicar cantidades, se utilizan ciertas expresiones que permiten conocer o definir el nombre o sustantivo, como lo hacen los artículos. Por ende, estas expresiones  de cantidad se ubican antes del sustantivo en la oración. Algunos de los cuantificadores más utilizados son: <em>much, many, a lot of y little.</em>
    
    p.mb-5 A continuación, se detalla el uso de cada una de las expresiones:

    TabsA.color-acento-botones.mb-5
      .tarjeta.color-acento-botones--borde.p-4(titulo="Uso de la expresión <em>“much”</em>")
        h4.colr_2 Uso de la expresión <em>“much”</em>
        p Esta es una expresión cuantificadora que se utiliza al hablar de sustantivos incontables en mucha cantidad. Se utiliza en oraciones afirmativas, negativas e interrogativas, pero generalmente se utiliza en frases u oraciones negativas e interrogativas con nombres incontables en singular. 
        p.text-bold <em>For example:</em>
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-2.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>How much <b>money</b> does he have?</span1></i>"
                :audio="require('@/assets/curso/audios/5/1.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 ¿Cuánto dinero tiene él?
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-3.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Nelly doesn’t have much <b>time</b> left. </span1></i>"
                :audio="require('@/assets/curso/audios/5/2.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 A Nelly no le queda mucho tiempo.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-4.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>You don’t need much <b>food.</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/3.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Ustedes no necesitan mucha comida.
        .row.d-flex.justify-content-center
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-5.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>How much <b>time</b> does he need to do the work?</span1></i>"
                :audio="require('@/assets/curso/audios/5/4.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 ¿Cuánto tiempo necesita él para hacer el trabajo?
      .tarjeta.color-acento-botones--borde.p-4(titulo="Uso de la expresión <em>“many”</em>")
        h4.colr_2 Uso de la expresión <em>“many”</em>
        p Este cuantificador permite expresar una gran cantidad de nombres contables en plural, en el idioma inglés. Se utiliza, generalmente, en oraciones o frases negativas e interrogativas con el nombre contable en plural.  
        p.text-bold <em>For example:</em>
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-6.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>How many <b>dogs</b> do you have?</span1></i>"
                :audio="require('@/assets/curso/audios/5/5.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 ¿Cuántos perros tienes?
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-7.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>They have many <b>apples</b> in the basket.</span1></i>"
                :audio="require('@/assets/curso/audios/5/6.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Ellos tienen muchas manzanas en la cesta.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-8.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>How many <b>oranges</b> do you buy at the market? </span1></i>"
                :audio="require('@/assets/curso/audios/5/7.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 ¿Cuántas naranjas compras en el mercado?
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-9.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>There are many <b>cars</b> on the avenue.</span1></i>"
                :audio="require('@/assets/curso/audios/5/8.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Hay muchos carros en la avenida.
      .tarjeta.color-acento-botones--borde.p-4(titulo="Uso de la expresión <em>“a lot of”</em>")
        h4.colr_2 Uso de la expresión <em>“a lot of”</em>
        p Este cuantificador puede usarse con nombres o sustantivos contables e incontables, resulta más informal y no se usa en oraciones interrogativas.   
        p.text-bold <em>For example:</em>
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-10.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Carol has a lot of <b>books.</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/9.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Carol tiene muchos libros.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-11.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Sue and Mark have a lot of <b>money.</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/10.mp3')"  
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Sue y Mark tienen mucho dinero.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-12.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Merly has not a lot of <b>books.</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/11.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Merly no tiene muchos libros.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-13.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Cleo has a lot of <b>toys.</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/12.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Cleo tiene muchos juguetes.
      .tarjeta.color-acento-botones--borde.p-4(titulo="Uso de la expresión <em>“a little”</em>")
        h4.colr_2 Uso de la expresión <em>“a little”</em>
        p Este cuantificador puede usarse con nombres o sustantivos contables e incontables, resulta más informal y no se usa en oraciones interrogativas.   
        p.text-bold <em>For example:</em>
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-5.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>They have little <b>time.</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/13.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Ellos tienen poco tiempo.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-3.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Do you have a little <b>Money?</b></span1></i>"
                :audio="require('@/assets/curso/audios/5/14.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 ¿Tienes un poco de dinero?
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-14.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Does Shirley eat a little <b>piece of meat?</b> </span1></i>"
                :audio="require('@/assets/curso/audios/5/15.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 ¿Come Shirley un pedacito de carne?
      .tarjeta.color-acento-botones--borde.p-4(titulo="Uso de la expresión <em>“too much”</em>")
        h4.colr_2 Uso de la expresión <em>“too much”</em>
        p Sirve para denotar un grado más allá de lo normal en un sustantivo. En general, puede señalarse que <em>“too much”</em> se usa con sustantivos incontables, como <em>water</em> (agua), <em>sugar</em> (azúcar), <em>pressure</em> (presión).  
        p.text-bold <em>For example:</em>
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-15.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>They drank too much <b>gin</b> last night.</span1></i>"
                :audio="require('@/assets/curso/audios/5/16.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Ellos tomaron demasiada ginebra anoche.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-16.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>That is too much <b>water</b> for you. </span1></i>"
                :audio="require('@/assets/curso/audios/5/17.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Esa es mucha agua para ti.
        .row.d-flex.justify-content-center.mb-3
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-17.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>There was too much <b>violence</b> in the camp. </span1></i>"
                :audio="require('@/assets/curso/audios/5/18.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Había demasiada violencia en el campo.
        p Debe acotarse que, en algunas ocasiones, <em>“too much”</em> se utiliza sin un sustantivo acompañante, para expresar que algo es demasiado: 
        .row  
          .col-12.col-md-4
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>You worry too much.</span1></i>"
                :audio="require('@/assets/curso/audios/5/19.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Te preocupas demasiado.
          .col-12.col-md-4
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>He loves her too much.</span1></i>"
                :audio="require('@/assets/curso/audios/5/20.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Él la ama demasiado.
          .col-12.col-md-4
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Mary studies too much.</span1></i>"
                :audio="require('@/assets/curso/audios/5/21.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Mary estudia demasiado.
      .tarjeta.color-acento-botones--borde.p-4(titulo="Uso de la expresión <em>“too many”</em>")
        h4.colr_2 Uso de la expresión <em>“too many”</em>
        p Sirve para denotar un grado más allá de lo normal en un sustantivo, pero, en este caso, <em>“too many”</em> se utiliza con sustantivos contables en plural, como <em>oranges</em> (naranjas), <em>ships</em> (barcos), <em>boxes</em> (cajas), entre otros.   
        p.text-bold <em>For example:</em>
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-18.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>She has too many <b>friends</b> on Whatsapp.</span1></i>"
                :audio="require('@/assets/curso/audios/5/22.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Ella tiene demasiados amigos en <em>Whatsapp</em>.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-19.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>Mary has too many <b>oranges</b> in the basket; she has more than 30.</span1></i>"
                :audio="require('@/assets/curso/audios/5/23.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Mary tiene demasiadas naranjas en la cesta; ella tiene más de 30.
        .row.d-flex.justify-content-center.mb-3.mb-md-0
          .col-12.col-md-2.mb-3.mb-md-0
            figure
              img(src='@/assets/curso/tema5/t5-12.svg', alt='Texto que describa la imagen')
          .col-12.col-md-5
            TarjetaAudio.color-acento-contenido.bgr_33.my-3(
              texto="<i><span1>There are too many <b>books</b> in the desk.</span1></i>"
                :audio="require('@/assets/curso/audios/5/24.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0 Hay demasiados libros en el escritorio.


</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({}),
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
