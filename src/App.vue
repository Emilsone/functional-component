<template>
  <div id="app">
    <UserProfile />
  </div>
</template>
<script>
import UserProfile from "./components/UserProfile.vue";


export default {
  name: "app",
  components: {
    UserProfile,

  },
};
</script>

<style >
@import url("https://fonts.googleapis.com/css2?family=Work+Sans&display=swap");
#app {
  font-family: "Work Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

<style module>
.heading {
  font-size: 50px;
  font-weight: 900;
  text-align: center;
}
</style>