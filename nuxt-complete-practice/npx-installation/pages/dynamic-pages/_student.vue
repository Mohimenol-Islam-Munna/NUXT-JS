<template>
  <h2>Student Dynamic Page :: {{ name }}</h2>
</template>

<script>
export default {
  data() {
    return {
      name: this.$route.params.student,
    };
  },
};
</script>
