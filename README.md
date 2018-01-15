<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <title>Техномарт</title>
  </head>
  <body>
<header class="main-header">
  <div class="header-top">
    <p class="logo">Техномарт</p>
    <!-- Не понимаю, когда оставлять значек для иконки (в <span>), а когда ничего не оставлять, будет псевдоэлемент -->
    <div class="search-link"><span class="icon-find"></span>Поиск
    </div>
    <!-- Будет вставлена форма поиска. И псевдо иконка -->
    <div class="bookmarks-link"><a href="bookmarks.html"><span class="icon-find"></span>Закладки</a>
          <span class="mookmarks-count">0</span>
    </div>

    <div class="basket-link"><a href="basket.html"><span class="icon-basket"></span>Корзина</a>
         <span class="basket-count">0</span>
    </div>

    <div class="checkout"><a href="checkout.html">Оформить заказ</a>
    </div>
  </div>
  <p class="purpose">Интернет-магазин строительных материалов и инструментов для ремонта</p>
  <div class="Phone-icon">
    <button>+7(812)555-05-55</button>
  </div>
  <div class="adress">
    <p>г.Санкт-Петербург, ул. Б Конюшенная, д.19/8</p>
  </div>
  <nav class="user-navigation">
   <ul class="user-navigation-list">
    <li class="login-link">Вход</li>
    <li class="check-in">Регистрация</li>
   </ul>
  </nav>
  <nav class="main-navigation">
   <ul class="site-navigation">
    <li><a href="home.html">Главная</a></li>
    <li><a href="company.html">Компания</a></li>
    <li><a href="catalog.html">Каталог</a></li>
    <li><a href="news.html">Новости</a></li>
    <li><a href="shares.html"> Спецпредложения</a></li>
    <li><a href="delivery.html">Доставка</a></li>
    <li><a href="contacts.html">Контакты</a></li>
   </ul>
  </nav>
</header>


<!-- Основное содержимое -->
<main>
  <h1 class="visually-hidden">Магазин "Техномарт"</h1>

  <!--Все, что предлагает Техномарт  -->
  <div class="assortment">
   <h2 class="visually-hidden">Наши предложения</h2>
   <ul class="assortment-list">
    <li>
      <h3>Материалы</h3>
      <a href="mainpage-link">На любой вкус</a>
    </li>
    <li>
      <h3>Инструмент</h3>
      <a href="mainpage-link">На все случаи</a>
    </li>
    <li>
      <h3>Техника</h3>
      <a href="mainpage-link">Для стройки</a>
    </li>
  </ul>
</div>

  <div class="slider">
   <div class="perforator">
    <img src="img.jpg" width="196" height="141" alt="Мужик с перфоратором">
    <h3>Перфораторы</h3>
    <p>Настоящие мужские игрушки</p>
    <a href="mainpage-link">Открыть каталог</a>
   </div>
   <div class="drills">
    <img src="img.jpg" width="196" height="141" alt="Мужик с дрелью у стены">
    <h3>Дрели</h3>
    <p>Соседям на радость!</p>
    <a href="mainpage-link">Открыть каталог</a>
  </div>
</div>

<div class="advantages">
  <ul class="advantages-list">
    <li>
      <h3>Скидки 50%</h3>
      <a href="mainpage-link">На 350 товаров</a>
    </li>
    <li>
      <h3>Доставка</h3>
      <a href="mainpage-link">Бесплатно</a>
    </li>
  </ul>
</div>

<!--Раздел популярных товаров  -->
<section class="popular-goods">
  <div class="title-popular-goods">
   <h2>Популярные товары:</h2>
   <a href="#">Все популярные товары</a>
  </div>
   <ul class="popular-goods-catalog">
    <li>
     <h3>Перфоратор BOSCH BFG 9000</h3>
     <img src="img/BFG-9000.jpg" width="196" height="141" alt="Перфоратор BOSCH BFG 9000">
     <p class="old-price">32500 Р.</p>
     <a href="today-price">25500 Р.</a>
    </li>
    <li>
     <h3>Перфоратор BOSCH BFG 3000</h3>
     <img src="img/BFG-3000.jpg" width="196" height="141" alt="Перфоратор BOSCH BFG 3000">
     <p class="old-price">22500 Р.</p>
     <a href="today-price">15500 Р.</a>
    </li>
    <li>
     <h3>Перфоратор BOSCH BFG 6000</h3>
     <img src="img/BFG-6000.jpg" width="196" height="141" alt="Перфоратор BOSCH BFG 6000">
     <p class="old-price">30500 Р.</p>
     <a href="today-price">25500 Р.</a>
    </li>
    <li>
     <h3>Перфоратор BOSCH BFG 2000</h3>
     <img src="img/BFG-2000.jpg" width="196" height="141" alt="Перфоратор BOSCH BFG 2000">
     <p class="old-price"></p>
     <!-- Скрою стилями старую цену. В дальнейшем,может понадобиться -->
     <a href="today-price">12500 Р.</a>
    </li>
    </ul>
</section>

<!--Популярные производители  -->
<section class="popular-brands">
 <div class="popular-brands-list">
  <h2>Популярные производители:</h2>
  <a href="#">Все производители</a>
</div>
  <ul class="popular-brands-catalog">
    <li><a href="#"><img src="img/brand-bosch.jpg" width="122" height="32" alt="BOSCH"></a>
    </li>
    <li><a href="#"><img src="img/brand-makita.jpg" width="123" height="40" alt="Макита"></a>
    </li>
    <li><a href="#"><img src="img/brand-dewalt.jpg" width="146" height="44" alt="Dewalt"></a>
    </li>
    <li><a href="#"><img src="img/brand-interskol.jpg" width="184" height="32" alt="Интерскол"></a>
    </li>
    <li><a href="#"><img src="img/brand-hitachi.jpg" width="143" height="22" alt="Hitachi"></a>
    </li>
    <li><a href="#"><img src="img/brand-lg.jpg" width="121" height="73" alt="LG"></a>
    </li>
    <li><a href="#"><img src="img/brand-aeg.jpg" width="151" height="84" alt="AEG"></a>
    </li>
    <li><a href="#"><img src="img/brand-metabo.jpg" width="155" height="55" alt="Metabo"></a>
    </li>
  </ul>
</section>

<!-- Сервис -->
<div class="aboute-servise">
 <section class="title-service">
  <h2 class="title-services">Сервисы</h2>
  <p>Хороший интернет-магазин отличается от плохого не только ценами!</p>
  <p>Мы стараемся изо всех сил, чтобы сделать ваши покупки приятными</p>
 </section>
 <div class="services-name">
  <ul class="services-name-list">
    <li class="services-name-item">Доставка</li>
    <li class="services-name-item">Гарантия</li>
    <li class="services-name-item">Кредит</li>
  </ul>
 </div>
 <section class="services-description">
   <h3 class="title-service-description">Доставка</h3>
    <p>Мы с удовольствием доставим ваш товар прямо к вашему подъезду совершенно бесплатно!
Ведь мы неплохо зарабатываем, поднимая его на ваш этаж!</p>
  </section>
</div>

 <section class="general-information">
   <div class="information">
    <h2 class="title-information">Компания "Техномарт"</h2>
    <p>Настоящий мужской шоппинг начинается здесь! Огромный выбор товаров для ремонта и
           строительства не оставит равнодушными любителей сэкономит на гастарбайтерах.</p>
    <p>Мы можем доставить ваш товар в самые отдаленные точки России!<br>
           Техномарт работает со многими транспортными компаниями:</p>
    <ul class="partners-list">
      <li>Деловые линии</li>
      <li>Автотрейдинг</li>
      <li>ЖелДорЭкспедиция</li>
    </ul>
    <a class="mainpage-link" href="ourcompany.html">Подробнее о компании</a>
  </div>
  <div class="location">
    <h2 class="title title-location">Контакты</h2>
    <p>Вы можете забрать товар сами, заехав в наш офис:</p>
    <a href="#"><img src="assets/img/map.jpg" alt="Расположение офиса на карте"></a>
    <a class="mappage-link" href="feedback.html">Заблудились? Напишите нам!</a>
  </div>
 </section>
</main>

<!--Подвал. -->
<footer class="main-footer">
  <div class="top-footer">
    <p class="logo">Техномарт</p>
     <nav class="menu-footer">
    <!-- "Верхний список" -->
       <ul class="menu-footer-list">
        <li><a href="company.html">Компания</a></li>
        <li><a href="news.html">Новости</a></li>
        <li><a href="company.html">Каталог</a></li>
        <li><a href="delivery.html">Доставка</a></li>
        <li><a href="contacts.html">Контакты</a></li>
       </ul>
     </nav>
     <p class="footer-contacts">г.Санкт-Петербург, ул. Б Конюшенная, д.19/8<br>
    +7(812) 555-05-55<br>
     </p>
  <!-- Нижний список -->
  <nav class="footer-assortment">
      <ul class="footer-assortment-list">
        <li><a href="material.html">Материалы</a></li>
        <li><a href="technology.html">Техника</a></li>
        <li><a href="tool.html">Инструмент</a></li>
        <li><a href="shares.html">Спецпредложения</a></li>
      </ul>
  </nav>
 </div>
 <!-- Самый Нижний слой  -->
 <div class="footer-bottom">
   <p class="footer-copyright">© 2010-2017 Компания "Техномарт"<br>
      Все права защищены<br>
   </p>
 <!--Соц сети.Позже будет ссылка на них  -->
   <ul class="footer social networks">
     <li><a href="#" class="social social-vk">В контакте</a></li>
     <li><a href="#" class="social social-fb">Facebook</a></li>
     <li><a href="#" class="social social-ig">Instagram</a></li>
   </ul>
<!-- Обратная связь и разработка. Как я поняла, что ссылки нужны.-->
   <p class="footer-feedback">Обратная связь:
    <a href="mailto:mail@htmlacademy">mail@htmlacademy.ru</a>
   </p>
   <p class="footer-developer">Разработано -
    <a href="https://htmlacademy.ru">htmlacademy.ru</a>
   </p>
  </div>
</footer>

  </body>
</html>
<!-- проверка для работы с леной в частном порядке -->
