<template>
  <div id="app">
    <commit-chart :width="600" :height="400"></commit-chart>
  </div>
</template>

<script>
import CommitChart from './components/CommitChart'

export default {
  name: 'app',
  components: {
    CommitChart
  }
}
</script>

<style>
</style>
