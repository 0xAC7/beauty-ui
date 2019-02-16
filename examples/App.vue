<template>
  <div id="app">
    <Button>按钮</Button>
  </div>
</template>

<script>
import Button from '../packages/components/button';

export default {
  name: 'app',
  components: {
    Button,
  },
};
</script>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
