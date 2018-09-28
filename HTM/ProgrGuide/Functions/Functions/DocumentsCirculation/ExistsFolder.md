<html>
<head>
<title>ExistsFolder</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Функция ExistsFolder</font></strong></p>

<p class="label"><font face="Arial">Возвращает наличие папки с 
заданным идентификатором.</font></p>

<p class="label"><font face="Arial">Возвращаемое значение логическое.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>ExistsFolder</strong>(<em>FolderId</em>)</font></p>

<p><font face="Arial">Синтаксис функции <strong>ExistsFolder</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><em><font face="Arial">FolderId</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор папки</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><a href="../../../functions.html"><font face="Arial">
См. также</font></a></p>

<p class="label">&nbsp;</p>

<p><strong><font size="3" face="Arial">Пример функции </font><font
face="Arial">ExistsFolder</font></strong></p>

<p><font face="Arial">Из описания документа приведен пример скриптовой 
процедуры Delete, в котором проверяется существование папки с идентификатором 
&quot;Contr.&quot; &amp; trim(Doc(&quot;CODE&quot;))</font></p>

<p><font face="Arial">Sub Delete()<br>
If <strong>ExistsFolder</strong>(&quot;Contr.&quot; &amp; trim(Doc(&quot;CODE&quot;))) Then <br>
&nbsp;&nbsp; Err.Raise gintUserErrors , &quot;Удаление недопустимо&quot;, _<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&quot;По данному договору имеется счет-фактура&quot;<br>
End If<br>
End Sub <br>
</font></p>
</body>
</html>