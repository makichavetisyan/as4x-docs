<html>
<head>
<title>Документ\SetRekvsClickDropDownEvent</title>
    <style type="text/css">
        .style1
        {
            text-decoration: none;
        }
        .style2
        {
            color: #000000;
        }
        .style3
        {
            color: #000000;
            text-decoration: none;
        }
        .style4
        {
            font-weight: normal;
        }
    </style>
</head>

<body>

<p><font size="4" face="Arial"><strong>Свойство SetRekvsClickDropDownEvent<br>
</strong></font></p>
    <p><font face="Arial"><a href="SetGridColsClickDropDownEvent.html">
См. также</a>&nbsp; 
        <a href="../../Examples/E_SetRekvsClickDropDownEvent.html">Пример</a> &nbsp;<a href="../Asdoc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Возвращает или устанавливает признак генерации 
    системного события <a href="../../ScriptProcs/ClickDropDown.html">
ClickDropDown</a>&nbsp;
соответственно для указанных реквизитов документа.</font></p>

<p class="label"><font face="Arial">Свойство для чтения и записи.</font></p>
    <p class="label">&nbsp;</p>

<p class="label"><b><font face="Arial">Синтаксис</font></b></p>

    <a href="../../ScriptProcs/ClickDropDown.html" class="style1">
    <p><font face="Arial"><span class="style2"><em>object.</em></span><span 
            class="style2"><strong>SetRekvsClickDropDownEvent</stro 
(<em> </strong>(sRekvNames,
</em>[<em>bValue</em>]<em>, [sDelimeter]</em> )</span></font></p>

<p><font face="Arial"><span class="style2">Синтаксис свойства<strong>

</strong> </span> 
    <strong>

    <strong>
    <span class="style2">SetRekvsClickDropDownEvent</stro
состоит из следующих частей:</font></span></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, являющееся 
	ссылкой на экземпляр объекта типа документ.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sRekvNames</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификаторы реквизитов&nbsp; документа, для которых 
	соответственно устанавливается разрешение для генерации системного события <a
    href="../../ScriptProcs/ClickDropDown.html">ClickDropDown</a> .</font></td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>bValue</em></font></td>
    <td width="71%"><font face="Arial">необязательное логическое выражение, 
        определяющее признак генерации системного события <a href="../../ScriptProcs/ClickDropDown.html">
	ClickDropDown</a> . 

    <a href="../../ScriptProcs/ClickDropDown.html" class="style1">
        <span class="style4"><span class="style2">По умолчанию принимает значени </span>

    <a href="../../ScriptProcs/ClickDropDown.html" class="style3">
        True</a><span class="style2">, при значении которого

    </span>

    <a href="../../ScriptProcs/ClickDropDown.html" class="style3">
        ядром системы генерируется данное событие</a></span><strong>.</strong></font></td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sDelimeter</em></font></td>
    <td width="71%"><font face="Arial">необязательное строковое выражение, определяющее 
        любой символ или пробел, с помощью которого задаются&nbsp; реквизиты в </font>

    </strong></strong>

        <font face="Arial"> <span>
        <em>RekvNames</em>. По умолчанию 

    <a href="../../ScriptProcs/ClickDropDown.html" class="style1">
        <span class="style2">задаются с помощью пробелов.</span></a></span></font></td>
  </tr>
</TBODY>
</table>

<p class="label"><br class="style2">

    <strong>
    <span class="style2">Примечание</span></p>

    </strong>

    </strong></strong>

<p class="label"><span class="style2">&nbsp;&nbsp;&nbsp;Данное свойство применимо только к 
реквизитам&nbsp; документа. Причем их внутренний тип</span><strong>
    </strong>
    <span class="style2">должен 
быть</span><strong>
    </strong>
    </font><font face="Arial"> <a href="../../Types/Tree().html">Tree()</a>, <a
href="../../Types/FULLTREE().html">FullTree()</a>
    <span class="style2">или</span> <a href="../../Types/Folder().html">
Folder()</a>.
</p>
    </font>

    <strong>
    </a>
    <p class="label">
        &nbsp;</p>
    <p class="label">
        &nbsp;</p>
</body>
</html>