<script setup>
definePageMeta({
  layout: 'custom2',
})

if (import.meta.client) {
  console.log('Running With Layout2 Page Setup')
}
</script>

<template>
  <div id="with-layout2">
    <div>with-layout2.vue</div>
  </div>
</template>
