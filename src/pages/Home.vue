<template>
  <div class="home">
    <div class="title">
      <h1>{{msg}}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      msg: 'Welcome to Your Vue.Js App',
    };
  },
};
</script>
