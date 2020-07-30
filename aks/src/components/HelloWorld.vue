<template>
  <div>
      <div class="header"></div>
      <div class="lbt">
          <el-carousel :interval="4000" type="card" height="200px">
                <el-carousel-item v-for="item in 6" :key="item">
                    <h3 class="medium">{{ item }}</h3>
                </el-carousel-item>
          </el-carousel>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
   .header {
     width: 100%;
     height:70px;
     background: pink;
   }
   .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 200px;
    margin: 0;
  }
  
  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
  .lbt {
    position: relative;
  }
</style>
