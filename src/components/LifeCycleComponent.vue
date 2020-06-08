<template>
  <div>
    <h1>Hook Life Cycle</h1>
    <p>กรุณาเปิด console log เพื่อดูว่า การทำงานของ Hook เป็นอย่างไร</p>
    
  </div>
</template>

<script>
export default {
  name: 'LifeCycleComponent',
  data: function() {
      return {
          message: ''
      }
  },
  beforeCreate: function() {
      this.message = 'Hook Before Create'
      console.log(this.message)
  },
  created: function() {
      this.message = 'Hook Create'
      console.log(this.message)
  },
  beforeMount: function() {
      this.message = 'Hook Before Mount'
      console.log(this.message)
  },
  mounted: function() {
      this.message = 'Hook Mount'
      console.log(this.message)
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


