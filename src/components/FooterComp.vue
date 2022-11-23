<template>
<footer>
    <div class="conteiner">
        <div class="DcComics">
        <div>
            <ul>
                <li class="titolo">DC COMICS</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
            </ul>
            <ul>
                <li class="titolo">Shop</li>
                <li>Characters</li>
                <li>Characters</li>
            </ul>
        </div>
        <div>
            <ul>
                <li class="titolo">DC</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
            </ul>  
        </div>
        <div>
            <ul>
                <li class="titolo">SITES</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>
                <li>Characters</li>               
            </ul>  
        </div>

    </div>

    <div class="img-logo">
        <img src="../assets/img/dc-logo-bg.png" alt="">
    </div>


    </div>
    <FooterComp/>
</footer>


    
</template>

<script>
    export default {
        name: "FooterComp"
    }
</script>

<style lang="scss" scoped>
footer{
    background-image:url(../assets/img/footer-bg.jpg) ;
    display: flex;
    justify-content: center;
}
.conteiner{
    width: 80%;
    display: flex;
    color: grey;

    
}

.DcComics{
    display: flex;
    flex-basis: 30%;
    margin: 25px 0;
}

.img-logo{
   flex-basis: 70%; 
   
   img{
    width: 50%;
   }
}

ul{
    list-style-type: none;
    li{
        margin: 5px 20px;
    }
}
.titolo{
   color: white;
}

</style>