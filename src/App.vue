<template>
  <div>
    <Main :propData='initData'/>
  </div>
</template>

<script>
import Main from './components/Main.vue'
export default {
    data(){
      return {
        initData: 'hello 你好'
      }
    },
    components:{
      Main
    }
}
</script>

<style>

</style>