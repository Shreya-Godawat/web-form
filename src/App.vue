<template>
  <SignupForm1 />
  <SignupForm2 />
  <SignupForm3 />
  <SignupForm4 />
  <ActivityCreation />
  <SigninForm />
</template>

<script>
import SignupForm1 from './components/SignupForm.vue'
import SignupForm2 from './components/SignupForm2.vue'
import SignupForm3 from './components/SignupForm3.vue'
import SignupForm4 from './components/SignupForm4.vue'
import ActivityCreation from './components/ActivityCreation.vue'
import SigninForm from './components/SigninForm.vue'

export default {
  name: 'App',
  components: {
    SignupForm1,
    SignupForm2,
    SignupForm3,
    SignupForm4,
    ActivityCreation,
    SigninForm
  }
}
</script>
