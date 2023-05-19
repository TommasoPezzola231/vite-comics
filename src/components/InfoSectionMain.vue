<script>

export default {
    name: "InfoSectionMain",

    components: {
    },
    data() {
        return {
            Elements: [
                {
                    img: "../assets/buy-comics-digital-comics.png",
                    text: "Digital Comics"
                },
                {
                    img: "../assets/buy-comics-merchandise.png",
                    text: "DC Merchandise"
                },
                {
                    img: "../assets/buy-comics-subscriptions.png",
                    text: "Subscription"
                },
                {
                    img: "../assets/buy-comics-shop-locator.png",
                    text: "Comic Shop Locator"
                },
                {
                    img: "../assets/buy-dc-power-visa.svg",
                    text: "DC Power Visa"
                }
            ]
        }
    }
}

</script>

<template>
    <section class="bg-primary text-white">
        <div class="customBox d-flex justify-content-around align-items-center">

            <div class="d-flex align-items-center p-3 m-2">
                <div>
                    <img src="../assets/buy-comics-digital-comics.png">
                </div>
                <div class="align-self-center ms-3">
                    <p>Digital Comics</p>
                </div>
            </div>

            <div class="d-flex align-items-center p-3 m-2">
                <div>
                    <img src="../assets/buy-comics-merchandise.png">
                </div>
                <div class="align-self-center ms-3">
                    <p>DC Merchandise</p>
                </div>
            </div>

            <div class="d-flex align-items-center p-3 m-2">
                <div>
                    <img src="../assets/buy-comics-subscriptions.png">
                </div>
                <div class="align-self-center ms-3">
                    <p>Subscription</p>
                </div>
            </div>

            <div class="d-flex align-items-center p-3 mx-2 my-5">
                <div>
                    <img src="../assets/buy-comics-shop-locator.png">
                </div>
                <div class="align-self-center ms-3">
                    <p>Comic Shop Locator</p>
                </div>
            </div>

            <div class="d-flex align-items-center p-3 m-2">
                <div>
                    <img src="../assets/buy-dc-power-visa.svg">
                </div>
                <div class="align-self-center ms-3">
                    <p>DC Power Visa</p>
                </div>
            </div>

        </div>
    </section>
</template>

<style scoped>
img {
    width: 50px;
}

p {
    margin-bottom: 0;
}
</style>