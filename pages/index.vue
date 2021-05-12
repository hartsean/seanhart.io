<template>
  <div class="container">
    <div>
      <h2 class="title">
        sean hart
      </h2>
      <div class="about subtitle">
        design and code for the web; music
      </div>
      <div class="links">
        <a
          href="http://hartsean.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          Past
        </a>
        <a
          href="/blog"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
        Current
        </a>
      </div>
    </div>
    <!-- <a href="https://affectionate-aryabhata-d2b1f5.netlify.app/">🚬</a> -->
  </div>
</template>

<script>
</script>

<style>
.container {
  background: #fef9e9;
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
a.b-g:hover{
  color: #DA2c38;
  background: fixed;
}
a {
  color: #016FB9;
}
a:hover{
  color: #DA2c38;
}
.title {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  color: #000;
  min-height: 100%;
  font-size: 2.1em;
}

.subtitle {
  color: #526488;
  padding-bottom: 15px;
}

</style>
