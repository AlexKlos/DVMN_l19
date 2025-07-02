# Видео-плеер на HTML, JS и Font Awesome

## Описание
Простой видеоплеер, стилизованный с помощью Font Awesome.

## Структура проекта
```
video-player/
├── .git/
├── dist/
├── font-awesome-4.7.0/
│   └── css/
│       └── font-awesome.min.css
├── venv/
├── favicon.png
├── index.html
├── player.js
└── .gitignore
```

## Используемые технологии
- HTML5
- CSS (встроенные стили)
- JavaScript (jQuery + Playable.js)
- Font Awesome 4.7
- favicon (иконка страницы)

## Как запустить
1. Установите Python-пакет livereload:
   ```
   pip install livereload
   ```
2. Запустите сервер:
   ```
   livereload dist
   ```
3. Откройте `http://127.0.0.1:35729/` в браузере.

## Примечание
- Font Awesome подключается локально.
- Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).
- Ссылка на сайт с плеером - [GitHub Pages](https://alexklos.github.io/DVMN_l19/)
