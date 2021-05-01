<template>
  <div class="container">
    <div>
      <h1 class="title">
        Sean Hart
      </h1>
      <div class="about subtitle">
        <p>musician, storyteller, traveler</p>
      </div>
      <div class="links">
        <a
          href="http://hartsean.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          History
        </a>
        <a
          href="/future"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          Future
        </a>
      </div>
    </div>
    <div class="smoking">
        <a href="https://affectionate-aryabhata-d2b1f5.netlify.app/">🚬</a> 
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
.smoking {
  position: absolute;
  float: left;
  margin-left: 95%;
}

</style>
