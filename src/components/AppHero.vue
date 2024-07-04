<script>
    export default {
        name: "AppHero",
    }
</script>

<template>
    <img src="../../public/Hero.webp" alt="Hero Image">
    <h2>HERO</h2>

</template>

<style scoped>
img{
    position: relative;
}
h2{
    color: red;
    font-size: 36px;
    position: absolute;
    top: 60%;
    left: 50%;
    transform: translate(-50%, -50%);

}

</style>