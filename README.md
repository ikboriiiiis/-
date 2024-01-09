## Блок-схема для данной задачи будет выглядеть следующим образом:

1. Начало программы.
2. Задание исходного массива строк (ввод с клавиатуры или задание на старте выполнения алгоритма).
3. Создание нового пустого массива строк.
4. Перебор всех элементов исходного массива строк в цикле.
5. Проверка длины текущей строки на меньше или равно 3 символам.
6. Если длина текущей строки меньше или равна 3 символам, то добавление ее в новый массив строк.
7. Переход к следующему элементу исходного массива строк.
8. Конец цикла.
9. Вывод нового массива строк.
10. Конец программы.

Таким образом, программа будет состоять из одного цикла с условием проверки длины каждой строки и добавления ее в новый массив, если она удовлетворяет условию.


![Сама блок схема:](схема.png)

## Решение задачи на C#

1. Вводим исходный массим строк с клавиатуры с помощью **Console.Write**
2. Создаем пустой массив для новых строк с помощью присвоения метода **string** к новому
3. Проходим по каждой строке и добавляем ее в новый массив, если ее длина меньше или равна 3 с помощью цикла **for**
4. Создаем новый массив с размером, соответствующему количеству найденных строк
5. Выводим новый массив из строк