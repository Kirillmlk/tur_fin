# TUR FIN

Одностраничный сайт на Vue 3 + Vite c настроенными стилями под дизайн.

## Стек

- Vue 3
- Vite
- CSS

## Структура проекта

- `src/App.vue` — основная разметка страницы
- `src/assets/app.css` — все стили проекта
- `src/assets/images` — изображения, используемые на странице
- `src/main.js` — точка входа и подключение глобальных стилей

## Запуск проекта

```bash
npm install
npm run dev
```

Сборка production-версии:

```bash
npm run build
npm run preview
```

## Куда добавлять картинки для README

Чтобы изображения отображались в `README.md`, положи их в папку:

- `docs/images`

Пример:

- `docs/images/preview-1.png`
- `docs/images/preview-2.png`

И вставляй в `README.md` так:

```md
![Главный экран](./docs/images/preview-1.png)
![Футер](./docs/images/preview-2.png)
```

Важно:

- используй относительные пути от корня репозитория;
- не используй пробелы в именах файлов (лучше `kebab-case`);
- после добавления новых изображений не забывай коммитить сами файлы картинок.
