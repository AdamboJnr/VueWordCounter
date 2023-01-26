<script scoped>
    export default{
        data(){
            return{
                text: ""
            }
        }
    }
</script>
<template>
    <input type="text" v-model="text"><br>
    <p>Words: {{ text.length }}</p>
</template>