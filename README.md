# Google sheets wow assignment script

## Attributes
|attribute name|attribute type|
|--------------|--------------|
|class         |String        |
|spec          |String        |
|role          |String        |
|name          |String        |

## Attribute values


## Types
|Type          | syntax |
|--------------|--------|
|String literal|`""`    |


## conditions

Conditional statements is built with comparison operators and logical operators

### Example
```c
class == "DeathKnight" && spec == "Blood"
```


### Comparison operators
where `A` is one of the [attributes](#attributes)

|Comparison type |operation| syntax                |
|----------------|---------|-----------------------|
|Equals          |`==`     |`A == "[somestring]"`  |
|Not Equals      |`!=`     |`A != "[somestring]"`  |

### Logical operators
|Logical type     |operation | syntax  | reduces to |
|-----------------|---------|--------|------------|
|Conjuction(and)  |`&&`     |`A && B`|            |
|Disjunction(or)  |&#124;&#124;     |A &#124;&#124; B|            |
|Joint Denial(nor)|~&#124;     |A ~&#124; B| !(A &#124;&#124; B)|
|Negation(not)    |`!`      |`!A`    |            |


## Definitions

Used to define short hand conditions.
Definiton name should always be upper case.

`#define [DEFINITION] [CONDITION]`

Usage
`[DEFINITION]`

### EXAMPLE

```c
#define TANK spec == "protection" || spec == "blood" || spec == "feralTank"
```

# Interpret

## Tokenization

## parsing tree

## Interpretation
