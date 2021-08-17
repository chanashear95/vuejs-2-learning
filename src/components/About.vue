<template>
  <div>
    <h2>About</h2>
    <p>Hello {{ userName }}, this is an about page.</p>
  </div>
</template>

<script>
export default {
  name: "About",
  data() {
    return {
      userName: this.$route.params.name,
    };
  },
};
</script>
