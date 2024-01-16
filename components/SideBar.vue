<template>

  
    <div class="hidden  md:block h-screen dark:bg-dim-200 px-2">
    <div class="sticky top-0 flex flex-col items-center lg:items-start">
       
        <NuxtLink to="/" class="my-2 p-2 hover:bg-blue-50 dark:hover:bg-white/20 rounded-full w-fit " :class="defaultTransition">
                
          <LogoTwitter class="w-6 h-6"/>
             
        </NuxtLink>

        <div class="mt-3 space-y-2"> 
          <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-home-solid" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Home</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-hashtag-20-solid" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Explore</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-bell" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Notification</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-inbox" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Messages</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-bookmark" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Bookmarks</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-document-text" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Lists</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-user" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">Profile</span>
        </NuxtLink>
        <NuxtLink to="/" class="linkHover flex items-center" active-class="font-semibold">
          <UIcon name="i-heroicons-plus-circle" class="w-6 h-6 "/>
          <span class="ml-4 hidden lg:block text-md ">More</span>
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