

<script>
import { createApp } from 'vue'
export default{
    data(){
        return
    },
    methods:{

    }
}

</script>



<template>
     <header class="flex-between">
        <section class="left-side-header">
            <img src="../../public/logo-small.png" title="Dropbox-Logo" alt="Logo-dropbox">
            <ul class="flex-between">
                <li>
                    <a href="#">Perchè Dropbox</a>
                </li>
                <li>
                    <a href="#">Funzioni</a>
                </li>
                <li>
                    <a href="#">Piani e Prezzi</a>
                </li>
            </ul>
        </section>
        <section class="right-side-header">
            <ul class="flex">
                <li>
                    <a href="#">Supporto</a>
                </li>
                <li>
                    <a href="#">Contatta l'ufficio vendite</a>
                </li>
                <li>
                    <a href="#">Accedi</a>
                </li>
                <li>
                    <button class="btn blue-button">
                        Inizia
                    </button>
                </li>
            </ul>
        </section>
    </header>
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
.button-text button{
    padding: 0.6rem 1.2rem;
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