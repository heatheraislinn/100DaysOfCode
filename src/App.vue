<template>
  <div>
    <Pokedex>
      <img src="Vue.js_Logo.svg.png" class="vue-logo" />
      <img src="GraphQL_Logo.svg.png" class="gql-logo" />
    </Pokedex>
  </div>
</template>

<script>
import Pokedex from '@/components/Pokedex'
export default {
  components: {
    Pokedex
  }
}
</script>

<style>
  .vue-logo {
    height: 100px;
    position: absolute;
    top: 5%;
    left: 5%;
  }

  .gql-logo {
    height: 90px;
    position: absolute;
    top: 33%;
    left: 40%;

  }
</style>
