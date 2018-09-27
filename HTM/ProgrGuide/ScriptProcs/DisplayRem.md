﻿<html>
<head>
<title>Системное событие DisplayRem</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Событие DisplayRem<br>
<br>
</strong></font><font face="Arial"><a href="DisplayFact.html">См. также</a>&nbsp;
<a href="../Examples/E_DisplayRem.html">Пример</a>&nbsp; <a
href="../Defs/Accounting.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Происходит перед сохранением 
проводок. Данное событие выводит возможные остатки объектов проводок в окне 
подтверждения. По прошествии 15 секунд окно предварительного показа остатков 
автоматически закрывается с условием &quot;Отмена&quot;, а регистрации проводок не 
происходит. Данное событие генерируется при значении функции <a href="../Functions/Functions/AccManagement/ShowTrans.html">
ShowTrans</a> = True, а также при вызове метода <a href="../Functions/ASDOC/CheckAndStore.html">
CheckAndStore</a>. Оно генерируется после события <a href="DisplayFact.html">
DisplayFact</a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Function <strong>DisplayRem</strong>(<em>xISN, 
xAccRem, xLinkedRem,<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
xAccRemNC, xLinkedRemNC</em>)<br>
<em>&nbsp;&nbsp;&nbsp;&nbsp; statements</em><br>
End Function</font></p>

<p><font face="Arial">Синтаксис события <strong>DisplayRem</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">xISN</font></em></td>
    <td width="71%"><font face="Arial">длинное целое, определяющее 
	внутрисистемный уникальный идентификатор объекта учета. </font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">xAccRem</font></em></td>
    <td width="71%"><font face="Arial">выражение типа Currency, 
	определяющее остаток объекта в основном учете в валюте. </font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">xLinkedRem</font></em></td>
    <td width="71%"><font face="Arial">выражение типа Currency, 
	определяющее остаток объекта в связанном учете в валюте.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">xAccRemNC</font></em></td>
    <td width="71%"><font face="Arial">выражение типа Currency, 
	определяющее остаток объекта в основном учете в национальной денежной 
	единице.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">xLinkedRemNC</font></em></td>
    <td width="71%"><font face="Arial">выражение типа Currency, 
	определяющее остаток объекта в связанном учете в национальной денежной 
	единице.</font></td>
  </tr>
</table>
</body>
</html>