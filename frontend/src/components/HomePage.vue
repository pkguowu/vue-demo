<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>
      <router-link to="/subpage">Go to Sub Page</router-link>
      <br><br>
      <router-link to="/trezor">Go to Trezor Demo</router-link>
    </h1>
  </div>
</template>

<script>
export default {
  name: "HomePage",
  data() {
    return {
      msg: "Welcome to Home Page",
      params: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
