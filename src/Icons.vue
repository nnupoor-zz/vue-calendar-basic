<template>
  <svg v-bind:width="width" :height="height">
    <use v-bind="{ 'xlink:href': '#sprite_' + id }" />
  </svg>
</template>

<script>
  export default {
    props: ['width','height','id']
  }
</script>

<style scoped>
svg {
  cursor: pointer;
}
</style>