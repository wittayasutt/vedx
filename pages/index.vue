<template>
  <section class="vedx">
    <cover />
    <slogan />
    <contact />
  </section>
</template>

<script>
  import Cover from '~/components/Cover.vue'
  import Slogan from '~/components/Slogan.vue'
  import Contact from '~/components/Contact.vue'

  export default {
  	components: {
  		Cover,
  		Slogan,
  		Contact
  	}
  }
</script>

<style lang="scss" scoped>
  section.vedx {
  }
</style>
