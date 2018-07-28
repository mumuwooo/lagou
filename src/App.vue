<template>
  <div id="app">
    <lg-header></lg-header>
    <router-view></router-view>
  </div>
</template>

<script>
  import Header from "@/components/Header";
export default {
  name: 'App',
  components:{
    "lg-header":Header,
  }
}
</script>

<style>
* {margin: 0;padding: 0;}
body {font-family: "Hiragino Sans GB", "Microsoft Yahei", "SimSun", Arial, "Helvetica Neue", Helvetica;
			background: #f8f9fc;}
a{text-decoration: none;}      
#app {

}      
</style>
