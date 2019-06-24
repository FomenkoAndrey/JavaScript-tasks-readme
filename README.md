# Проектные работа
1. Слайдер через прототипы
2. Добавление поддержки свайпа для мобильных устройств
3. Слайдер через классы
4. [Подключение и настройка слайдера с использованием плагина OwlCarousel](http://courses.fomenko.top/m2t6/)

# Теоретические вопросы
* Понятие "О большое"
* DOM
* Цикл событий
* Замыкания
* Прототипное наследование
* Как работает ключевое слово this
* Фазы события. Всплытие и перехват
* Способы обмена данными между клиентом и сервером. Основные сетевые протоколы
* Что такое REST и почему эта технология популярна?
* Медленный сайт, что делать?
* Какими фреймворками (библиотеками) вы пользовались? Достоинства / недостатки?
* Чему равно foo.x?
* Что выведется в консоль? Объясните почему

# Задачи с собеседований (FrontEnd)

## Легкие задачи

### #1
> Реализовать функцию isPrime(), которая возвращает true или false, указывая, является ли переданное ей число простым.

### #2
> Реализовать функцию factorial(), которая возвращает факториал числа n!, используя рекурсивный вызов.

### #3
> Реализовать функцию fib(), возвращающую n-ное число Фибоначчи двумя способами:
> * рекурсия - медленный способ
> * вычисление в цикле - быстрый способ

### #4
> Реализовать функцию isSorted(), которая возвращает true или false в зависимости о того, отсортирован ли переданный ей числовой массив.

### #5
> Создать собственную реализацию функции filter().

### #6
> Создать собственную реализацию функции reduce().

### #7
> Реализовать функцию reverse(), которая обращает порядок следования символов переданной ей строки, пользоваться встроенной функцией reverse() для выполнения задания - запрещено.

### #8
>  Создать собственную реализацию функции indexOf() для массивов.

### #9
> Реализовать функцию isPalindrome(), которая возвращает true или false в зависимости от того, является ли переданная ей строка палиндромом. Функция нечувствительна к регистру, к наличию в строке пробелов и спецсимволов.

### #10
> 10.1  
> Создать функция missingNum(), которая будет искать единственное пропущенное значение в неотсортированный массив уникальных чисел, начиная с минимального элемента массива. Функция должна вернуть пропущенное значение.  
>   
> 10.2  
> Реализовать функцию missing(), которая принимает неотсортированный массив уникальных чисел (то есть, числа в нём не повторяются) от 1 до некоего числа n, и возвращает число, отсутствующее в последовательности. В массиве может быть одно и более отсутствующих чисел, либо их может не быть вовсе.

### #11
> Реализовать функцию isBalanced(), которая принимает строку и возвращает true или false, указывая на то, сбалансированы ли фигурные скобки, находящиеся в строке.

### #12
>  Реализовать функцию minMaxReverse(), которая меняет местами минимальное и максимальное значения в неотсортированном числовом массиве.

### #13
> Создать функцию eachItemCount(), которая будет подсчитывать количество повторений каждого элемента в строке.

### #14
> Написать функцию сложения вида add(num1)(num2). Количество слагаемых не ограничено.

### #15
> Написать простую функцию, чтобы узнать равен ли один из входных параметров 3.

### #16
> Объединить два массива с вложенностью [1, [1, 2, [3, 4]], [2, 4]].

## Средняя сложность

### #1
> Создать функцию, прибавляющую 10 к переданному ей числу. Использовать мемоизацию.

### #2
> Реализовать функцию fibonacci(), аналогичную функции из предыдущей группы задач, но при этом использовать мемоизацию.

### #3
> Реализовать функцию isBalanced(), похожую на функцию из предыдущей группы заданий, но поддерживающую три типа скобок: * фигурные {}, квадратные [], и круглые (). При передаче функции строки, в которой имеются неправильные скобочные последовательности, функция должна возвращать false.

### #4
> Реализовать функцию unique(), которая принимает массив чисел и возвращает уникальные числа, найденные в нём.

### #5
> Реализовать функцию intersection(), которая принимает два массива и возвращает их пересечение.

### #6
> Создать реализацию функции sort(), которая сортирует числовой массив за время O(N×log(N)).

### #7
> Реализовать функцию includes(), которая возвращает true или false в зависимости от того, встречается ли переданное ей число в переданном ей отсортированном массиве. Может ли функция решить эту задачу за время O(log(N))?

### #8
> Реализовать функцию assignDeep(), которая похожа на Object.assign(), но выполняет глубокое объединение объектов. Для того, чтобы не усложнять задачу, можно исходить из допущения, что объекты могут содержать только числа и другие объекты (в них не может быть массивов, строк, и так далее).

### #9
> Реализовать функцию reduceAsync(), которая похожа на функцию reduce() из группы простых заданий, но работает с функциями, возвращающими promise-объекты, каждый из которых должен быть разрешён до перехода к следующему.

### #10
> Реализоваьт функцию seq(), пользуясь тем же подходом, что и при работе над функцией reduceAsync(). Эта функция должна принимать массив функций, которые возвращают promise-объекты, и разрешать их один за другим.

## Высокая сложность

### #1
> Реализовать функцию permute(), которая возвращает массив строк, содержащий все пермутации заданной строки.

### #2
> Создать самостоятельную реализацию функции debounce().

### #3
> Реализовать класс LinkedList, не используя встроенные массивы JavaScript ( [] ). Ваш LinkedList должен поддерживать лишь 2 метода: add() и has().

### #4
> Реализоваь класс HashMap, не используя встроенные объекты JavaScript ( {} ) или функцию map(). Вам дана функция hash(), которая принимает строку и возвращает некое число. Эти числа, в основном, уникальны, но возможна и ситуация, когда двум разным строкам соответствуют одинаковые числа.

### #5
> Реализовать класс BinarySearchTree. Он должен поддерживать 4 метода: add(), has(), remove(), и size().
