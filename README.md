# Yandex Golang Academy - SemiFinal Project: Distributed Calculator
Обновленный проект представляет из себя калькулятор с сохранением маетматического выражения в базу данных. При создании проекта я фокусировался в основном на backend. Backend реализован с помощью Golang, БД - PostgreSQL. Frontend - по базе - HTML, CSS, JS. upd: Все обернуто в Docker.

## Содержание
- [Как запустить приложение?]
- [Работа с приложением]
- [Схема API]
- [Перспективы развития]
- [Контакты]

## Как запустить приложение?

### Этап 0
Проект обернут в Docker, поэтому для установки и запуска нужно скачать [его](https://www.docker.com/products/docker-desktop/) (перейдите по ссылке и установите). Проверить работает ли Docker Engine можно введя в терминал: 
```docker```
(Должен появится список команд)

### Этап 1
Для запуска проекта необходина всего одна команда:
```docker-compose up```
Через некоторое время(до 5-7 минут), выведется лог **server started**. 

### Этап 2
Найдите 