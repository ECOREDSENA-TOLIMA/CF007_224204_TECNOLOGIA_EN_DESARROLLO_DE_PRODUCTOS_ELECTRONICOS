<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 2
        h1 Seguridad y salud en el trabajo
      
      .row.mb-5
        .col-12.col-md-3.mb-3.mb-md-0
          .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
            h5 Figura 5.
            span <em>Técnico electricista</em>
          span En Colombia el sistema de Seguridad y Salud en el Trabajo (SST), está definido por la ley 1552 de 2012 y regulado por la resolución 0312 de 2019. En el área de electrónica se aplica más que todo el séptimo estándar de esta resolución, el cual tiene que ver con la aplicación de medidas de prevención y control frente a todos los peligros y riesgos identificados. Los riesgos al trabajar con equipos electrónicos son inherentes y se debe tener especial cuidado cuando es necesario trabajar con ellos energizados.
        .col-12.col-md-5.mb-3.mb-md-0
          figure
            img(src="@/assets/curso/tema2/img-7.png", alt="Texto que describa la imagen" data-aos="zoom-in-up")
        .col-12.col-md-4
          span Este sistema está definido como aquella disciplina que busca los riesgos presentados al ejecutar una labor y evitar que se presenten problemas. Este ha venido evolucionando, inicialmente se le conocía como salud ocupacional, pero a medida que se modernizan las leyes, le han cambiado el nombre hasta que la última definición quedó como SG-SST (Sistema de Gestión de la Seguridad y Salud en el Trabajo).
          .cajon.bgr_16.p-4.mt-4
            p La ley 1562 del 2012 lo define como: “Es el conjunto de entidades públicas y privadas, normas y procedimientos, destinados a prevenir, proteger y atender a los trabajadores de los efectos de las enfermedades y los accidentes que puedan ocurrirles con ocasión o como consecuencia del trabajo que desarrollan”.

      .row.mt-5
        .row.mb-5
          .col-lg-4.d-none.d-lg-flex.p-0
            figure
              img(src='@/assets/curso/tema2/img-8.svg', alt='Texto que describa la imagen' data-aos="zoom-in")
          .col-lg-8.d-none.d-lg-flex.p-0
            figure
              img(src='@/assets/curso/tema2/img-9.svg', alt='Texto que describa la imagen')
              br
              br
              p La aplicación de este sistema mejora el ambiente laboral, el bienestar de los trabajadores, evitando ausentismo por enfermedad, pero el mayor impacto se da, al reducir la tasa de accidentalidad y una amplia mejora de la productividad, además que al implementar el sistema ayuda con el cumplimiento de las normas, por parte de las empresas y empleadores.
              br
              .h5(style="color: #3C0061") Existen referencias de empresas que mejoraron considerablemente su producción y posteriormente las ventas, solo con implementar un buen sistema de seguridad y salud en el trabajo.

      #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 2.1 Seguridad física y elementos de protección personal

      .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
        h5 Figura 6.
        span <em>Trabajo bajo normas de seguridad</em>

      .row.mb-5
        .col-12.col-md-6(data-aos="fade-right")
          figure
            img(src='@/assets/curso/tema2/img-10.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")
        .col-12.col-md-6(data-aos="fade-left")
          p El sistema de implementación de seguridad física debe involucrar tanto a la persona como a los equipos, ya que un equipo o herramienta en mal estado, también influye en la salud de las personas, es más, se extiende al plan de protección de datos de la empresa: todo aquello que involucre un riesgo físico para un equipo, también lo es para las personas aunque sea de manera indirecta. De ahí la importancia del uso adecuado de los elementos de protección personal - EPP.
          p Todos los requerimientos para la implementación de EPP en los lugares de trabajo para un ambiente saludable se encuentran contemplados en la Ley 9 de enero 24 de 1979 (Título III, artículos 122 a 124) y en la Resolución 2400 de mayo 22 de 1979 (Título IV, Capitulo II, artículos 176 a 201).
      
      p Es importante saber seleccionar los elementos de protección, porque un mal uso de ellos puede incurrir en accidentes. Dentro de los elementos más comunes se encuentran, ver figura 3:

      .col-xl-12.mx-auto.mb-5
          .titulo-sexto.color-acento-contenido(data-aos="fade-right")
            h5 Figura 7.
            span <em>Elementos de protección personal</em>
          .d-flex.flex-wrap.p-4.edit-bg-t2(
            :style="{'background-image': `url(${require('@/assets/curso//temas/tema2/bg-1.svg')})`}"
            data-aos="fade-left"
          )
            SlyderF.col-12.col-lg-12.my-auto.order-2.order-lg-1(columnas="col-12 col-xl-6")
              .tarjeta.color-acento-botones.p-3(style="background-color: #FDF2C8")
                .row.justify-content-center
                  .col-8
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-7.svg' style="max-width: 60%")
                    br
                p.mb-0.fw-bold.text-center.mb-2 Protección para el oído
                p.mb-0.fw.text-center.mb-2 Protectores auditivos de inserción, tipo tapón desechable, reutilizable o pre-moldeable. Supraaurales, tipo disco plano. Supraaurales, tipo banda ajustable. Circumaurales, tipo orejera universal, tipo orejeras con arnés, fijo de cabeza, fijo de <br>barbilla, fijo de nuca. Tipo cascos antirruido, tipo orejeras <br>acopladas a casco. Circuitos electrónicos incorporados, del <br>tipo dependientes del nivel y con aparatos de <br>intercomunicación.
                br
                br

              .tarjeta.color-acento-botones.p-3(style="background-color: #7DE5D2")
                .row.justify-content-center
                  .col-8
                    br
                    br
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-8.svg' style="max-width: 60%")
                    br
                p.mb-0.fw-bold.text-center.mb-2 Protección para la cabeza
                p.mb-0.fw.text-center.mb-2 Cascos de seguridad, los cuales están clasificados en categoría A, B, C y D. Prendas de protección para la cabeza, tales como, gorros, gorras, sombreros, de tejido recubierto. Cascos para usos especiales en fuego, cascos reflectantes.
                br
                br
                
              .tarjeta.color-acento-botones.p-3(style="background-color: #7DE5D2")
                .row.justify-content-center
                  .col-8
                    br
                    br
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-9.svg' style="max-width: 60%")
                    br
                p.mb-0.fw-bold.text-center.mb-2 Protección para los ojos y la cara
                p.mb-0.fw.text-center.mb-2 Lentes de seguridad tipo montura universal, montura integral, montura cazoletas. Pantallas faciales. Pantallas para soldadores de mano, de cabeza, acoplables a casco de protección. Lentes para usos especiales para trabajos con Rayos X, Rayos Ultravioleta, agentes biológicos y químicos.
                br
                br

              .tarjeta.color-acento-botones.p-3(style="background-color: #7DE5D2")
                .row.justify-content-center
                  .col-8
                    br
                    br
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-10.svg' style="max-width: 60%")
                    br
                p.mb-0.fw-bold.text-center.mb-2 Protección para las vías respiratorias
                p.mb-0.fw.text-center.mb-2 Equipos filtrantes de partículas molestas, nocivas, tóxicas o radiactivas; filtrantes combinados frente a gases y vapores; suministradores de aire, con casco o pantalla para soldadura, con máscara amovible para soldadura, para trabajos bajo el agua.
                br
                br

              .tarjeta.color-acento-botones.p-3(style="background-color: #7DE5D2")
                .row.justify-content-center
                  .col-8
                    br
                    br
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-11.svg' style="max-width: 60%")
                    br
                p.mb-0.fw-bold.text-center.mb-2 Protección de manos y brazos  
                p.mb-0.fw.text-center.mb-2 Guantes contra vibración, guantes contra riesgo mecánico, riesgo químico, riesgo biológico, riesgo eléctrico, riesgo de origen térmico y radiaciones, manoplas.
                br
                br

              .tarjeta.color-acento-botones.p-3(style="background-color: #7DE5D2")
                .row.justify-content-center
                  .col-8
                    br
                    br
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-12.svg' style="max-width: 60%")
                    br
                p.mb-0.fw-bold.text-center.mb-2 Protección de piernas 
                p.mb-0.fw.text-center.mb-2 Calzado de seguridad, calzado ocupacional  para riesgo eléctrico y químico; botas de goma o caucho,  protección contra el calor o el frío, rodilleras.
                br
                br

              .tarjeta.color-acento-botones.p-3(style="background-color: #7DE5D2")
                .row.justify-content-center
                  .col-8
                    br
                    img.mx-auto(src='@/assets/curso/temas/tema2/sl-13.svg' style="max-width: 60%")
                    br
                p.mb-0.fw.text-center.mb-2 Adicionalmente existen protectores de la piel como cremas de protección contra radiaciones por trabajo al aire libre; protectores del tronco y el abdomen como, chalecos, chaquetas y cotonas de protección contra el riesgo mecánico, químico, resistentes a la temperatura, chalecos salvavidas, delantales de protección contra los rayos x , cinturones de sujeción del tronco, equipos de protección contra las caídas distinto nivel tipo arnés, cinturones de posicionamiento, dispositivos de caídas de tipo deslizante, dispositivos con amortiguador, ropa de protección contra proyecciones de metales en fusión y radiaciones infrarrojas.

      Separador

      #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 2.2 Recomendaciones de trabajo con computadores

      .row.mb-5
        .col-12.col-md-3.mb-3.mb-md-0
          .titulo-sexto.color-acento-contenido.mb-5(data-aos="fade-down-right")
            h5 Figura 8.
            span <em>Disco duro</em>
          span El trabajo con computadores requiere de medidas especiales, si el trabajo no involucra la fuente de poder, el mayor riesgo es para el equipo, normalmente los módulos del computador trabajan con bajas tensiones. El principal cuidado que se debe tener es al trabajar con discos duros, debido a que estos funcionan con magnetismo y exponerlos a campos magnéticos intensos, puede borrar los datos grabados en este, así que es necesario utilizar destornilladores no imantados.
        .col-12.col-md-5.mb-3.mb-md-0
          figure
            img(src="@/assets/curso/tema2/img-11.png", alt="Texto que describa la imagen" data-aos="zoom-in-up")
        .col-12.col-md-4
          span No se debe abrir un disco duro (HDD) si no se cuenta con un cuarto limpio. 
          span.colr.text-bold Un partícula de polvo, por minúscula que parezca, puede ocasionar un mal funcionamiento de este, 
          | normalmente rayones en la superficie del disco duro, daño que es irreversible y que incurre en pérdida irrecuperable de datos.
          .cajon.bgr_5.p-4.mt-4
            p Los módulos electrónicos de los equipos de cómputo, por su parte, son sensibles a las descargas electrostáticas; es así como se debe usar una protección especial para trabajar con estos, la cual puede ser una manilla o una manta antiestática; de no contar con estos elementos, se debe descargar el cuerpo agarrando periódicamente una superficie metálica conectada a tierra.

      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/tema2/img-12.png')})`}"
        )
        .bloque-texto-g__texto.p-5
          p.mb-0 No se debe usar manilla antiestática cuando se trabaja con la fuente de poder, la razón es que la manilla representa una conexión a tierra y el positivo de la fuente de poder queda referenciado a tierra con una diferencia de potencial de 340 voltios, con una corriente relativamente alta, lo que puede representar un daño considerable al cuerpo, además de que si la descarga es de mano a mano, involucra al corazón.

</template>

<script>
export default {
  name: 'Tema2',
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

.p-6
  background-color: lighten(#B3009D, 55%)
  padding-bottom: 1.5rem !important
</style>
