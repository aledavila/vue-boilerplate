<template>
  <div class="title">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'title',
  data() {
    return {
      msg: 'Home Page',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
