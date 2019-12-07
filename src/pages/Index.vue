<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h1>Hello, world!</h1>

    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur
      excepturi labore tempore expedita, et iste tenetur suscipit explicabo!
      Dolores, aperiam non officia eos quod asperiores
    </p>

    <div class="buttons">
      <a
        class="button is-primary"
        href="https://gridsome.org/docs/"
        target="_blank"
        rel="noopener"
        >Gridsome Docs</a
      >
      <a
        class="button is-dark"
        href="https://github.com/gridsome/gridsome"
        target="_blank"
        rel="noopener"
      >
        <span class="icon">
          <i class="fab fa-github"></i>
        </span>
        <span>GitHub</span>
      </a>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!"
  }
};
</script>

<style lang="scss"></style>
