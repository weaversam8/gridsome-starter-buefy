<template>
  <!-- we use the Bulma Navbar component here (https://buefy.org/documentation/navbar) -->
  <b-navbar wrapper-class="container">
    <template slot="brand">
      <b-navbar-item tag="g-link" to="/">
        <strong>{{ $static.metadata.siteName }}</strong>
      </b-navbar-item>
    </template>
    <template slot="start">
      <b-navbar-item tag="g-link" to="/">
        Home
      </b-navbar-item>
      <b-navbar-item tag="g-link" to="/about/">
        About
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {};
</script>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="scss"></style>
