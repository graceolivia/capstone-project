<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "If this is displayed, Vue is working!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;

}
</style>
