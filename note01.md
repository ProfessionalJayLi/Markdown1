# Object Oriented Programming Notes 1

I think OOP is awesome!

```python
# Example class

class Person:
    def __init__(self, name):
        self.name = name
    
    def __str__(self):
        return f"Person Object called: {self.name}"
        
    def __repr__(self):
        return self.__str__()

```

## Definitions
    -Encapsulation: uses __ prefix, protects data making it not accessible outside the class
     ```python
    class Joe:
        def __init__(self, name, last):
            self.__name = name
            self.lastName = last

    joe = Joe("Joe", "Mama")
    # print(joe.__name) would produce error because it was encapsulated
    print(joe.lastName) # works because it wasn't incapsulated
     
     ```
    -Polymorphism: 
    -Override: 
    -Inheritance
    -Methods: functions or methods within the class
    -Attributes: Values the object's fields has
    -Fields: Variables that the class or object uses
