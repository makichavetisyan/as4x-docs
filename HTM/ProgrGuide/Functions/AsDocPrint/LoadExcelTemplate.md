<html>
<head>
<title>Шаблон печати\LoadExcelTemplate</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод LoadExcelTemplate<br>
<br>
</strong></font><font face="Arial"><a href="LoadWordTemplate.html">См. 
также</a>&nbsp; <u>Пример</u>&nbsp; <a href="../AsDocPrint.html">Применяется к</a></font></p>

<p><font face="Arial">Загружает шаблонную форму печати документа в 
формате Excel и создает ссылку на файл Excel-а.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><em>object</em><strong>.LoadExcelTemplate (</strong><em>sTmplName</em><strong>)</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>LoadExcelTemplate</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows" height="94">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%" height="18"><font face="Arial"><b>
	Параметр</b></font></td>
    <td class="label" width="71%" height="18"><font face="Arial"><strong>
	Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%" height="18"><font face="Arial"><em>object</em></font></td>
    <td width="71%" height="18"><font face="Arial">строковое 
	выражение, ссылающееся на <a href="../Functions/InterfaceManagment/DocP.html">
	объект печатной формы.</a></font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%" height="16"><font face="Arial"><em>sTmplName</em></font></td>
    <td width="71%" height="16"><font face="Arial">строковое 
	выражение, определяющее идентификатор шаблона</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание</b></font></p>

<p class="label"><font face="Arial">Данный метод вызывается из 
обработчиков системных событий <a
href="../../ScriptProcs/Print.html">Print</a>, <a href="../../ScriptProcs/PrintExcel.html">
PrintExcel</a>,
<a href="../../ScriptProcs/PrintWord.html">PrintWord</a>.</font></p>
</body>
</html>