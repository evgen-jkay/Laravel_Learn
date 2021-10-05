![Logo](public/frak.png)
---
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/evgen-jkay/frakvann/Laravel)
![GitHub](https://img.shields.io/github/license/evgen-jkay/frakvann)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/evgen-jkay/frakvann)
![GitHub issues](https://img.shields.io/github/issues/evgen-jkay/frakvann)

![GitHub Repo stars](https://img.shields.io/github/stars/evgen-jkay/frakvann?style=social)
![GitHub forks](https://img.shields.io/github/forks/evgen-jkay/frakvann?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/evgen-jkay/frakvann?style=social)

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/evgen-jkay/frakvann)
![GitHub last commit](https://img.shields.io/github/last-commit/evgen-jkay/frakvann)
![GitHub top language](https://img.shields.io/github/languages/top/evgen-jkay/frakvann)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/evgen-jkay/frakvann)
---
## Настройка:
1. Измените файл `.env.example` на `.env`.
2. В файле `.env` измените параметры для подключения к БД на свои:
```apacheconf
DB_HOST=127.0.0.1           // Host
DB_PORT=3306                // Port DB
DB_DATABASE=frakvann        // DB name
DB_USERNAME=root            // Login DB
DB_PASSWORD=                // Password DB
```
3. Измените так же параметры 
```apacheconf 
APP_NAME=Laravel
APP_URL=http://localhost
```
4. Для установки БД нужно запустить миграцию:
```apacheconf
php artisan migrate
```
> После установки миграции у Вас будет чистая база данных со всеми нужными таблицами.

## Сделано:
- [x] `v0.1` Создание проекта, бд, репозитория.
- [x] `v0.2` Регистрация/Авторизация 
- [x] `v0.3` Роли пользователей

## TODO
- [ ] Админ панель

> Данный проект в стадии разработки и доработки

<evgenlandarenko@gmail.com>
