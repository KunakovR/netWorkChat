# Курсовой проект "Сетевой чат"

###  Описание проекта ###

1. Разработать два приложения: сервер чата, клиент чата.
2. Все сообщения логируются
3. Присутствует файл settings с установками порта

###  Сервер ###
+ Установка порта для подключения клиентов через файл настроек (например, settings.txt);
+ Возможность подключиться к серверу в любой момент и присоединиться к чату;
+ Отправка новых сообщений клиентам;
+ Запись всех отправленных через сервер сообщений с указанием имени пользователя и времени отправки.

### Клиент ###
+ Выбор имени для участия в чате;
+ Прочитать настройки приложения из файла настроек - например, номер порта сервера;
+ Подключение к указанному в настройках серверу;
+ Для выхода из чата нужно набрать команду выхода - “/exit”;
+ Каждое сообщение участников должно записываться в текстовый файл - файл логирования. При каждом запуске приложения файл должен дополняться.
