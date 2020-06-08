<template>
  <div>
    <h1 class="h1Color">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'SecondComponent',
  props: {
    msg: String
  }
}
</script>
