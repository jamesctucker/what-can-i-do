<template>
  <div class="main p-4 mt-0 mb-0 mr-auto ml-auto">
    <div class="container">
      <Header />
      <nuxt />
      <Footer />
    </div>
  </div>
</template>
<script>
import Header from "../components/Header";
import Footer from "../components/Footer";

export default {
  name: "Layout",
  components: {
    Header,
    Footer
  }
};
</script>

<style>
html {
  font-family: "Lato", sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

div {
  background: #ffff;
}

nav {
  position: absolute;
  top: 0;
  left: 0;
}

p {
  font-size: 16px;
  color: #202040;
}

ul,
li {
  color: #202040;
  font-size: 16px;
}

ul {
  list-style-type: square;
  list-style-position: inside;
}

h6,
h5,
h4,
h3,
h2,
h1 {
  color: #202040;
  font-weight: 700;
  font-family: "Lato", sans-serif;
}

h1 {
  font-size: 2.5em;
}

h2 {
  font-size: 2em;
}

h3 {
  font-size: 1.75em;
}

h4 {
  font-size: 1.5em;
}

h5 {
  font-size: 1.25em;
}

h6 {
  font-size: 1.1em;
}

a:hover {
  color: rgb(255, 20, 147);
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.main {
  border-top: 10px solid rgb(20, 146, 255);
  min-height: 100vh;
}

.container {
  max-width: 800px;
  margin: 0 auto;
}
</style>
