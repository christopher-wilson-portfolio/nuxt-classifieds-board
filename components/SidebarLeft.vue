<script setup lang="ts">

</script>

<template>
  <aside class="flex flex-col content-center">
    <h1 class="text-center">Classifieds</h1>

    <main class="flex flex-col text-center">
      <NuxtLink to="/create-posting">create a posting</NuxtLink>
      <NuxtLink to="my-account">my account</NuxtLink>

      <section id="search">
        <input type="search" placeholder="search classifieds">
      </section>

      <section id="event-calendar"></section>

      <section id="site-links"></section>

      <section id="other-links"></section>
    </main>
  </aside>
</template>

<style scoped>
  aside {
    background-color: rgb(244, 244, 244);
    width: 198px;
  }
</style>
