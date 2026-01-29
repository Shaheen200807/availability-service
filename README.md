# Сервис бронирования аудиторий (Service A)

Микросервис для создания бронирований аудиторий с проверкой доступности через внешний API.

## 🚀 Технологии

- Django 5.x
- Django REST Framework
- Python 3.10+
- SQLite (по умолчанию)

## 📋 Endpoints

### Веб-интерфейс
- `GET /` - Форма создания бронирования
- `GET /bookings/` - Список всех бронирований

### API
- `POST /api/bookings/create/` - Создать бронирование
- `GET /api/bookings/list/` - Получить список бронирований
- `GET /api/bookings/health/` - Проверка работы сервиса
- `GET /api/bookings/check-service-b/` - Проверка доступности Сервиса B

## 📦 Формат запроса для создания бронирования
```json# booking-service
