# Lab2
### Short Circuiting

If `and` and `or` do not *short-circuit*, they just return the last value.

 `and` and `or` don't always return booleans when using values other than `True` and `False`.

```python
>>> True and 13
13
>>> not 10
False
```



# Mutability



```python
>>> a = [10] 
>>> b = a 
>>> a == b 
True 
>>> a.append(20) 
>>> a [10, 20] 
>>> b [10, 20] 
>>> a == b 
True
```

