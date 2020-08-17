<template>
  <section class="container">
    <div>
      <Toolbar/>
      <nuxt/>
    </div>
  </section>
</template>

<script>
import Toolbar from '@/components/Toolbar.vue';
export default {
  components: {
    Toolbar
  }
}
</script>
