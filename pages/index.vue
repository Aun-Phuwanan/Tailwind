<template>
  
  <div>
    <nav class=" flex items-center py-2 px-10 fixed bg-white w-full shadow-lg ">
      <div class="p-4  font-bold cursor-default">
        Home
      </div>
      <div class="px-4 py-2 cursor-pointer text-gray-500 rounded-lg hover:bg-green-100 hover:text-green-700 active:bg-green-100 text-green-700">About</div>
      <div class="px-4 py-2 cursor-pointer text-gray-500 rounded-lg hover:bg-green-100 hover:text-green-700">Login</div>
      <div class="px-4 py-2 text-gray-500 rounded-lg hover:bg-green-100 hover:text-green-700">
        <nuxt-link to="/es1">Next</nuxt-link></div>
    </nav>
    
    <indexmain/>
  </div>
</template>

<script>
export default {

 
}
</script>
