<template>
    <div v-for="person in persons" :key="person.id">
        <h2>Name: {{ person.name }}</h2>
        <h3>Age: {{ person.age }}</h3>
        <h3>Skills : </h3>
        <ul v-for="(skill, index) in person.skills" :key="index">
            <li>{{ skill }}</li>
        </ul>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                persons:[
                    {
                        id: "39834nfd87yf3wkjd8e983kjn3fv89",
                        name: "Washim Bari",
                        age: 25,
                        skills:['JavaScript', 'React JS','React Native']
                    },
                    {
                        id: "39ijf94i09ud90u4ino9d8fuoi409uf",
                        name: "Masud Biswas",
                        age: 25,
                        skills:['JavaScript', 'React JS','Node.js']
                    },
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>