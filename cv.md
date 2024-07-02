# Vsevolod  Adamovich

## Contact information

phone number: +375293271731

telegram: https://t.me/Kranut

LinkedIn: www.linkedin.com/in/vsevolod-adamovich-58408925b

email: sas4sevaadamovich@gmail.com

![avatar image](https://raw.githubusercontent.com/Pro100Sevchanskii/rsschool-cv/gh-pages/1671381101389.jpg)

## About me 

I am 19 years old, I live in Belarus, I am a 3rd year student at the Belarusian State University at the Faculty of Radiophysics and Computer Technology. In the first half of the 1st year I started to learn C++, at the beginning of the second year I started learning frontend, in the middle of the second year I studied a little ux/ui design and worked in Figma, I studied a little react.js, at the end of the second year I learned a little python. I play volleyball for the faculty, I like to play football, I practiced judo, basketball (I went to regional competitions), and I graduated from music school as an external student (specializing in accordion). In general, I am a very active and quite sociable person who wants to connect his life with programming.


## My skills

* C++
* Html, CSS, JS
* FIgma
* A litle Python
* A litle React.js


## Code example 

```
index.html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Family bakery</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="icon" href="/Pictures/logo.svg" type="image/x-icon">
</head>
<body>
    <header class="header container">
        <a href="#about">
            <img src="./Pictures/logo-light.svg" alt="logo-light">
        </a>
        <div class="header-menu">
            <ul class="header-menu-list">
                <li><a href="#about">О нас</a></li>
                <li><a href="#menu">Меню</a></li>
                <li><a href="#order">Заказы</a></li>
            </ul>
            <div>
                +375(**)***-**-**
            </div>
        </div>
    </header>
    <section class="hero container">
        <a name="about"></a>
        <div class="hero-content">
            <h1 class="hero-title">Домашняя выпечка с душой и любовью</h1>
            <p class="hero-description">Свежие булочки из натуральных ингредиентов с бесплатной доставкой прямо к вашему
                столу</p>
            <button class="btn btn-about">Узнать больше</button>
        </div>
        <div class="hero-img">
            <img src="./Pictures/hero.png" alt="hero-bakery">
        </div>
    </section>
    <section class="menu container">
        <a name="menu"></a>
        <h2 class="menu-title">Наше меню</h2>
        <div class="menu-content">
            <div class="menu-item">
                <img src="./Pictures/menu1.png" alt="img-menu-item">
                <div class="menu-inem-content">
                    <h3 class="title-menu-item">Кекс шоколадный</h3>
                    <p class="description-menu-item">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis exercitationem eveniet libero
                        sapiente natus ratione laudantium. Quam illum eaque quia ipsam aliquid, architecto deleniti
                        dicta ipsum provident eos beatae voluptas!
                    </p>
                </div>
            </div>
            <div class="menu-item">
                <img src="./Pictures/menu2.png" alt="img-menu-item">
                <div class="menu-inem-content">
                    <h3 class="title-menu-item">Хлеб домашний</h3>
                    <p class="description-menu-item">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis exercitationem eveniet libero
                        sapiente natus ratione laudantium. Quam illum eaque quia ipsam aliquid, architecto deleniti
                        dicta ipsum provident eos beatae voluptas!
                    </p>
                </div>
            </div>
            <div class="menu-item">
                <img src="./Pictures/menu3.png" alt="img-menu-item">
                <div class="menu-inem-content">
                    <h3 class="title-menu-item">Булочка с корицей</h3>
                    <p class="description-menu-item">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis exercitationem eveniet libero
                        sapiente natus ratione laudantium. Quam illum eaque quia ipsam aliquid, architecto deleniti
                        dicta ipsum provident eos beatae voluptas!
                    </p>
                </div>
            </div>
        </div>
        <button class="btn btn-order">Заказать</button>
    </section>
    <section class="order container">
        <a name="order"></a>
        <div class="order-content">
            <h2 class="title-order">Приём заказов</h2>
            <p>Оставте ваши контактные данные и мы перезвоним вам для согласования деталей заказа</p>
        </div>
        <div class="order-content">
            <form action="url" class="form">
                <input type="text" placeholder="Ваше имя" name="name" class="inp-form">
                <input type="tel" placeholder="Номер телефона" name="phone" class="inp-form">
                <input type="email" placeholder="E-mail" name="email" class="inp-form">
                <input type="submit" value="Отправить" class="btn btn-form">
            </form>
            <div class="agree-cook">
                <input type="checkbox" name="data" class="check-agree">
                <label for="data">Согласен(а) на обработку персональных данных</label>
            </div>
        </div>
    </section>
    <footer class="footer container">
        <img src="./Pictures/logo-dark.svg" alt="logo-dark">
        <div class="social-net">
            <a href="url-inst">
                <img src="./Pictures/instagram.svg" alt="inst">
            </a>
            <a href="url-facebook">
                <img src="./Pictures/facebook.svg" alt="facebook">
            </a>
            <a href="url-twit">
                <img src="./Pictures/twitter.png" alt="twitter">
            </a>
        </div>
    </footer>
</body>
<script src="./script.js"></script>
</html>
style.css
@import url('https://fonts.googleapis.com/css2?family=Inter&family=Montserrat:wght@600&family=Poppins&display=swap');
:root {
    --color-accent: #EE9227;
    --color-light: #f5f5f5;
    --color-dark: #333333;
    --handller-font: "Montserrat", sans-serif;
    --main-font: "Inter", sans-serif;
    --menu-font: "Poppins", sans-serif;
}
body {
    margin: 0;
    font-family: var(--main-font);
    color: var(--color-dark);
    background-color: var(--color-light);
}
h1,
h2 {
    font-family: var(--handller-font);
    color: var(--color-accent);
    font-size: 54px;
}
a {
    text-decoration: none;
    color: var(--color-dark);
}
ul {
    list-style: none;
    padding: 0px;
}
.container {
    padding: 0% 7%;
}
.btn {
    background-color: var(--color-accent);
    color: var(--color-light);
    font-size: 24px;
    padding: 15px 55px;
    border: none;
    border-radius: 16px;
    display: flex;
    justify-content: center;
}
.header,
.footer {
    min-height: 90px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.header-menu {
    display: flex;
    align-items: center;
    width: 50%;
    justify-content: space-between;
}
.header-menu-list {
    display: flex;
    padding: 0px;
    width: 50%;
    justify-content: space-between;
}
.hero,
.menu,
.order {
    min-height: 630px;
}
.hero {
    display: flex;
    align-items: center;
}
.hero-content {
    position: relative;
    float: left;
    z-index: 3;
}
.hero-description {
    width: 55%;
    margin: 50px 0px;
}
.hero-title {
    width: 70%;
}
.hero-img img {
    width: 100%;
}
.her-img {
    width: 55%;
    position: absolute;
    right: 0.5%;
    z-index: 1;
}
.menu {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-direction: column;
    margin-bottom: 55px;
}
.menu-item {
    width: 32%;
    border-radius: 26px;
    border: 1px solid var(--color-accent);
}
.menu-item img {
    width: 100%;
    border-radius: 26px 26px 0px 0px;
}
.menu-item-content {
    padding: 10px 32px;
}
.title-menu-item {
    font-size: 16px;
    color: var(--color-accent);
}
.description-menu-item {
    font-size: 14px;
}
.menu-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 55px;
}
.order {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    padding-top: 60px;
}
.form {
    margin: 55px 0px;
    display: flex;
    flex-direction: column;
}
.inp-form {
    padding: 9px;
    outline: none;
    font-size: 16px;
    background-color: var(--color-light);
    color: #8E8E8E;
    min-height: 30px;
    border: 1px solid;
    border-color: var(--color-light) var(--color-light) var(--color-accent);
    margin-bottom: 50px;
}
.order-content {
    width: 45%;
}
.aree-cook {
    margin-top: 25px;
}
.footer {
    background-color: #584B3C;
}
.social-net {
    display: flex;
    align-items: center;
    width: 13%;
    justify-content: space-between;
}
script.js
let btnOrder = document.querySelector('.btn-order')
let btnAbout = document.querySelector('.btn-about')
let btnForm = document.querySelector('.btn-form')
let checkbox = document.querySelector('.check-agree')
let agree = 0
btnAbout.addEventListener('click', () => {
    alert('Вся информация доступна по номеру телефона')
})
btnOrder.addEventListener('click', () => {
    alert('Чтобы оставить заказ заполните форму')
})
checkbox.addEventListener('click', () => {
    if (agree == 0) {
        agree = 1
    }
    else {
        agree = 0
    }
})
btnForm.addEventListener('click', () => {
    if (agree == 1) {
        alert('Ваши контактные данные приняты, ожидайте звонка')
    }
    else {
        alert('Вы не дали согласие на обработку персональных данных')
    }
})
```


## Experience 
None(


## Education 

1) Belarus State University Radiophysics and Computer Technology faculty (in process)

2) Stepik course with distinction "HTML CSS JS" (complited) (https://stepik.org/cert/2191700?lang=en)

3) Stepik course with distinction "Introduction to Programming (C++)" (complited) (https://stepik.org/cert/2137662?lang=en)

4) Stepik course ""Generation Python": a course for beginners" (in process)


## Languages 

* belarusian (native)
* russian (native)
* english (A2)
