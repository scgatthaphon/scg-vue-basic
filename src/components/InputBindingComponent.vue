<template>
  <div>
    <h1>Binding ข้อความจาก Input</h1>
    <p class="binding">{{ message }}</p>
    
    <input v-model="message">
  </div>
</template>

<script>
export default {
  name: 'InputBindingComponent',
  data: function() {
      return {
          message: ''
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.binding {
  color: #42b983;
  font-weight: 900;
}
</style>

