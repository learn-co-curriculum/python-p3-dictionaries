# Dictionaries

## Learning Goals

- Utilize Python's `dict` data type to accomplish several common programming tasks.
- Execute and test Python code using the Python shell.

## Key Vocab

- **Sequence**: a data structure in which data is stored and accessed in a
specific order.
- **Mapping**: a data structure in which data is stored in random order and
accessed using immutable keys.
- **Mutable**: an object that can be changed.
- **Immutable**: an object that cannot be changed. (_Many immutable objects
appear mutable because programmers reuse their names for new objects_.)
- **Arbitrary**: describes data whose value is unimportant to the data type
or structure in which it is contained.

## Introduction

Mappings are the next data structure we're going to look into. A mapping object
maps an immutable value to an arbitrary value. Where there are many types of
sequences in Python, there is only one type of mapping: the `dict`, or
dictionary.

In a Python dictionary, an immutable _key_ is mapped to an arbitrary _value_.
The result is a data type nearly identical to JSON:

```py
my_dict = {
    "key 1": "value 1",
    2.0: "value 2",
}
```

Keys can be composed of any immutable data type. The immutable types that we
have discussed so far are:

- `int`
- `float`
- `str`
- `bool`
- `tuple`
- `range`

While there are no explicit guidelines on which types of values to use for
`dict` keys, it is best to use descriptive strings unless the task you are
trying to accomplish requires you to use another data type.

## Resources

- [Python Mapping Types](https://docs.python.org/3/library/stdtypes.html#typesmapping)
- [Python Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#dictionaries)
