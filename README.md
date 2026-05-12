# GREEN-API-Demo
Тестовое_задание DevOps

HTML-страница для демонстрации работы с методами GREEN-API.

## Функционал

Страница позволяет вызывать следующие методы GREEN-API:
- **getSettings** - получение настроек инстанса
- **getStateInstance** - получение состояния инстанса
- **sendMessage** - отправка текстового сообщения
- **sendFileByUrl** - отправка файла по URL

## Использование

1. Создайте аккаунт на [GREEN-API](https://green-api.com)
2. Создайте новый инстанс в личном кабинете
3. Отсканируйте QR-код в WhatsApp
4. Откройте HTML-страницу
5. Введите `idInstance` и `ApiTokenInstance` из личного кабинета
6. Нажмите кнопки для вызова методов API

## API методы

| Метод | Описание |
|-------|----------|
| getSettings | Получение текущих настроек инстанса |
| getStateInstance | Получение состояния инстанса |
| sendMessage | Отправка текстового сообщения в WhatsApp |
| sendFileByUrl | Отправка файла по ссылке в WhatsApp |

## Технологии

- HTML5
- CSS3
- JavaScript (Fetch API)

## Ссылки

- [GREEN-API Documentation](https://green-api.com/docs/)
- [getSettings](https://green-api.com/docs/api/account/GetSettings/)
- [getStateInstance](https://green-api.com/docs/api/account/GetStateInstance/)
- [sendMessage](https://green-api.com/docs/api/sending/SendMessage/)
- [sendFileByUrl](https://green-api.com/docs/api/sending/SendFileByUrl/)
