<template>
  <v-layout class="QRCode" justify-center>
    <v-col cols="8" md="12">
      <p>参加者にバーコードを読み取らせてください</p>
      <qriously class="white" :value="url" :size="200" />
    </v-col>
  </v-layout>
</template>

<script>
import Vue from 'vue'
import VueQriously from 'vue-qriously'
Vue.use(VueQriously)

export default {
  name: 'QRCode',
  data: () => ({
    url: '1234567'
  })
}
</script>
