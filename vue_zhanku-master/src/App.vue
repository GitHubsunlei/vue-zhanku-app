<template>
  <div id="app">
    <v-nav></v-nav>
    <router-view></router-view>
    <v-footer></v-footer>
  </div>
</template>

<script>
import nav from "./components/layout/nav.vue";
import footer from "./components/layout/footer.vue";


export default {
  name: 'app',
  data(){
    return {
      msg:"Ok"
    }
  },
  components:{
    // 视图模板名称:对应的是一个组件
    "v-nav":nav,
    "v-footer":footer,
  }
}
</script>

