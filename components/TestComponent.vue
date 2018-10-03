<template>
  <h1>hello</h1>
</template>


<script>
export default {
  methods: {
    render (createElement) {
      return createElement('h1', 'Test Component')
    }
  }
}
</script>
