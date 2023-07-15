<script setup lang="ts">

import SidebarLeft from "~/components/SidebarLeft.vue";
import SidebarRight from "~/components/SidebarRight.vue";
</script>

<template>
  <div class="container flex flex-row justify-between pt-4">
    <SidebarLeft />

    <main>
      <header class="border-1 border-y-1">
        <h1>location</h1>
      </header>

      <section id="link-section" class="link-container">
        <div class="column">
          <ClassifiedLinkBlock section-name="community" columns="2" />
          <ClassifiedLinkBlock section-name="services" columns="2" />
          <ClassifiedLinkBlock section-name="discussion forums" columns="3" />
        </div>
        <div class="column">
          <ClassifiedLinkBlock section-name="housing" columns="1" />
          <ClassifiedLinkBlock section-name="for sale" columns="2" />
        </div>
        <div class="column">
          <ClassifiedLinkBlock section-name="jobs" columns="1" />
          <ClassifiedLinkBlock section-name="gigs" columns="2" />
          <ClassifiedLinkBlock section-name="resumes" columns=0 />
        </div>
      </section>
    </main>

    <SidebarRight />
  </div>
</template>

<style scoped>
  header {
    background-color: rgb(238, 238, 238);
    border: var(--color-grey-dark);
    color: var(--color-grey-dark);
    font-family: "Times New Roman", Times, serif;
    font-size: 1.5rem;
    line-height: 2.5rem;
    margin-bottom: 1.25rem;
    text-align: center;
  }

  main {
    width: 608px;
  }

  .column {
    display: flex;
    flex-direction: column;
    gap: 13px;
  }

  .container {
    gap: 20px;
    margin: 0 auto;
    width: 980px;
  }

  .link-container {
    display: grid;
    grid-auto-flow: column;
    grid-auto-columns: 1fr;
    grid-gap: 1.5rem;
  }
</style>
