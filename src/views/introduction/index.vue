<!--  -->
<template>
  <div class="container">
    <div class="img"></div>
    <div class="title">花束般的恋爱</div>
    <div class="class">124分钟/爱情/日本</div>
    <div><img src="@/assets/img/dislike.png" alt="">109&nbsp<img src="@/assets/img/like.png" alt="" style="margin-left:0.1rem;">104 <div>10人评分</div></div>
    <div>上影评分9.0 <div>豆瓣评分8.6</div></div>
    <div>第三方平台&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspBT&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp <img src="@/assets/img/right.png" alt=""></div>
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
.img{
    margin-left: 0.4rem;
    vertical-align: top;
    width: 2.3rem;
    height: 2.5rem;
    background: #eee;
    float: left;
    margin-top:0.1rem ;
    
}
.container{
  margin-top: 0.3rem;
  div:nth-child(4){
    font-size:0.1rem;
    margin-left:3.2rem;
    margin-bottom: 0.15rem;
    div{
      display: inline-block;
      margin-left: 0.6rem;
    }
    
    img{
      width: 0.4rem;
      vertical-align: top;
    }
  }
  div:nth-child(5){
    font-size:0.1rem;
    margin-left: 3.27rem;
    div{
      display: inline-block;
      margin-left: 0.4rem;
      color:gray
    }
  }
  div:nth-child(6){
    font-size:0.1rem;
    margin-left: 3.3rem;
    margin-top: 0.15rem;
    img{
      width:0.5rem;
      vertical-align: top;
    }
  }
}
.title{
 margin-left:3.2rem ;
 font-size: 0.4rem;
 font-weight:500;
}
.class{
  font-size: 0.15rem;
  margin-left:3.25rem ;
  margin-top:0.15rem;
  margin-bottom:0.15rem;
}
</style>