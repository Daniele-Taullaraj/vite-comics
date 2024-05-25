<script>
export default {
    data() {
        return {
            listMerc: [
                {
                    linkname: "DIGITAL COMICS",
                    src: "/src/assets/img/buy-comics-digital-comics.png"
                },
                {
                    linkname: "DC MERCHANDISE",
                    src: "/src/assets/img/buy-comics-merchandise.png"
                },
                {
                    linkname: "SUBSCRIPTION",
                    src: "/src/assets/img/buy-comics-subscriptions.png"
                },
                {
                    linkname: "COMIC SHOP LOCATOR",
                    src: "/src/assets/img/buy-comics-shop-locator.png"
                },
                {
                    linkname: "DC POWER VISA",
                    src: "/src/assets/img/buy-dc-power-visa.svg"
                },
            ]
        }
    },
    methods: {

    },
    mounted() {
    }

}
</script>

<template>
    <div class="row m-0">
        <div class="col-1 col-md-2"></div>

        <div class="col p-0 ">
            <div class="row d-flex justify-content-center p-0 m-0">


                <a v-for="element, index in listMerc" href="ss"
                    :class="[index == listMerc.length - 1 ? 'last-item' : '', 'col-6 col-sm-3 col-lg-2 d-flex align-items-center justify-content-center text-decoration-none text-white mx-3 p-0']">
                    <img :src="element.src" alt="immagine">
                    <span class="ms-2 text-nowrap">{{ element.linkname }}</span>
                </a>

            </div>
        </div>

        <div class="col-1 col-md-2"></div>
    </div>
</template>


<style scoped>
.row {
    background-color: #0282F9;
}

a img {
    height: 40%;
}

.last-item img {
    transform: scale(0.7);
}

a span {
    font-size: 0.6rem;
}

a:hover {
    cursor: pointer;
}

@media (min-width: 992px) and (max-width:1400px) {

    a {
        width: calc(100% / 7);
        transform: scale(0.8);
    }

}
</style>