<script>

</script>

<template>

    <div class="footer">
        <div class="left_footer">
            <span class="text_footer">Footer</span>
        </div>
        <div class="right_footer">
            <a href="https://t.me/Bunmuffin" class="telegram">Contact</a>
        </div>
    </div>

</template>

<style>

.footer{ 
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
	background: #899396;
	height: 70px;
    display: flex;
    align-items: center;
 }

 .right_footer{
    width: 50%;
    text-align: right;
 }

 .left_footer{
    width: 50%;
 }

 .text_footer {
    font-family: 'Open Sans';
    margin-left: 50px;
}

.telegram{
    font-family: 'Open Sans';
    text-decoration: none;
    color: rgb(68, 61, 110);
    margin-right: 50px;
}


</style>