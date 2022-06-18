<!--  -->
<template>
  <div class="container">
    <div>
        <br>
     <img src="@/assets/img/right-arrow.png" alt="" style="float:right; vertical-align: top; width: 0.5rem;"></img>
     <h1>&nbsp;推图集</h1><br>
    </div>
    <div class="photo">
        <div><img src="@/assets/img/photo1.png" alt=""></div>
        <div><img src="@/assets/img/photo2.png" alt=""></div>
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
    
    border-top:solid #eee 0.01rem;
    div{
        padding-right: 0.15rem;
        h1{
                font-size: 0.35rem;
                
                margin-left: 0.3rem;
                margin-right: 0.3rem;
                img{
                    vertical-align: top;
                }
            }
        }
    }
.photo{
    padding-left:0.35rem;
    overflow-x: scroll; -webkit-overflow-scrolling:touch;display: -webkit-box;white-space: nowrap;
    div{
        display: inline-block;
        margin-left: 0.01rem;
        img{
            width:3.5rem;
            height: 2.1rem;
        }
    }
}
</style>