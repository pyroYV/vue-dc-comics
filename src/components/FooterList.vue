<template>
    <div id="wrapper">
        <div class="category" v-for="(category, index) in categories" :key="index">
            <h3>{{category.text}}</h3>
            <ul class="">
                <li v-for="(element, i) in category.items" :key="i">
                    <a :href="element.url">{{element.text}}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterList',
        data() {
            return {
                categories: [{
                        text: "Dc Comics",
                        items: [{
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
                                text: "Videos",
                                url: "#"
                            },
                            {
                                text: "News",
                                url: "#"
                            }
                        ]
                    },
                    {
                        text: "Shop",
                        items: [{
                                text: "Shop DC",
                                url: "#"
                            },
                            {
                                text: "Shop DC Collectibles",
                                url: "#"
                            }
                        ]
                    },
                    {
                        text: "DC",
                        items: [{
                                text: "Terms Of Use",
                                url: "#"
                            },
                            {
                                text: "Privacy policy (New)",
                                url: "#"
                            },
                            {
                                text: "Ad Choices",
                                url: "#"
                            },
                            {
                                text: "Advertising",
                                url: "#"
                            },
                            {
                                text: "Jobs",
                                url: "#"
                            },
                            {
                                text: "Subscriptions",
                                url: "#"
                            },
                            {
                                text: "Talent Workshops",
                                url: "#"
                            },
                            {
                                text: "CPSC Certificates",
                                url: "#"
                            },
                            {
                                text: "Ratings",
                                url: "#"
                            },
                            {
                                text: "Shop Help",
                                url: "#"
                            },
                            {
                                text: "Contact Us",
                                url: "#"
                            }
                        ]
                    },
                    {
                        text: "Sites",
                        items: [{
                                text: "DC",
                                url: "#"
                            },
                            {
                                text: "MAD Magazine",
                                url: "#"
                            },
                            {
                                text: "DC Kids",
                                url: "#"
                            },
                            {
                                text: "DC Universe",
                                url: "#"
                            },
                            {
                                text: "DC Power Visa",
                                url: "#"
                            }
                        ]
                    }
                ]
            }
        }
    }
</script>

<style lang='scss' scoped>
    @import '../assets/style/variables.scss';
    @import '../assets/style/global.scss';


        #wrapper {
            max-width: 600px;
            display: flex;
            align-items: flex-start;
            max-height: 450px;
            flex-flow:column wrap;
            h3{
                padding-left:30px;
            }
        }
</style>