<template>
  <footer>
    <p>{{ info }}</p>
  </footer>
</template>

<script>
export default {
  props: {
    info: {
      type: String,
      required: true,
    },
  },
}
</script>

<style lang="scss" scoped></style>
