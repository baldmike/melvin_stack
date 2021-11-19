<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Click below, an example of Vue Router</h2>

    <div>
      <router-link v-bind:to="{ name: 'Posts' }" class="">Posts</router-link>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'You are now rocking the MEVN stack'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
