<template>
  <div class="content">
    <a :href="exampleThreeInput">Click Me</a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      exampleThreeInput: 'javascript:alert(\'XXS&nbsp;Success.\');window.location.replace(\'/\');',
    }
  }
}
</script>