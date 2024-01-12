<template>
    <div :class="{dark}">
        <h4 class="bg-red-400 dark:bg-gray-500">Welcome</h4>
        <NuxtLink to="/next">try link </NuxtLink>
    </div>
   
</template>

<script setup lang="ts">
const dark= ref(false)
</script>

<style scoped>

</style>