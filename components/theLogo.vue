<template>
  <div class="logo">
    <p :style="{ fontSize: size + 'px', color: color }"><b>dev</b>blog</p>
  </div>
</template>
<script>
export default {
  props: {
    size: {
      type: Number,
      default: 24,
    },
    color: {
      type: String,
      default: "#000000",
    },
  },
};
</script>
