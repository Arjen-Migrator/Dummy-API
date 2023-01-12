# Dummy-API

WIP

## Оглавление

1. [Описание проекта](#описание-проекта)
2. [Майнд-карта](#майнд-карта)
3. [Тест-кейсы](#тест-кейсы)
4. [Баг-репорты](#баг-репорты)
5. [Коллекция POSTMAN](#коллекция-postman)
6. [Автотесты](#автотесты)

## Описание проекта

http://dummyapi.io/ Данный сайт представляет собой сервис для тестированию API. 

Для выполнения запросов необходим app-id, который автоматически выдается после авторизации на сайте.

### User
___
### GET /user

Возвращает список пользователей, отсортированный по дате регистрации.
- доступен query params для вывода определенной страницы.
- доступен query params для отображения определенного числа пользователей на странице.


___
### GET /user/:id

Возвращает данные пользователя с указанным идентификатором.




___
### POST /user/create

Создает нового пользователя. Возвращает данные созданного пользователя.

В теле запроса обязательными являются следующие поля:
- firstName
- lastName
- email


___
### PUT /user/:id

Заменяет данные пользователя с указанным идентификатором. Возвращает обновленные данные.

В теле запроса указать только данные для замены. Email изменять запрещено.

___
### DELETE /user/:id

Удаляет данные пользователя с указанным идентификатором.


___


## Майнд-карта

![Alt-текст](https://i.imgur.com/76MAVP3.png "МК")

Также майнд-карту можно [скачать](https://github.com/Arjen-Migrator/Dummy-API/blob/main/DummyAPI.xmind).

## Тест-кейсы

## Баг-репорты

## Коллекция POSTMAN

## Автотесты
