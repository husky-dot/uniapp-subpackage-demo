<template>
  <view class="content">
    <SayHello />
  </view>
</template>

<script lang="ts">
import Vue from 'vue'
import SayHello from '@/components/SayHello.vue'

export default Vue.extend({
  components: {
    SayHello
  }
})
</script>

