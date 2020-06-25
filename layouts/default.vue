<template>
<<<<<<< HEAD
      <div >
       
=======
  <div>
    <nav
      class="navbar header has-shadow is-primary"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="navbar-brand">
        <a
          class="navbar-item"
          href="/"
        >
          <img
            src="~assets/buefy.png"
            alt="Buefy"
            height="28"
          >
        </a>

        <div class="navbar-burger">
          <span />
          <span />
          <span />
        </div>
      </div>
    </nav>

    <section class="main-content columns is-mobile">

      <aside class="column is-2 section">
        <p class="menu-label is-hidden-touch">General</p>
        <ul class="menu-list">
          <li
            v-for="(item, key) of items"
            :key="key"
          >
            <nuxt-link
              :to="item.to"
              exact-active-class="is-active"
            >
              <b-icon :icon="item.icon" /> {{ item.title }}
            </nuxt-link>
          </li>
        </ul>
      </aside>

      <div class="container column is-10">
>>>>>>> 5aa0f7f6a8f71bdcce9510cea953af3119eb779c
        <nuxt />
        <div class="navbar">  
          <ul>
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

<style>

.navbar ul{
 overflow: hidden;
  position: fixed;
  bottom: 0;
  width: 100%;
  border-top: black solid 1px;
    
}

ul{ 
    padding: 5px;
    display: flex; 
    flex-direction : row; 
    justify-content: space-around; 
};

</style>
