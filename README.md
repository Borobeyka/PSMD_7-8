# UI к базе данных PostgreSQL

Данная работа была выполнена в рамках практических работ по дисциплине "*Программные средства манипулирования данными*".
Работа построена на фреймворке **Flask** для языка программирования **Python**.

Веб-приложение имеет следующие маршруты:
- **/employees/register** → Страница с формой добавления нового сотрудника в систему
- **/employees/auth** → Страница авторизации сотрудника в системе
- **/employees/logout** → Алгоритм вывода пользователя из аккаунта
- **/tasks** → Страница с выводом доступных заданий (те, в которых сотрудник является исполнителем или автором)
- **/tasks/id** → Просмотр подробной информации по заданию, в соответствии с **id** в URL адресе (в котором, сотрудник - исполнитель или автор)
- **/tasks/edit/id** → Внесение изменений в задание
- **/tasks/finish/id** → Алгоритм завершения задания сотрудником
- **/tasks/create** → Страница с формой создания и назначение исполнителя задания
- **/tasks/report** → Страница с формированием отчетности по заданиям по определенным критериям
