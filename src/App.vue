<template>
  <div id="app">
    <header class="header">
      <div class="header__links">

        <nav class="menu-top">
          <ul class="menu-top__list">
            <li class="menu-top__list-item">Компания</li>
            <li class="menu-top__list-item">Портфолио</li>
            <li class="menu-top__list-item">Проектирование</li>
            <li class="menu-top__list-item">Ресторанам</li>
            <li class="menu-top__list-item">Застройщикам</li>
            <li class="menu-top__list-item">Гос.заказчикам</li>
            <li class="menu-top__list-item">Таблет-питание</li>
            <li class="menu-top__list-item">Сервис</li>
            <li class="menu-top__list-item">Контакты</li>

            <img class="header__contacts-img " src="">
            <a class="header__contacts-name" href='tel:8 495 790-72-05'>8 495 790-72-05</a>
            <img class="header__contacts-img" src="">
            <a class="header__contacts-name">info@stolovay.ru</a>
          </ul>
        </nav>

      </div>
    </header>
   
          
    
    <catalog/>
  </div>
</template>

<script>
import catalog from './components/catalog.vue'

export default {
  name: 'App',
  components: {
    catalog
  }
}
</script>

<style>

.header {
  width: auto;
  /* max-width: 1400px; */
  justify-content: space-around;
  font-size: 10px;
}

.header__links {
  display: flex;
  justify-content: space-between;
  padding-left: 8px;
}

.menu-top__list {
  padding-left: 24px;
  display: flex;
  list-style-type: none;
}

.menu-top__list-item{
  margin-left: 24px;
  margin-right: 24px;
  align-self: center;
  justify-content:start;  
}


</style>
