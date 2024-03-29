# job4j_fast_food_delivery

* [Описание](#описание)
* [Технологии](#технологии)
* [Функционал](#функционал)

## Описание
REST-сервис, через который курьеры доставляют готовые заказы.
Является частью проекта [job4j_fast_food](https://github.com/hasover/job4j_fast_food).

## Технологии
* Spring Boot (Web, Data)
* Apache Kafka
* PostgreSQL
* Liquibase
* Maven

## Функционал

Сервис определяет конечную точку `/deliveries`, с которой можно производить следующие операции:

- GET запрос для получения списка ожидающих доставки заказов.
- POST запрос для взятия заказа в обработку.
- PATCH запрос для обновления статуса заказа.