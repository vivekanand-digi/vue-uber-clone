<template>
  <div id="HOME" class="flex flex-col h-screen">
    <div class="m-3 mb-auto">

      <div class="grid grid-cols-2 gap-3 my-3">
        <ServiceSelectLarge text="Ride" imgageWidth="120" image="ride" />
        <ServiceSelectLarge text="Food" imgageWidth="120" image="food" promo="true" />
      </div>

      <div class="grid grid-cols-4 gap-3 my-3">
        <ServiceSelectSmall text="travel" image="travel" />
        <ServiceSelectSmall text="bike" image="bike" />
        <ServiceSelectSmall text="ride" image="ride" />
        <ServiceSelectSmall text="booked" image="booked" />
      </div>

    </div>
  </div>
</template>

<script setup>
import ServiceSelectSmall from '@/components/ServiceSelectSmall.vue'
import ServiceSelectLarge from '../components/ServiceSelectLarge.vue'
</script>