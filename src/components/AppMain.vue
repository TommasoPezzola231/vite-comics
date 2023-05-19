<script>

import InfoSectionMain from './InfoSectionMain.vue'

export default {
    name: "AppMain",
    components: {
        InfoSectionMain
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