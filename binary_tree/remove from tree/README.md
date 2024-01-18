# **Задача 0.2. Удалить из дереваво**
*Имя входного файла: input.txt <br/>
Имя выходного файла: output.txt <br/>
Ограничение по времени: 1 с <br/>
Ограничение по памяти: 256 МБ*

По набору ключей постройте бинарное поисковое дерево. Удалите из него ключ (правым удалением), если он есть в дереве. Выполните прямой левый обход полученного дерева.

## **Формат входных данных**
В первой строке записано целое число — ключ, который нужно удалить из дерева.
Вторая строка пустая.

Последующие строки содержат последовательность чисел — ключи вершин в порядке добавления в дерево. Ключи задаются в формате по одному в строке. Дерево содержит хотя бы две вершины.

Напомним, что в поисковом дереве все ключи по определению уникальны, поэтому при попытке добавить в дерево ключ, который там уже есть, он игнорируется.
## **Формат выходных данных**
Выведите последовательность ключей вершин, полученную прямым левым обходом дерева.
# **Примеры**
> input.txt :<br/>
3<br/>
<br/>
2<br/>
3<br/>
1<br/>
output.txt :<br/>
2<br/>
1<br/>

> input.txt :<br/>
2<br/>
<br/>
4<br/>
2<br/>
1<br/>
3<br/>
5<br/>
output.txt :<br/>
4<br/>
3<br/>
1<br/>
5