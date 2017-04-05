<template>
  
  <div class="box">
    <div class="item" v-for="item in data" >{{item}}</div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      data: [1,2,3,4,5,6,7,8,9,10]

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .box {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: flex-start;
    align-items: flex-start;    
  }

  .item {
    /*width: 10%;*/
    padding: 10px;
    margin: 10px;
    border: black 1px solid;
  }
</style>
