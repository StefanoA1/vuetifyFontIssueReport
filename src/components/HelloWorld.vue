<template>
  <div class="hello">
    <h1>This should be Montserrat, which it isn't: aaaa gggg</h1>
    <h3>This should be Montserrat, which it isn't: aaaa gggg</h3>
    <br>
    <p>This should be Open Sans, which it is: aaaa gggg</p>
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
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
