## List

List

A data structure that is a mutable(changeable) ordered sequence of elements. Defined by having values between square brackets, [].

*Ex.*
```python
student1 = "John"

student2 = ["John", "Chloe", "Ian", "Ashley"]
print(students)
>> ["John", "Chloe", "Ian", "Ashley"]

box = ["Anything", 123, True, 4.38, -13]
>> ["Anything", 123, True, 4.38, -13] 

box = ["Anything", 123, True, 4.38, -13]
box.append("toy")
box.insert(1, False)
print(box)
 
```
### Indexing List
Each item in a list corresponds to an index number, which uses an interger; starting with 0.

`len(grocerylist)` --> 6
len() gives us the length of our lists

### List Functions

adding elements/items
1. LIST.append(ELEMENT) # Adds a item to the end of the list
`grocerylist.append("milk")`
2. LIST.insert(INDEX, ELEMENT) #  Add a item in the index location
`grocerylist.index(3, "apples")`
3. LIST.remove(ELEMENT) # searches the list and removes it
`grocerylist.remove("banana")`
4. LIST.pop(INDEX) # remove the item at the specified index
`grocerylist.pop(4)`

To print an item we use LIST[INDEX]

## Tuple

Another type of list that stores data/values but in parenthesis (). 
Unlike lists, they __cannot__ be changed(they are unmutable).

`colors = ("Blue", "Red", "Yellow")`
`print(colors[2])` --> Yellow

## Dictionary
Also a another type of list that stores a data inside curly braces{ }
Similar to a list it is mutable however the index is a key, which is linked to a data/value.

```python
students = {
  "Visham" : "981023",
  "Jake" : "123810",
  "Ben" : "180921"
}
print(students["Visham"])
```
> 981023