1 задача


Можем пройти до sqrt(n), т.к любое не простое m представляется в виде
m = a * b, где a - простое
исходя из этого можно заметить, что min(a,b) <= sqrt(n)
поэтому при последовательном переборе до sqrt(n) мы точно его найдем
Алгоритмическая сложность ~ O(sqrt(n))
***
2 задача


Обычное перемножение векторов
Алгоритмическая сложность ~ O(n) , где n - это размерность векторов 
***
3 задача


Стандартный бинарный поиск по значениям монотоной функции f(x)
Алгоритмическая сложность (log(|b-a|))
***
4 задача


Алгоритмическая сложность ~ O(2^n * n)
***
5 задача


???
***
6 задача


Цикл идет сразу по двум элементам массива(с конца и начала)
Алгоритмическая сложность ~ O(n/2), где n - это длина строки
***
7 задача


Перемножение матриц
Алгоритмическая сложность ~ O(n^3)
***
8 задача


Считаем слова в файле
Алгоритмическая сложность ~ O(n), где n - это кол-во символов в файле
***
9 задача


Стандартный алгоритм бинарного поиска.
Алгоритмическая сложность ~ O(k * log(n)), где n - размер массива, а k - это кол-во искомых эл-тов.

***
10 задача


Реализация стека и динамического массива. 
Алгоритмическая сложность ~ O(n) 
***
11 задача


Реализован merge sort и quick sort, с компаратором.
Алгоритмическая сложность ~ O(n + n*log(n) + n + m*log(m)), где n - это кол-во всех бросков, а m - это кол-во неповторяющихся участников.
Итоговая алгоритмическая сложность ~ O(n*log(n))
***
12 задача


Реализовано АВЛ-дерево:
- Добавление эл-та ~ O(log(n))
- Удаление эл-та ~ O(log(n))
- Поиск эл-та ~ O(log(n))
- Расход памяти ~ O(n)
***
13 задача


Алгоритмическая сложность ~ O(n^2)
***
14 задача


Обычный поиск в ширину с использованием очереди.
V - мн-во всех вершин
E - мн-во всех ребер.
|V| = m * n , |E| = 4 * |V|


Алгоритмическая сложность ~ O(|V|+|E\) ~ O(5 |V|) ~ O(m*n)
Расход по памяти ~ O(m+n)
***
15 задача


Реализовано АВЛ-дерево для соотнесения формата (имя-индекс) и поиск за log(n).
Пусть V - это мн-во городов
E - мн-во ребер (путей)
Алгоритм работы программы:
1) Считывам файл одновременно заполняя АВЛ-дерево
2) Производим индексацию
2) Храним граф при помощи списка смежностей:
любому городу n соотносится массив состоящий из пар вида (a,b).
Это означает, что существует путь n -> a (стоимостью b)
3) Запускаем алгоритм Дейкстры
4)Восстанавливаем путь

Алгоритмическая сложность ~ O(n + |V| + (|V|^2 + |E|*log(|V|)) + |E|)  ~ O(|V|^2 + |E|*log(|V|))




