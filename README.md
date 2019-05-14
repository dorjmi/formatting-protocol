# Sayo Formatting Protocol (SFP)

Formatting Protocol designed by Sayo.

## Text Name

**With [space]**

```
Unique Naming Protocol
Alex Zeitlin
```

Usage: Title name, Local file name

Attention: No 's' after noun.

**Without [space]**

```
unique-naming-protocol
alex-zeitlin
```

Usage: Variable name, Online file name, Link name.

**Without `-`**

```
unique_naming_protocol
alex_zeitlin
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

`+` for press at the same time.

## Input Instruction

**Instruction**

```
[Input Instruction]
[Input Instruction: Default Answer]

[Blog URL]
[First Name: Alex]

```

**Optional Instruction**

```
2019.05.14, 01:32:25 [(Time Zone: +08:00)]
```

## Data with Value

```
[First Name: Alex, Last Name: Zeitlin]
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