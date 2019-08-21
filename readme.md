# sayo formatting protocol

sayo formatting protocol (sfp) is a formatting protocol designed by sayo.

to-do

- emoji
- verb and noun

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
    - [array](#array)
  - [symble](#symble)
    - [step](#step)
    - [punctuation](#punctuation)
    - [tab](#tab)

## text

### name

with ' ', use ' '

> sayo naming protocol
>
> alex zeitlin
> 
> usage: title name, local file name

without ' ', use '-'

> sayo-formatting-protocol
>
> alex-zeitlin
> 
> usage: variable name, online file name, link name, code file name.

without ' ' or '-', use '_'

> sayo_formatting_protocol
>
> alex_zeitlin
>
> not recommand: '_' is usually as subscript

name in setence

> my name is 'alex zeitlin'
> this protocol is 'sayo formatting protocol'

attention:

1. use noun, do not use verb.
2. no 's' after noun.
3. file must have extension name.

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

> '这是一段引用'
>
> 这是一个 '文字块'
> [中文输入法为什么会有全角和半角的区别?](https://www.zhihu.com/question/19605819/answer/12355856)

[Chinese Copywriting Guidelines - Sparanoid](https://sparanoid.com/note/chinese-copywriting-guidelines/)
### abbreviation

Use Text Name

### extra information

> Sentence (Extra information).

usage: adding extra information to paragraph.

## number

### date

> [year].[month].[day].[hour]:[minute]:[second] ([Time Zone])
>
> 2019.05.14.01.32.25
>
> 2019.05.14.01.32.25+08:00

usage: time, version number.

explanation: no ' ', '+08:00' is optional.

### array

array

> [first item, Second Item, Third Item, ...]
>
> [9, 7, 2]
>
> [Jobs, Gates, Page]

Array with Value

> [First Item: First Value, Second Item: Second Value, ...]
>
> [First Name: Alex, Last Name: Zeitlin]

dimensional Array

``` sfp
[9, 7, 2; 3, 5, 1; 4, 9, 3]

[9, 7, 2
 3, 5, 1
 4, 9, 3]
```

multi-dimensional Array

``` sfp
[1, 2:
 9, 7, 2
 3, 5, 1
 4, 9, 3]

[1, 3:
 9, 7, 2;
 3, 5, 1;
 4, 9, 3]

[1, 2: 9, 7, 2; 3, 5, 1; 4, 9, 3]
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

### tab

use 2 space as a tab.