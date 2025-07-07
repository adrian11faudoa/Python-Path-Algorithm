Subject: 


Immutable data types, such as integers, strings, tuples, and Booleans.
Mutable data types, such as lists, and dictionaries.
A dictionary is identified by a pair of curly braces, {}.

Dictionaries store data in the form of key-value pairs. A key is separated from the correspondent value by a colon. And each key-value pair is separated from the following pair by a comma:

Example Code:
```
    my_dict = {
    'name': 'Michael',
    'occupation': 'Lumberjack'
    }
```

Example Code:
```
    copper = {
        'species': 'guinea pig',
        'age': 2
    }
    copper['food'] = 'hay'
    copper['species'] = 'Cavia porcellus'
```


To iterate over the keys of a dictionary, you can simply put the dictionary into a for loop. The code below would print each key in the dictionary dict:

Example Code:
```
    for i in dict:
        print(i)
```

If you want to iterate over the values of the dictionary keys, one way is to use the .values() method.

Example Code:
```
    for i in copper.values():
        print(i)
```

if you want to be able to go through the key-value pairs, you can use the .items() method.

Example Code:
```
    for i in copper.items():
        print(i)
```

To iterate over the elements in those tuples you can add a second loop variable:

Example Code:
```
    for i, j in dict.items():
        print(i, j)
```

You can remove a key-value pair from a dictionary by using the del keyword:

Example Code:
```
    my_dict = {
        'name': 'Michael',
        'occupation': 'Lumberjack'
    }

    del my_dict['occupation']
```


Graphs are data structures representing relations between pairs of elements. These elements, called nodes, can be real-life objects, entities, points in space or others. The connections between the nodes are called the edges.

A graph is called a weighted graph when its edges are associated with weights, representing a distance, time or other quantitative value.


With a dictionary comprehension, you can create a dictionary starting from an existing dictionary:

Example Code:
```
    {key: val for key in dict}
```

In the example above, val is the value that key will have in the new dictionary, and dict is the existing dictionary.

Dictionary comprehensions support conditional if/else syntax too:

Example Code:
```
    {key: val_1 if condition else val_2 for key in dict}
```

In the example above, dict is the existing dictionary. When condition evaluates to True, key will have the value val_1 , otherwise val_2.


Make a copy of a list. For that you can use the slice syntax:

Example Code:
```
    my_list[:]
```
Where my_list is the list you want to copy.


Python provides a concise way to write if/else conditionals by using the ternary syntax:

Example Code:
```
    val_1 if condition else val_2
```
The expression above evaluates to val_1 if condition is true, otherwise to val_2


