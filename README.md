# Sayo Formatting Protocol (SFP)

Formatting Protocol designed by Sayo.

## Text Name

With [space]

> Unique Naming Protocol
>
> Alex Zeitlin

Usage: Title name, Local file name

Without [space]

> unique-naming-protocol
>
> alex-zeitlin

Usage: Variable name, Online file name, Link name.

Without ' - '

> unique_naming_protocol
>
> alex_zeitlin

Attention: 
1. Use 'Noun', do not use 'Verb'
2. No ' s ' after noun.

## Date

> [Year].[Month].[Day], [Hour]:[Minute]:[Second] ([Time Zone])
>
> 2019.05.14, 01:32:25
>
> 2019.05.14, 01:32:25 +08:00


Usage: Time, Version number.

Explanation: [space] must be added, '+08:00' is optional.

## Keyboard Key

Single Key

> [space]

Multiple Key

> [command | ctrl] + [shift] + [c]

Explaination: ' + ' for press at the same time.

## Input Instruction

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

## Array

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

``` SFP
[9, 7, 2; 3, 5, 1; 4, 9, 3]

[9, 7, 2;
 3, 5, 1;
 4, 9, 3]
```

Multidimensional Array

``` SFP
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

> Sentence (Extra information).

Usage: Adding extra information to paragraph.

## Quotation + Text Block

Latin Character

> 'This is a quote.'
>
> This is a 'Text Block'

Chinese Japanese Korean (CJK) Character

> 「这是一段引用」
>
> 这是一个「文字块」

Single Character

> ' [Single Character] '
>
> ' S ', ' ' '

## Step

`First -> Second -> Third`

'<-' in RTL(Right To Left)


> اول -> ثان -> ثالث


## Punctuation

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

## User Name

With ' - '

> user-name

Without ' - '

> user_name

Name Is Duplicated

> user-name-[Identification Number: 99]

## Abbreviation

Use Text Name