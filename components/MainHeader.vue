<script setup lang="ts">

import HouseIcon from 'assets/icons/DarkLogo.svg?skipsvgo'

const nav = [
  {
    url: '#',
    label: 'Реализованные проекты'
  },
  {
    url: '#',
    label: 'Новости'
  },
  {
    url: '#',
    label: 'Контакты'
  },
]

</script>

<template>
  
  <header class="header">

    <div class="header_left_block">
      <a href="/">
        <HouseIcon />
      </a>
      <ul class="menu">
        <li v-for='item in nav'>
          <a :href='item.url'>
            {{  item.label }}
          </a>
        </li>
      </ul>
    </div>



    <div class="header_right_block">
      <a class="tel" href="tel:88001234567"><SvgoPhoneIcon class="Icon" />+7 (900) 900-90-90</a>
      <BaseButton />
    </div>

  </header>


</template>


<style lang="scss" scoped>

.header{
    font-family: 'Montserrat';
    background-color: #FFFFFF;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 24px 88px;
}

.menu{
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

.Icon{
  color: #029F59;

}

</style>