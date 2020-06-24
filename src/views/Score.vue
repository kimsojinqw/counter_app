<template>
  <div class="score">
    <h1>Score</h1>
    <p>{{ count }}</p>
  </div>
</template>


<script>
export default{
  computed:{
    count(){
      return this.$store.getters.count
    }
  }
}
</script>