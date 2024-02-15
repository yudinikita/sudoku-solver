# Sudoku Solver | Решатель судоку

Консольная утилита, которая решает судоку (размером: 9*9) значения представлены в двумерном массиве и ищет первое правильное решение методом рекурсивного перебора.

### Обзор

Метод: рекурсивный перебор

Заполнение: через код, в двумерный массив

Сложность судоку: любая

### Как использовать?

В файле `Sudoku-Solver.cpp` заполнить двумерный массив своими значениями

```C++
size_t sud[N*N][N*N] = {
	0,0,5   ,3,0,0    ,0,0,0,
	8,0,0   ,0,0,0    ,0,2,0,
	0,7,0   ,0,1,0    ,5,0,0,
  
	4,0,0   ,0,0,5    ,3,0,0,
	0,1,0   ,0,7,0    ,0,0,6,
	0,0,3   ,2,0,0    ,0,8,0,
  
	0,6,0   ,5,0,0    ,0,0,9,
	0,0,4   ,0,0,0    ,0,3,0,
	0,0,0   ,0,0,9    ,7,0,0
};
```

Вывод результата

```C++
1 4 5 | 3 2 7 | 6 9 8
8 3 9 | 6 5 4 | 1 2 7
6 7 2 | 9 1 8 | 5 4 3
------+-------+------
4 9 6 | 1 8 5 | 3 7 2
2 1 8 | 4 7 3 | 9 5 6
7 5 3 | 2 9 6 | 4 8 1
------+-------+------
3 6 7 | 5 4 2 | 8 1 9
9 8 4 | 7 6 1 | 2 3 5
5 2 1 | 8 3 9 | 7 6 4
Время: 0.021 сек
```

### Информация

Время создания: несколько часов

Дата создания: 05.12.2018

Автор: Юдин Никита

---

> Site [yudinikita.ru](https://yudinikita.ru) &nbsp;&middot;&nbsp;
> Email <mail@yudinikita.ru> &nbsp;&middot;&nbsp;
> GitHub [@yudinikita](https://github.com/yudinikita)
