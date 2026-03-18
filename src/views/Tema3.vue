<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Prevención de la contaminación cruzada
    
    p.mb-5 La #[b contaminación cruzada] es una práctica inadecuada que ocurre durante la elaboración de los alimentos cuando se #[b cruzan procesos], permitiendo que los microorganismos pasen de un alimento contaminado a otro que se encuentra limpio o listo para el consumo. Un ejemplo común se presenta cuando se manipula #[b carne cruda] y posteriormente se manipula un #[b alimento cocido] sin realizar una correcta higiene, lo que ocasiona la contaminación de este último.

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img42.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La prevención de la contaminación cruzada es fundamental para garantizar la #[b inocuidad de los alimentos] y proteger la salud del consumidor. Para ello, deben aplicarse medidas higiénicas estrictas durante todo el proceso productivo.

    <!------------------------------------------ SUBTEMA 1 ------------------------------------------>
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.1 Medidas para la prevención de la contaminación cruzada

    p.mb-5 Para evitar la transferencia de microorganismos entre alimentos crudos y alimentos listos para el consumo, es indispensable aplicar una serie de #[b medidas preventivas] que aseguren un adecuado control higiénico y un flujo de producción ordenado.

    .fondo___slider.mb-0
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Separación de alimentos
                p.mb-0 Evitar el contacto directo o indirecto entre alimentos listos para el consumo y materias primas que aún no han sido procesadas.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img43.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Indumentaria
                p.mb-0 La falta de indumentaria adecuada o el uso de ropa sucia puede generar contaminación cruzada.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img44.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Lavado de manos
                p.mb-0 Es obligatorio lavarse las manos entre operaciones dentro del mismo proceso de elaboración.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img45.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Higienización de utensilios
                p.mb-0 Los equipos y utensilios que hayan estado en contacto con materias primas deben limpiarse y desinfectarse antes de reutilizarse.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img46.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Flujo del proceso
                p.mb-0 Todas las etapas del proceso deben realizarse de manera secuencial para evitar cruces innecesarios.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img47.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Pediluvios
                p.mb-0 Cuando sea necesario, deben instalarse pediluvios para la limpieza y desinfección de botas.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img48.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Lavamanos
                p.mb-0 En la entrada de las áreas de fabricación deben instalarse lavamanos de pedal; el secado debe hacerse con toallas desechables o secadores.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img49.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Control del personal
                p.mb-0 Los jefes de producción deben garantizar que los operarios tengan las manos debidamente higienizadas antes de iniciar labores.
              .col-xl-6
                figure
                  img(src='@/assets/curso/temas/img50.png', alt='' style="max-width: 500px").m-auto
      
    <!------------------------------------------ SUBTEMA 2 ------------------------------------------>
    Separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.2 Conservación de productos frescos

    p.mb-5 Las #[b frutas y verduras frescas] son parte fundamental de la alimentación diaria de la población. Para disfrutar de estos alimentos de manera segura, es necesario aplicar una correcta manipulación desde el momento de la compra hasta su preparación, con el fin de evitar #[b enfermedades transmitidas por los alimentos]. A continuación se presentan recomendaciones generales para la selección y preparación de productos frescos, orientadas a preservar su calidad e inocuidad y a reducir riesgos para la salud.

    .bg--img_03.mb-0
      .row.h-100.align-items-center
        .col-xl-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/temas/img51.png", alt="" ).m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Recomendaciones para adquirir productos frescos").ajuste-cajaAcordion
              p.mb-3 La selección adecuada de los productos frescos constituye el primer paso para asegurar su calidad e inocuidad. En el momento de la compra, se recomienda considerar los siguientes aspectos:
              ul.fa-ul.estilo___ul_1.mb-3
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Estado físico]: las frutas y verduras no deben presentar golpes ni daños visibles.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Productos cortados]: no se recomienda adquirir frutas o verduras cortadas o preempacadas abiertas, como media sandía o ensaladas picadas.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Apariencia]: deben conservar un aspecto fresco y, de ser posible, mantenerse en refrigeración o sobre hielo.
                li.mb-0
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Separación en la compra]: las carnes deben transportarse en bolsas distintas a las frutas y verduras, con el fin de prevenir la contaminación cruzada.
            .row(titulo="Recomendaciones para preparar productos frescos").ajuste-cajaAcordion
              p.mb-3 Antes del consumo, los productos frescos deben manipularse siguiendo prácticas higiénicas adecuadas, con el propósito de reducir la carga microbiana y prevenir riesgos para la salud.
              ul.fa-ul.estilo___ul_1.mb-3
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Lavado de manos]: lavarse las manos con agua y jabón desinfectante durante aproximadamente 20 segundos.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Inspección]: revisar que las frutas y verduras se encuentren en buen estado y no presenten signos de deterioro.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Lavado]: lavar adecuadamente los productos con agua potable; no utilizar detergentes ni jabones.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Limpieza con cepillo]: pepinos, melones y papas deben limpiarse con un cepillo limpio para retirar la suciedad adherida.
                li.mb-0
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Secado]: secar los productos con toalla de papel o con una tela limpia.

    <!------------------------------------------ SUBTEMA 3 ------------------------------------------>
    Separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 3.3 Productos frescos prelavados
    
    p.mb-5 Los productos frescos #[b prelavados, precortados y empacados] pueden consumirse sin necesidad de un nuevo lavado. Sin embargo, como medida adicional de precaución, pueden lavarse nuevamente. En caso de que vengan en #[b bolsas abiertas], es obligatorio realizar nuevamente su limpieza e higienización. Para reforzar la seguridad alimentaria durante la manipulación de productos frescos, se deben aplicar las siguientes recomendaciones generales: 

    .fondo___carrusel
      .px-5

        .row.justify-content-center.mb-5
          .col-xl-3.col-md-8(data-aos="zoom-in")
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img52.jpg', alt="").m-auto
                h4 Separación de alimentos
                p.mb-0 Mantener frutas y verduras separadas de pescados, aves, mariscos crudos y carnes rojas.
          .col-xl-3.col-md-8(data-aos="zoom-in").espacio___movil_3
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img53.jpg', alt="").m-auto
                h4 Limpieza de utensilios
                p.mb-0 Lavar utensilios, platos, tablas y superficies con suficiente agua caliente después de cada uso.
          .col-xl-3.col-md-8(data-aos="zoom-in").espacio___movil_3
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img54.jpg', alt="").m-auto
                h4 Tablas de corte
                p.mb-0.ajuste___card_1 Utilizar tablas de material no poroso, evitando las de madera.
          .col-xl-3.col-md-8(data-aos="zoom-in").espacio___movil_3
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img55.jpg', alt="").m-auto
                h4 Superficies
                p.mb-0.ajuste___card_1 Preferir mesas y utensilios de acero inoxidable para facilitar la limpieza y desinfección.

        .style___box_6.mb-0(data-aos="zoom-in")
          .row.align-items-center
            .col-xl-auto.col-md-2(data-aos="fade-right")
              figure
                img(src='@/assets/curso/temas/img56.svg', alt='' style="width: 85px").m-auto
            .col-xl.col-md-10.espacio___movil_3
              p.mb-0 La aplicación rigurosa de estas medidas permite #[b reducir significativamente la contaminación cruzada] y asegurar alimentos #[b seguros, higiénicos y aptos para el consumo humano].

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
