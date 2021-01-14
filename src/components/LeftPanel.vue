<template>
  <div class="panel left-panel">
    <div class="content">
      <h3>New here ?</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molestiae
        eligendi aspernatur alias dignissimos?
      </p>
      <button
        id="sign-up-btn"
        class="btn transparent"
        @click="toggleMode('sign-up-mode')"
      >
        Sign up
      </button>
    </div>

    <img src="../assets/svg/log.svg" alt="" class="image" />
  </div>
</template>

<script>
export default {
  inject: ["toggleMode"],
};
</script>
