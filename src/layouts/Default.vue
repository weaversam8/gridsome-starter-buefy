<template>
  <div class="layout">
    <!-- This is the navigation bar component -->
    <Navbar />
    <!-- the section adds vertical padding to your content -->
    <section class="section">
      <!-- the container class adds horizontal padding when not on mobile -->
      <div class="container">
        <!-- the content class formats normal HTML elements underneath it to match Bulma's style -->
        <div class="content">
          <!-- Page content is added here -->
          <slot />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";

export default {
  components: {
    Navbar
  }
};
</script>

<style lang="scss"></style>
