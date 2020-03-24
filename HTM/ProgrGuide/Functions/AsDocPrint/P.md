---
layout: page
title: "AsDocPrint/P"
---

# P մեթոդ

[См. также](../AsDocPrint.md) [Օրինակ](../../Examples/E_AsDocPrint.html) [Применяется к](../AsDocPrint.md)

Տեղեկանքի մեջ ավելացնում է նոր տող։ Տողը կարող է լինել ձևանմուշ, որի մեջ տեղադրվելու են պարամետրերի արժեքները։ 


## Շարահյուսություն

``` vb
object.P strPrint, [StrOrLngISN]
```

Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object | Փաստաթղթից տեղեկանք տպելու օբյեկտի հղում։ |
| strPrint | Տպելու ձևի տող։ |
| StrOrLngISN | Ներքին նույնականացման համար։ Տրված լինելու դեպքում հասանելի են դառնում այդ փաստաթղթի գործողությունները։ |


## Նկատառումներ

* Տողի ձևանմուշի մեջ տեղադրման կետերը գրվում են հետևյալ ձևով՝  `^` + *պարամետրի կոդ* կամ `^` + *փաստաթղթի դաշտերի ներքին անուն*։

``` vb
Sub Print()
    DocP.S 14, Param("BANKNAME")
    DocP.P " Բանկի անվ. ^14       "
    DocP.P " Կր. հաշիվ  ^ACCCR       Գումար ^SUMMA "
End Sub
```

* Տողի ձևանմուշի մեջ կարելի է կիրառել [ձևաչափի](../AsRepViewer/UseFormatting.md) տրոհները։

``` vb
Sub Print()
    DocP.P " <b>Բանկի անվ. ^14       </b>"
End Sub
```