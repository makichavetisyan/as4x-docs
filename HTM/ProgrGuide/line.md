---
layout: page
title: "Line նկարագրություն"
---

# Բաժանարար-գծի նկարագրություն 

Նախատեսված է փաստաթղթի վրա հորիզոնական գիծ տեղադրելու համար, որի վրա կարող է նաև գրված լինել որևէ տեքստ։

## Շարահյուսություն 

``` as4x
Line {
    Caption = sLineCaption;
    ECaption = sLineECaption;  
    AllowCaption = nAllowCaption;
};
```

| Պարամետր | Նկարագրություն |
|--|--|
| sLineCaption | Գծի վրայի տեքստը։ Չլրացնելու դեպքում գծի վրա տեքստ չի գրվում։ |
| sLineECaption | Գծի վրայի տեքստը օտար լեզվով։ |
| nAllowCaption | Տեքստի դիրքը գծի վրա։ <br/> 0 արժեքի դեպքում գլխագիրը ձախ կողմում է, <br/> 1-ի դեպքում՝ աջ, <br/> 2-ի դեպքում՝ կենտրոնում։ <br/> Լռությամբ արժեքը 0։ |