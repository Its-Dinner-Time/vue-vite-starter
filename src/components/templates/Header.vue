<script setup lang="ts"></script>

<template>
  <div>
    <span>Header</span>
  </div>
  <button class="btn-primary">test</button>
</template>

<style scoped lang="scss">
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer components {
  div {
    & span {
      @apply bg-slate-500;
    }
  }
}
</style>
