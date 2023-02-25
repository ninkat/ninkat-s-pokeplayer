<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height p-4">
      <div class="container pt-3">

      </div>

    </div>

    <div id="footer" class="bg-primary p-2">
      
    </div>
  </div>
  </template>
  
  <script>
  
  export default 
  {
    name: 'SplashPage',
    data(){
      return {
        title: "StudyLog \"Prototype\""
        
      }
      
    }
  };
  </script>
  
  <style scoped>
  .full-height {
    min-height: 100vh;
  }

   #home-page {
    background-color: #92D2F2;
    background: url("https://i.ibb.co/r3FfnQr/olja-lobkis-studygram-04.jpg") no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    opacity: 0.95;
   }
   #umsae-logo {
    max-height: 80vh;
   }
   
   .border {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  height: 10%;
  }
  .display-3 {
  color: black;
}
  </style>
    
    