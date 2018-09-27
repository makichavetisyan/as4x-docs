﻿<html>
<head>
<title>Системное событие BeforeImport</title>
<style type="text/css">
.auto-style1 {
	text-align: left;
}
</style>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие BeforeImport<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <u>Пример&nbsp;</u> <a
href="../Defs/doc.html">Применяется к</a></font></p>

<p class="auto-style1"><font face="Arial">Происходит при импорте 
документа.&nbsp;Если функция возвращает True, то документ сохраняется в системе 
и регистрируется как импортированный. Если возвращается False, то документ не 
сохраняется в системе, но транзакция в рамках которой импортирвался документ 
успешно заканчивается. Режим с возвратом False позволяет во время обработки 
BeforeImport сохранить в системе документ отличный по типу от импортируемого.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Public Function <strong>BeforeImport</strong>() as Boolean<br>
<em>&nbsp;&nbsp;&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p class="label">&nbsp;</p>

</body>
</html>