<script>
export default {
    name: "appHero",
    data () {
        return{
            jumbotron: "Jumbotron vite!"
        }
    }
}
</script>

<template>
    <h3>{{ jumbotron }}</h3>
</template>

<style>
h3 {
    color: red;
    font-size: 2rem;
    text-align: center;
    margin-top: 20px;
}
</style>