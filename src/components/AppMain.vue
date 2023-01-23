<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <main>

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

    a {
        color: white;

        &:hover {
            color: $dc_blue;
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