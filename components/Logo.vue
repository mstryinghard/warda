<template>
  <h1 class="inline-flex font-mono tracking-tight text-white inline">
    <span>&#123;</span>
    <span v-if="close">/</span>
    <span>exp</span>
    <span>:</span>
    <span>warda</span>
    <span>&#125;</span>
  </h1>
</template>

<script>
export default {
  props: {
    close: {
      type: Boolean,
      default: false
    }
  }
}
</script>
