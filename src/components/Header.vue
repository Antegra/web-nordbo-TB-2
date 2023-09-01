

<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a style="width:312px; height:128px;" class="navbar-item" href="https://bulma.io">
      <img style="width:312px; max-height:128rem; height:128px;" src="\src\assets\img\nordbo-logo.webp">
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <RouterLink to="/" class="navbar__item">
        Sale
        
      </RouterLink>
      <div style="width: 100%; height: 100%; position: relative; transform: rotate(-0deg); transform-origin: 0 0">
    <div style="width: 7.93px; height: 49.47px; left: 0px; top: -3.26px; position: absolute; transform: rotate(-90deg); transform-origin: 0 0; background: #3DBFEA"></div>
    <div style="width: 12.83px; height: 3.20px; left: 11.15px; top: -0.02px; position: absolute; transform: rotate(-115.63deg); transform-origin: 0 0; background: white"></div>
    <div style="width: 12.80px; height: 3.20px; left: 18.14px; top: 0px; position: absolute; transform: rotate(-115.63deg); transform-origin: 0 0; background: #FFFEFE"></div>
</div>
      <RouterLink to="/products" class="navbar__item">
        Products
      </RouterLink>
      <RouterLink to="/clients" class="navbar__item">
        Clients
      </RouterLink>
      
    </div>

    <div class="navbar-end">
      <div class="navbar__item">
        <div class="buttons">
          <div class="navbar__item has-dropdown is-hoverable">
            <a class="navbar-link navbar__item navbar-icon">
              <img src="\src\assets\img\settings.webp">
            </a>

        <div class="navbar-dropdown">
          <a class="navbar__item">
            Settings
          </a>
          <a class="navbar__item">
            Increased contrast
          </a>
          <a class="navbar__item">
            Color blindness
          </a>
          <a class="navbar__item">
            Larger text
          </a>
          <a class="navbar__item">
            Dark theme
          </a>
          <a class="navbar__item">
            Screen reader
          </a>
        </div>
      </div>
          
          <RouterLink to="/login"  class="navbar__item navbar-icon">
            <img src="\src\assets\img\logout.webp">
          </RouterLink>
        </div>
      </div>
    </div>
  </div>
</nav>
</template>

<style lang="scss" scoped>

@import "../../node_modules/bulma/css/bulma.min.css";


.navbar-start {
  justify-items: center;
  margin: auto;
  font-size: large;

  
}

.navbar-start a {
  margin-left: 40px;
  margin-right: 40px;
}

.navbar-end {
  max-width:100px;
}

.navbar-icon img {
  width:50px; 
  max-height:50rem;
}

.navbar__item {
  font-family: Ubuntu;
}

</style>