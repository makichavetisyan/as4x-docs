﻿<html>
<head>
<title>DefaultComment</title>
</head>

<body>

<p><font face="Arial"><strong><font size="3">Пример события 
SetPrintWidth</font></strong></font></p>

<p><font face="Arial">Из <a href="../Defs/doc.html">описания документа</a> 
приведен пример обработчика события
<strong>SetPrintWidth</strong>.<br>
</font></p>

<p><font face="Arial">Function <b>SetPrintWidth</b>()<br>
&nbsp;&nbsp;&nbsp; If Doc(&quot;CODE&quot;) = &quot;0&quot; Then <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SetPrintWidth = 89<br>
&nbsp;&nbsp;&nbsp; ElseIf Doc(&quot;CODE&quot;) = &quot;1&quot; and Doc(&quot;RepNum&quot;)=2 Then<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SetPrintWidth = 230<br>
&nbsp;&nbsp;&nbsp; Else<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SetPrintWidth = 230<br>
&nbsp;&nbsp;&nbsp; End If<br>
End Function</font></p>
</body>
</html>