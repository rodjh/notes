# Metaclassess

## Basic Principles

* Everything is an object
* Everything has a type
* No real difference between 'class' and 'type' (see note)
* Classes are objects
* Their type is `type`

**Note:** Typically the term type is used for the built-in types and the term class for user-defined classes. Since Python 2.2 there has been no real difference and 'class' and 'type' are synonyms.

```python
Python 2.5.1 (r251:54869, Apr 18 2007, 22:08:04)
>>> class Something(object):
...     pass
...
>>> Something
<class '__main__.Something'>
>>> type(Something)
<type 'type'>
```




* In exactly the same way as any other object in Python.


```
>>> help(type)
Help on class type in module __builtin__:

class type(object)
 |  type(object) -> the object's type
 |  type(name, bases, dict) -> a new type




