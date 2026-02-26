<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .color___box_1
      .px-5

        p.mb-5 La manipulación de alimentos es un conjunto de prácticas esenciales que permiten conservar los productos en condiciones seguras para el consumo humano. Estas acciones incluyen desde la selección y limpieza de las materias primas hasta su procesamiento, empaque, almacenamiento y transporte, con el objetivo de mantener la calidad y evitar cualquier tipo de contaminación.

        .row.align-items-center.mb-5.style___box_1.m-0(data-aos="zoom-in")
          .col-xl
            p.mb-0 Una adecuada manipulación garantiza la inocuidad de los alimentos, es decir, que estén libres de agentes físicos, químicos o biológicos que puedan causar enfermedades. Por ello, los manipuladores deben contar con formación en buenas prácticas higiénicas, así como con controles médicos que certifiquen su estado de salud, ya que su rol es clave para proteger la salud pública.
          .col-xl-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/intro/img2.jpg", alt="" ).m-auto
        
        p.mb-0 Además, existen diferentes métodos de conservación como la refrigeración, congelación, deshidratación, pasteurización o el uso de atmósferas modificadas, que permiten alargar la vida útil de frutas y verduras sin afectar su valor nutricional. Aplicar correctamente estas técnicas ayuda a prevenir el deterioro de los alimentos y reduce el riesgo de desperdicio.

</template>

<script>
export default {
  name: 'Introduccion',
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
