<script setup lang="ts">

import HouseIcon from 'assets/icons/LightLogo.svg?skipsvgo'

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

    <footer class="footer">

        <a href="/"><HouseIcon /></a>

        <ul class="menu">
            <li v-for='item in nav'>
                <a :href='item.url'>
                    {{  item.label }}
                 </a>
            </li>
        </ul>

        <div class="info">
            <a class="item" href="tel:88001234567"><SvgoPhoneIcon class="Icon" />+7 (900) 900-90-90</a>
            <a class="item" href="mailto:info@gmail.com"><SvgoEmailIcon class="Icon" />info@gmail.com</a>
            <p class="item"><SvgoPointIcon class="Icon" />г. Владивосток ул. Выселковая 49, стр. 3</p>
        </div>

        <BaseButton class="button" />

        <p class="additionally">© Загдом, 2021</p>
        <p class="additionally">Политика конфиденциальности</p>
        <p class="additionally">Пользовательское соглашение</p>


    </footer>

</template>


<style lang="scss" scoped>

.footer{
    font-family: 'Montserrat';
    background-color: #254741;
    padding: 24px 88px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 32px;
}


.menu{
    display: flex;
    flex-direction: column;
    gap: 24px;
    padding-top: 10px;
}

.menu a{
    text-decoration: none;
    color: #FFF;
}

.Icon{
    color: #029F59;
}

.info{
    display: flex;
    flex-direction: column;
    gap: 24px;
    padding-top: 10px;
}

.item{
    color: #FFF;
    text-decoration: none;
    display: flex;
    gap: 8px;
}

.button{
    justify-self: end;
    align-self: flex-start;
}

.additionally{
    color: #a8b5b3;
    font-size: 14px;
}

</style>