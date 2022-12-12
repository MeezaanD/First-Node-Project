<template>
  <nav>
    <nav class="navbar navbar-expand-lg bg-dark">
      <div class="container-fluid">
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link active text-light" aria-current="page" href="/">Home</a>
            <a class="nav-link text-light" href="/about">About</a>
            <a class="nav-link text-light" href="/contact">Contact</a>
          </div>
        </div>
      </div>
    </nav>
  </nav>
  <body>
  </body>
  <router-view/>
  <div>
    <footer class="foot">
      <p>&copy; Copyright 2022 </p>
    </footer>
  </div>
</template>

<style>
.foot {
  text-align: center;
}
</style>
