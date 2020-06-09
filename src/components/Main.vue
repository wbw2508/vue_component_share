<template>
  <div class="container">
    <div>{{msg}}</div>
    <div>{{propData}}</div>
  </div>
</template>

<script>
import {a} from './wbw.js'
export default {
  name: 'wbw',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  props: {
      propData: {
          type: String,
          default: '我是默认值'
      }
  },
  mounted(){
    console.log(a)
  }
}
</script>

<style lang="scss">
.container{
    text-align: center;
}
</style>