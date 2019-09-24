---
layout: page
title: "Tree Definition"
---

# Ծառ-տեղեկատուի նկարագրություն

[См. также](../Defs.html)

Ծառ-տեղեկատուն կարող է լինել կա՛մ միամակարդակ, կա՛մ բազմամակարդակ հիերարխիայով։ Ծառը կարող է ունենա պարզ հանգույցներ, որոնք պարունակում են միայն կոդ և անուն կամ փաստաթուղթ հանգուցներ։

## Շարահյուսություն

``` as4x
TREE { 
    Name = sTreeName;
    Caption = sTreeCaption;
    ECaption = sTreeECaption;
    Description = sTreeDescription;
    Type = nType;
    CodeLen = nCodeLen;
    UpperCase = nUpperCase;
    AllowEdit = nAllowEdit;
    AllowView = nAllowView;
    AllowDelete = nAllowDelete;
    AllowAddNode = nAllowAddNode;
    AllowExport = nAllowExport;
    AllowHistory = nAllowHistory;
    PathLastSeparator = nPathLastSeparator;
    Doc { = sDocName1; ...; = sDocNameN; };
    DefaultFunction = sDefaultFuncName;
    SelectNonDoc = nAllowSelectNonDoc
    Version = nVersion;
    SCRIPT {
       Subs and Functions
    };
}; 
```
Բաղադրիչներն են՝

| Պարամետր | Նկարագրություն |
|--|--|
| sTreeName | Տողային արտահայտություն, որը սահմանում է ծառի ներքին անունը։ |
| sTreeCaption | Տողային արտահայտություն, որը սահմանում է ծառի գլխագիրը։ |
| sTreeECaption | Տողային արտահայտություն, որը սահմանում է ծառի գլխագիրը օտար լեզվով։ |
| sTreeDescription | Տողային արտահայտություն, որը սահմանում է ծառի հակիրճ նկարագրությունը։ |
| nType | Թվային արտահայտություն, որը սահմանում է ծառի տիպը՝ 1 - միամակարդակ կամ 2 - բազմամակարդակ։ |
| nCodeLen | Թվային արտահայտություն, որը սահմանում է ծառի կոդի երկարությունը։ |
| nUpperCase | Թվային արտահայտություն, որը ընդունում է 1 կամ 0 արժեք և սահմանում է ծառի հանգույցների կոդը բոլորը մեծատառով պահելու հատկությունը։ Ըստ լռության 0 է։ |
| nAllowEdit | 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանվում է ծառի հանգույցը խմբագրելու թույլատվությունը։ |
| nAllowView | 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանում է ծառի հանգույցը դիտելու թույլատվությունը։ |
| nAllowDelete | 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանում է ծառից հանգույց ջնջելու թույլատվությունը։ |
| nAllowAddNode | 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանում է ծառին հանգույց ավելացնելու թույլատվությունը։ |
| nAllowExport | 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանում է ծառից հանգույց արտահանելու թույլատվությունը։ |
| nAllowHistory | 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանում է ծառի հանգույցների փաստաթղթի պատմությունը դիտելու թույատվությունը։ Ըստ լռության 1 է։ |
| nPathLastSeparator | 1 կամ 0 արժեք ընդունող թվային արտահայտություն։ 1 արժեքի դեպքում TREES աղյուսակի fCODX սյան արժեքի վերջում ավելանում է \ բաժանիչ նշանը, հակառակ դեպքում այդ նշանը չկա։ Ըստ լռության 0 է։ |
| sDocNamei | Տողային արտահայտություն, որը սահմանում է այն [փաստաթղթերի](doc.html) տեսակները, որոնց հնարավոր է ստեղծել ծառի միջից։ Ծառի հագույց և տերև կարող են լինել տարբեր տիպի փաստաթղթեր, ընդ որում դրանց հերթականությունը ծառի հիերարխիայի մեջ ոչ մի կերպ չի որոշվում։ Դրվում է միայն հետևյալ սահմանափակումը. փաստաթղթային հանգույցի տակից չի կարելի ավելացնել ոչ փաստաթղթային հանգույց, թույլատրվում է ավելացնել միայն փաստաթղթային հանգույցներ։ Պետք է հիշել, որ ծառից փաստաթուղթ ստեղծելու համար նույն փաստաթղթի ստեղծումը պետք է հասանելի լինի ԱՇՏ-ից։ |
| nAllowSelectNonDoc| 1 կամ 0 արժեք ընդունող թվային արտահայտություն, որը սահմանում է ծառ-տեղեկատուից ոչ փաստաթղթային հանգույցի ընտրության թույլատվությունը։ |
| sDefaultFuncName | Այն ֆունկցիայի անունը, որը կանչվում է մկնիկի կրկնակի սեղմման կամ Enter ստեղնի սեղմման ժամանակ։ Թույլատրելի արժեքները նկարագրված են ստորև։ |
| nVersion | (Հնացած) Ամբողջ տիպի թվային արտահատություն, որը սահմանում է ծառի նկարագրության տարբերակի համարը։ |
| Subs and Functions | Նկարագրության սկրիպտային բաժին, որը կարող է պարունակել ինչպես [համակարգային իրադարձությունների մշակիչներ](../scriptstproced.html), այնպես էլ օգտագործողի կողմից գրված պրոցեդուրաներ և ֆունկցիաներ։ |


## Հաստատուններ

`sDefaultFuncName`-ի արժեքներն են՝ 

| Արժեք | Նկարագրություն |
|--|--|
| EDITITEM | Փաստաթուղթը բացում է էկրանին խմբագրման ռեժիմում։ |
| VIEWITEM | Փաստաթուղթը բացում է էկրանին դիտման ռեժիմում։ |
| DELETEITEM | Փաստաթուղթը ջնջում է։ |
| VISAITEM | Փաստաթուղթը բացում է էկրանին վավերացման ռեժիմում։ |
| SECONDENTRYITEM | Փաստաթուղթը բացում է էկրանին կրկնակի մուտքագրման ռեժիմում։ |
| Այլ արժեքներ | Կանչվում է օգտագործողի կողմից գրված այն ֆունկցիան, որը սահմանված է RegistrFunction-ի միջոցով։ |


## Օրինակ

``` as4x
TREE {
    NAME = SectEmpl;
    CAPTION = "Աշխատակիցների տեղեկատու";
    DESCRIPTION = "Աշխատակիցների տեղեկատու, ըստ բաժինների"
    TYPE = 2;
    CODELEN = 6;
    ALLOWEDIT = 1;
    ALLOWVIEW = 1;
    ALLOWDELETE = 1;
    ALLOWADDNODE = 1;
    DOC { = Employee; = Section; };
};
```