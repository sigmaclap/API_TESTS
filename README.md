В директории /tests располагается файл с тестами

В директории /tests/images лежат картинки для теста добавления питомца и теста добавления картинки

В корневой директории лежит файл settings.py - содержит информацию о валидном логине и пароле, а так же неверном для
проверки негативных тестов.

В корневой директории лежит файл api.py, который является библиотекой к REST api сервису веб приложения Pet Friends

Библиотека api написана в классе, что соответствует принципам ООП и позволяет удобно пользоваться её методами.
При инициализации библиотеки объявляется переменная base_url которая используется при формировании url для запроса.

Методы имеют подродное описание.

Тесты проверяют работу методов используя api библиотеку.
