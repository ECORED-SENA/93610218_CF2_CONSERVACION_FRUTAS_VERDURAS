<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 ¿Qué es la manipulación de alimentos?

    p.mb-5 La manipulación de alimentos comprende el conjunto de técnicas y procedimientos que se realizan con el objetivo de que #[b el alimento mantenga todas sus propiedades físicas, conserve su calidad y prolongue su vida útil], sin sufrir ningún tipo de contaminación, garantizando así que sea seguro para el consumo humano.

    .row.align-items-center.mb-5.style___box_6.m-0(data-aos="zoom-in")
      .col-xl-auto(data-aos="fade-right")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img1.svg", alt="" ).m-auto
      .col-xl
        p.mb-0 Una adecuada manipulación de los alimentos, desde la recepción de las materias primas hasta su transformación, conservación y comercialización, es un factor determinante para asegurar la inocuidad y la calidad final del producto.
    
    p.mb-0 Está comprobado que una mala manipulación reduce la vida útil del alimento, favorece su contaminación y puede provocar enfermedades transmitidas por alimentos en la población. Por esta razón, los métodos más eficaces para la prevención de estas enfermedades son la aplicación constante de medidas higiénicas.

    <!------------------------------------------ SUBTEMA 1 ------------------------------------------>
    Separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 ¿Qué es un manipulador de alimentos?

    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-0(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Se considera #[b manipulador de alimentos] a toda persona que, de manera directa o indirecta, participa en la #[b transformación, preparación, almacenamiento, transporte o comercialización] de alimentos. De su actuación depende que el alimento no se contamine. Además, el manipulador tiene una #[b responsabilidad ética y social] de proteger la salud de los consumidores, aplicando prácticas higiénicas adecuadas y utilizando correctamente las técnicas necesarias para el desarrollo de su labor.

    <!------------------------------------------ SUBTEMA 2 ------------------------------------------>
    Separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Principios generales e higiene de los alimentos
    
    p.mb-5 Los #[b principios generales de higiene de los alimentos] constituyen una fase fundamental para garantizar la #[b inocuidad alimentaria]. Están dirigidos a todas las personas que producen, conservan, almacenan o comercializan productos alimenticios, es decir, a quienes forman parte del #[b sector de los alimentos]. Su correcta aplicación permite reducir riesgos y asegurar alimentos seguros para el consumidor final. A continuación, se presentan algunos conceptos clave relacionados con la higiene e inocuidad de los alimentos:

    .fondo___slider.mb-0
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Contaminación
                p.mb-0 Presencia de agentes físicos, químicos o biológicos que se introducen en un alimento de forma natural o por acción del ser humano.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img4.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Contaminante
                p.mb-0 Cualquier sustancia o agente que se añade a un producto y provoca la pérdida de su inocuidad.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img5.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Desinfección
                p.mb-0 Eliminación de agentes patógenos mediante el uso de agentes químicos y métodos físicos.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img6.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Higiene de los alimentos
                p.mb-0 Conjunto de mecanismos y prácticas de manipulación que garantizan la inocuidad en toda la cadena productiva.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img7.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Inocuidad de los alimentos
                p.mb-0 Condición que asegura que un alimento está libre de agentes contaminantes que puedan causar daño a la salud del consumidor.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img8.png', alt='' style="max-width: 500px").m-auto

    <!------------------------------------------ SUBTEMA 3 ------------------------------------------>
    Separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Requisitos del personal manipulador de alimentos

    p.mb-5 El personal manipulador de alimentos debe cumplir una serie de #[b requisitos sanitarios] antes de iniciar cualquier operación de #[b transformación o conservación]. Estos requisitos están sujetos a las recomendaciones establecidas por el Ministerio de Salud y Protección Social, a través de la #[b Resolución 2674 de 2013], la cual reemplazó el #[b Decreto 3075 de 1997]. 

    .row.align-items-center.style___box_3.m-0(data-aos="zoom-in")
      .col-xl-auto(data-aos="fade-right")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img9.svg", alt="" ).m-auto
      .col-xl
        p.mb-0 Esta normativa establece las condiciones necesarias para asegurar #[b la higiene, calidad e inocuidad de los alimentos] destinados al consumo humano.

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
