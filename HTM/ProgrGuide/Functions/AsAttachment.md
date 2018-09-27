﻿<html>
<head>
<title>Data</title>
</head>

<body>

<h1><font size="4" face="Arial">Объект файловое дополнение</font></h1>

<p><font face="Arial">Файловое дополнение используется для 
прикрепления файла к документу, если в определении данного документа задан 
признак приклепления. К каждому документу могут быть подсоединены несколько 
файловых дополнений, являющихся элементами <a href="AsAttachmentCollection.html">
коллекции файловых дополнений</a> данного документа. Файловые дополнения 
хранятся в таблице <a href="../Database/DocsAttach.html">DOCSATTACH</a>. С каждым 
файловым дополнением ассоциируется версия, дата последнего изменения, 
пользователь, сделавший эти изменения и компьютер с которого были сделанны 
последние изменения.</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Свойства</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><a href="AsAttachment/Comment.html">
	Comment</a></font></td>
    <td width="71%"><font face="Arial">Возвращает или устанавливает 
	комментарий для файлового дополнения.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><a href="AsAttachment/FileName.html">
	FileName</a></font></td>
    <td width="71%"><font face="Arial">Возвращает имя файлового 
	дополнения.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><a href="AsAttachment/FullFileName.html">
	FullFileName</a></font></td>
    <td width="71%">

<p><font face="Arial">Возвращает полный путь файлового дополнения на 
данном компьютере.</font></p>

    </td>
  </tr>
</table>

<p>&nbsp;</p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><strong>Методы</strong></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><a href="AsAttachment/GetLatestVersion.html">
	GetLatestVersion</a></font></td>
    <td width="71%"><font face="Arial">Загружает новую версию 
	файлового дополнения с сервера. </font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><a href="AsAttachment/OpenFile.html">
	OpenFile</a></font></td>
    <td width="71%"><font face="Arial">Открывает локальную копию 
	файлового дополнения.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><a href="AsAttachment/StoreInServer.html">
	StoreInServer</a></font></td>
    <td width="71%"><font face="Arial">Сохраняет локальную копию 
	файлового дополнения на сервере.</font></td>
  </tr>
</table>
</body>
</html>