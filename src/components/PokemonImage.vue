<template>
    <div class="pokemon-container">
        <img class="hidden-pokemon" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/1.svg" alt="pokemon">

        <img class="fade-in" src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/1.svg" alt="pokemon">

    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

    .pokemon-container {
        height: 200px;
        display: flex;
        justify-content: center;
        padding: 30px 0;
    }

    img {
        height: 200px;
        position: absolute;
        user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        -webkit-user-drag: none;
        -webkit-user-select: none;
    }
    .hidden-pokemon {
        filter: brightness(0%)
    }
</style>