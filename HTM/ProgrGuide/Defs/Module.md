﻿<html>
<head>
<title>Module Definition</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Описание модуля</font></strong></p>

<p><font face="Arial">Описывается процедурный модуль. Он может 
содержать процедуры и функции для доступа к ним из скриптового раздела описаний <a href="doc.html">
документов</a>, <a href="Data.html">источников данных</a>, <a href="Tree.html">
деревьев</a>, <a href="report.html">отчетов</a>
и <a href="Accounting.html">учетов</a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>Module</strong> { <strong>Name</strong> 
=<em>
sModName</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Caption</strong> = <em>sModCaption</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ЕCaption</strong> = <em>sModЕCaption</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Public&nbsp; </strong>= <em>nModPublic</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Version </strong>= <em>nVersion</em>;<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Script</strong> {<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong><em>Subs and Functions<br>
</em><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong>};<br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong>};<br>
</font></p>

<p><font face="Arial">Синтаксис описания процедурного модуля состоит 
из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sModName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор модуля, для доступа к нему <a href="report.html">
	из описания отчета</a> или процедуры <a href="../Functions/Functions/SysDefManagment/RunSub.html">
	RunSub</a>.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sModCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок модуля</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sModECaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок модуля на иностранном языке</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>nModPublic</em></font></td>
    <td width="71%"><font face="Arial">численное выражение, 
	принимающее значение 0 или 1, определяющее возможность доступа к процедурам 
	и функциям модуля из любого скрипта. Такой модуль называется общедоступным.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>nVersion</em></font></td>
    <td width="71%"><font face="Arial">численное выражение целого 
	типа, определяющее номер версии описания модуля.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Subs and Functions</em></font></td>
    <td width="71%"><font face="Arial">пользовательские процедуры и 
	функции в любом количестве</font></td>
  </tr>
</TBODY>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание<br>
<br>
</b>Если <em>nModPublic</em>=0, тогда доступ к функциям и процедурам, описанным 
в модуле может осуществлятся только с помощью метода <a href="../Functions/Functions/SysDefManagment/RunSub.html">
RunSub</a>.</font></p>

<p class="label"><font face="Arial"><a href="../Defs.html">См. также</a></font></p>

<p class="label">&nbsp;</p>
</body>
</html>