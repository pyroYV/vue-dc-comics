<template>
    <header class="container-lg">
        <div class="row d-flex justfy-content-between">
            <div class="col-2">
                <img src="../assets/img/dc-logo.png" alt="DC Logo">
            </div>
            <div class="col-4"></div>
            <nav class="d-flex col-6">
                <ul>
                    <li v-for="(link, index) in headerNav" :key="index">
                        <a href="link.url">{{link.text}}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
    export default {
        data() {
            return {
                headerNav: [{
                        text: "Characters",
                        url: "#"
                    },
                    {
                        text: "Comics",
                        url: "#"
                    },
                    {
                        text: "Movies",
                        url: "#"
                    },
                    {
                        text: "TV",
                        url: "#"
                    },
                    {
                        text: "Games",
                        url: "#"
                    },
                    {
                        text: "Collectibles",
                        url: "#"
                    },
                    {
                        text: "Videos",
                        url: "#"
                    },
                    {
                        text: "Fans",
                        url: "#"
                    },
                    {
                        text: "News",
                        url: "#"
                    },
                    {
                        text: "Shop",
                        url: "#"
                    }
                ],
            }
        },
    }
</script>

<style lang='scss'>
    @import '../assets/style/variables.scss';
    @import '../assets/style/global.scss';

    header {


        img {
            height: 100px;
            padding: 5px;
        }

        nav {
            ul {
                display: flex;
                align-items: center;
                justify-content: center;
                margin: 0;

                li {
                    display: inline-block;
                    padding: 1rem;
                    height: 100px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    a{
                        text-decoration: none;
                    }
                    &:hover {
                        border-bottom: 4px solid $brand-color;
                    }

                }
            }
        }
    }
</style>