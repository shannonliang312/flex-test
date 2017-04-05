<template>
  <div id="app">
    <div class="box">
      <div class="item" v-for="item in data" >{{item}}</div>
    </div>
    <div class="media">
      <img class="media-img" src="./assets/logo.png" alt="">
      <div class="media-body">
        <h3>test</h3>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
        <div>
          dsfasdfasdfasdfasfdaadfasfasd
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      data: [1,2,3,4,5,6,7,8,9,10]
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
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

  .media {
    width: 30%;
    padding: 10px;
    border: black 10px solid;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: flex-start;
  }

  .media-img {
    margin-right: 10px;
    flex: 1;
  }

  .media-body {
    flex: 0;
    width: 100%
  }
</style>
