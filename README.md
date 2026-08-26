# Сегментация пользователей для персонализированных маркетинговых акций

## Стек:
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](#)
[![Redash](https://img.shields.io/badge/Redash-FF7964?style=for-the-badge&logo=redash&logoColor=white)](#)


## Данные

Для анализа используются три таблицы:

| Таблица | Содержание | Ключевые поля |
|---|---|---|
| `customers` | Информация о клиентах | `customer_id`, `customer_city`, `created_at` |
| `orders` | История заказов и их статусы | `order_id`, `customer_id`, `order_status`, `order_created_time`, `order_delivered_customer_time` |
| `customer_actions` | События взаимодействия клиентов с магазином | `customer_id`, `event_timestamp`, `event_type`, `order_id`, `product_id` |
