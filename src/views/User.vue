<template>
  <div class="User">
    <div>
      <Bingo/>
    </div>
    <div>
      <History/>
    </div>
    <div>
      <Ranking/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Bingo from '@/components/Bingo.vue'
import History from '@/components/History.vue'
import Ranking from '@/components/Ranking.vue'

export default {
  name: 'User',
  components: {
    Bingo,
    History,
    Ranking
  }
}
</script>
