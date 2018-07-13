<template>
  <div class="header screen-1">
    <div class="overlay"></div>
    test
  </div>
</template>

<script>
export default {
  name: "screen1"
}
</script>

<style scoped lang="scss">
.header {
  position: relative;
  background: url('../assets/images/bg-header.jpg');

  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto;
    display: inline-block;
    max-width: 100%;
    max-height: 100%;
    background-color: rgba(0, 0, 0, .7);
  }
}
</style>
