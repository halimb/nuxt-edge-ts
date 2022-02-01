<template>
  <div>{{helloWorld}}</div>
</template>

<script lang="ts">
export default {
  computed: {
    // Should cause a typescript error
    helloWorld(): number {
      return "Hello world"
    }
  }
}
</script>
