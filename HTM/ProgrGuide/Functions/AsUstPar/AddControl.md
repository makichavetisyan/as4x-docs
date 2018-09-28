<html>
<head>
<title>Диалог\AddControl</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод AddControl<br>
<br>
</font></strong><font face="Arial"><a href="../Asustpar.html">См. также</a>&nbsp;
<a href="../../Examples/E_AsUstPar.html">Пример</a>&nbsp; <a href="../Asustpar.html">
Применяется к</a></font></p>

<p><font face="Arial">Добавляет реквизит ввода в пользовательский 
диалог.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>call</strong> <em>object</em>.<strong>AddControl(</strong><em>RekvName, 
CaptionRekv, TypeRekv</em><strong>, </strong>[<em>AttribRekv</em>]<em>, </em>[<em>ValueRekv</em>]<strong>,
</strong>[<em>ECaptionRekv</em>]<strong>, </strong>[<em>iSaveValue</em>], 
    [<em>iCommentlen</em>] 
)</font></p>

<p><font face="Arial">Синтаксис метода <strong>AddControl</strong>
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
    <td width="29%"><font face="Arial"><em>RekvName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>CaptionRekv</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок реквизита в диалоге.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">TypeRekv</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее <a href="../../types.html">тип реквизита</a> в диалоге. </font></td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><em><font face="Arial">AttribRekv</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее <a href="Attribute.html">атрибуты</a>
    реквизита (их может быть несколько). </font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">ValueRekv</font></em></td>
    <td width="71%"><font face="Arial">необязательное выражение типа 
	Variant, определяющее первоначальное значение реквизита.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">ECaptionRekv</font></em></td>
    <td width="71%"><font face="Arial">необязательное строковое 
	выражение, определяющее заголовок реквизита в диалоге на иностранном языке.</font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">iSaveValue</font></em></td>
    <td width="71%"><font face="Arial">необязательное численное 
	выражение, определяющее признак запоминания значений реквизита. При 1 - 
	текущее значение реквизита запоминается в реестре, а при значении 0 - нет. 
	По умолчанию принимает значение 1.<br />
        </font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>iCommentlen</em></font></td>
    <td width="71%"><font face="Arial">необязательное численное 
        выражение, определяющее длину комментарий для типов
        <a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/progr_guide/htm/ProgrGuide/Types/Folder().html">
        Folder()</a>,
        <a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/progr_guide/htm/ProgrGuide/Types/Tree().html">
        Tree()</a> и
        <a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/progr_guide/htm/ProgrGuide/Types/FULLTREE().html">
        FullTree()</a>. По умолчанию принимает значение 32.<br />
        </font></td>
    </tr>
    </table>

</body>
</html>