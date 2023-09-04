<template>
  <svg
    :width="width"
    :height="height"
    viewBox="0 0 10 9"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <circle cx="6.33823" cy="3.79411" r="2.58824" :stroke="color" />
    <path d="M3.91171 5.55884L1.26465 8.2059" :stroke="color" />
  </svg>
</template>
<script>
export default {
  props: {
    width: {
      type: Number,
      default: 10,
    },
    height: {
      type: Number,
      default: 9,
    },
    color: {
      type: String,
      default: "#F6F6F6",
    },
  },
};
</script>
