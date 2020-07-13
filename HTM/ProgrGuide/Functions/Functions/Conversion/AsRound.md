---
layout: page
title: "AsRound ֆունկցիա"
---

# AsRound ֆունկցիա

Թիվը կլորացնում է նշված ճշտությամբ և վերադարձնում ստացված արժեքը։

``` vb
Public Function AsRound(ByVal Number As Currency, _
                        ByVal Precision As Long) As Currency
```

Բաղադրիչներն են՝

| Պարամետր | Նկարագրություն |
|--|--|
| Number | Մուտքային թիվ։ |
| Precision | Կլորացման աստիճան։ |

## Կարգաբերումներ

`Precision`-ը կարող է ընդունել հետևյալ արժեքները՝

| Արժեքներ | Նկարագրություն |
|--|--|
| .... |  |
| 2 | Ստորակետից հետո կլորացումը կատարվում է մինչև հարյուրերրորդական թվերով։ Округление проводится до сотых долей после запятой |
| 1 | Ստորակետներից հետո կլորացվումը կատարվում է մինչև տասական թվերով ։ Округление проводится до десятых долей после запятой |
| 0 | Կլորացումը կատարվում է միավորներով։ Округление проводится до единиц |
| -1 | Կլորացումը կատարվում է մինչև տասական թվիը։ Округление проводится до десятков числа |
| -2 | Կլորացվում է մինչև հարյուրերրորդական թիվը։ Округление проводится до сотых числа |
| -3 | Կլորացվում է մինչև հազարերրորդական թիվը։ Округление проводится до тысячных числа |
| -4 | Կլորացվում է մինչև հարյուր հազարերրորդական թիվը։ Округление проводится до сотни тысячных |
| ... | .... |

## Նկատառումներ

[Տես նաև](AsRoundDiv.html)