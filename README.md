# Перечень автоматизируемых сценариев.
## Переход к проффесии с главной страницы:
### Предусловие: Открыта главная страница Нетологии (https://netology.ru/)
### №1 
1. Кликнуть на главной странице на раздел "Программирование"
2. Выбрать курс "Тестироващик ПО"
### №2
1. Кликнуть на главной странице на раздел "Программирование"
2. Ввести в поисковую строку "Тестировщик ПО"
3. Выбрать курс "Тестировщик ПО"
### №3
1. Кликнуть кнопку "Каталог курсов"
2. Кликнуть "Программирование"
3. Выбрать курс "Тестировщик ПО"
### №4
1. Кликнуть кнопку "Каталог курсов"
2. Ввести в поисковую строку "Тестировщик ПО"
3. Выбрать курс "Тестировщик ПО"
### №5
1. Кликнуть на главной странице "Полный каталог"
2. Выбрать курс "Тестировщик ПО"
### №6
1. Прокрутить страницу вниз до "Подвала"
2. Нажать "Каталог курсов"
3. Выбрать курс "Тестировщик ПО"
### №7
1. Прокрутить страницу вниз до "Подвала"
2. Нажать "Программирование"
3. Выбрать курс "Тестировщик ПО"
## Ожидаемый результат: Переход на страницу курса "Тестировщик ПО"
## Переход к анкете на заявку.
### Предусловие: Открыта страница курса "Тестировщик ПО"
### №1 
1. Кликнуть на кнопку "Записаться".
### №2 
1. Прокрутить страницу вниз
2. Кликнуть на кнопку "Записаться"
## Ожидаемый результат: Переход на страницу анкеты.
## Позитивный сценарий - заполнение анкеты валидными данными:
#### Предусловие: Открыта анкета для заявки.
#### Входные данные:
#### <u>Имя</u> - Написано на кириллице или латинице не менее 2-х букв из спец. символов (дефис и пробел).
#### <u>Номер телефона</u> - Формат из 11 цифр.
### №1
1. Заполнить валидные данные в поле "Имя"
2. Заполнить валидные данные в поле "Номер телефона"
3. Нажать кнопку "Записаться"
## Ожидаемый результат: Сообщение об успешной записи.
## Негативный сценарий - пустое поле:
#### Предусловие: Открыта анкета для заявки.
### №1
1. Оставить пустым поле "Имя"
2. Заполнить валидные данные в поле "Номер телефона"
3. Нажать кнопку "Записаться"
### №2
1. Заполнить валидные данные в поле "Имя"
2. Оставить пустым поле "Номер телефона"
3. Нажать кнопку "Записаться"
## Ожидаемый результат: Сообщение о незаполненном поле "Обязательное поле"
## Негативный сценарий - невалидные данные:
#### Предусловие: Открыта анкета для заявки.
### №1
1. Заполнить невалидные данные в поле "Имя"
2. Заполнить валидные данные в поле "Номер телефона"
3. Нажать кнопку "Записаться"
### №2
1. Заполнить валидные данные в поле "Имя"
2. Заполнить невалидные данные в поле "Номер телефона"
3. Нажать кнопку "Записаться"
## Ожидаемый результат: Невозможно записаться из-за неверно заполненных полей.

# Перечень используемых инструментов с обоснованием выбора:
- IntelliJ IDEA - среда работы с кодом.
- Java 11 - автотесты написаны на этом языке.
- Gradle - сборка проекта.
- Lombok - для сокращения кода
- Selenium или Selenide - для тестирования GUI
- Faker - для генерации данных
- Allure - создание отчётов
- Git и GitHub - управление версиями
# Перечень необходимых разрешений, данных и доступов:
1. Разрешение на тестирование
2. Техническая документация
3. База данных
# Перечень и описание возможных рисков при автоматизации:
1. Автотесты могут утратить актуальность
2. В HTML нет "data test id"
# Перечень необходимых специалистов для автоматизации:
Один QA engineer
# Интервальная оценка с учётом рисков в часах:
80 Человеко-часов (10 рабочих дней).