<template>
  <div>
      <h1>Minimal Vue Webpack</h1>
      <div>
          <test/>
      </div>
  </div>
</template>

<script>
import { defineComponent } from 'vue'; 
import test from './components/test.vue';

export default defineComponent({
components: { test },
  name: 'App'
});

</script>

<style scoped>
  h1 {
      width: 100%;
      text-align: center;
      margin-top: 10px;
  }

  img {
      display: block;
      margin: auto;
  }
</style>