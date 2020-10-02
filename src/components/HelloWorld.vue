<template>
  <div class="hello" :color="colorHello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    colorHello: String
  }
};
</script>

<style scoped></style>
