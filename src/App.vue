<template>
  <div id="app">
    <LogoComponent />
    <FirstComponent msg="First Component" />
    <SecondComponent msg="Second Component" />
    <hr>
    <InputBindingComponent />
    <hr>
    <LifeCycleComponent />
    
  </div>
</template>

<script>
import LogoComponent from './components/LogoComponent.vue'
import FirstComponent from './components/FirstComponent.vue'
import SecondComponent from './components/SecondComponent.vue'
import InputBindingComponent from './components/InputBindingComponent.vue'
import LifeCycleComponent from './components/LifeCycleComponent.vue'

export default {
  name: 'App',
  components: {
    LogoComponent,
    FirstComponent,
    SecondComponent,
    InputBindingComponent,
    LifeCycleComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
