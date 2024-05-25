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
    <div>

        <SectionJumbo />
        <SectionSeries />
        <SectionMerch />

    </div>
</template>

<style scoped>
div {
    background-color: #1C1C1C;
}

#dafinire {
    background-color: red;
}
</style>
