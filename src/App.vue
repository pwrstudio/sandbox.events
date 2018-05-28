<template>
  <div id="app">
    <div id="nav">
      <span class='main-title'>SANDBOX</span>
      <span class='divider'>/</span>
      <router-link to="/0">0</router-link>
      <span class='divider'>/</span>
      <router-link to="/1">1</router-link>
      <span class='divider'>/</span>
      <router-link to="/2">2</router-link>
      <span class='divider'>/</span>
      <router-link to="/3">3</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@import './assets/fonts/lincolnmitre/stylesheet.css';

body,
html {
  font-family: 'lincolnmitrelm', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #00f;
  font-size: 64px;
  background: #000;
  padding: 0;
  margin: 0;
  overflow-x: hidden;
}

#app {
  padding: 0;
  margin: 0;
}

a {
  color: inherit;
  text-decoration: none;
  &:hover,
  &:active {
    text-decoration: none;
    color: #fff;
  }
  &.router-link-active {
    color: #fff;
  }
}

#nav {
  margin-left: 20px;
  user-select: none;
}

.divider {
  color: #fff;
  margin-right: 10px;
  margin-left: 10px;
}

.main-title {
  // text-decoration: underline;
  // border-bottom: 8px solid #00f;
}
</style>
