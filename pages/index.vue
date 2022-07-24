<template>
 <div class="landing">
   <b-jumbotron bg-variant="dark" header="Weekly Task Alterra" lead="Tugas Weekly 1 dan 2" text-variant="white">
    <p>For more information visit website</p>
    <b-button to="/satu" pill variant="primary">Weekly Task 1</b-button>
  <b-button to="/dua" pill variant="primary">Weekly Task 2</b-button>
  </b-jumbotron> 
 </div>
</template>

<script>
export default {
  name: 'IndexPage', 
  layout: 'blank'
}
</script>
<style scoped>
.landing {
  align-content: center;
  align-items: center;
}
</style>