# Kotlin

- [1. Kotlin Introduction / Введение в язык Kotlin](./docs/01_Intro.md)
  - [Basic overview / Общий обзор](./docs/01_Intro.md#basic-overview--общий-обзор)
    - [What is Kotlin? / Что такое Kotlin?](./docs/01_Intro.md#what-is-kotlin--что-такое-kotlin)
    - [Why Use Kotlin? / Почему Kotlin?](./docs/01_Intro.md#why-use-kotlin--почему-kotlin)
    - [Usage / Область применения](./docs/01_Intro.md#usage--область-применения)
  - [Kotlin Get Started / Что такое Kotlin](./docs/01_Intro.md#kotlin-get-started--что-такое-kotlin)
    - [Экосистема Kotlin](./docs/01_Intro.md#экосистема-kotlin)
    - [История Kotlin](./docs/01_Intro.md#история-kotlin)
- [2. Kotlin Basics / Основы языка Kotlin](./docs/02_Basics.md)
  - [Kotlin Syntax / Структура программы и базовый синтаксис](./docs/02_Basics.md#kotlin-syntax--структура-программы-и-базовый-синтаксис)
    - [Main / Точка входа](./docs/02_Basics.md#main--точка-входа)
    - [Main Parameters / Параметры функции `main`](./docs/02_Basics.md#main-parameters--параметры-функции-main)
    - [Инструкции и блоки кода](./docs/02_Basics.md#инструкции-и-блоки-кода)
    - [Определение имени пакета и импорт](./docs/02_Basics.md#определение-имени-пакета-и-импорт)
  - [Kotlin Input/Output (Print Text) / Консольный ввод и вывод](./docs/02_Basics.md#kotlin-inputoutput-print-text--консольный-ввод-и-вывод)
    - [Kotlin Output (Print) / Вывод в стандартный поток](./docs/02_Basics.md#kotlin-output-print--вывод-в-стандартный-поток)
      - [The `println()` function / Функция `println()`](./docs/02_Basics.md#the-println-function--функция-println)
      - [The `print()` function / Функция `print()`](./docs/02_Basics.md#the-print-function--функция-print)
    - [Ввод с консоли](./docs/02_Basics.md#ввод-с-консоли)
      - [Функция `readLine`](./docs/02_Basics.md#функция-readline)
      - [Сравнение `readLine()`, `readln()`, `readlnOrNull()`](./docs/02_Basics.md#сравнение-readline-readln-readlnornull)
  - [Kotlin Comments / Комментарии](./docs/02_Basics.md#kotlin-comments--комментарии)
    - [Single-line Comments / Однострочные комментарии](./docs/02_Basics.md#single-line-comments--однострочные-комментарии)
    - [Multi-line Comments / Многострочные комментарии](./docs/02_Basics.md#multi-line-comments--многострочные-комментарии)
  - [Kotlin Variables / Переменные](./docs/02_Basics.md#kotlin-variables--переменные)
    - [Variables declaration / Объявление переменных](./docs/02_Basics.md#variables-declaration--объявление-переменных)
    - [Изменяемые и неизменяемые переменные](./docs/02_Basics.md#изменяемые-и-неизменяемые-переменные)
    - [Notes on `val` / По поводу `val`](./docs/02_Basics.md#notes-on-val--по-поводу-val)
    - [Variable Type / Тип переменной](./docs/02_Basics.md#variable-type--тип-переменной)
    - [Compile-time constants / Определение констант](./docs/02_Basics.md#compile-time-constants--определение-констант)
    - [Display Variables / Вывод переменных](./docs/02_Basics.md#display-variables--вывод-переменных)
    - [Variable Names / Именование переменных](./docs/02_Basics.md#variable-names--именование-переменных)
  - [Kotlin Data Types / Типы данных](./docs/02_Basics.md#kotlin-data-types--типы-данных)
    - [Data Types overview / Обзор типов данных](./docs/02_Basics.md#data-types-overview--обзор-типов-данных)
    - [Numbers / Числа](./docs/02_Basics.md#numbers--числа)
    - [Integer Types / Целочисленные типы](./docs/02_Basics.md#integer-types--целочисленные-типы)
      - [`Byte`](./docs/02_Basics.md#byte)
      - [`Short`](./docs/02_Basics.md#short)
      - [`Int`](./docs/02_Basics.md#int)
      - [`Long`](./docs/02_Basics.md#long)
    - [Difference Between `Int` and `Long` / Отличие `Int` от `Long`](./docs/02_Basics.md#difference-between-int-and-long--отличие-int-от-long)
    - [Floating Point Types / Числа с плавающей точкой](./docs/02_Basics.md#floating-point-types--числа-с-плавающей-точкой)
      - [Scientific Numbers / Научная нотация](./docs/02_Basics.md#scientific-numbers--научная-нотация)
    - [Booleans / Логический тип `Boolean`](./docs/02_Basics.md#booleans--логический-тип-boolean)
      - [Boolean Values / Логические значения](./docs/02_Basics.md#boolean-values--логические-значения)
      - [Boolean Expression / Логическое выражение](./docs/02_Basics.md#boolean-expression--логическое-выражение)
    - [Characters / Символы](./docs/02_Basics.md#characters--символы)
    - [Strings / Строки](./docs/02_Basics.md#strings--строки)
      - [Kotlin Strings / О строках](./docs/02_Basics.md#kotlin-strings--о-строках)
      - [Access a String / Доступ к элементам строки](./docs/02_Basics.md#access-a-string--доступ-к-элементам-строки)
      - [String Length / Длина строки](./docs/02_Basics.md#string-length--длина-строки)
      - [String Functions / Строковые функции](./docs/02_Basics.md#string-functions--строковые-функции)
      - [Comparing Strings / Сравнение строк](./docs/02_Basics.md#comparing-strings--сравнение-строк)
      - [Finding a String in a String / Поиск подстроки](./docs/02_Basics.md#finding-a-string-in-a-string--поиск-подстроки)
      - [Quotes Inside a String / Кавычки внутри строк](./docs/02_Basics.md#quotes-inside-a-string--кавычки-внутри-строк)
      - [String Concatenation / Конкатенация строк](./docs/02_Basics.md#string-concatenation--конкатенация-строк)
      - [String Templates \& Interpolation / Шаблоны строк и интерполяция](./docs/02_Basics.md#string-templates--interpolation--шаблоны-строк-и-интерполяция)
    - [Arrays / Массивы](./docs/02_Basics.md#arrays--массивы)
    - [Выведение типа](./docs/02_Basics.md#выведение-типа)
    - [Статическая типизация](./docs/02_Basics.md#статическая-типизация)
    - [Type Conversion / Преобразование типов](./docs/02_Basics.md#type-conversion--преобразование-типов)
    - [Тип `Any`](./docs/02_Basics.md#тип-any)
  - [Kotlin Operators / Операции](./docs/02_Basics.md#kotlin-operators--операции)
    - [Kotlin Operators / Операторы](./docs/02_Basics.md#kotlin-operators--операторы)
    - [Операции с числами](./docs/02_Basics.md#операции-с-числами)
      - [Arithmetic Operators / Арифметические операции](./docs/02_Basics.md#arithmetic-operators--арифметические-операции)
    - [Bitwise operators / Поразрядные операции](./docs/02_Basics.md#bitwise-operators--поразрядные-операции)
    - [Kotlin Assignment Operators / Операции присвоения](./docs/02_Basics.md#kotlin-assignment-operators--операции-присвоения)
    - [Условные выражения](./docs/02_Basics.md#условные-выражения)
      - [Kotlin Comparison Operators / Операции отношения](./docs/02_Basics.md#kotlin-comparison-operators--операции-отношения)
      - [Kotlin Logical Operators / Логические операции](./docs/02_Basics.md#kotlin-logical-operators--логические-операции)
  - [Управляющие конструкции. Условия и циклы](./docs/02_Basics.md#управляющие-конструкции-условия-и-циклы)
    - [Kotlin Conditions / Условия](./docs/02_Basics.md#kotlin-conditions--условия)
    - [Kotlin If ... Else / Условная конструкция if...else](./docs/02_Basics.md#kotlin-if--else--условная-конструкция-ifelse)
      - [Kotlin `if`](./docs/02_Basics.md#kotlin-if)
      - [Kotlin `else`](./docs/02_Basics.md#kotlin-else)
      - [Kotlin `else if`](./docs/02_Basics.md#kotlin-else-if)
      - [Возвращение значения из `if`](./docs/02_Basics.md#возвращение-значения-из-if)
    - [Kotlin If..Else Expressions / Условное выражение `if`](./docs/02_Basics.md#kotlin-ifelse-expressions--условное-выражение-if)
    - [Kotlin When / Условная конструкция `when`](./docs/02_Basics.md#kotlin-when--условная-конструкция-when)
      - [Выражение else](./docs/02_Basics.md#выражение-else)
      - [Сравнение с набором значений](./docs/02_Basics.md#сравнение-с-набором-значений)
      - [`when` и динамически вычисляемые значения](./docs/02_Basics.md#when-и-динамически-вычисляемые-значения)
      - [`when` как альтернатива для `if..else`](./docs/02_Basics.md#when-как-альтернатива-для-ifelse)
      - [Возвращение значения](./docs/02_Basics.md#возвращение-значения)
    - [Kotlin `when` expression / Условное выражение `when`](./docs/02_Basics.md#kotlin-when-expression--условное-выражение-when)
    - [Loops / Циклы](./docs/02_Basics.md#loops--циклы)
      - [Kotlin While Loop / Цикл `while`](./docs/02_Basics.md#kotlin-while-loop--цикл-while)
      - [The Do..While Loop / Цикл `do..while`](./docs/02_Basics.md#the-dowhile-loop--цикл-dowhile)
      - [Сравнение `while` и `do..while`](./docs/02_Basics.md#сравнение-while-и-dowhile)
      - [Kotlin For Loop / Цикл `for`](./docs/02_Basics.md#kotlin-for-loop--цикл-for)
      - [Traditional For Loop / Традиционный цикл for](./docs/02_Basics.md#traditional-for-loop--традиционный-цикл-for)
      - [Kotlin Break and Continue / Операторы `continue` и `break` в циклах](./docs/02_Basics.md#kotlin-break-and-continue--операторы-continue-и-break-в-циклах)
        - [Kotlin Continue](./docs/02_Basics.md#kotlin-continue)
        - [Kotlin Break](./docs/02_Basics.md#kotlin-break)
  - [Flow Control / Управление потоком](./docs/02_Basics.md#flow-control--управление-потоком)
    - [Операторы перехода](./docs/02_Basics.md#операторы-перехода)
    - [Метки операторов break и continue](./docs/02_Basics.md#метки-операторов-break-и-continue)
    - [Возврат к меткам](./docs/02_Basics.md#возврат-к-меткам)
