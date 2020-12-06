# hJson

A package for handling json files

`pip install py-hJson`

Example : 
```python
import hJson

data = hJson.load('example.json')
print(data)
print()

data['test'] = 100
data = hJson.save('example.json', data)
print(data)
print()

check = hJson.check('example.json')
print(check)
```

Output : 
```
{
    'test' : 0
}

{
    'test' : 100
}

True
```
