<template>
  <a :href="link">{{ name }}</a>
</template>

<script>
export default {
  name: "VButton",
  props: {
    name: String,
    link: String
  }
}
</script>