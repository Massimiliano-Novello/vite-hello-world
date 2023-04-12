<script>
export default {
    name: "appHero",
    data () {
        return{
            jumbotron: "Questo è l'immagine di vite",
        }
    }
}
</script>

<template>
    <h3>{{ jumbotron }}</h3>
    <div class="image">
        <img src="https://lh3.googleusercontent.com/GftmWvsKYrMnWv88XI5BExZGIqh30wGCfU-OrwZb2yiCXMmFlsN88U7625jCdpfeUSfMSlDO2tf9j_uTPVHUZHO6cka_nr84IAYZDhg" alt="">

    </div>

</template>

<style>
h3 {
    color: red;
    font-size: 2rem;
    text-align: center;
    margin-top: 20px;
}

img {
    padding: 30px;
    height: 300px;
    object-fit: cover;
    border-radius: 20px;
}

.image {
    text-align: center;

}
</style>