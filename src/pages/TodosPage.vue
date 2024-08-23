<template>
  <q-page class="row items-center justify-evenly">
    <TodosList />
  </q-page>
</template>

<script setup lang="ts">
// import { ref } from 'vue';
import TodosList from '../components/TodosList.vue';

defineOptions({
  name: 'TodosPage',
});
</script>
