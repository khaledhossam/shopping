<template>
<div>
  <nav-bar></nav-bar>
  <right-nav></right-nav>
  <category></category>
  <offers></offers> 
</div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import RightNav from '@/components/RightNav.vue'
import Category from '@/components/Category.vue'
import Offers from '@/components/Offers.vue'
export default {
  name: 'App',

  components: {
    "nav-bar":NavBar,
    "right-nav":RightNav,
    "category":Category,
    "offers":Offers
  },

  data: () => ({
    //
  }),
};
</script>
