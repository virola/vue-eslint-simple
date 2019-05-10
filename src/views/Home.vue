<template>
  <div class="home">
    <h1>首页</h1>
    <div class="conainer"></div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      points: [],
      startTime: Date.now(),
    };
  },
};
</script>
