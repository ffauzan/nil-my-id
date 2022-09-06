<template>
  <div class="grid h-screen place-items-center bg-gray-900">
    <h1 class="text-5xl font-mono font-bold">
      <span class="text-violet-400">var</span>
      <span
        class="bg-clip-text Pastel bg-gradient-to-r from-green-200 via-green-300 to-blue-500 background-animate text-transparent"
        >myId</span
      >
      <span class="text-green-400"><i>*string</i></span>
      <span class="text-cyan-400">=</span>
      <span
        class="bg-clip-text Pastel bg-gradient-to-r from-pink-300 via-purple-300 to-indigo-400 background-animate text-transparent"
        >nil</span
      >
    </h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
