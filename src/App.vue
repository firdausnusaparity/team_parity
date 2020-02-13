<template>
  <div id="app">
    <LoginNav />
    <SignUp />
  </div>
</template>

<script>
import LoginNav from "./components/LoginNav";
import SignUp from "./components/SignUp";

export default {
  name: "app",
  components: { LoginNav, SignUp }
};
</script>
