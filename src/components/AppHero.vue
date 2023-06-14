<script>

import { createApp } from 'vue'
export default{
    data(){
        return{

        }
    },
    methods:{

    },
    mounted(){

    }
}
</script>


<template>
    <div class="jumbotron">
        <div class="margin-auto jumbotron-wrapper-top">
            <h1>
                Tutto ciò che ti serve per il lavoro, in un unico posto
            </h1>
        </div> 

        <div class="margin-auto jumbotron-wrapper-bottom flex">
            <div class="jumbotron-text">

                <div class="top-text">
                        Finalmente tutti i tuoi strumenti,contenuti e collaboratori sono accesibili dallo stesso posto.
                        Dropbox Business e piu di uno spazio di archiviazione
                        sicuro. e un mondo intelligente e integrato per ottimizzare il flusso di lavoro esistente.
                </div>
                <div class="button-text">
                    <button class="blue-button">
                        Inizia la tua prova gratuita
                    </button>
                </div>
                <div class="middle-text">
                    <p>
                        Annulla in qualsiasi momento
                    </p>
                </div>
                <div class="bottom-text">
                    <i class="fa-solid fa-arrow-down fa-2x"></i>
                </div>
            </div>
            <div class="jumbotron-image">
                <img src="./img/jumbo.png" alt="jumbotron-image">
            </div>
        </div>
    </div>
</template>

<style scoped>
/* RESET */
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html{
    overflow-x: hidden;
}
body{
    font-family:'Open Sans', sans-serif;
    color: black;
}
.flex{
    display: flex;
}
.margin-auto{
    margin: 0 auto;
}
.flex-between{
    display: flex;
    justify-content: space-between;
}
.flex-wrap{
    display: flex;
    flex-wrap: wrap;
}
.flex-center{
    display: flex;
    align-items: center;
}
header{
    padding: 1.2rem 1rem;
    font-size: 0.75rem;
}
.left-side-header{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.left-side-header>img{
    padding-right: 2.2rem;
}
.right-side-header{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.right-side-header>ul{
    display: flex;
    align-items: center;
}
.right-side-header>ul li:hover{
    text-decoration: underline;
}
.left-side-header>ul li:hover{
    text-decoration: underline;
}
h1{
    font-size: 3.5rem;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
}
.jumbotron{
    width: 100%;
    height: 500px;
    background-color: #b4d0e7;
    padding: 1.8rem 0;
}
.jumbotron-wrapper-top{
    padding: 1.3rem 1rem;
    width: 60%;
    height: 150px;
}
.button-text button{
    padding: 0.6rem 1.2rem;
}
.jumbotron-wrapper-bottom{
    padding: 2rem 0;
    border-color: cyan;
    width: 60%;
    height: 350px;
}
.jumbotron-text{
    width: 35%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding-left: 1rem;
}
.top-text{
    font-size: 0.75rem;
    flex-basis: auto;
}
.button-text{
    flex-basis: auto;
}
.checklist{
    font-size: 0.6rem;
    margin-top: 4rem;
}
.checklist ul li i{
    color: #0061ff;
}
.middle-text{
    flex-basis: auto;
    font-size: 0.8rem;
}
.bottom-text{
    flex-basis: auto;
    padding-bottom: 0.8rem;
}
.jumbotron-image{
    width: 65%;
}
.jumbotron-image>img{
    height: 350px;
}
ul{
    list-style-type: none;
}
a{
    text-decoration: none;
    color: black;
    padding-right: 1rem;
}
button{
    border: none;
    color: white;
}
.blue-button{
    background-color: #0061ff;
    padding: 0.3rem 1rem;
}
.white-btn{
    border: 1px solid #5f5f5f;
    color: #5f5f5f;
    padding: 0.5rem;
    background-color: white;
}
main{
    max-width: 780px;
    height: 100%;
    padding: 6rem 0;
}
div.bussines-top{
    width: 100%;
    border: 1.5rem solid white;
}
div.bussines-top>h2{
    font-size: 1.8rem;
}
div.bussines-checkbox{
    width: 100%;
    border: 1.5rem solid white;
}
form>span{
    padding-right: 2.5rem;
}
div.bussines-column-wrapper{
    display: flex;
    flex-wrap: wrap;
    border: 0.2rem solid white;
}
div.bussines-column{
    width: calc(100% / 3);
    border: 1.5rem solid white;
}
.column-text{
    border: 1px solid #e2e4e2;
    padding: 1.8rem;
    width: 100%;
    height: 660px;
    position: relative;
}
.upper-text>h3{
    margin-bottom: 1rem;
    text-indent: -0.3rem;
}
.price{
    font-size: 0.8rem;
}
.upper-text ul li{
    margin-bottom: 0.5rem;
    text-indent: -0.3rem;
}
.montly{
    color: #5f5f5f;
    font-size: 0.8rem;
}
.list-properties{
    margin-top: 2rem;
    font-size: 0.6rem;
}
.list-properties ul li{
    margin-bottom: 1rem;
    text-indent: -0.3rem;
}
.checklist ul li{
    margin: 1rem 0;
    text-indent: -0.3rem;
}
.line-column{
    border-top: 1px solid #e3e3e5;
    width: 15%;
    top: 57%;
    position: absolute;
}
.button-purchase{
    margin-top: 1.8rem;
    font-size: 0.6rem;
}
.button-purchase .btn-contacts{
    padding: 0.6rem 3.5rem;
}
.button-purchase p a{
    text-decoration: underline;
    color: #0061ff;
}
.button-purchase button{
    font-size: 0.5rem;
    padding: 0.6rem 1.5rem;
    margin-bottom: 1rem;  
}
div.upper-column{
    font-size: 0.7rem;
    width: 100%;
    height: 30px;
    background-color: white;
    border: 1px solid #e2e2e4;
    border-bottom: none;
    padding: 0.4rem 0;
    text-align: center;
}
.bussines-footer-upper{
    text-align: center;
    padding: 0.4rem 0;
}
div.bussines-footer{
    border: 1.5rem solid white;
    border-top: 0.5rem solid white;
}
div.bussines-footer>.bussines-footer-upper{
    font-size: 0.7rem;
    width: 100%;
    height: 30px;
    border: 1px solid #e2e4e2;
    border-bottom: none;
}
div.bussines-footer>.bussines-footer-lower{
    border: 1px solid #e2e4e2;
}
.enterprise-text{
    width: 70%;
    height: 100%;
    padding: 1.5rem;
}
.enterprise-text>h3{
    margin-bottom: 0.5rem;
}
.enterprise-text>strong{
    font-size: 0.8rem;
}
.enterprise-text>p{
    font-size: 0.65rem;
    margin-top: 1.5rem;
}
.enterprise-button{
    width: 30%;
    height: 100%;
    padding: 1.5rem 0;
}
.enterprise-button>button{
    font-size: 0.7rem;
    padding: 0.5rem 2rem;
}
.partner-box{
    width: 100%;
    height: 400px;
    border: 1.5rem solid white;
    margin-top: 2.5rem;
    display: flex;
}
.image-partner{
    width: 55%;
    height: 100%;
}
.text-partner{
    font-size: 0.7rem;
    width: 45%;
    height: 100%;
    padding-top: 1.5rem;
    padding-left: 3.2rem;
  }
.text-partner>p{
    padding-bottom: 1.4rem;
    padding-right: 2rem;
}
.text-partner>h2{
    margin-bottom: 0.8rem;
    padding-right: 1rem;
}
.image-partner>img{
    height: 100%;
}
.title-operations{
    border: 1.5rem solid white;
    border-bottom: none;
}
.operations-boxes{
    display: flex;
    flex-wrap: wrap;
}
.box-operation{
    width: calc(100% / 3);
    border: 1.5rem solid white;
    font-size: 0.6rem;
}
.box-operation>img{
    width: 100%;
}
.step-title{
    font-size: 1rem;
    padding-bottom: 1.1rem;
}
.dropbox-team{
    width: 70%;
    border: 1.5rem solid white;
    padding-top: 3.8rem;
}
.team-numbers>h1{
    font-size: 2.2rem;
    padding-bottom: 2rem;
}
.link-about-clients a{
    text-decoration: underline;
    color: #406af0;
}
.team-boxes{
    display: flex;
}
.left-team-boxes,.right-team-boxes,.mid-team-boxes{
    width: calc(100vw / 3);
    height: calc(100vw / 3);
}
div.designit{
    background-color: #a2d39b;
    border: 8px solid #d1e9cd;
}
div.arizona{
    background-color: #61082b;
}
div.arizona>img{
    height: 85px;
}
div.florida{
    background-color: #0093ce;
}
div.florida>img{
    height: 25px;
}
div.topps{
    background-color: #fe1b1b;
}
div.topps>img{
    height: 50px;
}
div.world-bicyle{
    background-color: #d5001e;
}
div.hearst-corp{
    background-color: #b4d0e7;
}
div.hearst-corp>img{
    height: 10px;
}
div.lonely-planet{
    background-color: #0d2481;
}
div.lonely-planet>img{
    height: 55px;
}
div.clearchannel{
    background-color: #ffd82f;
}
div.clearchannel>img{
    height: 70px;
}
.mid-team-boxes{
    background-color: #f5f5f5;
    padding: 2rem;
    position: relative;
    overflow: auto;
}
.mid-team-boxes>img{
    height: 50px;
    margin-bottom: 1.2rem;
}
.mid-team-boxes>p{
    font-size: 0.75rem;
    padding-bottom: 2rem;
}
.mid-team-boxes :nth-child(3){
    padding-top: 2rem;
}
.mid-team-boxes>.border-top{
    border-top: 1px solid #dbdbdd;
    position: absolute;
    top: 28%;
    width: 18%;
}
.right-team-boxes{
    background-color: rgb(65, 159, 241);
}
.team-member{
    width: 50%;
    height: 50%;
    position: relative;
    display: flex;
}
.team-member>img{
    height: 35px;
    margin: auto;
    filter: invert(1);
}
.dropbox-company{
    width: 100%;
    background-color: #b4d0e7;
}
.wrapper-dropbox-company{
    max-width: 780px;
    display: flex;
    align-items: center;
    padding: 3.5rem 0;
}
.dropbox-company-title{
    padding: 2rem 6rem;
    width: 65%;
}
.dropbox-company-title>h1{
    color:#5c0022;
    font-size: 1.4rem;
}
.start-button-free{
    width: 30%;
    text-align: right;
}
.start-button-free>button{
    padding: 0.45rem 2rem;
    margin-bottom: 1rem;
    font-size: 0.7rem;
}
.questions-wrapper{
    max-width: 780px;
    padding: 6rem 0;
}
.questions-wrapper>h2{
    padding-bottom: 2.5rem;
}
.questions-wrapper>p{
    font-weight: bold;
    padding: 2rem 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.questions-wrapper p>i{
    padding-right: 1.5rem;
}
footer{
    background-color: black;
    width: 100%;
    padding: 4rem 0;
}
.footer-wrapper{
    max-width: 1000px;
    display: flex;
    flex-wrap: wrap;
}
.footer-column{
    height: 100%;
    width: 20%;
    font-size: 0.8rem;
}
.footer-column>h3{
    margin-bottom: 2rem;
    color: white;
}
.footer-column ul li{
    margin-bottom: 0.8rem;
}
.footer-column ul li a:hover{
    text-decoration: underline;
}
.footer-column ul li a{
    color: white;
}
.footer-bottom{
    width: 100%;
    height: 100px;
    padding: 1rem 0;
    position: relative;
    margin-top: 3rem;
    font-size: 0.8rem;
}
.line-footer{
    border-top: 1px solid white;
    width: 10%;
    top: 5%;
    position: absolute;
}
.footer-bottom>div{
    color: #534b42;
    padding: 2rem 0;
}

.hidden-question{
    display:none;
}

.fa-chevron-down:hover .hidden-question{
    display: block;
}

</style>

<!-- Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->
<!-- Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron. -->