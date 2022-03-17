<template>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name: "greeting-page",
  props: {
    title: {
      type: String,
      default: "hello",
    },
  },
};
</script>
