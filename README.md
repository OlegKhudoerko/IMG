# Итоговая проверочная работа

**Задача: Сформировать массив строк из имеющего массива строк, длина строк которых меньше или равна 3 символам**

<img src=".//IMG/block_diagram.svg " width="55%" align="right"> 

## Решение

1. Определяем переменные:
* " " **maxLenght** - для поиска строк в основном массиве, длина которых не больше этого значения.
* " "  **j** - счетчик количества индексов основного массива, строки которого меньше или равно 3 символам.

2. Пользователь вводит с клавиатуры некоторое количество слов, символов или чисел через "ПРОБЕЛ".
Полученные данные **dataArray** (строка) с помощью метода String.Splint() и разделителя "ПРОБЕЛ" 
разбиваем на подстроки и формируем основной массив строк **array**

