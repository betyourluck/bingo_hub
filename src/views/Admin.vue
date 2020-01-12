<template>
  <div class="Admin">
    <img alt="Vue logo" src="../assets/logo.png">
    <UserList/>
    <History/>
    <Ranking/>
  </div>
</template>

<script>
// @ is an alias to /src
import UserList from '@/components/UserList.vue'
import History from '@/components/History.vue'
import Ranking from '@/components/Ranking.vue'

export default {
  name: 'Admin',
  components: {
    UserList,
    History,
    Ranking
  }
}
</script>
