<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    //- .bloque-texto-a debe ir acompañado de una de una de estas clases => 
    //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
    .row.justify-content-center
      .col-lg-11
        .bloque-texto-a.color-acento-contenido.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/introduccion/img1.svg', alt="Seguridad de la información").mx-auto
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p La seguridad de la información, hoy por hoy, es uno de los temas más importantes en el mundo tecnológico, debido al incremento elevado de los ataques cibernéticos a los que los usuarios están expuestos. Los smartphones pasaron de ser una moda a ser una herramienta de trabajo y/o también un estilo de vida. Los ciberatacantes, día a día, se las ingenian para que los usuarios caigan en sus nuevas fechorías, sin que estos últimos lo sepan; es por esta razón que hay organizaciones que exigen tratar los datos haciendo uso de estándares los cuales disminuyen esa brecha de riesgo.
    
    .cajon.color-acento-contenido.p-4.mb-4
        p En relación con la elaboración del componente, es importante especificar que se abordaron varios autores conocidos en el campo de la seguridad en las redes; se referencian en la bibliografía aquellos de quienes se tomaron los conceptos y ejemplos; respetando al igual que ellos, la recopilación y producción de material para el uso en educación. Es preciso señalar que el conocimiento es social y, por lo tanto, es para usarlo; cuando se investiga especialmente en el campo de la educación se busca aportar a la formación de quienes necesitan adquirir el conocimiento. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de las redes de datos.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
