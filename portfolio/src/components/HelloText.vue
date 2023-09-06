<template>
  <div class="hello">
    <h1>{{ txt }}</h1>
    <p>Este es el render de mi componente</p>
  </div>
</template>
<script>
export default {
  name: "HelloText",
  props: {
    txt: String,
  },
};
</script>
