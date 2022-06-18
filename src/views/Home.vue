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
    <movie-recommendation/>
    <tuiClip/>
</div>
  
  
</template>

<script lang="ts">
import introduction from '@/views/introduction/index.vue'
import recommandation from '@/views/recommendation/index.vue'
import actor from '@/views/actor/index.vue'
import movieRecommendation from '@/views/movieRecommendation/index.vue'
import tuiClip from '@/views/tuiClip/index.vue'
undefined
export default {
  data () {
    return {
    };
  },

  components: { introduction, recommandation,actor,movieRecommendation,tuiClip },

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
      vertical-align:middle;
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
