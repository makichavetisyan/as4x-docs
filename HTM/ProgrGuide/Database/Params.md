﻿<html>
<head>
<title>Таблица PARAMS</title>
</head>

<body>

<h1><font size="4" face="Arial">Таблица PARAMS</font></h1>

<p><font face="Arial">Таблица параметров настроек и установок.<br>
</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="20%"><font face="Arial"><b>Поле</b></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Тип 
	данных</strong></font></td>
    <td class="label" width="20%"><font face="Arial"><strong>Null</strong></font></td>
    <td class="label" width="40%"><font face="Arial"><strong>Описание </strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fPARID</font></td>
    <td width="20%"><font face="Arial">char (20)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентификатор параметра
    </font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fTYPE</font></td>
    <td width="20%"><font face="Arial">char (1)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">&#39;0&#39; - не имеет разреза по 
	пользователям,&nbsp;</font>
      &#39;<font face="Arial">1&#39; - разрез по пользователям</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fVTYPE</font></td>
    <td width="20%"><font face="Arial">char (32)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">тип значения параметра</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fVALUE</font></td>
    <td width="20%"><font face="Arial">varchar (255)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">значение параметра </font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fDESC</font></td>
    <td width="20%"><font face="Arial">varchar (50)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">описание параметра </font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fPERM</font></td>
    <td width="20%"><font face="Arial">char (1)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">признак загрузки параметра из 
	ОЗУ или из таблицы</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fGROUP</font></td>
    <td width="20%"><font face="Arial">varchar (20)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">группа параметра из 
	одноуровневого бездокументного дерева-справочника PARGROUP</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fUPACCESS</font></td>
    <td width="20%"><font face="Arial">char (1)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">доступ на изменение параметра: <br>
    0 - меняет разработчик <br>
    1 - меняет администратор и разработчик<br>
    2 - меняет пользователь,<br>
    администратор и разработчик</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fEDESC</font></td>
    <td width="20%"><font face="Arial">varchar (50)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">описание параметра на 
	иностранном языке</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fMEMO</font></td>
    <td width="20%"><font face="Arial">varchar (7000)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial"><span lang="ru">длинное </span>
	описание<span lang="ru"> 
	ïàðàìåòðà</span></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fKIND</font></td>
    <td width="20%"><font face="Arial">char (10)</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial"><span lang="ru">группа 
	параметра</span></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fID</font></td>
    <td width="20%">IDENTITY</td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">идентичная колонка таблицы</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial">fCHANGEDATE</font></td>
    <td width="20%"><font face="Arial">smalldatetime</font></td>
    <td width="20%"><font face="Arial">NOT NULL</font></td>
    <td width="40%"><font face="Arial">дата последней модификации 
	параметра</font></td>
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
    <td width="33%"><font face="Arial">iPARAMS</font></td>
    <td width="33%"><font face="Arial">UNIQUE,CLUSTERED</font></td>
    <td width="33%"><font face="Arial">fPARID</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iPARAMS2</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fPERM, fPARID</font></td>
  </tr>
  <tr>
    <td width="33%"><font face="Arial">iPARAMS3</font></td>
    <td width="33%">&nbsp;</td>
    <td width="33%"><font face="Arial">fKIND </font></td>
  </tr>
</table>

<p class="label"><font face="Arial"><b><br>
Примечание</b></font></p>

<p class="label"><a href="database_scheme.html"><font face="Arial">См. 
также</font></a></p>
</body>
</html>