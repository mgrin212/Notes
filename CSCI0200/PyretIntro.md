# Pyret Intro

### Data Types

- numbers: 0,1,2,-5
- strings "abc", "cs200"
- Booleans: true, false

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
