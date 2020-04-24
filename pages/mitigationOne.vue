<template>
  <div class="content">
    <div v-html="sanitizeInput(exampleTwoInput)"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      exampleTwoInput: '<h1>XSS Sanitized</h1><img src=x onerror=alert(\"XXS&nbsp;Success&nbsp;!!\")>',
    }
  },
  methods: {
    sanitizeInput: function(htmlContent){
      return this.$sanitize(htmlContent);
    }
  },
}
</script>

<style>

</style>