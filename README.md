# cs4330FinalProject

## Team Members
Jakob Daugherty

## Comparison Languages

 Python vs. C#

### Comparison Criteria

| Criteria                                            | Python | C# |
|-----------------------------------------------------|--------|----|
| Language purpose/genesis                            | [Python](https://docs.python.org/3/license.html) was created in the early 1990's by Guido van Rossum at Stichting Mathematisch Centrum in the Netherlands. As an interpreted language, python has emphasized code readability, and reducing the number of lines of code required to express concepts. Guido van Rossum envisioned python as a successor of a language called [ABC](http://homepages.cwi.nl/~steven/abc/programmers/handbook.html). ABC is a language intended to be used in place of BASIC, Pascal or AWK. | C# was created with roots in the C family of languages as a simple, modern, object-oriented, and type-safe programming language. Further addressing support of component-oriented programming, by providing features such as, garbage-collection, exception handling, and type-safe design. These features provide a more natural approach to developing software components than C++, Java, and JavaScript. |
| Unique features of the language                     | Python, differing from most programming languages, requires no type declarations. Essentially eliminating the idea of incompatible data types. | C# ensures that programs and libraries can evolve over time and remain compatible, using versioning. Essentially eliminating the idea of "dll hell" when new library versions are released. |
| Name spaces                                         | In [Python](https://docs.python.org/3/tutorial/classes.html#python-scopes-and-namespaces), a name space is a mapping from names to objects, and eliminates confusion around similar names in different namespaces by using prefixed module names. Namespaces are used to determine the scope of names at time of execution, providing a global namespace for the current function and a module namespace for outside functions. | In [C#](https://docs.microsoft.com/en-us/dotnet/articles/csharp/language-reference/keywords/namespace), the ```namespace``` keyword is used to declare a scope that contains a set of related objects. You can use a namespace to organize code elements and to create globally unique types; like a class, interface, or another namespace. |
| Types                                               | The principal built in types are numerics, sequences, mappings, classes, instances and exceptions. Python uses ["call-by-object,"](http://www.python-course.eu/passing_arguments.php) meaning Python will initially behave like call-by-reference, but as soon as you change the value of an object, Python "switches" to call-by-value. Class definitions allow for the creation of new types. | [In C#](https://docs.microsoft.com/en-us/dotnet/articles/csharp/programming-guide/types/index), every variable and constant has a type, as does every expression that evaluates to a value. Value types are derived from System.ValueType, and any reference type is defined as a class, delegate, array, or interface. New value types can be created as enums and structs. |
| Classes                                             | [Python's](https://docs.python.org/3/tutorial/classes.html#a-first-look-at-classes) class mechanism adds classes with a minimum of syntax and semantics. Providing standard Object Oriented Programming functions like inheritance and method overriding, and dynamic creation and modification. An example of a python class can be found [Here](classPython.md) |  |
| Instance reference name in data type (class)        | self | this |
| Properties                                          |        |    |
| Interfaces / protocols                              |        |    |
| Inheritance / extension                             |        |    |
| Reflection                                          |        |    |
| Memory management                                   |        |    |
| Comparisons of references and values                |        |    |
| Null/nil references                                 | None | null |
| Errors and Exception Handling                       |        |    |
| Lambda expressions, closures, or functions as types |        |    |
| Implementation of listeners and event handlers      |        |    |
| Singleton                                           |        |    |
| Procedural programming                              |        |    |
| Functional programming                              |        |    |
| Multithreading                                      |        |    |
