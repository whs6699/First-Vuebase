<template>
    <div>
        <MyButton buttonName="s" :buttonAge="12"></MyButton>
        <MyButton buttonName="w" :buttonAge="17"></MyButton>

    </div>
</template>

<script>
import MyButton from '@/components/MyButton'
export default {
    name:'',
    components: {
        MyButton:MyButton
    }
}
</script>

<style scoped>

</style>