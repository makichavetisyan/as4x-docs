---
layout: page
title: "CopyDoc ֆունկցիա"
---

# CopyDoc ֆունկցիա

[Հատկություններ և մեթոդներ](../../Asdoc.md)

Ստեղծում է արդեն գոյություն ունեցող փաստաթղթի պատճեն օբյեկտը։  
Տրված ISN-ով փաստաթոսւղթը բեռնում է տվյալների պահոցից, այդ թվում ջնջված փաստաթղթի, ապա դրա հիման վրա ստեղծում պատճեն օբյեկտը։

## Շարահյուսություն

``` vb
Set oDoc = CopyDoc(nISN, [ByVal BeforeCopyParam As Variant], [ByVal Mode As Integer])
```

Բաղադրիչներն են՝
    
| Պարամետր | Նկարագրություն |
|--|--|
| oDoc | Պատճենված փաստաթղթի հղում։ |
| nISN | Պատճենման ենթակա փաստաթղթի ներքին նույնականացման համար։ |
| BeforeCopyParam | Տվյալ պարամետրի արժեքը փոխանցվում է փաստաթղթի [BeforeCopy](../../../ScriptProcs/BeforeCopy.html) իրադարձությանը։ |
| Mode | Սահմանում է փաստաթղթի պատճենման ռեժիմը։ <br/> `0` - պատճենվում են բոլոր դաշտերի արժեքները։ <br/> `1` - պատճենման ռեժիմը համապատասխանում է վիզուալ պատճենմանը, որը և կախված է փաստաթղթի նկարագրության մեջի [CopyAsRepeatable](../../../Defs/doc.md) արժեքից։ <br/> `2` - պատճենվում են միայն այն դաշտերը, որոնք պարունակում են `N` հայտանիշը։ <br/> Լռությամբ արժեքը 0: |

## Նկատառումներ

[Տես նաև](../../../constructors.html)

## Oրինակ

Օրինակի մեջ կանչվում է CopyDoc ֆունկցիան, որտեղ nDoc-ը հղվում է պատճեվված փաստաթղթի վրա նրա բոլոր հատկություններով և մեթոդներով։

``` vb
Set nDoc = CopyDoc(mDoc.ISN)
nDoc.State = mDoc.State
nDoc.Store()
```