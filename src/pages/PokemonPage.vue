<script>


import {defineComponent} from "vue";
import PokemonPicture from "@/pages/PokemonPicture.vue";
import PokemonOptions from "@/pages/PokemonOptions.vue";

export default defineComponent({
  components: {PokemonOptions, PokemonPicture},

})
</script>
<template>
  <h1>¿Quién es este pokemon?</h1>
  <PokemonPicture pokemon-id="10"/>
  <PokemonOptions />
</template>

<style>
h1,h2 {
  text-align: center;
}
/*img {*/
/*  display: block;*/
/*  margin: 0 auto;*/

/*  !*height: 200px;*!*/
/*  !*position: absolute;*!*/
/*  !*right: 32%;*!*/
/*  user-select: none;*/
/*  -moz-user-select: none;*/
/*  -ms-user-select: none;*/
/*  -webkit-user-drag: none;*/
/*  -webkit-user-select: none;*/
/*}*/
</style>
