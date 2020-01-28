## [Welcome]
<ul>
    <li>Простой Java Client для доступка к JIRA REST-API</li>
    <li>Автор: Евгений Савкин</li>
    <li>ЯП: Kotlin</li>
    <li>https://docs.atlassian.com/jira/REST/cloud/</li>
</ul>

## [Запуск из Java]
<ul>
    <li>Import jira-buddy.jar в свой проект</li>
    <li>или добавить зависимость ru.vtb / jira-buddy / 1.0  </li>
    <li>Пример вызова методов:  </li>
</ul>
![example](/src/main/resources/example.jpg)

```kotlin
/**
* IssueWorks содержит все custom методы
*/
interface IssueWorks {
// Все рабочие методы и описание в интерфейсе
}
```
## [Навигатор по библиотеке]

* IssueWorks - реализация всех рабочих методов
* IssueClient - все по задачам. Включая так-же Attachments, Transitions, Comments и Worklog
* ProjectClient - все по проектам. Включая Components и Versions
* UserClient - все по пользователям.
* SearchClient - jql search
* SystemClient - все глобальное Инфо по Jira. Такие как: Status, Priority, IssueTypes информация.

