<h1>API Liquidity - системы расчета ликвидности</h1>

**Задача:**
Спроектировать RestAPI для АС «Ликвидность торговой книги», которое предоставляет возможность для реализации следующих действий пользователей: 
- Запуск расчета за дату и всем потокам или выбранному;
- Поиск расчетов с использованием фильтров;
- Просмотр статуса запущенного расчета;
- Запуск формирования отчета за дату;
- Поиск отчетов с использованием фильтров;
- Просмотр статуса запущенного отчета;
- Остановка процесса формирования отчета;
- Скачивание отчета.
- Просмотр списока пользователей;
- Блокировка и активация аккаунтов;
- Редактирование данных пользователей и их прав.

И взаимодействия внутренних сервисов:
- Получение данных по платежам;
- Формирование платежей;
- Удаление платежей за дату с использованием фильтра по потоку.

**Реализация**
> [Спецификация OpenAPI](https://github.com/anastassaa/liquidity_calc/blob/master/Liquidity-1.0.0-swagger.yaml)</br>


*Разработана с помощью https://app.swaggerhub.com*
