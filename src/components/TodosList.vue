<template>
  <div>
    <div>LIST</div>
    <div v-for="i in 10" :key="i" class="flex">
      <div>{{ i }}</div>

      <TodosTask />
    </div>
  </div>
</template>

<script setup lang="ts">
// import { ref } from 'vue';
import TodosTask from './TodosTask.vue';

defineOptions({
  name: 'TodosList',
});
</script>
