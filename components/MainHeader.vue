<script>


</script>

<template>
  
  <header>

    <div class="header_left_block">
      <a href="/">
          <img src="~/assets/img/logo.png" height="40px">
      </a>
      <ul class="menu">
        <li><a href="#">Реализованные проекты</a></li>
        <li><a href="#">Новости</a></li>
        <li><a href="#">Контакты</a></li>
      </ul>
    </div>



    <div class="header_right_block">
      <a class="tel" href="tel:88001234567"><img src="~/assets/img/tel.png" height="16px">+7 (900) 900-90-90</a>
      <BaseButton />
    </div>

  </header>


</template>


<style lang="scss" scoped>

header{
    font-family: 'Montserrat';
    background-color: #FFFFFF;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 24px 88px;
}

.menu{
  margin: 0;
  padding: 0;
  list-style-type: none;
  display: flex;
  gap: 24px;
}

.menu a{
  text-decoration: none;
  color: #666666;
}

.tel{
  color: #254741;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 8px;
}

.header_right_block{
  display: flex;
  gap: 24px;
}

.header_left_block{
  display: flex;
  gap: 80px;
  align-items: center;
}

</style>