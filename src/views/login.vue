<template>
  <div class="123">123</div>
</template>

<script>
import { ssrContextKey } from '@vue/runtime-core'
export default {
  create(){
    console.log(this.$store.state.count,'0')
    this.$store.commit("increment")
    console.log(this.$store.state.count,'1')

  }
}


</script>

<style>

</style>