<template>
    <div v-html="html"></div>
    <div v-html="popup"></div>
    <h2 v-bind:id="exampleId">Heading id </h2>
    <h2 v-bind:class="exampleClass">Heading class</h2>
    <button v-bind:disabled="exampleDisabled">Button</button>
</template>

<script>

export default({
    setup() {
       return {
        html: "<b>Washim Bari</b>",
        popup: `<a href="#" onclick="alert('Win prize!')" >Win Prize!</a>`,
        exampleId: 'exampleId',
        exampleClass: 'exampleClass',
        exampleDisabled: true
       }
    },
})
</script>

<style scoped>

</style>
