<script>
import AppContents from './AppContents.vue'
export default {
    data() {
        return {

        }
    },
    components: { AppContents }
}
</script>

<template>
    <main>

        <div class="contents">
            <div class="container">
                <div class="row">

                    <AppContents></AppContents>

                </div>
            </div>
        </div>


        <nav>
            <div class="container">
                <ul>
                    <li><a href="">DIGITAL COMICS</a></li>
                    <li><a href="">DC MERCHANDISE</a></li>
                    <li><a href="">SUBSCRIPTION</a></li>
                    <li><a href="">COMIC SHOP LOCATOR</a></li>
                    <li><a href="">DC POWER VISA</a></li>
                </ul>
            </div>
        </nav>
    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/_variables' as *;

main {

    color: white;

    .contents {
        background-color: rgb(41, 41, 41);
        min-height: 150px;
        padding: 3rem;

        display: flex;
        align-items: center;


        .row {
            display: flex;
            flex-wrap: wrap;
            gap: 2%;

        }



    }

    nav {
        background-color: $dc_blue;

        ul,
        .container {
            display: flex;
            align-items: center;
            justify-content: space-around;

            height: 180px;

        }

    }

}
</style>