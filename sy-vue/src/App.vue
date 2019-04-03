<template>
  <div id="app">
    <div @clicl="sclick">{{message}}</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data(){
    return{
      message:'haha'
    }
  },
  methods:{
    sclick(){
      this.message="jeje"
    }
  }
}
</script>

<style>

</style>
