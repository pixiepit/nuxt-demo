<template>
  <figure>
    <nuxt-img :src="image" :alt="name" width="300" />
    <figcaption>{{ bio }}</figcaption>
  </figure>
</template>

<script>
export default {
  props: {
    image: {
      type: String,
      required: true
    },
    name: {
      type: String,
      required: true
    },
    bio: {
      type: String,
      required: true
    }
  }
}
</script> 