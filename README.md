# A G - Аниме портал

Сайт для просмотра аниме с официальной озвучкой. Создан с использованием HTML, CSS и JavaScript.

## Структура проекта

```
anime-site/
│
├── index.html          # Главная страница
├── catalog.html        # Каталог аниме
├── top.html            # Топ аниме
├── css/
│   └── style.css       # Основные стили
├── js/
│   └── main.js         # JavaScript функционал
├── images/             # Изображения и постеры
│   └── placeholder.jpg
└── anime/              # Страницы отдельных аниме
    └── gurren-lagann.html # Пример страницы аниме
```

## Как добавить новое аниме

1. Создайте новый HTML файл в папке `anime/` по образцу `gurren-lagann.html`
2. Добавьте информацию об аниме (название, описание, рейтинг и т.д.)
3. Добавьте плеер Kodik в блок с классом `player`
4. Добавьте карточку аниме на главную страницу и в каталог

### Пример добавления плеера Kodik

```html
<div class="player">
    <!-- Вставьте код плеера Kodik здесь -->
    <iframe src="https://kodik.info/..." frameborder="0" allowfullscreen></iframe>
</div>
```

## Как изменить стили

Все стили находятся в файле `css/style.css`. Для изменения цветовой схемы можно отредактировать переменные CSS в начале файла:

```css
:root {
    --primary-color: #6a3de8;
    --secondary-color: #9370DB;
    --accent-color: #ff6b6b;
    --dark-bg: #121212;
    --darker-bg: #0a0a0a;
    --light-text: #f5f5f5;
    --dark-text: #333;
    --gray-text: #aaa;
    --card-bg: #1e1e1e;
    --border-radius: 8px;
    --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
}
```

## Контакты

По всем вопросам и предложениям обращайтесь:
- Email: example@example.com
- Telegram: @example 