<template>

    <div>
        <div>
            <HomeHeader></HomeHeader>
        </div>
        <div>
            <ToDoItem></ToDoItem>
        </div>
        
    </div>
   
    


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