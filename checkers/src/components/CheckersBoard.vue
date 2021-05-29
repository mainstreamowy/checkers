<template>
  <div class="board">
  <table class="board">
    <tr>
      <td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td>
      <td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td>
    </tr>
    <tr>
      <td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td>
      <td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td>
    </tr>
    <tr>
      <td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td>
      <td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="black"/></td>
    </tr>
    <tr>
      <td class="board_brown"></td><td class="board_cream"></td><td class="board_brown"></td><td class="board_cream"></td>
      <td class="board_brown"></td><td class="board_cream"></td><td class="board_brown"></td><td class="board_cream"></td>
    </tr>
    <tr>
      <td class="board_cream"></td><td class="board_brown"></td><td class="board_cream"></td><td class="board_brown"></td>
      <td class="board_cream"></td><td class="board_brown"></td><td class="board_cream"></td><td class="board_brown"></td>
    </tr>
    <tr>
      <td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td>
      <td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td>
    </tr>
    <tr>
      <td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td>
      <td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td>
    </tr>
    <tr>
      <td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td>
      <td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td><td class="board_brown"><Pawns image="white"/></td><td class="board_cream"></td>
    </tr>
  </table>
</div>
</template>

<script>
import Pawns from './Pawns'

export default {
  name: 'CheckersBoard',
  data(){
    return{
      msg: 'Halla'
    }
  },
  components: {
    Pawns,
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

.board{
  border-radius: 5px;
  border-color: black;
  border: 1px solid;
  padding: 20px;
  width:fit-content;
}

.board_cream{
  background-color: #ffffcc;
  height:64px;
  width:64px;
}

.board_brown{
  background-color: #12cc44;
  height:64px;
  width:64px;
}

</style>
