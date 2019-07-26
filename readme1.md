# sayo formatting protocol

sayo formatting protocol (sfp) is a formatting protocol designed by sayo.

to-do

- emoji

## table of content

- [sayo formatting protocol](#sayo-formatting-protocol)
  - [table of content](#table-of-content)
  - [text](#text)
    - [name](#name)
    - [user name](#user-name)
    - [keyboard key](#keyboard-key)
    - [input instruction](#input-instruction)
    - [quotation + text block](#quotation--text-block)
    - [abbreviation](#abbreviation)
    - [extra information](#extra-information)
  - [number](#number)
    - [date](#date)
    - [Array](#array)
  - [symble](#symble)
    - [step](#step)
    - [punctuation](#punctuation)

## text

### name

with ' '

> sayo naming protocol
>
> alex zeitlin

usage: title name, local file name

without ' '

> unique-naming-protocol
>
> alex-zeitlin

usage: variable name, online file name, link name, code file name.

without ' ' or '-'

> unique_naming_protocol
>
> alex_zeitlin

attention:

1. Use noun, do not use verb.
2. No 's' after noun.
3. File must have extension name.

### user name

with '-'

> user-name

without '-'

> user_name

name is duplicated

> user-name-[Identification Number: 99]

### keyboard key

single key

> [space]

multiple key

> [command | ctrl] + [shift] + [C]

explaination: '+' for press at the same time.

### input instruction

instruction

> [Input Instruction]
>
> [Blog URL]

instruction with example

> [Input Instruction: Example]
>
> [First Name: Alex]

optional instruction

> ([Optional Instruction: Answer])
>
> 2019.05.14, 01:32:25 ([Time Zone: +08:00])

### quotation + text block

latin character

> 'This is a quote.'
>
> This is a 'Text Block'

cjk character

cjk: chinese japanese korean

> 「这是一段引用」
>
> 这是一个「文字块」

### abbreviation

Use Text Name

### extra information

> Sentence (Extra information).

usage: adding extra information to paragraph.

## number

### date

> [year].[month].[day], [hour]:[minute]:[second] ([Time Zone])
>
> 2019.05.14.01.32.25
>
> 2019.05.14.01.32.25+08:00

Usage: Time, Version number.

Explanation: no ' ', '+08:00' is optional.

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

## symble

### step

`first -> second -> third`

'<-' in rtl (right to left)

> اول -> ثان -> ثالث

### punctuation

' + ': and

> '[space] + [a]'

' | ': or

> He | She

' . ': belonging

> [big].[small]
>
> Father.Son, 2019.05.14, system.right

' : ': explanation + example

> Explanation: This is an explanation
>
> SFP: Sayo Formatting Protocol
>
> Example: This is an example
>
> First Name: Alex

' ... ': Et cetera

> [first item, second item, third item, ...]