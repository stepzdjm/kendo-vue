<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
/* You can add global styles to this file, and also import other style files */
body {
  margin: 0;
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  text-align: left;
  background-color: #fff;
}

.k-grid-table td {
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow: hidden;
}

.k-grid-table td.numeric {
  text-align: right;
}

.k-grid-table .fintech-icons .k-icon {
  flex: 0 1 auto;
  font-size: 16px;
  width: 16px;
  height: 16px;
  margin-left: 4px;
}

.k-grid-table .fintech-icons {
  display: flex;
  justify-content: flex-end;
}

.k-grid-table .changePositive,
.k-grid-table .changeNegative,
.k-grid-table .strongPositive,
.k-grid-table .strongNegative {
  color: #fff !important;
  padding: 2px 5px;
}

.k-grid-table .positive {
  color: #4eb862 !important;
}

.k-grid-table .positive.strongPositive {
  color: rgba(78, 184, 98, 0.8) !important;
}

.k-grid-table .negative {
  color: #d31642 !important;
}

.k-grid-table .negative.strongNegative {
  color: rgba(255, 19, 74, 0.8) !important;
}

.k-grid-table .strongNegative {
  color: #fff;
}

.k-grid-table .change .changePositive {
  border-right: 4px solid #335e3b;
  padding-right: 4px;
}

.k-grid-table .change .changeNegative {
  border-right: 4px solid #7a1c32;
  padding-right: 4px;
}

.k-grid-table .change .strongPositive {
  border-right: 4px solid #459a55;
  padding-right: 4px;
}

.k-grid-table .change .strongNegative {
  border-right: 4px solid #d31642;
  padding-right: 4px;
}

.controls-holder {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.switches {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex: 1 0 0%;
    min-width: 500px;
    padding-right: 20px;
    font-size: 0.9rem;
    margin-bottom: -20px;
}

.control-item {
    padding-right: 20px;
}

.k-slider {
    height: 24px;
    display: block;
}

.fintech-slider {
    width: 40%;
    min-width: 145px;
}

.fintech-play-controls {
    width: 45%;
    min-width: 500px;
    margin-top: 20px;
}

.fintech-play-controls button {
  width: 200px;
}

.sample-toolbar {
    height: 20px;
    font-size: 0.8rem;
    line-height: 20px;
}
</style>
