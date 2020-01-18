<template>
  <v-container class="fill-height" fluid>
    <v-layout text-center wrap>
      <div class="Admin">
        <Game/>
        <img alt="Vue logo" src="../assets/logo.png">
        <UserList/>
        <History/>
        <Ranking/>
      </div>
    </v-layout>
  </v-container>
</template>

<script>
// @ is an alias to /src
import UserList from '@/components/UserList.vue'
import History from '@/components/History.vue'
import Ranking from '@/components/Ranking.vue'
import Game from '@/components/Game.vue'

export default {
  name: 'Admin',
  components: {
    Game,
    UserList,
    History,
    Ranking
  }
}
</script>
