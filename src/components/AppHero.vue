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
                        <div class="button-text">
                            <button class="blue-button">
                                Inizia la tua prova gratuita
                            </button>
                            <p class="mt-2">
                                Annulla in qualsiasi momento
                            </p>
                            <div>
                                <i class="fa-solid fa-arrow-down fa-2x"></i>
                            </div>
                        </div>
                </div>
            </div>
            <div class="jumbotron-image">
                <img src="../../public/jumbo.png" alt="jumbotron-image">
            </div>
        </div>
    </div>
</template>

<style scoped>
/* RESET */
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
    text-align: left;
    margin-bottom: 5rem;
}
.jumbotron-wrapper-top{
    padding: 1.3rem 1rem;
    width: 60%;
    height: 150px;
}

.button-text{
    margin-top: 4rem;
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

</style>

<!-- Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->
<!-- Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron. -->