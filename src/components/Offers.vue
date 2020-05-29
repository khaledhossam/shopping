<template>
<v-container fluid>
<div>
  <v-container fluid>
    <h1 class="banner"> Hot offers for you </h1>
    <v-row>
      <v-col cols="6" sm="4">
        <v-img
          src="@/assets/offers1.png"
          gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
        ></v-img>
      </v-col>

      <v-col cols="6" sm="4">
        <v-img src="@/assets/offers2.png">
          <div class="fill-height bottom-gradient"></div>
        </v-img>
      </v-col>

      <v-col cols="6" sm="4">
        <v-img src="@/assets/offers3.png">
          <div class="fill-height repeating-gradient"></div>
        </v-img>
      </v-col>
    </v-row>
  </v-container>

  <v-container fluid>
    <h1 class="banner"> Products you may like  </h1>
    <v-row>
      <v-col cols="6" sm="2">
        <v-img
          src="@/assets/prod1.png"
          gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
        ></v-img>
      </v-col>

      <v-col cols="6" sm="2">
        <v-img src="@/assets/prod2.png">
          <div class="fill-height bottom-gradient"></div>
        </v-img>
      </v-col>

      <v-col cols="6" sm="2">
        <v-img src="@/assets/prod3.png">
          <div class="fill-height repeating-gradient"></div>
        </v-img>
      </v-col>

            <v-col cols="6" sm="2">
        <v-img src="@/assets/prod2.png">
          <div class="fill-height bottom-gradient"></div>
        </v-img>
      </v-col>

      <v-col cols="6" sm="2">
        <v-img src="@/assets/prod5.png">
          <div class="fill-height bottom-gradient"></div>
        </v-img>
      </v-col>

      <v-col cols="6" sm="2">
        <v-img src="@/assets/prod6.png">
          <div class="fill-height bottom-gradient"></div>
        </v-img>
      </v-col>

    </v-row>
  </v-container>


  <v-container fluid>
    <h1 class="banner"> News Feed  </h1>
    <v-row>
      <v-col cols="6" sm="5">
          <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="@/assets/feeds1.png"
    >
   
    </v-img>

    <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

    <v-card-text class="text--primary">
      <div>Whitehaven Beach</div>

      <div>Whitsunday Island, Whitsunday Islands</div>
    </v-card-text>
    <b-button class="button"  href="#" variant="primary">Call to Action</b-button>

  </v-card>
</v-col>

  <v-col cols="6" sm="6">
 <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="@/assets/feeds2.png"
    >
   
    </v-img>

    <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

    <v-card-text class="text--primary">
      <div>Whitehaven Beach</div>

      <div>Whitsunday Island, Whitsunday Islands</div>
    </v-card-text>

    <b-button class="button" href="#" variant="primary">Call to Action</b-button>
  </v-card>       

      </v-col>

  
    </v-row>
  </v-container>



  <v-container fluid>
    <h1 class="banner"> Services </h1>
    <v-row>
      <v-col cols="6" sm="5">
          <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="@/assets/feeds1.png"
    >
   
    </v-img>

    <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

    <v-card-text class="text--primary">
      <div>Whitehaven Beach</div>

      <div>Whitsunday Island, Whitsunday Islands</div>
    </v-card-text>
    <b-button class="button"  href="#" variant="primary">Call to Action</b-button>

  </v-card>
</v-col>

  <v-col cols="6" sm="6">
 <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="@/assets/feeds2.png"
    >
   
    </v-img>

    <v-card-subtitle class="pb-0">Number 10</v-card-subtitle>

    <v-card-text class="text--primary">
      <div>Whitehaven Beach</div>

      <div>Whitsunday Island, Whitsunday Islands</div>
    </v-card-text>

    <b-button class="button" href="#" variant="primary">Call to Action</b-button>
  </v-card>       

      </v-col>

  
    </v-row>
  </v-container>


</div>
</v-container>
</template>

<style>
.banner{
    font-family: 'Roboto';
    font-size: 30px;
    font-weight: 500;
    color: rgba(22, 19, 90, 1);
    padding-left: 20%;
    padding-top: 20px;
    
    
}
.button {
  font-family: Roboto;
  background-color:rgba(22, 19, 90, 1);
  border-radius: 8px;
  height: 40px;
  width: 135px;
  float: right;
  
}


.v-card__actions {
    align-items: center;
    display: flex;
    padding: 8px;
    float: right;
}


</style>