<template>
  <div>
    <footer class="bottom-0">
    <hr class="border-gray-600">
    <p class="px-4 my-4 text-gray-600 text-center">
  &copy; {{ new Date().getFullYear() }} -
  {{ new Date().toLocaleString('default', { month: 'long' }) }} 
  {{ new Date().getDate() }} 
  {{ new Date().toLocaleTimeString() }}
</p>

   </footer>

  </div>
</template>

<script setup>

</script>

<style>

</style>