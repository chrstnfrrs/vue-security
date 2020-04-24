<template>
  <div class="content">
    <div v-html="exampleTwoInput"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      exampleTwoInput: '<h1>XSS Attack</h1><img src=x onerror=alert(\"XXS&nbsp;Success&nbsp;!!\")>',
    }
  },
}
</script>

<style>

</style>