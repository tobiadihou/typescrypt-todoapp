<template>
    <div>
        
        <TodoHeader />
      
        <TodoMain />
        
        <TodoFooter />
    </div>
</template>

<script setup lang="ts">
import TodoHeader from '@/components/TodoHeader.vue';
import TodoMain from '@/components/TodoMain.vue';
import TodoFooter from '@/components/TodoFooter.vue';
</script>

<style scoped></style>