<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Свадьба Ирины и Павла</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>

    <header>
        <h1>Ирина & Павел</h1>
        <p class="date">6 июня 2025 года</p>
    </header>

    <section class="invitation">
        <p>Этот момент настал! Совсем скоро состоится день нашей свадьбы, и мы будем счастливы, если Вы разделите с нами этот чудесный день!</p>
        <img src="wedding.jpg" alt="Свадебное фото">
    </section>

    <section class="calendar">
        <h2>Свадьба состоится</h2>
        <p class="wedding-date">6 июня 2025 года</p>
    </section>

    <section class="location">
        <h2>Место проведения</h2>
        <p>г. Красный Холм, Народная площадь, 24</p>
        <iframe src="https://www.google.com/maps?q=Красный+Холм,+Народная+площадь,+24&output=embed" width="100%" height="300"></iframe>
    </section>

    <section class="countdown">
        <h2>До свадьбы осталось</h2>
        <p id="timer"></p>
    </section>

    <section class="rsvp">
        <button onclick="openForm()">Подтвердить присутствие</button>
        <form id="rsvpForm" style="display: none;">
            <label>Фамилия, Имя:</label>
            <input type="text" id="name" required>

            <label>Планируете ли Вы присутствовать?</label>
            <select id="attendance">
                <option>Да, с удовольствием</option>
                <option>Нет</option>
            </select>

            <label>Ваши предпочтения:</label>
            <select id="drink">
                <option>Шампанское</option>
                <option>Красное вино</option>
                <option>Белое вино</option>
                <option>Водка</option>
                <option>Виски</option>
            </select>

            <button type="button" onclick="sendEmail()">Отправить</button>
        </form>
    </section>

</body>
</html>
