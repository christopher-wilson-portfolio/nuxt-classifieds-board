<script setup lang="ts">

</script>

<template>
  <aside>
    <section id="language">
      <select name="languages" id="select-language">
        <option value="en">English</option>
      </select>
    </section>

    <section id="loctations">
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
    background-color: rgb(244, 244, 244);
  }
  ul {
    list-style-type: none;
  }
</style>
