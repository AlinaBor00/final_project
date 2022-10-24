# **Final project**
## Задача:
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Решение:
Задаем два массива.
Создаем метод NewArray, в котором цикл равен по размеру длине массива, внутри цикла проверяем условие <=3, если да, то элемент первого массива заносится в count элемент второго массива. 
Переменная count создается для того, чтобы поочередно перемещать элементы из первого массива во второй.
Метод PrintArray создается для распечатки массива.