<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" /> -->
    <h1>
      <a href="http://39.105.166.182:8081/" target="_blank">1.ts实现axios</a>
    </h1>
    <hr />
    <h1>
      <a href="http://39.105.166.182:8082/" target="_blank"
        >2.珠峰构架师成长计划</a
      >
    </h1>
    <hr />
    <h1>
      <a href="http://39.105.166.182:8083/" target="_blank">3.数据大屏</a>
    </h1>
    <hr />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component"
import HelloWorld from "@/components/HelloWorld.vue" // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style lang="less" scoped>
.home {
  padding-left: 30px;
  padding-right: 30px;

  h1 {
    color: black;
  }
}
</style>
