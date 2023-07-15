<script setup lang="ts">
defineProps({
  columns: Number,
  sectionName: String,
})
</script>

<template>
  <section>
    <header>
      <h2>{{ sectionName }}</h2>
    </header>

    <div class="flex flex-col"></div>
  </section>
</template>

<style>
  header {
    background-color: var(--color-grey-light);
    border-top: 1px solid var(--color-grey-med);
    border-bottom: 1px solid var(--color-grey-med);
  }

  h2 {
    font-size: 1rem;
    font-weight: bold;
    line-height: 28px;
    text-align: center;
  }

  section {
    color: blue;
  }
</style>
