<template>
  <div>
    <TodoHeader />

    <TodoMain :taches="todos" />

    <TodoFooter />
  </div>
</template>

<script setup lang="ts">
import TodoHeader from '@/components/TodoHeader.vue'
import TodoMain from '@/components/TodoMain.vue'
import TodoFooter from '@/components/TodoFooter.vue'

interface Todo {
  id: number
  title: string
  complete: boolean
}
const todos: Todo[] = [
  {
    id: 1,
    title: 'Tâche 1',
    complete: true
  },
  {
    id: 2,
    title: 'Tâche 2',
    complete: false
  },
  {
    id: 3,
    title: 'Tâche 3',
    complete: false
  },
  {
    id: 4,
    title: 'Tâche 4',
    complete: false
  },
  {
    id: 5,
    title: 'Tâche 5',
    complete: false
  }
]
</script>

<style scoped></style>
