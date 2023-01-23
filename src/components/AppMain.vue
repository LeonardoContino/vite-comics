<script>
import AppDataComics from './AppDataComics.vue'
export default{
    components:{AppDataComics},
    props: {
        comics: Array
    },
    
    data(){
        return{
            
            iconList: [
                {
                    text: 'DIGITAL COMICS',
                     img: '../assets/img/buy-comics-digital-comics.png'
                },
                {
                    text: 'DC MERCHANDISE',
                     img: '../assets/img/buy-comics-digital-comics.png'
                },
                {
                    text: 'SUBSCRIPTION',
                     img: '../assets/img/buy-comics-digital-comics.png'
                },
                {
                    text: 'COMIC SHOP LOCATOR',
                     img: '../assets/img/buy-comics-digital-comics.png'
                },
                {
                    text: 'DIGITAL DC POWER VISA',
                     img: '../assets/img/buy-comics-digital-comics.png'
                }
            ],
 

        }
    }
}

</script>

<template>
    
    <div class="content">
        <div class="btn-series">Current series</div>
        <div  class="cards-comics">
            <AppDataComics v-for="comic in comics" :key="comic.series" :comic="comic" ></AppDataComics>
        </div>
        <div class="btn-more">
            load more
        </div>
        
        
    </div>

    <section class="icon">
        <div>
            <div class="image-icon">
                
            </div>
            <div class="text-icon"></div>
        </div>
    </section>
</template>

<style scoped lang="scss">
.content{
    position: relative;
    min-height: 150px;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    width: 100%;
    justify-content: center;
    color: white;
    background-color: #1C1C1C;
}

.icon{
    height: 200px;
    background-color:#1382F9 ;
}
.cards-comics{
    display: flex;
    width: 1200px;
    flex-wrap: wrap;
    
    
.card{
    flex-basis: calc(100% / 6);
    
}
}
.btn-more{
    background-color: #1382F9;
    color: white;
    padding: 10px 30px;
    cursor: pointer;
}
.btn-series{
    position: absolute;
    background-color: #1382F9;
    color: white;
    cursor: pointer;
    top: -20px;
    left: 50px;
    padding: 5px 20px;

}



</style>