<template>
  <div class="container" />
</template>

<script>
export default {
  computed: {
    blogPosts () {
      return this.$store.state.blogPosts
    }
  }
}
</script>
