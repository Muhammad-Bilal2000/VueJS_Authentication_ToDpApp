<template>
  <div>
    <!-- <div>Welcome Page</div> -->
    <img alt="Vue logo" src="../assets/logo.png" />
    <h1>Welcome to Vue.js Todo App</h1>
    <button type="submit" class="btn btn-primary">
      <router-link class="nav-link" to="/login">Go to login page</router-link>
    </button>
    <!-- <div>
            <router-link to="/posts">Go to posts page</router-link>
    </div> -->
  </div>
</template>
<script>
export default {};
</script>
<style>
img {
  padding-top: 10%;
}
.nav-link{
    color: white;
}
.nav-link :hover{
    color: rgb(231, 210, 210);
}
</style>
