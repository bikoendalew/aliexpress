<template>
  <div class="flex items-center container mx-auto  bg-white py-3"> 
  <Logo/>
  <Search/>
  
  </div>

</template>

<script>
import Logo from './LogoHeader.vue'
import Search from './SearchComponent.vue'
import Navbar from '../Navbar.vue'

export default {
 components:{
    Logo,Search,Navbar
 }
}
</script>

<style>

</style>