# Sayo Formatting Protocol

Sayo Formatting Protocol (SFP) is a formatting protocol designed by Sayo.

To do

- Emoji

## Table of Content

- [Sayo Formatting Protocol](#sayo-formatting-protocol)
  - [Table of Content](#table-of-content)
  - [Text](#text)
    - [Name](#name)
    - [User Name](#user-name)
    - [Keyboard Key](#keyboard-key)
    - [Input Instruction](#input-instruction)
    - [Quotation + Text Block](#quotation--text-block)
    - [Abbreviation](#abbreviation)
    - [Extra Information](#extra-information)
  - [Number](#number)
    - [Date](#date)
    - [Array](#array)
  - [Symble](#symble)
    - [Step](#step)
    - [Punctuation](#punctuation)

## Text

### Name

With ' '

> Unique Naming Protocol
>
> Alex Zeitlin

Usage: Title name, Local file name

Without ' '

> unique-naming-protocol
>
> alex-zeitlin

Usage: Variable name, Online file name, Link name.

Without ' ' or '-'

> unique_naming_protocol
>
> alex_zeitlin

Attention:

1. Use noun, do not use verb.
2. No 's' after noun.
3. File must have extension name.

### User Name

With '-'

> user-name

Without '-'

> user_name

Name Is Duplicated

> user-name-[Identification Number: 99]

### Keyboard Key

Single Key

> [space]

Multiple Key

> [command | ctrl] + [shift] + [c]

Explaination: '+' for press at the same time.

### Input Instruction

Instruction

> [Input Instruction]
>
> [Blog URL]

Instruction with Example

> [Input Instruction: Example]
>
> [First Name: Alex]

Optional Instruction

> ([Optional Instruction: Answer])
>
> 2019.05.14, 01:32:25 ([Time Zone: +08:00])

### Quotation + Text Block

Latin Character

> 'This is a quote.'
>
> This is a 'Text Block'

CJK Character

CJK: Chinese Japanese Korean

> 「这是一段引用」
>
> 这是一个「文字块」

### Abbreviation

Use Text Name

### Extra Information

> Sentence (Extra information).

Usage: Adding extra information to paragraph.

## Number

### Date

> [Year].[Month].[Day], [Hour]:[Minute]:[Second] ([Time Zone])
>
> 2019.05.14, 01:32:25
>
> 2019.05.14, 01:32:25 +08:00

Usage: Time, Version number.

Explanation: ' ' must be added, '+08:00' is optional.

### Array

Array

> [First Item, Second Item, Third Item, ...]
>
> [9, 7, 2]
>
> [Jobs, Gates, Page]

Array with Value

> [First Item: First Value, Second Item: Second Value, ...]
>
> [First Name: Alex, Last Name: Zeitlin]

2 Dimensional Array

``` sfp
[9, 7, 2; 3, 5, 1; 4, 9, 3]

[9, 7, 2;
 3, 5, 1;
 4, 9, 3]
```

Multidimensional Array

``` sfp
[1, 2:
 9, 7, 2;
 3, 5, 1;
 4, 9, 3]

[1, 3:
 9, 7, 2;
 3, 5, 1;
 4, 9, 3]
```

## Symble

### Step

`First -> Second -> Third`

'<-' in RTL(Right To Left)

> اول -> ثان -> ثالث

### Punctuation

' + ': And

> '[space] + [a]'

' | ': Or

> He | She

' . ': Belonging

> [Big].[Small]
>
> Father.Son, 2019.05.14, system.right

' : ': Explanation + Example

> Explanation: This is an explanation
>
> SFP: Sayo Formatting Protocol
>
> Example: This is an example
>
> First Name: Alex

' ... ': Et cetera

> [First Item, Second Item, Third Item, ...]