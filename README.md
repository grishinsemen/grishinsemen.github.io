# grishinsemen.github.io

Личный сайт Семёна Гришина, младшего системного аналитика. Живёт на GitHub Pages: **https://grishinsemen.github.io/**

## Что внутри

Одна статическая страница без сборки и зависимостей.

```
.
├── index.html   # вся страница: разметка и стили
└── README.md
```

- Тёмная и светлая тема подхватываются из настроек системы.
- Шрифты Unbounded и Manrope подгружаются с Google Fonts, без них работает системный.
- Блок «Как я подхожу к задаче» работает на нативных `<details>`, JavaScript и картинок нет.

## Запуск локально

```bash
git clone https://github.com/grishinsemen/grishinsemen.github.io.git
cd grishinsemen.github.io
python -m http.server 8000
```

Открыть http://localhost:8000. Можно и просто открыть `index.html` в браузере.

## Публикация

Репозиторий с именем `<логин>.github.io` публикуется автоматически.
В **Settings → Pages** должно стоять: *Source: Deploy from a branch*, ветка `main`, папка `/ (root)`.
После `git push` сайт обновляется за одну-две минуты.

## Связанное

- Pet-проекты по анализу данных: [grishinsemen/Pet-projects](https://github.com/grishinsemen/Pet-projects)
- Связаться: [Telegram](https://t.me/samuellg), grishinsemen@yandex.ru
