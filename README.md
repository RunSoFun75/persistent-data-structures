## Неизменяемые структуры данных

Неизменяемые структуры данных — это структуры данных, которые при внесении в них каких-то изменений сохраняют все свои предыдущие состояния и доступ к этим состояниям. 

## 1. Задача

Реализовать библиотеку со следующими структурами данных в неизменяемых вариантах: 
+ Массив (константное время доступа, переменная длина). 
+ Двусвязный список. 
+ Ассоциативный массив (на основе Hash-таблицы, либо бинарного дерева). 

## 2. Требования

+ Требуется собственная реализация перечисленных структур. 
+ Требуется реализовать перечисленные структуры данных на основе метода толстых узлов (fat-node). 
+ Требуется реализовать единый API для всех перечисленных структур данных. 

## 3. Дополнительные требования

+ Требуется обеспечить произвольную вложенность данных (по аналогии с динамическими языками), не отказываясь при этом полностью от типизации посредством generic/template. 
+ Требуется реализовать универсальный undo-redo механизм для перечисленных структур данных с поддержкой каскадности (для вложенных структур). 
+ Требуется реализовать более эффективное по скорости доступа представление структур данных, чем метод толстых узлов (fat-node). 
+ Требуется расширить экономическое использование памяти на операцию преобразования одной структуры к другой.
+ Требуется реализовать поддержку транзакционной памяти (TSM). 

## 4. Реализация

+ Реализация неизменяемых структур данных будет осуществляться путем применения метода копирования пути.

## 5. Авторы 

+ Базаров Андрей, гр. 23223. 
+ Королев Андрей, гр. 23223. 
