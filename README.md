# medstudent1
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Качественное медицинское образование</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffffff;
            margin: 0;
            padding: 0;
            color: #333;
            animation: fadeIn 1s ease-in-out;
        }

        header {
            background-color: #ff6347; /* Яркий оранжевый */
            color: white;
            text-align: center;
            padding: 40px 0;
            animation: slideInDown 1s ease-out;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        header p {
            font-size: 18px;
            font-weight: bold;
        }

        nav {
            background-color: #ff4500; /* Яркий красный */
            padding: 12px 0;
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }

        nav a {
            color: white;
            margin: 0 20px;
            font-size: 18px;
            text-decoration: none;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffeb3b; /* Желтый цвет для акцентов */
        }

        section {
            padding: 50px 20px;
            margin: 20px;
        }

        footer {
            background-color: #ff4500; /* Яркий красный */
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        .content {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            animation: fadeIn 2s ease-in-out;
        }

        .testimonial, .resources {
            background-color: #f9f9f9;
            padding: 30px;
            border-radius: 10px;
            animation: fadeIn 2s ease-in-out;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .contact-form {
            background-color: #ffffff;
            padding: 25px;
            border-radius: 10px;
            animation: fadeIn 2.5s ease-in-out;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .payment-btn {
            background-color: #ff6347; /* Яркий оранжевый */
            color: white;
            padding: 15px 25px;
            border: none;
            border-radius: 8px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .payment-btn:hover {
            background-color: #ff5722; /* Более насыщенный оранжевый */
        }

        /* Анимации */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideInDown {
            from {
                transform: translateY(-100%);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Стиль для вставки видео и аудио */
        .media-container {
            margin-top: 20px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
        }

        video, audio {
            width: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }

        input[type="file"] {
            padding: 5px;
            margin-top: 10px;
        }

        .upload-btn {
            background-color: #ff6347; /* Оранжевый */
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        .upload-btn:hover {
            background-color: #ff5722; /* Более насыщенный оранжевый */
        }

        /* Стиль для формы отзывов */
        .review-form {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }

        .review-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            height: 150px;
        }

        .review-form button {
            background-color: #ff6347; /* Оранжевый */
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        .review-form button:hover {
            background-color: #ff5722; /* Более насыщенный оранжевый */
        }

    </style>
</head>
<body>

<header>
    <h1>Качественное медицинское образование</h1>
    <p>Доступ к знаниям, инновационные методы обучения и цифровые инструменты для студентов и врачей</p>
</header>

<nav>
    <a href="#home">Главная</a>
    <a href="#courses">Курсы</a>
    <a href="#news">Новости</a>
    <a href="#reviews">Отзывы</a>
    <a href="#contact">Контакты</a>
</nav>

<section id="home">
    <h2>Быстрое и доступное медицинское образование</h2>
    <p>Мы предоставляем доступ к лучшим ресурсам для студентов медиков, резидентов и врачей. Мы поможем вам найти сайты, источники и приложения для повышения квалификации, научных исследований, мотивации, а также методики для успешного карьерного роста.</p>
</section>

<section id="courses">
    <h2>Курсы для студентов медицинских вузов</h2>
    <p>Для студентов медицинских вузов существует множество курсов, которые помогут в освоении ключевых навыков, углублении знаний и расширении практического опыта. Эти курсы охватывают широкий спектр тем, от основ медицины до специализированных областей.</p>

    <h3>1. Курсы по основам медицины</h3>
    <ul>
        <li><strong>Анатомия:</strong> изучение структуры человеческого тела, его органов и систем.</li>
        <li><strong>Физиология:</strong> понимание того, как работают различные системы организма.</li>
        <li><strong>Биохимия:</strong> основы биохимических процессов в организме.</li>
        <li><strong>Фармакология:</strong> изучение лекарственных препаратов, их механизмов действия, показаний и побочных эффектов.</li>
    </ul>
    <!-- Место для добавления видео, аудио и файлов -->
    <div class="media-container">
        <h4>Добавить материал по теме "Курсы по основам медицины"</h4>
        <label for="video-upload">Загрузить видео:</label>
        <input type="file" id="video-upload" accept="video/*">
        <label for="audio-upload">Загрузить аудио:</label>
        <input type="file" id="audio-upload" accept="audio/*">
        <button class="upload-btn">Загрузить материал</button>
    </div>

    <!-- Добавляйте другие курсы аналогично -->
</section>

<section id="news">
    <h2>Новости о медицине</h2>
    <p>Читайте последние новости из мира медицины, исследования и публикации на ведущих платформах.</p>
    <ul>
        <li><a href="https://pubmed.ncbi.nlm.nih.gov/" target="_blank">PubMed - Открытые публикации в области медицины</a></li>
        <li><a href="https://www.cochranelibrary.com/" target="_blank">Cochrane Library - Протоколы и систематические обзоры</a></li>
    </ul>
</section>

<section id="reviews">
    <h2>Отзывы и опыты</h2>
    <p>Поделитесь своим опытом, отзывами или задайте вопрос! Мы ценим ваше мнение.</p>

    <div class="review-form">
        <h3>Оставить отзыв</h3>
        <form action="#">
            <textarea placeholder="Ваш отзыв..." required></textarea>
            <button type="submit">Отправить отзыв</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Качественное медицинское образование. Все права защищены.</p>
</footer>

</body>
</html>
