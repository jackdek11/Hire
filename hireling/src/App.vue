<script setup lang="ts">

</script>

<template>
  <div class="w-full h-full">
    <div class="custom-bg-color ">
    </div>
  </div>
</template>

<style scoped>
.custom-bg-color {
  position: absolute;
  width: 20vw;
  bottom: 0px;
  left: 0px;
  height: 30vh;
  background-color: var(--vt-c-powder);
  border-radius: 1rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
