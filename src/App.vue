<template>
  <div id="app">
    <body>
   <nav class="navbar navbar-expand-lg navbar-light bg-gradient-light">
    <router-link to="/" class="navbar-brand">HOME</router-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
         <router-link to="/atom" class="nav-link">Atom</router-link>
        </li>
         <li class="nav-item active">
         <router-link to="/molecule" class="nav-link">Molecule</router-link>
        </li>
         <li class="nav-item active">
         <router-link to="/organism" class="nav-link">Organism</router-link>
        </li>
      </ul>
    </div>
  </nav>
  </body>
  <router-view/>
  <footer id="sticky-footer" class="py-4 bg-secondary text-white-50">
    <div class="container text-center">
      <small>Copyright &copy; Naufal Rinaldi</small>
    </div>
  </footer>
  </div>
   <!-- <router-link to="/">Home</router-link> |
    <router-link to="/atom">Atom</router-link> |
    <router-link to="/molecule">Molecule</router-link> |
    <router-link to="/organism">Organism</router-link>
    <router-view/> -->
</template>

<style scoped>
#sticky-footer {
  flex-shrink: none;
  position: absolute;
  right: 0;bottom:0;left:0;
}
</style>
