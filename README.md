# Итоговая проверочная работа

**Задача: Сформировать массив строк из имеющего массива строк, длина строк которых меньше или равна 3 символам**.

<img src=".//IMG/block_diagram.svg " width="55%" align="right"> 

## Решение

Определяем переменные:
 * **maxLenght** - для поиска строк в основном массиве, длина которых не больше этого значения.
 * **j** - счетчик количества индексов основного массива, строки которого меньше или равно 3 символам.

Пользователь вводит с клавиатуры некоторое количество слов, символов или чисел через "ПРОБЕЛ".

Полученные данные **dataArray** (строка) с помощью метода String.Splint() и разделителя "ПРОБЕЛ" 
разбиваем на подстроки и формируем основной массив строк **array**

C помощью цикла перебираем основной массив. Если находится строка в массиве, длина которой меньше или равна 3-м символов, то увеличиваем счетчик **"J"**
Затем создаем новый массив с количеством **"J"** строк. Сбрасываем счетчик.
Далее заново с помощью цикла перебираем основной массив, значения строк, длина которых меньше или равна 3 символам, последовательно копируем в новый массив строк.

Производим вывод в консоль содержимого основного массива строк и содержимое нового массива строк.
