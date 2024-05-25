<script>


export default {
    data() {
        return {
            linkFooter: [
                {
                    title: "DC COMICS",
                    links: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"]
                },
                {
                    title: "SHOP",
                    links: ["Shop DC", "Shop DC Collectibles"]
                },
                {
                    title: "DC",
                    links: ["Terms of Use", "Privacy policy(New)", "Ad Choices", "Advertising", "Jobs", "Subscription", "Talent Workshop", "CPSC Certificates", "Ratings", "Shopo Help", "Contact Us"]
                },
                {
                    title: "SITES",
                    links: ["DC", "MAD Magazines", "DC Kids", "DC Universe", "DC Power Visa"]
                }
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
    <div id="bg-footer" class="position-relative w-100 ">
        <div id="dc-logo" class="position-absolute top-0 h-100 w-100 "></div>
        <div class="row m-0">
            <div class="col-1 col-md-2"></div>
            <div class="col-11 col-sm-10 col-md-6 col-xl-4">
                <div class="row py-5">


                    <div class="col-4">
                        <div v-for="element, index in linkFooter">
                            <h5 v-if="index == 0 || index == 1" class="pt-2 text-white">{{ element.title }}</h5>
                            <a v-for="link in element.links" v-if="index == 0 || index == 1"
                                href="https://www.google.com" class="d-block text-nowrap">{{ link }}</a>
                        </div>
                    </div>

                    <div class="col-4">
                        <div v-for="element, index in linkFooter">
                            <h5 v-if="index == 2" class="pt-2 text-white">{{ element.title }}</h5>
                            <a v-for="link in element.links" v-if="index == 2" href="https://www.google.com"
                                class="d-block text-nowrap">{{ link }}</a>
                        </div>
                    </div>

                    <div class="col-4">
                        <div v-for="element, index in linkFooter">
                            <h5 v-if="index == linkFooter.length - 1" class="pt-2 text-white">{{ element.title }}</h5>
                            <a v-for="link in element.links" v-if="index == linkFooter.length - 1"
                                href="https://www.google.com" class="d-block text-nowrap">{{ link }}</a>
                        </div>
                    </div>


                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
#bg-footer {
    background-image: url(../../assets/img/footer-bg.jpg);
}

#dc-logo {
    background-image: url(../../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position-x: 80%;
    background-position-y: 50%;
    pointer-events: none;
}

a {
    text-decoration: transparent;
    color: #737680;
    font-size: 0.8rem;
}

a:hover {
    cursor: pointer;
    text-decoration: underline;
}
</style>