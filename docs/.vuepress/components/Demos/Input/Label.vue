<template lang="html">
  <div class="centerx labelx">
    <vs-input vs-label="Name" vs-placeholder="Placeholder" v-model="value1"/>
    <vs-input disabled="true" vs-label="Password" vs-placeholder="Disabled" v-model="value2"/>
  </div>
</template>

<script>
export default {
  data(){
    return {
      value1:'',
      value2:''
    }
  }
}
</script>

<style lang="stylus">
  .labelx
    .vs-input
      margin 10px;
</style>
