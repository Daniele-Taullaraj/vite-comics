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

    <div class="container-fluid p-0 m-0 ">
        <div class="row m-0 d-flex align-items-center">
            <div class="col-1 col-md-2"></div>
            <div class="col-2 col-md-1">
                <button class="text-white px-2 p-lg-2" id="sign-up"><span>SIGN-UP NOW</span></button>
            </div>
            <div class="col-1 col-sm-2 col-md-3"></div>
            <div class="col-7 col-sm-4 col-md-5 d-flex align-items-center">
                <span class="m-0 me-2" id="follow-us">FOLLOW US</span>
                <button class="social-btn border-0 mx-1 mx-xl-3"><img src="../../assets/img/footer-facebook.png"
                        alt=""></button>
                <button class="social-btn border-0 mx-1 mx-xl-3"><img src="../../assets/img/footer-twitter.png"
                        alt=""></button>
                <button class="social-btn border-0 mx-1 mx-xl-3"><img src="../../assets/img/footer-youtube.png"
                        alt=""></button>
                <button class="social-btn border-0 mx-1 mx-xl-3"><img src="../../assets/img/footer-pinterest.png"
                        alt=""></button>
                <button class="social-btn border-0 mx-1 mx-xl-3"><img src="../../assets/img/footer-periscope.png"
                        alt=""></button>
            </div>
            <div class="col-1 col-md-1"></div>
        </div>
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
    font-size: 100%;
    white-space: nowrap;
    line-height: 2rem;
}

#follow-us {
    color: #0282F9;
    font-size: 100%;
    white-space: nowrap;
}

.social-btn {
    background-color: #303030;
}

@media (max-width: 1200px) {

    .social-btn {
        transform: scale(0.8);
    }

    #sign-up span {
        font-size: 60%;
    }

    #follow-us {
        font-size: 60%;
    }
}
</style>