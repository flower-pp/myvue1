<template>
  <div class="hello">
    <h4>What's your favourate flower?</h4>
    <p><span>flower</span>：{{myMessage}}</p>
  </div>
</template>

<script>
export default {
  name: 'child',
  props: [
    'myMessage',
  ],
  // mounted(){
  //   console.log("子组件打印:",this.myMessage);
  // }
}
</script>

<style scoped>
  .hello{
    margin-top: 30px;
  }
  h4,p{
    color: #41b883;;
    text-align: left;
    font-size: 20px;
  }
  p{
    font-size: 12px;
  }
  span{
    color: #35495e;
  }
</style>
