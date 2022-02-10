<template>
    <div id="Presentation">
        <img class="Image_pres" src="https://raw.githubusercontent.com/Snakeshader-pro/CV_Vrai_SITE/master/src/assets/Image_Pres.PNG" alt="">
        <h1> 
            
            <p>Théo</p>
            <p>Stoffelbach</p> 

        </h1>
    </div>

</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#Presentation {
    padding-top: 50px;
    width: 100%;
    height: 100vh;

    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #162124;
}

.Image_pres {
    margin-left: 80px;
    width: 40vw;
    max-width: 810px;
    height: auto;

}

.One {
    height: 100vh;
    background-image: linear-gradient(180deg, rgb(37, 163, 10),rgb(138, 191, 54),rgb(239, 219, 97));
}

#Presentation h1{
    font-size: 144px;
    margin-right: 80px;
    width: 100%;
    color: white;

    display: flex;
    flex-direction: column;
    font-family: 'game power', sans-serif;

}

@media screen and (max-width: 1000px) {
    #Presentation {
        flex-direction: column;
        align-items: center;
    }
    .Image_pres {
    width: 80vw;
    margin: 0;
}



}

</style>
