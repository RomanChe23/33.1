Дипломный проект: реальный кейс компании «Ростелеком Информационные Технологии»

Автоматизированное тестирование обновленной страницы авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии ( https://b2c.passport.rt.ru/ )

Тест-кейсы и баг-репорты: https://docs.google.com/spreadsheets/d/1vvwHSJ9PFxjLEGicWJVVD1SMC1EPqgPH4jweIs6GsQc/edit?usp=sharing

В папке pages в файле base_page.py находится конструктор webdriver и общие методы для всех тестируемых страниц.

В папке pages в файлах auth_page.py, change_pass_page.py, reg_page.py находятся методы проверок: файл auth_page.py содержит проверки методов авторизации; файл change_pass_page.py содержит методы проверки формы восстановления пароля; файл reg_page.py содержит методы проверки формы регистрации.

В папке с тестами в файлах test_auth_page.py, test_change_pass_page.py, test_reg_page.py находятся тесты. Все тесты помечены номером, совпадающим с номером тест-кейса в Google-таблицах.

В папке pages в файле "locators.py доступны все локаторы.

В корне проекта в файле conftest.py находится фиксура с открытием и закрытием браузера.

В корне проекта в файле settings.py хранятся методы и переменные для параметризации тестов.

В корне проекта в файле pytest.ini зарегистрированы метки маркировки тестов.

В корне проекта в файле requirements.py используются библиотеки.
