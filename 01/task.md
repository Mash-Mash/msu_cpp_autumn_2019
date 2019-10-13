### Практическая часть


Используя метод рекурсивного спуска, написать калькулятор. Поддерживаемые операции:

- умножение
- деление
- сложение
- вычитание
- унарный минус

Для вычислений использовать тип int, приоритет операций стандартный. Передача выражения осуществляется через аргумент командной строки, поступаемые числа целые, результат выводится в cout. Пример:

```
calc "2 + 3 * 4 - -2"
```

Вывод:

```
16
```

Должна быть обработка ошибок, в случае некорректного выражения выводить в консоль ошибку и возвращать код отличный от 0. Тесты обязательны.