<script>

</script>

<template>

    <div class="main">
            <div class="banner">Banner</div>
            <div class="content_hello">
                <div class="text_one_ch">Hello, World!</div>
                <div class="text_two_ch">Look at my website</div>
            </div>
            <div class="block_for_cards">
                <div class="card">Here</div>
                <div class="card">And here</div>
            </div>
    </div>

</template>

<style lang="scss">

.main{
    height: calc(100vh - 140px);
    display: flex;
    position: relative;
    flex-direction: column;
}


@mixin card($fill: #D5FDD1) {
    background: $fill;
    padding-left: 10px;
}

.card {
    @include card();
    height: 70%;
    display: flex;
    align-items: center;
    font-family: 'Montserrat';
    font-size: 2rem;
}

.banner {
    @include card(#009C00);
    font-family: 'Montserrat';
    font-size: 2rem;
    color: white;
    height: 15%;
    margin-top: 100px;
    margin-left: 100px;
    margin-right: 100px;
    display: flex;
    align-items: center;
}

.content_hello{
    height: 60%;
    margin-left: 100px;
    margin-right: 100px;
    position: relative;
    flex-direction: column;
}

.text_one_ch{
    height: 50%;
    font-family: 'Montserrat';
    font-size: 3rem;
    display: flex;
    align-items: center;
    font-weight: bold;
}

.text_two_ch{
    height: 50%;
    font-family: 'Montserrat';
    font-size: 2.5em;
    display: flex;
    align-items: center;
}

.block_for_cards{
    height: 25%;
    margin-left: 100px;
    margin-right: 100px;
    margin-bottom: 100px;
    display: grid;
    align-items: center;
    grid-template-columns: 300px 300px;
    grid-column-gap: 30px;
}



</style>