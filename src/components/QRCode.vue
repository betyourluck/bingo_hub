<template>
  <div class="QRCode">
    <qriously :value="url" :size="200" />
  </div>
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
