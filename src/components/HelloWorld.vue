<template>
  <div>hello, {{name}} !</div>
</template>
<script>
export default {
  name: 'helloWorld',
  props: {
    name: {
      type: String,
      default: ''
    }
  }
}
</script>