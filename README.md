# C-2019
## C/C++ university lesson

Compare and start by *gcc [lesson]/[task].c && a*

### [Тема 1. Введение](https://vk.com/doc296044466_516282976?hash=5f3c57c938962b01bb&dl=31b754de429bb3304f)
> 1. Даны два ненулевых числа. Найти их сумму, разность, произведение и частное.
2. Даны два числа. Найти среднее арифметическое их квадратов и среднее арифметическое их модулей.
3. Скорость лодки в стоячей воде V км/ч, скорость течения реки U км/ч (U < V). Время движения лодки по озеру T1 ч, а по реке (против течения) – T2 ч. Определить путь S, пройденный лодкой.
4. Скорость первого автомобиля V1 км/ч, второго – V2 км/ч, расстояние между ними S км. Определить расстояние между ними через T часов, если автомобили удаляются друг от друга.
5. Дана длина окружности. Найти площадь круга, ограниченного этой окружностью. В качестве значения Pi использовать 3.14.
6. Даны координаты трех вершин треугольника (x1, y1), (x2, y2), (x3, y3). Найти его периметр и площадь

### [Тема 2. Структура программы. Структура if](https://vk.com/doc296044466_516282979?hash=7064363e6d1bbd92e8&dl=3d1994bc15c56d8e13)
> 1. Определить по результатам сессии, состоящей из трех экзаменов, тип учащегося: отличник, хорошист или двоечник.
2. Определить взаимное расположение двух окружностей. Даны координаты центров и радиусы окружностей (всего 4 варианта взаимного расположения).
3. Даны целочисленные координаты точки плоскости (x,у). Определить область, которой принадлежит эта точка: номер четверти, или имя оси, или начало координат.
4. Определить вид треугольника по заданным длинам сторон.
5. Значения переменных x, y, z поменять местами так, чтобы они оказались упорядоченными по возрастанию: x <= y <= z.
6. Даны четыре целых числа, одно из которых отлично от трех других, равных между собой. Найти порядковый номер этого числа.

### [Тема 3. Структура программы. Структура switch](https://vk.com/doc296044466_516282981?hash=175df65fca2a427014&dl=45fd8d6aad3433fe26)
> 1. По заданному числу в диапазоне 100—999 выводит строку — словесное описание данного числа, например, 256 — «двести пятьдесят шесть», 814 — «восемьсот четырнадцать».
2. По заданному возрасту в диапазоне 20—69 выводит строку — словесное описание указанного возраста, правильно согласуя число со словом «год», например, 20 — «двадцать лет», 32 — «тридцать два года», 41 — «сорок один год».
3. По номеру года выводит его название в восточном календаре. В восточном календаре принят 60-летний цикл, состоящий из 12-летних подциклов, обозначаемых названиями цвета: зеленый, красный, желтый, белый и черный. В каждом подцикле год носит название животного: крысы, коровы, тигра, зайца, дракона, змеи, лошади, овцы, обезьяны, курицы, собаки и свиньи. Известно, что 1984 год был началом цикла — годом зеленой крысы.
4. Сумма прописью. Дано вещественное число R, (0 <= R <= 100) с не более чем двумя значащими цифрами после десятичной точки. Считаем, что R обозначает денежную сумму в рублях. Вывести на экран правильно согласованную фразу, обозначающую R, в виде "X рублей Y копеек"(например, число 22.21 должно быть выведено в виде "22 рубля 21 копейка").

### [Тема 4. Структура программы. Операторы цикла](https://vk.com/doc296044466_516282984?hash=46a47d7fce73615832&dl=e75f7a5a81382bc272)
> 1. Написать программу, которая для заданного целого неотрицательного числа выводит инверсию его разрядов. Пример: результат инверсии числа 3725 равен 5273.
2. Даны целые положительные числа N и K. Найти сумму 1K+2K+3K+…+NK.
3. Для заданного числа N (0 < N < 27), реализовать программу, которая выводит все числа из диапазона от 0 до 999, сумма цифр которых равна N.
4. Последовательность чисел Фибоначчи { fi } задается рекуррентным соотношением: f0 = 0; f1 = 1; fk = fk-2 + fk-1 , k=2,3,4, … ; Вычислить сумму всех чисел Фибоначчи, которые не превосходят заданное число m.
5. Дано вещественное число A и целое N. Определить значение следующего выражения: 1-A+A2-A3+…+(-1)NAN. Замечание: условный оператор не использовать.
6. Написать программу, которая выводит на консоль таблицу умножения

### [Тема 5. Массивы](https://vk.com/doc296044466_516282962?hash=9f37563541114dd774&dl=a1046f767cadf0fb60)
> 1. Задан массив из N вещественных элементов. Вычислить сумму элементов массива, имеющих четные индексы.
2. Задан массив из N вещественных элементов. Определить количество элементов массива, которые больше своего левого соседа.
3. Задан массив из N целочисленных элементов. Определить число чередований знака, т.е. число переходов с «-» на «+» и с «+» на «-».
4. Задан массив из N вещественных элементов. Вычислить сумму элементов массива, индексы элементов которых образуют последовательность чисел Фибоначчи.
5. Задан массив из N вещественных элементов. Удалить из массива элементы, величина которых находится в интервале (a, b) (числа a и b (0 < a < b) — даны), оставляя неизменным порядок следования остальных элементов.
6. Задан массив Y[n], элементами которого являются целые числа. Преобразовать массив так, чтобы все его нечетные элементы оказались в конце. Порядок элементов в четной и нечетной частях может измениться.

### [Тема 6. Массивы](https://vk.com/doc296044466_516283087?hash=7d0d62bb780c886b2e&dl=6f4a0b53e86c5dbb2c)
> 1. Дан массив целых чисел размера N. Найти количество его локальных минимумов, т.е. случаев, когда элемент массива меньше своих соседних.
2. Задан массив, состоящий из N целых чисел. Элементы массива, стоящие на четных номерах, отсортировать в порядке возрастания. Порядок и расположение остальных элементов не должен измениться.
3. Дан целочисленный массив размера N. Найти минимальный из его локальных максимумов.
4. Задан массив, состоящий из N целых чисел. Элементы массива, являющиеся четными, отсортировать в порядке возрастания. Порядок и расположение остальных элементов не должен измениться.
5. Дан целочисленный массив размера N. Определить количество участков, на которых его элементы монотонно возрастают.
6. Заданы два целочисленных массива длины N и M соответственно. Каждый массив не содержит повторений. Построить массив, являющийся объединением заданных наборов.

### [Тема 7. Функции](https://vk.com/doc296044466_516283089?hash=ebf8002835b214dd2b&dl=e5df48e96f715fcba3)
> 1. Написать функции:
    a. Ввод действительного числа с контролем (скопировать)
    b. Ввод целого числа с контролем
    c. Ввод, вывод действительного массива (скопировать)
    d. Ввод, вывод целочисленного массива
    e. Генерация значений действительного массива
    f. Генерация значений целочисленного массива
2. Написать функцию main, в которой тестируются все написанные функции
3. Все функции написать в едином файле
4. Сохранить этот файл на флешке, для использования в последующих лабораторных работах
5. Дополнительно
    a. Поиск номера максимального элемента действительного массива
    b. Поиск номера максимального элемента целочисленного массива
    c. Поиск номера минимального элемента действительного массива
    d. Поиск номера минимального элемента целочисленного массива
    e. Поиск номера заданного элемента действительного массива
    f. Поиск номера заданного элемента целочисленного массива
    g. Сортировка элементов действительного массива
    h. Сортировка элементов целочисленного массива

### [Тема 8. Функции](https://vk.com/doc296044466_516283091?hash=1ac49421526fd26b0f&dl=943a92f6dc474a8a3c)

### [Тема 9. Сортировка](https://vk.com/doc296044466_516283092?hash=987239456f53ff142c&dl=ed57c8e49093795add)

### [Тема 10. Рекурсивные функции](https://vk.com/doc296044466_516283093?hash=fc372a804904b77886&dl=2ef8e7466cae11b619)
### [Тема 11. Указатели и динамические массивы](https://vk.com/doc296044466_516283095?hash=ad71e5e37d8e9968bd&dl=e4896b186ae606aa9a)
### [Тема 12. Модульная структура программы](https://vk.com/doc296044466_516283096?hash=4212ba79f322b6b5c4&dl=e014f4000b73ea5ddb)
### [Тема 13. Строки](https://vk.com/doc296044466_516283097?hash=9af3e36214697a1329&dl=2e5968ab1e8bd9f878)
### [Тема 14. Файлы](https://vk.com/doc296044466_516283099?hash=d06f928071c77484e5&dl=d649d905011bfcb446)
### [Тема 15. Структуры](https://vk.com/doc296044466_516283085?hash=a6e5b07249415e0e29&dl=24e5032fa8a961d44f)

# [Учебно-методическое пособие](https://vk.com/doc296044466_516282965?hash=2f1e5fde53dff85212&dl=ef9a53cf0a5682eb05)
