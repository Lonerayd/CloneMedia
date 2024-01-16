<template>
    <div class="grid grid-cols-12 mx-auto sm:px-6 lg:max-w-7xl lg:gap-1">
        <header class="xs-col-span-1 lg:col-span-2 ">
        <SideBar/>
         </header>

    <main >
        <div >
            <slot/>

        </div>
       
    </main>
    </div>
   
  
</template>

<script setup lang="ts">
  
 const dark= ref(false)
</script>

<style scoped>

</style>