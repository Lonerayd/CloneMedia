<template>
   <div class="hidden  md:block xs-col-span-1 xl:col-span-2 h-screen dark:bg-dim-200">
    <div class="sticky top-0 flex flex-col">
        
        <div class="my-2 p-2 hover:bg-blue-50 dark:hover:bg-white/20 rounded-full w-fit " :class="defaultTransition">
                <NuxtLink to="/"> 
                <LogoTwitter class="w-8 h-8   "/>
                </NuxtLink>
        </div>
        
    </div>
   
   </div>
</template>

<script setup lang="ts">
  const defaultTransition = useTransitionStyle()
</script>

<style scoped>

</style>