<template>
  <div>
    <h2 v-for="name in fullName" :key="name.firstName">{{name.firstName}} {{name.lastName}}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      fullName: [
        { firstName: "Washim", lastName: "Bari" },
        { firstName: "Masud", lastName: "Biswas" },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>