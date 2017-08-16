<template>
  <div class="hello">
    <form id="slick-login">
      <label for="username">username</label><input type="text" name="username" placeholder="me@tutsplus.com">
      <label for="password">password</label><input type="password" name="password" placeholder="password">
      <input type="submit" value="Log In">
    </form>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
