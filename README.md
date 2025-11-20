# Docker Compose Quickstart: Flask + Redis

Простое веб-приложение на Flask с счётчиком посещений в Redis.

## Структура проекта

- `app.py` — код Flask-приложения
- `requirements.txt` — зависимости Python
- `Dockerfile` — сборка образа веб-приложения
- `compose.yaml` и `infra.yaml` — конфигурация Docker Compose

## Как запустить

```bash
git clone https://github.com/твой-username/composetest.git
cd composetest

# Запуск в обычном режиме
docker compose up --build

# Или режим разработки с автоматической синхронизацией кода
docker compose watch
```

![Счётчик увеличивается](media/redis.gif)
