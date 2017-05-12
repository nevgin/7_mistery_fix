# Решение квадратных уравнений 

Данная программа вычисляет корни квадратного уравнения

#  Как использовать 

Для использования необходимо импортировать модуль в свою программу на python с помощью команды `from quadratic_equation import get_roots`, после чего можно использовать функцию get_roots(a,b,c).
Где a коэфициент при квадратном члене, b линейном, и c - константа.
В случае отрицательного дискриминанта функция возвращает в качестве корней None,None, в случае нулевого - x1, None, в случае положительного - x1,x2

# Как тестировать 
Для тестирование необходимо в вашем командном интерпретаторе запустить команду:
```bash
python tests.py
```

# Цели проекта 

Код написан в образовательных целях. Курс обучения для web разработчиков - [DEVMAN.org](https://devman.org)
