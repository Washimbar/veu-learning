<template>
    <div>
        <h1 v-for="(name, index) in names" :key="name">{{index +1}} {{name}}</h1>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                names: ['washim', 'jasimuddin', 'masud', 'amir'],
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>