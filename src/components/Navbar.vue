<template>
    <div>
     <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/properties">Properties</router-link> |
    <router-link to="/admin">Admin</router-link> 
  </nav>   
    </div>
</template>
<script>
export default {
    name:'Navbar',
}
</script>

<style>
 nav {
  padding: 30px;
  background-color: cornflowerblue;
}

nav a {
  color: black;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: white;
  font-weight:bold;
}
</style>