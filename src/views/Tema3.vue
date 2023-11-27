<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Partes interesadas
    p.mb-5(data-aos='fade-right') #[strong.txt-color-acento-contenido Una parte interesada, o también conocida como “#[em stakeholder]”, es cualquier individuo, grupo de interés u organización que puede influir en las labores de una empresa]. Por otro lado, una parte interesada puede ser una persona interna o externa de una organización que puede afectar las actividades que desarrolla; pueden estar representadas por los clientes, proveedores, trabajadores, propietarios de una empresa, inversionistas, gobierno, entre otros, como se observa en la siguiente figura.
    .margin-n.p-5.mb-5(style='background-color: #FFF9ED' data-aos="zoom-in")
      .row.justify-content-center.align-items-center
        .col-lg-5.col-8
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 9
            span Partes interesadas internas y externas
          img(src='@/assets/curso/temas/tema2/6.svg', alt='Esquema de las partes internas (empleados, gerentes y propietarios) y partes externas (proveedores, sociedad, gobiernos, acreedores y clientes).')
        .col-lg-5.col-8
          img(src='@/assets/curso/temas/tema2/7.svg', alt='')
      hr.border-3
    //TODO agregar el enlace ---------------------------------------------------------
    .tarjeta.bg-color-adicional-2.p-4.mb-5(data-aos="zoom-in")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/temas/tema1/10.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h4.mb-1 Partes interesadas #[em stakeholders]
              p.text-small.mb-0 Como ampliación a este tema, observar el video: “partes interesadas #[em stakeholder]”, que se encuentra en el material complementario.
            .col-sm-auto
              a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=9AtaIAZEu0c" target="_blank")
                span Ver video
                i.fas.fa-video
    p.mb-5(data-aos='fade-right') Según la norma ISO 9001:2015, las partes interesadas se dividen en partes internas y externas; del mismo modo, cada parte establece unos actores adecuados para la aplicación del sistema de gestión de calidad, las cuales son:
    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-4.mb-lg-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/1.svg' alt='AvatarTop' style='width: 120px')
          div(style='background-color: #FAD6C3').p-5.h-100.pt-4
            .titutlo.rounded-pill.d-inline-block.p-3.bg-white.mt-5.d-flex.justify-content-center.mb-3
              h4.mb-0.text-center Clientes
            p Las empresas deben ofrecer productos o servicios que cumplan con todos los estándares de calidad y garantías con el propósito de satisfacer las expectativas de los clientes.
      .col-lg-4.mb-lg-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/2.svg' alt='AvatarTop' style='width: 120px')
          div(style='background-color: #FAD6C3').p-5.h-100.pt-4
            .titutlo.rounded-pill.d-inline-block.p-3.bg-white.mt-5.d-flex.justify-content-center.mb-3
              h4.mb-0.text-center Recursos humanos
            p Busca el desarrollo profesional, la seguridad en el trabajo, los planes de carrera y la orientación de los colaboradores, para lograr una ventaja competitiva. Todo esto se toma en cuenta al momento de definir el entorno de la empresa.
      .col-lg-4.mb-lg-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/3.svg' alt='AvatarTop' style='width: 120px')
          div(style='background-color: #FAD6C3').p-5.h-100.pt-4
            .titutlo.rounded-pill.d-inline-block.p-3.bg-white.mt-5.d-flex.justify-content-center.mb-3
              h4.mb-0.text-center Accionistas, socios o propietarios
            p Son los encargados de buscar mejora continua en sus procesos, para poder crecer la organización, con el fin de mejorar su rentabilidad y productividad, reducir costos y aumentar los beneficios.
    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-4.mb-lg-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/4.svg' alt='AvatarTop' style='width: 120px')
          div(style='background-color: #FAD6C3').p-5.h-100.pt-4
            .titutlo.rounded-pill.d-inline-block.p-3.bg-white.mt-5.d-flex.justify-content-center.mb-3
              h4.mb-0.text-center Proveedores
            p Es importante mantener la relación con los proveedores, porque proporcionan los materiales que se requieren para el desarrollo de las actividades.
      .col-lg-4.mb-lg-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/5.svg' alt='AvatarTop' style='width: 120px')
          div(style='background-color: #FAD6C3').p-5.h-100.pt-4
            .titutlo.rounded-pill.d-inline-block.p-3.bg-white.mt-5.d-flex.justify-content-center.mb-3
              h4.mb-0.text-center Competencia
            p Investigar quiénes son sus competidores permitirá la identificación de amenazas y tener una estrategia para la reacción frente a dicha amenaza.
      .col-lg-4.mb-lg-0.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/6.svg' alt='AvatarTop' style='width: 120px')
          div(style='background-color: #FAD6C3').p-5.h-100.pt-4
            .titutlo.rounded-pill.d-inline-block.p-3.bg-white.mt-5.d-flex.justify-content-center.mb-3
              h4.mb-0.text-center Agentes sociales
            p Las organizaciones son instituciones sociales que comparten en todo momento con personas, por lo tanto, es esencial promover el respeto e interactuar de forma constante para tener una imagen positiva que los individuos perciben de la organización a nivel corporativo.
    h3(data-aos="fade-right") Metodologías de selección y priorización de partes interesadas.
    p.mb-5(data-aos='fade-right') Un mapeo de #[em stakeholders] es una ilustración visual de las personas que pueden afectar en un plan organizacional e identificar cómo están relacionadas. Para su realización, se deben tener en cuenta los siguientes pasos:
    TabsA.color-acento-botones.mb-5(data-aos="zoom-in")
      //- .tarjeta debe ir acompañado de una de una de estas clases =>
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.p-4(titulo="a. Identificar" style='background-color: #F3EDFF; border: 4px solid #E3D8FF')
        .row.justify-content-center.mb-5
          .col-md-6.mb-4.mb-md-0
            h4 Identificar a las partes interesadas
            p  La fase inicial es elaborar un #[em brainstorming] o lluvia de ideas, donde se identificará a todas las partes interesadas: organizaciones, grupos o personas que se puedan ver influenciadas en el proyecto, que tienen una afectación de este o algún problema en su éxito.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema3/7.jpg', alt='Texto que describa la imagen').mb-3
      .tarjeta.p-4(titulo="b. Analizar" style='background-color: #F3EDFF; border: 4px solid #E3D8FF')
        .row.justify-content-center.mb-5
          .col-md-6.mb-4.mb-md-0
            h4 Analizar
            p  En el segundo paso, se fijarán funciones y proyecciones de las partes interesadas, de tal modo que se detectará y especificará qué tan relevantes son los #[em stakeholders] hallados y cuál es su grado de influencia en el ejercicio.
            a.boton.color-acento-botones.indicador__container(@click="modal1 = true")
              span Ampliar imagen
              i.fas.fa-search
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema3/8.svg', alt='Diagrama de skateholders en los que se encuentran: consumidores, accionistas, empleados, proveedores, comunidades, medios, ONG, consumidores, Gobiernos e inversionistas.').mb-3
            figcaption Nota. Adaptado de Benavides (2016).
      .tarjeta.p-4(titulo="c. Priorizar" style='background-color: #F3EDFF; border: 4px solid #E3D8FF')
        .row.justify-content-center.mb-5
          .col-md-6.mb-4.mb-md-0
            h4 Priorizar
            p  Este paso consiste en comprender las necesidades de los #[em stakeholders] y cómo se perciben en el proyecto. Por esta razón, es indispensable clasificar los grupos de interés claves y establecer sus acciones comunicacionales primordiales. Cabe destacar que cada rol que tendrá un grupo de interés y su grado de afectación determinarán las actividades que debe asumir.
            a.boton.color-acento-botones.indicador__container(@click="modal2 = true")
              span Ampliar imagen
              i.fas.fa-search
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema3/9.svg', alt='Matriz para comprender la percepción de los skateholders entre el poder e interés; en este caso, mantener satisfecho, gestionar atentamente, monitorear y mantener informado.').mb-3
            figcaption  Nota. Adaptado de Calvo (s. f.).
      .tarjeta.p-4(titulo="d. Comunicaciones" style='background-color: #F3EDFF; border: 4px solid #E3D8FF')
        .row.justify-content-center.mb-5
          .col-md-6.mb-4.mb-md-0
            h4 Comunicaciones con las partes interesadas
            p  Cuando ya están definidos los grupos de interés cruciales, se iniciará a elaborar y diseñar un plan comunicacional que integre a todos.
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema3/10.jpg', alt='').mb-3
    ModalA(:abrir-modal.sync="modal1")
      figure
        img(src='@/assets/curso/temas/tema3/8.svg', alt='Diagrama de skateholders en los que se encuentran: consumidores, accionistas, empleados, proveedores, comunidades, medios, ONG, consumidores, Gobiernos e inversionistas.')
    ModalA(:abrir-modal.sync="modal2")
      figure
        img(src='@/assets/curso/temas/tema3/9.svg', alt='Matriz para comprender la percepción de los skateholders entre el poder e interés; en este caso, mantener satisfecho, gestionar atentamente, monitorear y mantener informado.')

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    modal1: false,
    modal2: false,
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
