# Ventanas Perfect — статическая выгрузка

Статический сайт, сборка не нужна.

## Деплой

1. Перетащить папку `vercel` в Vercel (или загрузить её содержимое в репозиторий).
2. Framework Preset — **Other**, Build Command — пусто, Output Directory — `.`.

Через CLI:

```
npm i -g vercel
cd vercel
vercel --prod
```

## Страницы

- `/` — главная (`index.html`)
- `/setki-plisse` — сетки плиссе (`setki-plisse.html`)

## Состав

- `*.dc.html` — общие компоненты (шапка, футер, кнопка, отзывы, FAQ, примеры работ); подгружаются страницами, лежат рядом с ними
- `support.js`, `image-slot.js` — рантайм (обязательны)
- `img/` — фото и иконки

Шрифты (Rubik, Golos Text) — с Google Fonts.
