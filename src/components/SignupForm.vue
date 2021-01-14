<template>
  <form @submit.prevent class="sign-up-form">
    <h2 class="title">Sign up</h2>
    <div class="input-feild">
      <i class="fas fa-user"></i>
      <input type="text" placeholder="Username" />
    </div>
    <div class="input-feild">
      <i class="fas fa-envelope"></i>
      <input type="text" placeholder="Email" />
    </div>
    <div class="input-feild">
      <i class="fas fa-lock"></i>
      <input type="password" placeholder="Password" />
    </div>
    <input type="submit" value="Sign up" class="btn solid" />

    <p class="social-text">Or Sign up with Social platforms</p>

    <div class="social-media">
      <a href="#" class="social-icon"><i class="fab fa-facebook-f"></i></a>
      <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
      <a href="#" class="social-icon"><i class="fab fa-google"></i></a>
      <a href="#" class="social-icon"><i class="fab fa-linkedin-in"></i></a>
    </div>
  </form>
</template>
