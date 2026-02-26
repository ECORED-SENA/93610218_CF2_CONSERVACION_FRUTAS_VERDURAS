<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema:
        'Manipulación y conservación de alimentos: seguridad, técnicas y prevención',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> identificar los conceptos clave sobre la manipulación adecuada de alimentos, las técnicas de conservación, las prácticas higiénicas y la prevención de la contaminación en la industria alimentaria.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO.',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es el principal objetivo de la manipulación de alimentos?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Prolongar la vida útil de los alimentos sin perder su sabor.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Evitar la contaminación y mantener sus propiedades físicas.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Hacerlos más atractivos visualmente para el consumidor.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reducir el costo de producción.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: '¿Quiénes son considerados manipuladores de alimentos?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Solo los cocineros profesionales.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Todas las personas involucradas en el proceso de transformación o manipulación.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Solamente los trabajadores en la industria de restaurantes.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Aquellos que distribuyen alimentos en supermercados.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: '¿Qué tipo de contaminación se puede dar en los alimentos?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Solo biológica.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Física y mecánica únicamente.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Física, química y biológica.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Contaminación genética.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Cuál es la finalidad del escaldado antes de congelar verduras?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Evitar que pierdan el color.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Desactivar enzimas e inhibir microorganismos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Hacerlas más blandas al cocinarlas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Eliminar los pesticidas por completo.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Qué temperatura se recomienda para mantener los alimentos refrigerados?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: '10 - 12 °C.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: '5 - 7 °C.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: '1 - 3 °C.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: '18 - 20 °C.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto: '¿Qué es la contaminación cruzada?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'El uso excesivo de sal en los alimentos.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'El contacto directo con productos desinfectados.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Transferencia de microorganismos entre alimentos por malas prácticas.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Una técnica para prolongar la vida útil del alimento.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Cuál es una medida de protección que debe tomar un manipulador de alimentos?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Usar ropa colorida y sin gorro.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'No usar maquillaje ni accesorios.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'No lavarse las manos para evitar resequedad.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Usar perfumes para neutralizar olores.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué método de conservación es más adecuado para largos períodos?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Pasteurización.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Congelación.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Refrigeración.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Escaldado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: '¿Qué significa atmósfera modificada?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Almacenar alimentos en espacios oscuros.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Reducir la humedad del entorno.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Reducir el oxígeno y aumentar CO₂ y nitrógeno.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto:
                'Aumentar la presión del aire donde se guarda el alimento.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Qué tipo de frutas no deben refrigerarse por riesgo de pasmarse?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Manzana, pera, uva.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Banano, piña, mandarina.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Mango, lulo, fresa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Tomate de árbol, maracuyá, curuba.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'El uso de guantes rotos está permitido si se lavan con frecuencia.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'El Clostridium botulinum es un microorganismo indicador en procesos de esterilización.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto:
            'La liofilización es un método económico de conservación de alimentos.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto:
            'Los alimentos deshidratados pesan menos y ocupan menos espacio.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            'No es necesario lavar las frutas si vienen prelavadas y empacadas herméticamente.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
