### Задача 1: API Gateway
API Gateway | Маршрутизация | Аутентификация | HTTPS
------------|---------------|----------------|-------
Kong|+|+|+
Tyk.io|+|+|+
Express Gateway|+|+|+
KrakenD|+|+|+
AWS API Gateway|+|+|+
Google Cloud API Gateway|+|+|+

Это не полноый список API Gateway, на сегодняшний момент большинство API Gateway обладают необходимыми характеримтиками. Я думаю что можно рассмотреть несколько вариантов:
  - некоторые API Gateway можно разместить на стороне облачных ресурсов если с точки зрения безопасности не будет возражении
  - среди opensource решении для сервисов с чувствительной информацией можно выделить Kong, так как в opensource наличие большого сообщества играет важную роль  


### Задача 2: Брокер сообщений
Брокер|Кластеризация|Хранение|Скорость|Форматы|Права|Простота
------|-------------|--------|--------|-------|-----|---------
Redis|+|-|+|+|+|+
RabbitMQ|+|+|+|+|+|+|
Kafka|+|+|+|+|+|+|
Apollo|-|+|-|-|+|+|

Иcходя из таблицы я бы сделал выбор в пользу  Kafka, так как он более производителен и сообщетсво у него обширное- будет проще сопровождать.
