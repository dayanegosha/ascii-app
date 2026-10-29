# .ascii app

архивная версия браузерного конвертера видео в ASCII-анимацию.

актуальная версия находится в репозитории [ascii video studio](https://github.com/dayanegosha/ascii-video-studio). этот репозиторий сохранён для истории.

приложение работает в браузере и не загружает видео на сервер: кадры обрабатываются через Canvas, а результат записывается через MediaRecorder.

## запуск

```sh
npm install
npm start
```

## сборка

```sh
npm run build
```

готовые файлы появятся в `dist/`.

## лицензия

[MIT](LICENSE)
