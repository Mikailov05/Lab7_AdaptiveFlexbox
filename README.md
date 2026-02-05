Лабораторная работа №7. Адаптивная верстка: Flexbox
Цель работы
Освоить современные технологии CSS-разметки — Flexbox.

Теоретическая часть
Адаптивная верстка — подход к созданию веб-страниц, при котором дизайн и контент автоматически подстраиваются под размер экрана устройства.

Flexbox — одномерная система компоновки для размещения элементов в строку или столбец.

Основные понятия Flexbox
Flex-контейнер — родительский элемент с display: flex

Flex-элементы — дочерние элементы внутри контейнера

Ключевые свойства Flexbox
flex-direction — направление элементов (row, column, row-reverse, column-reverse)

justify-content — выравнивание по главной оси

align-items — выравнивание по поперечной оси

flex-wrap — перенос элементов (nowrap, wrap, wrap-reverse)

gap — отступы между элементами

flex-grow, flex-shrink, flex-basis — управление размером элементов

align-self — индивидуальное выравнивание элемента

Практическая часть
Создание рабочей директории
Откройте VS Code, создайте новое окно.

Создайте папку Lab7_Adaptive_FIO (где FIO — ваша фамилия).

Создайте файлы:

index.html

styles.css

README.md

Создайте папку img для скриншотов.

Инициализация Git-репозитория
Инициализируйте репозиторий:

bash
git init -b main
Добавьте файлы в индекс:

bash
git add .
Создайте первый коммит:

bash
git commit -m "Initial commit"
Подключение к GitHub
Создайте публичный репозиторий на GitHub: Lab7_AdaptiveFlexbox

Привяжите локальный репозиторий:

bash
git remote add origin <URL_вашего_репозитория>
git push -u origin main
Базовая структура HTML
html
<!DOCTYPE html>
<html lang="ru-RU">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Адаптивная верстка: Flexbox и Grid</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Лабораторная работа №7</h1>
    <p>Изучаем Flexbox и Grid</p>
</body>
</html>
Примеры работы с Flexbox
Навигационное меню — горизонтальное выравнивание ссылок

Карточки товаров — адаптивная сетка с переносом

Центрирование элемента — использование justify-content и align-items

Самостоятельная работа
Создайте скриншоты для каждого свойства Flexbox и сохраните в папку img.

Сверстайте страницу по образцу, используя только Flexbox.

Оформите README.md с описанием выполненной работы.

Команды для отправки работы
bash
git add .
git commit -m "Added complete README for Lab7"
git push
