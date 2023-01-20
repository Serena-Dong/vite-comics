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
        <div class="contents">
            <div class="container">
                <h1>Contents goes here</h1>
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

<style lang="scss" scope>
main {

    color: white;

    .contents {
        background-color: rgb(41, 41, 41);
        height: 150px;

        display: flex;
        align-items: center;

    }

    nav {
        background-color: #0d7bec;

        ul {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: space-around;

            height: 180px;

            a {
                color: white;
            }
        }

    }

}
</style>