# lab_5
**Условие**

![усл](https://github.com/eternsss/lab_5/assets/155539142/2839f0db-c3fb-4f6e-af26-a4e75a73527c)

**Описание проделанной работы**

1. В функции is_prime(num) вычисляется простое число. Если число меньше 2, то функция возвращает False. Затем идет цикл, в котором проверяется, делится ли число на какое-либо число от 2 до квадратного корня из этого числа. Если делится, то число не является простым и возвращается False, иначе возвращается True.
2. Функция prime_number_generator() - является генератором для простых чисел. Также проверяем число на простоту, если число подходит, то с помощью yield возвращаем его.
3. Перебираем первые 10 простых чисел и выводим их
4. В переменной mapped_generator мы используем функцию map к генератору. Строка mapped_generator = map(lambda x: x, prime_number_generator()) - возвращает исходное значение
5. В переменной total_sum мы суммируем первые 10 простых чисел
6. Выводим сумму 


**Результат**

![результат](https://github.com/eternsss/lab_5/assets/155539142/96abc5a0-4177-4065-8b82-3a2448308f9b)

**Ссылки на используемые материалы**

[Функция reduce()](https://docs-python.ru/standart-library/modul-functools-python/funktsija-reduce-modulja-functools/)

[Функция filter()](https://pythonru.com/uroki/funkcija-filter-dlja-nachinajushhih)

[Функция map()](https://www.digitalocean.com/community/tutorials/how-to-use-the-python-map-function-ru)

[Генераторы](https://skillbox.ru/media/code/generatory_python_chto_eto_takoe_i_zachem_oni_nuzhny/)
