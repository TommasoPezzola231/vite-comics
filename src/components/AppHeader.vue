<script>

export default {
    name: "AppHeader",

    components: {
    },
    data() {
        return {
            Elements: [
                { text: "Characters" },
                { text: "Comics" },
                { text: "Movies" },
                { text: "Tv" },
                { text: "Games" },
                { text: "Collectibles" },
                { text: "Videos" },
                { text: "Fans" },
                { text: "News" },
                { text: "Shop" }

            ]
        }

    }
}

</script>

<template>
    <header class="customBox ">
        <nav class=" d-flex justify-content-between align-items-center h-100">
            <div class="logo">
                <a><img class="align-self-center" src="../assets/dc-logo.png" alt=""></a>
            </div>
            <ul class="navbar-nav d-flex flex-row align-items-center">
                <li v-for="element in Elements" class="nav-item mx-2">{{ element.text }}</li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
header {
    height: 120px;
}

img {
    height: 80px;
}
</style>