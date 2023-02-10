# RussianCitiesExtractor

This is a clumsy but prefectly working NER tool that uses regex and DAWG to extract city names and to convert them into their normal forms
The message is: Since the number of Named Entities is limited we can easily use less complex algos to extract them

```python
from RussianCitiesExtractor.City import CityExtractor
# input
extraсtor = CityExtractor()
extraсtor.extract("В городе Тотьме на некоторых зданиях я видел узоры, характерные для зодческой культуры Нижнего Новгорода")

```


```python

# output
['тотьма', 'нижний новгород']

```
