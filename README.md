Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Для решения данной задачи можно использовать следующий алгоритм.
1.	Задать размер первоначального массива.
2.	Заполнить первоначальный массив строками, либо ввести его с клавиатуры.
3.	Создать новый массив, размер которого будет равен количеству строк из первоначального массива, удовлетворяющих условию длины (меньше или равно трем символам).
4.	Используя цикл, пройтись по каждой строке первоначального массива.
5.	Внутри цикла проверить длину текущей строки. Если она меньше или равна трем символам, то добавить эту строку в новый массив.
6.	Вывести новый массив на экран или произвести необходимую обработку полученного 