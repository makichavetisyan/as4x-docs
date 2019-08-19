---
layout: page
title: "AsMsgBox"
---


# AsMsgBox ֆունկցիա

[См. также](../../../functions.html) [Օրինակ](#Օրինակ)

Էկրանի վրա բացում է հաղորդագրության պատուհան՝ սպասելով, որ օգտագործողը ընտրի ինչ-որ կոճակ, և վերադարձնում է սեղմված կոճակի կոդը։


## Շարահյուսություն

``` vb
AsMsgBox (Prompt, [Buttons], [Title], [SecondsToShow], [EnglishPrompt], [EnglishTitle])
```

Բաղադրիչներն են՝
    
| Պարամետր | Նկարագրություն |
|--|--|
| Prompt | Տողային արտահայտություն, որը սահմանում է ցուցադրվող հաղորդագրության տեքստը։ Համակարգը ավտոմատ բաժանում և փոխադրում է հաղորդագրության տեքստը նոր տող։ Բայց եթե ցանկանում եք տեքստային հաղորդագրությունում ավելացնել տողը փոխադրող սիմվոլներ, ապա դա կարելի է անել CHR(13) սիմվոլների միջոցով։ |
| Buttons | Ոչ պարտադիր, VbMsgBoxStyle տիպի, որը սահմանում է թե որ կոճակները պետք է լինեն պատուհանի վրա, դրանցից որի վրա պետք է լինի ֆոկուսը պատուհանի ակտիվացման ժամանակ և վերին ձախ անկյունում պատկերակը։ VbMsgBoxStyle-ի արժեքները բիթային չհատվող են և նախատեսված են միաժամանակ մի քանիսը տալու համար (տե՛ս օրինակը ստորև)։ |
| Title | Ոչ պարտադիր տողային հաղորդագրություն, որը սահմանում է հաղորդագրության պատուհանի գլխագիրը։ |
| SecondsToShow | Ոչ պարտադիր ամբողջ տիպի թվային արտահայտություն, որը սահմանում է հաղորդագրության էկրանին երևալու ժամանակը վայրկյաններով։ Ժամանակի ավարտից հետո պատուհանը ավտոմատ կփակվի՝ սեղմելով ըստ լռության կոճակը։ Եթե պարամետրը բացակայում է, ապա հաղորդագրությունը շարունակաբար կլինի էկրանին, մինչև կոճակներից մեկի սեղմումը։ Տրանզակցիոն պրոցեդուրաների ժամանակ անհրաժեշտ է փոխանցել վայրկյանները, որպեսզի խուսափենք տվյալների բազան անորոշ ժամանակով զբաղեցնելուց։ |
| EnglishPrompt | Ոչ պարտադիր տողային արտահայտություն, որը սահմանում է երևացող հաղորդագրության տեքստը անգլերենով։ |
| EnglishTitle | Ոչ պարտադիր տողային հաղորդագրություն, որը սահմանում է դիալոգային պատուհանի հաղորդագրության վերնագիրը անգլերենով։ |

## Վերադրձվող արժեքի տիպ
VbMsgBoxResult

## Հաստատուններ

**VbMsgBoxStyle**, Buttons-ի արժեքներն են՝ 

| Հաստատուն | Արժեք | Նկարագրություն |
|--|--|--|
| vbOKOnly | 0 | Ցուցադրում է միայն **OK** կոճակը։ |
| vbOKCancel | 1 | Ցուցադրում է **OK** և **Cancel<** կոճակները։ |
| vbAbortRetryIgnore | 2 | Ցուցադրում է **Abort**, **Retry** և **Ignore** կոճակները։ |
| vbYesNoCancel | 3 | Ցուցադրում է **Yes**, **No** և **Cancel** կոճակները։ |
| vbYesNo | 4 | Ցուցադրում է **Yes** և **No** կոճակները։ |
| vbRetryCancel | 5 | Ցուցադրում է **Retry** և **Cancel** կոճակները։ |
| vbCritical | 16 | Ցուցադրում է **Critical Message** <img src="../../../../../IMAGES/CRITICAL.GIF" alt="Critical.gif (257 bytes)" /> պատկերակը։ |
| vbQuestion | 32 | Ցուցադրում է **Warning Query** <img src="../../../../../IMAGES/QUESTION.GIF" alt="Question.gif (263 bytes)" /> պատկերակը։ |
| vbExclamation | 48 | Ցուցադրում է **Warning Message** <img src="../../../../../IMAGES/Exclamation.gif" alt="Exclamation.gif (244 bytes)" /> պատկերակը։ |
| vbInformation | 64 | Ցուցադրում է **Information Message** <img src="../../../../../IMAGES/Information.gif" alt="Information.gif (256 bytes)" /> պատկերակը։ |
| vbDefaultButton1 | 0 | Առաջին կոճակը հանդիսանում է ըստ լռության կոճակ։ |
| vbDefaultButton2 | 256 | Երկրորդ կոճակը հանդիսանում է ըստ լռության կոճակ։ |
| vbDefaultButton3 | 512 | Երրորդ կոճակը հանդիսանում է ըստ լռության կոճակ։ |
| vbDefaultButton4 | 768 | Չորրորդ կոճակը հանդիսանում է ըստ լռության կոճակ։ |


**VbMsgBoxResult**, վերադարձվող արժեքներն են՝

| Հաստատուն | Արժեք | Սեղմված կոճակ |
|--|--|--|
| vbOK | 1 | OK |
| vbCancel | 2 | Cancel |
| vbAbort | 3 | Abort |
| vbRetry | 4 | Retry |
| vbIgnore | 5 | Ignore |
| vbYes | 6 | Yes |
| vbNo | 7 | No |


## Օրինակ
Բացվում է հաղորդագրության պատուհան «Փակե՞լ պատուհանը» տեքստով, **Yes** և **No** կոճակներով և հարցի պատկերակով: Կոճակներից ոչ մեկը 30 վայրկյան չսեղմելու դեպքում պատուհանը ավտոմատ կփակվի ոչ կոճակի սեղմումով։ 

``` vb
Dim res As VbMsgBoxResult
res = AsMsgBox("Փակե՞լ պատուհանը", vbYesNo + vbDefaultButton2 + vbQuestion,, 30)

If res = vbYes Then
    'Այստեղ փակում է պատուհանը 
End If
```