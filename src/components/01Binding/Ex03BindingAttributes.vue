<template>
  <div>
    <h2 v-bind:id="exampleId">Heading id </h2>
    <h2 v-bind:class="exampleClass">Heading class</h2>
    <button v-bind:disabled="exampleDisabled">Button</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      exampleId: "exampleId",
      exampleClass: "exampleClass",
      exampleDisabled: true,
    };
  },
};
</script>

<style lang="scss" scoped></style>
