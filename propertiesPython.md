# Python Properties

```python
class C:
  def __init__(self):
    self.__x = None

  def getx(self):
    return self.__x

  def setx(self, value):
    self.__x = value

  def delx(self):
    del self.__x

  x = property(getx, setx, delx, "I'm the 'x' property.")

```

If _c_ is an instance of C, ```c.x``` will invoke the getter, ```c.x = value``` will invoke the setter and ```del c.x``` the deleter. 
