<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark bg-gradient">
    <div class="container-fluid">
      <!-- <a class="navbar-brand" href="#">Gif Routes</a> -->
      <router-link class="navbar-brand" to="/">Gif Router</router-link>
      <button class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarNav"
              aria-controls="navbarNav"
              aria-expanded="false"
              aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
            <router-link class="nav-link active" aria-current="page" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link" href="#">About</a> -->
            <router-link class="nav-link active" aria-current="page" to="/about">About</router-link>
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link" href="#">About</a> -->
            <router-link class="nav-link active" aria-current="page" to="/gifs">Gifs</router-link>
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link" href="#">About</a> -->
            <router-link class="nav-link active" aria-current="page" to="/stickers">Stickers</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
}
</script>

<style>
</style>
