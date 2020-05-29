<template>
  <v-card
    height="1650px"
    width="250px"
    class="mx-auto"

  >
    <v-navigation-drawer permanent>
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="title">
            My Account
          </v-list-item-title>
          <v-list-item-subtitle>
       
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list
        dense
        nav
      >
        <v-list-item
          v-for="item in items"
          :key="item.title"
          link
        >
          <v-list-item-icon>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </v-card>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          { title: 'Home', icon: 'mdi-view-dashboard' },
          { title: 'Hot Offers', icon: 'mdi-image' },
          { title: 'Products', icon: 'mdi-image' },
          { title: 'Services', icon: 'mdi-image' },
          { title: 'New Feeds', icon: 'mdi-image' },
          { title: 'Terms & Policy', icon: 'mdi-image' },
          { title: 'About', icon: 'mdi-help-box' },
        ],
        right: null,
      }
    },
  }
</script>
<style>
.mx-auto{
    float: left;
    
}
.v-list-item__title{
    font-family: 'Roboto';
    font-size: 16px;
    font-weight: bold;
    height: 19px;
    width: 43px;
    color: rgba(36, 170, 147, 1);
    padding-left: 20px;

}


</style>