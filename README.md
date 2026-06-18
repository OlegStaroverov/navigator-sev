# Sevastopol Digital Navigator Mini App

Готовая статическая сборка мини-аппа для GitHub Pages.

## Как залить через браузер

1. Открой GitHub.
2. Создай новый репозиторий, например `sevastopol-navigator-miniapp`.
3. Нажми `uploading an existing file`.
4. Перетащи в окно GitHub все файлы и папки из этой папки:
   `C:\Users\PC\Desktop\mini_app_github_upload`
5. Нажми `Commit changes`.
6. Открой `Settings` -> `Pages`.
7. В `Build and deployment` выбери:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
8. Нажми `Save`.

Через 1-3 минуты GitHub выдаст ссылку вида:

`https://USERNAME.github.io/REPOSITORY/`

Эту ссылку потом надо будет поставить в бота как URL мини-аппа.

## Что внутри

- `index.html` - главная страница мини-аппа.
- `404.html` - копия главной страницы для нормальной работы роутинга на GitHub Pages.
- `.nojekyll` - чтобы GitHub Pages не ломал папку `static`.
- `static` - собранные стили, скрипты, шрифты и иконки.
- `region.json` - данные каналов, сервисов и ботов.
