<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" src="./assets/build-a-bot-logo.png">
            Build-a-Bot
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <HomePage/>
    </main>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'app',
  components: {
    HomePage,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
}

main {
  margin: 0 auto;
  padding: 30px;
  background-color: #fff;
  width: 1024px;
  min-height: 300px;
}

.nav-item {
}

.logo {
}
</style>
