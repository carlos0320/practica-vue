<template>
    <div>
        <h2 :style="myStyle">hola</h2>
        <input type="text" v-model="inputText">
    </div>
    
</template>

<script>
export default {
    name: "EjercicioUno",
    data: function(){
        return {
            inputText:"#ffffff",
             myStyle:{
                color:inputText
            }
    }
}}
</script>

