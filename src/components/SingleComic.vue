<template>
  <div class="thumb p-4">
    <div class="img-cutter"><img :src="thumb" :alt="series"></div>
    <h5>{{series}} </h5>
  </div>
</template>

<script>
export default {

    props:{
        thumb:String,
        price:Number,
        series:String,
        type:String,
    },
}
</script>

<style lang='scss'>
.thumb{
    display: flex;
    flex-direction: column;

    align-items: center;
    overflow: hidden;
    .img-cutter{
        height: 200px;
        overflow: hidden;
    }
    img{
        height: 300px;
        object-fit: contain;
        object-position: top;
    
    }
    h5{
        margin: 1rem;
    }

}
</style>