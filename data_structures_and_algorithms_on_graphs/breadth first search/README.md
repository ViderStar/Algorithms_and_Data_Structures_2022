# **Задача 0.8. Поиск в ширину**
*Имя входного файла: input.txt <br/>
Имя выходного файла: output.txt <br/>
Ограничение по времени: 1 с <br/>
Ограничение по памяти: 256 МБ*

Для ориентированного графа, заданного матрицей смежности, выполнили поиск в ширину. При неоднозначности выбора очередной вершины всегда выбирали вершину с меньшим номером. В процессе поиска в ширину в момент посещения вершины ей присваивали метку (нумерация меток начинается с единицы). Определите, какую метку получила каждая из вершин графа (поиск в ширину выполняли до тех пор, пока все вершины не получили метки).

## **Формат входных данных**
В первой строке записано целое число n вершин орграфа (1 ≤ n ≤ 100). Вершины нумеруются числами от 1 до n. Далее записана матрица смежности графа: n строк по n чисел, каждое из которых — 0 или 1. Числа разделяются одиночными пробелами. Гарантируется, что все элементы на главной диагонали нулевые.
## **Формат выходных данных**
Выведите n чисел, i-е из которых — метка, которую получила вершина i.

# **Примеры**
> input.txt :<br/>
7<br/>
0 1 1 0 0 0 0<br/>
0 0 0 0 1 0 0<br/>
0 1 0 1 1 0 0<br/>
0 1 0 0 1 0 0<br/>
0 0 0 0 0 1 0<br/>
0 0 0 1 0 0 0<br/>
0 0 0 0 0 1 0<br/>
output.txt :<br/>
1 2 3 5 4 6 7