# **Задача 0.1. Построить матрицу смежности**
*Имя входного файла: input.txt <br/>
Имя выходного файла: output.txt <br/>
Ограничение по времени: 1 с <br/>
Ограничение по памяти: 64 МБ*

Неориентированный граф задан списком рёбер. Постройте матрицу смежности этого графа. Гарантируется, что в графе нет петель и кратных рёбер.

## **Формат входных данных**
В первой строке записаны два целых числа n и m — число вершин (1 ≤ n ≤ 100) и число рёбер графа (0 ≤ m ≤ n(n − 1) / 2). Вершины графа пронумерованы числами от 1 до n. В следующих m строках описаны рёбра: в каждой строке заданы через пробел две вершины u и v (1 ≤ u, v ≤ n, причём u и v различны), которые соединены ребром.
## **Формат выходных данных**
Выведите матрицу смежности графа: n строк по n чисел, каждое число — 0 или 1, числа в строках разделены пробелами.

# **Примеры**
> input.txt :<br/>
3 2<br/>
1 2<br/>
2 3<br/>
output.txt :<br/>
0 1 0<br/>
1 0 1<br/>
0 1 0<br/>

> input.txt :<br/>
4 3<br/>
1 2<br/>
1 3<br/>
2 4<br/>
output.txt :<br/>
0 1 1 0<br/>
1 0 0 1<br/>
1 0 0 0<br/>
0 1 0 0<br/>