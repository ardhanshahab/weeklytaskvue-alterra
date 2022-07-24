<template>
 <div class="container-fluid"> 
  <b-tabs content-class="mt-3">
    <b-tab title="Git" active>
      <img src="@/static/git.png" alt="GIT" class="my-2" width="50%">
      </b-tab>
    <b-tab title="UI/UX">
      <div class="d-flex col-12">
        <img src="@/static/uiux.png" alt="UIUX" class="my-2" width="50%">
        </div>
      <div class="d-flex col-6">
        <b-button href="https://docs.google.com/document/d/1LGbc4Hkq9HOIx6djMApjJy25nPxZ48YGdkzl41CRNO0/edit?usp=sharing">Tugas</b-button>
      </div>
      </b-tab>
    <b-tab title="Figma">
      <div class="d-flex col-12">
      <img src="@/static/figma.png" alt="FIGMA" class="my-2" width="50%">      
      </div>
      <div class="d-flex col-6">
      <b-button href="https://www.figma.com/file/rnRFXj7IBnwBANVr8UU8un/tugas-figma?node-id=0%3A1">Tugas</b-button>
      </div>
      </b-tab>
    <b-tab title="HTML">
      <div class="d-flex col-12">
        <img src="@/static/html.png" alt="HTML" class="my-2" width="50%">      
      </div><div class="d-flex col-6">
      <b-button href="https://github.com/ardhanshahab/vue_muhamad-ardhan-hadaina/tree/main/5_HTML/Praktikum">Tugas</b-button>
      </div>
      </b-tab>

      <b-tab title="CSS">
      <div class="d-flex col-12">
        <img src="@/static/css.png" alt="HTML" class="my-2" width="50%">
      </div>
      <div class="d-flex col-6">
        <b-button href="https://github.com/ardhanshahab/vue_muhamad-ardhan-hadaina/tree/main/6_CSS">Tugas</b-button>
      </div>
      </b-tab>

    <b-tab title="Bootstrap">
      <div class="d-flex col-12">
        <img src="@/static/bootstrap.png" alt="HTML" class="my-2" width="50%">
      </div>
      <div class="d-flex col-6">
        <b-button href="https://github.com/ardhanshahab/vue_muhamad-ardhan-hadaina/tree/main/7_Bootstrap/Praktikum">Tugas</b-button>
      </div>
      </b-tab>

      <b-tab title="JavaScript">
      <div class="d-flex col-12">
        <img src="@/static/js.png" alt="HTML" class="my-2" width="50%">
      </div>
      <div class="d-flex col-6">
        <b-button href="https://github.com/ardhanshahab/vue_muhamad-ardhan-hadaina/tree/main/8_Javascript%20Refresment">Tugas</b-button>
      </div>
      </b-tab>
    <b-tab title="CleanCode">
      <div class="d-flex col-12">
        <img src="@/static/cleancode.png" alt="HTML" class="my-2" width="50%">
      </div>
      <div class="d-flex col-6">
        <b-button href="https://github.com/ardhanshahab/vue_muhamad-ardhan-hadaina/tree/main/9_CleanCode/Praktikum">Tugas</b-button>
      </div>
      </b-tab>
    
  </b-tabs>
 </div>
</template>

<script>
export default {
  name: 'IndexSatu', 
  layout: 'blank'
}
</script>
<style scoped>
.landing {
  align-content: center;
  align-items: center;
}
</style>