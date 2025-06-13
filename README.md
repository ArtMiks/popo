# popo
/programming-for-kids/  
│── index.html          (Главная страница)  
│── about.html          (О проекте)  
│── materials.html      (Материалы)  
│── contacts.html       (Контакты)  
│── css/  
│   └── style.css       (Стили)  
│── js/  
│   └── script.js       (Скрипты)  
│── images/             (Изображения)  
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Программирование для детей</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="logo">Программируем с детьми!</div>
        <nav>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="about.html">О проекте</a></li>
                <li><a href="materials.html">Материалы</a></li>
                <li><a href="contacts.html">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Учим детей программировать весело!</h1>
            <p>Интерактивные уроки, игры и задания для детей 7-12 лет.</p>
            <button onclick="location.href='materials.html'">Начать обучение</button>
        </section>

        <section class="features">
            <div class="feature">
                <h3>Scratch</h3>
                <p>Создаём первые игры с блоками.</p>
            </div>
            <div class="feature">
                <h3>Python</h3>
                <p>Простые программы на языке Python.</p>
            </div>
            <div class="feature">
                <h3>Robotics</h3>
                <p>Программируем роботов.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Программирование для детей. Все права защищены.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>О проекте | Программирование для детей</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="logo">Программируем с детьми!</div>
        <nav>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="about.html">О проекте</a></li>
                <li><a href="materials.html">Материалы</a></li>
                <li><a href="contacts.html">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="about">
            <h1>О нашем проекте</h1>
            <p>Мы помогаем детям младшего школьного возраста освоить основы программирования в игровой форме.</p>
            <p>Наша цель — сделать обучение увлекательным и доступным.</p>
            <img src="images/kids-coding.jpg" alt="Дети программируют">
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Программирование для детей. Все права защищены.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Материалы | Программирование для детей</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="logo">Программируем с детьми!</div>
        <nav>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="about.html">О проекте</a></li>
                <li><a href="materials.html">Материалы</a></li>
                <li><a href="contacts.html">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="materials">
            <h1>Учебные материалы</h1>
            <div class="material-item">
                <h3>Scratch для начинающих</h3>
                <p>Видеоуроки и задания.</p>
                <a href="#">Скачать</a>
            </div>
            <div class="material-item">
                <h3>Python в Minecraft</h3>
                <p>Программируем в игре.</p>
                <a href="#">Скачать</a>
            </div>
            <div class="material-item">
                <h3>Робототехника Lego</h3>
                <p>Собираем и программируем.</p>
                <a href="#">Скачать</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Программирование для детей. Все права защищены.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Контакты | Программирование для детей</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="logo">Программируем с детьми!</div>
        <nav>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="about.html">О проекте</a></li>
                <li><a href="materials.html">Материалы</a></li>
                <li><a href="contacts.html">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="contacts">
            <h1>Свяжитесь с нами</h1>
            <form>
                <input type="text" placeholder="Ваше имя">
                <input type="email" placeholder="Email">
                <textarea placeholder="Ваше сообщение"></textarea>
                <button type="submit">Отправить</button>
            </form>
            <div class="contact-info">
                <p>Email: kids-coding@example.com</p>
                <p>Телефон: +7 (123) 456-78-90</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Программирование для детей. Все права защищены.</p>
    </footer>
</body>
</html>
/* Общие стили */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #4CAF50;
    color: white;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}

/* Главная страница */
.hero {
    text-align: center;
    padding: 3rem 0;
    background: #f4f4f4;
}

.features {
    display: flex;
    gap: 2rem;
    margin-top: 2rem;
}

.feature {
    background: #e2e2e2;
    padding: 1rem;
    border-radius: 5px;
}

/* О проекте */
.about img {
    max-width: 100%;
    height: auto;
}

/* Материалы */
.material-item {
    background: #f4f4f4;
    padding: 1rem;
    margin-bottom: 1rem;
    border-radius: 5px;
}

/* Контакты */
.contacts form {
    max-width: 500px;
    margin: 0 auto;
}

.contacts input, .contacts textarea {
    width: 100%;
    padding: 0.5rem;
    margin-bottom: 1rem;
}

.contacts button {
    background: #4CAF50;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}
// Можно добавить анимации или обработку форм
document.querySelector('form')?.addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Сообщение отправлено! Мы скоро свяжемся с вами.');
});
