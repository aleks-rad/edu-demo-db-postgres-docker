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

### Схема БД

> SQL-скрипт взят с официального сайта postgres (в качестве предметной области выбраны авиаперевозки по России):
[https://www.postgrespro.ru/education/demodb](https://www.postgrespro.ru/education/demodb)

![image](https://user-images.githubusercontent.com/10981830/213874402-99897476-0808-4759-a005-1eaddbb432bd.png)
