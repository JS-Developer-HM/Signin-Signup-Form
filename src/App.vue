<template>
  <div class="container" :class="containerClass">
    <div class="forms-container">
      <div class="signin-signup">
        <sign-in-form></sign-in-form>
        <sign-up-form></sign-up-form>
      </div>
    </div>
    <div class="panels-container">
      <left-panel></left-panel>
      <right-panel></right-panel>
    </div>
  </div>
</template>
<script>
import SignInForm from "./components/SigninForm.vue";
import SignUpForm from "./components/SignupForm.vue";
import LeftPanel from "./components/LeftPanel.vue";
import RightPanel from "./components/RightPanel.vue";

export default {
  components: { SignInForm, SignUpForm, LeftPanel, RightPanel },
  name: "App",
  data() {
    return {
      containerClass: "sign-in-mode",
    };
  },
  methods: {
    toggleMode(cl) {
      this.containerClass = cl;
    },
  },

  provide() {
    return {
      containerClass: this.containerClass,
      toggleMode: this.toggleMode,
    };
  },
};
</script>
