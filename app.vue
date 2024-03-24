<script>



</script>

<template>
  <div class="root">
    <MainHeader />
    <MainComponent />
    <MainFooter />
  </div>
</template>


<style lang="scss">

@import 'reset-css';

html, body, #__nuxt{
  height: 100%;
}

.root {
  height: 100%;
  display: grid;
  grid-template-rows: min-content auto min-content;
}


</style>