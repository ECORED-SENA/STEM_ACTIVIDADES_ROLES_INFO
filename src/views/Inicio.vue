<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Metodología STEM: didácticas activas y roles en el aula
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Metodología STEM: didácticas activas y roles en el aula
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 41220018
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en semanas: 
                p.banner-principal__datos__item__texto 4 Semanas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2oNhGHrX9fw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenido a este ambiente virtual de aprendizaje que surge en el marco de la educación STEM enfocada desde la Ciencia, la Tecnología, la Ingeniería y las Matemáticas. Debido a que esta involucra las formas de enseñar y aprender convoca a los profesores a su reflexión y aplicación en su contexto académico; pero ¿cómo implementar la educación STEM desde el rol del profesor?, es una interesante pregunta que tratará de orientar el presente curso.
    
    p.mt-3 Para iniciar, observe el video que se presenta como punto de partida.

    .video.mt-4
      | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2oNhGHrX9fw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Las dinámicas sociales están cambiando y exigiendo transformaciones en los proyectos educativos y curriculares de las instituciones de educación. Hoy la educación debe revisar estas dinámicas para desarrollar capacidades en los aprendices que respondan a las necesidades de una sociedad del conocimiento, y para ello, se debe reconocer que el conocimiento científico es un aspecto importante para cualificar a lo largo de los proyectos de vida de las personas. Hacer esto conlleva a una educación orientada a conectar la escuela con la vida.

    p.mt-3 En este sentido y como respuesta a lo anterior se diseña el presente curso para proponer la educación STEM como una solución educativa direccionada a crear escenarios de aprendizaje pensados desde la Ciencia, la Tecnología, la Ingeniería y las Matemáticas, con el fin de construir las condiciones de una sociedad del conocimiento que incluya una variedad de competencias básicas que preparen al recurso humano para enfrentar estos desafíos; pero hacer esto implica un proceso de transformación del pensamiento de los profesores y la implementación de  diversas estrategias didácticas que le permitan a los involucrados plantear soluciones a problemas reales de su entorno.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    p #[strong 240201064.] Orientar investigación formativa según referentes técnicos.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    p Profesionales relacionados con el área educativa.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso

    p El egresado del curso estará capacitado para:

    ul
      li 
        i.fas.fa-check
        |  Identificar y desarrollar estrategias didácticas desde el enfoque de la educación STEM.
      li 
        i.fas.fa-check
        |  Analizar actividades para el desarrollo del pensamiento, acordes con la metodología STEM.
      li
        i.fas.fa-check
        |  Formular propuestas curriculares acordes con las necesidades de su contexto y planeadas desde la educación STEM.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica

    p Centrada en la construcción de la autonomía para garantizar la calidad en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales, soportadas en el uso de las Tecnologías de la Información y la Comunicación (TIC), integradas en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.

    p.mt-3 Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje, que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:

    ul
      li 
        i.fas.fa-check
        |  El instructor - tutor
      li 
        i.fas.fa-check
        |  El entorno
      li
        i.fas.fa-check
        |  Las TIC
      li
        i.fas.fa-check
        |  El trabajo colaborativo
  

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5
    .titulo__template--a.mb-4
      span.h4 7. Créditos

    Creditos

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({}),
}
</script>

<style lang="sass"></style>
