<template>
  <div id="app">
    {{ message }}
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    message: String,
  },
};
</script>
