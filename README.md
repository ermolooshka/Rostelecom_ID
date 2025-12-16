# Ростелеком_ID

- Мною были протестированы требования заказчиков. 
- Разработаны тест-кейсы и обнаруженные дефекты. 
- При разработке тест-кейсов были применены технологии тест-дизайна: эквивалентное разбиение, исследовательское тестирование, попарное тестирование.
- Отчет создан с помощью инструмента Google-таблицы: https://docs.google.com/spreadsheets/d/1Taf5G-QhmXSII5jEranFcN_s9dw0Ukd1XY0ukkp_btU/edit?usp=sharing .
- Были написаны автотесты. 
- Для тестирования сайта был использован интсрумент Selenium. 
- При написании автотестов дополнительно установлены библиотеки: pytest(7.2.0),  selenium (4.7.2), pytest-selenium(4.0.0), termcolor allure-python-commons(2.12.0).


Запуск тестов:

- Установить все требования: pip install -r requirements.txt
- Загрузите свой Selenium WebDriver с https://chromedriver.chromium.org/downloads (выберите версию, совместимую с вашим браузером)
- Запустить тесты: pytest -v --driver Chrome --driver-path /chromedriver test_rostelecom.py
