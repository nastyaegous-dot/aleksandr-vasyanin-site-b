# aleksandr-vasyanin.ru

Готовая статическая версия сайта Александра Васянина.

## Что внутри

- `index.html` — основная страница
- `assets/videos/` — 3 видеоотзыва
- `assets/docs/` — резюме для HR и Executive CV
- `CNAME`, `robots.txt`, `sitemap.xml` — служебные файлы для публикации

## Как опубликовать

1. Загрузить содержимое этой папки на любой статический хостинг: Netlify, Vercel, Cloudflare Pages, GitHub Pages, Timeweb, Beget или другой.
2. В настройках хостинга привязать домен `aleksandr-vasyanin.ru`.
3. У регистратора домена направить DNS на выбранный хостинг.
4. Проверить, что открываются:
   - главная страница
   - `https://aleksandr-vasyanin.ru/robots.txt`
   - `https://aleksandr-vasyanin.ru/sitemap.xml`

## Важно

- Один видеоотзыв сейчас в формате `.mov`: `assets/videos/artemiy-miller.mov`.
- Для максимальной совместимости со всеми браузерами позже лучше перекодировать его в `.mp4`.
- Остальные два видео уже лежат в `.mp4`.
