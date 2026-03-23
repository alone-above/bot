# Alone Above — Bot Service

Telegram бот на aiogram 3.x + PostgreSQL (asyncpg).

## Переменные окружения (Railway → Variables)

| Переменная | Описание |
|---|---|
| `BOT_TOKEN` | Токен бота от @BotFather |
| `ADMIN_IDS` | ID администраторов через запятую |
| `MANAGER_ID` | ID менеджера для уведомлений |
| `SUPPORT_USERNAME` | @username поддержки |
| `SHOP_NAME` | Название магазина |
| `KASPI_PHONE` | Номер Kaspi для оплаты |
| `DATABASE_URL` | PostgreSQL internal URL (Railway) |
| `DATABASE_PUBLIC_URL` | PostgreSQL public URL |
| `CRYPTOBOT_TOKEN` | Токен CryptoBot (если используется) |

## Запуск

```
web: python main.py
```
