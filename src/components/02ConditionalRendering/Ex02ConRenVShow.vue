<template>
    <div>
        <h2 v-show="isVisible">This is v-show . If it's value is true display it else make it display none.</h2>
        <h2 v-show="isShow">This is v-show . If it's value is true display it else make it display none.</h2>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                isVisible: true,
                isShow: false,
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>