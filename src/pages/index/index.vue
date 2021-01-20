<template>
  <div class="text-center">
    <div class="mt-2 bg-red-200">
      {{ title }}
    </div>
  </div>
</template>

<script lang="ts">
  import Vue from "vue";
  export default Vue.extend({
    data() {
      return {
        title: "Hello",
      };
    },
    onLoad() {},
    methods: {},
  });
</script>
