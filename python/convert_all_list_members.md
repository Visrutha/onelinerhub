# How to convert all list members to another data type

```python
converted = list(map(str, iterable_name))
```

- converted - new list that contain converted values
- list - convert the final result to list
- str - data type you want the list member to convert to(target data type) e.g.(str, int, bool)
- iterable_name - list you want to source list

input:
```python
list_of_numbers = ["1", "2", "3"]
```
code:
```python
converted = list(map(int, list_of_numbers)) # Note that if list contain a non base10 number return exception
```
output:
```python
[1, 2, 3]
```