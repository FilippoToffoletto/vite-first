<script>
import PrimoComponente from './components/Header.vue'
import MainText from './components/MainText.vue'

  export default {
    name:'app',
    components :{
      PrimoComponente,
      MainText
    }
  }
</script>

<template>
  <div class="container">
    <PrimoComponente/>
    <MainText/>
  </div>

</template>


<style>

.container{
  width: 70vw;
  height: 90vh;
  margin: 5vh auto;
  border: 1px solid white;
  border-radius: 20px;
}
</style>