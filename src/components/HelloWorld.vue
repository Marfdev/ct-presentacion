<template>      
  <div class="home-view">
    
    <h1 class="display-2 font-weight-thin mb-5 greeting-title">Welcome to Vuetify</h1>
    <v-img
      alt="Vuetify Logo"
      :src="require('../assets/logo.svg')"
      class="my-5 phone-logo"
      contain
      height="200"
    />

    <div class="action-cont">
      <v-btn class="intro-btn">
        <v-icon>mdi-vuetify</v-icon>
        Get started
      </v-btn>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data: () => ({}),
  }
</script>
