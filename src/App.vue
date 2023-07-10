<template>
  <div>
    <div>{{greet}} I am {{name}} . I am {{age}} years old.</div>
    <div v-html="ex"></div>
  </div>
</template>

<script>
export default ({
  name: 'app',
  data() {
    return{
      greet: 'Hello',
      name: 'Washim Bari',
      age: 25,
      ex: '<b>Hello</b>'
    }
  },
})
</script>

<style>

</style>
