# .ascii app

Архивная версия браузерного конвертера видео в ASCII-анимацию.

Актуальная версия находится в репозитории [ascii video studio](https://github.com/dayanegosha/ascii-video-studio). Этот репозиторий сохранён для истории.

Приложение работает в браузере и не загружает видео на сервер: кадры обрабатываются через Canvas, а результат записывается через MediaRecorder.

## запуск

```sh
npm install
npm start
```

## сборка

```sh
npm run build
```

Готовые файлы появятся в `dist/`.

## лицензия

[MIT](LICENSE)
