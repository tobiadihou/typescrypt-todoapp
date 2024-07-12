<template>
  <header class="header">
    <router-link to="/">
      <h1>Todo header</h1>
    </router-link>

    <input
      type="text"
      class="new-todo"
      autofocus
      autocomplete="off"
      placeholder="Entrez une tâche"
    />
  </header>
</template>

<script setup lang="ts"></script>

<style scoped></style>
