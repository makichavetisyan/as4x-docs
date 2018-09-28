<html>
<head>
<title>SetParam</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод SetParam</strong></font></p>

<p><font face="Arial">Устанавливает новое значение параметра. В 
отличие от свойства <a href="Param.html">Param</a>, данная процедура изменяет 
значение параметра непосредственно в базе данных, несмотря на перманентность. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>SetParam</strong> (<em>sParId, sValue, </em>
[<em>nSUID</em>])</font></p>

<p><font face="Arial"><br>
Синтаксис метода<strong> SetParam</strong> состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr vAlign="top">
    <td width="29%"><em><font face="Arial">sParId</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор существующего параметра. Если параметр с 
	указанным идентификатором не существует, генерируется ошибка.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sValue</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Variant, 
	определяющее подставляемое значение параметра. Если подставляемое значение 
	не соответствует типу параметра, генерируется ошибка.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">nSUID</font></em></td>
    <td width="71%"><font face="Arial">необязательное численное 
	выражение целого типа, определяющее код пользователя для которого изменяется 
	значение параметра. Если код пользователя не задан, то значение параметра 
	устанавливается для всех пользователей одновременно.</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание<br>
</b><br>
<a href="GetParam.html">См. также</a></font></p>
</body>
</html>