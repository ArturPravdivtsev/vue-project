<template>
  <div>
    <app-counter></app-counter>
    <app-car 
    ></app-car>
  </div>
</template>

<script>
import Car from './Car.vue'
import Counter from './Counter.vue'
export default {
  components: {
    appCar: Car,
    appCounter: Counter
  }
}
</script>

<style>
.car {
  border: 1px solid #000
}
</style>
