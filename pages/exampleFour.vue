<template>
  <div class="content">
    <a :style="exampleThreeInput">Click Me</a>
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