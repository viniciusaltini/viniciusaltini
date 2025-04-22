## Welcome
<br>

```python
class Altini:

    def __init__(self):
        self.username = 'Altini'
        self.country = 'Brazil'
        self.age = '17'
        self.name = 'Vinícius Altini'
        self.position = 'Learning Java'
        self.links = 'https://beacons.ai/viniciusaltini'

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = Altini()
    print(me)


```
