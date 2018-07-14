<template>
  <div class>
    <h1>{{ msg }}</h1>
    <router-link to="/">home</router-link>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data: function() {
    return {
      msg: "Hello World"
    };
  }
};
</script>

<style scoped>
</style>
