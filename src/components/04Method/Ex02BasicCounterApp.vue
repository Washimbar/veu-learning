<template>
    <div>
        <h2>Count : {{ count }}</h2>
        <button @click="inc">Increment</button>
        <button @click="dec">Decrement</button>
        <button @click="reset">Reset</button>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                count: 0,
            }
        },
        methods:{
            inc(){
                this.count += 1;
            },
            dec(){
                this.count -= 1;
            },
            reset(){
                this.count = 0;
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>