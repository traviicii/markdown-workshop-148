# Markdown Workshop Lecture

## Basic Markdown syntax {#top}

### 1. Headers

There are 6 sizes of header denoted by 1-6 consecutive # symbols

**Example**
> # header size 1
> ## header size 2
> ### header size 3
> #### header size 4
> ##### header size 5
> ###### header size 6

**Syntax**
```md
# header size 1
## header size 2
### header size 3
#### header size 4
##### header size 5
###### header size 6
```

### 2. Emphasis

We can make things **bold**
```md
**bold**
```


We can make things *italic*
```md
*italic*
```

We can make things ***bold and italic***
```md
***bold and italic***
```

We can ~~strike through text~~
```md
~~strike through text~~
```

We can ~~***also do this!***~~
```md
~~***also do this!***~~
```


### 3. Lists

#### Ordered

1. the first thing
    - this is important
    - another important thing
        - important thing about this thing
            - another thing?!
1. the second thing
1. third thing

#### Unordered

- one thing
- another things
- last thing

### 4. Links and images

#### Inserting a link

[Poke API](https://pokeapi.co/)

[Back to the top!](#top)

#### Inserting an Image

![An image of Ditto the pokemon](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/132.svg)

![](132.svg)

## Advanced Features

### Tables

**Syntax**
```md
| Parameter | Type | Description |
|---|----|---|
| first name | string | Required |
| email | string | Required |
```

**Result**
| Parameter | Type | Description |
|---|----|---|
| `first name` | `string` | Required |
| `email` | `string` | Required |

### Code `Block`!

```
simple code block
pip install this
```

```python
def solution():
    this = "that"
    for i in range(0, 20, 2):
        print(i)
    return this
```

```bash
pip install flask
```

### Block Quotes

> A block quote could be a side note, further ==info about a certain step==, or perhaps a definition for something

### Definitions

What is an ORM?
: An ORM is an Object Relational Mapper that helps us to relate a coding language like Python inSQL queries

**What is an ORM?**
> An ORM is an Object Relational Mapper that helps us to relate a coding language like Python inSQL queries