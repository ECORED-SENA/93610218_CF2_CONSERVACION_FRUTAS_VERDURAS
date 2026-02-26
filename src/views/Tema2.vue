<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Personal manipulador de alimentos

    p.mb-5 El #[b personal manipulador de alimentos] cumple un papel fundamental en la protección de la #[b salud pública], ya que de sus prácticas depende, en gran medida, la #[b inocuidad de los alimentos].

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img10.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Por esta razón, debe cumplir requisitos de #[b salud, capacitación e higiene personal], establecidos por la normativa sanitaria vigente en Colombia y por las políticas internas de cada empresa.

    <!------------------------------------------ SUBTEMA 1 ------------------------------------------>
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Requisitos de salud del personal manipulador

    p.mb-5 Toda persona que manipule alimentos debe demostrar un buen estado de salud para evitar la transmisión de enfermedades a los alimentos y, posteriormente, a los consumidores. Para garantizar esta condición, se deben cumplir las siguientes disposiciones:

    .bg--img_03.mb-0
      .row.h-100.align-items-center
        .col-xl-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/temas/img11.png", alt="" ).m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Examen médico anual").ajuste-cajaAcordion
              p.mb-3 El manipulador de alimentos debe contar con un examen médico que certifique su adecuado estado de salud. Este examen debe realizarse #[b una vez al año].
            .row(titulo="Chequeos médicos adicionales").ajuste-cajaAcordion
              p.mb-3 El operario debe someterse a un chequeo médico cada vez que el jefe lo considere necesario, especialmente después de ausencias laborales por #[b síntomas infecciosos] que puedan representar un riesgo de #[b contaminación].
            .row(titulo="Medidas preventivas por parte de la empresa").ajuste-cajaAcordion
              p.mb-3 La empresa es responsable de adoptar medidas preventivas cuando exista #[b sospecha de enfermedad grave] transmisible a los alimentos. 
            .row(titulo="Capacitación continua").ajuste-cajaAcordion
              p.mb-3 El personal debe recibir capacitación permanente en #[b Buenas Prácticas de Manufactura (BPM)] y en prácticas higiénicas para aplicar correctamente las precauciones durante su labor.

    <!------------------------------------------ SUBTEMA 2 ------------------------------------------>
    Separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Prácticas higiénicas y medidas de protección
    
    p.mb-5 Las #[b prácticas higiénicas y medidas de protección personal] son obligatorias para todo manipulador de alimentos, ya que reducen significativamente el riesgo de contaminación durante los procesos de preparación y transformación. A continuación, se resumen los principales requisitos que debe cumplir el personal manipulador:

    .fondo___carrusel
      .px-5
        .row.align-items-center.mb-5
          .col-xl-4(data-aos="fade-right")
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img13.png', alt='' style="max-width: 350px").m-auto
          .col-xl-8(data-aos="fade-left")
            SlyderF(columnas="col-lg-6 col-xl-6")
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img14.png').m-auto
                h4.mb-3.estilo-text Higiene personal
                p.mb-0 Mantener una adecuada higiene corporal en todo momento.
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img15.png').m-auto
                h4.mb-3.estilo-text Indumentaria
                p.mb-0 Utilizar uniforme de #[b color claro], con cremalleras o cierres. El delantal debe ir por encima del uniforme.
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img16.png' ).m-auto
                h4.mb-3.estilo-text Uso del delantal
                p.mb-0 No se debe salir del área de trabajo con el delantal ni ingresar con él desde el exterior.
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img17.png').m-auto
                h4.mb-3.estilo-text Lavado de manos
                p.mb-0 Lavar las manos con agua y jabón desinfectante, especialmente al cambiar de actividad.
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img18.png').m-auto
                h4.mb-3.estilo-text Cabello
                p.mb-0 Mantener el cabello recogido y cubierto con #[ malla o gorro].
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img19.png' ).m-auto
                h4.mb-3.estilo-text Barba
                p.mb-0 En el caso de los caballeros con barba, es obligatorio el uso de tapabocas.
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img20.png').m-auto
                h4.mb-3.estilo-text Maquillaje
                p.mb-0 No se permite el uso de maquillaje en las operarias.
              .tarjeta.color-acento-botones
                .row.justify-content-center.mb-3
                  .col-12
                    img(src='@/assets/curso/temas/img21.png').m-auto
                h4.mb-3.estilo-text Tapabocas
                p.mb-0 Su uso es obligatorio según el nivel de riesgo de contaminación del proceso.

        p.mb-5 En relación con la higiene personal, se establecen los siguientes requisitos específicos de presentación, conducta y control en el área de proceso, los cuales deben ser cumplidos obligatoriamente por todo manipulador de alimentos para prevenir la contaminación y garantizar la inocuidad del producto.

    .row.align-items-center.mb-5
      .col-xl-8(data-aos="fade-right")
        SlyderF(columnas="col-lg-6 col-xl-6")
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img23.png' ).m-auto
            h4.mb-3.estilo-text Uñas
            p.mb-0 Deben mantenerse cortas, limpias y sin esmalte.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img24.png' ).m-auto
            h4.mb-3.estilo-text Accesorios
            p.mb-0 No se permite el uso de anillos, aretes, pulseras u otros accesorios.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img25.png' ).m-auto
            h4.mb-3.estilo-text Calzado
            p.mb-0 Debe ser resistente e #[b impermeable].
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img26.png' ).m-auto
            h4.mb-3.estilo-text Guantes
            p.mb-0 Usar guantes en buen estado, sin roturas ni imperfecciones.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img27.png' ).m-auto
            h4.mb-3.estilo-text Conducta en el área de proceso
            p.mb-0 Está prohibido comer, fumar o escupir.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img28.png' ).m-auto
            h4.mb-3.estilo-text Lesiones o infecciones
            p.mb-0 Personas con lesiones o infecciones en la piel no deben manipular alimentos.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img29.png' ).m-auto
            h4.mb-3.estilo-text Uniforme
            p.mb-0 No realizar labores que puedan contaminar el uniforme de trabajo.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img30.png' ).m-auto
            h4.mb-3.estilo-text Dispositivos electrónicos
            p.mb-0 No usar celulares ni equipos de cómputo en el área de proceso.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-12
                img(src='@/assets/curso/temas/img31.png' ).m-auto
            h4.mb-3.estilo-text Visitantes
            p.mb-0 Las personas visitantes deben cumplir con todas las normas higiénicas establecidas.
      .col-xl-4(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src='@/assets/curso/temas/img22.png', alt='' style="max-width: 350px").m-auto

    p.mb-5 El cumplimiento estricto de estos requisitos y prácticas garantiza no solo la #[b calidad del producto], sino también la #[b seguridad del consumidor], fortaleciendo la confianza en los alimentos elaborados y comercializados.

    .style___box_6(data-aos="zoom-in")
      p.mb-0 Los productos que hayan sido devueltos al sitio de proceso porque tienen problemas de inocuidad y de vencimiento no deben volver a ser reenvasados o reprocesados bajo ninguna justificación.

    <!------------------------------------------ SUBTEMA 3 ------------------------------------------>
    Separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Correcta manipulación de los alimentos
    
    .row.align-items-center.mb-5
      .col-xl
        p.mb-0 La correcta manipulación de los alimentos consiste en aplicar procedimientos adecuados que impidan la contaminación por microorganismos, garantizando así la inocuidad, la calidad y la seguridad del alimento en todas las etapas del proceso productivo. Esto abarca desde la recepción de la materia prima hasta la fabricación y conservación del producto final.
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src='@/assets/curso/temas/img32.png', alt='' ).m-auto
    
    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Recepción de la materia prima

    p.mb-5 La recepción de las materias primas es una etapa crítica, ya que de ella depende la calidad e inocuidad del producto final. Por esta razón, deben cumplirse los siguientes criterios:

    .fondo___slider.mb-5
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Inspección
                p.mb-0 Las materias primas deben ser inspeccionadas y presentar características físicas óptimas, sin agentes contaminantes.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img33.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Frutas y verduras
                p.mb-0 No deben presentar deterioro ni estar contaminadas con excrementos de animales.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img34.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Ficha técnica
                p.mb-0 Las materias primas deben contar con una ficha técnica que especifique características como estado de madurez, grados Brix, entre otros.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img35.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Limpieza y desinfección
                p.mb-0 Deben limpiarse y desinfectarse utilizando agua potable.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img36.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Descongelación
                p.mb-0 Las materias primas congeladas deben descongelarse con varias horas de anticipación a su uso.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img37.png', alt='' style="max-width: 500px").m-auto

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Envases y embalajes

    p.mb-5 Los #[b envases y embalajes] utilizados en contacto con los alimentos cumplen una función esencial en la protección contra la contaminación. Para ello, deben cumplir con los siguientes requisitos:

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/temas/img38.png", alt="" ).m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Materiales").ajuste-cajaAcordion
              p.mb-3 Deben estar elaborados con materiales que conserven la inocuidad del alimento, conforme a la normativa sanitaria vigente.
            .row(titulo="Protección").ajuste-cajaAcordion
              p.mb-3 Deben proteger el alimento de cualquier tipo de contaminación.
            .row(titulo="Uso exclusivo").ajuste-cajaAcordion
              p.mb-3 No deben utilizarse para fines distintos a contener alimentos.
            .row(titulo="Higiene").ajuste-cajaAcordion
              p.mb-3 Los envases en contacto directo con el alimento deben permanecer limpios y desinfectados, sin representar riesgo para la salud pública.
            .row(titulo="Almacenamiento").ajuste-cajaAcordion
              p.mb-3 Deben almacenarse en lugares adecuados, limpios e higiénicos, para evitar su contaminación.

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Fabricación de alimentos

    p.mb-5 A continuación, se presenta un pódcast que aborda los principios fundamentales de la fabricación de productos alimenticios, detallando las operaciones del proceso, los controles sanitarios necesarios y las técnicas de conservación aplicables para garantizar la inocuidad y calidad del producto final.

    .row.align-items-center.m-0
      .col-xl
        .row.align-items-center.style___box_4(data-aos="zoom-in")
          .col-auto
            figure.d-none.d-xl-block(data-aos="fade-right")
              img(src="@/assets/curso/temas/img40.svg" style="max-width: 220px").m-auto
          .col
            h4.mb-4 Pódcast
            TarjetaAudio.color-acento-contenido.mb-3(
              texto="Fabricación de alimentos"
              :audio="require('@/assets/componentes/audios/Podcast_1_CF2_Fabricacion_de_alimentos.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
      .col-xl-auto
        figure(data-aos="fade-left").d-none.d-xl-block
          img(src="@/assets/curso/temas/img41.png" ).m-auto

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

<style lang="sass"></style>
