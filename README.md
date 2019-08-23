# Basic Python Datastructures
![python logo](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)


This is a basic guide covering some basic datastructures found natively in Python.

## Overview
Here are the items that will be briefly covered in this exploration of basic Python datastructures.

1. Lists
1. Dictionaries
1. Tuples
1. Sets

## 1. Lists
Lists in python behave much the same as arrays or lists found in other languages. 
Here are a couple of methods available for use.
 - .append(x)
 - .extend(x where x is an iterable)
 - .insert(i, x)
 - .remove(x)
 - .pop([i])
 - .count(x)
 
 Documentation for lists can be found [here](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists).
 
 Below is some example code for lists.
 ```
 my_items = ['item1', 'item2', 'item3', 'item1']
 my_items.count('item1')
 # 2
 my_other_items = ['item4']
 my_items.extend(my_other_items)
 ```
 
## 2. Dictionaries
Dictionaries also behave much the same as in other languages.
Here are a couple of methods available for use.
  - .get(x)
  - .values()
  - .items()
  - .pop(x)
  - .popitem()
  - .clear()

Documentation for dictionaries can be found [here](https://docs.python.org/3/tutorial/datastructures.html#dictionaries).

Below is some example code for dictionaries.
```
my_dict = {'joey':10, 'connor':3}
my_dict['kevin'] = 6
my_dict.pop('kevin')
print(my_dict.values())
```

## 3. Tuples
Tuples work as immutable lists in python and once created cannot be modified. Because of this they can be easily hashed and used as keys in dictionaries.

Here are a couple of methods available for use.
 - .count(x)
 - .index(x)

Documentation for tuples can be found [here](https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences).

Below is some example code for tuples.
```
t = 1, 2, 3, 4, 5, 6, 7
u = ()
r = (10, 11, 12)
s = t, r 
# nested tuples are possible
if 4 in t1:
  print('4 is in t1')
 
print(t.index(5)) 
```
## 4. Sets
Sets are useful for the same reason in Python as every other langauge. Useful for membership testing along with the removal of duplicate elements.

Here are a couple of methods available for use.
 - .add(x)
 - .remove(x) # will raise exception if x not present
 - .discard(x) # will not raise exception if x is not present
 - .clear()
 - .difference(x)
 - .intersection(x)
 - .union(x)

Documentation for sets can be found [here](https://docs.python.org/3/tutorial/datastructures.html#sets).

Below is some example code for sets.
```
s1 = set() # for empty sets
s2 = {1, 2, 3, 3, 3, 3, 3, 4}
s2
# {1, 2, 3, 4}
```

![stack overflow logo](https://logodix.com/logo/379477.png)
Stack overflow is always a valuable resource when learning to program in a new language and would highly recommend searching for any problems you encounter [there](https://stackoverflow.com/questions/tagged/python).
