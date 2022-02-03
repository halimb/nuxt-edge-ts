<template>
  <div
  @click="
    myFunc()
    myVar = 42
  "
  ></div>
</template>

<script lang="ts">
import Vue from "vue"

export default Vue.extend({
  data: () => {
    return {
      myVar: 0
    }
  },
  methods: {
    myFunc() {}
  }
})
</script>
