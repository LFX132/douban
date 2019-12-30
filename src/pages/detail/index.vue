<template>
    <div class="list">
        <div class="hero">
            <img src="" alt="">
            <p></p>
        </div>
    </div> 
</template>

<script>
import heroList from '@/data/lol_duowan'
export default {
  data () {
    return {
      heroList
    }
  }

}
</script>

<style lang="less">
   .list{
       display: flex;
       flex-wrap: wrap;
   }

</style>