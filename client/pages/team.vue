<template>
  <div>
    <h1>Super Team</h1>
    <section class="container mx-auto flex flex-wrap justify-center gap-4">
      <Card v-for="member in members" :key="member.id" :member="member" />
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      members: [
        {
          name: 'Andrea',
          image: '/assets/andrea-pic.jpg',
          bio: 'Andrea is a cool person, apparently.',
        },
        {
          name: 'Anthony',
          image: '/assets/anthony-pic.jpg',
          bio: 'Super duper cool Anth.',
        },
        {
          name: 'Italo',
          image: '/assets/italo-pic.jpg',
          bio: 'Italo! Italo! Italo!',
        },
      ],
    }
  },
}
</script>

<style>
figcaption {
  @apply text-center text-lg;
}
</style>