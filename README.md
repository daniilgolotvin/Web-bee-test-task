

# Webbe test 

## Описание

Проект представляет собой ознакомительную страницу, включающую интерактивную карту с маркером местоположения, таймер посещения страницы и другие элементы. Страница создана с использованием HTML, CSS и JavaScript, а также Yandex Maps API для отображения карты.

## Функциональность

- **Интерактивная карта**: Отображает карту с маркером местоположения пользователя. При отсутствии доступа к геопозиции отображается карта Москвы.
- **Таймер посещения страницы**: Отсчитывает время, проведенное пользователем на странице.
- **Адаптивный интерфейс**: Страница адаптируется под различные устройства благодаря медиазапросам.

## Установка

1. Склонируйте репозиторий:
    ```sh
    https://github.com/daniilgolotvin/MyStudyProject.git
    ```

2. Перейдите в директорию проекта:
    ```sh
    cd your-repo
    ```

3. Откройте файл `index.html` в вашем браузере.

## Структура проекта

- `index.html` - Главная HTML-страница проекта.
- `index.css` - Основной файл стилей CSS.
- `components/map.js` - JavaScript файл для работы с картой.
- `components/time.js` - JavaScript файл для таймера.
- `components/activity.js` - JavaScript файл для других интерактивных элементов страницы.
- `images/` - Директория с изображениями и иконками, используемыми на странице.

## Использование

### Интерактивная карта

На странице присутствует кнопка "Map", при нажатии на которую отображается карта с маркером. По умолчанию карта отображает центр Москвы. Если пользователь предоставляет доступ к своей геопозиции, маркер будет установлен на его местоположении.

### Таймер посещения

Таймер начинает отсчет времени с момента загрузки страницы и показывает, сколько времени пользователь провел на сайте.

### Адаптивный интерфейс

Страница адаптируется под размеры экрана устройства, что делает ее удобной для просмотра как на настольных компьютерах, так и на мобильных устройствах.

## Зависимости

Проект использует следующие внешние библиотеки и API:

- [Yandex Maps API](https://tech.yandex.ru/maps/doc/jsapi/2.1/quick-start/index-docpage/)


## Авторы

- **Daniil Golotvin** - Основной разработчик.
