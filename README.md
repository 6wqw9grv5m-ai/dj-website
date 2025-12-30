<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Сергей Ламбрианиди | DJ Lambriq</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #000;
        color: #fff;
        scroll-behavior: smooth;
    }

    /* HERO */
    .hero {
        height: 100vh;
        background: url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4') center/cover no-repeat;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-align: center;
        text-shadow: 0 0 25px rgba(0,0,0,.7);
        padding: 0 20px;
    }
    .hero h1 {
        font-size: 60px;
        margin: 0;
        animation: fadeIn 2s;
    }
    .hero p {
        font-size: 22px;
        opacity: .9;
    }

    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    section {
        padding: 60px 20px;
        max-width: 900px;
        margin: auto;
    }

    h2 {
        font-size: 36px;
        margin-bottom: 15px;
    }

    /* Stats */
    .stats {
        display: flex;
        justify-content: space-between;
        gap: 20px;
        flex-wrap: wrap;
        text-align: center;
    }
    .stats div {
        flex: 1;
        min-width: 150px;
        font-size: 32px;
        font-weight: bold;
    }
    .stats div span {
        display: block;
        font-size: 16px;
        opacity: .6;
        font-weight: normal;
    }

    /* Links */
    .links a {
        display: block;
        background: #fff;
        color: #000;
        padding: 15px;
        border-radius: 8px;
        text-align: center;
        font-size: 18px;
        text-decoration: none;
        margin-bottom: 10px;
        font-weight: bold;
    }

    .gallery img {
        width: 100%;
        border-radius: 10px;
        margin-bottom: 15px;
    }

    footer {
        text-align: center;
        padding: 40px;
        opacity: .5;
    }
</style>
</head>

<body>

<!-- HERO -->
<div class="hero">
    <h1>СЕРГЕЙ ЛАМБРИАНИДИ</h1>
    <p>DJ • Producer • Performer</p>
</div>

<!-- ABOUT -->
<section id="about">
    <h2>Обо мне</h2>
    <p>
        Позвольте представить талантливого ди-джея, который стал настоящей сенсацией в мире ивент-мероприятий.
        Проект гастролирует по России и за её пределами: Египет, Турция, Таиланд, страны СНГ.
        Призёр Adrenaline Rush FMX. Выступал для МТС, ЭТМ, Лукойл, Газпром, СургутНефтегаз, LOTI.
    </p>

    <p>
        На главных сценах Дня города в Муроме, Ялте, Екатеринбурге, Когалыме.
        Участник мировых фестивалей: Лига Диджеев 2024, Movida Corona International 2013,
        Sochi Music Weekend 2017.
    </p>

    <p>
        Как резидент Bonfire Records, Lambriq работает с передовыми продюсерами мирового уровня.
        Его треки собрали более миллиона прослушиваний на Spotify. Поддержка Ummet Ozcan, KYGO,
        Mahmut Orhan и Dancing Astronaut подтверждает его уровень и стиль.
    </p>
</section>

<!-- STATISTICS -->
<section id="stats">
    <h2>Цифры</h2>
    <div class="stats">
        <div>10<span>Стран</span></div>
        <div>10<span>Лет опыта</span></div>
        <div>100<span>Компаний</span></div>
    </div>
</section>

<!-- MEDIA -->
<section id="media">
    <h2>Медиа</h2>
    <div class="links">
        <a href="https://disk.yandex.ru/a/7WijMuSEcZGA9w" target="_blank">ФОТО</a>
        <a href="https://disk.yandex.ru/a/BWS6HFPN-wrwtA" target="_blank">ВИДЕО</a>
        <a href="https://disk.yandex.ru/d/lS_bk-4WbydX9A" target="_blank">АУДИО</a>
    </div>
</section>

<footer>
    © 2025 Sergey Lambriq — All rights reserved
</footer>

</body>
</html> 
index.html
