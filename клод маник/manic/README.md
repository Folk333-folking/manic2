# Nude Studio — сайт маникюрного салона (Go + SQLite)

Запуск:  go run .   →  http://localhost:8080   (админка: /admin.html)

Переменные окружения:
- ADMIN_LOGIN, ADMIN_PASSWORD — первый администратор (если пароль не задан, он печатается в консоль один раз)
- TELEGRAM_BOT_TOKEN, TELEGRAM_CHAT_ID — уведомления администратору о записях и отменах
- MIN_CANCEL_HOURS — за сколько часов клиент ещё может отменить запись (по умолчанию 2)
- DB_PATH (по умолчанию salon.db), TZ_NAME (по умолчанию Europe/Moscow), PORT, COOKIE_SECURE=1 (на https)

Render: Build `go build -o app .`, Start `./app`. Базу на бесплатном тарифе нужно хранить на постоянном диске.
