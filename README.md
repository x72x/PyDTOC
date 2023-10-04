<p align="center">
    <b>
        Dictionary to class
    </b>
</p>

# Install:
---
- `pip install pydtoc`


# Simple example:
---
## Code for print:
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

## Print key of value:
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
