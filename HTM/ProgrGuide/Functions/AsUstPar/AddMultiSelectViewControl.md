<html>
<head>
<title>Диалог\AddMultiSelectViewControl</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Метод AddMultiSelectViewControl<br>
<br>
</strong></font><font face="Arial"><a href="AddViewControl.html">См. 
также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Asustpar.html">Применяется к</a></font></p>

<p><font face="Arial">Добавляет в пользовательский диалог реквизит 
типа <a href="../AsModalBrowser.html">произвольный вспомогательный список выбора</a>, 
с возможностью <a href="../AsModalBrowser/MultiSelect.html">отбора нескольких 
строк</a>. Вспомогательный список может содержать несколько колонок из вида 
просмотра, но две колонки должны быть специально объявлены для кода и 
наименования.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>call</strong> <em>object</em>.<strong>AddMultiSelectViewControl 
(</strong><em>sNameControl, sCaptionControl, sЕCaptionControl, sViewCode</em><strong>, </strong><em>
    sCodeColumnId, sCommentColumnId,  
Params()</em><strong>)</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>
AddMultiSelectViewControl</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее переменную, ссылающуюся на экземпляр объекта пользовательского 
	диалога.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">sNameControl</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sCaptionControl</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sЕCaptionControl</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге на иностранном языке.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sViewCode</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор базового вида просмотра, приводимого для выбора 
	значения.</font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>sCodeColumnId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор значимой колонки из вида просмотра. Значение 
	данной колонки будет подставлено в поле, после выбора из списка.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sCommentColumnId</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор колонки наименования из вида просмотра. </font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Params()</em></font></td>
    <td width="71%"><font face="Arial">массив параметров. Первый параметр <em>Params(0)</em> 
        определяет атрибуты реквизита(их может быть несколько). Второй параметр&nbsp; <em>Params(1)</em> 
        определяет значение реквизита. Все остальные, начиная с третьего 
        параметра, предназначены 
	для подстановки в вид просмотра.
    </font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Установки</b></font></p>

<p><font face="Arial">Установки для первого параметра <em>Params(0)</em> 
    следующие:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Значениеение</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial">&quot;B&quot;</font></td>
    <td width="71%"><font face="Arial">отсутствует кнопка выбора 
	значения реквизита (типа Folder, Tree) из списка &nbsp; </font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial">&quot;C&quot;</font></td>
    <td width="71%"><font face="Arial">после выбора значения реквизита 
	(типа Folder или Tree) его наименование не приводится рядом с выбранным 
	значением кода.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial">&quot;D&quot;</font></td>
    <td width="71%"><font face="Arial">данный реквизит доступен только 
	для чтения</font></td>
  </tr>
    <tr>
    <td style="width: 29%"><font face="Arial">&quot;H&quot;</font></td>
    <td width="71%"><font face="Arial">скрытый невидимый реквизит, при его наличии 
        остальные атрибуты реквизита игнорируются.</font></td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial">&quot;R&quot; </font></td>
    <td width="71%"><font face="Arial">данный реквизит обязателен для 
	заполнения.</font></td>
  </tr>
    <tr>
    <td style="width: 29%"><font face="Arial">&quot;S&quot;</font></td>
    <td width="71%"><font face="Arial">текущее значение реквизита не 
	запоминается в реестре</font></td>
    </tr>
</table>

<p class="label">&nbsp;</p>
</body>
</html>