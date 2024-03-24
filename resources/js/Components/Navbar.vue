<template>
    <header class="bg-gray-100">
      <nav class="container mx-auto px-8">
        <ul class="flex justify-end space-x-8  py-3 test-sm">
            <li> 
                <a href="/">sell on aliexpress</a>
            </li>

             <li> 
                <a href="/">help</a>
            </li>
             <li> 
                <a href="/" class="flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg"  fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-1">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z" />
                    </svg>

                Wishlist</a>
            </li>
             <li  class="relative" @mouseover="isAccountHover=true" cursor-pointer> 
               
                <span href="/" :class="isAccountHover? 'text-red-400':'' " class="flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5 mr-1">
                <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                </svg>
                
                Account </span>
                <div v-if="isAccountHover" @mouseleave="isAccountHover=false" class="absolute right-0  p-4 h-max w-max mt-3 bg-gray-100">
                    <div class="flex space-x-2 py-2 border-b-2 border-gray-200">
                        <button class="bg-red-500 text-white py-2 px-8 text-center font-bold rounded-sm">Join</button>
                        <button class="bg-red-100 text-red py-2 px-8 text-center font-bold rounded-sm">Sign in</button>
                    </div>
                    <ul class="my-3 text-sm">
                        <li>
                            <a href="/">My Orders</a>
                        </li>
                         <li>
                            <a href="/">My Wishlist</a>
                        </li>
                         <li>
                            <a href="/">My Coupons</a>
                        </li>

                         <li>
                            <a href="/">Message Center</a>
                        </li>
                    </ul>
                </div>

                
            </li>
        </ul>
      </nav>
   </header>
</template>

<script>
export default {
 data(){
        return {
            isAccountHover: false,
        }
    },
}
</script>

<style>

</style>