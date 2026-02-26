<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Conservación de frutas y verduras en frío

    p.mb-5 La #[b conservación de frutas y verduras en frío] es una de las técnicas más antiguas y seguras para prolongar la #[b vida útil de los alimentos]. Desde tiempos antiguos, los seres humanos utilizaban los lugares más fríos de sus cavernas para conservar sus alimentos. Con el paso del tiempo, se emplearon cajones de madera con hielo, aunque este método presentaba limitaciones debido al derretimiento del hielo. En la actualidad, se cuenta con #[b equipos modernos de refrigeración y congelación] que permiten un control preciso de la temperatura.

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img57.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La conservación en frío consiste en #[b someter el alimento a bajas temperaturas] con el fin de #[b reducir el crecimiento de microorganismos], disminuir la #[b actividad enzimática] y mantener las c#[b aracterísticas físicas y químicas] del alimento. Este método es considerado uno de los #[b más seguros] para la conservación de alimentos frescos.

    <!------------------------------------------ SUBTEMA 1 ------------------------------------------>
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 4.1 Métodos de conservación en frío

    p.mb-5 Estos métodos reducen la actividad microbiana y las reacciones químicas del alimento mediante el control de la temperatura, lo que permite prolongar su tiempo de conservación.

    TabsA.color-acento-botones.mb-5(data-aos="zoom-in")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Refrigeración")
        h4 Refrigeración
        p.mb-0 Método de conservación a corto plazo. Consiste en mantener el alimento a temperaturas cercanas a los 0 °C, lo que impide el crecimiento de microorganismos y retarda las reacciones químicas. En promedio, las verduras pueden conservarse hasta dos semanas y las frutas más de cuatro semanas.
      .tarjeta.color-acento-botones--borde.p-4(titulo="Congelación")
        h4 Congelación
        p.mb-0 Método de conservación a largo plazo. Consiste en convertir rápidamente el agua del alimento en hielo, a temperaturas de -18 °C o inferiores. Las frutas y verduras pueden conservarse entre 3 y 12 meses sin deterioro significativo de su calidad.
    
    p.mb-5 En general, la aplicación del frío en la conservación de frutas y verduras requiere prácticas específicas según el método utilizado y las características del alimento:

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Aplicación de la refrigeración

    p.mb-5 A continuación, se presenta un pódcast sobre la correcta aplicación de la refrigeración en frutas y verduras, con el fin de preservar su calidad, prolongar su vida útil y evitar pérdidas durante su almacenamiento y comercialización.

    .row.align-items-center.m-0.mb-5
      .col-xl
        .row.align-items-center.style___box_4.fit___box_4(data-aos="zoom-in")
          .col-auto
            figure.d-none.d-xl-block(data-aos="fade-right")
              img(src="@/assets/curso/temas/img40.svg" style="max-width: 220px").m-auto
          .col
            h4.mb-4 Pódcast
            TarjetaAudio.color-acento-contenido.mb-3(
              texto="Aplicación de la refrigeración"
              :audio="require('@/assets/componentes/audios/Podcast_2_CF2_Aplicacion_de_la_refrigeracion.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
      .col-xl-auto
        figure(data-aos="fade-left").d-none.d-xl-block
          img(src="@/assets/curso/temas/img58.png" style="max-width: 450px").m-auto
    
    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Aplicación de la congelación en verduras

    p.mb-5 La congelación de verduras requiere un tratamiento específico según la especie, debido a que su comportamiento varía de acuerdo con su composición físico-química. Para obtener resultados adecuados, se deben considerar los siguientes aspectos:

    .row.align-items-center.m-0.style___box_7(data-aos="zoom-in")
      .col-xl-auto
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img59.jpg" style="max-width: 450px").m-auto
      .col-xl
        ul.fa-ul.estilo___ul.mb-0
          li.mb-1
            span.fa-li
              i.fas.fa-arrow-alt-circle-right
            | #[b Temperatura previa]: las frutas y verduras deben refrigerarse previamente entre 5 y 7 °C.
          li.mb-1
            span.fa-li
              i.fas.fa-arrow-alt-circle-right
            | #[b Empaques]: deben ser transparentes, de cierre hermético y elaborados en plástico resistente y flexible.
          li.mb-0
            span.fa-li
              i.fas.fa-arrow-alt-circle-right
            | #[b Preparación previa]: antes de la congelación, resulta fundamental aplicar el proceso de escaldado.

    <!------------------------------------------ SUBTEMA 2 ------------------------------------------>
    Separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 4.2 Escaldado (blanqueado)

    p.mb-5 El #[b escaldado] consiste en introducir las frutas o verduras en #[b agua hirviendo durante un tiempo determinado], con el objetivo de #[b desactivar enzimas, inhibir el crecimiento de microorganismos] y mejorar el #[b color y el sabor]. Las verduras de cáscara dura requieren mayor tiempo de escaldado, como en el caso de la remolacha. Después del escaldado, es recomendable #[b sumergir las verduras en agua fría], secarlas adecuadamente y empacarlas en #[b bolsas herméticas] antes de la congelación.

    .color___box_2
      .px-5

        .row.justify-content-center.mb-5
          .col-xl-6
            .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
              h5 Tabla 1.
              span Tiempos de escaldado de verduras
            .tabla-a(data-aos="zoom-in")
              table
                thead
                  tr
                    th.ajuste-border-tabla.texto-left Vegetal
                    th.texto-left Tiempo de escaldado en agua hirviendo
                tbody
                  tr
                    td.ajuste-border-tabla.texto-left Espárragos pequeños
                    td.texto-left 2 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Espárragos grandes
                    td.texto-left 4 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Remolacha pequeña
                    td.texto-left 25-30 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Remolacha mediana
                    td.texto-left 45-50 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Brócoli
                    td.texto-left 3 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Coliflor
                    td.texto-left 3 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Repollitos de Bruselas
                    td.texto-left 3 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Zanahoria en cubos
                    td.texto-left 2 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Papa en cubos
                    td.texto-left 1 minuto.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Acelga
                    td.texto-left 3 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Espinaca
                    td.texto-left 2 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Choclo
                    td.texto-left 7-11 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Granos de choclo
                    td.texto-left 4 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Arvejas
                    td.texto-left 2-3 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Champiñón
                    td.texto-left 3,5 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Pimiento rojo en mitades
                    td.texto-left 3 minutos.
                  tr
                    td.ajuste-border-tabla.texto-left Pimiento rojo en tiras
                    td.texto-left 2 minutos.
                  tr.ajuste-color-tabla
                    td.ajuste-border-tabla.texto-left Pimiento rojo asado
                    td.texto-left Puede asarse y congelarse sin escaldar.

        p.mb-0 La correcta aplicación de la #[b refrigeración, congelación y escaldado] permite conservar frutas y verduras en condiciones seguras, manteniendo su #[b calidad nutricional, sensorial e higiénica], y reduciendo los riesgos para la #[b salud del consumidor].

    <!------------------------------------------ SUBTEMA 3 ------------------------------------------>
    Separador
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 4.3 Empaque y consideraciones generales en la congelación de frutas
    
    p.mb-5 El #[b empaque] es una etapa fundamental en la conservación de frutas por congelación, ya que influye directamente en la #[b calidad, seguridad y vida útil] del producto. El recipiente donde se empacan los trozos de fruta debe quedar #[b bien lleno, sin presencia de aire], correctamente #[b sellado y rotulado] con el nombre del producto, la fecha de elaboración y el #[b gramaje].

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img61.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Es importante tener en cuenta que, durante la congelación, #[b los microorganismos no se eliminan], sino que permanecen #[b inactivos]. Por esta razón, al momento de la #[b descongelación], no se debe romper la #[b cadena de frío], ya que esto favorece la reactivación microbiana y el deterioro del alimento.

    p.mb-5 En general, #[b casi todas las frutas pueden congelarse], aunque algunas verduras como el tomate, el pimentón y otras destinadas a ensaladas no se recomiendan para este proceso, debido a que pierden su #[b textura crujiente]. Las frutas pueden congelarse en forma de #[b pulpa, jugo, rebanadas o enteras], y se les puede adicionar azúcar y #[b ácido cítrico], el cual ayuda a retardar la #[b oxidación química] causada por la acción de las enzimas.

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Procesos para congelar las frutas

    p.mb-5 Existen diferentes #[b procesos de congelación de frutas], los cuales permiten conservar mejor sus características sensoriales y evitar el deterioro durante el almacenamiento.

    .fondo___slider.mb-0
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Proceso de fruta en almíbar
                p.mb-3 Este método permite conservar la fruta protegida por una solución azucarada, la cual contribuye a mantener su textura y su sabor durante el almacenamiento.
                ul.fa-ul.estilo___ul.mb-0
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Preparación del almíbar]: disolver una taza de azúcar en dos tazas de agua.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Cocción]: llevar la mezcla a cocción hasta alcanzar los 100 °C.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Enfriamiento]: dejar enfriar completamente el almíbar antes de su uso.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Preparación de la fruta]: lavar, pelar y cortar la fruta en trozos adecuados.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Adición]: cubrir la fruta por completo con el almíbar preparado.
                  li.mb-0
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Empaque]: empacar la fruta en bolsas plásticas de polietileno, dejando un pequeño espacio libre y sellar adecuadamente.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img62.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Frutas con adición de vitamina C
                p.mb-3 Algunas frutas, al ser peladas o cortadas, presentan pardeamiento enzimático, lo cual ocasiona pérdida de color y de apariencia. Para prevenir este fenómeno, se utiliza ácido ascórbico (vitamina C).
                ul.fa-ul.estilo___ul.mb-0
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Preparación del ácido ascórbico]: si se emplea en tabletas, estas deben macerarse hasta obtener un polvo fino.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Dosificación]: adicionar 5 g de ácido ascórbico por cada litro de almíbar frío.
                  li.mb-0
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Aplicación]: mezclar el ácido ascórbico con el almíbar antes de incorporarlo a la fruta.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img63.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Proceso de fruta con azúcar
                p.mb-3 Este proceso permite conservar la fruta mediante la acción del azúcar y la concentración de su jugo natural.
                ul.fa-ul.estilo___ul.mb-0
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Preparación]: colocar la fruta en un recipiente adecuado.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Adición de azúcar]: agregar azúcar en la cantidad requerida.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Concentración]: llevar la mezcla al fuego y revolver hasta que el jugo de la fruta se integre con el azúcar.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Hervido]: dejar hervir la preparación durante el tiempo necesario.
                  li.mb-1
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Enfriamiento]: retirar del fuego y dejar enfriar completamente.
                  li.mb-0
                    span.fa-li
                      i.fas.fa-arrow-alt-circle-right
                    | #[b Empaque]: empacar el producto dejando un espacio libre, con el fin de permitir la expansión durante la congelación.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img64.png', alt='' style="max-width: 500px").m-auto

    <!------------------------------------------ SUBTEMA 4 ------------------------------------------>
    Separador
    #t_4_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 4.4 Consejos para la refrigeración y congelación
    
    p.mb-5 Para mantener la #[b seguridad e inocuidad de los alimentos], se deben seguir las siguientes recomendaciones prácticas:

    .fondo___carrusel
      .px-5

        .row.justify-content-center.mb-5
          .col-xl-3.col-md-8(data-aos="zoom-in")
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img65.jpg', alt="").m-auto
                h4 Alimentos calientes
                p.mb-0 No introducir alimentos calientes en la nevera ni en el congelador; deben enfriarse previamente.
          .col-xl-3.col-md-8(data-aos="zoom-in").espacio___movil_3
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img66.jpg', alt="").m-auto
                h4 Cadena de frío
                p.mb-0 Evitar que el refrigerador o el congelador se apaguen, ya que esto puede dañar los alimentos almacenados.
          .col-xl-3.col-md-8(data-aos="zoom-in").espacio___movil_3
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img67.jpg', alt="").m-auto
                h4 Limpieza de equipos
                p.mb-0 Al limpiar estos equipos, debe hacerse en el menor tiempo posible.
          .col-xl-3.col-md-8(data-aos="zoom-in").espacio___movil_3
            .style___box_5.h-100
              .row.justify-content-center.mb-3
                .col-12
                  figure.mb-4
                    img(src='@/assets/curso/temas/img68.jpg', alt="").m-auto
                h4 Organización
                p.mb-0 Agrupar los productos congelados para evitar la pérdida de frío durante la limpieza.

        .row.align-items-center.m-0.style___box_6(data-aos="zoom-in")
          .col-xl-auto(data-aos="fade-right")
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img69.svg" ).m-auto
          .col-xl
            p.mb-0 La correcta aplicación de estos #[b procesos de empaque, congelación y conservación] permite mantener la #[b calidad nutricional, sensorial e higiénica] de las frutas, garantizando alimentos #[b seguros] y aptos para el consumo.

    <!------------------------------------------ SUBTEMA 5 ------------------------------------------>
    Separador
    #t_4_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 4.5 Pulpas de frutas

    p.mb-5 La #[b pulpa de fruta] es un producto de #[b consistencia pastosa] que se obtiene a partir de la #[b desintegración de la fruta fresca], conservando su sabor, color y valor nutricional. Este producto es ampliamente utilizado por su facilidad de conservación y por permitir el aprovechamiento de frutas en óptimo estado de madurez. Para su correcta elaboración, es necesario seguir una serie de pasos que garanticen la #[b calidad y la inocuidad] del producto final.

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Selección de las frutas

    p.mb-5 La selección es una etapa fundamental, ya que la calidad de la pulpa depende directamente del #[b estado físico y del grado de madurez] de la fruta utilizada. Las frutas deben estar sanas, limpias y libres de golpes o magulladuras. A continuación, se presentan algunos ejemplos de criterios a tener en cuenta al momento de la compra:

    .fondo___slider.mb-5
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Piña
                p.mb-0 Debe ceder al presionarla con el dedo, tener olor dulce, no presentar golpes y la zona inferior no debe estar negra.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img70.png', alt='' style="max-width: 500px").m-auto
            
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Mango
                p.mb-0 La cáscara debe ser de color amarillo, firme y sin golpes ni magulladuras.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img71.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Maracuyá
                p.mb-0  Se deben elegir los frutos más pesados; cuando la piel está arrugada indica que está listo para el consumo.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img72.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Fresa
                p.mb-0 Debe ser firme y brillante, con hojas verdes; se deben evitar las que presenten daños o decoloración.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img73.png', alt='' style="max-width: 500px").m-auto

            .row.h-100.justify-content-center.align-items-center
              .col-xl-6.mb-4
                h4 Tomate de árbol
                p.mb-0 La piel debe ser brillante y sin golpes; requiere una manipulación cuidadosa por ser muy delicado.
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img74.png', alt='' style="max-width: 500px").m-auto

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Acondicionamiento de la fruta

    p.mb-5 El #[b acondicionamiento] consiste en preparar la fruta para su posterior transformación en pulpa. En esta etapa se realiza el #[b lavado] y, cuando el proceso lo exige, el #[b pelado].

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img75.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El lavado es indispensable, ya que permite eliminar la contaminación presente en la cáscara. Debe realizarse con #[b agua potable], teniendo en cuenta que cada fruta, por sus características físicas, puede requerir un método de limpieza diferente.
    
    p.mb-5 En algunos casos, es necesario retirar la cáscara de frutas como #[b lulo, tomate de árbol, curuba, maracuyá y mango], operación que puede realizarse con cuchillo o pelador. Para facilitar el pelado, a varias de estas frutas se les puede aplicar un proceso de escaldado, lo que permite desprender la cáscara con mayor facilidad.

    .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img39.svg" style="max-width: 60px").m-auto
      .col
        h3 Licuado, empaque y congelación

    p.mb-5 Una vez realizadas las etapas anteriores, se procede a la #[b elaboración de la pulpa], siguiendo las siguientes recomendaciones:

    .row.align-items-center.mb-5
      .col-xl-4(data-aos="fade-right")
        figure.d-none.d-xl-block
          img(src='@/assets/curso/temas/img90.png', alt='' style="max-width: 350px").m-auto
      .col-xl-8(data-aos="fade-left")
        SlyderF(columnas="col-lg-6 col-xl-6")
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/temas/img76.svg' style="max-width: 90px").m-auto
            h4.mb-3.estilo-text Licuado
            p.mb-0 La fruta debe licuarse sin adicionar agua.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/temas/img77.svg' style="max-width: 90px").m-auto
            h4.mb-3.estilo-text Colado
            p.mb-0 La pulpa se pasa por un colador para retirar semillas o residuos sólidos.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/temas/img78.svg' style="max-width: 90px").m-auto
            h4.mb-3.estilo-text Empaque
            p.mb-0 Se empaca en la mayor cantidad posible (por libras), retirando el aire del empaque.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/temas/img88.svg' style="max-width: 90px").m-auto
            h4.mb-3.estilo-text Conservación
            p.mb-0 Se almacena en el congelador para prolongar su vida útil.
          .tarjeta.color-acento-botones.ajuste___carrusel_card.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/temas/img89.svg' style="max-width: 90px").m-auto
            h4.mb-3.estilo-text Conservación adicional
            p.mb-0 Se puede adicionar #[b ácido cítrico] para mejorar la conservación y retardar la oxidación.
          
    p.mb-0 La aplicación adecuada de estos pasos permite obtener #[b pulpas de frutas seguras, de buena calidad y aptas para el consumo], facilitando su almacenamiento y uso posterior sin comprometer sus características sensoriales ni su inocuidad.

</template>

<script>
export default {
  name: 'Tema4',
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
