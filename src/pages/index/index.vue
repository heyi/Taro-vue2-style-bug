<template>
  <view class="index" :style='style'>
    <text>{{ msg }}</text>
  </view>
</template>

<script>
import './index.less'

export default {
  data() {
    return {
      msg: 'Hello world!',
      style: {
        '-webkit-text-fill-color' : '#2233fd',
        '-webkit-text-stroke-color' : '#445566',
        'textAlign' :'right'
      }
    }
  }
}
</script>
