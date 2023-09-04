<template>
  <svg
    :width="width"
    :height="height"
    viewBox="0 0 11 5"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <line y1="0.5" x2="10.5882" y2="0.5" :stroke="color" />
    <line y1="4.02942" x2="10.5882" y2="4.02942" :stroke="color" />
  </svg>
</template>
<script>
export default {
  props: {
    width: {
      type: Number,
      default: 11,
    },
    height: {
      type: Number,
      default: 5,
    },
    color: {
      type: String,
      default: "#f7f7f7",
    },
  },
};
</script>
