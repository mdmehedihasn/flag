<template>
    <div class="flex-container">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
    </div>
</template>
<style>
    .flex-container{
        display: flex;
        background: green;
        /*gap:10px;*/

    }
    .flex-container > div{ 
        border: 3px solid blue;
        background: rgb(180, 180, 83);
        text-align: center;
        color: white;
        line-height: 70px;
        margin: 10px;
        
    }
</style>