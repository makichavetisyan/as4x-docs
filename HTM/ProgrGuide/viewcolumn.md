﻿<html>
<head>
<title>Описание колонки вида просмотра</title>
<style type="text/css">
.style1 {
	color: blue;
	text-decoration: underline;
}
.style2 {
	border-width: 0;
}
.style3 {
	border: 1px solid #C5C5C5;
}
.style4 {
	font-weight: bold;
	border: 1px solid #C5C5C5;
}
.style7 {
	border: 1px solid #C5C5C5;
}
</style>
</head>

<body>

<p><strong><font size="4" face="Arial">Описание колонки вида просмотра</font></strong></p>

<br />
<font face="Arial"><b>Синтаксис<br />
</b><strong><br />
Column {&nbsp; <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Name </strong>=<strong> </strong><em>sColumnName</em><strong>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Total </strong>=<strong> </strong><em>nColumnTotal</em><strong>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Order </strong>=<strong> </strong><em>nColumnOrder</em><strong>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; AltFont </strong>=<strong> </strong><em>nColumnAltFont</em><span lang="en-us"><strong>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>
<span class="style2"><span lang="en-us">Type<span lang="ru"> </span></span>
</span>
</strong><span lang="en-us"><span class="style2"><em>=</em><span lang="ru"><em>
</em> </span>
<em>sColumnType; </em><strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Caption </strong>
<em>= sColumnCaption; </em><strong> <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ECaption </strong>
<em>= sColumnECaption; </em><strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ShowType<span lang="ru"> </span></strong>
<em>=</em><span lang="ru"><em> </em> </span>
<em>sColumnShowType</em><strong>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Activation<span lang="ru"> </span></strong><em>=</em><span lang="ru"><em> </em> </span>
<em>sActivation;</em><strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Calculation<span lang="ru"> </span></strong><em>=</em><span lang="ru"><em> </em> </span>
<em>sCalculation</em><strong>;</strong></span></span><strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
};</strong><br />
</font>

<table cellPadding="5" cols="2" frame="below" rules="rows" class="style2">
<TBODY>
  <tr vAlign="top">
    <td class="label" style="width: 2%">&nbsp;</td>
    <td class="style4" width="29%"><font face="Arial">Параметр</font></td>
    <td class="style3" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td class="style3" style="width: 2%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style3"><font face="Arial"><em>sColumnName</em></font></td>
    <td width="71%" class="style3">
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	строковое выражение, определяющее идентификатор колонки в виде просмотра.
	Идентификатор колонки или
	</span>
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	совпадает с идентификатором колонки в
	<a style="text-underline: single;" class="style1" href="Defs/Data.html">
	<span style="color: blue">источнике данных</span></a><span lang="en-us">
	</span>или должна быть задана формула вычисления.</span></td>
  </tr>
  <tr>
    <td class="style3" style="width: 2%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style3"><font face="Arial"><em>nColumnTotal</em></font></td>
    <td width="71%" class="style3">
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	необязательное числовое выражение, принимающее значения 1 или 0, 
	определяющее наличие итоговой суммы для числовых колонок. </span>
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	По умолчанию равно 0. </span></td>
  </tr>
  <tr>
    <td class="style3" style="width: 2%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style3"><font face="Arial"><em>nColumnOrder</em></font></td>
    <td width="71%" class="style3">
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	необязательное числовое выражение, определяющее номер очередной сортировки 
	колонки, если такая понадобится. Если принимающее значение &gt; 0, то 
	сортировка колонки проводится по возрастанию. Если принимающее значение &lt; 0, 
	то сортировка колонки проводится по убыванию. </span>
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	Одновременно может быть задана сортировка по пяти колонкам.</span></td>
  </tr>
  <tr>
    <td class="style3" style="width: 2%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style3"><font face="Arial"><em>nColumnAltFont</em></font></td>
    <td width="71%" class="style3">
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	необязательное числовое выражение, принимающее значения </span>
	<span lang="en-us" style="font-size: 12.0pt; line-height: 115%; font-family: Arial, sans-serif; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	0, 1</span><span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	или </span>
	<span lang="en-us">
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	2</span></span><span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">, 
	определяющее шрифт колонки. <br />
	</span>
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	<span lang="en-us">0 -&nbsp; </span>Используется армянский
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	шрифт <span lang="en-us">(</span>значение по умолчанию).<br />
	</span> </span>
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	1 -&nbsp; Если значении параметра </span>
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	USEALTFONT</span><span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">=</span><span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">True</span><span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">, 
	то 
	для колонки используется альтернативный (русский) шрифт,<br />
	2 -&nbsp;&nbsp; Если значении параметра
	<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	USEALTFONT</span>=<span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: EN-US; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">True 
	и пользователь использует английский (значении параметра LANG = 3) </span>&nbsp;для колонки используется альтернативный 
	(русский) шрифт</span><span lang="en-us"><span style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">.</span></span></td>
  </tr>
	<tr>
		<td style="width:3%; padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<img src="../../IMAGES/pubfield.gif" width="16" height="16"></td>
		<td width="29%" style="width:29.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
<em>
<font face="Arial"><span lang="en-us"><span class="style2">sColumnType</span></span></font></em></p>
		</td>
		<td width="71%" style="width:71.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU">
		необязательное
		строковое выражение, определяющее </span>
		<span style="font-size:12.0pt;font-family:
  &quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;">
		<a href="types.html">
		<span lang="RU" style="color:blue;mso-ansi-language:RU">внутренний тип 
		данных колонки</span></a></span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">. Необходимо задавать для </span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">вычисляемых </span>
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">колонок.</span></p>
		</td>
	</tr>
	<tr>
		<td style="width:3%; padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<img src="../../IMAGES/pubfield.gif" width="16" height="16"></td>
		<td width="29%" style="width:29.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
<font face="Arial"><span lang="en-us"><span class="style2">
<em>sColumnShowType</em></span></span></font></p>
		</td>
		<td width="71%" style="width:71.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU">
		необязательное строковое выражение, определяющее </span>
		<span style="font-size:
  12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;">
		<a href="types.html">
		<span lang="RU" style="color:blue;mso-ansi-language:RU">внутренний тип 
		данных колонки</span></a></span><span style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU"> <span lang="RU">при показе.</span></span><span style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;">&nbsp;</span><span lang="RU" style="font-size:12.0pt;
  font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;;
  mso-ansi-language:RU"> Если данный параметр опущен, то используется значение 
		свойства </span>
		<span style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;">Type</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">. Данное свойство обычно 
		использует если тип данных соответствующий значениям в колонке неудобен 
		для показа. Например, если значение</span><span style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;">&nbsp;</span><span style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU"> </span>
		<span style="font-size:12.0pt;
  font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;">
		Type</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">=</span><span style="font-size:12.0pt;
  font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;">C</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">(150), но в большинстве 
		случаев достаточно видеть начало строки, то можно установить </span>
		<span style="font-size:12.0pt;
  font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;">
		ShowType</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">=</span><span style="font-size:12.0pt;
  font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:&quot;Times New Roman&quot;">C</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU">(32).</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,&quot;serif&quot;;mso-fareast-font-family:
  &quot;Times New Roman&quot;;mso-ansi-language:RU"><o:p></o:p></span></p>
		</td>
	</tr>
	<tr>
		<td style="width:3%; padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<img src="../../IMAGES/pubfield.gif" width="16" height="16"></td>
		<td width="29%" style="width:29.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
<font face="Arial"><span lang="en-us"><span class="style2"><em>sColumnCaption</em></span></span></font></p>
		</td>
		<td width="71%" style="width:71.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU">
		необязательное
		строковое выражение, определяющее наименование-заголовок для колонки. </span></p>
		</td>
	</tr>
	<tr>
		<td style="width:3%; padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<img src="../../IMAGES/pubfield.gif" width="16" height="16"></td>
		<td width="29%" style="width:29.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
<font face="Arial"><span lang="en-us"><span class="style2"><em>sColumnECaption</em></span></span></font></p>
		</td>
		<td width="71%" style="width:71.0%;padding:3.75pt 3.75pt 3.75pt 3.75pt" class="style7">
		<p class="MsoNormal">
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU">
		необязательное
		строковое выражение, определяющее наименование-заголовок для колонки на 
		иностранном языке</span><span lang="RU" style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,&quot;serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU"><o:p></o:p></span></p>
		</td>
	</tr>
	<tr>
    <td class="style3" style="width: 2%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style3">
<em>
<font face="Arial"><span lang="en-us"><span class="style2">sActivation</span></span></font></em></td>
    <td width="71%" class="style3">
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	необязательное 
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU">
		строковое выражение</span>, задает формулу активации колонки.&nbsp; Если 
	формула активации пропущена, то колонка всегда видна. </span></td>
  </tr>
	<tr>
    <td class="style3" style="width: 2%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style3">
<font face="Arial"><span lang="en-us"><span class="style2">
<em>sCalculation</em></span></span></font></td>
    <td width="71%" class="style3">
	<span lang="RU" style="font-size: 12.0pt; line-height: 115%; font-family: &quot;Arial&quot;,&quot;sans-serif&quot;; mso-fareast-font-family: &quot;Times New Roman&quot;; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA">
	необязательное
		<span lang="RU" style="font-size:12.0pt;font-family:&quot;Arial&quot;,&quot;sans-serif&quot;;
  mso-fareast-font-family:&quot;Times New Roman&quot;;mso-ansi-language:RU">
		строковое выражение</span>, задающее формулу расчета&nbsp; колонки. </span></td>
  </tr>
</TBODY>
</table>

</body>

</html>