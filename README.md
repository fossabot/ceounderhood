# ceounderhood.ru

Коллективный твиттер предпринимателей и руководителей. Новый автор каждую неделю.

## Старт проекта

    git clone git@github.com:memphys/ceounderhood.git
    cd ceounderhood
    npm install
    npm start

## Проект

* `authors.js` — список авторов
* `stats.js` — генерация статистики
* `test.js` — тесты
* `gulpfile.babel.js` — сборка сайта
* `webpack.config.babel.js` — конфиг для js-bundling
* `package.json`, `.editorconfig`, `.eslintrc`, `.gitignore` — переносимое окружение
* `.travis.yml` — конфиг для тревиса
* `.deploy.sh` — деплой с тревиса
* `README.md`

### Дамп

* `update.js` — апдейт дампа
* `dump/index.js` — получение дампа
* `dump/*.json` — дамп информации об авторах ('tweets', 'info', 'media', 'followers', 'mentions')
* `dump/images/` — дамп изображений авторов
* `helpers/` — хелперы

### Сайт

* `css/` — CSS для сайта
* `layouts/` — Шаблоны для сайта
* `static/` — статические файлы для сайта
* `pages/` — маркдаун страницы на сайте
* `migration/` — миграции для старых проектов

[![Build Status](https://travis-ci.org/memphys/ceounderhood.svg?branch=master)](https://travis-ci.org/memphys/ceounderhood)[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fmemphys%2Fceounderhood.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fmemphys%2Fceounderhood?ref=badge_shield)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fmemphys%2Fceounderhood.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fmemphys%2Fceounderhood?ref=badge_large)