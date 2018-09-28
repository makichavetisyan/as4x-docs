<html>
<head>
<title>Текущий вид просмотра\RegistrNode</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод RegistrNode<br>
<br>
</font></strong><font face="Arial"><a href="../Frmpttel.html">См. также</a>&nbsp;
<a href="../../Examples/E_FrmPttel_RegistrNode.html">Пример</a>&nbsp; <a
href="../Frmpttel.html">Применяется к</a></font></p>

<p><font face="Arial">Добавляет группировочный узел в подменю вызовов 
пользовательских функций. При большом количестве вызываемых функций их удобнее 
сгруппировать в структуру подменю, используя данный метод.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.RegistrNode (</strong><em>NodeId, 
mnCaption, </em>[<em>ParentId</em>]<em>, </em>[<em>ECaption</em>]<em>, [AvailableFor])</em></font></p>

<p><font face="Arial">Синтаксис метода <strong>RegistrNode</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>object</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на текущую папку.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>NodeId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор узла.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>mnCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок узла.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>ParentId</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее ссылку на идентификатор (<em>NodeId</em>) узла 
	дерева контекстных вызовов. Если не задано, то текущий пункт меню 
	добавляется на корневом уровне.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>ЕCaption</em></font></td>
    <td width="79%"><font face="Arial">необязательное строковое 
	выражение, определяющее заголовок узла добавляемой в контекстное меню на 
	иностранном языке. По умолчанию значение равно <em>Caption.</em></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>AvailableFor</em></font></td>
    <td width="79%"><font face="Arial">необязательное цифровое 
	выражение, определяющее <a href="../../Constants/const_RegistrFunctionAvailability.html">константу видимости</a> группировочного узла.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">Данный метод должен быть вызван в 
обработчике системного события
<a href="../../ScriptProcs/FunctionsData.html">Functions</a>. </font></p>
</body>
</html>