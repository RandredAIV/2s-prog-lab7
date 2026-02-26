# RU

# Рекурсивные алгоритмы

## Описание

Данная лабораторная работа посвящена изучению рекурсивного программирования,
принципов работы стека вызовов и разработке алгоритмов с использованием рекурсии.

В рамках работы реализованы задачи генерации арифметических выражений
и сопоставления строк с шаблонами с использованием рекурсивных методов
и динамического программирования.

---

## Цели работы

- Изучение принципов рекурсивного программирования
- Анализ работы стека при рекурсивных вызовах
- Разработка алгоритмов на основе рекурсии
- Тестирование и анализ корректности программ

---

## Задание 7.1 — Генерация арифметических выражений

### Условие

Дано число **m**.

Необходимо в последовательности цифр  
1 2 3 4 5 6 7 8 9  
расставить знаки «+» и «-» таким образом,
чтобы значение полученного выражения было равно **m**.

### Пример

m = 122  
12+34-5-6+78+9

### Реализация

- Рекурсивный перебор всех возможных комбинаций знаков
- Вычисление значения сформированного выражения
- Вывод выражений, равных заданному числу

---

## Задание 7.2 — Сопоставление строк с шаблоном

Реализовано сопоставление строки и шаблона с поддержкой специальных символов:

- `?` — соответствует любому одному символу
- `*` — соответствует любой последовательности символов (включая пустую)

Сопоставление должно охватывать всю входную строку полностью.

### Реализация

- Рекурсивный алгоритм сопоставления (C++)
- Алгоритм динамического программирования (Java)
- Проверка корректности работы на тестовых примерах

---

## Используемые языки программирования

- C++
- Java

---

## Как использовать

1. Открыть соответствующий файл задания.
2. Скомпилировать программу выбранного языка.
3. Запустить программу.
4. Ввести необходимые параметры.
5. Получить результат вычислений в консоли.

---

# EN

# Recursive Algorithms

## Description

This laboratory work focuses on recursive programming,
stack behavior during recursive calls,
and development of algorithms using recursion.

The project includes arithmetic expression generation
and wildcard string pattern matching implemented
with recursive techniques and dynamic programming.

---

## Objectives

- Study recursive programming principles
- Analyze stack behavior during recursion
- Develop algorithms using recursion
- Test and validate implemented programs

---

## Task 7.1 — Arithmetic Expression Generation

### Problem

Given a number **m**,

place '+' and '-' signs between digits  
1 2 3 4 5 6 7 8 9  
so that the resulting expression equals **m**.

### Example

m = 122  
12+34-5-6+78+9

### Implementation

- Recursive generation of all possible sign combinations
- Expression evaluation
- Output expressions equal to the target value

---

## Task 7.2 — Wildcard Pattern Matching

Implement string pattern matching with support for:

- `?` — matches any single character
- `*` — matches any sequence of characters (including empty)

The matching must cover the entire input string.

### Implementation

- Recursive matching algorithm (C++)
- Dynamic programming solution (Java)
- Testing on sample cases

---

## Programming Languages

- C++
- Java

---

## How to Use

1. Open the required source file.
2. Compile the required source file.
3. Run the program.
4. Enter input parameters.
5. View the results in the console.
