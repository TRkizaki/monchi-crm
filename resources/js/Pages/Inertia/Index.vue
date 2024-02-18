<script setup>

</script>

<template>
  <div v-if="$page.props.flash.message" class="bg-blue-300">
  {{ $page.props.flash.message }}
  </div>   
</template>

