<script>
export default {
    name: "AppHero",
    data() {
        return {
            img: "img/vbanner.jpg"
        }
    }
}

</script>

<template>
    <div>
        <img :src="img">
    </div>
</template>

<style scoped>
img {
    max-width: 100%;
    width: 900px;
}
</style>
