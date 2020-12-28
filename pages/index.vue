<template>
  <div class="container">
    <div>
      <h1 class="title">
        Sean Hart
      </h1>
      <div class="about subtitle">
        <p>Hi, I play the drums, design websites and develop apps.</p>
        <p>If you want to work together, <a href="mailto:hartsean@gmail.com?Subject=Sean%20Hart%20Website%20Inquiry">email me here</a>. Thanks :)</p>
      </div>
      <Logo />
      <div class="links">
        <!-- <a
          href="http://hartsean.com/Sean_Hart_Resume.pdf"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          My Resume
        </a> -->
        <!-- <a
          href="https://github.com/hartsean"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a> -->
        <a
          href="http://hartsean.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green b-g"
        >
          Past Work
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
  background: #44b6af!important;
  background: fixed;
}
.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #232323;
  letter-spacing: 1px;
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
