<script>

</script>

<template>

    <div class="header">
        <div class="left_header">
            <span class="text_header">Header</span>
        </div>
        <div class="right_header">
            <a href="https://t.me/Bunmuffin" class="telegram">Contact</a>
        </div>
    </div>

</template>

<style>

.header{ 
    width: 100%;
	background: #a5def0;
	height: 70px;
    display: flex;
    align-items: center;
    grid-template-columns: 30% 70%;
 }

 .right_header{
    width: 50%;
    text-align: right;
 }

 .left_header{
    width: 50%;
 }

 .text_header {
    font-family: 'Open Sans';
    font-weight: 700;
    margin-left: 50px;
}

.telegram{
    font-family: 'Open Sans';
    font-weight: 700;
    text-decoration: none;
    color: black;
    margin-right: 50px;
}


</style>