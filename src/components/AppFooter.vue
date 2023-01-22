<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="footer-nav">

                    <div class="footer-col">
                        <h2>DC COMICS</h2>
                        <ul>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Comics</a></li>
                            <li><a href="">Movies</a></li>
                            <li><a href="">Tv</a></li>
                            <li><a href="">Games</a></li>
                            <li><a href="">Video</a></li>
                            <li><a href="">News</a></li>
                        </ul>
                        <h2>SHOP</h2>
                        <ul>
                            <li><a href="">Shop DC</a></li>
                            <li><a href="">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h2>DC</h2>
                        <ul>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h2>SITES</h2>
                        <ul>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                        </ul>
                    </div>

                </div>
                <figure>
                    <img src="../assets-vue-dc-comics-1/img/dc-logo-bg.png" alt="">
                </figure>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container">
                <div class="footer-sign">
                    <a href="">
                        <h2>SIGN-UP NOW!</h2>
                    </a>
                </div>
                <div class="footer-social">
                    <ul>
                        <li><a href="">
                                <h2>FOLLOW US</h2>
                            </a></li>
                        <li><a href=""><img src="../assets-vue-dc-comics-1/img/footer-facebook.png" alt=""></a></li>
                        <li><a href=""><img src="../assets-vue-dc-comics-1/img/footer-twitter.png" alt=""></a></li>
                        <li><a href=""><img src="../assets-vue-dc-comics-1/img/footer-youtube.png" alt=""></a></li>
                        <li><a href=""><img src="../assets-vue-dc-comics-1/img/footer-pinterest.png" alt=""></a></li>
                        <li><a href=""><img src="../assets-vue-dc-comics-1/img/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scope>
@use '../assets/scss/partials/_variables' as *;

footer {
    h2 {
        color: white;
    }

    ul li {
        margin: 1rem 0 1rem;
    }

    a {
        color: grey;

        &:hover {
            color: white;
        }
    }

    .footer-top {
        background-image: url('../assets-vue-dc-comics-1/img/footer-bg.jpg');
        height: 480px;

        .footer-nav {
            padding: 2rem 0 2rem;
            display: flex;


            .footer-col {
                margin-right: 2rem;

                h2 {
                    margin-bottom: 1.5rem;
                }

                ul {
                    margin-bottom: 2rem;
                }
            }

        }

        .container {
            justify-content: space-between;
        }


        figure img {
            height: 85%
        }


    }

    .footer-bottom {
        display: flex;

        height: 150px;
        background-color: rgb(45, 45, 45);

        .container {
            justify-content: space-between;
            align-items: center;
        }

        .footer-sign {
            h2 {
                border: 2px solid $dc_blue;
                padding: 1rem;
            }
        }

        .footer-social {
            ul {
                display: flex;
                align-items: center;

                li {
                    margin: 1rem;

                    h2 {
                        color: $dc_blue;
                    }
                }
            }
        }
    }

}
</style>