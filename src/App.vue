<template>
  <div id="app" class="app container mx-auto">
    <router-view/>
  </div>
</template>

<style lang="scss">
@import url("~@/styles/main.scss");

html,
body {
  @apply h-full;
}

.app {
  @apply h-full font-gotham-regular;
}

</style>
