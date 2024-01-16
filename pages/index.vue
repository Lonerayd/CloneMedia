<template>
    <div >
        <h4 class="bg-red-400 dark:bg-gray-500 ">Welcome</h4>
        <NuxtLink to="/next">try link </NuxtLink>
        <ClientOnly>
    <UButton
      :icon="isDark ? 'i-heroicons-moon-20-solid' : 'i-heroicons-sun-20-solid'"
      color="gray"
      variant="ghost"
      aria-label="Theme"
      @click="isDark = !isDark"
    />

   
  </ClientOnly>
    </div>
   
</template>

<script setup lang="ts">
const colorMode = useColorMode()


const isDark = computed({
  get () {
    return colorMode.value === 'dark'

  },
  set () {
    if (colorMode.preference){
        colorMode.preference = colorMode.value === 'dark' ? 'light' : 'dark'
    }
   
  }
})

</script>

<style scoped>

</style>