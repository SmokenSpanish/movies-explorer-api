# Movies Explorer (Backend) 

## Описание проекта и функциональность

Проект представляет собой сервис Movies Explorer, в котором можно найти фильмы по запросу и сохранить в личном кабинете.

## Используемые технологии

* __`Node.js`__
* __`Express.js`__
* __`MongoDB`__

## Роуты

* __`GET`__ `/users/me` — возвращает информацию о пользователе (`email и имя`);
* __`PATCH`__ `/users/me` — обновляет информацию о пользователе;
* __`GET`__ `/movies` — все сохранённые пользователем фильмы;
* __`POST`__ `/movies` — создаёт фильм с переданными в теле данными;
* __`DELETE`__ `/movies/movieId` — удаляет сохранённый фильмы по `_id`;
* __`POST`__ `/signup` — создаёт пользователя с переданными в теле данными;
* __`POST`__ `/signin` — возвращает `JWT`, если в теле запроса переданы правильные почта и пароль.
* __`POST`__ `/signout` — удаляет `JWT` из `cookie`;

## Запуск проекта
1. `git clone` [`https://github.com/SmokenSpanish/movies-explorer-api.git`](https://github.com/SmokenSpanish/movies-explorer-api.git)
2. `npm install`
3.`npm run start` — запускает сервер   
4.`npm run dev` — запускает сервер с hot-reload

## Ссылки на проект:
##### Публичный IP-адрес сервера:
* [`178.154.198.78`](http://178.154.198.78);
##### Backend:
* [`https://api.movies.spanish.nomoredomains.rocks`](https://api.movies.spanish.nomoredomains.rocks);
