<template>
  <div id="app">
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item is-size-3">
     Golkanda resorts
    </a>

    <a role="button" class="navbar-burger burger"
    aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-end">
      <router-link to="/" class="navbar-item">
        Home
      </router-link>

      <router-link to="/Events" class="navbar-item">
       Events and Services
      </router-link>

      <router-link to="/Gallery" class="navbar-item">
       Gallery
      </router-link>

      <router-link to="/Contact" class="navbar-item">
       Get in touch!
      </router-link>
    </div>
  </div>
</nav>
    <router-view/>
    <br>
    <div class="footer">
     <div class="columns">
       <div class="column is-4">
         <div class="text">
           Location
         </div>
         <div class="map">
           <img src="@/assets/map.png" alt="">
         </div>
       </div>
        <div class="column is-4">
          <div class="text">
           Contact us:
         </div>
         <div class="text">
           Sagar Mahal Complex, Gandipet,
         </div>
          <div class="text">
            R R District, Near Osman Sagar Lake,
          </div>
          <div class="call">
            <div class="text">
              Call us
            </div>
            <div class="text">
              +91 123456789
            </div>
          </div>
        </div>
        <div class="column is-4">
          <i class="fa fa-facebook" aria-hidden="true"></i>
        </div>
     </div>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.footer {
  background: grey;
}

.text {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
}

.map {
  width: 180px;
  height: 180px;
}

</style>
