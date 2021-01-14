<template>
  <div class="panel right-panel">
    <div class="content">
      <h3>One of us ?</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molestiae
        eligendi aspernatur alias dignissimos?
      </p>
      <button
        id="sign-in-btn"
        class="btn transparent"
        @click="toggleMode('sign-in-mode')"
      >
        Sign up
      </button>
    </div>

    <img src="../assets/svg/register.svg" alt="" class="image" />
  </div>
</template>

<script>
export default {
  inject: ["toggleMode"],
};
</script>
