<template>
  <h1>{{ text }}</h1>
  <p>
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad mollitia minima
    at quia a, earum eum odit blanditiis nam qui nobis incidunt sed, magni
    corporis, dolorum numquam molestias porro vero.
  </p>
</template>

<script>
export default {
  data() {
    return {
      text: "Hola Vue",
    };
  },
};
</script>
<style>
p {
  color: red;
}
</style>
