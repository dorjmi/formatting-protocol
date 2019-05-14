# Sayo Formatting Protocol

Formatting Protocol designed by Sayo.

## Text Name

**With [space]**

```
Unique Naming Protocol
Sayo Melu
```

Usage: Title name, Local file name

Attention: No 's' after noun.

**Without [space]**

```
unique-naming-protocol
sayo-melu
```

Usage: Variable name, Online file name, Link name.

**Without `-`**

```
unique_naming_protocol
sayo_melu
```


## Date

```
'2019.05.14, 01:32:25'
'2019.05.14, 01:32:25 +08:00'
```

Usage: Time, Version number.
[space] must be added, +08:00 is optional.

## Keyboard Key

```
[space]
[command | ctrl] + [c]
```

'+' for press at the same time.

## Input Instruction

**Instruction**

```
[Input Instruction: Default Answer]
[First Name: Alex]
```

**Optional**

```
2019.05.14, 01:32:25 [(Time Zone: +08:00)]
```

## Data with Value

```
[First Name: Alex, Second Name: Underwood]
```

Array

```
[9, 7, 2]
[Jobs, Gates, Page]
```

2 Dimensional Array

```
[9, 7, 2; 3, 5, 1; 4, 9, 3]

[9, 7, 2;
 3, 5, 1;
 4, 9, 3]
```

Multidimensional Array

```
[1:
9, 7, 2;
3, 5, 1;
4, 9, 3]

[1, 2:
9, 7, 2;
3, 5, 1;
4, 9, 3]
    
[1, 3:
9, 7, 2;
3, 5, 1;
4, 9, 3]
```

## Extra Information

```
Sentence (Extra information).
```

Usage: Adding extra information to paragraph.

## Quote + Text Block

```
'This is a quote.'
This is a 'Text Block'
```

## Step

`First -> Second -> Third`

'<-' in RTL(Right To Left)

```
اول -> ثان -> ثالث
```

## Punctuation

```
'+' And: '[space] + [a]'
'|' Or: 'He | She'
'.' Belonging: sfp.add-item
':' Example: `Example: Example is an example`
```

## User Name

**With '-'**
`user-name`

**Without '-'**

`user_name`

**Name Is Duplicated**

`user-name-[Identification Number: 99]`