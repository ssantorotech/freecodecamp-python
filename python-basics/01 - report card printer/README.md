# Variables and Data Types

## Description

This exercise introduces Python variables and basic data types. It demonstrates how to assign values to variables, use `type()` to identify their data types, and use `isinstance()` to verify a variable's type.

## Code

```python
name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))

age = 20
print(age, type(age))

score = 80.5
print(isinstance(score, float))
print(score, type(score))
```

## Expected Output

```text
Alice <class 'str'>
True <class 'bool'>
20 <class 'int'>
True
80.5 <class 'float'>
```

## Concepts

`str`: Represents text.

`bool`: Represents Boolean values, `True` or `False`.

`int`: Represents integers.

`float`: Represents decimal numbers.

`type()`: Returns the type of a variable.

`isinstance()`: Checks whether a value belongs to a specified type.

## Conclusion

This exercise covers Python variables, basic data types, and type checking using `type()` and `isinstance()`.
