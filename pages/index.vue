<template>
  <section>
    <b-navbar type="dark" style="z-index: 100;" absolute>
      <b-navbar-brand href="#">
        <img src="Logo horizontal.png" alt="Logo Studio 26" height="60">
      </b-navbar-brand>
    </b-navbar>
    <b-container fluid class="px-0 py-0">
      <sectionOne />
      <sectionTwo />
    </b-container>
    <sectionFooter />
  </section>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
