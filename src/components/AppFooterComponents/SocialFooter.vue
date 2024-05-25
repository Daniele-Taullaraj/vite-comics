<script>


export default {
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
    <div class="row m-0 d-flex align-items-center">
        <div class="col-2"></div>
        <div class="col-2">
            <button class="text-white p-2" id="sign-up"><span>SIGN-UP NOW</span></button>
        </div>
        <div class="col-3"></div>
        <div class="col-3 d-flex align-items-center">
            <span class="m-0 me-2" id="follow-us">FOLLOW US</span>
            <button class="social-btn border-0 mx-2"><img src="../../assets/img/footer-facebook.png" alt=""></button>
            <button class="social-btn border-0 mx-2"><img src="../../assets/img/footer-twitter.png" alt=""></button>
            <button class="social-btn border-0 mx-2"><img src="../../assets/img/footer-youtube.png" alt=""></button>
            <button class="social-btn border-0 mx-2"><img src="../../assets/img/footer-pinterest.png" alt=""></button>
            <button class="social-btn border-0 mx-2"><img src="../../assets/img/footer-periscope.png" alt=""></button>
        </div>
        <div class="col-2"></div>
    </div>
</template>

<style scoped>
.row {
    background-color: #303030;
    height: 15vh;
}

#sign-up {
    background-color: #303030;
    border: 2px solid #0282F9;
}

#sign-up span {
    font-size: 0.8rem;
}

#follow-us {
    color: #0282F9;
}

.social-btn {
    background-color: #303030;
}
</style>