Индивидуальный проект, написан на JAVA backend. 
В данном проекте реализована система для учёта пропусков (пропущенных занятий/дней) студентами. 
В системе реализована работа с REST API с JWT токеном, авторизация, аутентификация пользователей, полное подключение и настройка Swagger’а, а также экспорт и прикрепление подтверждающих документов. Проработана валидация данных, для всех запросов. 
Использовал базу данных H2. Реализованные сущности: 
1)	Пользователь - классический пользователь системы. Разделяется на 3 роли: Деканат, Преподаватель и Студент. У деканата есть возможность одобрить заявку на пропуск, назначить роли преподавателю. Роль деканата назначается админом.
2)	Заявка - сущность, описывающая пропуск студентом занятий с n по k. Хранит в себе функционал продления k до любого значения, прикрепления подтверждающих документов, отклонения\подтверждения заявки.
3)	Подтверждение - документ, прикрепляемый к заявке.
