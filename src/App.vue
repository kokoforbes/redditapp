<template>
  <div id="app">
    <header>
      <h3>Subreddits</h3>
    </header>
    <subreddits category="food"></subreddits>
    <subreddits category="sports"></subreddits>
    <subreddits category="movies"></subreddits>
    <subreddits category="art"></subreddits>
    <subreddits category="technology"></subreddits>
    <subreddits category="funny"></subreddits>
  </div>
</template>

<script>

import subreddits from './components/subreddits'
export default {
  name: 'App',
  components: {
   subreddits,
  }
}
</script>

<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  color: #666;
  background: #f4f4f4;
  margin: 0;
  padding: 0;
}

header {
  padding: 10px;
  background: coral;
  color: #fff;
  text-align: center;
}

a {
  text-decoration: none;
}
</style>
