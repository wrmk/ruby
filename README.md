# Самоучитель Ruby

Примеры к книге "Самоучитель Ruby"

![обложка книги](http://www.bhv.ru/largeimg/204313.jpg "Самоучитель Ruby")

## Цель книги

Цель книги — полное и последовательное изложение языка программирования Ruby. Книга рассчитана как на начинающих разработчиков, не владеющих ни одним языком программирования, так и на опытных программистов, желающих освоить Ruby. Ruby-разработчикам со стажем книга так же будет полезна, поскольку освещает нововведения языка, начиная с версии 2.0 до версии 2.6.

При создании книги не ставилась задача создать иллюзию, будто язык Ruby простой и не потребует усилий для его освоения. Ruby не является С-подобным и часто использует уникальные конструкции и решения, не имеющие аналогов в других живых языках программирования. Казалось бы знакомые по другим языкам конструкции, часто ведут себя в нем немного по-другому или в корне имеют иное назначение и свои особенности синтаксиса.

## Как создавалась книга...

Книга была написана за 6 месяцев, однако подготовка к ее созданию заняла 7 лет, на протяжении которых я работал Ruby-разработчиком в компаниях Newsmedia, Rambler&Co и Mail.ru. В каждой из них вел авторские курсы, посвященные программированию баз данных, программированию на Ruby, автоматическому тестированию и веб-программированию с использованием фреймворка Ruby on Rails. Однако большая часть времени была посвящена разработке Ruby-проектов: портал Rambler.ru, телеканал Life, газета izvestia.ru.

## О авторе

**Симдянов Игорь Вячеславович**, разработчик с 20 летним стажем, ведущий разработчик группы компаний Rambler&Co, преподаватель и методист GeekBrains (Mail.ru). Автор двух десятков книг по веб-разработке и базам данных.

## Приобретение книги

[Купить бумажную книгу через Labirint.ru.](https://www.labirint.ru/books/712808/)

## Помощь и отзывы

Раздел [Issues](https://github.com/igorsimdyanov/ruby/issues)

## Содержание

### Предисловие 

- Цель книги
- Как создавалась книг
- Терминология
- Исходные коды
- Задания
- Типографские соглашения
- Благодарности

### [Глава 1. Введение в язык Ruby](intro)

- Философия Ruby
- Реализации Rub
- Версии
- Установка Ruby
- Запуск программы на выполнение
- Задания

### [Глава 2. Быстрый старт](start)

- Соглашения Ruby
- Комментарии
- Элементы языка
- Вывод в стандартный поток
- Как пользоваться документацией?
- Задания

### [Глава 3. Утилиты и гемы](utils)

- Утилиты
- Интерактивный Ruby
- Шаблонизатор `erb`
- Утилита `rake`
- Утилита `rdoc`
- Гемы
- Задания

### [Глава 4. Предопределенные классы](ruby_classes)

- Синтаксические конструкторы
- Строки. Класс `String`
- Символы. Класс `Symbol`
- Целые числа. Класс `Integer`
- Вещественные числа. Класс `Float`
- Диапазоны. Класс `Range`
- Массивы. Класс `Array`
- Хэши. Класс `Hash`
- Логические объекты `true` и `false`
- Объект `nil`
- Задания

### [Глава 5. Переменные](variables)

- Типы переменных
- Присваивание 
- Клонирование
- Задания

### [Глава 6. Константы](constants)

- Создание и определение констант
- Предопределенные константы
- Ключевые слова `__LINE__` и `__FILE__`
- Метод `require`
- Метод `require_relative`
- Подключение стандартных классов
- Подключение гемов
- Задания

### [Глава 7. Операторы](operators)

- Операторы — это методы
- Арифметические операторы
- Присваивание
- Операторы строк
- Операторы сравнения
- Поразрядные операторы
- Оператор безопасного вызов
- Ключевое слово `defined?`
- Приоритет операторов
- Задания

### [Глава 8. Ветвление](conditions)

- Ключевое слово `if` 
- Логические операторы
- Ключевое слово `unless`
- Условный оператор
- Ключевое слово `case` 
- Советы
- Задания

### [Глава 9. Глобальные методы](methods)

- Создание метод
- Параметры и аргументы
- Возвращаемое значение
- Получатель метода
- Псевдонимы методов
- Удаление метода
- Рекурсивные методы
- Предопределенные методы
- Логические методы
- bang-методы
- Задания

### [Глава 10. Циклы](cycles)

- Цикл `while`
- Вложенные циклы
- Досрочное прекращение циклов
- Цикл `until`
- Цикл `for`
- Задания

### [Глава 11. Итераторы](iterators)

- Итераторы и блоки
- Обход итераторами массивов и хэшей
- Итератор `times`
- Итераторы `upto` и `downto`
- Итераторы коллекций
- Итератор `tap`
- Сокращенная форма итераторов
- Досрочное прекращение итерации
- Класс `Enumerator`
- Задания

### [Глава 12. Блоки](block)

- Блоки в собственных методах
- Передача значений в блок
- Метод `block_given?`
- Возврат значений из блока
- Итератор `yield_self`
- Передача блока через парамет
- Различие `{ ... }` и `do ... end`
- Блоки в рекурсивных методах
- Класс `Proc`
- Методы `proc` и `lambda`
- Различия `proc` и `lambda`
- Задания

### [Глава 13. Классы](classes)

- Создание класса
- Класс — это объект
- Как проектировать классы?
- Переопределение методов
- Открытие класса
- Тело класса и его свойства
- Вложенные классы
- Константы
- Переменные класса
- Задания

### [Глава 14. Методы в классах](class_methods)

- Сохранение состояния в объекте
- Установка начального состояния объекта
- Специальные методы присваивания
- Синглетон-методы
- Методы класса
- Обработка несуществующих методов
- Метод `send`
- Задания

### [Глава 15. Преобразование объектов](overload)

- Сложение строк и чисел
- Методы преобразования объектов
- Сложение объектов
- Сложение объекта и числа
- Сложение объекта и строки
- Сложение объекта и массива
- Перегрузка `[]` и `[]=`
- Перегрузка унарных операторов `+`, `–` и `!`
- Какие операторы можно перегружать?
- DuckType-типизация
- Задания

### [Глава 16. Ключевое слово self](self)

- Ссылки на текущий объект
- Значения `self` в разных контекстах
- Приемы использования `self`
- Задания

### [Глава 17. Наследование](inheritance)

- Наследование
- Логические операторы
- Динамический базовый класс
- Наследование констант
- Иерархия стандартных классов
- Переопределение методов
- Удаление методов
- Поиск метода
- Задания

### [Глава 18. Области видимости](scope)

- Концепция видимости
- Открытые методы
- Закрытые методы
- Защищенные методы
- Закрытый конструктор
- Паттерн «Одиночка» (Singleton)
- Вызов закрытых методов
- Информационные методы
- Области видимости при наследовании
- Области видимости методов класса
- Задания

### [Глава 19. Модули](namespaces)

- Создание модуля
- Оператор разрешения области видимости
- Пространство имен
- Вложенные классы и модули
- Доступ к глобальным классам и модулям
- Задания

### [Глава 20. Подмешивание модулей](mixins)

- Класс `Module`
- Подмешивание модулей в класс
- Подмешивание модулей в объект
- Синглетон-методы модуля
- Области видимости
- Стандартный модуль `Kernel`
- Поиск методов в модулях
- Метод `prepend`
- Методы обратного вызова
- Уточнения
- Псевдонимы методов
- Задания

### [Глава 21. Стандартные модули](modules)

- Модуль `Math`
- Модуль `Singleton`
- Модуль `Comparable`
- Модуль `Enumerable`
- Модуль `Forwardable`
- Маршаллизация
- JSON-формат
- YAML-формат
- Задания

### [Глава 22. Свойства объектов](objects)

- Общие методы
- Неизменяемые объекты
- Заморозка объектов
- Небезопасные объекты
- Задания

### [Глава 23. Массивы](arrays)

- Модуль `Enumerable`
- Заполнение массива
- Извлечение элементов
- Поиск индексов элементов
- Случайный элемент массива
- Удаление элементов
- Замена элементов
- Информация о массиве
- Преобразование массива
- Арифметические операции с массивами
- Логические методы
- Вложенные массивы
- Итераторы
- Сортировка массивов
- Задания

### [Глава 24. Хэши](hashes)

- Создание хэша
- Заполнение хэша
- Извлечение элементов
- Поиск ключа
- Обращение к несуществующему ключу
- Удаление элементов хэша
- Информация о хэшах
- Хэши как аргументы методов
- Объединение хэшей
- Преобразование хэшей
- Сравнение ключей
- Преобразование ключей хэша
- Задания

### [Глава 25. Классы коллекций](collections)

- Множество `Set`
- Класс `Struct`
- Класс `OpenStruct`
- Задания

### [Глава 26. Исключения](exceptions)

- Генерация и перехват исключений
- Исключения — это объекты
- Стандартные ошибки
- Создание собственных исключений
- Перехват исключений
- Многократная попытка выполнить код
- Перехват исключений: почти всегда плохо
- Блок `ensure`
- Блок `else`
- Перехват исключений в блоке
- Задания

### [Глава 27. Файлы](files)

- Класс `IO`
- Создание файла
- Режимы открытия файла
- Закрытие файла
- Чтение содержимого файла
- Построчное чтение файла
- Запись в файл
- Произвольный доступ к файлу
- Пути к файлам
- Манипуляция файлами
- Задания

### [Глава 28. Права доступа и атрибуты файлов](files_attributes)

- Типы файлов
- Определение типа файла
- Время последнего доступа к файлу
- Права доступа вUNIX-подобной системе
- Задания

### [Глава 29. Каталоги](catalogs)

- Текущий каталог
- Создание каталога
- Чтение каталога
- Фильтрация содержимого каталога
- Рекурсивный обход каталога
- Удаление каталога
- Задания

### [Глава 30. Регулярные выражения](regexp)

- Как изучать регулярные выражения?
- Синтаксический конструктор
- Оператор `=~`
- Методы поиска
- Синтаксис регулярных выражений
- Модификаторы
- Где использовать регулярные выражения?
- Примеры
- Задания

### [Глава 31. Веб-программирование](rack)

- Протокол HTTP
- Веб-серверы
- Гем Rack
- Ruby on Rails
- Задания

### [Глава 32. Автоматическое тестирование](tests)

- Типы тестирования
- Преимущества и недостатки тестирования
- Фреймворки для тестирования
- Задания

### Заключение 
### Приложение 1. Справочные таблицы
### Приложение 2. Содержимое электронного архива