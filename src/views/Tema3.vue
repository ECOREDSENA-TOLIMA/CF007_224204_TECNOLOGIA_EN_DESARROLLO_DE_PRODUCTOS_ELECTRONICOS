<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Riesgos en ensamble electrónico
    
    .row.mb-5
      .col-12.col-md-3.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 10.
          span <em>Torre de comunicación</em>
        span Cuando se trabaja con ensambles eléctricos se pueden enfrentar riesgos de diferentes tipos, siendo el eléctrico el más común. Aunque también existen riesgos de tipo mecánico, sobre todo cuando se está fabricando la placa de circuito impreso y dependiendo del tipo de fabricación que se esté utilizando, se pueden enfrentar riesgos de cortes en la piel, riesgos de esquirlas de material en los ojos, incluso riesgo químico si el trabajo de soldadura es manual, ya que los vapores emanados al soldar pueden ser inhalados ocasionando problemas respiratorios.
      .col-12.col-md-5.mb-3.mb-md-0
        figure
          img(src="@/assets/curso/tema2/img-13.png", alt="Texto que describa la imagen" data-aos="zoom-in-up")
      .col-12.col-md-4
        span Otro riesgo ocurre cuando se trata de trabajos con módulos que se encuentran instalados en las alturas, tal es el caso de módulos de telecomunicaciones, que normalmente se encuentran en antenas a alturas considerables; en este caso, es necesario considerar el trabajo seguro en altura, tema también regulado en Colombia por la Resolución 1409 de 2012. 
        .cajon.bgr_16.p-4.mt-4
          p Por otra parte, algunos componentes electrónicos pueden explotar, tal es el caso de los capacitores mal polarizados, dependiendo de la capacitancia, lo que puede ocasionar daños en los ojos y el rostro. Los elementos de potencia, como SCR y demás tiristores, también pueden explotar y expulsar esquirlas en forma de proyectil, si son sometidos a cortocircuito de altas corrientes.

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1 Concepto y afectaciones de descargas electroestáticas y sobrecargas eléctricas

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 11.
      span <em>Trabajador en alta tensión</em>

    .row.mb-5
      .col-12.col-md-6(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2/img-14.png', alt='Texto que describa la imagen' data-aos="zoom-in")
      .col-12.col-md-6(data-aos="fade-left")
        p Se produce una descarga eléctrica cuando se hace circular una corriente de electrones a través de un cuerpo. Se considera una sobrecarga, cuando esta corriente supera el límite soportado por este cuerpo conductor de la electricidad. El concepto de descargas eléctricas tiene dos puntos de enfoque: desde la afectación al cuerpo humano y la afectación al equipo electrónico.
        .cajon.bgr_5.p-3.mt-4
          p En el cuerpo humano una corriente de más de 25 mA se considera sobrecarga y puede ocasionar daños severos e irreversibles, si esta corriente circula por órganos importantes, puede ocasionar la muerte.
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="fade-right")
        p El Reglamento técnico de instalaciones eléctricas (RETIE), es un documento técnico válido para Colombia emitido por el Ministerio de Minas y Energía. Este reglamento tiene como anexo la norma NTC 2050 que indica el Código Eléctrico Colombiano vigente desde noviembre de 1998. En este reglamento se definen algunos parámetros para el trabajo con equipos electrónicos.
        .bgr_16.p-4.mb-3
          span.colr.text-bold.mb-0 Las descargas en los equipos electrónicos se pueden evitar. 
          | En términos generales para los trabajos de mantenimiento, es suficiente con usar manillas o mantas electrostáticas para evitar sobrecargas a los elementos sensibles. Estos accesorios ayudan a proteger los elementos electrónicos, pero aumentan el riesgo a la persona ya que lo conectan directamente a tierra, exponiéndola a sobrecargas, por eso es importante identificar los elementos con los que se pueden trabajar; por ejemplo, y como norma general, no se deben usar accesorios para electricidad estática con los equipos energizados.
      .col-12.col-md-6(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/img-15.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")

    Separador

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2 Formas de uso y mantenimiento de accesorios

    .p-3.mb-4.d-flex.flex-wrap.align-items-center
      img.mb-4.mb-lg-0.col-lg-1.mx-auto(src="@/assets/curso/tema1/decorador-2.svg" data-aos="fade-right" style="max-width: 85px")
      .col-md-11.ps-lg-4(data-aos="fade-left")
        p.mb-0 Los accesorios para eliminación de cargas electrostáticas incluyen desde las manillas o brazaletes, hasta las mantas electrostáticas, y también se incluyen las bolsas y esponjas para almacenar elementos electrónicos sensibles a estas descargas. Las manillas se colocan en una mano y debe haber contacto físico galvánico, con la piel, el conductor de la manilla envía las descargas electrostáticas a la conexión a tierra.

    p.mb-5.text-center(data-aos="fade") A continuación se presentan algunos de estos accesorios.

    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 12.
          span <em>Contactos eléctricos de la manilla antiestática</em>
        figure
          img(src='@/assets/curso/tema2/img-16.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
          
      .col-12.col-md-4.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 13.
          span <em>Bolsa antiestática</em>
          br
          br
        figure
          img(src='@/assets/curso/tema2/img-17.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
      .col-12.col-md-4(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
          h5 Figura 14.
          span <em>Espuma antiestática</em>
          br
          br
        figure
          img(src='@/assets/curso/tema2/img-18.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")

    .row
      p.mb-5 El mantenimiento más común de estos accesorios consiste en conservar con buena conductividad los contactos eléctricos. Es común que con el sudor de la piel, estos tienden a oxidarse, lo que evita la buena conducción eléctrica y las hace ineficientes. Las mantas deben permanecer limpias y despejadas de objetos, sobre todo de bolsas plásticas que evitan una buena conductividad eléctrica con las manos que entran en contacto.
    
    Separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.3 Características e impacto de la compatibilidad electromagnética

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 15.
      span <em>Torre panorámica Tokio</em>

    
    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/tema2/img-19.png', alt='Texto que describa la imagen')

      .col-12.col-md-7(data-aos="fade-left")
        p.mb-0 Todo equipo electrónico, necesita de un fluido eléctrico para su funcionamiento. Por regla este fenómeno físico lleva asociado un campo magnético; es decir, todo electrón fluyendo a través de un conductor lleva asociado un campo magnético, el cual se manifiesta como líneas de flujo magnético alrededor del conductor. Fue Michael Faraday en 1821 quien realizó los estudios que llevaron a entender mejor este fenómeno y a darle una utilidad práctica, revolucionando por completo el mundo que conocíamos hasta el momento.
        .col-12.col-md-12
          .cajon.bgr_5.p-4.mt-4
            p Ahora bien, lo contrario también es cierto, un campo magnético en movimiento cruzando a un conductor, ocasionará que los electrones se muevan. Este fenómeno tiene mucha aplicación y fue lo que permitió la construcción de los generadores eléctricos, así como también la trasmisión de señales a través del espacio vacío; esto dio origen a las telecomunicaciones.      
      .col-12.col-md-9.mb-3.mb-md-0.py-5.my-5(data-aos="fade-right")
        p Resulta que las emisiones de señales pueden ser perjudiciales para otros equipos, si no son controladas; son múltiples la señales electromagnéticas emitidas día a día, solo imagina, cada emisora de radio, cada canal de televisión, cada aparato de celular, funcionan por señales que viajan en el espacio, es natural pensar que la señal que emite mi celular puede afectar al de mi compañero, o a otro equipo como el televisor o radio, es así en realidad, pero el desarrollador de estos equipos debe tener en cuenta estos parámetros e incluirlos en el diseño. A continuación, en la figura 16 se presenta un ejercicio que se puede realizar como comprobación de lo que se ha expuesto.
      .col-12.col-md-3.mt-3(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2/img-20.svg', alt='Texto que describa la imagen' data-aos="zoom-in-up")

    .col-xl-10.mx-auto.mb-5
      .titulo-sexto.color-acento-contenido(data-aos="fade-right")
        h5 Figura 16.
        span <em>Ejercicio</em>
      .d-flex.flex-wrap.p-4.edit-bg-t2(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/bg-1.svg')})`}"
        data-aos="fade-right"
      )
        .col-lg-7.order-2.order-lg-1
          .p-3
            h4.mb-4(style="color: #00CCA7") Ejercicio          
            p.mb-0(style="color: #FFFF") Encender el radio de la casa y sintonizar una frecuencia que no esté emitiendo nada, es decir, desplazarse a una frecuencia que no esté siendo utilizada; este experimento funciona mejor en Banda A.M.
            br
            p.mb-0(style="color: #FFFF") Ahora se acerca el control remoto de un televisor y se presiona cualquier tecla. Se notará que, aunque el control no entra en contacto con el radio, se puede escuchar un sonido cada vez que se presiona una tecla, haciendo evidente que el control remoto del televisor interfiere con el radio. Si está lloviendo, también se puede observar que cada vez que hay un relámpago, este interfiere en el radio. 
        img.col-lg-4.mx-auto.mb-4.mb-lg-0.order-1.order-lg-2.position-relative(src="@/assets/curso/temas/tema2/img-21.svg" style="right: 0; max-width: 400px; z-index: 1" data-aos="zoom-in-up")

    h4.mb-5.text-center(data-aos="fade") Todo diseñador de equipos electrónicos debe tener en cuenta estos aspectos:
    
    .row.mb-5.justify-content-center.align-items-center(data-aos="zoom-in-up")
      .col-12.col-md-3.mb-3.mb-md-0
        .bgr_19.p-4.h-100
          br
          figure.mb-3.d-flex.justify-content-center
            img.img80(src='@/assets/curso/tema3/t3-1.svg', alt='Texto que describa la imagen')
          br
          p.mb-0.text-center Asegurar que las señales electromagnéticas en su trayectoria no sean afectadas por perturbaciones electromagnéticas.
      .col-12.col-md-3.mb-3.mb-md-0
        .bgr_19.p-4.h-100
          br
          figure.mb-3.d-flex.justify-content-center
            img.img80(src='@/assets/curso/tema3/t3-2.svg', alt='Texto que describa la imagen')
          br 
          p.mb-0.text-center Evitar que se generen perturbaciones electromagnéticas.
          br
          br
      .col-12.col-md-3.mb-3.mb-md-0
        .bgr_19.p-4.h-100
          br
          figure.mb-3.d-flex.justify-content-center
            img.img80(src='@/assets/curso/tema3/t3-3.svg', alt='Texto que describa la imagen')  
          br
          p.mb-0.text-center Minimizar la sensibilidad a las perturbaciones electromagnéticas.
          br
          br

    .row.mb-5
      .col-12.col-md-4.mb-3.mb-md-0
        .cajon.bgr_16.p-4.mt-1
          p Es aquí donde surge el estudio de la compatibilidad electromagnética, que busca minimizar los problemas ocasionados por las emisiones electromagnéticas en el diseño de tarjetas de circuito impreso. 
      .col-12.col-md-4.mb-3.mb-md-0
        figure
          img(src="@/assets/curso/tema3/img-23.png", alt="Texto que describa la imagen" data-aos="zoom-in-up")
      .col-12.col-md-4
        span Adicional a estos aspectos, es importante considerar la distribución óptima de los componentes con rutas de conexión y sistemas de tierra adecuada. Esto debe optimizarse en los diseños donde se trabajan con altas frecuencias, y en el que los problemas de acoplamientos electromagnéticos son más comunes, por lo que siempre hay que reforzar con sistemas de apantallamiento. Es necesario entonces recordar y considerar tanto la radiación emitida, como la absorbida.


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

<style lang="sass">
.edit-bg-t2
  background-repeat: no-repeat
  background-position: center
  background-size: cover
  border-radius: 26px
  position: relative
</style>
