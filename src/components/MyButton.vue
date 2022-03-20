<template>
    <div class="my-button">
        <h1>我爱你{{buttonName}}</h1>
        <h2>年龄：{{buttonAge}}</h2>
        <button @click="count++">爱了{{count}}次</button>
    </div>
</template>


<script>
export default {
    data(){
        return {
            count:0
        }
    },
    props: {
        buttonName:{
            type: String,
            required:false
        },
        buttonAge:{
            type:Number,
            required:true
        }
   }
}
</script>

<style scoped>
.my-button{
    padding: 20px;
    margin-bottom: 20px;
    border: 1px solid red;

}
h1{
    color: aqua;
}
</style>