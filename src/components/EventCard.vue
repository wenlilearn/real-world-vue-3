<script setup>
import { ref } from 'vue'
// defineProps({
//   msg: {
//     type: String,
//     required: true
//   }
// })
const event = ref({
  id: 5928101,
  category: 'animal welfare',
  title: 'Cat Adoption Day',
  description: 'Find your new feline friend at this event.',
  location: 'Meow Town',
  date: 'January 28, 2022',
  time: '12:00',
  petsAllowed: true,
  organizer: 'Kat Laydee'
})
</script>

<template>
  <div class="event-card">
    <h2>{{event.title}}</h2>
    <span>@{{event.time}} on {{event.date}}</span>
  </div>
</template>

<style scoped></style>
