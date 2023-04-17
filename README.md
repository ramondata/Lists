![lists](https://github.com/ramondata/Tipos_de_dados/blob/master/david-clode-vb-3qEe3rg8-unsplash.jpg)

*Some ways to Create a list and how we may use/manipulate these lists* 🐍
===========

list is a most common used structure in Python. We can understanding about it because is so easy make or treat data with these structure.

Usually in the world of programming languages, this structure is often used to store data with the same data type or almost with data type distinct.
The name used for these structure is array or vector.

Inside Python, there's some libraries with the same idea, like list. For example in lib numpy exist the array function. With these struct is possible use data with same data type or not. there's another lib with struct looks like list too.

So, most developers and IT professionals often prefer use the structure list, cause it`s built in and very powerfull to manipulation of any types of data.

Let's see below, how we can build a list in Python:

- [x] Using square brackets: mode 1

```
some_names_1: list = ["ramon", "carol", "chico"] 
```


<sub>
nomes_2: list = "ramon|carol|chico".split("|") #tipo 2
sobrenomes = ("barbosa", "freitas")
sobre_nomes_3: list = list(sobrenomes) #tipo 3
nomes_4: list = [item for item in sobrenomes if item == "barbosa"] #list comprehensions #tipo 4
nomes_5: list = list(map(lambda x: x, ("chico dogao", "chico bonitao", "chico sapecao"))) #tipo 5
</sub>
