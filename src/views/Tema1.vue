<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Seguridad de información en la red
    
    p.mb-4 Tradicionalmente las redes cableadas o redes alámbricas se han considerado más seguras que las redes inalámbricas. El uso de internet y la evolución de las comunicaciones han hecho que las instalaciones no sean únicas, sino que pueden situarse a miles de kilómetros. A su vez una red privada virtual permite mediante el uso de Internet, establecer esta conexión realizando una inversión moderada. Una VPN o red privada es, básicamente, una red virtual que se crea dentro de otra red, habitualmente internet. Para un cliente VPN se trata de una conexión que se establece entre su equipo y el servidor, esta conexión es transparente para él, simplemente los datos le son enviados de la misma manera que si llegaran a través de la LAN a la que se conecta. 
    
    //- .bloque-texto-a debe ir acompañado de una de una de estas clases => 
    //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
    .row.justify-content-center.mb-4
      .col-lg-11
        .bloque-texto-a.color-acento-contenido--color2.p-4.p-md-5.mb-5 
            .row.m-0.align-items-center.justify-content-between
              .col-lg-8
                .bloque-texto-a__texto.p-4
                  p.mb-4 Por lo que los IDS [Intrusion Detection Systems - Sistemas de Detección de Intrusiones] son un paso adelante en las funciones que implementan los cortafuegos (firewalls). Existen varias herramientas de detección de intrusos, pero su uso es bastante complejo, algunos ejemplos más representativos son tripwire enterprise (permite detectar las acciones en la red que no se ajustan a la política de seguridad de la empresa, e informar de aquellos que necesitan especial atención) y snort (es una aplicación de código abierto que permite tanto la detección de intrusión como su prevención) (B2B Consultores, 2020).
                  p Este IDS escucha el tráfico de la red en tiempo real y lo relaciona con una serie de normas ya predefinidas, que pueden descargarse desde internet. Cuando encuentra alguna coincidencia alerta sobre ella, hace un log de dicho tráfico o lo ignora, según se ha indicado en la norma (B2B Consultores, 2020).
              .col-lg-4.mb-4.mb-lg-0.align-self-center
                figure
                  img(src='@/assets/curso/tema1/img1.svg', alt="Sistemas de Detección de Intrusiones").mx-auto

    #t_1_1.titulo-segundo
      .h2 1.1 Integridad

    .row.justi-content-center(style="padding-bottom:60px;")
      .col-lg-5.self-align-center
        figure
          img(src='@/assets/curso/tema1/img2.svg', alt="integridad").mx-auto
      .col-lg-7.self-align-center
        p.mb-4 s una característica que permite mantener los datos sin modificaciones no autorizadas, que la información permanezca tal como fue generada, sin manipulación o alteraciones realizadas por personal no autorizado.
        .cajon.color-acento-contenido.p-4.mb-4
          p Hay violación de integridad cuando un empleado, proceso o programa borra o modifica datos importantes que pertenecen a la información. Para conservar la integridad de un mensaje se debe adjuntar los datos de comprobación de integridad, por ejemplo, la firma digital es uno de ellos.

    separador

    #t_1_2.titulo-segundo
      .h2 1.2 Confidencialidad

    .row.justify-content-center.mb-5
      .col-lg-7.align-self-center
        p.mb-2 Según afirma Seguridad en redes (s.f.), es la propiedad de prevenir la divulgación de información a personas o sistemas no autorizados. A grandes rasgos, la confidencialidad es el acceso a la información únicamente por personas que cuenten con la debida autorización.
        p.mb-0 De acuerdo con Seguridad en la red (s.f.):
        .row.justify-content-center
          .col-lg-10
            .bloque-texto-b.color-secundario.p-5
              .bloque-texto-b__texto
                i.fas.fa-quote-left
                p.mb-0 #[strong … en una transacción por internet se requiere que el número de la tarjeta de crédito sea transmitida desde el comprador al comerciante y de este a una red de procesamiento de transacciones. El sistema intenta hacer valer la confidencialidad mediante el cifrado del número de la tarjeta y los datos que contiene la banda magnética durante la transmisión de estos. Si una parte no autorizada obtiene el número de la tarjeta en modo alguno, se ha producido una violación de la confidencialidad. La pérdida de la confidencialidad de la información puede adoptar muchas formas. Cuando alguien mira por encima de su hombro, mientras tiene información confidencial en la pantalla, cuando se publica información privada, cuando una laptop con información sensible sobre una empresa es robada, cuando se divulga información confidencial a través del teléfono, etc. Todos estos casos pueden constituir una violación de la confidencialidad (s.p.).]
                i.fas.fa-quote-right
      .col-lg-5.align-self-center
        figure
          img(src='@/assets/curso/tema1/img3.svg', alt="confidencialidad").mx-auto

    separador  

    #t_1_3.titulo-segundo
      .h2 1.3 Disponibilidad

    .row.justify-content-center
      .col-lg-11
        .bloque-texto-a.color-acento-contenido.p-4.p-md-4.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema1/img4.svg', alt="disponibilidad", style="width:70%;").mx-auto
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p Se define como la capacidad de garantizar que tanto el sistema como los datos van a estar disponibles al usuario en todo momento, por ejemplo, el objetivo de la plataforma SENA Sofia Plus por el hecho de mantener disponible la información de los cursos disponibles. Constantemente está recibiendo consultas, acceso y peticiones, por lo que siempre deberá estar disponible para los usuarios. “La disponibilidad supone que el sistema informático se mantenga trabajando sin sufrir ninguna degradación en cuanto a accesos. Es necesario que se ofrezcan los recursos que requieran los usuarios autorizados cuando se necesiten” (www.pmg-ssi.com, 2018).

    separador


    #t_1_4.titulo-segundo
      .h2 1.4 Ataques a la seguridad de la red


    separador

    #t_1_5.titulo-segundo
      .h2 1.5 Herramientas de seguridad

    #t_1_6.titulo-segundo
      .h2 1.6 Vulnerabilidades y amenazas

    #t_1_7.titulo-segundo
      .h2 1.7 Análisis de seguridad de la red

    #t_1_8.titulo-segundo
      .h2 1.8 Análisis de riesgos

    #t_1_9.titulo-segundo
      .h2 1.9 Matriz de control

    #t_1_10.titulo-segundo
      .h2 1.10 Estimación de la vulnerabilidad

    #t_1_11.titulo-segundo
      .h2 1.11 Requisitos de la seguridad

    #t_1_12.titulo-segundo
      .h2 1.12 Revisión y actualizaciones de la política de la seguridad







  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
