<template>
  <div class="Start">
    <img alt="Vue logo" src="../assets/logo.png">
    <QRCode/>
  </div>
</template>

<script>
// @ is an alias to /src
import QRCode from '@/components/QRCode.vue'

export default {
  name: 'Start',
  components: {
    QRCode
  }
}
</script>
