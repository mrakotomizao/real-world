<template>
  <div>
    <BaseAvatar :url="url" class="avatar"></BaseAvatar>
    <slot name="heading"></slot>
    <slot name="paragraph"></slot>
  </div>
</template>

<script>
export default {
  props: {
    url: {
      type: String,
      default: 'default.png'
    }
  }
}
</script>

<style scoped>
</style>
