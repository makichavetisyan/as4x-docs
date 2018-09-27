﻿<html>
<head>
<title>OnEachRow</title>
</head>

<body>

<p><font face="Arial"><strong><font size="3">Пример события </font>
OnEachRow</strong></font></p>

<p><font face="Arial">Ниже приведен фрагмент из <a
href="../Defs/Data.html">описания источника данных</a> с примером обработчика 
события <strong>OnEachRow</strong>, в котором для виртуальной колонки Simbol, 
определяется значение скриптовой глобальной переменной KasSim, которая и 
заполняется в колонку Simbol.</font></p>

<p><font face="Arial">.....<br>
COLUMN {NAME = KASSIMV; CAPTION=#Simbol; TYPE=C(#LenKasSimv); <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>
SOURCE=1</strong>; FIELD=<strong>Simbol</strong>; DESCRIPTION=#KasSimv;}; <br>
PARAM {Description =#StartDate ;TYPE=DATE;};<br>
PARAM {Description =#EndDate ;TYPE=DATE;};<br>
PARAM {Description =#Acc ; TYPE=C(17);};<br>
SCRIPT {<br>
Dim <strong>KasSim</strong><br>
<br>
Function <strong>Simbol</strong>()<br>
&nbsp;&nbsp;&nbsp; Simbol=<strong>KasSim</strong><br>
End Function<br>
<br>
Sub <strong>OnEachrow</strong>()<br>
&nbsp;&nbsp; lngOBJECT = DS(&quot;fISN&quot;)<br>
&nbsp;&nbsp; Set xDoc = <a href="../Functions/Functions/DocumentsCirculation/LoadDoc.html">
LoadDoc</a>(lngOBJECT) <br>
&nbsp;&nbsp; If xDoc.<a href="../Functions/ASDOC/ExistsRekv.html">ExistsRekv</a>(&quot;KASSIMV&quot;) 
then <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>KasSim</strong> = xDoc(&quot;KASSIMV&quot;)<br>
&nbsp;&nbsp; Else<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>KasSim</strong>=&quot;?&quot;<br>
&nbsp;&nbsp; End If&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
End Sub&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
};<br>
</font></p>
</body>
</html>