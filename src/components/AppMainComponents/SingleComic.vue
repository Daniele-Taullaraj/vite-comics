<script>
export default {
    props: ["card"],
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
    <div class="col-2 pt-5">
        <img :src="card.thumb" alt="">
        <h6 class="pt-2 m-0">{{ card.series }}</h6>
    </div>
</template>


<style scoped>
img {
    width: 100%;
    height: 80%;
}
</style>