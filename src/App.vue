<template>
  <div id="app">
    <header>
      <div class="title">
        <img src="@/assets/logo.png" alt="ngxify">
        <span>ngxify</span>
      </div>
      <ul class="dropdown">
        <li><!-- TODO --></li>
      </ul>
    </header>
    <div class="layout">
      <div class="desktop">
        <!-- TODO -->
      </div>
      <div class="favorite">
        <!-- TODO -->
      </div>
    </div>
    <footer>
      <span>Copyright &copy; Nutcore LLC.</span>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      config: {},
      locale: localStorage["locale"]
    };
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  header {
    display: flex;
  }

  .title {
    display: flex;
    align-items: center;
    font-size: 1.6em;
  }
  .title img {
      height: 32px;
  }
  .title span {
    margin: 8px;
  }
}
</style>
