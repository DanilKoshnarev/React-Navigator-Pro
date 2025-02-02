# React Navigator Pro

## Описание
"React Navigator Pro" - это проект, демонстрирующий использование принципов чистой архитектуры для создания приложения на React с использованием `react-router-dom` для маршрутизации.

## Структура проекта
Проект разделен на несколько слоев для улучшения читаемости и поддерживаемости кода:

- **Domain**: Основные бизнес-логика и правила.
- **Application**: Интерфейсы, юзкейсы и реализации для работы с данными.
- **Infrastructure**: Реализация деталей инфраструктуры, таких как API-вызовы, работа с базой данных и так далее.
- **Presentation**: Компоненты React и работа с пользовательским интерфейсом.

## Установка
1. Клонируйте репозиторий:
    ```bash
    git clone <URL репозитория>
    ```
2. Перейдите в каталог проекта:
    ```bash
    cd <название каталога>
    ```
3. Установите зависимости:
    ```bash
    npm install
    ```

## Запуск
Для запуска приложения выполните команду:
```bash
npm start
```

## Структура каталогов
```plaintext
.
├── domain
│   └── entities
│       └── Data.js
├── application
│   ├── usecases
│   │   └── GetDataList.js
│   └── repositories
│       └── DataRepository.js
├── infrastructure
│   └── api
│       └── ApiDataRepository.js
├── presentation
│   ├── components
│   │   └── Layout.jsx
│   ├── pages
│   │   ├── DataListPage.jsx
│   │   ├── DataPage.jsx
│   │   ├── DataDeletePage.jsx
│   │   └── DataCreatePage.jsx
│   └── routes
│       └── AppRoutes.jsx
├── package.json
└── README.md
```

## Описание компонентов
### Domain
- **Data.js**: Класс сущности данных.

### Application
- **GetDataList.js**: Юзкейс для получения списка данных.
- **DataRepository.js**: Интерфейс репозитория данных.

### Infrastructure
- **ApiDataRepository.js**: Реализация репозитория данных с использованием API.

### Presentation
- **Layout.jsx**: Компонент макета страницы.
- **DataListPage.jsx**: Компонент страницы списка данных.
- **DataPage.jsx**: Компонент страницы данных с динамическим параметром id.
- **DataDeletePage.jsx**: Компонент страницы удаления данных.
- **DataCreatePage.jsx**: Компонент страницы создания данных.
- **AppRoutes.jsx**: Компонент маршрутизации приложения.

## Лицензия
Этот проект лицензирован под лицензией MIT. Для получения дополнительной информации см. файл LICENSE.
```
