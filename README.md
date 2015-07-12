# word-count

## Задача
Реализовать функцию, которая принимает на вход строку и возвращает число слов в этой строке.
Слова разделены пробелами (и возможно не одним), а знаки пунктуации не учитываются.

Функцию можно реализовать используя три подхода (чем больше тем лучше, но не обязательно):
* процедурный
* ооп
* функциональный

## Ограничения
* Язык JavaScript.
* Нельзя использовать сторонние библиотеки.
* Допускается только посимвольный перебор строки.

## Оформление решения
* Создайте файл в папке `solutions` с именем `<github name>.js`.
* Скопируйте туда содержимое файла `solutions/mokevnin.js`.
* Реализуйте функции `imperative`, `oop`, `functional` (не все, а те которые сможете).
* Убедитесь что проходят тесты.
* Отправьте пулреквест. Пулреквест должен содержать только один коммит (используйте squash для слияния).

## Окружение
* make.
* nodejs v0.12.*.

## Проверка решения
* Установка: `make install`.
* Запуск тестов: `make test`.