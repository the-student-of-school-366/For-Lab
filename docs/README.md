#Документация
## Общее описание решения
- В процессе выполнения данной лабораторной работы был создан репозиторий на GitHub, куда был загружено 2 файла с геометрическими формуллами на языке python. Так же проект имеет fork с другим проектом.
## Описание функций с примерами вызова
### triangle.py

- def area(a, h):  
    return a * h / 2

      '''Принимает на вход сторону и высоту треугольника и возвращвет его плошадь'''

    example:
    input: 2, 5
    output: 5

- def perimeter(a, b, c):  
      return a + b + c

      '''Принимает на вход стороны треугольника и возвращвет его периметр'''
    example:
    input: 2, 3, 4
    output: 9

### rectangle.py
- def area(a, b):
      return a * b

        '''Принимает на вход стороны прямоугольника и возвращвет его плошадь'''
        example:
        input: 2, 3
        output: 12

def perimeter(a, b):
    return (a + b)*2

    '''Принимает на вход сторонЫ прямоугольника и возвращвет его периметр'''
    example:
    input: 3, 4
    output: 6
### circle.py
import math


def area(r):
    return math.pi * r * r 

    '''Принимает радиус окуружности и возвращает площадь окружности.'''
    example:
    input: 3
    output: 28.2743...
def perimeter(r):
    return 2 * math.pi * r

    '''Принимает радиус окуружности и возвращает длинну окружности.'''
    example:
    input: 3, 4
    output: 6

### square.py
def area(a):
    return a * a

    '''Принимает на вход сторону квадрата и возвращвет его плошадь'''
    example:
    input:  4
    output: 16

def perimeter(a):
    return 4 * a

    '''Принимает на вход сторону квадрата и возвращвет его периметр'''
    example:
    input: 3
    output: 12

##история изменения проекта
### commit db1a640e5e4058618c15e68950723d7dd3d8e386 (HEAD -> new_features_409730)
    Author: Uldanov Ananda <ananda.uldanov.2005@gmail.com>
    Date:   Wed Sep 27 12:11:13 2023 +0300
    fixed mistake in rectangle,py
### commit 30a65b3a9b96ee25df5831985a255cbba8c23a5f

    Author: Uldanov Ananda <ananda.uldanov.2005@gmail.com>
    Date:   Wed Sep 27 11:56:38 2023 +0300
    add new file - rectangle.py

