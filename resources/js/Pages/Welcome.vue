<template>
    <Index />
    <div class="bg-gray-100 h-screen">
        <!-- category -->
        <div class="w-full justify-center space-x-4  max-w-screen-xl mx-auto  py-6 flex">
            <CategoriesMenu/>
            <!-- slider -->
            <div class="w-3/5  space-y-6">
                <div class="space-x-6 font-bold">
                    <a class=" hover:text-red-500"  href="/">Live</a>
                    <a class=" hover:text-red-500"  href="/">Flash Deals</a> 
                    <a class=" hover:text-red-500"  href="/">Store You'll Love</a>
                    <a class=" hover:text-red-500"  href="/">New User Zone</a>
                </div>

                <div class="h-52">
                  <img class="rounded-lg h-full w-full object-cover" 
                  src="https://ae04.alicdn.com/kf/S2cb99275d6ab4824af4e37c45dd9ed97x.jpg_480x480.jpg_.webp"  alt="brand"/>
                </div>

                 <div class="w-full px-5  h-48 bg-gradient-to-r from-yellow-500 to-red-500 rounded-lg flex " >
                        <div class=" w-1/4 space-y-2"> 
                           <h5 class="font-bold">Welcome new comers</h5>
                           <p>Exculisiv price for new comers: act now!</p>
                           <button class="bg-red-500 text-white py-1 px-2">get your cuopon</button>
                           
                        </div>

                        <div class="flex space-x-2 mt-2 w-3/4">
                           <div class="rounded-lg bg-white w-24  h-44">
                             <img class="pt-8" src="https://ae04.alicdn.com/kf/S2cb99275d6ab4824af4e37c45dd9ed97x.jpg_480x480.jpg_.webp">
                             <div class="mx-auto mb-0">
                               <p class="font-bold text-white bg-red-500 mb-0 px-2">Birr 3000</p>
                                 <p class="font-medium text-sm text-gray-500 line-through mb-0 px-2">Birr 6000</p>
                             </div>
                           </div>
                           <div class="rounded-lg bg-white  w-24   h-44">
                               <img class="pt-8" src="https://ae04.alicdn.com/kf/S9218c4dfd58c42378c1d570493b82f5bU.png_480x480.png_.webp">
                             <div class="mx-auto mb-0">
                               <p class="font-bold text-white bg-red-500 mb-0 px-2">Birr 7000</p>
                                 <p class="font-medium text-sm text-gray-500 line-through mb-0 px-2">Birr 30000</p>
                             </div>
                           </div>
                           <div class="rounded-lg bg-white  w-24  h-44">
                               <img class="pt-8" src="https://ae04.alicdn.com/kf/S337c025d39af4a40a75317c3e2d1ceb7F.png_480x480.png_.webp">
                             <div class="mx-auto mb-0">
                               <p class="font-bold text-white bg-red-500 mb-0 px-2">Birr 5000</p>
                                 <p class="font-medium text-sm text-gray-500 line-through mb-0 px-2">Birr 30000</p>
                             </div>
                           </div>
                           <div class="rounded-lg bg-white  w-24  h-44">
                               <img class="pt-8" src="https://ae04.alicdn.com/kf/Sd223968c8dcf47c3b91c2c39e42e1da9I.jpg_480x480.jpg_.webp">
                             <div class="mx-auto mb-0">
                               <p class="font-bold text-white bg-red-500 mb-0 px-2">Birr 200</p>
                               <p class="font-medium text-sm text-gray-500 line-through mb-0 px-2">Birr 300</p>
                             </div>
                           </div>
                        </div>
                </div>

            </div>
            <!-- welcome section -->
            <div class="w-1/4 bg-gradient-to-b from-yellow-200 to-white space-y-4 items-center">
              <div></div>
              <div><img src="https://www.svgrepo.com/show/532392/user-shield.svg"></div>
              <div class="w-full mx-6 "><h3 class="font-bold">Welcome To Aliexpress</h3></div>
              <div class="space-between flex space-x-3 mx-6">
               <button class="bg-red-500 px-7 py-2 text-white rounded-lg">Join</button>
               <button class="bg-white px-4 py-2 text-black rounded-lg">Sign in</button>
              </div>
            </div>
        </div>
    </div>
</template>

<script>
import Index from "../Components/Header/Index.vue";
import CategoriesMenu from "../Components/CategoriesMenu.vue";
export default {
    components: { Index, CategoriesMenu },
};
</script>

<style></style>
