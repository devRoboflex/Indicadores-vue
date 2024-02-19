<template class="body">

        <router-view />

    <br><br><br>
    <FooterComponent></FooterComponent>
</template>

<script>
import FooterComponent from "@/components/footer/FooterComponent"
export default {
    data() {
        return {

        }

    },

    components: {
        FooterComponent: FooterComponent,
    }
}
</script>

<style>
body {
    font-family: 'montserrat', sans-serif;
    background-color: rgba(234, 234, 234, 1) !important;

}

.menu {
    z-index: 9999999;
    position: fixed;
    width: 100%;
    margin-top: 0;
}
.views {
    margin-top: 1rem;
}

.footer {
    position: absolute;
}


</style>