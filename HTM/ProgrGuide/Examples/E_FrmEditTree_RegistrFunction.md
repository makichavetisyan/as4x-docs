﻿<html>
<head>
<title>CurrentTree\RegistrFunction</title>
</head>

<body>

<p><font size="3" face="Arial"><strong>Пример метода RegistrFunction</strong></font></p>

<p><font face="Arial"><font size="3">Ниже приводится </font>обработчик 
системного события <a href="../ScriptProcs/FunctionsTree.html">Functions</a>
из описания дерева, где использован метод RegistrFunction, который в контекстное 
меню добавляет строчку &quot;Новое посещение&quot;. При ее вызове срабатывает процедура 
CreateSp, создающая новый экземпляр документа spasoper. Она срабатывает на 
рабочих местах трех типов NbAcc, NewDoc и Adm.</font></p>

<p><font face="Arial">Sub Functions()<br>
&nbsp;&nbsp; set xTree= <a href="../Functions/Functions/InterfaceManagment/CurrentTree.html">
CurrentTree</a><br>
&nbsp;&nbsp; xTree.<strong>RegistrFunction</strong> &quot;Новое посещение&quot;, 
&quot;CreateSp&quot;, &quot;NbAcc; NewDoc; Adm&quot;<br>
End Sub<br>
<br>
Sub CreateSp() <br>
&nbsp;&nbsp; Set tmpDoc = xProc.<a href="../Functions/Functions/DocumentsCirculation/CreateDoc.html">CreateDoc</a>(&quot;spasoper&quot;)<br>
&nbsp;&nbsp; tmpDoc(&quot;PartCode&quot;) = Doc(&quot;CODE&quot;)<br>
&nbsp;&nbsp; tmpDoc.<a href="../Functions/ASDOC/Show.html">Show</a> <br>
End Sub<br>
<br>
};<br>
};</font></p>
</body>
</html>