<script>

export default {
    name: "CurrentSeries",
    props: [
        "cards"
    ],
    data() {
        return {
            props: {
                thumb: String,
                price: String,
                series: String,
                type: String

            }
        }
    }
}

</script>

<template>
    <h4 class="py-1 px-3 text-white bg-primary position-absolute top-0 start-0 translate-middle ms-5">CURRENT SERIES</h4>

    <div v-for="card in cards" class="col-2 p-2">
        <img :src="card.thumb">
        <h6>{{ card.series }}</h6>
    </div>

    <button class="align-self-center py-1 px-5 text-white bg-primary mx-auto mb-4"> Load More </button>
</template>

<style scoped>
img {
    width: 100%;
    aspect-ratio: 1/1;
}

h6 {
    margin-top: 1rem;
    margin-bottom: 3rem;
    font-weight: bold;
}
</style>