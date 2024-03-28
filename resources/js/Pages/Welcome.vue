
<template>
 
   <Index/>
   <div class="bg-gray-100 h-screen">
      <!-- category -->
      <div class="w-full px-64 py-5">
         <div class=" w-1/4 bg-white">
            <p class="flex items-center">
              
                  <img class="mr-2" src="https://cdn-icons-png.flaticon.com/512/561/561123.png" alt="Menu" title="Menu" width="23" height="23">
              
               Categories
               </p>
             <ul class="mt-4 text-sm">
              <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg class="mr-2" width="24" height="24" viewBox="0 0 24 24">
                     <path fill-rule="evenodd" d="M5 3h14v18H5V3zm3 2v12h8V5zM8 16H7V8h1z" clip-rule="evenodd"/>
                  </svg></i>
                  <a href="/" >Women's Fashion</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg width="24" class="mr-2" height="24" viewBox="0 0 24 24">
                     <path fill-rule="evenodd" d="M18 3h2v18h-2V3zM3 3h2v18H3V3zM8 5h8v14H8V5z" clip-rule="evenodd"/>
                  </svg></i>
                  <a href="/">Men's Clothing</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg width="24" height="24" class="mr-2" viewBox="0 0 24 24">
                     <path d="M12 8c-1.94 0-3.5 1.56-3.5 3.5v4.84l7.7 7.7c.18.18.43.18.61 0l1.41-1.41c.18-.18.18-.43 0-.61L15.5 16v-4.84c0-1.94-1.56-3.5-3.5-3.5zM8 11v1H6v2h2v1z"/>
                  </svg></i>
                  <a href="/" >Jewelry & Watches</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg width="24" class="mr-2" height="24" viewBox="0 0 24 24">
                     <path fill-rule="evenodd" d="M3 3h18v18H3V3zm4 2v14H16V5zM9 16H8v2h1z" clip-rule="evenodd"/>
                  </svg></i>
                  <a href="/" >Bags & Luggage</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg class="mr-2" width="24" height="24" viewBox="0 0 24 24">
                     <path d="M12 16c-3 0-5.41-2.41-5.41-5.41s2.41-5.41 5.41-5.41 5.41 2.41 5.41 5.41-2.41 5.41-5.41 5.41zM10 5h4v6h-4V5zM16 5h4v6h-4V5z"/>
                  </svg></i>
                  <a href="/" >Shoes</a>
                  </li>

                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg class="mr-2" width="24" height="24" viewBox="0 0 24 24">
                     <path d="M15.5 1h-8C6.11 1 5 1.9 5 3v18c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2zM13 18h-2v-2h2v2zM11 16h-2v-2h2v2zM18 11c-1.1 0-2 .9-2 2s.9 2 2 2c1.1 0 2-.9 2-2s-.9-2-2-2z"/>
                  </svg></i>
                  <a href="/" >Consumer Electronics</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg class="mr-2" width="24" height="24" viewBox="0 0 24 24">
                     <path d="M12 2C6.47 2 1.5 6.47 1.5 12s4.97 10 10.5 10 10.5-4.97 10.5-10S17.53 2 12 2zm0 18c-4.14 0-7.5-3.36-7.5-7.5 0-4.14 3.36-7.5 7.5-7.5 4.14 0 7.5 3.36 7.5 7.5 0 4.14-3.36 7.5-7.5 7.5z"/>
                  </svg></i>
                  <a href="/" >Home Improvement</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg class="mr-2" width="24" height="24" viewBox="0 0 24 24">
                     <path d="M18 5v14h-4V5zM3 18h8v-8H3v8zM7 5v14h2V5H7z"/>
                  </svg></i>
                  <a href="/" >Toys & Hobbies</a>
                  </li>
                  <li class="flex items-center hover:text-red-500 hover:shadow-lg py-2">
                  <i><svg  class="mr-2" width="24" height="24" viewBox="0 0 24 24">
                     <path d="M12 2C6.47 2 1.5 6.47 1.5 12s4.97 10 10.5 10 10.5-4.97 10.5-10S17.53 2 12 2zm0 18c-4.14 0-7.5-3.36-7.5-7.5 0-4.14 3.36-7.5 7.5-7.5 4.14 0 7.5 3.36 7.5 7.5 0 4.14-3.36 7.5-7.5 7.5z"/>
                  </svg></i>
                  <a href="/">Beauty & Health (Makeup)</a>
                  </li>

             </ul>
             </div> 
         <!-- slider -->
         <div class="w-2/4 bg-white"></div>
           <!-- welcome section -->
         <div class="w-1/4 bg-white"></div>
      </div>
   </div>
</template>

<script>

import Index from '../Components/Header/Index.vue'
export default{
   components:{Index }
}
</script>

<style>

</style>
