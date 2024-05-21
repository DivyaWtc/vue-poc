<template>

    <HomeHeader></HomeHeader>
    <ToDoItem></ToDoItem>


</template>


<script>
import HomeHeader from './HomeHeader.vue';
import ToDoItem from  './ToDoItem.vue'

export default{
    name:'HomePage',
    components:{
        HomeHeader,
        ToDoItem
    }

    
}




</script>


<style>





</style>