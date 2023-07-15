<template>
    <div>
        <h2> Number - {{ num }}</h2>
        <h2>Add method - {{ add() }}</h2>
        <h2>Add Multiply method - {{ mul(3,7) }}</h2>
        <h2>Subtract method - {{ subtract(33) }}</h2>
        <h2>Multiply method - {{ subtract(num) }}</h2>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                num : 6,
            }
        },
        methods:{
            add(){
                return 3 + 4;
            },
            mul(a, b){
                return a * b;
            },
            subtract(a){
                return a - this.num;
            }
        }

    }
</script>

<style lang="scss" scoped>

</style>