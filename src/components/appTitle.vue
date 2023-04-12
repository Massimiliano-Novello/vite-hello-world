<script>
export default {
    name: "appTitle",
    data () {
        return{
            title: "La mia prima app con vite!"
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style>
h1 {
    color: blue;
    font-size: 3rem;
    text-align: center;
    margin-top: 10px;
}
</style>