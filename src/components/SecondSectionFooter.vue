<script>

export default {
    name: "SecondSectionFooter",

    components: {
    },
    data() {
        return {

        }
    }
}

</script>

<template>
    <section>
        <div class="customBox d-flex justify-content-between align-items-center">

            <div class="signUp">
                <button class="p-2 my-4">SIGN-UP NOW!</button>
            </div>

            <div class="social d-flex">
                <div class="me-3">FOLLOW US</div>
                <img class="me-3" src="../assets/footer-facebook.png">
                <img class="me-3" src="../assets/footer-twitter.png">
                <img class="me-3" src="../assets/footer-youtube.png">
                <img class="me-3" src="../assets/footer-pinterest.png">
                <img class="me-3" src="../assets/footer-periscope.png">
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    background-color: #303030;
}

button {
    color: white;
    border: 2px solid cornflowerblue;
    background-color: transparent;
}

.social>div {
    color: cornflowerblue;
    font-size: 20px;
    font-weight: bold;
}
</style>