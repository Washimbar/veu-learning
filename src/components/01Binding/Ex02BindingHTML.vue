<template>
  <div v-html="html"></div>
  <div v-html="popup"></div>
</template>

<script>
export default {
  setup() {
    return {
      html: "<b>Washim Bari</b>",
      popup: `<a href="#" onclick="alert('Win prize!')" >Win Prize!</a>`,
    };
  },
};
</script>

<style scoped>
</style>