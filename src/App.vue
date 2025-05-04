<template>
  <h1 id="google-logo">
    <span class="g1">G</span>
    <span class="o1">o</span>
    <span class="o2">o</span>
    <span class="g2">g</span>
    <span class="l">l</span>
    <span class="e">e</span>
  </h1>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
/* Import Montserrat font */
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

#app {
  font-family: 'Montserrat', sans-serif;
  text-align: center;
  margin-top: 15vh;
}

/* Google Logo */
#google-logo {
  font-size: 87px;  
  font-weight: 570;
}

/* Light Mode Logo */
.g1 { color: #4285F4; }  /* Blue */
.o1 { color: #EA4335; }  /* Red */
.o2 { color: #FBBC05; }  /* Yellow */
.g2 { color: #4285F4; }  /* Blue */
.l  { color: #34A853; }  /* Green */
.e  { color: #EA4335; }  /* Red */
</style>
