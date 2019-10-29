<template>
  <div>
    <h1 class="page-title">{{ page.title }}</h1>
    <div class="page-content">
      <slot />
    </div>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  props: ['page']
})
</script>