<script>

import SecondSectionFooter from './SecondSectionFooter.vue'

export default {
    name: "AppFooter",

    components: {
        SecondSectionFooter
    },
    data() {
        return {

        }
    }
}

</script>

<template>
    <footer>

        <section class="customBox d-flex justify-content-between">
            <div class="footer d-flex">

                <div class="col mx-4 d-flex flex-column">
                    <h6>DC Comics</h6>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <h6>Shop</h6>
                    <a>Prova</a>
                    <a>Prova</a>
                </div>

                <div class="col mx-4 d-flex flex-column">
                    <h6>DC</h6>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                </div>

                <div class="col mx-4 d-flex flex-column">
                    <h6>Sites</h6>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                    <a>Prova</a>
                </div>
            </div>
            <div class="logoFooter align-self-center h-100">
                <img src="../assets/dc-logo-bg.png">
            </div>
        </section>

        <SecondSectionFooter />

    </footer>
</template>

<style scoped>
footer {
    background-image: url(../assets/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 400px;
}

h6 {
    color: white;
    margin-top: 2rem;
    margin-bottom: 1rem;
}

a {
    color: gray !important;
}

img {
    height: 400px
}
</style>