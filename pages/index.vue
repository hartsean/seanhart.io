<template>
  <div class="container">
    <div>
      <h1 class="title">
        Sean Hart
      </h1>
      <div class="about subtitle">
        <p>plays drums, designs websites, and builds apps.</p>
        <p>If you want to work together, <a href="mailto:hartsean@gmail.com?Subject=Sean%20Hart%20Website%20Inquiry">shoot me an email</a>. Thanks :)</p>
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
          class="button--blue b-b"
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
  color: #FFF!important;
  background: #016FB9!important;
  background: fixed;
}
.title {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  color: #232323;
  min-height: 100%;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
a{
  color: #44b6af;
}
a:hover {
  color: #526488;
}
.links {
  padding-top: 15px;
}

</style>
