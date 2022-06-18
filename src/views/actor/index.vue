<!--  -->
<template>
  <div class="bar">
    <h1><br>&nbsp演职员</br></h1><br>
    <div class="container">
        <div><img src="@/assets/img/1.png" alt=""><p style="font-size:0.3rem;">111</p></div>
        <div><img src="@/assets/img/2.png" alt=""><p>111</p></div>
        <div><img src="@/assets/img/3.png" alt=""><p>111</p></div>
        <div><img src="@/assets/img/4.png" alt=""><p>111</p></div>
        <div><img src="@/assets/img/4.png" alt=""><p>111</p></div>
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
.bar{
    h1{
        font-size: 0.35rem;
        border-top:solid #eee 0.02rem;
        margin-left: 0.3rem;
        margin-right: 0.3rem;
    }
}
.container{
    padding-left:0.35rem;
    overflow-x: scroll; -webkit-overflow-scrolling:touch;display: -webkit-box;white-space: nowrap;
    div{
        display: inline-block;
        margin: 0.1rem;
        img{
            width: 2rem;
            height: 2.6rem;
        }
    }
}
</style>