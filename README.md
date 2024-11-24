# Практическое Занятие Python.

## №1 Конвертер секунд



## №2 Поиск с остановкой
Напишите программу, которая выводит чётные числа из заданного списка и останавливается, если встречает число 237.

```python
numbers = [
    386, 462, 47, 418, 907, 344, 236, 375, 823, 566, 597, 978, 328, 615, 953, 
    345, 399, 162, 758, 219, 918, 237, 412, 566, 826, 248, 866, 950, 626, 
    949, 687, 217,
]
```

## №3 Выведите список файлов в указанной директории
Выведите список файлов в указанной директории.

Подсказка: Воспользуйтесь методом listdir() модуля os



## №4 Генератор числа
При заданном целом числе n посчитайте n + nn + nnn.
Подсказка: воспользуйтесь возможностью умножения строк. Для перевода из строки и число служит функция int(), обратно – str()



## №5 Проверка корректности имени файла
Напишите программу, которая принимает имя файла и выводит его расширение. Если расширение у файла определить невозможно, сообщите пользователю об ошибке.

Подсказка: воспользуетесь методом строк split() для разбиения сроки. Метод принимает разделитель, по которому разбивается исходные строка. Входной файл должен быть вида «имяфайла.расширение», все остальные комбинации должны быть признаны ошибочными - «имяфайла.», «.расширение», «имяфайла»



## №6 Списки и кортежи
Вы принимаете от пользователя последовательность чисел, разделённых запятой. Составьте список (list) и кортеж (tuple) с этими числами.

Подсказка: воспользуетесь методом строк split() для разбиения сроки. 



## №7 Скрабл
В настольной игре Скрабл (Scrabble) каждая буква имеет определенную ценность. В случае с английским алфавитом очки распределяются так: <br>
A, E, I, O, U, L, N, S, T, R – 1 очко; <br>
D, G – 2 очка;<br>
B, C, M, P – 3 очка;<br>
F, H, V, W, Y – 4 очка;<br>
K – 5 очков;<br>
J, X – 8 очков;<br>
Q, Z – 10 очков.<br>
Напишите программу, которая вычисляет стоимость введенного пользователем слова. Будем считать, что на вход подается только одно слово, которое содержит только английские буквы.<br>
Пример ввода:<br>
notebook<br>

Пример вывода:<br>
12<br>




## №8 База данных
Дан словарь
```python
{'class':{'student':{'name':'Mike','marks':{'physics':70,'history':80}}}}.
```
Выведите на экран имя студента и его оценку по истории





## №9 Переводчик
Создайте программу-переводчик, которая хранит перевод слов с русского языка на английский. После запуска программа выводит список слов в словаре и предлагает пользователю ввести слово для перевода. Если введенного слова нет в словаре выводится сообщение.




