<<<<<<< Updated upstream


<template>
      <div >
        <nuxt />
        <div class="navbar">  
          <ul>
=======
<template>
  <div class="content" id="anchor1">

        <nuxt />
        

        <a class="retour"><nuxt-link :to="{path: '/', hash: '#anchor1'}" class="button">^</nuxt-link></a>
        <div class="barnav">  
          <ul class="navicone">
>>>>>>> Stashed changes
            <li>
              <nuxt-link to="/">
              <i class="fa fa-home" aria-hidden="true"></i>
              </nuxt-link>
            </li>
            <li>
               <nuxt-link to="/">
              <i class="fa fa-cutlery" aria-hidden="true"></i>
              </nuxt-link>
            </li>
            <li>
               <nuxt-link to="/">
              <i class="fa fa-book" aria-hidden="true"></i>
              </nuxt-link>
            </li>
            <li>
               <nuxt-link to="/">
              <i class="fa fa-address-card-o" aria-hidden="true"></i>
              </nuxt-link>
            </li>
          </ul>
          </div>
      </div> 
</template>

<<<<<<< Updated upstream
<style>
=======
<style langue="css">

body{
  /* background-color: lightblue; */
  height: 10000px;
  }
.barnav .navicone{
>>>>>>> Stashed changes

.navbar ul{
 overflow: hidden;
 bottom: 0;
  position: fixed;
  
  width: 100%;
  border-top: black solid 1px;
    
}

<<<<<<< Updated upstream
ul{ 
=======
       .retour, .retour:visited{
         position: fixed;
         right: 5px;
         bottom:25.5vh;
         text-decoration: none;
       }   

       .button, .button:visited{
         background-color: white;
         color: lightblue;
         font-size: 1.8em;
         
         
       }


       .button:hover{
         background-color: lightblue;
         color: white;
         text-decoration: none;
         }


.navicone{ 
  margin-left: 0;
    height:25vh;
>>>>>>> Stashed changes
    padding: 5px;
    display: flex; 
    flex-direction : row; 
    justify-content: space-around; 
};


</style>
