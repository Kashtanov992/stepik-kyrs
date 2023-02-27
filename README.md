# put your python code here
print ("Здравствуй, мир!")

# put your python code here
print('4', '8', '15', '16', '23', '42')

# put your python code here
print('4')
print('8')
print('15')
print('16')
print('23')
print('42')

# put your python code here
a=input()
b=input()
c=input()
d=input()
print(b, c, d, sep=a)

name=input()
print('Привет,', name, end='!')

language = 'Python'
language = 'Pascal'
print(language)

s1 = 'C++'
s2 = 'Python'
s3 = 'Java'
s3 = s2
s1 = s3

    print(‘Follow PEP8!’)
    print(‘Follow’, ‘PEP8!’)
    print(‘Follow’, ‘PEP8′, sep=’**’)
    name = input()

    # print('Java')
# print('Ruby')
# print('Scala')
print('Python', end='+')  # print('C++')
# print('GO')
print('C#', end='=') # print('C')
print('awesome')
# finish


3
----------------
---------------
--------------
4
a = input()
b = input()
if a == b:
    print('Пароль принят')
else:
    print('Пароль не принят')

    # put your python code here

a = int(input())

if a % 2 == 0:        # если делится без остатка значит четное
    print('Четное')
else:
    print('Нечетное')

    # put your python code here
a = int(input())
first = a // 1000
second = a // 100 - (a // 1000 * 10)
third = (a % 100 - a % 10) / 10
last = a % 10
if first + last == second - third:
    print('ДА')
else:
    print('НЕТ')

# put your python code here

age = int(input())
if age >= 18:
    print('Доступ разрешен')
else:
    print('Доступ запрещен')

# put your python code here

a = int(input())
b = int(input())
c = int(input())
if b - a == c - b:
    print('YES')
else:
    print('NO')

    # put your python code here

a = int(input())
b = int(input())
if a > b:
    print(b)
else:
    print(a)

    # put your python code here

a, b, c, d = int(input()), int(input()), int(input()), int(input())
if a > b:
    a = b
if c > d:
    c = d
if a > c:
    a = c
print(a)

# put your python code here
age = int(input())

if age <= 13:
    print('детство')
if 14 <= age <= 24:
    print('молодость')
if 25 <= age <= 59:
    print('зрелость')
if age >= 60:
    print('старость')

# put your python code here


a = int(input())
b = int(input())
c = int(input())
d = int()
d = 0
if a > 0:
    d = d + a
if b > 0:
    d = d + b
if c > 0:
    d = d + c
print(d)

# put your python code here
a = int(input())
if a > -1 and a < 17:
    print('Принадлежит')
else:
    print('Не принадлежит')

# put your python code here
n = int(input())
if not (-3 < n < 7):
    print('Принадлежит')
else:
    print('Не принадлежит')


    # put your python code here
a = int(input())
if (a > -30 and a <= -2) or (a > 7 and a <= 25):
    print('Принадлежит')
else:
    print('Не принадлежит')


    a = int(input())
if (a % 7 == 0 or a % 17 == 0) and (a >= 1000 and a <= 9999):
    print('YES')
else:
    print('NO')


    # put your python code here
a = int(input())
b = int(input())
c = int(input())
if (a < (b + c)) and (b < (a + c)) and (c < (a + b)):
    print("YES")
else:
    print("NO")


    # put your python code here
year = int(input())

# Делится на 4 без остатка но на 100 с остатком
# или делится на 400 без остатка
if (year % 4 == 0 and year % 100 != 0) or year % 400 == 0:
    print('YES')
else:
    print('NO')


    # put your python code here
r1, c1, r2, c2 = int(input()), int(input()), int(input()), int(input())

# если строка откуда куда равны r1 == r2
# или столбец откуда куда равны c1 == c2
if r1 == r2 or c1 == c2:
    print('YES')
else:
    print('NO')# put your python code here



# put your python code here
x1 = int(input())
y1 = int(input())
x2 = int(input())
y2 = int(input())
x = x2 - x1  # разность координат по оси x
y = y2 - y1  # разность координат по оси y

# Так как король может ходить во все направления, но только на одну клетку, нужно сделать проверку: отличается ли конечная позиция от начальной на 1
if -1 <= x <= 1 and -1 <= y <= 1:
    print('YES')
else:
    print('NO')


# put your python code here
Zoom_Speed = int(input())      # Скорость Зума
Flash_Speed = int(input())     # Скорость Флеша
if Zoom_Speed > Flash_Speed:   # Если Зум быстрее Флеша - Флеш проиграет
    print('NO')
elif Flash_Speed > Zoom_Speed: # Если Флеш быстрее Зума - Флеш выиграет
    print('YES')
else:                          # Если скорость Флеша и Зума одинакова, то выиграет тот, на чьей стороне будет удача
    print("Don't know")

    # put your python code here
a = int(input())
b = int(input())
c = int(input())

if a == b == c:
    print('Равносторонний')
elif a == b or a == c or b == c:
    print('Равнобедренный')
else:
    print('Разносторонний')


    # put your python code here
a, b, c = int(input()), int(input()), int(input())
if a < b < c or a > b > c:
    print(b)
elif b < c < a or b > c > a:
    print(c)
else:
    print(a)


    # put your python code here

m = int(input())
if m == 2:
    print('28')         # если это февраль
elif m <= 7:            # если месяц до июля
    print(30 + m%2 )    # то к 30 дням добавляем остаток от деления месяца
else:
    print(31 - m%2 )    # то из 31 дня убавляем остаток от деления месяца

    # put your python code here
n = int(input())
if n < 60:
    print('Легкий вес')
elif n < 64:
    print('Первый полусредний вес')
elif n < 69:
    print('Полусредний вес')


    # put your python code here
a, b = int(input()), int(input())
s = input()
if s == '+':
    print(a + b)
elif s == '-':
    print(a - b)
elif s == '*':
    print(a * b)
elif s == '/':
    if b == 0:
        print('На ноль делить нельзя!')
    else:
        print(a / b)
else:
    print('Неверная операция')


# put your python code here
a = input()
b = input()
if a == 'красный' and b == 'синий' or a == 'синий' and b == 'красный':
    print('фиолетовый')
elif a == 'красный' and b == 'красный':
    print('красный')
elif a =='красный' and b =='желтый' or a =='желтый' and b =='красный':
    print('оранжевый')
elif a =='желтый' and b =='желтый':
    print('желтый')
elif a =='синий' and b =='желтый'or a =='желтый' and b =='синий':
    print('зеленый')
elif a =='синий' and b =='синий':
    print('синий')
else:
    print('ошибка цвета')


    # put your python code here
n = int(input())

if n < 0 or n > 36:
    print('ошибка ввода')
elif n == 0:
    print('зеленый')
elif 1 <= n <= 10:
    if n % 2 == 0:
        print('черный')
    else:
        print('красный')
elif 11 <= n <= 18:
    if n % 2 == 0:
        print('красный')
    else:
        print('черный')
elif 19 <= n <= 28:
    if n % 2 == 0:
        print('черный')
    else:
        print('красный')
elif 29 <= n <= 36:
    if n % 2 == 0:
        print('красный')
    else:
        print('черный')


        # put your python code here
a1 = int(input())
b1 = int(input())
a2 = int(input())
b2 = int(input())

if a2 > b1 or a1 > b2:  # отсекаем отсутствие пересечений и общей точки
    print('пустое множество')
elif a1 == b2:  # первое условие общей точки
    print(a1)
elif a2 == b1:  # второе условие общей точки
    print(a2)
else:  # осталось найти только пересечение
    if a1 > a2:  # получаем первую точку пересечения путем отсечения лишней точки
        a2 = a1
    if b1 < b2:  # получаем вторую точку пересечения
        b2 = b1
    print(a2, b2)



5
------
-----
----

6
 put your python code here

a = float(input())
b = float(input())

print((a * b) / 2)

# put your python code here

a = float(input())
b = float(input())
c = float(input())
print(a/(c+b))

# put your python code here
n = float(input())
if n == 0:
    print('Обратного числа не существует')
else:
    print(1 / n)

F = float(input())
print(5 / 9 * (F - 32))


# put your python code here
age = int(input())
if 0 < age <= 2:
    print(age * 10.5)
else:
    print(2 * 10.5 + (age - 2) * 4)


    # put your python code here
x = float(input())
print(int(x*10)%10)


# put your python code here
a = float(input())
print(a - int(a))


# put your python code here
a, b, c, d, e = int(input()), int(input()), int(input()), int(input()), int(input())

print('Наименьшее число =', min(a, b, c, d, e))
print('Наибольшее число =', max(a, b, c, d, e))


# put your python code here
a, b, c = int(input()), int(input()), int(input())
print(max(a, b, c))
print(a + b + c - min(a, b, c) - max(a, b, c))
print(min(a, b, c))



# put your python code here
x = int(input())
a = x % 10
b = x // 10 % 10
c = x // 100
if a + b + c == 2 * max(a, b, c):
    print("Число интересное")
else:
    print("Число неинтересное")



a = abs(float(input()))
b = abs(float(input()))
c = abs(float(input()))
d = abs(float(input()))
e = abs(float(input()))

print(a + b + c + d + e)



p1 = int(input())
p2 = int(input())
q1 = int(input())
q2 = int(input())

print(abs(p1 - q1) + abs(p2 - q2))

# put your python code here
a = input()
b = input()
print("Hello", a, b+"!", "You just delved into Python")


# put your python code here

command = input()
dlina = str(len(command))

print('Футбольная команда ' + command + ' имеет длину ' + dlina + ' символов')


# put your python code here

a = input()
b = input()
c = input()

if min (len(a), len(b), len(c)) == len(a):
    print(a)
elif min (len(a), len(b), len(c)) == len(b):
    print(b)
else:
    print(c)
if max (len(a), len(b), len(c)) == len(a):
    print(a)
elif max (len(a), len(b), len(c)) == len(b):
    print(b)
else:
    print(c)


    # put your python code here

a = len(input())
b = len(input())
c = len(input())

if a + b + c == (min(a, b, c) + max(a, b, c))/2*3:
    print("YES")
else:
    print("NO")



# put your python code here

s = input()
if 'синий' in s:
    print('YES')
else:
    print('NO')


    # put your python code here
s = input()
if 'суббота' in s or 'воскресенье' in s:
    print('YES')
else:
    print('NO')

# put your python code here
s = input()
if 'суббота' in s or 'воскресенье' in s:
    print('YES')
else:
    print('NO')


# put your python code here
import math
x1, x2, y1, y2 = float(input()), float(input()), float(input()), float(input())
print(math.hypot(x1 - y1, x2 - y2))




R = float(input())
from math import pi # импорт math и дал ей псевдоним pi
print(pi*R**2)      # площадь круга
print(2*pi*R)       # длина окружности


# put your python code here
import math
a, b  = float(input()), float(input())
sab, pab = a + b, a * b
print(sab / 2)                         # Среднее арифметическое
print(math.sqrt(pab))                  # Среднее геометрическое
print(2 * pab / sab)                   # Среднее гармоническое
print(math.sqrt((a**2 + b**2) / 2))    # Среднее квадратичное



# put your python code here
from math import *
# Поскольку тригонометрические функции работают с радианами, нужно градусы перевести в радианы
x = radians(float(input()))
print(sin(x) + cos(x) + tan(x)**2)

# put your python code here
import math
a = float(input())
print(math.ceil(a) + math.floor(a))



# put your python code here
import math
a = float(input())
print(math.ceil(a) + math.floor(a))

from math import *

a = float(input())
b = float(input())
c = float(input())
d = b**2-4*a*c        # Ищем дискриминант

if d < 0:
    print('Нет корней')
elif d == 0:          # если дискриминант ==0 (имеет один корень)
    print(-b / (2*a))
elif d > 0:           # Если дискриминант >0 то два корня
    x1 = (-b - d ** 0.5) / (2*a)
    x2 = (-b + d ** 0.5) / (2*a)
    print(min(x1, x2))
    print(max(x1, x2))


    # put your python code here
from math import *
n, a = float(input()), float(input())
ans = (n * pow(a, 2)) / (4 * tan(pi / n))
print(ans)




# put your python code here
from math import *
n, a = float(input()), float(input())
ans = (n * pow(a, 2)) / (4 * tan(pi / n))
print(ans)


# put your python code here

for _ in range(10):
    print('Python is awesome!')


    # put your python code here
a = input()
b = int(input())
for _ in range(b):
    print(a)



# put your python code here
for i in range(6):
    print('A' * 3)
for i in range(5):
    print('B' * 4)
print('E')
for i in range(9):
    print('T' * 5)
print('G')



# put your python code here

n = int(input())
for i in range(n):
    print('*' * 19)


    # put your python code here

a = input()
for b in range(10):
    print(b, a)



# put your python code here



n=int(input())
for i in range(n+1):
    print('Квадрат числа', i, 'равен', i**2)





    # put your python code here

n = int(input())
for i in range(n):
    print('*' * (n - i))


7
-----------------------------
