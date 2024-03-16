<script>


</script>

<template>
  
  <header>

    <a href="/">
        <img src="~/assets/img/logo.png" height="40px">
    </a>

    <ul class="menu">
      <li>Реализованные проекты</li>
      <li>Новости</li>
      <li>Контакты</li>
    </ul>

    <div class="header_right_block">
      <a class="tel" href="tel:88001234567"><img src="~/assets/img/tel.png" height="20px">+7 (900) 900-90-90</a>
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
    padding-left: 88px;
    padding-right: 88px;
    padding-top: 29px;
    padding-bottom: 29px;
}

.menu{
  color: #666666;
  margin: 0;
  padding: 0;
  list-style-type: none;
  display: flex;
  gap: 24px;
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

</style>