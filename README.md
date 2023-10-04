# About this project:
- This project created to convert any dict into class in python :) check [PyPI](https://pypi.org/project/python-dtoc/)


# Install:
- `pip install python-dtoc`


## Simple example:
- <b>Print the object :</b>
---
```python
from pydtoc import dtc

foo = dtc({'str': 'string', 'int': 1, 'list': [1, 2, 3, 4, {'hi': True}]})

print(foo)
```

- <b>Output :</b>
```json
{
    "str": "string",
    "int": 1,
    "list": [
        1,
        2,
        3,
        4,
        {
            "hi": true
        }
    ]
}
```

- <b>Print the value of an key :</b>
---
```python
from pydtoc import dtc

foo = dtc({'str': 'string', 'int': 1, 'list': [1, 2, 3, 4, {'hi': True}]})

print(foo.list[-1].hi)
print(foo.str)
```

- <b>Output :</b>
```
True
string
```
