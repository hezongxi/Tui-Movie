<template>
<div>
  <div class="home">
    <div>
        <img class="img" src="@/assets/img/back.png" alt="">
        <div>电影详情</div>
    </div>
  </div>
    <introduction/>
    <recommandation/>
    <actor/>
</div>
  
  
</template>

<script lang="ts">
import introduction from '@/views/introduction/index.vue'
import recommandation from '@/views/recommendation/index.vue'
import actor from '@/views/actor/index.vue'
undefined
export default {
  data () {
    return {
    };
  },

  components: { introduction, recommandation,actor },

  computed: {},

  methods: {}
}


</script>
<style lang="less" >
  .home{
    background-color: white;
    font-size: 0.371rem;
    border-bottom:solid #eee 0.03rem ;
    div{
      text-align:center;
      div{
        margin: 0.13rem;
        margin-right: 0.37rem;
      }
    }
  }
  .img{
    float: left;
    width: 0.6rem;
  }
</style>
