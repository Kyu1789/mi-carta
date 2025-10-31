<template>
  <q-layout view="lHh Lpr lFf">

    <mi-encabezado />

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script setup>
// Importamos tu componente de encabezado para poder usarlo
import MiEncabezado from 'components/MiEncabezado.vue'

// (Hemos borrado todo el código del menú lateral que estaba aquí)
</script>