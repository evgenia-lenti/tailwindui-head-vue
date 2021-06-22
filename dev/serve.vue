<template>
  <div id="app">
    <!--    <tailwindui-head-vue-sample />-->
    <table-component>
      <table-head></table-head>

      <table-body></table-body>
    </table-component>
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import TableComponent from "../src/lib-components/table-component";
import TableHead from "../src/lib-components/table-head";
import TableBody from "../src/lib-components/table-body";
// Uncomment import and local "components" registration if library is not registered globally.
// import { TailwinduiHeadVueSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  components: {TableBody, TableHead, TableComponent},
  // components: {
  //  TailwinduiHeadVueSample,
  // }
});
</script>


