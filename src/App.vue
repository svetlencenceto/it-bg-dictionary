<template>
  <div id="app">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Добре дошли в КодЪ'
    }
  }
}
</script>

<style lang="scss">
h1 {
  text-align: center;
}
</style>
