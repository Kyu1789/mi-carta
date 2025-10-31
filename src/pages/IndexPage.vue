<template>
  <q-page padding> <mi-descripcion />

    </q-page>
</template>

<script>
// 1. Importamos los componentes que creamos
// (OJO: No importamos MiEncabezado porque lo pondremos en otro lado)
import MiDescripcion from 'src/components/MiDescripcion.vue'

export default {
  name: 'IndexPage',

  // 2. Los "registramos" para poder usarlos en el <template>
  components: {
    MiDescripcion
  }
}
</script>
