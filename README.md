<div align="center">

  <h3>RUD3US</h3>

<img
    src="https://avatars.githubusercontent.com/u/80245370?v=4"
    alt="Rudy Icon"
    width="180"
    style="border-radius: 50%; box-shadow: 0 8px 24px rgba(0,0,0,0.18); border: 1px solid #e5e7eb;"
  />

  <p><sub>Used Services:</sub></p>

</div>

<p align="center">
  <a href="https://github.com/RudySource?tab=repositories">
    <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://dotnet.microsoft.com/">
    <img src="https://img.shields.io/badge/.NET-5C2D91.svg?style=for-the-badge&logo=.net&logoColor=white"/>
  </a>
  <a href="https://www.sqlite.org/">
    <img src="https://img.shields.io/badge/SQLite-003B57.svg?style=for-the-badge&logo=sqlite&logoColor=white"/>
  </a>
  <a href="https://learn.microsoft.com/dotnet/csharp/">
    <img src="https://img.shields.io/badge/C%23-239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white"/>
  </a>
</p>

<div align="center" style="max-width: 600px; margin: 0 auto; padding: 18px; border-radius: 18px; background: rgba(255,255,255,0.06); box-shadow: 0 14px 30px rgba(0,0,0,0.08);">

## Основная информация

**ФИО**: Rudy Rudy Rudy

**Группа**: ИСП-233

**Дата**: 24.08.2077

</div>

# Лабораторная работа №35. Подключаем фронтенд к API: доска мемов

## Как запустить проект?

### Backend

```bash
dotnet restore
dotnet build
dotnet run
```

### Frontend

```bash
Запустите `index.html` через плагин GoLive
```

> [!NOTE]
> Swagger будет доступен по адресу:
> `https://localhost:port/swagger`
> **Точный порт можно посмотреть в** `MemesApi/Properties/launchSettings.json`.

## Обязательная таблица — что изучили:

| Концепция                               | Где используется                          |
| --------------------------------------- | ----------------------------------------- |
| `fetch(url)`                            | GET-запрос к API                          |
| `fetch(url, { method, headers, body })` | POST и DELETE запросы                     |
| `response.ok`                           | Проверка успешности ответа                |
| `response.json()`                       | Чтение JSON из ответа                     |
| `JSON.stringify(...)`                   | Объект JS -> JSON-строка для отправки     |
| `async / await`                         | Ожидание ответа от сервера                |
| `try / catch / finally`                 | Обработка ошибок при `fetch`              |
| `CORS`                                  | Разрешение запросов между разными портами |
| `AddCors + UseCors`                     | Включение CORS в ASP.NET Core - два шага  |
