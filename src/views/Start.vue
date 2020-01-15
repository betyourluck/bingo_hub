<template>
  <div class="Start">
    <p>ゲーム作成ボタンを押してください</p>
    <div class="my-2">
      <v-btn x-large color="primary" dark>ゲームを作成する</v-btn>
    </div>
    <QRCode/>
    <UserList/>
    <div class="my-2">
      <v-btn x-large color="success" dark>ゲームを開始する</v-btn>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import QRCode from '@/components/QRCode.vue'
import UserList from '@/components/UserList.vue'

export default {
  name: 'Start',
  components: {
    QRCode,
    UserList
  }
}
</script>
