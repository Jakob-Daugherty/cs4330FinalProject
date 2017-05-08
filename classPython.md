# First look at Python classes

## by: Jakob Daugherty

### Simple class definition

```python
class ClassName:
  <statement-1>
  .
  .
  .
  <statement-n>
```
### Creating new instances and constant initializing

Example class definition

```python
class Dog:

  def __init__(self, name):
    self.name = name
    self.tricks = [] # creates a new empty list for each Dog

  def add_trick(self, trick):
    self.tricks.append(trick)
```

Example main program and output

```
>>> d = Dog('Fido')
>>> e = Dog('Buddy')
>>> d.add_trick('roll over')
>>> e.add_trick('play dead')
>>> d.tricks
['roll over']
>>> e.tricks
['play dead']
```

### Destructing / de-initializing

Since class instances are dynamic at runtime, they are removed as soon as the program stops running.
