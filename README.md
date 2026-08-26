# Сегментация пользователей для персонализированных маркетинговых акций

## Стек:
https://img.shields.io/badge/SQL


## Данные

Для анализа используются три таблицы:

| Таблица | Содержание | Ключевые поля |
|---|---|---|
| `customers` | Информация о клиентах | `customer_id`, `customer_city`, `created_at` |
| `orders` | История заказов и их статусы | `order_id`, `customer_id`, `order_status`, `order_created_time`, `order_delivered_customer_time` |
| `customer_actions` | События взаимодействия клиентов с магазином | `customer_id`, `event_timestamp`, `event_type`, `order_id`, `product_id` |
