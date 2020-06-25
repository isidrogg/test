<script lang="ts">
import Vue from 'vue';
import Ejemplo from '@/ejemplo.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    Ejemplo
  }
});
</script>

<template>
  <div id="app">
    <ejemplo />
  </div>
</template>
