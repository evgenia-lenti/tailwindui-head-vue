<template>
  <div class="flex flex-col">
    <div class="-my-2 sm:-mx-6 lg:-mx-8">
      <div class="py-2 align-middle inline-block min-w-full sm:px-6 lg:px-8">
        <div class="shadow border-b border-gray-200 sm:rounded-lg">
          <table class="table min-w-full divide-y divide-gray-200">
            <slot/>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import { defineComponent } from 'vue';

export default /*#__PURE__*/defineComponent({
  name: 'TableComponent', // vue component name
  data() {
    return {

    };
  }
});
</script>

