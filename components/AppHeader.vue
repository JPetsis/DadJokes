<template>
  <header class="header">
    <h1 class="title">Dad Jokes</h1>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/jokes">Jokes</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "AppHeader"
};
</script>

<style>
.header {
  align-items: center;
  margin: 1rem auto;
  padding: 1rem auto;
  border-bottom: 1px dotted #ccc;
}
.header .title {
  font-size: 3rem;
  color: #526488;
  font-size: 3rem;
  text-align: center;
}
.header ul {
  display: flex;
  margin: 1rem auto;
  justify-content: center;
}
.header a {
  display: inline-block;
  background: #333;
  color: #fff;
  padding: 0.3rem 1rem;
  margin-right: 0.5rem;
}
@media (min-width: 640px) {
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 1rem auto;
    padding: 1rem auto;
    border-bottom: 1px dotted #ccc;
  }
}
</style>
