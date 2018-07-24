# Array.diff
Codewars 6kyu Kata

Tags: *Fundamental*, *Arrays*


## Index

[1. Instructions](#1-instructions/) 

[2. Lessons learned](#2-lessons-learned)



## 1. Instructions
```
Your goal in this kata is to implement a difference function, which subtracts one list from another and returns the result.

It should remove all values from list a, which are present in list b.

array_diff([1,2],[1]) == [2]

If a value is present in b, all of its occurrences must be removed from the other:

array_diff([1,2,2,2,3],[2]) == [1,3]
```


## 2. Lessons learned
### Filter
[map, filter, reduce](https://medium.com/jsguru/javascript-functional-programming-map-filter-and-reduce-846ff9ba492d)