Let's create a list of animals and see how we can modify it.

```py-cell
animals = ["rabbit", "hamster"]
print(animals)
```

We can add a new animal to the end of the list using `append()`.

```py-cell
animals.append("rat")
print(animals)
```

To add an animal at the beginning, use `insert()` with index 0.

```py-cell
animals.insert(0, "chinchilla")
print(animals)
```

We can combine two lists using the `+` operator. This creates a new list and leaves the originals unchanged.

```py-cell
shopping_list = ["apples", "bananas", "bread"]
combined = animals + shopping_list
print(combined)
print(animals)  # Original list unchanged
print(shopping_list)   # Original list unchanged
```

Trying to access an index that doesn't exist will raise an `IndexError`.

```py-cell
print(animals[99])
```

Trying to assign a value to an index that doesn't exist will also raise an `IndexError`.

```py-cell
animals[99] = "alligator"
```
