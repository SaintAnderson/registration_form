Проект c формой регистрации и на чистом PHP с использованием стилей CSS и подключение базы данных MySQL.

Перед запуском проект необходимо создать базу данных MySQL(к примеру "test") и в ней создать таблицу "users".
В таблице создать следующие поля с типами данных:

- id  INT  11  A_I
- full_name  VARCHAR  355  NULL
- login  VARCHAR  100  NULL 
- email  VARCHAR  355  NULL
- password  VARCHAR  355  NULL
- avatar  VARCHAR  355  NULL

После создании необходимых полей нужно выполнить следующую команду в папке с index.php:
- php -S localhost:8000
