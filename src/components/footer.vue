<template>
  <div>
    <footer class="fixed-bottom clearfix">
        <div class="col4">
          <router-link to="/index">flower study</router-link>
        </div>
        <div class="col4">
          <router-link to="/second">yours</router-link>
        </div>
        <div class="col4">
          <router-link to="/news">about us</router-link>
        </div>
        <div class="col4">
          <router-link to="/third">others</router-link>
        </div>
    </footer>
  </div>
</template>
<script>
    export default{
        data(){
            return{
                msg: 'Hello vue'
            }
        }
    }
</script>
<style>
    .fixed-bottom {
        background: pink;
        width: 100%;
        bottom: 0;
        z-index: 99;
        margin:0 auto;
    }
    .fixed-bottom div {
        display: block;
        float: left;
        text-align: center;
        padding-left:60px;
    }
    .fixed-bottom a {
        width: 100%;
        display: block;
        font-size: 30px;
        color: #7a7a7a;
        line-height: 50px;
    }
</style>
