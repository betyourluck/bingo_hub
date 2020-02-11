<template>
  <v-container class="fill-height" fluid>
    <v-layout text-center wrap>
      <v-row align="center" justify="center" class="ma-12">
        <v-col cols="8" md="12">
          <p>ゲーム作成ボタンを押してください</p>
          <v-btn x-large color="primary" justify="center" dark>ゲームを作成する</v-btn>
          <UserList/>
          <QRCode/>
          <v-btn x-large color="success" justify="center" dark>ゲームを開始する</v-btn>
        </v-col>
      </v-row>
    </v-layout>
  </v-container>
</template>

<script>
// @ is an alias to /src
import QRCode from '@/components/QRCode.vue'
import UserList from '@/components/UserList.vue'

export default {
  name: 'Start',
  data: () => ({
    test: 'tests'
  }),
  components: {
    QRCode,
    UserList
  }
}
</script>
