Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры: ["hello", "2", "world", ":-)"] -> ["2", ":-)"] ["1234", "1567", "-2", "computer science"] -> ["-2"] ["Russia", "Denmark", "Kazan"] -> []

Алгоритм выполнения задачи:

Задаем массив array, задаем длину строки len = 4. Задаем переменную size.
Выполняем цикл for чтобы найти количество элементов длиной меньше len.
Задаем массив modded размером size.
Выполняем цикл for чтобы внести строки в массив modded
Отображаем визуально как изменился массив после выполения задачи