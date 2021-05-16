<template>
  <p>
    <Hello visitorName="Satyam" />
  </p>
  <div class="row">
    <div class="col-md-6">
      <Hardik txt="Username" pwd="password" />
    </div>
    <div class="col-md-6">
      <Hardik txt="Email" pwd="otp" />
    </div>
  </div>
</template>

<script>
import Hardik from "./components/Hardik.vue";
import Hello from "./components/Hello.vue";
export default {
  name: "App",
  components: {
    Hardik,
    Hello,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
