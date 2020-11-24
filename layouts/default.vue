<template>
  <div class="container">
    <Header />
    <Nuxt />
  </div>
</template>

<style>
  html {
    font-family:
      'Source Sans Pro',
      -apple-system,
      BlinkMacSystemFont,
      'Segoe UI',
      Roboto,
      'Helvetica Neue',
      Arial,
      sans-serif;
    font-size: 0.9em;
    word-spacing: 1px;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
    background-color: gray;
  }
  *,
  *::before,
  *::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  a {
    text-decoration: none;
    color: #101622;
  }
  a:hover {
    color: gray;
  }
  ul {
    list-style-type: none;
  }

  .text-justify {
    text-align: justify;
  }

 .container {
   width: 100%;
   min-height: 100vh;
   margin: 0 auto;
   padding: 0 10px;
   display: flex;
   flex-direction: column;
   justify-content: center;
   text-align: center;
   line-height: 1.5em;
   color: #101622;
   background-color: #fff;
 }
 header {
   flex-grow: 1;
 }
  article, section, main {
   flex-grow: 999;
 }
@media (min-width: 540px ) {
  .container {
    width: 540px;
  }
}
</style>

