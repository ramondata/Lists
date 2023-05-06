```
    __    _      __      
   / /   (_)____/ /______
  / /   / / ___/ __/ ___/
 / /___/ (__  ) /_(__  ) 
/_____/_/____/\__/____/  
                         
```

*Some ways to create a list and how we may use/manipulate these one* 🐍
===========

list is a most common used structure in Python. We can understanding about it because is so easy make or treat data with these structure.

Usually in the world of programming languages, this structure is often used to store data with the same data type or almost with data type distinct.
The name used for these structure is array or vector.

Inside Python, there's some libraries with the same idea, like list. For example in lib numpy exist the array function. With these struct is possible use data with same data type or not. there's another lib with struct looks like list too.

So, most developers and IT professionals often prefer use the structure list, cause it`s built in and very powerfull to manipulation of any types of data.

Let's see below, how we can build a list in Python:

- [x] Using square brackets: *`mode 1`*

```
some_names_1: list = ["ramon", "carol", "chico"] 
```

- [x] Using a separeted with split function: *`mode 2`*

```
nomes_2: list = "ramon|carol|chico".split("|")
```

- [x] Casting another type to list type: *`mode 3`*

```
sobrenomes: tuple = ("barbosa", "freitas")

sobre_nomes_3: list = list(sobrenomes)
```
- [x] List comprehensions: *`mode 4`*

```
sobrenomes: tuple = ("barbosa", "freitas")

nomes_4: list = [item for item in sobrenomes if item == "barbosa"]
```

- [x] lazy function map to list: *`mode 5`*

```
nicks: tuple = ("chico dogao", "chico bonitao", "chico sapecao")

nomes_5: list = list(map(lambda x: x, nicks))
```

Manipulation Lists
============================

After make ou initialized a list in Python, we can change this. Let's see a most methods and functions for lists, below

- [x] Append:

Append is an important method to add new data in list
```
array_with_name_of_friends: list = ['Eduardo']

array_with_name_of_friends.append('Jo')
```

- [x] Insert:

The structure of lists, each position there's a index number beginner with 0

To use the method insert, we need fill the index and after, the data. See below:
```
array_with_name_of_friends = ['Eduardo', 'Jo']
array_with_name_of_friends.insert(0, 'Carol')
```

- [x] Extend:

This method is important to aggregation a list inside another list
It's looks like a union for lists
```
total_of_chair_room_1 = [9,12,33]
number_of_chair_room_2 = [4, 12, 25]
total_of_chair_all_rooms = list()

total_of_chair_all_rooms.extend(total_of_chair_room_1)
total_of_chair_all_rooms.extend(total_of_chair_room_2)
```
> total_of_chair_all_rooms: [9,12,33,4,12,25]

- [x] Pop:

This method is usually used to drop a data from the list. 
You can drop allways the last item from the list or drop a specific data filling index about that.

```
animals_names = ['duck', 'tiger', 'aligator', 'snake']
animals_names.pop()
```
> animals_names: ['duck', 'tiger', 'aligator']

```
animals_names = ['duck', 'tiger', 'aligator', 'snake']
animals_names.pop(1)
```

> animals_names: ['duck', 'aligator', 'snake']

Remember: index of lists start with 0 (zero).


- [x] Remove:

Method did use to remove a data specific, but we fill the data and not index about data.
```
pencil_color = ['yellow', 'blue', 'green']
pencil_color.remove('blue')
```
> pencil_color: ['yellow', 'green']

the remove method will drop the first ocurrency of data, if you wanna drop all items, is necessary make a logic about that, using set or apply the remove more times.

Remember: if data were int, fill data without `''`.





*`to be continued`*








