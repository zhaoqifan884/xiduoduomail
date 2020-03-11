<template>
  <div id="app">
    <router-view/>
    <main-table-bar/>
  </div>
</template>

<script>
import MainTableBar from "components/content/mainTableBar/MainTableBar";

export default {
  name: 'App',
  components: {
    MainTableBar
  }
}
</script>

<style>
  @import "assets/css/base.css";
</style>
