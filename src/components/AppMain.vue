<script>
import SectionMerch from './AppMainComponents/SectionMerch.vue';
import SectionJumbo from './AppMainComponents/SectionJumbo.vue';
import SectionSeries from './AppMainComponents/SectionSeries.vue';




export default {
    components: {
        SectionMerch,
        SectionJumbo,
        SectionSeries,
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

        <SectionJumbo />
        <SectionSeries />
        <SectionMerch />

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
