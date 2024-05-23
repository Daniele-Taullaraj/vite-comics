<script>
import AppSectionLinkFooter from './AppFooterComponents/AppSectionLinkFooter.vue';
import AppSectionSocialFooter from './AppFooterComponents/AppSectionSocialFooter.vue';


export default {
    components: {
        AppSectionLinkFooter,
        AppSectionSocialFooter
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
    <footer>
        <AppSectionLinkFooter />
        <AppSectionSocialFooter />
    </footer>
</template>

<style scoped></style>
