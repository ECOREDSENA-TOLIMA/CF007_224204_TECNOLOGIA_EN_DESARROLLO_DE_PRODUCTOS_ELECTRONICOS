<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Normatividad técnica
    
    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/tema1/ilustracion1.svg', alt='Texto que describa la imagen')
      .col-12.col-md-6(data-aos="fade-left")
        p.mb-0 Existe una regulación en el montaje de circuitos y tarjetas electrónicas, las cuales van desde la estética en el diseño y la funcionalidad, hasta las condiciones de operación y afectación al medio ambiente y salud de las personas en contacto con el producto electrónico final.  
        br
        .cajon.bgr_16.p-5.mb-3
          p.mb-0 Es obligatorio seguir estas regulaciones, sobre todo si el producto a desarrollar pretende ser comercializado, porque debe pasar por una serie de pruebas técnicas que tienen como propósito validar el cumplimiento de los parámetros establecidos en las normas.
        p.mb-0 Las normas aplicadas a la fabricación de circuitos impresos son conocidas como las normas IPC <em>(Institute of Printed Circuit</em> por sus siglas en inglés, creadas por la <em>Association Connecting Electronics Industries).</em> Algunas de ellas son de carácter privado y normalmente se requiere de licenciamiento para su consulta y aplicación, aunque hay procesos que son de seguimiento estándar y aplican para toda la fase de fabricación. <br><br> La figura 2 permite visualizar las diferentes normas y su aplicación.

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 2
      span <em>Normas IPC y aplicación según componente en la tarjeta</em>

    .row.mb-5.justify-content-center(data-aos="fade-down-right")
      .col-12.col-md-10
        figure
          img(src='@/assets/curso/tema1/ilustracion2.svg', alt='Texto que describa la imagen')

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Alcance y aplicabilidad en montaje de tarjetas de circuito impreso

    .row.mb-5
      .col-12.col-md-8.mb-3.mb-md-0
        p.mb-5(data-aos="fade") Las tarjetas de circuito impreso son utilizadas prácticamente en todos los productos electrónicos, es así como hasta el producto electrónico más diminuto hace uso de ellas. A continuación, se presenta una comparación de sus diseños conforme avanzó el tiempo.

        TabsC.color-acento-contenido.mb-5
          .py-3.py-md-4(titulo="Placa Antigua")
            .row.justify-content-center
              .col-md-4.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/tema1/ilustracion3.svg', alt='Placa Antigua' data-aos="zoom-in")
              .col-md-1    
              .col-md-5.p-3
                h4(style="color: #B3009D") Placa Antigua
                p Antes del circuito impreso era normal encontrar diseños electrónicos que demandaban muchos cables, lo que redunda en mal funcionamiento del equipo debido al ruido electromagnético generado y absorbido; esto además hacía que la labor de mantenimiento fuera muy compleja y frecuente.
          .py-3.py-md-4(titulo="Placa Moderna")
            .row.justify-content-center
              .col-md-4.mb-4.mb-md-0
                figure
                  img(src='@/assets/curso/tema1/ilustracion4.svg', alt='Placa Moderna' data-aos="zoom-in")
              .col-md-1    
              .col-md-5
                h4(style="color: #B3009D") Placa Moderna
                p Las tarjetas electrónicas modernas utilizan un sustrato no conductor de la electricidad, normalmente baquelita; sobre este sustrato se embalsa una capa de un material conductor, generalmente cobre. Luego sobre este, se dibujan las pistas que harán de conductores para posteriormente eliminar el cobre sobrante. Lógicamente este proceso ha venido evolucionando, manteniéndose el principio del sustrato y el conductor, cambiando los procesos de eliminación del cobre sobrante.
    
      .col-12.col-md-4
        figure
          img(src='@/assets/curso/tema1/ilustracion5.svg', alt='Texto que describa la imagen')

    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-down-right")
      h5 Figura 3
      span <em>Normas IPC y aplicación según componente en la tarjeta</em>

    .bgr_13.p-5.mb-5
      .row
        .col-12.col-md-4.mb-3.mb-md-0(data-aos="fade-up")
          p.mb-0 La aplicación de estas tarjetas de circuito impreso permitió minimizar los diseños, haciendo productos más pequeños y eficientes en términos energéticos, lo que conllevó al uso de baterías y contribuyó con su portabilidad, como característica principal. De igual forma, a medida que los componentes se hicieron más reducidos, también se surge la necesidad de crear placas más pequeñas con pistas más delgadas, evolucionando también su proceso de fabricación, tal como se presentan en las siguientes imágenes de equipos de comunicación.
        .col-12.col-md-4
          figure
            img(src='@/assets/curso/tema1/ilustracion6.png', alt='Texto que describa la imagen' data-aos="zoom-in")
        .col-12.col-md-4
          figure
            img(src='@/assets/curso/tema1/ilustracion7.png', alt='Texto que describa la imagen' data-aos="zoom-in")

    Separador

    
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Procedimientos y criterios de inspección de calidad en ensamble electrónico

    .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
      h5 Figura 4
      span <em>Soldadura correcta</em>

    .row.mb-5
      .col-12.col-md-6.mb-3.mb-md-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/tema1/ilustracion8.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
      .col-12.col-md-6(data-aos="fade-left")
        p.mb-0 La norma más comúnmente usada en la inspección de circuitos electrónicos es la norma IPC610 (www.ipc.org), la cual establece el estándar de calidad para circuitos electrónicos que sirven como guía para el diseño, montaje, ensamble, inspección, cables, insumos de soldadura, pruebas y otros elementos. El cumplimiento de estas normas permite hablar el mismo lenguaje en productores y consumidores; también, contribuyen a que estos encajen perfectamente en cualquier lugar del mundo sin problemas de compatibilidad.
        br
        .bgr.p-3.mb-3
          p.mb-0 Una inspección visual a un producto electrónico permite verificar el cumplimiento de algunos parámetros establecidos, es así como puntos de soldadura mal puestos, elementos mal colocados, pistas que no cumplen reglas de diseño, son indicadores de que no se cumplieron los procedimientos de ensamble del producto.
        p.mb-0 Es necesario consultar las normas para tener claro cuáles son estos criterios de aceptabilidad de un producto electrónico, la siguiente figura 2 expone la función de cada una.
      
      
      
    .col-xl-10.mx-auto.mb-5
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Figura 5.
          span <em>Tipos de normas.</em>
        .d-flex.flex-wrap.p-4.edit-bg-t2(
          :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/bg-1.svg')})`}"
          data-aos="fade-left"
        )
          SlyderF.col-12.col-lg-8.my-auto.order-2.order-lg-1(columnas="col-12 col-xl-6")
            .tarjeta.color-acento-botones.p-3(style="background-color: #D9F8F2")
              .row.justify-content-center
                .col-8
                  img.mx-auto(src='@/assets/curso/temas/tema2/sl-1.svg' style="max-width: 95px")
              p.mb-0.fw-bold.text-center.mb-2.mt-5 Norma IPC 600
              p.mb-0.fw.text-center.mb-2 Para la Inspección de <br>PCB sin ensamblar. <br>Esta es usada por todos los fabricantes de circuito impreso o PCB.
              
            .tarjeta.color-acento-botones.p-3(style="background-color: #FDF2C8")
              .row.justify-content-center
                .col-8
                  img.mx-auto(src='@/assets/curso/temas/tema2/sl-1.svg' style="max-width: 95px")
              p.mb-0.fw-bold.text-center.mb-2.mt-5 Norma JSTD-001
              p.mb-0.fw.text-center.mb-2 Para requerimientos de <br>soldaduras, fluxes, <br>limpiadores. Esta la <br>usan los soldadores y <br>ensambladores.
              
            .tarjeta.color-acento-botones.p-3(style="background-color: #FDF2C8")
              .row.justify-content-center
                .col-8
                  img.mx-auto(src='@/assets/curso/temas/tema2/sl-1.svg' style="max-width: 95px")
              p.mb-0.fw-bold.text-center.mb-2.mt-5 Norma IPC 620 
              p.mb-0.fw.text-center.mb-2 Para aceptación de cables <br>y arneses, de <br>industrias como <br>maquinaria, automotriz <br>y espacial.
              
            .tarjeta.color-acento-botones.p-3(style="background-color: #FDF2C8")
              .row.justify-content-center
                .col-8
                  img.mx-auto(src='@/assets/curso/temas/tema2/sl-1.svg' style="max-width: 95px")
              p.mb-0.fw-bold.text-center.mb-2.mt-5 Norma IPC 7711/21  
              p.mb-0.fw.text-center.mb-2 Para reparación, <br>retrabajo o <br>modificación de placas <br>de circuito impreso.

            .tarjeta.color-acento-botones.p-3(style="background-color: #FDF2C8")
              .row.justify-content-center.mt-5
                .col-8
                  img.mx-auto(src='@/assets/curso/temas/tema2/sl-1.svg' style="max-width: 95px")
              p.mb-0.fw-bold.text-center.mb-2 Norma IPC 2221  
              p.mb-0.fw.text-center.mb-2 Diseño de placas de <br>circuito impreso.

          img.col-lg-4.mx-auto.mb-4.mb-lg-0.order-1.order-lg-2.banner-principal-decorativo-4.position-relative(src="@/assets/curso/temas/tema2/img-4.svg" style="right: 0; max-width: 250px")

    Separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Requisitos de aceptabilidad de ensambles eléctricos y electrónicos soldados

    .p-3.mb-4.d-flex.flex-wrap.align-items-center
      img.mb-4.mb-lg-0.col-lg-1.mx-auto(src="@/assets/curso/tema1/decorador-2.svg" data-aos="fade-right" style="max-width: 85px")
      .col-md-11.ps-lg-4(data-aos="fade-left")
        p.mb-0 Una simple inspección visual puede arrojar resultados de un producto no conforme. Soldaduras mal puestas, chasis mal fijado, tornillería fuera de parámetros, pueden arrojar la no satisfacción de un producto electrónico. 

    p.mb-5.text-center(data-aos="fade") A continuación se presentan algunos de los parámetros a tener en cuenta. 

    .d-flex.flex-wrap.mb-5
      .col-12.col-md-3
        figure
          img(src='@/assets/curso/tema1/img-1.svg', alt='Texto que describa la imagen' data-aos="zoom-in-up" style="max-width: 250px")
      .col-xl-9.pe-xl-1.order-2.order-xl-1
        AcordionA.mb-5.bgr_7(tipo="b" clase-tarjeta="tarjeta color-acordeon-a" data-aos="fade-right")
          .row(titulo="Pistas conductoras" style="color: #FFFF").p-4
            .col-md-6.mb-4.mb-md-0
              br
              br
              br
              br
              p Es común cometer el error de las pistas conductoras en la placa, ya que  no debe haber pista con ángulos de 90°. 
            .col-md-6
              figure
                img(src='@/assets/curso/tema1/img-2.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
                
          .row(titulo="Distribución de componentes").p-4
            .col-md-6.mb-4.mb-md-0
              br
              br
              p Otro parámetro para tener en cuenta es la distribución de los componentes electrónicos en la placa, muchos <em>softwares</em> de modelado de tarjetas lo hacen automáticamente y algunos parámetros ya están establecidos, sin embargo, muchas veces se hace necesario reordenar algunos componentes, sobre todo el de separar la parte análoga de la parte digital, en las tarjetas que contienen estos dos tipos de componentes.
            .col-md-6
              figure
                img(src='@/assets/curso/tema1/img-3.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")

          .row(titulo="Planos de tierra").p-4
            .col-md-6.mb-4.mb-md-0
              br
              p Los planos de tierra deben estar bien definidos. Esta parte es muy importante, ya que estos ayudan al mejoramiento de la compatibilidad electromagnética como también en el acople de la red, el cual a su vez es fundamental para eliminar los ruidos producidos en la fuente de poder.
              p La pista de tierra en paralelo con la pista de alimentación de la fuente, proporcionan un capacitor que ayuda al acople de la red. Este sistema funciona mejor en placas multicapa.
            .col-md-6
              br
              figure
                img(src='@/assets/curso/tema1/img-4.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")

          div(titulo="Apantallamiento").p-4
            .col-lg-12
              p En tarjetas dedicadas a la transmisión y recepción de señales, es importante contar con un apantallamiento, ya que esta pantalla, es la que no permite la emisión ni la recepción de ruido electromagnético.
            .row.justify-content-center
              .col-lg-10
                .row  
                  .col-lg-6
                    figure
                      img(src='@/assets/curso/tema1/img-5.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
                  .col-lg-6
                    figure
                      img(src='@/assets/curso/tema1/img-6.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
            br
            .col-lg-12  
              p Una pantalla no es más que una protección metálica conectada al polo a tierra por lo que envía el ruido eléctrico hacia tierra, disminuyendo la emisión de electromagnetismo e impidiendo que el externo llegue a los circuitos. Una tarjeta dedicada a comunicaciones normalmente debe venir con este sistema, el no tenerlo es causal de no conformidad.

    .row
      p.mb-5 En equipos Biomédicos, las normas son extremas, estas deben regirse a normatividad especial, lo mismo que para la aeronáutica. Normalmente el desarrollo de estos productos requiere de un estudio especializado, con los permisos debidos.


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
.slyder-f
  .slyder-f__main .horizontal-scroll
    display: flex
    align-items: stretch !important
    height: 100%
    .slyder-f__slyde
      display: flex
      .tarjeta
        width: 100%
  .slyder-f__btn
    background-color: #FFD947
    height: 30px
    max-width: 30px
    border-radius: 50%
    margin: auto
    i
      font-size: 16px
    .fa-chevron-left:before
      margin-left: .8rem
    .fa-chevron-right:before
      margin-right: .8rem
.linea-tiempo-edit
  .linea-tiempo-d__item__content
    transition: all .3s linear
  .linea-tiempo-d__item--selected
    .linea-tiempo-d__item__number
      background-color: #F5D0F0 !important
      color: black !important
    .linea-tiempo-d__item__content
      background-color: #F5D0F0 !important

.color-acordeon-a
  background: #3C0061
  animation: background .3s linear
  &.acordion__activo
    background: #3C0061

.acordion__accion__btn--b
  background: #FFD947

.p-4
  background-color: #FFFF
  padding-bottom: 1rem !important

.acordion__titulo h3
  color: #FFFF
</style>
