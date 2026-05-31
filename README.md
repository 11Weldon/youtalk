# YouTalk Blog

Учебный проект — блог сервиса онлайн-психотерапии YouTalk.

## Структура

```
youtalk/
├── blog.html       — страница блога
├── article.html    — страница статьи
├── css/
│   └── style.css   — все стили (БЭМ, адаптив)
├── icons/          — SVG-иконки
├── images/         — папка для фотографий (добавить вручную)
└── README.md
```

## Как запустить

### Вариант 1 — Просто открыть в браузере
Двойной клик на `blog.html` — откроется в браузере. Всё работает без сервера.

### Вариант 2 — VS Code + Live Server (рекомендуется)
1. Установить VS Code: https://code.visualstudio.com
2. Установить расширение **Live Server**
3. Открыть папку `youtalk/` в VS Code
4. ПКМ на `blog.html` → **Open with Live Server**
5. Адрес: `http://127.0.0.1:5500/blog.html`

### Вариант 3 — Python
```bash
cd youtalk
python -m http.server 8080
# Открыть: http://localhost:8080/blog.html
```

## Добавление своих изображений

Положите фото в папку `images/` с именами:
- `card-1.jpg` … `card-8.jpg` — фото для карточек блога
- `article-cover.jpg` — обложка статьи
- `article-inline.jpg` — inline-фото внутри статьи

Если фото нет — автоматически показывается эмодзи-заглушка.
