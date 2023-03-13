# FinalTask
## Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Описание алгоритма решения:
1. Сначала объявляется два массива: array1 и array2 одинаковой длины. Потом метод, в котором цикл соразмерен длине массива. 
2. Внутри цикла проверяется условие ( <=3 ); если да, то элемент первого массива заносится в count элемент второго массива. Переменная count создана для того, чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. 
3. После присвоения увеличивается переменная count на 1 и возвращается к циклу for, в котором i увеличивается на 1. И так проверяется до последнего элемента массива.
##### P.S. Графическое представление метода в папке Schem.