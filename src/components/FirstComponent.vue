<template>
  <div>
    <h1 class="h1Color">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'FirstComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.h1Color {
  color: #42b983;
}
</style>
