<template>
  <div class="container">
    <div>
      <h1 class="title">
        Sean Hart
      </h1>
      <div class="about subtitle">
        <p>plays drums, designs websites, and builds apps.</p>
        <p>If you want to work together, <a href="mailto:hartsean@gmail.com?Subject=Your%20Subject">shoot me an email</a>. Thanks <span class="smiley">:)</span></p>
      </div>
      <Logo />
      <div class="links">
        <a
          href="http://hartsean.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          Past Work
        </a>
        <a
          href="https://affectionate-aryabhata-d2b1f5.netlify.app/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          No Smoking
        </a>
      </div>
    </div>
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
.smiley {
  color: red;;
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
  color: #016FB9;
  min-height: 100%;
  font-size: 3em;
}

.subtitle {
  color: #526488;
  padding-bottom: 15px;
}

</style>
