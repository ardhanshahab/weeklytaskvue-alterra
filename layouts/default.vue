<template>
<div>
        <Navbar/>
        <div class="row">
        <div class="col-3 p-0">
        <Sidebar/>
        </div>
        <div class="col-9 container-fluid mt-2">
            <Nuxt/>
        </div>
        </div>
    </div>
</template>
<script>
import Sidebar from '~/components/sidebar.vue';
import Navbar from '~/components/navbar.vue';
export default {
    name: "defaultLayout",
    components: { Sidebar, Navbar }
}
</script>