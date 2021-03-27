<template>
  <div>
    <v-card
      min-height="100px"
      flat
      tile
      color="#647547"
      class="d-flex justify-center white--text"
    >
      <v-card-title>
        <p class="d-none d-md-flex display-1 my-0">Nosotros</p>
        <p class="d-md-none title my-0">Nosotros</p>
      </v-card-title>
    </v-card>
    <v-container class="d-flex justify-center">
      <div class="all-text py-16 max-width">
        <div class="text-mivico">
          <h2 class="display-2 font-weight-bold my-10 color-title">Misión</h2>
          <p class="text-justify">
            Somos una empresa dedicada a la producción y comercialización de
            productos cosméticos para aquellas mujeres que buscan el
            fortalecimiento, cuidado y crecimiento acelerado de cejas y pestañas
            por medio de componentes naturales qué brinden seguridad y
            disminuyan los riesgos que pueden ocurrir al usar productos
            químicos.
          </p>
        </div>
        <div class="text-mivico">
          <h2 class="display-2 font-weight-bold my-10 color-title">Visión</h2>
          <p class="text-justify text-black">
            Para el 2026 Seremos una empresa con distribuidoras especializadas
            en cada rincón del Valle de Aburra con un amplio portafolio de
            productos de belleza y cuidado personal, siempre hablando con
            transparencia, veracidad y demostrando que se pueden lograr
            productos efectivos, de alta calidad, 100% naturales y amigables con
            él medio ambiente.
          </p>
        </div>
        <div class="text-mivico pb-5">
          <h2 class="display-2 font-weight-bold my-10 color-title">
            Valores Corporativos
          </h2>
          <ul class="text-justify values-list">
            <li>
              Amabilidad: <br />
              Siempre tenemos una actitud cálida y cortes con nuestros clientes.
            </li>
            <br />
            <li>
              Honestidad: <br />
              Actuamos siempre basándonos en la verdad y con coherencia, así nos
              encargamos de cumplir con cada uno de los objetivos que nos
              proponemos.
            </li>
            <br />
            <li>
              Responsabilidad: <br />
              Hacemos lo que se requiera para cumplir a nuestros clientes.
            </li>
            <br />
            <li>
              Servicio: <br />
              Con amabilidad, efectividad y atención oportuna a las necesidades
              de los clientes.
            </li>
            <br />
            <li>
              Respeto: <br />
              Por la gente, la competencia, el medio ambiente y por lo que
              hacemos.
            </li>
            <br />
            <li>
              Conciencia ambiental: <br />
              Estamos convencidos de que el cuidado del medio ambiente requiere
              de todos, por ello lo tenemos muy presente en el desarrollo de
              cada uno de nuestros procesos y productos.
            </li>
          </ul>
        </div>
      </div>
    </v-container>
  </div>
</template>

<script>
export default {}
</script>

<style>
.max-width {
  max-width: 900px !important;
}

.color-title {
  color: #647547;
}
</style>
