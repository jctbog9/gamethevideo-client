<template>
  <div>
    <DesktopHeader />
    <Nuxt />
  </div>
</template>

<script>
import DesktopHeader from '../components/DesktopHeader'

export default {
  components: {
    DesktopHeader
  }
}
</script>

<style>
body {
  margin: 0px;
  padding: 0px;
}
</style>
