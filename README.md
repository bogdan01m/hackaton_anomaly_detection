# Проект для Обнаружения Аномалий во Временных Рядах

## Описание

Этот проект предназначен для обнаружения аномалий во временных рядах с использованием различных моделей машинного обучения. Веб-приложение позволяет визуализировать данные и аномалии для каждой метрики и модели.

## Структура проекта

- `app.py`: Основное Streamlit приложение.
- `server.py`: Flask сервер для обработки запросов.
- `generate_anomalies.py`: Скрипт для генерации данных с аномалиями.
- `requirements.txt`: Файл с зависимостями проекта.
- `styles.css`: CSS стили для оформления приложения.
- `Dockerfile`: Dockerfile для создания образа Docker.
- `docker-compose.yml`: Файл для запуска контейнера Docker.

## Установка и запуск

### Локальный запуск

1. Установите зависимости:

   ```bash
   pip install -r requirements.txt
