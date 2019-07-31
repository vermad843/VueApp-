<template>
<div class ="home text-center">
<div class="jumbotron">
  <h1 class="display-3">Vue App</h1>
  <p class="lead"></p>
  <hr class="my-4">
  <p></p>
  <p class="lead">
    <router-link class="btn btn-primary btn-lg"
     :to ="{name : 'signup'}"
      role="button">Sign Up</router-link>
  </p>
</div>
</div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',

};
</script>
