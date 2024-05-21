<template>
    <div class="parent-container">
        <div class="container">
            <div class="sub-container">
                
    
            </div>
    
        </div>

    </div>
    
</template>

<script>
export default{
    name:'ToDoItem',
}

</script>

<style scoped>
.parent-container
{
    display: flex;
    justify-content: center;
    align-items: center;
    
   
}
.container{
    background-color:rgb(112, 59, 198);
    height: 500px;
    width:500px;
    display: flex;
    justify-content: center;
    align-items: center;


}
.sub-container{
    background-color:whitesmoke;
    height: 400px;
    width:400px;
    
    

}



</style>