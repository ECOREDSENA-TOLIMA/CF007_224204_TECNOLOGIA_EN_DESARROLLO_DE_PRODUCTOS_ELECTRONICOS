<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .titulo-sexto.color-acento-contenido(data-aos="fade-down-right")
      h5 Figura 1.
      span <em>Tarjeta electrónica</em>

    .bg_grad-07
      figure.mb-3
        img(src='@/assets/curso/introduccion/img1.svg', alt='Texto que describa la imagen' data-aos="zoom-in")
      
      p.mb-5 Un proceso clave en la línea de producción del desarrollo de productos electrónicos es la fabricación de tarjetas electrónicas. Este proceso requiere de la aplicación de varias normas de seguridad que buscan, primero que todo, proteger la vida, así como también conservar en buen estado los equipos y herramientas utilizadas en el proceso.
    br
    br
    .row.mb-3
      .col-12.col-md-6(data-aos="fade-right")
        p También hay que tener en cuenta el concepto de compatibilidad electromagnética, porque es un requisito que debe cumplir todo producto a desarrollar, el cual consiste tanto en la capacidad de absorber y desechar el ruido electromagnético externo como en la no emisión de este último. Este (el producto) debe poder ser operado en cualquier ambiente sin causar perturbaciones a otros equipos, sobre todo si se trata de equipos médicos, que operan bajo condiciones óptimas, debido a que de ellos depende, en muchos casos, la vida.
      .col-12.col-md-6(data-aos="fade-left")
        figure
          img(src='@/assets/curso/introduccion/cuadro1.png', alt='Texto que describa la imagen' data-aos="zoom-in-up")

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
