<template>
  <tbody class="bg-white divide-y divide-gray-200">
  <slot/>
  </tbody>
</template>

<script>

import { defineComponent } from 'vue';

export default /*#__PURE__*/defineComponent({
  name: 'TableBody', // vue component name
  data() {
    return {

    };
  }
});
</script>
