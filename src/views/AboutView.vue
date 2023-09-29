<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div v-for="shop,index  ">
      <coffeeShop name price image  ></coffeeShop>






    </div>
  </div>
</template>




<script setup>
import {ref} from 'vue'
import coffeeShop from './components/coffeeShop.vue'

const travelList =ref([
  {
    'ท่าช้าง'




  }




])






</script>






<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
