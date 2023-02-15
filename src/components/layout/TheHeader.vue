<template>
  <header>
    <h1>More on Vue Components</h1>
    <!-- <HeaderSearch /> -->
  </header>
</template>
<script>
// import HeaderSearch from './components/HeaderSearch.vue';
  export default {
    components:{
      // HeaderSearch
    }
  }
</script>

<style scoped>
  header {
    width: 100%;
    height: 5rem;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #14005e;
    font-family:monospace;
  }

  header h1 {
    color: white;
    margin: 0;
  }
</style>