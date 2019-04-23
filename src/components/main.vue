<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <button v-on:click="click">Click here</button>
   
  </div>
</template>

<script>
export default {
  name: 'main',
  data () {
    return {
      msg: 'Welcome to EGCO427'
    }
  },
  methods: {
    click: function(){
      alert('Hello')
    }
    
  },
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
