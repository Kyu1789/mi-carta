<template>
  <div class="q-pa-md">
    <div class="row q-gutter-md justify-center">

      <div class="col-xs-12 col-md-5">

        <q-card class="q-mb-md">
          <q-card-section>
            <div class="text-h6">
              <q-icon name="person" class="q-mr-sm" />
              Sobre Mí
            </div>
          </q-card-section>
          <q-separator />
          <q-card-section>
            <p>
              Soy un estudiante de diseño web apasionado por crear aplicaciones 
              modernas con Vue.js y Quasar. Me especializo en el desarrollo
              de componentes y siempre me gusta aprender nuevos lenguajes de programación.
            </p>
            <p>
              Busco aplicar mis conocimientos en un entorno profesional para
              crecer y aportar valor.
            </p>
          </q-card-section>
        </q-card>

        <q-card>
          <q-card-section>
            <div class="text-h6">
              <q-icon name="construction" class="q-mr-sm" />
              Habilidades Técnicas
            </div>
          </q-card-section>
          <q-separator />
          <q-card-section>
            <q-chip color="primary" text-color="white" icon="fab fa-vuejs">
              Vue.js
            </q-chip>
            <q-chip color="blue-8" text-color="white" icon="fab fa-dev">
              Quasar
            </q-chip>
            <q-chip color="orange-9" text-color="white" icon="fab fa-html5">
              HTML5
            </q-chip>
            <q-chip color="blue-7" text-color="white" icon="fab fa-css3-alt">
              CSS3
            </q-chip>
            <q-chip color="yellow-9" text-color="black" icon="fab fa-js-square">
              JavaScript
            </q-chip>
            <q-chip color="red-7" text-color="white" icon="fab fa-git-alt">
              Git / GitHub
            </q-chip>
          </q-card-section>
        </q-card>

      </div>

      <div class="col-xs-12 col-md-4">

        <q-card>
          <q-card-section>
            <div class="text-h6">
              <q-icon name="contacts" class="q-mr-sm" />
              Contacto y Redes
            </div>
          </q-card-section>
          <q-separator />

          <q-list>

            <q-item>
              <q-item-section avatar>
                <q-icon name="email" color="grey-8" />
              </q-item-section>
              <q-item-section>
                chaynatm1@gmail.com
              </q-item-section>
            </q-item>

            <q-item>
              <q-item-section avatar>
                <q-icon name="phone" color="grey-8" />
              </q-item-section>
              <q-item-section>
                +51 987 654 321
              </q-item-section>
            </q-item>

            <q-item>
              <q-item-section avatar>
                <q-icon name="location_on" color="grey-8" />
              </q-item-section>
              <q-item-section>
                Lima, Perú
              </q-item-section>
            </q-item>

            <q-separator />

            <q-item clickable tag="a" href="https://github.com/tu-usuario" target="_blank">
              <q-item-section avatar>
                <q-icon name="fab fa-github" />
              </q-item-section>
              <q-item-section>
                GitHub
              </q-item-section>
              <q-item-section side>
                <q-icon name="launch" />
              </q-item-section>
            </q-item>

            <q-item clickable tag="a" href="https://linkedin.com/in/tu-usuario" target="_blank">
              <q-item-section avatar>
                <q-icon name="fab fa-linkedin" color="blue-7" />
              </q-item-section>
              <q-item-section>
                LinkedIn
              </q-item-section>
              <q-item-section side>
                <q-icon name="launch" />
              </q-item-section>
            </q-item>

          </q-list>
        </q-card>

      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'MiDescripcion'
  // El script se queda simple, toda la magia está en el <template>
}
</script>

<style scoped>
/* Estilos para que las tarjetas tengan un look más suave */
.q-card {
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
}
</style>