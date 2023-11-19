# protos
contract description

### структура
```sso
├── cmd.............. Команды для запуска приложения и утилит
│   ├── migrator.... Утилита для миграций базы данных
│   └── sso......... Основная точка входа в сервис SSO
├── config........... Конфигурационные yaml-файлы
├── internal......... Внутренности проекта
│   ├── app.......... Код для запуска различных компонентов приложения
│   │   └── grpc.... Запуск gRPC-сервера
│   ├── config....... Загрузка конфигурации
│   ├── domain
│   │   └── models.. Структуры данных и модели домена
│   ├── grpc
│   │   └── auth.... gRPC-хэндлеры сервиса Auth
│   ├── lib.......... Общие вспомогательные утилиты и функции
│   ├── services..... Сервисный слой (бизнес-логика)
│   │   ├── auth
│   │   └── permissions
│   └── storage...... Слой работы с данными 
│       └── sqlite.. Реализация на SQLite
├── migrations....... Миграции для базы данных
├── storage.......... Файлы хранилища, например SQLite базы данных
└── tests............ Функциональные тесты```
