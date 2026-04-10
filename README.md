# Python Shape Calculator

A Python-based shape calculator that uses Object-Oriented 
Programming and inheritance to calculate properties of 
rectangles and squares.

## Features
- Calculate area of rectangles and squares
- Calculate perimeter of rectangles and squares
- Calculate diagonal length
- Visual picture representation using asterisks
- Calculate how many times one shape fits inside another
- Square inherits from Rectangle (OOP Inheritance)

## How It Works
A Rectangle is created with a width and height. A Square 
inherits from Rectangle but keeps all sides equal. Both 
shapes can calculate their own area, perimeter, diagonal, 
and more.

## Technologies Used
- Python
- Object-Oriented Programming (OOP)
- Inheritance
- Math module

## Example
```python
rect = Rectangle(10, 5)
print(rect.get_area())
# Output: 50

print(rect.get_picture())
# Output:
# **********
# **********
# **********
# **********
# **********

sq = Square(4)
print(sq)
# Output: Square(side=4)

print(rect.get_amount_inside(sq))
# Output: 2
```

## Author
crazytuff13
