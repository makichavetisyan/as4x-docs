﻿<html>
<head>
<title>Системное событие документа ClickDropDown</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Событие ClickDropDown<br>
<br>
</strong></font><a href="../scriptstproced.html">См. также</a>&nbsp; <u>Пример</u>&nbsp;
<a href="../Defs/doc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">В некоторых случаях, при выборе 
значений реквизитов документа типа <a
href="../Types/Tree().html">Tree()</a>, <a href="../Types/FULLTREE().html">
FullTree()</a>, <a
href="../Types/Folder().html">Folder()</a> необходимо приводить не весь список 
одноуровневого дерева или папки, а некоторое его отфильтрованное подмножество. 
Этого можно достичь в обработчике системного события <strong>ClickDropDown</strong>, 
если генерация данного события <a href="../Functions/ASDOC/ClickDropDownEvent.html">
разрешена</a>
ядром системы. В обработчике события нужно создать экземпляр <a href="../Functions/AsModalBrowser.html">
объекта типа произвольный вспомогательный список</a>, который и будет появляться 
при нажатии кнопки выбора значения реквизита. Т.о. в результате нажатия кнопки 
выбора будет приводиться не папка, указанная в описании реквизита, а 
отфильтрованный вспомогательный список. Данное событие может генерироваться 
также для числовых типов <a href="../Types/Summa.html">Summa</a>, <a href="../Types/Summap.html">
SummaP</a>,
<a href="../Types/N().html">N()</a>, <a href="../Types/Np().html">NP()</a>,
<a href="../Types/Ch().html">CH()</a> (например для выбора партий товара на 
количестве).</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>ClickDropDown</strong> (<strong><em>Rekv</em></strong>,
<em>Top</em>, <em>Left</em>, [<em>sValue</em>])</font></p>

<p><font face="Arial">&nbsp;&nbsp; <strong>Select Case</strong> <strong>
Rekv</strong>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Case</strong> <em>Rekv1</em><br>
<em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; statements1</em><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Case</strong> <em>Rekv2</em><br>
<em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; statements2</em><br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; . . . . .<br>
</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Case</strong> <em>RekvN</em><br>
<em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; statementsN</em><br>
<strong>&nbsp;&nbsp;&nbsp; End Select&nbsp; </strong>&nbsp;&nbsp; <br>
<br>
End Sub</font></p>

<p><font face="Arial">Синтаксис события <strong>ClickDropDown</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Rekv_i</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в документе, для которого сгенерировано 
	данное событие.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Top</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Single, 
	определяющее расстояние между верхним краем вспомогательного списка и 
	верхним краем формы документа.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Left</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Single, 
	определяющее расстояние между левым краем вспомогательного списка и левым 
	краем формы документа.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sValue</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, для передачи в качестве поискового <a href="../Functions/AsModalBrowser/LookUpValue.html">
	значения</a>
    параметра в <a href="../Functions/AsModalBrowser/LookUpColumn.html">искомой 
	колонке</a>. Данный параметр используется для установки маркера на строку с 
	указанным значением при наборе с клавиатуры. Тип поиска должен быть 
	установлен с помощью свойства <a
    href="../Functions/AsModalBrowser/LookUpSoftMode.html">LookUpSoftMode</a>.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>statements_i</em></font></td>
    <td width="71%"><font face="Arial">подпрограмма создания ссылки на <a href="../Functions/AsModalBrowser.html">
	объект типа произвольного вспомогательного списка</a>.</font></td>
  </tr>
</table>
</body>
</html>