<script setup>
import MAComponent from './components/MAComponent.vue';
import MBComponent from './components/MBComponent.vue';
import MCComponent from './components/MCComponent.vue';
import MDComponent from './components/MDComponent.vue';
</script>

<template>
  <main class="container mx-auto grid gap-4 p-4 grid-cols-3 md:grid-cols-12">
    <m-a-component class="col-span-3" />
    <m-b-component class="col-span-3" />
    <m-c-component class="col-span-3" />
    <m-d-component class="col-span-3" />
  </main>
</template>
