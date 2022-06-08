<template>
  <form>
    <div class="mb-3">
      <h2>Sign Up</h2>
    </div>
    <div class="mb-3">
      <label for="name" class="form-label bold">Name</label>
      <input
        type="text"
        class="form-control"
        id="name"
        placeholder="Your name"
        v-model="name"
        required
      />
    </div>
    <div class="mb-3">
      <label for="mail" class=" form-label bold">Email address</label>
      <input
        type="email"
        class="form-control"
        id="mail"
        placeholder="name@example.com"
        v-model="email"
        required
      />
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
    <div class="mb-3 form-check">
      <input
        type="checkbox"
        class="form-check-input"
        id="exampleCheck1"
        v-model="terms"
        required
      />
      <label class="form-check-label" for="exampleCheck1"
        >I have read the Terms and Conditions</label
      >
    </div>
    <br /><br />
    <div class="d-grid footer">
      <button class="btn btn-primary" type="button">Save & Next</button>
    </div>
  </form>
</template>

<script>
export default {
  data() {
    return {
      name: "",
      email: "",
      password: "",
      terms: false
    };
  },
};
</script>


<style>
form {
  background-color: white;
  margin: auto;
  padding: 20px 20px;
}

.bold {
  font-weight: bold;
}

.right {
  position: absolute;
  right: 0px;
  padding: 0px 30px;
}

.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  margin: auto;
  padding: 20px 20px;
  color: white;
  background-color: white;
}
</style>