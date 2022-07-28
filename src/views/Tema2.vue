<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero.colr
        span 2
      h1 Expresiones de precios - <em>How much is it?</em>
    
    .bg_grad-05.mb-5
      .row.d-flex.justify-content-center
        .col-12.col-md-4.mb-3.mb-md-0(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema2/t2-1.png', alt='mujer con pulgares arriba')
        .col-12.col-md-7
          p Al ir de compras, las personas deben preguntar por el precio de las cosas que quieren comprar. Y para preguntar por el precio de algún objeto se utiliza la expresión <em>“How much”</em> y se acompaña del verbo <em>“to be”</em>.
          .row.mb-3
            .col-12.col-md-6(data-aos="fade")
              .tarjeta-avatar
                img.img90(src='@/assets/curso/tema2/t2-2.svg' alt='AvatarTop')
                .tarjeta.color-acento-botones
                  .text-white.p-4
                    p Si se trata de un solo objeto <b>(singular)</b>, se utiliza <em><b>“How much is…?</b></em> / ¿Cuánto cuesta…?
            .col-12.col-md-6(data-aos="fade")
              .tarjeta-avatar
                img.img90(src='@/assets/curso/tema2/t2-3.svg' alt='AvatarTop')
                .tarjeta.bgr_15
                  .p-4
                    p Si se trata de varios objetos <b>(plural)</b>, se utiliza: <em><b>“How much are…?</b></em> / ¿Cuánto cuestan…?
          p.text-center <b>Por ejemplo:</b>
          p.mb-0.text-center <em>How much is the shirt?</em> / ¿Cuánto cuesta la camisa?
          p.mb-0.text-center <em>How much are the tickets?</em> / ¿Cuánto cuestan las entradas?
    
    .bg_grad-06.mb-5
      .row.d-flex.justify-content-center
        .col-12.col-md-7.mb-3.mb-md-0
          p Para responder a la pregunta ¿Cuánto cuesta…?, se utiliza la misma estructura, pero en forma declarativa o afirmativa.
          p.colr_2 <b>Example:</b> 
          .row
            .col-12.col-md-6(data-aos="fade")
              .tarjeta-avatar
                img.img90(src='@/assets/curso/tema2/t2-4.svg' alt='AvatarTop')
                .tarjeta.color-acento-contenido
                  .text-white.p-4
                    p <em><b>Question: How much is the book?</b></em> / ¿Cuánto cuesta el libro?
                    p <em><b>Answer: The book is $50.</b></em> / El libro cuesta 50 dólares.
            .col-12.col-md-6(data-aos="fade")
              .tarjeta-avatar
                img.img90(src='@/assets/curso/tema2/t2-5.svg' alt='AvatarTop')
                .tarjeta.bgr_16
                  .p-4
                    p <em><b>Question: How much are the notebooks?</b></em> / ¿Cuánto cuestan los cuadernos?
                    p <em><b>Answer: The notebooks are $180.</b></em> / Los cuadernos cuestan 180 dólares.
        .col-12.col-md-4(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/tema2/t2-6.png', alt='mujer con pulgares arriba')
    
    p.mb-5 Ahora, revise algunas preguntas y respuestas de acuerdo con el siguiente contenido: 

    .bg_grad-07.mb-5
      p.text-center <em>Look at the following picture and pay attention to the given prices.</em>
      .row.d-flex.justify-content-center
        .col-12.col-md-11
          ImagenInfografica.color-acento-botones.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/tema2/t2-7.svg', alt='Texto que describa la imagen')
            .tarjeta.bgr_17.p-3(x="15.5%" y="30%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the bracelet?</span1></i><br><i><span1>The bracelet is $15. / It is $15.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/1.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="33%" y="30%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the ball?</span1></i><br><i><span1>The ball is $9. / It is $9.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/2.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="50.5%" y="30%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much are the skates?</span1></i><br><i><span1>The skates are $78. / They are $78.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/3.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="68%" y="30%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the laptop?</span1></i><br><i><span1>The laptop is $455. / It is $455.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/4.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="85.5%" y="30%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the dress?</span1></i><br><i><span1>The dress is $66. / It is $66.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/5.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")

            .tarjeta.bgr_17.p-3(x="15.5%" y="59%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the skirt?</span1></i><br><i><span1>The skirt is $31. / It is $31.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/6.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="33%" y="59%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the shirt?</span1></i><br><i><span1>The shirt is $43. / It is $43.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/7.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="50.5%" y="59%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much are the earrings?</span1></i><br><i><span1>The earrings are $12. / They are $12.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/8.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="68%" y="59%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the blouse?</span1></i><br><i><span1>The blouse is $25. / It is $25.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/9.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="85.5%" y="59%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the necklace?</span1></i><br><i><span1>The necklace is $29. / It is $29.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/10.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false") 

            .tarjeta.bgr_17.p-3(x="15.5%" y="88%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much are the jeans?</span1></i><br><i><span1>The jeans are $45. / They are $45.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/11.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="33%" y="88%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the wristwatch?</span1></i><br><i><span1>The wristwatch is $100. / It is $100.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/12.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="50.5%" y="88%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the T-shirt?</span1></i><br><i><span1>The T-shirt is $18. / It is $18.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/13.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="68%" y="88%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the ring?</span1></i><br><i><span1>The ring is $49. / It is $49.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/14.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")
            .tarjeta.bgr_17.p-3(x="85.5%" y="88%" numero="+")
              .bgr_18
                TarjetaAudio.color-acento-contenido(
                  texto="<i><span1>How much is the TV?</span1></i><br><i><span1>The TV is $899. / It is $899.</span1></i>"
                  :audio="require('@/assets/curso/audios/2/15.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false")   

    .row.pst_3              
      .col-12.col-md-5.mb-3.mb-md-0
        figure
          img(src='@/assets/curso/tema2/t2-8.jpg', alt='mujer con pulgares arriba')
      .col-12.col-md-7
        p.text-bold <em>A kind clerck</em> / Un empleado amable
        p Cuando se visita una tienda para comprar un producto que se necesita, existe una persona que recibe al cliente y lo atiende, preguntándole acerca de lo que requiere para poder darle información y mostrar los productos que ofrecen en la tienda, de manera que la experiencia del cliente sea agradable y lo motive a regresar.
        p El intercambio entre el cliente <em>(customer)</em> y el empleado <em>(clerk)</em> debe ser respetuoso, por lo que el empleado tratará de saber lo que necesita la persona que visita la tienda y actuará con prontitud, utilizando preguntas claves sobre el color y la talla, para que el cliente o usuario se sienta bien atendido. Seguidamente, se presenta un diálogo en la tienda <em>(store, shop)</em>, como se muestra a continuación:

    .bg_grad-08.mb-5
      .row.d-flex.align-items-center
        .col-12.col-md-2.mb-3.mb-md-0
          figure.d-flex.justify-content-center
            img.img160(src='@/assets/curso/tema2/t2-9.svg', alt='mujer con pulgares arriba')
        .col-12.col-md-8.mb-3.mb-md-0
          .tarjeta.tarjeta--azul.pst_3.bg3.p-1
            SlyderA(tipo="b")
              TraduccionChat.mb-5.color-primario(:dialogo="traduccionChat")
              TraduccionChat.mb-5.color-primario(:dialogo="traduccionChat1")
              TraduccionChat.mb-5.color-primario(:dialogo="traduccionChat2")
              TraduccionChat.mb-5.color-primario(:dialogo="traduccionChat3")
              
        .col-12.col-md-2
          figure.d-flex.justify-content-center
            img.img160(src='@/assets/curso/tema2/t2-10.svg', alt='mujer con pulgares arriba')
    
    .row.mb-5
      .col-12.col-md-7
        p Para preguntar el precio de un producto, se emplea la estructura <em>How much + verbo to be:</em>
        .row.mb-3
          .col-12.col-md-6(data-aos="fade")
            .tarjeta-avatar
              img.img90(src='@/assets/curso/tema2/t2-2.svg' alt='AvatarTop')
              .tarjeta.color-acento-botones
                .text-white.p-4
                  p En caso de ser un solo ítem o producto, se utiliza: <em><b>“How much is”</b></em> + el ítem o producto.
          .col-12.col-md-6(data-aos="fade")
            .tarjeta-avatar
              img.img90(src='@/assets/curso/tema2/t2-3.svg' alt='AvatarTop')
              .tarjeta.bgr_15
                .p-4
                  p En caso de ser dos o más ítems o productos, se utiliza <em><b>“How much are”</b></em> + los ítems o productos.
      .col-12.col-md-5
        figure
          img(src='@/assets/curso/tema2/t2-13.jpg', alt='mujer con pulgares arriba')
    
    p.mb-5 Ahora, practique: 

    Dialogo.color-primario(:dialogo="dialogo")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Actividad - completar <em>how much</em>
      template(#descripcion-actividad) Arrastra y suelta el cada una de las palabras en el orden correcto.

    
</template>

<script>
import TraduccionAudio from '../components/TraduccionAudio.vue'
import DialogoChat from '../components/DialogoChat.vue'
import TraduccionChat from '../components/TraduccionChat.vue'
export default {
  name: 'Tema2',
  components: {
    TraduccionAudio,
    DialogoChat,
    TraduccionChat,
  },
  data: () => ({
    dialogo: {
      personajes: [
        {
          nombre: '<em>Book</em>',
          img: require('@/assets/curso/tema2/t2-14.svg'),
        },
        {
          nombre: '<em>Gloves</em>',
          img: require('@/assets/curso/tema2/t2-15.svg'),
        },
        {
          nombre: '<em>Socks</em>',
          img: require('@/assets/curso/tema2/t2-16.svg'),
        },
        {
          nombre: '<em>Umbrella</em>',
          img: require('@/assets/curso/tema2/t2-17.svg'),
        },
      ],
      dialogo: [
        {
          personaje: '<em>Book</em>',
          textoIng: 'How *** the book?<br>The book is $48. ',
          textoEsp: '¿Cúanto cuesta el libro?<br>El libro cuesta $48.',
          audio: require('@/assets/curso/audios/2.1/2.mp3'),
          palabra: 'much is',
        },
        {
          personaje: '<em>Gloves</em>',
          textoIng: 'How much are the gloves?<br>The gloves are ***',
          textoEsp: '¿Cúanto cuestan los guantes?<br>Los guantes cuestan $8',
          audio: require('@/assets/curso/audios/2.1/3.mp3'),
          palabra: '$8',
        },
        {
          personaje: '<em>Socks</em>',
          textoIng: 'How *** the socks?<br>The socks are $4.',
          textoEsp:
            '¿Cuánto cuestan los calcetines?<br>Los calcetines cuestan $4.',
          audio: require('@/assets/curso/audios/2.1/4.mp3'),
          palabra: 'much are',
        },
        {
          personaje: '<em>Umbrella</em>',
          textoIng: 'How much is the ***<br>The umbrella is $15',
          textoEsp: '¿Cuánto cuesta el paraguas?<br>El paraguas cuesta $15.',
          audio: require('@/assets/curso/audios/2.1/5.mp3'),
          palabra: 'umbrella',
        },
      ],
    },
    traduccionChat: {
      personajes: [
        {
          nombre: '<em>Charlie</em><br>Empleado',
          img: require('@/assets/curso/tema2/t2-11.svg'),
        },
        {
          nombre: '<em>Customer</em><br>Cliente',
          img: require('@/assets/curso/tema2/t2-12.svg'),
        },
      ],
      dialogo: [
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'Good morning. May I help you?',
          textoEsp: 'Buenos días. ¿Puedo ayudarle?',
          audio: require('@/assets/curso/audios/2.1/charla/1.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'Yes, please. I like that dress. How much is it?',
          textoEsp: 'Si, por favor. Me gusta ese vestido. ¿Cuánto cuesta?',
          audio: require('@/assets/curso/audios/2.1/charla/2.mp3'),
        },
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'Which one? What color do you prefer?',
          textoEsp: '¿Cuál? ¿Qué color prefiere?.',
          audio: require('@/assets/curso/audios/2.1/charla/3.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'The red one.',
          textoEsp: 'El rojo.',
          audio: require('@/assets/curso/audios/2.1/charla/4.mp3'),
        },
      ],
    },
    traduccionChat1: {
      personajes: [
        {
          nombre: '<em>Charlie</em><br>Empleado',
          img: require('@/assets/curso/tema2/t2-11.svg'),
        },
        {
          nombre: '<em>Customer</em><br>Cliente',
          img: require('@/assets/curso/tema2/t2-12.svg'),
        },
      ],
      dialogo: [
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'It´s only $55. It’s on sale.',
          textoEsp: 'Cuesta solo 55 dólares. Está en oferta.',
          audio: require('@/assets/curso/audios/2.1/charla/5.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng:
            'Ok. It’s reasonable. I’ll take it. And, how much are those shoes?',
          textoEsp:
            'Está bien. Es razonable. Me lo llevo. ¿Y cuánto cuestan esos zapatos?',
          audio: require('@/assets/curso/audios/2.1/charla/6.mp3'),
        },
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'The red ones?',
          textoEsp: '¿Los rojos?',
          audio: require('@/assets/curso/audios/2.1/charla/7.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'Yes, the red shoes.',
          textoEsp: ' Si, los zapatos rojos.',
          audio: require('@/assets/curso/audios/2.1/charla/8.mp3'),
        },
      ],
    },
    traduccionChat2: {
      personajes: [
        {
          nombre: '<em>Charlie</em><br>Empleado',
          img: require('@/assets/curso/tema2/t2-11.svg'),
        },
        {
          nombre: '<em>Customer</em><br>Cliente',
          img: require('@/assets/curso/tema2/t2-12.svg'),
        },
      ],
      dialogo: [
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'They are $88.',
          textoEsp: 'Cuestan 88 dólares.',
          audio: require('@/assets/curso/audios/2.1/charla/9.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'That’s ok. I’ll take them, too.',
          textoEsp: ' Está bien. Los llevaré también.',
          audio: require('@/assets/curso/audios/2.1/charla/10.mp3'),
        },
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'And what size do you like the red dress?',
          textoEsp: ' ¿Y en qué talla quiere el vestido rojo?',
          audio: require('@/assets/curso/audios/2.1/charla/11.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'Medium, please.',
          textoEsp: ' Talla mediana, por favor.',
          audio: require('@/assets/curso/audios/2.1/charla/12.mp3'),
        },
      ],
    },
    traduccionChat3: {
      personajes: [
        {
          nombre: '<em>Charlie</em><br>Empleado',
          img: require('@/assets/curso/tema2/t2-11.svg'),
        },
        {
          nombre: '<em>Customer</em><br>Cliente',
          img: require('@/assets/curso/tema2/t2-12.svg'),
        },
      ],
      dialogo: [
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'Would you like to try it on?',
          textoEsp: '¿Quiere probárselo?',
          audio: require('@/assets/curso/audios/2.1/charla/13.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'No, thanks.',
          textoEsp: 'No, gracias.',
          audio: require('@/assets/curso/audios/2.1/charla/14.mp3'),
        },
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng: 'How are you going to pay?',
          textoEsp: '¿Cómo va a pagar?',
          audio: require('@/assets/curso/audios/2.1/charla/15.mp3'),
        },
        {
          personaje: '<em>Customer</em><br>Cliente',
          textoIng: 'With my Visa credit card.',
          textoEsp: 'Con mi tarjeta de crédito Visa.',
          audio: require('@/assets/curso/audios/2.1/charla/16.mp3'),
        },
        {
          personaje: '<em>Charlie</em><br>Empleado',
          textoIng:
            'Ok. Let’s go to the register cash. Thanks for your purchase!',
          textoEsp:
            'Está bien. Vamos a la caja registradora. ¡Gracias por su compra!',
          audio: require('@/assets/curso/audios/2.1/charla/17.mp3'),
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
