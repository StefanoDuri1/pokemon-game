<template>
    <div>
        <h1>Who is this Pokemon?</h1>

        <PokemonImage/>
        <PokemonOptions/>
    </div>
</template>
<script>
import PokemonImage from '../components/PokemonImage.vue'
import PokemonOptions from '../components/PokemonOptions.vue'

export default {
    components: { 
        PokemonOptions, 
        PokemonImage 
    },

}
</script>
