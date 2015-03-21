# Разговорный бот на PHP для Вконтакте
##Установка:
![ID бота](http://i2.wp.com/i.gyazo.com/7cd78815452ddf729e14815e4c0efb72.png?resize=625%2C43)
* 1. Зарегистрируйтесь на сайте iii.ru и создайте себе "инфа". Используйте его номер в скрипте.
* 2. Импортируйте `dump.sql` в свою базу данных
* 3. Переименуйте `config.sample.php` в `config.php` предварительно изменив данные для коннекта к базе данных
* 4. Создайте приложение для ВК 
* 5. Вставте свой `APP_ID` и `APP_SECRET` в `config.php`
* 6. Получите "долгоиграющий" access token для работы с `VK API` с помощью ссылки - [получить token](https://oauth.vk.com/authorize?client_id=4798482&redirect_uri=http://api.vk.com/blank.html&scope=offline,messages,friends,status,wall&display=page&response_type=token). Естественно вы можете отредактировать ссылку и использовать свои данные изменив токен на временный.
* 7. Установить зависимости через Composer `composer.phar install`
* 8. Пользуйтесь запустив` `index.php`

Если добавить `update.php` в Крон, то бот будет постоянно онлайн