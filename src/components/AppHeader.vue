<script>
export default {
    data() {
        return {
            data: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]
        }
    }
}
</script>

<template>
    <header>
        <div class="container">
            <figure>
                <a href="">
                    <img src="../assets-vue-dc-comics-1/img/dc-logo.png" alt="">
                </a>
            </figure>
            <nav>
                <ul v-for="title in data" :key="title.text">
                    <li><a href="">{{ title.text }}</a></li>

                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
.container {
    display: flex;
    justify-content: space-around;
    align-items: center;

    padding: 1rem;
    background-color: white;

    nav {
        display: flex;
        flex-direction: row;

        li {
            color: black;

            a {
                color: black;

                &:hover {
                    color: blue;
                    border-bottom: 5px solid blue;
                    padding-bottom: 3.5rem;
                }
            }
        }
    }
}
</style>