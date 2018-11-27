<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body, h1, h2, h3, h4, h5, h6, p {
  margin: 0;
  font-family: pt-sans;
}

@font-face {
  font-family: pt-sans;
  font-weight: 400;
  src: url('./assets/fonts/pt-regular.woff');
}

@font-face {
  font-family: pt-sans;
  font-weight: 700;
  src: url('./assets/fonts/pt-bold.woff');
}

#app {

}
</style>
