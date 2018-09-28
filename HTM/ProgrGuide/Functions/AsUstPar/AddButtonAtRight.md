<html>
<head>
<title>Dialog\AddButtonAtRight</title>
    <style type="text/css">
        .style2
        {
            height: 33px;
        }
        .style3
        {
            font-family: Arial, Helvetica, sans-serif;
        }
        .newStyle1
        {
        }
        .style4
        {
            height: 47px;
        }
    </style>
</head>

<body>

<p><strong><font size="4" face="Arial">Метод AddButtonAtRight<br>
<br>
</font></strong><font face="Arial"><a href="../Asustpar.html">См. также</a>&nbsp; 
Пример&nbsp; <a href="../Asustpar.html">Применяется к </a></font></p>

<p><font face="Arial">Добавляет кнопку в пользовательский 
диалог справа от указанного реквизита.</font></p>

<p>&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>call</strong> <em>object</em>.<strong>AddButtonAtRight(</strong><em>NameButtonAtRight<strong>,</strong> 
    NameControl<strong>,</strong> </em>[<em>Caption</em>]<em><strong>,</strong> </em>
    [<em>ECaption</em>]<strong>, </strong>[<em>ButtonCaption</em>]<em><strong>,</strong> </em>
    [<em>ButtonEcaption</em>]<strong>,
</strong>[<em>Picture</em>]<strong>, </strong>[<em>AtrButton</em>]<strong>,</strong>
    [<em>sngWidth</em>] <strong>, </strong>[<em>iLeftPosition</em>]<strong>, </strong>
    [<em>iCaptionAlign</em>]<strong>)</strong></font></p>

<p><font face="Arial">Синтаксис метода <strong>AddButtonAtRight </strong>состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">object</font></em></td>
    <td width="71%">
        <p class="style3">
            <font face="Arial">Строковое выражение, определяющее переменную, ссылающуюся на 
            экземпляр объекта пользовательского диалога.</font></p>
      </td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">NameButtonAtRight</font></em></td>
    <td width="71%">
        <p>
            <font face="Arial">Строковое выражение, определяющее идентификатор кнопки.</font></p>
      </td>
  </tr>
    <tr>
    <td width="29%"><font face="Arial"><em>NameControl</em></font></td>
    <td width="71%">
        <p>
            <font face="Arial">Строковое выражение, определяющее идентификатор реквизита, 
            справа от которого будет добавлена кнопка.</font></p>
      </td>
    </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Caption</em></font></td>
    <td width="71%">
        <p>
            <font face="Arial">Необязательное строковое выражение, определяющее текст, приписываемый к 
            кнопке слева.</font></p>
      </td>
  </tr>
  <tr>
    <td width="29%" class="style4"><font face="Arial"><em>ECaption</em></font></td>
    <td width="71%" class="style4">
        <p>
            <font face="Arial">Необязательное строковое выражение, определяющее текст на иностранном языке, 
            приписываемый к кнопке слева.</font></p>
      </td>
  </tr>
</TBODY>
  <tr>
    <td width="29%"><font face="Arial"><em>ButtonCaption</em></font></td>
    <td width="71%">
        <p>
            <font face="Arial">Необязательное строковое выражение, определяющее текст записываемый на 
            кнопке.</font></p>
      </td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>ButtonEcaption</em></font></td>
    <td width="71%">
        <p>
            <font face="Arial">Необязательное строковое выражение, определяющее текст на иностранном языке, 
            записываемый на кнопке.</font></p>
      </td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Picture</em></font></td>
    <td width="71%">
        <p>
            <font face="Arial">Необязательное строковое выражение, определяющее 
            идентификатор 
            рисунка, отображаемого на кнопке формата Bitmap (*.bmp) из ресурсного файла 
            проекта (*.res). </font></p>
      </td>
  </tr>
  <tr>
    <td width="29%" class="style2"><font face="Arial">AtrButton</font></td>
    <td width="71%" class="style2">
        <p>
            <font face="Arial">Необязательное строковое выражение, определяющее <a href="Attribute.html">атрибут</a> кнопки.</font></p>
      </td>
  </tr>
    <tr>
    <td width="29%" class="style2"><font face="Arial">sngWidth</font></td>
    <td width="71%" class="style2">
        <p>
            <font face="Arial">Необязательное чысленное&nbsp; выражение, определяющее ширину кнопки 
            в пикселях. По умолчанию принимает значение 0.<br />
            </font></p>
        </td>
    </tr>
    <tr>
    <td width="29%" class="style2"><font face="Arial"><em>iLeftPosition</em></font></td>
    <td width="71%" class="style2">
        <p>
            <font face="Arial">Необязательное целое, чысленное&nbsp; выражение, определяющее 
            удаленность кнопки 
            с левой стороны. По умолчанию принимает значение 0.</font></p>
        </td>
    </tr>
</table>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
    <tr>
    <td width="29%" class="style2"><font face="Arial"><em>iCaptionAlign</em></font></td>
    <td width="71%" class="style2">
        <p>
            <font face="Arial">Необязательное целое, чысленное&nbsp; выражение, определяющее 
            положение заголовка кнопки. При значении 1 - с отступом, 0 - без отступа, с 
            начальной позиции. По умолчанию принимает значение 0.</font></p>
        </td>
    </tr>
</table>

</body>
</html>