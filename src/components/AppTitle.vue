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
    <div class="container">
        <h1>
            La mia prima app con Vite!
        </h1>
        <img src="../../public/vite.svg" alt="vite-logo">
    </div>
</template>

<style scoped>
div.container{
   text-align: center;
   display: flex;
   background: linear-gradient(#e66465, #0ea1eb);
   padding: 5rem;
   border-radius: 2rem;
}

div.container:hover{
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px 0px;
    transition: all .2s ease-in-out;
    transform:scale(1.1);
}

h1{
    border: 1rem;
    color: yellow;
    font-size: 2rem;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

img{
    margin-left: 3rem;
    width: 90px;
    height: 90px;
}
</style>

<!-- Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->
