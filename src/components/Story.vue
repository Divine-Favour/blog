<template>
  <div>
    <button @click="back">Back</button>
    <h2>{{details.title}}</h2>
  </div>
</template>

<script>
export default {
  name: 'Story',
  props: [
    'post'
  ],
  data() {
    return {
      details:""
    }
  },
  methods: {
    getDetails() {
      this.details = this.post
    },
    back(){
      window.location.reload()
    }
  },
  mounted() {
    this.getDetails()
  }
}
</script>

<style scoped>

</style>
