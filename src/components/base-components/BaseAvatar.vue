<template>
  <div class="image">
    <img
      :src="url"
      alt="Avatar"
      class="avatar"
      :style="{width: width + 'px', height:height + 'px'}"
    />
  </div>
</template>

<script>
export default {
  props: {
    url: String,
    width: {
      type: String,
      default: '50'
    },
    height: {
      type: String,
      default: '50'
    }
  }
}
</script>

<style scoped>
.avatar {
  vertical-align: middle;
  border-radius: 50%;
}
</style>
