# Articles Listing

### Requirements
 - PHP >= 7.4 
 - PDO

### Установка

1. Клонируйте данный репозиторий.

2. Установите зависимости композера:
```sh
$ composer install
```
3. Сгенерируйте ключ приложения:
```sh
$ php artisan key:generate
```
 
4. Запустите выполнение миграций: 
```sh
$ php artisan migrate
```

5. Запустите выполнение сидеров:
```sh
$ php artisan db:seed
```

6. Установите зависимости npm:
```sh
$ npm install
```

7. Соберите frontend приложения: 
```sh
$ npm run prod
```
