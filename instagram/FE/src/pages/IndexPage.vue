<template>
  <q-page class="flex flex-center">
     <q-btn color="blue" label="register" class="full-width" rounded @click="$router.push('/register')" />
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
