<template>
  <section class="container">
    <p>{{ message }}</p>
    <hr>
    <h1>Top Page</h1>
    <router-link to="/mypage">My Page</router-link>
  </section>
</template>

<script>
export default {
  data() {
    return {
      message:"Hello World!"
    }
  }
}
</script>

