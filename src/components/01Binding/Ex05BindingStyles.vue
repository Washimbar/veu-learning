<template>
  <div>
    <!-- Simple Inline style -->
    <h2 v-bind:style="{ color: 'red', fontSize: '30px' }">Inline Style</h2>
    <!-- Reuseable inline style -->
    <h2 v-bind:style="inLineStyle">This is example of inline style</h2>
    <!-- Reuseable inline style with multiple style -->
    <h2 v-bind:style="inLineStyle">This is example of inline style</h2>
    <h3 v-bind:style="[inLineStyle, inLineStyle2]">This is example of use of multiple inline style objects</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      inLineStyle: {
        color: "white",
        backgroundColor: "green",
        fontSize: "30px",
        height: "80px",
      },
      inLineStyle2:{
        border: "3px solid",
        borderColor: "red",
      }
    };
  },
};
</script>

<style>
</style>