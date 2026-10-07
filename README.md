# vikifitmeals

Приложение с рецептами. Работает как сайт и ставится на экран телефона.

## Как выложить
1. На github.com создайте репозиторий `vikifitmeals` (Public).
2. Add file → Upload files: загрузите ВСЕ файлы и папку `photos` (папку можно перетащить целиком или загрузить файл из неё отдельно, указав путь `photos/...`).
3. Settings → Pages → Source: Deploy from a branch, ветка `main`, папка `/ (root)` → Save.
4. Адрес: https://ВАШ_ЛОГИН.github.io/vikifitmeals/

## Как добавить рецепт
Откройте `recipes.js`, скопируйте блок рецепта, поменяйте текст, положите фото в `photos/` и загрузите на GitHub. В `sw.js` поднимите номер в `CACHE` и добавьте фото в список ASSETS.

## Файлы
- `index.html` — приложение
- `recipes.js` — рецепты и ссылки (сайт, Instagram, Telegram)
- `cover.jpg` — обложка, `photos/` — фото блюд
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` — значок
- `sw.js` — работа без интернета
