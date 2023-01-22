# edu-demo-db-postgres-docker
Демо postgres БД в докере для практики SQL. Содержит docker-compose для старта контейнера с postgres БД и sql-скрипт для создания схемы БД и наполнения данными таблиц.

### Старт
> Необходимо наличие установленного докера в системе

В корне проекта выполнить команду:

`docker-compose up`

Для доступа к БД можно использовать любой клиент, например **DBeaver**

### Настройки доступа:

- Хост: localhost
- Порт: 5432
- База данных: demo
- Пользователь: postgres
- Пароль: postgres
- Схема: bookings

### Примеры SQL-запросов
Примеры SQL-запросов для данной БД представлены на [wiki-странице](https://github.com/aleks-rad/edu-demo-db-postgres-docker/wiki/%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D1%8B-SQL-%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%BE%D0%B2)

### Схема БД

> SQL-скрипт взят с официального сайта postgres (в качестве предметной области выбраны авиаперевозки по России):
[https://www.postgrespro.ru/education/demodb](https://www.postgrespro.ru/education/demodb)

![image](https://user-images.githubusercontent.com/10981830/213874402-99897476-0808-4759-a005-1eaddbb432bd.png)
