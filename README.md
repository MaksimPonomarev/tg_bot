Всем привет)
Тесты: https://ponomarevmaksim.atlassian.net/jira/software/projects/BOT/boards/2
Я разработал Telegram-бота с именем @manual_test_x_y_bot, который имеет следующие функции:

Основные функции:
Меню действий при запуске команды /start:

Получение ссылок на социальные сети:
ВКонтакте
GitHub
LinkedIn
Отправка случайного анекдота
Калькулятор:

После активации калькулятора, бот отслеживает все сообщения пользователя и автоматически обрабатывает математические выражения, содержащие операции:
сложение (+)
вычитание (-)
умножение (*)
деление (/)
Для завершения работы калькулятора достаточно отправить команду stop, после чего можно снова использовать другие функции бота.
Регистрация и логин:

Регистрация пользователя с вводом логина и пароля, которые сохраняются в базе данных. Пароль сохраняется в зашифрованном виде с использованием хеширования для повышения безопасности.
Авторизация с проверкой логина и пароля по данным в базе. Если данные корректны — доступ разрешен, если нет — доступ запрещен.

Бот сам запускался на ubunty при включении пк, и также я добавил првоерку раз в час работает ли он, если нет, то сам перезапускался.
