<!DOCTYPE html>
<meta charset="UTF-8">

   <head>
    <title>Выполнение Заданий по HTML</title>
    
</head>
<body>
<body style="background-color: lightblue;">
    <section>
        <h1>Задания по HTML</h1>
        <h2>Задание 1: Три вида списков</h2>
        <h3>Маркированный список:</h3>
        <ul>
            <li>Пункт первый (без нумерации)</li>
            <li>Пункт второй</li>
        </ul>
        <h3>Нумерованный список:</h3>
        <ol>
            <li>Шаг один (с нумерацией)</li>
            <li>Шаг два</li>
        </ol>
        <h3>Список определений:</h3>
        <dl>
            <dt>HTML</dt>
            <dd>Язык гипертекстовой разметки.</dd>
        </dl>
        <hr>
    </section>

    <section>
        <h2>Задание 2: Словарь терминов (Список определений)</h2>
        <dl>
            <dt>Web server</dt>
            <dd>Сервер, хранящий и пересылающий HTML-документы...</dd>
            <dt>HOME PAGE</dt>
            <dd>«Домашняя страница». Головная, начальная страница...</dd>
            <dt>CSS</dt>
            <dd>Cascading Style Sheets - Каскадные таблицы стилей.</dd>
        </dl>
        <hr>
    </section>

    <section>
        <h2>Задание 3: Заголовки с выравниванием</h2>
        <h1 style="text-align: center;">Главный Заголовок (По центру)</h1> 
        <h2 style="text-align: left;">Подзаголовок (По левому краю)</h2>
        <h3 style="text-align: right;">Раздел (По правому краю)</h3>
        <hr>
    </section>
    
    <section>
        <h2>Элементы форматирования</h2>
        <p>
            Фрагмент, выделенный <b style="font-weight: bold;">полужирным шрифтом</b>. 
            <br>
            Фрагмент, выделенный <i>курсивом</i>. 
            <br>
            Фрагмент, выделенный <span style="font-size: large;">увеличенным шрифтом</span>.
        </p>
        <hr>
    </section>

    <section id="zadanie4">
        <h2>Задание 4: Гиперссылки</h2>
        <p><b>Внутренний переход:</b> <a href="#zadanie6">Перейти к Заданию 6</a></p>
        <p><b>Загрузка файла:</b> <a href="document.pdf" download>Загрузить файл (должен существовать)</a></p>
        <p><b>Внешняя страница:</b> <a href="https://www.google.com" target="_blank">Перейти на Google</a></p>
        <hr>
    </section>

    <section>
        <h2>Задание 5: Таблица и Изображения</h2>
        <h3>Фрагмент таблицы:</h3>
        <table border="1" style="width: 50%; border-collapse: collapse;">
            <tr align="center">
                <th colspan="3">Это таблица</th>
            </tr>
            <tr align="center">
                <th>Это</th>
                <th>ячейки</th>
                <th>для</th>
            </tr>
            <tr align="center">
                <th colspan="3">данных</th>
            </tr>
        </table>
        
        <h3>Изображения (Последовательно и Мозаикой):</h3>
        <p>Изображения: <img src="https://i.pinimg.com/originals/16/14/29/16142922ea01d6b8cef9a139b7ff1471.jpg" alt="Изображение 1" style="width: 100px;"> <img src="https://i.pinimg.com/736x/d4/37/59/d43759688a194a29f0523b65ecd61da7.jpg" alt="Изображение 2" style="width: 100px;"></p>
        <hr>
    </section>

    <section id="zadanie6">
        <h1 style="color: blue;">Задание 6: Итоговая Страница (Тематика: Основы HTML)</h1>
        
        <h2>Пояснение: Заголовки и Параграфы</h2>
        <p>Страница имеет главный заголовок и подзаголовки для разделения контента.</p>
        
        <h2>Пояснение: Все виды списков</h2>
        <ol><li>Нумерованный список</li></ol>
        <ul><li>Маркированный список</li></ul>
        <dl><dt>Список определений</dt><dd>Термин и его описание.</dd></dl>
        
        <h2>Пояснение: Таблица</h2>
        <table border="1"><tr><td>Пример</td><td>Таблицы</td></tr></table>
        
        <h2>Пояснение: Гиперссылки</h2>
        <p>Проверка работы всех видов ссылок:</p>
        <p><b>E-mail:</b> <a href="mailto:roteys01@gmail.com">Написать мне</a></p>
        <p><b>Внешняя:</b> <a href="https://youtu.be/j-iheFkstFQ?si=FyyucTZeZBCJm7lY" target="_blank">Открыть Google</a></p>
    </section>

</body>
</html>
