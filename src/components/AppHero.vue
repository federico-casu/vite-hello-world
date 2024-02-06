<template>
    <!-- html componente -->
    <figure>
        <img :src="getImagePath(imageName)" alt="">
    </figure>
</template>


<script>
// Js componente

export default {
    name: 'AppHero',

    data() {
        return {
            imageName: 'Vue+Vite.jpg'
        }
    },
    methods: {
        getImagePath(img) {
            return new URL(`../assets/${img}`, import.meta.url).href
        }
    }
}
</script>


<style scoped>
/* stile del componente */
</style>
