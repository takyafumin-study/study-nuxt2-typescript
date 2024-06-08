<template>
  <section class="container">
    <div>
      <NuxtLogo />
      <h1 class="title">test</h1>
      <h2 class="subtitle">My awesome Nuxt.js project</h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
        <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'

@Component({
  components: {
    NuxtLogo: () => import('~/components/NuxtLogo.vue'),
  },
})
export default class Index extends Vue {}
</script>
