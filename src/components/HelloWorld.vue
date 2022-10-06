<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Insert test code here
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
h1 {
  font-family: "Berlin Sans FB Demi",serif;
}
</style>
