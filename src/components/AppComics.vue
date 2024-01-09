<script>
export default {
    name: 'AppComics',
    props: {
        comic: Object
    }

}
</script>

<template lang="">
    
    <div class="regular-card">
    
        <img :src="comic.thumb">
        <h6 class="card-text">{{comic.series}}</h6>
                          
    </div>
   
</template>

<style lang="scss">
.regular-card {
    margin: 10px;
    width: calc(100% / 6 - 20px);



    img {
        aspect-ratio: 1 / 1;
        max-width: 100%;

    }

    h6 {
        text-transform: uppercase;
        margin-top: 5px;
    }
}
</style>