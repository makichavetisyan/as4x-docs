<html>
<head>
<title>Проводка\DbCr</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Свойство DbCr<br>
<br>
</font></strong><font face="Arial"><a href="../Asfact.html">См. также</a>&nbsp;
<a href="../../Examples/E_AsFact.html">Пример</a>&nbsp; <a href="../Asfact.html">
Применяется к</a></font></p>

<p><font face="Arial">Возвращает или устанавливает признак дебетования 
или кредитования объекта проводки.</font></p>

<p><font face="Arial">Свойство для чтения и записи.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.DbCr</strong> [=<em>sValue</em>]&nbsp; 
&nbsp;</font></p>

<p><font face="Arial">Синтаксис свойства <strong>DbCr</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>object</em></font></td>
    <td width="71%"><font face="Arial">переменная, ссылающаяся на 
	объект типа проводка.</font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial"><em>sValue</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее признак дебетования или кредитования объекта.</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">Установки для <em>sValue</em>
следующие:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Значение</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">D</font></td>
    <td width="71%"><font face="Arial">Выбранный объект дебетуется</font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><font face="Arial">C</font></td>
    <td width="71%"><font face="Arial">Выбранный объект кредитуется</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><b><font face="Arial">Примечание</font></b></p>

<p class="label"><font face="Arial">Если в описании учета указано, что 
ведется <a href="../ASAccounting/Remainder.html">отслеживание остатков</a>, а 
свойство DbCr не равно &#39;D&#39; или &#39;C&#39;, то выдается сообщение об ошибке.</font></p>
</body>
</html>