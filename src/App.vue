<template>
    <div class="container">
        <AppTitle></AppTitle>
        
    </div>
</template>


<script>

import AppTitle from './components/AppTitle.vue'

export default {
    components: {
        AppTitle
    }
}
</script>


<style>
/* CSS RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* FONT RESET */
html {
    font-family: sans-serif;
}

/* IMG RESET */
img {
    max-width: 100%;
    display: block;
}

#app {
    background-color: #202020;
    color: white;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    padding: 2rem;
}

.container {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}
</style>
