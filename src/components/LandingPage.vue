<template>
    <div id="app">
      <LandingPage />
    </div>
  </template>
  
  <script>
  import LandingPage from './components/LandingPage.vue';
  
  export default {
    name: 'App',
    components: {
      LandingPage
    }
  };
  </script>
<style scoped>
.landing-page {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-image: url('https://jefthanizaam01.github.io/favoriteimages/images/watchdesign.jpg');
  background-size: cover;
  background-position: center;
}

.overlay {
  background-color: rgba(0, 0, 0, 0.5); 
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}

.title {
  font-size: 4em;
  color: #b0a8a1; 
  margin: 0;
}

.slogan {
  font-size: 1.5em;
  color: #b0a8a1; 
}
</style>
  