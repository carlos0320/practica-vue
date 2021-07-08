<template>
    <div>
        <h2>{{inputText}}</h2>
    <input type="text" v-model="inputText">
    </div>
    
</template>

<script>
export default {
    name: "EjercicioUno",
    data: function(){
        return {
            inputText: ""
        }
    }
}
</script>