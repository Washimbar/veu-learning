<template>
  <div>

    <h2 v-if="num === 0">This is a zero.</h2>
    <h2 v-else-if="num > 0">This is a positive number.</h2>
    <h2 v-else-if="num < 0">This a negative number.</h2>
    <h2 v-else>This is not a number.</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      num: 'hi',
    };
  },
};
</script>

<style lang="scss" scoped>
</style>