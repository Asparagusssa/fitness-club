# Дипломный проект "Качалкино"

## Описание

"Качалкино" - это web-приложение, которое предназначено для организации и управления групповыми тренировками в фитнес-центре. Приложение позволяет клиентам бронировать тренировки, а также управлять своими абонементами и балансом.

## Установка

### 1. Клонируйте репозиторий к себе на компьютер и перейдите в него: 
```bash
git clone https://github.com/Asparagusssa/fintess-club.git
```
```bash
cd fitness-club
```
### 2. Установите все необходимые зависимости:
```bash
composer install
npm install
```
### 3. Настройка базы данных:
Переименуйте файл ```.env.example``` в ```.env```. 

Подключите и настройте свою базу данных в файле ```.env```
### 4. Сгенерируйте ключ приложения:
```bash
php artisan key:generate
```
### 5. Выполните миграции для создания таблиц в базе данных: 
```bash
php artisan migrate --seed
``` 
### 6. Запустите проект на вашем локальном компьютере: 
```bash
php artisan serve
npm run dev
```
