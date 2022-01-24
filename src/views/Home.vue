<template>
  <div class="home">
      <h2>{{msg}}</h2>
  </div>
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue';

export default defineComponent({
  setup() {
    const msg = ref('welcome to use');
    return {
      msg,
    };
  },
});
</script>
<style lang="less" scoped>

</style>
