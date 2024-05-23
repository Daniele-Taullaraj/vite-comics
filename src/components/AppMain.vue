<script>
import AppSectionMerch from './AppMainComponents/AppSectionMerch.vue';

export default {
    components: {
        AppSectionMerch,
    },
    data() {
        return {
        }
    },
    methods: {

    },
    mounted() {
    }

}
</script>

<template>
    <main>
        <div class="container-fluid p-0 ">

            <div class="row py-5 m-0">
                <div class="col-2"></div>
                <div class="col" id="dafinire"> CONTENT GOES HERE </div>
                <div class="col-2"></div>
            </div>

            <AppSectionMerch />

        </div>
    </main>
</template>

<style scoped>
main {
    background-color: #1C1C1C;
    color: white;
}

#dafinire {
    background-color: red;
}
</style>
