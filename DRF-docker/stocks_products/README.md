# Django REST API Container

Этот проект представляет собой REST API сервер на Django, упакованный в Docker контейнер.

## Запуск проекта

1. Сборка образа:
   ```bash
   docker build -t stocks_product .
   ```

2. Запуск контейнера:
   ```bash
   docker run -p 8000:8000 stocks_product
   ```

