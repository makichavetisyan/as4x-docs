﻿<html>
<head>
<title>Таблица DOCS</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица DOCS</font></h1>

<p><font face="Arial">Таблицa хранения документов.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Тип 
	данных</strong></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Null</strong></font></td>
    <td class="label" width="40%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fISN</font></td>
    <td width="20%"><font face="Arial">int </font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор документа</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fNAME</font></td>
    <td width="20%"><font face="Arial">char (8)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор типа документа</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fSTATE</font></td>
    <td width="20%"><font face="Arial">smallint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">состояние документа. При 
	создании документа он находится в состоянии 0, а после его сохранения 
	переходит в состояние 1. Дальнейшие наращивания состояния документа 
	происходят согласно поведению документа. Ядро системы влияет на текущее 
	состояние документа в следующих случаях: при визировании документа его 
	состояние автоматически увеличивается на 1, а при отказе визирования - 
	увеличивается на 2. Изменение <a
    href="Folders.html">статуса</a> завизированного документа <a
    href="Folders.html">в папке</a> производится из скрипта.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fNEXTTRANS</font></td>
    <td width="20%"><font face="Arial">int</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">номер очередной транзакции для 
	данного документа.</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fTS</font></td>
    <td width="20%"><font face="Arial">timestamp</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">отметка времени последнего 
	изменения, применяется для оптимистической блокировки</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fBODY</font></td>
    <td width="20%"><font face="Arial">varchar (4000)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">тело документа, где хранятся 
	значения реквизитов</font></td>
  </tr>
  <tr>
    <td width="20%">fCREATIONDATE</td>
    <td width="20%">datetime</td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">дата создания документа</font></td>
  </tr>
  <tr>
    <td width="20%">fCREATORSUID</td>
    <td width="20%"><font face="Arial">smallint</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор пользователя, 
	создавшего документ</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><font face="Arial"><b><br>
Индекс</b></font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="33%"><font face="Arial"><b>Имя индекса</b></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Тип </strong></font></td>
    <td class="label" width="33%"><font face="Arial"><strong>Имя 
	столбцов</strong></font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iDOCS1</font></td>
    <td width="33%"><font face="Arial">UNIQUE,&nbsp; CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fISN</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iDOCS2</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fNAME</font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
<br>
Примечание</b></font></p>

<p class="label"><font face="Arial"><a href="database_scheme.html">См. 
также</a></font></p>
</body>
</html>