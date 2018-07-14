<template>
  <div class>
    <h1>{{ msg }}</h1>
    <router-link :to="{name:'HelloWorld'}">hello world</router-link>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: function() {
    return {
      msg: "Home"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
