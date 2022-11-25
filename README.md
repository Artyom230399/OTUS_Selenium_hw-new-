## Задание
1. Написать фикстуру для запуска разных браузеров (firefox, chrome, opera, по желанию - safari, edge, yandex).
2. Выбор браузера должен осуществляться путем передачи аргумента командной строки pytest.
3. По завершению работы тестов должно осуществляться закрытие браузера.
4. Добавить опцию командной строки, которая указывает базовый URL opencart.
5. Написать тесты проверяющие элементарное наличие элементов на разных страницах приложения opencart
6. Реализовать минимум пять тестов (одни тест = одна страница приложения)
7. Использовать методы явного ожидания элементов
## Покрыть нужно:
- Главную
- Каталог
- Карточку товара
- Страницу логина в админку /admin
- Страницу регистрации пользователя (/index.php?route=account/register)
- Какие именно элементы проверять определить самостоятельно, но не меньше 5 для каждой страницы.