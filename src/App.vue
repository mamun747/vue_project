<template>
  <div>
    <helloworld/>
  </div>
</template>

<script setup>
import { defineAsyncComponent } from 'vue';

// Dynamically import the HelloWorld component
const helloworld = defineAsyncComponent(() => import('./components/list.vue'));
</script>