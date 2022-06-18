<!--  -->
<template>
  <div class="container">
    <div class="pannel">
        <van-tabs v-model="active" animated color="black">
        <van-tab title='简介'>
            <div class="text">在东京京王线的明大前站，错过末班车的山音麦(菅田将晖饰)和八谷绢(有村架纯饰)偶然相识，在深夜咖啡馆聊起文学、电影和音乐，发现喜好惊人-致的他们瞬间坠入爱河，开始了五年恋爱..<div class="button">展开</div></div>
        </van-tab>
        <van-tab title='推荐'>
            内容
        </van-tab>
        <van-tab title='影评'>
            内容
        </van-tab>
        </van-tabs>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
    };
  },

  components: {},

  computed: {},

  mounted: {},

  methods: {}
}

</script>
<style lang='less' scoped>
.container{
    background: #eee;
    padding-top: 0.15rem;
    
    margin-top:0.5rem ;
    .pannel{
        padding:0.2rem;
        background: white;
    }
}
.button{
    font-size: 0.27rem;
    color:#86b6f9ec;
    display: inline-block;
}
.text{
    padding: 0.25rem;
    padding-top: 0.3rem;
    line-height: 0.5rem;
}
</style>