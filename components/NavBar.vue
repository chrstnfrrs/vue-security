<template>
  <nav>
    <nuxt-link class="navLinks" to="/">Home</nuxt-link>
    <nuxt-link class="navLinks" to="/examples">Examples</nuxt-link>
    <nuxt-link class="navLinks" to="/mitigations">Mitigations</nuxt-link>
  </nav>
</template>

<script>
export default {

}
</script>

<style>
nav{
  height: 40px;
  padding: 0px 32px;
  display: flex;
  align-items: center;
  background-color: #101010;
}
.navLinks{
  font-size: 14px;
  margin-right: 12px;
  color: #e5e5e5;
  text-decoration: none;
}
</style>