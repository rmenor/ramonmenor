<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Ramón Menor
      </h1>
      <h3 class="subtitle">Desarrollo web con Nuxt.</h3>
      <p>
        Esta página esta desarrollada con Nuxtjs, un framework basado en vue.js
        para realizar páginas de tipo SPA (Static Page Aplication) o SSR (Server
        Side Rendering)
      </p>
      <br>
      <p>
        <a
          href="https://nuxtjs.org"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Visita Nuxt.js
        </a>
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
