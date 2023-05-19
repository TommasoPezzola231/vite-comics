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
            <template v-for="element in Elements">
                <div class="d-flex align-items-center p-3 m-2">
                    <div>
                        <img src={{ element.img }} alt="">
                    </div>
                    <div>
                        <p>{{ element.text }}</p>
                    </div>
                </div>
            </template>
        </div>
    </section>
</template>

<style scoped></style>