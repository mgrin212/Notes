# Pyret Intro

### Data Types

- numbers: 0,1,2,-5
- strings "abc", "cs200"
- Booleans: true, false
- Lists

```pyret
2 / 3
2 + (4 * 5)
"hi"
not(1 == 1)
```

### Defined Data Types

```pyret
data Animal:
  | boa(name :: String, length :: Number, eats :: String)
  | dillo(length :: Number, isDead :: Boolean)
end

fun canShelter(ani :: Animal):
  cases(Animal) ani:
    | boa(nm, len, eats) => false
    | dillo(len, isDead) => (len > 50) and isDead
  end
end
```

```pyret
>>> fred-boa = boa("Fred", 20, "lettuce")
>>> fred-boa.name
"Fred"
```

### Lists
```pyret
nums = [list: 1,2,3,4,5]
```

Things to do with lists:

- sort
- pull out items
- loop through lists
- call a function on items in a list
- filter through a list
