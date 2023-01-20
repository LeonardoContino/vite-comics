<script>

</script>

<template>
        
        <footer class="row">
            <div class="container d-flex">
                <div class="col">
                    <h4>DC COMICS</h4>
                        <div>
                            <p>Characters</p>
                            <p>Comics</p>
                            <p>movie</p>
                            <p>tv</p>
                            <p>games</p>
                            <p>videos</p>
                            <p>News</p>
                        </div>
                    <h4>SHOP</h4>
                    <div>
                        <p>shop dc</p>
                        <p>shop dc</p>

                    </div>
                </div>
                <div class="col">
                    <h4>DC</h4>
                    <div>
                            <p>Characters</p>
                            <p>Comics</p>
                            <p>movie</p>
                            <p>tv</p>
                            <p>games</p>
                            <p>videos</p>
                            <p>News</p>
                        </div>
                </div>
                <div class="col">
                    <h4>SITES</h4>
                    <div>
                            <p>Characters</p>
                            <p>Comics</p>
                            <p>movie</p>
                            <p>tv</p>
                            
                        </div>
                </div>
            </div>


    </footer>

    <section class="follow">
        <div class="row-follow container">
            <div class="col-sign">
                <h4>SIGN-UP NOW!</h4>
                
            </div>
            <div class="col-icon-follow d-flex">
                <h4>FOLLOW US</h4>
                <figure>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">




                </figure>
            </div>
        </div>
    </section>
    
    
</template>

<style scoped>
.row{
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    min-height: 300px;
    display: flex;
    height: 100%;
    

}
.d-flex{
    display: flex;
}
.col{
    
    width: 150px;
    height: 100%;
    color: white;
    margin: 20px 0;
}
.col p{
    color: rgba(255, 255, 255, 0.6);
    font-size: 10px;
}
.follow{
    background-color: #303030 ;
    height: 100px;
}
.row-follow{
    display: flex;
    align-items: center;
    height: 100%;
    justify-content: space-between;
    

}
.col-sign{
    color: white;
}
.col-sign h4{
    padding: 10px;
    border: 2px solid #117CE9;
}
.col-sign h4:hover{
    background-color: #117de981;
    cursor: pointer;
}
.col-icon-follow{
    
    align-items: center;
}
.col-icon-follow figure img{
    padding: 5px;
}
</style>