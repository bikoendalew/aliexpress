<template>
  <div class="flex flex-col">
    <div>
        <input type="text" placeholder="shoe in ethiopia" class="w-120 focus:outline-none focus:ring-2 focus:ring-red-500  focus:border-transparent rounded-l-md border-2 border-red-500 border-r-0 "  />
    <select class="w-1/5 focus:outline-none focus:ring-2 focus:ring-red-500  focus:border-transparent  border-2 border-red-500 border-r-0 border-l-0">
    <option value="0">All Categories</option>
    <option value="200003482">Women's Clothing</option>
    <option value="200003463">Men's Clothing</option>
    <option value="200003655">Phones & Telecommunications</option>
    <option value="200001065">Computer & Office</option>
    <option value="200003614">Consumer Electronics</option>
    <option value="200003235">Home & Garden</option>
    <option value="200002394">Beauty & Health</option>
    <option value="200003498">Automobiles & Motorcycles</option>
    <option value="200001536">Jewelry & Accessories</option>
    <option value="200002097">Toys & Hobbies</option>
    <option value="200003572">Home Improvement</option>
    <option value="200002984">Tools</option>
    <option value="200003558">Sports & Entertainment</option>
    <option value="200003456">Mother & Kids</option>
    <option value="200002960">Furniture</option>
    <option value="200003595">Electronic Components & Supplies</option>
    <option value="200003604">Office & School Supplies</option>
    <option value="200003596">Security & Protection</option>
    <!-- Add more options as needed -->
  </select>

  <button class="bg-red-500 text-white  p-2  rounded-r-md">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
    <path fill-rule="evenodd" d="M9 3.5a5.5 5.5 0 1 0 0 11 5.5 5.5 0 0 0 0-11ZM2 9a7 7 0 1 1 12.452 4.391l3.328 3.329a.75.75 0 1 1-1.06 1.06l-3.329-3.328A7 7 0 0 1 2 9Z" clip-rule="evenodd" />
    </svg>

  </button>
   <!-- <Cart/> -->
  

    </div>
    
    <div class="space-x-2 grid grid-cols-6 text-sm divide-2 divide-x divide-gray-400 py-2 ">
        <a href="/" class="hover:text-red-500 text-center">running pants</a>
        <a href="/" class="hover:text-red-500 text-center">men sport</a>
        <a href="/" class="hover:text-red-500 text-center">survival kit</a>
        <a href="/" class="hover:text-red-500 text-center">r5 3200</a>
        <a href="/" class="hover:text-red-500 text-center">ps2 usb</a>
    </div>
  </div>
</template>


<script>
import  Cart from './CartComponent.vue'

export default{
  components:{Cart}
  }
</script>
