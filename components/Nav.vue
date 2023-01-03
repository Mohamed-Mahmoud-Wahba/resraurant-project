<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <nuxt-link class="navbar-brand" to="/">Restaurantly</nuxt-link>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <nuxt-link class="nav-link active" aria-current="page" to="/">Home</nuxt-link>
              </li>
              <li class="nav-item">
                <nuxt-link class="nav-link" to="/resraurants">Resraurant</nuxt-link>
              </li>

            </ul>
          </div>
        </div>
      </nav>
</template>
<style lang="scss" scoped>
.ml-auto{
    margin-left: auto;
}
</style>