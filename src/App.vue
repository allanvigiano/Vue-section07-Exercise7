<template>
    <div class="container">

        <app-header></app-header>

        <div class="row">

            <app-servers></app-servers>

            <app-server-details></app-server-details>
        </div>

        <app-footer></app-footer>

    </div>
</template>

<script>
    import Header from './Header.vue';
    import Footer from './Footer.vue';
    import Servers from './Servers.vue';
    import ServerDetails from './ServerDetails.vue';

    export default {
        data: function () {
            return {

            };
        },
        components: {
            'app-header': Header,
            'app-footer': Footer,
            'app-servers': Servers,
            'app-server-details': ServerDetails,
        }
    }
</script>

<style>

</style>
