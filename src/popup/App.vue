<template>
  <div class="container">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hey, it is the Popup page running on Vue.js!',
    };
  },
};
</script>

<style scoped lang="scss">
  .container {
    text-align: center;

    h1 {
      font-weight: 600;
    }
  }
</style>