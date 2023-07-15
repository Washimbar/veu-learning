<template>
    <div v-for="(person, index) in persons" :key="index">
        <h2 v-if="person != 'Washim Bari'">Name : {{ person }}</h2>
        <h2>{{ 0 == []}}</h2>
        <h2>{{ "0" == 0 }}</h2>
        <h2>{{ '0' == [] }}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            persons: ['Washim Bari', 'Jasimuddin Bari'],
        }
    }
}
</script>

<style lang="scss" scoped></style>