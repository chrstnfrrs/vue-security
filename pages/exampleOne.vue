<template>
  <div class="content">
    <p>{{exampleOneInput}}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      exampleOneInput: '<img src=x onerror=alert(\"XXS&nbsp;Success&nbsp;!!\")>',
    }
  },
}
</script>

<style>

</style>