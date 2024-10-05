
# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`

# Общее описание решения
## Square
- Задавая одну сторону находит площадь квадрата и его периметр
## Circle
- Задавая радиус находит площадь круга и его периметр 

# Описание каждой функции с примерами вызова
## Функции для квадрата
### area(a) - Нахождение площади квадрата
- Принимает число a (одну из сторон), возвращает квадрат числа a (его площадь)
```python
def area(a):   #(a = 5)
    return a * a   #(вернет число 25)
```
### perimeter(a) - Нахождение периметра квадрата
- Принимает число a (одну из сторон), возвращает число a умнотженное на 4 (его периметр)
```python
def perimeter(a):   #(a = 5)
    return 4 * a   #(вернет число 20)
```

## Функции для круга
### area(a)
- Принимает число r (радиус круга), возвращает число π * r² (площадь круга)
```python
def area(r):   #(a = 4)
    return math.pi * r * r   #(вернет число 50,24)
```
### perimeter(r)
- Принимает число r (радиус круга), возвращает число 2 * π * r (периметр круга)
```python
def perimeter(r):   #(a = 4)
    return 2 * math.pi * r   #(вернет число 25,12)
```

# История изменения проекта
1.  **d76db2a** L-04: Add calculate.py
    Добавлен файл для выполнения расчетов
    
2.  **51c40eb** L-04: Doc updated for triangle
    Обновлена документация для triangle.py

3.  **d080c78** L-04: Triangle added
    Добавлен файл для работы с треугольником
    
4.  **d078c8d** L-03: Docs added
    Добавлены документации для предыдущих функций
    
5.  **8ba9aeb** L-03: Circle and square added
    Добавлены файлы для работы с кругом и квадратом
