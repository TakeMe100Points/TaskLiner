<div id="MainTitle">

# Серверное приложение

</div>
<div id="SubTitle"> 

### Серверное приложение для приложения трэкинга задач как одиночных пользователей, так и компаний, а также генерации отчетов

</div>

Клиент-серверное решение состоит из двух приложений : WPF клиент (https://github.com/NoTh0ughts/TaskLinerClientApp) и .NET Core сервера (этот репозиторий)
Серверное приложение позволяет аутентифицировать пользователей и проводить синхронизацию именений в задачах или проектах.

---

## Технологический стек:
<div id="TechStack">

* ASP.NET
* MySQL
* MediatR
* EF

</div>

## Диаграмма классов
![image](https://user-images.githubusercontent.com/57771719/224713561-5e1ea0fb-c298-4c11-bb97-b3f4143f92ac.png)

## Как запустить?
1. Скопировать репозиторий коммандой ```git clone https://github.com/NoTh0ughts/TaskLiner TaskLinerServer```
2. Перейти в консоли в папку с проектом 
3. Восстановить зависимости коммандой ```dotnet restore```
4. Запустить сервер ```dotnet  run```
