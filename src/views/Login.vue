<template>
  <div class="container-fluid m-0 p-0">
    <login/>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from '@/components/Login.vue'

export default {
  name: 'HomeView',
  components: {
    Login
  }
}
</script>
