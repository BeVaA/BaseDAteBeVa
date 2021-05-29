# Проект 1

About: https://github.com/RyabovNick/databasecourse_p1/tree/master/Project1

## Сервис управления доступами персонала для действий на объекте

1. Администратор. Добавление нового сотрудника
2. Администратор. Выдача прав по доступу в определённые помещения (единичное, временное, постоянное)
3. Сотрудник. Попытка прохода в определенное помещение
4. Администратор. Уведомления о попытке прохода без разрешения
5. Сотрудник. Запрос доступа для прохода (разовое, временное)
6. Администратор. Просмотр списка всех пользователей с поиском по: правам, фамилии/имени/отчеству, по активности. Сортировка по: активности последней, пагинация.
7. Администратор. Просмотр всех действий конкретного пользователя (время входа, время выхода; поиск по помещению, пагинация)
8. Администратор. Некоторые помещения должны иметь максимальное время нахождения в них, уведомлять администратора если сотрудник превышает это время. Записывать такие инциденты в базу.
9. Администратор. Забрать права (Предусмотреть случай, когда сотрудник вошёл в помещение и у него забрали права на выход).
10. Администратор. Просмотр всех инцидентов (сортировка по дате, сотруднику). Возможность решить инцидент (записать решение)