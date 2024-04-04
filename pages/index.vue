<template>
  <div class="container">
    <div>
      <h2 class="title">
        Sean Hart
      </h2>2
      <div class="about subtitle">
        Software Engineer, Web Developer, Customer Success
      </div>
      <div class="links">
        <a
          href="https://www.linkedin.com/in/sean-c-hart/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          LinkedIn.
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
  background: #000;
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
