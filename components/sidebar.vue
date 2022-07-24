<template>
                    <div class="dark sidebar m-0 pl1 w100">
                    <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                        <nuxt-link to="/git" class="text-white">Git</nuxt-link>
                    </div>
                <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/uiux" class="text-white">UI/UX</nuxt-link>
                    </div>
                <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/figma" class="text-white">Figma</nuxt-link>
                    </div>
                    <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/html" class="text-white">HTML</nuxt-link>
                    </div>
                    <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/css" class="text-white">CSS</nuxt-link>
                    </div>
                    <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/bootstrap" class="text-white">Bootstrap</nuxt-link>
                    </div>  
                    <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/js" class="text-white">JavaScript</nuxt-link>
                    </div>      
                <div class="d-flex justify-content-between align-items-center border-bottom list-group-item dark text-white p-3 ">
                    <nuxt-link to="/cleancode" class="text-white">Clean Code</nuxt-link>
                    </div>
                </div>
                
</template>
<script>
export default {
    name: 'sidebarVue'
}
</script>
<style scoped>
.unguprimary {
    background-color: #50266A;
}
.ungusecondary {
    background-color: #794B93;
}
.sidebar {
   min-height: 100vh;
}
.pl1 {
    padding-left: 10px;
}
.ml1 {
    margin-left: 10px;
}
.w100 {
    width: 100%;
}
.w10px {
    width: 10px;
}
.svgmx {
margin-left: 2px;
margin-right: 10px;
color: white;
}
.iconmx {
    margin-left: 0px;
    
}
.dark {
    background-color: #343a41;
}
</style>