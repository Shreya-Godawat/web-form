<template>
  <form action="">
    <div class="mb-3">
      <h2>Sign In</h2>
      <div class="mb-3">
        <label for="mail" class="form-label bold">Email address</label>
        <input
          type="email"
          class="form-control"
          id="mail"
          placeholder="name@example.com"
          v-model="email"
          required
        />
      </div>
    </div>
    <div class="mb-3">
      <label for="password" class="form-label bold">Password</label>
      <input
        type="password"
        class="form-control"
        id="password"
        placeholder="Password"
        v-model="password"
        required
      />
    </div>
    <br /><br />
    <div class="d-grid footer">
      <button class="btn btn-primary" type="button">Sign In</button>
    </div>
  </form>
</template>

<script>
export default {
  data() {
    return {
      email: "",
      password: ""
    };
  },
};
</script>

