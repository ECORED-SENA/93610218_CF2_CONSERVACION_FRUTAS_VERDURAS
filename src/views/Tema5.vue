<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Conservación de frutas y verduras por calor y reducción de agua
    
    .row.align-items-center.m-0.style___box_6.fit___box_6.mb-5(data-aos="zoom-in")
      .col-xl-auto(data-aos="fade-right")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img91.svg" ).m-auto
      .col-xl
        p.mb-0 La #[b conservación de frutas y verduras] mediante #[b calor y reducción del contenido de agua] tiene como objetivo #[b eliminar o inhibir el crecimiento de microorganismos y prolongar la vida útil] de los alimentos, manteniendo condiciones seguras para el consumo humano.

    <!------------------------------------------ SUBTEMA 1 ------------------------------------------>
    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.1 Conservación de frutas y verduras por calor

    p.mb-5 En frutas y verduras, los métodos de conservación por calor más utilizados son la #[b pasteurización] y la #[b esterilización], los cuales actúan principalmente sobre los #[b microorganismos patógenos] y las #[b enzimas] responsables del deterioro del alimento. Los métodos de conservación por calor permiten reducir o eliminar los microorganismos presentes en los alimentos y prolongar su vida útil mediante la aplicación controlada de altas temperaturas:




    .tarjeta--container.row.justify-content-center.mb-5.m-0(data-aos="zoom-in")
      .col-xl-6.col-md-10.tarjeta.color-acento-contenido.p-5
        .row.d-flex.align-items-end.mb-4
          .col-auto(data-aos="fade-right")
            figure
              img(src='@/assets/curso/temas/img92.svg', alt='' style="max-width: 100px")
          .col
            h2 Pasteurización
        p Este método fue desarrollado por #[b Louis Pasteur], quien descubrió una forma de eliminar microorganismos patógenos en la leche. Consiste en someter el alimento a #[b altas temperaturas] y luego enfriarlo rápidamente, con el fin de evitar la sobrecocción y la supervivencia de microorganismos termófilos. Puede realizarse mediante dos tratamientos: temperaturas altas entre #[b 75 y 90 °C durante 2 a 3 minutos], o temperaturas bajas entre #[b 60 y 65 °C durante 3 a 4 horas].
      .col-xl-6.col-md-10.tarjeta.color-primario.text-white.p-5.espacio___movil_3
        .row.d-flex.align-items-end.mb-4
          .col-auto(data-aos="fade-right")
            figure
              img(src='@/assets/curso/temas/img93.svg', alt='' style="max-width: 100px")
          .col
            h2 Esterilización
        p Consiste en someter el alimento, dentro de un #[b recipiente cerrado], a temperaturas entre #[b 116 y 120 °C durante 15 minutos]. Se utiliza principalmente en #[b alimentos enlatados] y tiene como objetivo eliminar todos los microorganismos perjudiciales para el ser humano y desnaturalizar enzimas.
    
    .row.align-items-center.mb-0.style___box_2.m-0(data-aos="zoom-in")
      .col-xl-auto
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img79.png", alt="" ).m-auto
      .col-xl
        p Para verificar que el proceso de esterilización se ha realizado correctamente, la industria alimentaria utiliza como microorganismo indicador al Clostridium botulinum, ya que este se desarrolla con facilidad en ambientes sin oxígeno, característicos de los productos enlatados.
        p.mb-0 La presencia de este microorganismo suele asociarse a malas prácticas de manipulación, como golpes o abolladuras en los envases durante el almacenamiento. Por esta razón, no se deben comprar ni consumir alimentos enlatados en mal estado o vencidos, ya que representan un riesgo para la salud.

    <!------------------------------------------ SUBTEMA 2 ------------------------------------------>
    Separador
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.2 Conservación de frutas y verduras por reducción de agua y control de oxígeno

    p.mb-5 La reducción de agua es un método de conservación que consiste en extraer la mayor cantidad de humedad posible del alimento, impidiendo así el crecimiento bacteriano. Las verduras con un 8 % de humedad y las frutas con menos del 18 % no presentan condiciones favorables para el desarrollo de microorganismos. Los métodos de conservación por eliminación de agua buscan disminuir la actividad microbiana y enzimática del alimento al reducir su contenido de humedad, con el fin de prolongar su vida útil:

    .fondo___slider.mb-5
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Secado al sol
                p.mb-0 Consiste en exponer los productos al sol para que pierdan agua. Requiere condiciones climáticas favorables y es muy utilizado en productos como el café.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img80.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Secado artificial
                p.mb-0 Se realiza en secadoras mediante aire caliente, hasta alcanzar niveles de humedad entre #[b 1% y 5%].
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img81.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Liofilización
                p.mb-0 El alimento se congela y luego se somete a una cámara de vacío, donde el agua se elimina por sublimación. El producto final contiene aproximadamente #[b 2% de agua]. Es un método costoso, pero conserva muy bien las características sensoriales.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img82.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Salazón
                p.mb-0 Consiste en adicionar grandes cantidades de sal al alimento. Los productos obtenidos por este método presentan #[b menor valor nutritivo].
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img83.png', alt='' style="max-width: 500px").m-auto

    p.mb-5 La deshidratación de frutas y verduras permite reducir el contenido de agua del alimento, facilitar su conservación y generar cambios físicos, químicos y sensoriales que deben considerarse tanto en procesos industriales como caseros:

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/temas/img84.png", alt="" ).m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Ventajas de los alimentos deshidratados").ajuste-cajaAcordion
              p.mb-3 La deshidratación ofrece beneficios relevantes que facilitan la conservación, el almacenamiento y el transporte de frutas y verduras.
              ul.fa-ul.estilo___ul_1.mb-3
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Peso]: al perder agua, los alimentos reducen su peso en comparación con su estado natural.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Almacenamiento]: ocupan menos espacio, lo que facilita su almacenamiento y transporte.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Calidad sensorial]: pueden conservar su consistencia y sus características organolépticas.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Refrigeración]: solo requieren refrigeración en el momento de su rehidratación.
                li.mb-0
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Vida útil]: presentan un tiempo de conservación prolongado.
            .row(titulo="Reducción casera de agua en frutas y verduras").ajuste-cajaAcordion
              p.mb-3 La deshidratación puede realizarse de forma casera, siempre que se mantengan condiciones adecuadas de higiene y control de la temperatura.
              ul.fa-ul.estilo___ul_1.mb-3
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Selección]: la fruta debe presentar buenas condiciones físicas.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Preparación]: lavar y cortar en trozos, cubos, tiras o rodajas de aproximadamente 5 mm.
                li.mb-0
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Deshidratación]: realizar el proceso en horno o microondas, iniciando a temperaturas de 45 a 50 °C y aumentando gradualmente hasta 65 a 70 °C. El tiempo estimado es de 30 minutos a 1 hora en horno y de 8 a 10 horas en microondas.
            .row(titulo="Cambios en las frutas por deshidratación").ajuste-cajaAcordion
              p.mb-3 Durante el proceso de deshidratación, las frutas experimentan cambios inevitables como consecuencia de la pérdida de agua y de la aplicación de calor.
              ul.fa-ul.estilo___ul_1.mb-3
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Cambios físicos]: endurecimiento y encogimiento del alimento.
                li.mb-1
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Cambios químicos]: desnaturalización de algunas vitaminas.
                li.mb-0
                  span.fa-li
                    i.fas.fa-arrow-alt-circle-right
                  | #[b Cambios sensoriales]: alteraciones en el color, el sabor, la textura y el olor.
    
    p.mb-0 La correcta aplicación de los métodos de c#[b onservación por calor y reducción de agua] permite obtener alimentos #[b seguros], con mayor #[b durabilidad], teniendo en cuenta los posibles cambios nutricionales y sensoriales que pueden presentarse durante estos procesos.

    <!------------------------------------------ SUBTEMA 3 ------------------------------------------>
    Separador
    #t_5_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.3 Control de oxígeno y regulación del pH en la conservación de alimentos

    p.mb-5 El #[b control del oxígeno] es un factor determinante en la conservación de los alimentos, ya que la mayoría de los #[b microorganismos] requieren oxígeno para crecer y multiplicarse. Por esta razón, la industria alimentaria ha desarrollado diferentes #[b técnicas de conservación] que modifican el ambiente que rodea al alimento o alteran sus condiciones químicas, con el fin de #[b retardar el deterioro] y prolongar su #[b vida útil].

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Métodos de control del oxígeno

    p.mb-5 Las siguientes técnicas se utilizan para limitar la disponibilidad de oxígeno alrededor del alimento y así disminuir el crecimiento microbiano:

    TabsC.color-acento-contenido.mb-5(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Atmósfera modificada")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img85.png', alt="" ).m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Atmósfera modificada
            p.mb-0 Consiste en reducir el contenido de oxígeno y aumentar la concentración de dióxido de carbono (CO₂) y nitrógeno, lo que retrasa el crecimiento de microorganismos y el deterioro del alimento.

      .py-3.py-md-4(titulo="Empaque al vacío")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img86.png', alt="" ).m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Empaque al vacío
            p.mb-0 Se extrae completamente el aire del envase, evitando la presencia de oxígeno. Este método permite conservar las #[b características sensoriales] del producto, como color, sabor y textura.
    
    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Conservación mediante la regulación del Ph

    p.mb-5 Además del control del oxígeno, otra estrategia eficaz de conservación es la #[b regulación del pH] del alimento. Este método consiste en #[b adicionar sustancias ácidas], como #[b ácido acético o vinagre], con el fin de #[b disminuir el pH] y crear un ambiente desfavorable para el crecimiento de microorganismos.

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img87.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Un alimento conservado mediante la regulación del pH puede alcanzar una #[b vida útil de hasta 12 meses], siempre que se mantengan adecuadas condiciones de higiene y almacenamiento.
    
    p.mb-0 La aplicación combinada de técnicas como el #[b control del oxígeno] y la #[b regulación del pH] contribuye significativamente a la #[b seguridad alimentaria], permitiendo conservar los alimentos por más tiempo sin comprometer su #[b calidad ni inocuidad].
    
</template>

<script>
export default {
  name: 'Tema5',
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
