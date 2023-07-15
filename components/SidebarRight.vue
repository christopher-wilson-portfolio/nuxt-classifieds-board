<script setup lang="ts">

</script>

<template>
  <aside class="flex flex-col content-center flex-wrap">
    <section id="language">
      <select name="languages" id="select-language">
        <option value="en">English</option>
      </select>
    </section>

    <section id="locations">
      <header>nearby</header>
      <ul>
        <li>location a</li>
        <li>location b</li>
      </ul>
    </section>
  </aside>
</template>

<style scoped>
  aside {
    background-color: var(--color-white);
    width: 114px;
  }

  ul {
    list-style-type: none;
  }
</style>
