﻿<html>
<head>
<title>Grid AddRow &amp; Value Example</title>
</head>

<body>

<p><strong><font face="Arial"><font size="3">Пример </font>метода 
AddRow и свойства Value</font></strong></p>

<p><font face="Arial">Ниже приведен пример добавления строчки в 
грид-таблицу документа и присваивания его колонкам значений.</font></p>

<p><font face="Arial">Set tGrd=xDoc.<a href="../Functions/ASDOC/Grid.html">Grid</a>(&quot;TRACTS&quot;)
<br>
.....<br>
for ind=0 to cnt<br>
&nbsp;&nbsp; tGRD.<strong>Addrow</strong><br>
&nbsp;&nbsp; tGRD.<strong>Value</strong>(ind,&quot;DOCNUM&quot;)=vtrndoc(ind)<br>
&nbsp;&nbsp; tGRD.<strong>Value</strong>(ind,&quot;DATE&quot;)=vtrdate(ind)<br>
&nbsp;&nbsp; tGRD.<strong>Value</strong>(ind,&quot;SUMMA&quot;)=vtrsum(ind)<br>
Next <br>
</font></p>
</body>
</html>