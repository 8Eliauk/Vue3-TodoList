<script setup name="App">
import MyHeader from './components/MyHeader.vue';
import MyList from './components/MyList.vue';
import MyFooter from './components/MyFooter.vue';
</script>

<template>
  <div class="todo-container">
    <div class="todo-wrap">
      <MyHeader/>
      <MyList/>
      <MyFooter/>
    </div>
  </div>
</template>

<style scoped>

</style>
