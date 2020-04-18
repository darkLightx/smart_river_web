<template>
  <div id="app">
    <!-- <i class="iconfont">&#xe65a;</i>
    <font-awesome-icon :icon="['fas', 'square']" /> -->
    <river-selection></river-selection>
  </div>
</template>

<script>
import RiverSelection from './components/Selection/RiverSelection'

export default {
  name: 'App',
  components: {
    RiverSelection
  }
}
</script>

<style>
  @import './assets/css/base.css';
</style>
