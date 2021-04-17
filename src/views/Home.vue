<template>
  <div class="home">
    <div class="container">
      <div class="row d-flex justify-content-center align-items-center">
        <Login />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from "@/components/Login.vue";

export default {
  name: "Home",
  components: {
    Login,
  },
};
</script>

<style scoped>
.home {
  display: flex;
  align-items: center;

  height: 100vh;
}
</style>