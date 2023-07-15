<template>
    <div>
        <h2>Name - {{ name }}</h2>
        <button v-on:click="name = 'Bari'">Change name</button>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                name: "Washim",
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>