<template>
     <div :class="{dark}">
        <div class="min-h-full">
            <!-- <AppHead/> -->
            <div class="grid grid-cols-12 mx-auto sm:px-6 lg:max-w-7xl lg:px-8 lg:gap-5">
                
               
             

               <SideBar/>
               <slot/>

            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
  const dark= ref(true)
</script>

<style scoped>

</style>