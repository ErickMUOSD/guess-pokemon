<script setup>
import {computed} from 'vue'

const props = defineProps(
  {
    pokemonId: {
      type: Number,
      required: true
    }
  }
)
const imgSrc = computed(() => {
  return "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/1.svg"
})
</script>
<template>
  <div class="pokemon-container">
    <img class="fade-in"
         src="{{imgSrc}}"
         alt="pokemon">
    <img class=" hidden-pokemon"
         src="{{imgSrc}}"
         alt="pokemon">
  </div>

</template>
<style scoped>
.hidden-pokemon {
  filter: brightness(0);
}

.pokemon-container {
  height: 200px;
  display: flex;
  justify-content: center;
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


</style>

