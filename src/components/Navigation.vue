<template>
  <v-toolbar app color="brown darken-4" dark>
    <img class = "logo" src="../assets/tx-logo.png"> <p class = "name"> TEXAS </p> 
    <router-link to="/">About</router-link> <p>|</p> 
    <router-link to="/funfact">Fun Facts</router-link>
  </v-toolbar>
</template>

<script>
export default {
    name: 'Navigation'
};
</script>

<style scoped>
.logo{
  height: 64px;
  width: 64px;
  margin-right: 10px;
}

.name{
  margin-right: 10px;
}

a {
  font-weight: bold;
  color: #FFFFFF;
  padding-right: 10px;
  padding-left: 10px;
}

a.router-link-exact-active {
  color: #BF0A30;
}

p {
    color: #FFFFFF;
}

</style>