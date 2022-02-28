# Тестовое задание 
При запуске `docker-compose up` собирается один контейнер, после чего запускаются 3:

- Приложение php, которое берет код из src/
- Контейнер базы MariaDB
- Контейнер с phpMyAdmin

MariaDB и phpMyAdmin находятся в одной сети, успешно получается войти в базу через phpMyAdmin.
Пароль находится в compose. Можно было через переменные сделать или секреты, но мне лень.

Приложение http://localhost:8081/hello.php
База весит на порту 8082
PhpMyAdmin http://localhost:8083/index.php