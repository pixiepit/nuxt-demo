<template>
  <figure>
    <nuxt-img :src="member.image" :alt="member.name" width="300" />
    <figcaption>{{ member.bio }}</figcaption>
  </figure>
</template>

<script>
export default {
  props: ['member'],
}
</script> 