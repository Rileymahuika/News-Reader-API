<template>
  <header>
    <h3>Header</h3>
    <div class="nav-link">
      <router-link v-bind:to="'/'">Home</router-link>
      <router-link v-bind:to="'/about'">About</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "MyHeader"
};
</script>

<style>

.nav-link {
  display:flex;
  flex-direction:row;
  justify-content:center;
  padding: 12px;
}
.router-link-exact-active {
  color: green;
  text-decoration: none;
  font-size: 20px;
}
.router-link-active {
  color: green;
  text-decoration: none;
  font-size: 20px;
}

h3 {
  text-align: center;
  font-size: 30px;
}
</style>