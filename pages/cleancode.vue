<template>
 <div class=""> 
  <div class="d-flex judul col-12">
  <h3>Clean Code</h3>
  </div>
  <div class="d-flex image col-12">
  <img src="@/static/cleancode.png" alt="GIT" class="my-2" width="50%">  
  </div>
  <div class="d-block desc">
    <p>istilah untuk kode yang mudah dibaca, dipahami dan diubah oleh programmer</p> 
    <p>Karakteristik Clean Code</p>
    <ul>
      <li>Mudah dipahami</li>
      <li>Mudah dicari</li>
      <li>Singkat dan jelas</li>
      <li>Konsisten</li>
      <li>komentar yang spesfik</li>
    </ul>
    <p>Keep it so simple jangan membuat fungsi yang melakukan banyak tugas seperti mengeksekusi a, merubah b dan mengecek fungsi c</p>
  </div>    
 </div>
</template>

<script>
export default {
  name: 'cleancodeVue', 
}
</script>
<style scoped>
.landing {
  align-content: center;
  align-items: center;
}
</style>