<template>
  <view class="content">
  </view>
</template>

<script lang="ts">
import Vue from 'vue'
import { add } from '@/utils/common'

export default Vue.extend({
  created() {
    console.log(add(1, 2))
  }
})
</script>

<style>