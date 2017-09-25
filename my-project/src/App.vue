<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <router-link to="/" tag="li" exact><a>首页</a></router-link>
    <router-link to="/blog" tag="div" active-class="starkwang"><a>博客</a></router-link>
    <router-link to="/daily" tag="div" active-class="starkwang"><a>知乎日报</a></router-link>
    <router-link to="/Study" tag="div" active-class="starkwang"><a>学习页面</a></router-link>
    <router-link to="/Work" ><a>工作页面</a></router-link>
    <router-link to="/About" ><a>关于我页面</a></router-link>
<!--    
    <a href="/">首页</a>
    <a href="/Study">学习页面</a>
    <a href="/Work">工作页面</a>
    -->
    <span>Hi I'm SuSu</span>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
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
.router-link-active{
background-color:pink;
}
.starkwang{
background-color:yellow;
}
.shudong{
  background-color: blue;
}
</style>
