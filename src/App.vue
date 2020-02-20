<template>
  <div>
    <div class="bg-black text-white px-10 py-5 flex">
      <div class="w-1/2 mr-6">
        <span class="text-2xl">Logo</span>
      </div>
      <div id="menu" class="w-1/2">
        <ul class="inline-flex">
          <li class="">Home</li>
          <li class="mx-10">Articles</li>
          <li>About</li>
        </ul>
      </div>
    </div>
    <div class="mx-20 my-20">
      <Posts />
    </div>
  </div>
</template>

<script>
import Posts from './components/Posts'

export default {
  name: 'App',
  components: {
    Posts
  },
  data() {
    return {
      
    }
  }
}
</script>

<style>
  body {
    background: whitesmoke;
  }
</style>
