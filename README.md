# Портфолио — Марат Мурзагалиев

Продуктовый дизайнер из Москвы. Сайт-портфолио: статичный HTML без сборки.

## Что внутри

| Файл | Что это |
|---|---|
| `index.html` | Главная: работы, концепты, стек, обо мне |
| `waste-pickup.html` | Кейс: вывоз мусора для частного дома |
| `rakurs-studio.html` | Кейс: Rakurs Studio |
| `memento.html` | Кейс: Memento |
| `twist-ui.html` | Кейс: Twist UI |
| `cv.pdf` | Резюме, открывается по кнопке CV |
| `assets/` | Картинки, видео, шрифт, архив Memento |
| `vercel.json` | Настройки для Vercel: чистые URL и кэш для `assets/` |

## Как запустить локально

Открыть `index.html` в браузере. Кейсы открываются в попапе через iframe, поэтому в некоторых браузерах с `file://` удобнее поднять простой сервер:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Деплой

Подходит любой статический хостинг. На Vercel: импортировать репозиторий, фреймворк — Other, без команды сборки.

Видео в части концептов и в кейсе вывоза мусора подгружаются с Vimeo, живое демо Twist UI — с twist-ui.vercel.app.

## Контакты

Telegram [@martgarcon](https://t.me/martgarcon) · [miefrzevv@gmail.com](mailto:miefrzevv@gmail.com)
# portfoliov2
