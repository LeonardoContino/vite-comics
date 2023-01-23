<script>
export default{
    props: {
        comic: Object
    },

}
</script>


<template>
    <div class="card">
         <img :src="comic.thumb" alt="comic.series">
        <figcaption class="img-text">{{ comic.series }}</figcaption>
    </div>
</template>


<style scoped lang="scss">
.card{
    width: 150px;
    background-color: #1C1C1C;
 img{
    width: 150px;
    height: 150px;
    object-fit: cover;
    padding-bottom: 5px;
 .img-text{
    width: 100%;
 }
}
}
 

</style>