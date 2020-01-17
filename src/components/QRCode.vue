<template>
  <v-layout class="QRCode" justify-center>
    <qriously :value="url" :size="200" />
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
