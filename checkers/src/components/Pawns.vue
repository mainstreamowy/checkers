<template>
  <div>
      <img src="@/assets/cb.png" v-if="image==='black'"/>
      <img src="@/assets/cw.png" v-if="image==='white'"/>
   </div>
</template>

<script>

export default {
  name: 'Pawns',
  // Dziala jako funkcja, zwraca dane ktore chcemy aby aplikacja je wykorzystala
  data(){
    return {
      id:1,
      images: 'white',
    }
  },
  // WHAT WE EXPECT TO HAVE
  props:{
    image:{
      type: String,
      required: true
    }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
