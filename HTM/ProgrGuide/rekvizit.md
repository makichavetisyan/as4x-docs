---
layout: page
title: "Rekvizit նկարագրություն"
---

# Մուտքագրման դաշտի նկարագրություն

Նախատեսված է փաստաթղթի վրա մուտքագրման դաշտ տեղադրելու համար։ Դաշտը կարող է նաև չլինել տեսանելի և օգտագործվել ծրագրային պրոցեսներում։

## Շարահյուսուրյուն

``` as4x
Rekvizit {
    Name = sRekvName;
    Caption = sRekvCaption;  
    ECaption = sRekvECaption;
    Type = sRekvType;
    Atributs = sRekvAtr;
    DisplayAtRight = nDisplayAtRight;
    ShowCaption = nShowCaption;   
    Distance = nDistance;   
    CommentLen = nCommentLen;
    ShowType = sRekvShowType;
    DropDown  { ViewName = sViewName; Code = sViewCodeCol; Comment = sViewCaptionCol;
        ParamValue { Name = sParamName1; Value= sParamValue1; };
        '...
        ParamValue { Name = sParamNameN; Value= sParamValueN; };
    };
};
```

| Պարամետր | Նկարագրություն |
|--|--|
| sRekvName | Դաշտի ներքին անունը։ |
| sRekvCaption | Դաշտի անվանումը։ |
| sRekvECaption | Դաշտի անվանումը օտար լեզվով։ |
| sRekvType | Դաշտի արժեքների [ներքին տիպը](types.md)։ |
| sRekvAtr | Դաշտի հատկանիշները։ Կարող են նշվել միառժամանակ մի քանիսը։ Արժեքներն են՝ <br/> `R` Պարտադիր լրացման դաշտ։ <br/> `S` դաշտը ենթակա է կրկնակի մուտքագրման։ <br/> `C` [Tree](Types/Tree.md), [FullTree](Types/FULLTREE.md), [Folder](Types/Folder.md) տիպերի համար ցույց չի տալիս  անվանումը ցանկից ընտրելուց հետո։ Իսկ [Date](Types/Date.md) տիպի դաշտի կողքին ցույց է տալիս շաբաթվա օրվա անվանումը։ <br/> `B` Թաքցնում է ցանկից ընտրելու կոճակը, իսկ թվային տիպերի համար հաշվիչի ցուցադրման փոխարեն աշխատացնում է `DropDown` իրադարձությունը։ <br/> `I` Դաշտը լրացվում է Overwrite ռոժիվով Insert-ի  փոխարեն (միայն [C()](Types/C.md) տիպի համար)։ <br/> `H` Անտեսանելի դաշտ, որի առկայության դեպքում դաշտի մնացած հատկանիշները անտեսվում են։ <br/> `N` Հաջորդական մուտքագրման ռեժիմում դաշտը պահպանում է նախորդող փաստաթղթի արժեքը։ <br/> `U` Լատինական փոքրատառ տառերը  դարձնում է մեծատառ։ <br/> `F` Դաշտի համար այլընտրանքային(ռուսերեն) տառատեսակի օգտագործում։ <br/> `V` Փաստաթղթի պահպանման ժամանակ անջատում է դաշտի տիպի ստուգումը միջուկի կողմից։ <br/> `Z` Փաստաթղթի դիտելուց Tab/Enter ստեղները բաց չի թողնում այս դաշտը։ <br/> `P` Նշված դաշտը ֆոկուս կստանա փաստաթղթի ակտիվանալուց։ <br/> `E` ԱՆջատում է մուտքագրվող արժեքի ցուցակում լինելու ստուգումը։ Օգտագործվում է [Tree](Types/Tree.md), [Folder](Types/Folder.md) և [NumPair](Types/NumPair.md) տիպի դաշտերի համար։ <br/> `T` Տվյալների պահոցում դաշտի արժեքի չի պահպանվում: Նմանատիպ տաշտերի արժեքները սովորաբար սահմանվում են փաստաթղթի բեռնման ժամանակ [AfterLoad](ScriptProcs/AfterLoad.md) իրադարձության մեջ։ |
| sDisplayAtRight | 0 արժեքի դեպքում դաշտը տեղադրվում է նոր տողում։ <br/> 1 արժեքի դեպքում՝ նախորդ դաշտի աջ կողմից `Distance` հեռավորության վրա։ <br/> 2 արժեքի դեպքում դաշտը տեղադրվում է նախորդ դաշտի տողում պատուհանի ձախ եղրից `Distance` հեռավորության վրա։ <br/> Լռությամբ արժեքը 0։ |
| nShowCaption | 1 արժեքի դեպքում կոճակի անվանումը կցուցադրվի։ Կիրառելի է միայն `DisplayAtRight`-ի 1 կամ 2 արժեքների դեպքում։ Լռությամբ արժեքը 0։ |
| nDistance | Դաշտի հեռավորությունը նախորդ դաշտից կամ պատուհանի եզրից։ Տե՛ս `DisplayAtRight`: Լռությամբ արժեքը 100։ |
| nCommentLen | Սահմանում է [Folder()](Types/Folder.md), [Tree()](Types/Tree.md) և [FullTree()](Types/FULLTREE.md) տիպի դաշտի մեկնաբանության երկարությունը։ Լռությամբ արժեքը 32։ |
| sRekvShowType | դաշտի ցուցադրման տիպ։ Օգտագործվում է միայն [C()](Types/C.md) տիպի դաշտերի համար։ Գրելաձևն է՝ `С(RowCount * SymbolPerRow)`, որտեղ `RowCount`-ը ցուցադրման ժամանակ տողերի քանակն է, իսկ `SymbolPerRow`-ը՝ նիշերի քանակը յուրաքանչյուր տողի մեջ։ |
| sViewName | Դիտելու ձևի ներքին անուն, որը բացվում է այս դաշտի համար։ |
| sViewCodeCol |Դիտելու ձևի սյունակի ներքին անուն, որի արժեքը լրացվելու է դաշտի մեջ։ |
| sViewCaptionCol | Դիտելու ձևի սյունակի ներքին անուն, որի արժեքը լրացվելու է դաշտի մեկնաբանության մեջ։ |
| sParamName | Դիտելու ձևին փոխանցվող պարամետրի ներքին անուն։ |
| sParamValue | Դիտելու ձևին փոխանցվող պարամետրի արժեք։ |

## Նկատառումներ

DropDown-ը հնարավոր է օգտագործել միայն [Folder()](Types/Folder.md), [FullTree()](Types/FULLTREE.md), [Tree()](Types/Tree.md) և [CH()](Types/Ch.md) տիպի դաշտերի համար։ Ցանկալի է որպեսզի օգտագործման ժամանակ համապատասխան դաշտի հատկանիշը պարունակի `V` արժեքը։