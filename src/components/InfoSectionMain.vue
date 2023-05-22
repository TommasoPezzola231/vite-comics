<script>

export default {
    name: "InfoSectionMain",
    props: [
        "Elements"
    ],
    components: {
    },
    data() {
        return {

        }
    }
}

</script>

<template>
    <section class="bg-primary text-white">
        <div class="customBox d-flex justify-content-around align-items-center">

            <div v-for="Element in Elements" class="d-flex align-items-center p-3 m-2">
                <div>
                    <img :src="Element.img">
                </div>
                <div class="align-self-center ms-3">
                    <p>{{ Element.text }}</p>
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