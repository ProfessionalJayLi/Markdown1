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
 
# Example of Encapsulation
class Joe:
    def __init__(self, name, last):
        self.__name = name
        self.lastName = last

joe = Joe("Joe", "Mama")
# print(joe.__name) would produce error because it was encapsulated
print(joe.lastName) # works because it wasn't incapsulated

# Example of Polymorphism
class Slime:
    def __init__(self, hp, dmg)
        self.hp = 10
        self.dmg = 5

    def attack(self, enemy):
        enemy.hp -= self.dmg
        
class Goblin:
    def __init__(self, hp, dmg)
        self.hp = 25
        self.dmg = 7

    def attack(self, enemy):
        enemy.hp -= self.dmg

def attacking(attacker, enemy):
    attacker.attack(enemy)

slime = Slime()
goblin = Goblin()
attacking(slime, goblin)
print(goblin.hp) # prints out 20 instead of 25 cause the method worked
```

## Definitions
    -Encapsulation: uses __ prefix, protects data making it not accessible outside the class
    -Polymorphism: methods that different classes and objects and requires parameters
    -Override: methods which use the same method name and parameters (variables needed)
    -Inheritance
    -Methods: functions or methods within the class
    -Attributes: Values the object's fields has
    -Fields: Variables that the class or object uses
