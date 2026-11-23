<template>
  <q-page class="q-pa-md">
    <h1 class="text-h5">Moja opažanja</h1>
    <p>Ovdje će biti popis spremljenih opažanja.</p>
  </q-page><p>ID opažanja: {{ route.params.id }}</p>
</template>
<script setup>
import { useRoute } from 'vue-router';
const route = useRoute();
</script>
