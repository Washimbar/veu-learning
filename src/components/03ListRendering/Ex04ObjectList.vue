<template>
    <ul v-for="(value, key, index) in myInfo" :key="index">
       <li>Value : {{ value }}</li>
       <li>Key : {{ key }}</li>
       <li>Index : {{ index }}</li>
    </ul>
</template>

<script>
    export default {
        data(){
            return {
                myInfo: {
                    name: "Washim Bari",
                    age: 25,
                    height: `5'9''`
                }
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>