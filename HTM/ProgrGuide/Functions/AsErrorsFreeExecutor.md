﻿<html>
<head>
<title>Обновитель экрана</title>
<style type="text/css">
.auto-style1 {
	font-family: Arial;
	color: #0000FF;
	text-decoration: underline;
}
.auto-style2 {
	font-family: Arial;
	font-size: medium;
}
.auto-style3 {
	font-family: Arial;
}
</style>
</head>

<body>

<h1><font size="4" face="Arial">Объект </font><span class="auto-style2">
AsErrorsFreeExecutor</span></h1>

<p><font face="Arial">Класс <span class="auto-style3">AsErrorsFreeExecutor 
предназначен для </span>для исполнения скриптовой процедуры в режиме, когда 
возникавшие ошибки не передаются обработчику, а сохраняются в отчете.<span class="auto-style3">
</span>Создание объекта AsErrorsFreeExecutor 
обеспечивается через функцию
<a href="Functions/CreateErrorsFreeExecutor.html">CreateErrorsFreeExecutor</a>.</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Свойства</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
    <tr>
    <td class="auto-style1" width="29%">
	    <a href="AsErrorsFreeExecutor/ErrorsCount.html">ErrorsCount</a></td>
    <td class="label" width="71%"><font face="Arial">Возвращает количество ошибок, 
        возникающих во время исполнения скриптовой процедуры.</font></td>
  </tr>
    <tr>
    <td class="auto-style1" width="29%">
	<a href="AsErrorsFreeExecutor/OnErrorRollBack.html">OnErrorRollBack</a></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или устанавливает признак 
	<span lang="ru">отката транзакции при ошибке</span>.</font></td>
    </tr>
    <tr>
    <td class="auto-style1" width="29%">
	<a href="AsErrorsFreeExecutor/Properties.html">Properties</a></td>
    <td class="label" width="71%">

<p class="label"><font face="Arial">Возвращает ссылку на объект типа Dictionary. 
Данное свойство применяется для хранения некоторых значений для последующей их 
обработки. </font></p>
		</td>
    </tr>
  <tr>
    <td class="label" width="29%"><font face="Arial"><a href="AsErrorsFreeExecutor/RepViewer.html">
	RepViewer</a></font></td>
    <td class="label" width="71%"><font face="Arial">Возвращает или 
	устанавливает объект отчет в котором сохраняются все сообщения об ошибках 
	возникавшие во время исполнения скриптовой процедуры.</font></td>
  </tr>
  </table>

<p>&nbsp;</p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Методы</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><a href="AsErrorsFreeExecutor/Run_Err.html"><font face="Arial">
	Run</font></a></td>
    <td width="71%"><font face="Arial">Выполняет скриптовую процедуру. 
        </font></td>
  </tr>
    <tr>
    <td width="29%"><a href="AsErrorsFreeExecutor/RunEx_Err.html"><font face="Arial">
	RunEx</font></a></td>
    <td width="71%"><font face="Arial">Выполняет скриптовую процедуру, с учетом возврата 
        значений ссылочных параметров(<strong><em>Byref</em></strong>).</font></td>
    </tr>
  <tr>
    <td width="29%" class="auto-style1" style="height: 32px">
	<a href="AsErrorsFreeExecutor/SetErrSubParams.html">SetErrSubParams</a></td>
    <td width="71%" style="height: 32px"><font face="Arial">Устанавливает 
	параметры для процедуры вывода дополнительных сообщений об ошибке. Если 
	параметры не устанавливаются, то процедура вызывается с параметрами, что 
	были переданы методу <span lang="en-us">Run.</span></font></td>
  </tr>
</table>
</body>
</html>