<template>
  <header class="container-lg">
    <div class="row justfy-content-between">
        <div class="col-2">
            <img src="../assets/img/dc-logo.png" alt="DC Logo">
        </div>      
    <nav class="d-flex col-6">
        <ul>
            <li v-for="(link, index) in headerNav" :key="index" >
                <a href="">{{link}}</a>
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
            headerNav: [
                'CHARACTERS',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP'
            ]
        }
    },
}
</script>

<style lang='scss'>
@import '../assets/style/variables.scss'; 

header{
    padding: 1rem;
    img{
        height: 100px;
    }
    nav{
        ul{
            display: flex;
            align-items: center;
            justify-content: center;
            list-style: none;
            li{
                display: inline-block;
                padding: 1rem;
                height: 100%;
                            display: flex;
            align-items: center;
            justify-content: center;
                    &:hover{
                    border-bottom:1px solid $brand-color
                }
                a{
                    text-decoration:none;
                }
            }
        }
    }
}

</style>