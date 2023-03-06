# Yandex Inerview Kit

--- 

## Полезные ссылки:
- https://proglib.io/p/slozhnost-algoritmov-i-operaciy-na-primere-python-2020-11-03 - сложность операций в Python
- https://pythonist.ru/obhod-dvoichnogo-dereva-na-python/ - обход дерева
- https://eddmann.com/posts/depth-first-search-and-breadth-first-search-in-python/ - BFS/DFS
- https://pythonist.ru/algoritmy-sortirovki-s-python/ - алгоритмы сортировки
- https://habr.com/ru/post/550088/ - Хабр. Собеседование в Яндекс. Театр абсурда.

---

## Содержание
1. [Последовательность из 0 и 1](#1)
2. [Списки](#2)
3. [Деревья](#3)
4. [Отрезки](#4)
5. [Скобки/полиз](#5)
6. [Палиндромы/анаграммы](#6)
7. [Геометрические](#7)
8. [Реализовать класс](#8)
9. [Строки/массивы](#9)
  + [Проверить](#9_1)
  + [Найти](#9_2)
  + [Изменить](#9_3)
10. [Веб](#10)
11. [Жизненные](#11)
12. [Математические](#12)

> Yandex_pt1 [1-34]

> Yandex_pt2 [35-68]

> Yandex_pt3 [69-96]

---

## Задачи

<a name="1"></a> 
## [ Последовательность из 0 и 1 ]
- 2	[Longest Subarray of 1's After Deleting One Element](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element)
- 19 [Max Consecutive Ones II](https://leetcode.com/problems/max-consecutive-ones-ii) - можете превратить в 1 не более одного 0
- 39 [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii) - вы можете поменять не более k нулей на 1
- 69 Максимальная длина из "1" после удаления одного "0"

<a name="2"></a> 
## [ Списки ]
- 14 [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list) [1, 2, 3, 4, 5] -> [5, 4, 3, 2, 1]
- 16 [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists) [[1, 4, 5], [1, 3, 4], [2, 6]] -> [1, 1, 2, 3, 4, 4, 5, 6]
- 36 [Add Two Numbers](https://leetcode.com/problems/add-two-numbers) [2, 4, 3] + [5, 6, 4] -> [7, 0, 8]
- 38 [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists) [1, 2, 4], [1, 3, 4] -> [1, 1, 2, 3, 4, 4]
- 50 [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list) [1, 2, 3, 4, 5], 2 -> [1, 2, 3, 5]
- 67 [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list) [1, 2, 2, 1] -> True

<a name="3"></a> 
## [ Деревья ]
- 28 [Symmetric Tree](https://leetcode.com/problems/symmetric-tree) Симметричное ли дерево?
- 30 [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree) Является ли дерево БДП?
- 42 [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree) - Наименьший общий предок 
- 53 [Lowest Common Ancestor of a Binary Tree III](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii) - Есть ссылка на рожителя
- 60 [Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst) - вернуть сумму значений всех узлов со значением в диапазоне [low, high]
- 63 [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum) - вернуть максимальную сумму пути любого непустого пути
- 76 Найти наибольшую сумму в дереве
- 79 Binary Tree Zigzag Level Order Traversal - вывести древо зигзагом
- 89 Сериализация/десериализация BST 
- 97 Path Sum - Существует ли путь от корня до листа, который равен таргету?

<a name="4"></a> 
## [ Отрезки ]
- 22 [Merge Intervals](https://leetcode.com/problems/merge-intervals) - найти интервалы, которыми можно перекрыть заданные
- 25 [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii) - найти минимальное количество конференц-залов
- 34 [Interval List Intersections](https://leetcode.com/problems/interval-list-intersections) - найти пересечение этих двух списков интервалов

<a name="5"></a> 
## [ Скобки/полиз ]
- 13 [Generate Parentheses](https://leetcode.com/problems/generate-parentheses) - сгенерировать всевозможные скобочные последовательности
- 18 [Valid Parentheses](https://leetcode.com/problems/valid-parentheses) - проверить, сбалансирована ли скобочная последовательность
- 45 [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation) - ПОЛИЗ

<a name="6"></a> 
## [ Палиндромы/анаграммы ]
- 6	[Valid Palindrome](https://leetcode.com/problems/valid-palindrome)
- 26 [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string)

<a name="7"></a> 
## [ Геометрические ] 
- 1	[Line Reflection](https://leetcode.com/problems/line-reflection) - существует ли такая прямая, что после отражения всех точек через данную прямую множество исходных точек совпадает с множеством отраженных
- 55 [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle) - найти наибольший прямоугольник из 1
- 72 Определить номер первой колонки, в которой есть хоть одна единица
- 90 Развернуть матрицу на 90 градусов
- 91 [Spiral Matrix II](https://leetcode.com/problems/spiral-matrix-ii) - Генерация спиральной матрицы

<a name="8"></a> 
## [ Реализовать класс ]
- 5	[Zigzag Iterator](https://leetcode.com/problems/zigzag-iterator)
- 11 [Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1)
- 12 [LRU Cache](https://leetcode.com/problems/lru-cache)
- 32 [Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator) - [[[1], 2, [4]], [4, [5]]] -> [1, 2, 3, 4, 5] 
- 35 [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks) - реализовать очередь через стек
- 52 [Max Stack](https://leetcode.com/problems/max-stack) - операции с максимальным числом в стеке

<a name="9"></a> 
## [ Строки/массивы ] 
<a name="9_1"></a> 
### Проверить
- 7	[One Edit Distance](https://leetcode.com/problems/one-edit-distance) - Строку можно получить из другой одним редактированием
- 15 [Permutation in String](https://leetcode.com/problems/permutation-in-string) - Вернуть true, если одна из перестановок s1 является подстрокой s2.
- 48 [Is Subsequence](https://leetcode.com/problems/is-subsequence) - Является ли одна строка подпоследовательностью другой
- 73 Можно ли получить одну строку из другой за <= 1 одно исправление

<a name="9_2"></a> 
### Найти

- 8	[Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k) - Вернуть общее количество подмассивов, **сумма которых равна k**
- 99 Найти индекс подмассива, **сумма которого равна k**
- 64 [Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum) - непрерывная подпоследовательность, **сумма которой кратна k**
- 95 [Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) - Найти количество не пустых подмассивов, **сумма которых кратна k**
- 70 Найти подотрезок с наименьшей суммой по модулю
- 71 Найти подотрезок с наибольшей суммой
---
- 54 [Longest Substring with At Most Two Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters) - Самая длинная подстрока, элементы встречаются максимум два раза
- 29 [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters) - Самая длинная подстрока без повторяющихся символов
- 33 [Consecutive Characters](https://leetcode.com/problems/consecutive-characters) - Найти максимальную длину непустой подстроки, содержащей только один уникальный символ
- 74 Найти подстроку, которая совпадает с точностью до перестановки
- 40 [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring) - Самая длинная подстрока палиндром
- 78 Minimum Window Substring - минимальная подстрока, содержащая перестановку
- 24 [Two Sum](https://leetcode.com/problems/two-sum) - Найти два числа, которые дают таргет
- 57 [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) - два числа, которые дают таргет
- 96 3 Sum - Найти три числа, которые дают таргет
- 46 [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays) - Найти средний элемент из двух слитых отсортированных отрезков
- 43 [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii) - Пересечение двух массивов (кол-во сохраняется)
- 51 [Perfect Squares](https://leetcode.com/problems/perfect-squares) - 12 -> 3 (4 + 4 + 4 = 12)
- 56 [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array) - [4,6,8,9,1,3] (Найти за nlogn)
- 59 [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array) - минимум в сдвинутом массиве
- 62 [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self) - a -> res (res[i] = a[0]*...*a[i-1]*a[i+1]*...)
- 68 [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string) - Найти индекс первого уникального символа
- 84 Minimum Operations to Make Array Equal - найти минимальное количество операций, чтобы сделать все элементы равными
- 86 Find Smiles Position - найти в строке позиции смайлов вида :-)
- 94 [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements) - Найти K ближайших элементов
- 81 Count Number of Occurrences in a Sorted Array - в отсортированном массивее найти количество вхождений
- 92 [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string) - Найти первое вхождение одной строки в другую
- 93 [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) - Найти первое и последнее вхождение в отсортированном списке

<a name="9_3"></a> 
### Изменить
- 3	[Summary Ranges](https://leetcode.com/problems/summary-ranges) - [0, 1, 2, 4, 5, 7] -> ["0->2", "4->5", "7"]
- 4	[String Compression](https://leetcode.com/problems/string-compression) - ["a","a","b","b","c","c","c"] -> ["a","2","b","2","c","3"]
- 9	[Move Zeroes](https://leetcode.com/problems/move-zeroes) - [0,1,0,3,12] -> [1,3,12,0,0]
- 10 [Group Anagrams](https://leetcode.com/problems/group-anagrams) - ["eat","tea","tan","ate","nat","bat"] -> [["bat"],["nat","tan"],["ate","eat","tea"]]
- 37 [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array) - Слить два неубывающих массива в один неубывающий
- 49 [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array) - [-4,-1,0,3,10] -> [0,1,9,16,100]
- 58 [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array) - [0,0,1,1,1,2,2,3,3,4] -> [0,1,2,3,4,,,,,]
- 61 [Partition Labels](https://leetcode.com/problems/partition-labels) - Разделить строку на как можно больше частей, чтобы каждая буква встречалась не более чем в одной части
- 65 [Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii) - Перевернуть все слова в строке
- 85 Remove All Occurrences of a Substring

<a name="10"></a> 
## [ Веб ]
- 17 [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls)
- 21 [Design Hit Counter](https://leetcode.com/problems/design-hit-counter)
- 47 [Simplify Path](https://leetcode.com/problems/simplify-path) - упростить путь url
- 80 Logger Rate Limiter

<a name="11"></a> 
## [ Жизненные ]
- 20 [Maximize Distance to Closest Person](https://leetcode.com/problems/maximize-distance-to-closest-person) - посадить человека дальше от всех
- 23 [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water) - найти количество воды после дождя
- 31 [Number of Islands](https://leetcode.com/problems/number-of-islands) - найти количество островов из 1
- 41 [Jewels and Stones](https://leetcode.com/problems/jewels-and-stones)
- 77 Найти максимальное число постояльцев, которые одновременно проживали в гостинице
- 82 Minimize the Maximum Difference between Heights
- 87 Здания, которые могут увидеть закат
- 88 Здания, которые могут увидеть океан
- 96 [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary) - Проложить путь для аэропортов

<a name="12"></a> 
## [ Математические ]
- 27 [Implement Rand10() Using Rand7()](https://leetcode.com/problems/implement-rand10-using-rand7) - реализовать рандомайзер до 10 через ранд до 7
- 44 [Missing Number](https://leetcode.com/problems/missing-number) - Вернуть пропущенное число из диапазона [0..n]
- 66 [Add Strings](https://leetcode.com/problems/add-strings) - Сложить строки как числа
- 75 Перевернуть int
- 83 Find smallest missing number in sorted array - найти наименьшее пропущенное число

## Training list (Yandex_training.ipynb)

Список задач, которые рекомендуют прорешать перед собеседованием

![Training list](https://github.com/nikolskiyv/algorithm_practice/blob/master/training_list.png)
