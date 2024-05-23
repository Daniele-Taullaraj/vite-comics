<script>
export default {
    data() {
        return {
            linkHeader: [
                "CHARACTER",
                "COMICS",
                "MOVIES",
                "TV",
                "GAMES",
                "COLLECTIBLES",
                "VIDEOS",
                "FANS",
                "NEWS",
                "SHOP"
            ],
        }
    },
    methods: {

    },
    mounted() {
    }

}


</script>

<template>
    <header>
        <div class="container-fluid p-0">
            <div class="row m-0">
                <div class="col-2"></div>
                <div class="col-1 h-100 d-flex justify-content-center align-items-center">
                    <img src="../assets/img/dc-logo.png" alt="logo dc" class="h-75">
                </div>
                <div class="col-2"></div>
                <div class="col-5 h-100 p-0 d-flex">
                    <a v-for="link in linkHeader" href="https://www.google.com"
                        class="mx-2 fw-bold text-decoration-none d-flex align-items-center ">{{ link }}</a>
                </div>
                <div class="col-2"></div>
            </div>
        </div>
    </header>
</template>

<style scoped>
.row {
    background-color: white;
    height: 15vh;
}

.col-5 a {
    font-size: 0.8rem;
    border-bottom: 5px solid transparent;
    color: #737680;
}

.col-5 a:hover {
    color: #0282F9;
    border-bottom: 5px solid #0282F9;
}
</style>
