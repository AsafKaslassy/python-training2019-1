# Object Oriented Programming in Python
## Date: Thursday, January 23th 2020

### Topics
#### Introduction
    * Magic functions
    * type of `class`.
```python
# Example Class
class TestClass:
    pass
print(type(TestClass))  # Print: class 'type'

# Example to print a number
print(type(1))  # Print: class 'int'
```

* Inhetitance
    * super()
    
* Polymorphysm

### Lesson assignments
* [Rectangle](/seminars/lessons/23.1.2020/rectangle/rectangle.py)
* [Parallel lines](/seminars/lessons/23.1.2020/parallel_lines)
* [Student - person](/seminars/object_oriented)

### Notes
* first parameter is `self` inside the `def` when function is in the class.
* `__init__` variables must to be dynamic
* class name `Person(Inherited)`
* `super()` - usage of the inherited class, example:

`super().__init__(var1, var2)`
  * the `super()` is imported to use because it's a must to split and
stay organised which is inherited or not.
* 
