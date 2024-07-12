<template>
  <footer class="footer">
    <span class="todo-count"
      ><strong>{{ remaining }}</strong> Tâche{{ remaining > 1 ? 's' : '' }} restante{{
        remaining > 1 ? 's' : ''
      }}</span
    >
    <ul class="filters">
      <li>
        <router-link to="#">Tous</router-link>
        <router-link to="#">En cours</router-link>
        <router-link to="#">Terminés</router-link>
      </li>
    </ul>
    <button class="clear-completed">Eff. tâche terminées</button>
  </footer>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const remaining = ref<number>(5)
</script>

<style scoped></style>
