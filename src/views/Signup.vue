<template>

   <section>
   <h1>Signup</h1>
<form>
  <div class="form-group ">
    <label for="username ">Username </label>
    <input
     type="text"
     class="form-control"
     id="username "
     aria-describedby="usernameHelp"
     placeholder="Enter Username ">
    <small id="emailHelp" class="form-text text-muted">Enter a username</small>
  </div>
  <div class="form-row">
  <div class="form-group col-md-6">
    <label for="password">Password</label>
    <input
     type="password"
      class="form-control"
       id="password"
        placeholder="Password">
  </div>


  <div class ="form-group">
    <label for="confirmpassword">ConfirmPassword</label>
    <input
     type="password"
     class="form-control"
     id="conifrmpassword"
      placeholder="Password">
  </div>

  </div>

  <button type="submit" class="btn btn-primary">Sign Up</button>

</form>
   </section>
</template>

<script>
export default {

}
</script>

<style>

</style>

