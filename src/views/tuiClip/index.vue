<!--  -->
<template>
  <div class="container">
    <h1><br>&nbsp;推剪辑</h1></br>
    <van-swipe class="my-swipe" :autoplay="3000" indicator-color="black">
        <van-swipe-item><div><img src="@/assets/img/video1.png" alt=""><p class="paragragh">花式般的恋爱：连二次元都打不败的爱情，为何值得我们相信？</p></div><br>
    <div><img src="@/assets/img/video2.png" alt=""><p class="paragragh">高分电影《花束般的恋爱》既浪漫又写实，你我都经历过的爱情！？</p><br><br></div></van-swipe-item>
        <van-swipe-item>2</van-swipe-item>
        <van-swipe-item>3</van-swipe-item>
        <van-swipe-item>4</van-swipe-item>
    </van-swipe>
    <br>
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
  .my-swipe .van-swipe-item {
    color: black;
    text-align: center;
  }
.container{
  
  div{
    
    text-align:center;
    img{
      width: 7rem;
      
    }
  }
}
h1{
        font-size: 0.35rem;
        border-top:solid #eee 0.01rem;
        margin-left: 0.3rem;
        margin-right: 0.3rem;
    }
.paragragh{
  padding-left: 0.2rem;
  padding-right:0.2rem;
}
</style>