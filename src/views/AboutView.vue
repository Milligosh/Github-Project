<script setup>
import GitDetails from '../components/GitDetails.vue';
</script>

<template>
  <div class="container" >
    <header>
      <div class="header">
        <h2>devfinder</h2>
        <h5>Dark</h5>
      </div>
    </header>
    <GitDetails followers="milliegosh"/>
  </div>
</template>

<style scoped>
 
.header h2{
  font-size: 26px;
  font-weight: 700;
  line-height: 39px;
  text-align: left;
  background: #222731;
}

.header h5{
  font-size: 13px;
  font-weight: 700;
  line-height: 19px;
  letter-spacing: 2.5px;
  text-align: right;
  background: #4B6A9B;
}

header{
  display: flex;
  justify-content: space-between;
}
</style>
