<template>
  <div id="app">
    <nav>
      <HeaderSet />
      <HeroSet />
    </nav>
    <router-view/>
  </div>
</template>

<script>
import HeaderSet from '@/components/HeaderSet.vue'
import HeroSet from '@/components/HeroSet.vue'
export default {
  components: {
    HeaderSet,
    HeroSet
  }
}
</script>

