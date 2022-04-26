<template>
  <div>Hello {{ value }}</div>
  <div>This site is running on VueJs.</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World!!"
    };
  }
};
</script>
