<template>
    <div class="flex-container">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
        <div>6</div>
        <div>7</div>
        <div>8</div>
        <div>9</div>
        
    </div>
</template>
<style scoped>
.flex-container{
    display: flex;
    align-items: stretch;
    background: rgb(16, 221, 211);
}
.flex-container > div{
    background: rgb(230, 226, 14);
    width: 100%;
    color: black;
    font-size: 30px;
    text-align: center;
    border: 1px solid rgb(44, 89, 240);
    margin: 10px;
    line-height: 75px;
}
</style>