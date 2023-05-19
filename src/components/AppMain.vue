<script>

import InfoSectionMain from '../components/InfoSectionMain.vue'

export default {
    components: {
        name: "AppMain"
    },
    data() {
        return {

        }
    }
}

</script>

<template>
    <main class="bg-dark">
        <section class="customBox debug text-white">
            <p class="fs-3"> -- Content goes here -- </p>
        </section>

        <InfoSectionMain />
    </main>
</template>

<style scoped>
.debug {
    height: 150px;
    display: flex;
    align-items: center;
}
</style>