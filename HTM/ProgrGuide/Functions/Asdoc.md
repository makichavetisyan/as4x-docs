﻿<html>
<head>
<title>Документ</title>

 <style type="text/css">
        body {
              font-family: Arial;
             }
        th, td {
                padding: 5px;
               }
     table tr{
            border: 1px solid black;
           }
  </style>



</head>

<body>

<h1 style="font-size: 18px;">Объект документ</h1>

<p>Документ должен быть <a
href="../Defs/doc.html">заранее описан</a> и загружен в систему. Создание и 
доступ к экземплярам документов обеспечивается через функции <a href="Functions/DocumentsCirculation/CreateDoc.html">
CreateDoc</a>,
<a href="Functions/DocumentsCirculation/DocFromScreen.html">DocFromScreen</a>,
<a href="Functions/DocumentsCirculation/LoadDoc.html">LoadDoc</a>, <a href="Functions/DocumentsCirculation/CopyDoc.html">
CopyDoc</a>,
<a href="Functions/DocumentsCirculation/LoadDocFromFolder.html">LoadDocFromFolder</a>.</p>

<table cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" style="width: 29%">Свойства</td>
    <td class="label" style="width: 71%">Описание</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Attachments.html">
	Attachments</a></td>
    <td class="label" style="width: 71%">Возвращает 
	коллекцию файловых дополнений, прикрепленных к данному документу.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Body.html">
	Body</a></td>
    <td class="label" style="width: 71%">Возвращает тело документа DOCS таблицы без гридов.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/BodyG.html">
	BodyG</a></td>
    <td class="label" style="width: 71%">Возвращает тело гридов документа таблицы DOCSG.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Caption.html">
	Caption</a></td>
    <td class="label" style="width: 71%">Возвращает 
	заголовок-наименование документа из его описания.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/CheckValue.html">
	CheckValue</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает режим проверки типа реквизита документа при присвоении 
	значения.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ChangeRequest.html">
	ChangeRequest</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает объект типа <i>ChangeRequest</i>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/ClickDropDownEvent.html">ClickDropDownEvent</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает признак генерации системных событий <a href="../ScriptProcs/ClickDropDown.html">
	ClickDropDown</a> или <a
    href="../ScriptProcs/ClickDropDownGrid.html">ClickDropDownGrid</a>
    соответственно для указанного реквизита или грид-таблицы документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Control.html">
	Control</a></td>
    <td class="label" style="width: 71%">Возвращает ссылку 
	на осуществляющий ввод элемент управления.</td>
  	</tr>
	<tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ControlValue.html">
	ControlValue</a></td>
    <td class="label" style="width: 71%">Устанавливает 
        значение для элемента управления, осуществляющий ввод</td>
  	</tr>
	<tr>
    <td class="label" style="width: 29%">
	<a href="ASDOC/CreateDialog.html">CreateDialog</a></td>
    <td class="label" style="width: 71%">Возвращает диалог 
	в который входят все видимые реквизиты документа.</td>
  	</tr>
	<tr>
    <td class="label" style="width: 29%">
	<a href="ASDOC/CreationDate.html">CreationDate</a></td>
    <td class="label" style="width: 71%">Возвращает дату 
	создания документа.</td>
  	</tr>
	<tr>
    <td class="style1" style="width: 29%">
	<a href="ASDOC/CreatorSUID.html">CreatorSUID</a></td>
    <td class="style1" style="width: 71%">Возвращает 
	идентификатор создателя документа.</td>
  	</tr>
    <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/CustomFlag.html">CustomFlag</a></td>
    <td class="label" style="width: 71%">Возвращает или устанавливает свойство пользовательского флага.</td>
    </tr>
    <tr>
    <td class="label" style="width: 29%">
        <a href="ASDOC/Deleting.html">Deleting</a></td>
    <td class="label" style="width: 71%">

<p>Возвращает признак того, что документ находится в процессе 
    удаления.</p>

	  </td>
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/DocType.html">
	DocType</a></td>
    <td class="label" style="width: 71%"><p>Возвращает тип 
	документа (т.е. его идентификатор) из описания.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ECaption.html">
	ECaption</a></td>
    <td class="label" style="width: 71%"><p>Возвращает 
	заголовок-наименование документа на иностранном языке из его описания.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ExistsGrid.html">
	ExistsGrid</a></td>
    <td class="label" style="width: 71%"><p>Возвращает 
	наличие грид-таблицы в описании документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ExistsInDB.html">
    ExistsInDB</a></td>
    <td class="label" style="width: 71%"><p>
    Возвращает признак сохранения в базе данных.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ExistsRekv.html">
    ExistsRekv</a></td>
    <td class="label" style="width: 71%"><p>
    Возвращает наличие реквизита в описании документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><font
    face="Arial"><a href="ASDOC/ExistsSub.html">ExistsSub</a></td>
    <td class="label" style="width: 71%">Возвращает 
	признак наличии данной процедуры в описании документа. </td>
  </tr>
    <tr>
    <td class="label" style="width: 29%"><font
    face="Arial"><a href="ASDOC/FixedValue.html">FixedValue</a></td>
    <td class="label" style="width: 71%">Возвращает или устанавливает признак фиксации значения 
    реквизита документа. </td>
    </tr>
  <tr>
    <td class="label" style="width: 29%">
	<a href="ASDOC/FormActivated.html">FormActivated</a></td>
    <td class="label" style="width: 71%">Возвращает 
	признак активности UI документа</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%">
	<a href="ASDOC/Formatted.html">Formatted</a></td>
    <td class="label" style="width: 71%">Возвращает 
	форматированное представление значения реквизита. </td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/GetNextTrans.html">GetNextTrans</a></td>
    <td class="label" style="width: 71%">Возвращает новый 
	логический номер очередной транзакции. </td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Grid.html">
	Grid</a></td>
    <td class="label" style="width: 71%"><p>Возвращает 
	ссылку на объект грид-таблицу в документе. </td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Image.html">
	Image</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает значение реквизита-изображения документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%">
	<a href="ASDOC/IsHidden.html">IsHidden</a></td>
    <td class="label" style="width: 71%">Возвращает 
	признак невидимости реквизита в описании документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%">
	<a href="ASDOC/IsHiddenGrid.html">IsHiddenGrid</a></td>
    <td class="label" style="width: 71%">Возвращает 
	признак невидимости грид-таблицы документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ISN.html">
	ISN</a></td>
    <td class="label" style="width: 71%"><p class="label">
	Возвращает внутрисистемный уникальный идентификатор документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/IsNew.html">
	IsNew</a></td>
    <td class="label" style="width: 71%">Возвращает 
	признак нового документа или черновика.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/LastFixedState.html">LastFixedState</a></td>
    <td class="label" style="width: 71%">Возвращает 
	последнее зафиксированное в базе состояние документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/LogTransactions.html">LogTransactions</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает разрешение на автоматическую регистрацию в историю документа 
	записи о проведении проводок.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Memo.html">
	Memo</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает значение для данного реквизита <a
    href="../Defs/doc.html#Memo">Memo</a>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Mode.html">
	Mode</a></td>
    <td class="label" style="width: 71%">Возвращает режим 
	показа документа.</td>
  </tr>
    <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/NextTrans.html">NextTrans</a></td>
    <td class="label" style="width: 71%">Возвращает номер очередной транзакции, 
    которая не увеличивается на единицу при каждом его запросе.
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/NestedTransactions.html">NestedTransactions</a></td>
    <td class="label" style="width: 71%">Возвращает 
	количество элементов массива, не прошедших вложенную транзакцию, и объект 
	типа <a
    href="AsRepViewer.html">отчет</a>, содержащий сообщения об ошибках.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ParentISN.html">
	ParentISN</a></td>
    <td class="label" style="width: 71%">Возвращает 
	внутрисистемный уникальный идентификатор (ISN) родительского документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Parents.html">
	Parents</a></td>
    <td class="label" style="width: 71%">Возвращает 
	коллекцию ISN-ов родительских документов для текущего.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Properties.html">
	Properties</a></td>
    <td class="label" style="width: 71%">Возвращает ссылку 
	на объект Dictionary языка SaxBasic.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ReadOnly.html">
	ReadOnly</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает статус режима редактирования реквизита документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ReadOnlyAttachments.html">
	ReadOnlyAttachments</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает статус режима редактирования файловых дополнений прикрепленных 
	к данному документу.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ReadOnlyIm.html">
	ReadOnlyIm</a></td>
    <td class="label" style="width: 71%"><p class="label">
	Возвращает или устанавливает статус режима редактирования 
	реквизита-изображения документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/ReadOnlyMemo.html">ReadOnlyMemo</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает статус режима редактирования реквизита-мемо документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Rekv.html">
	Rekv</a></td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает значение реквизита документа.</td>
  </tr>
    <tr>
    <td class="label" style="width: 29%"><font
    face="Arial"><a href="ASDOC/SetFactsCreatorState.html">SetFactsCreatorState</a><br />
        </td>
    <td class="label" style="width: 71%">Возвращает или 
	устанавливает состояние определяющее идентификатор пользователя-автора 
	проводок документа</td>
    </tr>
    <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/SetGridColsClickDropDownEvent.html">
	    SetGridColsClickDropDownEvent</a></td>
    <td class="label" style="width: 71%">Возвращает или устанавливает 
        признак генерации системного события&nbsp;
        <a href="../../ScriptProcs/ClickDropDownGrid.html">ClickDropDownGrid</a> 
        соответственно для указанных столбцов<strong> </strong>грид-таблицы документа.</td>
    </tr>
    <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/SetRekvsReadOnly.html">
	    SetRekvsReadOnly</a></td>
    <td class="label" style="width: 71%">Возвращает или устанавливает статус 
        режима редактирования набора реквизитов документа.</td>
    </tr>
    <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/SetRekvsClickDropDownEvent.html">
	    SetRekvsClickDropDownEvent</a></td>
    <td class="label" style="width: 71%">Возвращает или устанавливает 
        признак генерации системного события
        <a href="../../ScriptProcs/ClickDropDown.html">ClickDropDown</a>&nbsp; соответственно 
        для указанных реквизитов документа.</td>
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/State.html">
	State</a></td>
    <td class="label" style="width: 71%"><p class="label">
	Возвращает или устанавливает состояние документа.</td>
  </tr>
  <tr>
    <td class="auto-style4" style="width: 29%">
    <a href="ASDOC/StoredFacts.html">StoredFacts</a></td>
    <td class="auto-style4" style="width: 71%">Возвращает 
	коллекцию сохраненных ïðîâîäоê.</td>
  </tr>
    <tr>
    <td class="label" style="width: 29%">
    <a href="ASDOC/Structure.html">Structure</a></td>
    <td class="label" style="width: 71%">Возвращает ссылку 
	на объект типа структура документа.</td>
    </tr>
  <tr>
    <td class="label" style="width: 29%">
    <a href="ASDOC/VisualFormAvailable.html">VisualFormAvailable</a></td>
    <td class="label" style="width: 71%">

<p>Возвращает признак того, что визуальная форма документа доступна.</p>

	  </td>
  </tr>
</table>

<p>&nbsp;</p>

<table cols="2" frame="below" rules="rows">
  <tr vAlign="top">
    <td class="label" style="width: 29%"><strong>Методы</strong></td>
    <td class="label" style="width: 71%"><strong>Описание</strong></td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Archived.html">Archived</a></td>
    <td class="label" style="width: 71%">Проверяет архивирован ли документ или нет.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ChangeISN.html">
	ChangeISN</a></td>
    <td class="label" style="width: 71%">Находит новый 
	свободный внутрисистемный уникальный идентификатор для заданного документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/CheckAndStore.html">CheckAndStore</a></td>
    <td class="label" style="width: 71%">Производит 
	необходимые проверки и запоминает документ в заданном режиме.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Doc_CloseForm.html">CloseForm</a></td>
    <td class="label" style="width: 71%">Закрывает форму документа.</td>
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Confirm.html">Confirm</a></td>
    <td class="label" style="width: 71%"><span class="auto-style1">Визирует документ</span>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/CreateFactsUsingDocCreator.html">CreateFactsUsingDocCreator</a></td>
    <td class="label" style="width: 71%"><span class="auto-style1">Назначает создателя документа автором будущих проводок</span>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ExistsButton.html">ExistsButton</a></td>
    <td class="label" style="width: 71%"><span class="auto-style1">Проверяет наличие кнопки в описании документа</span>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ExistsPage.html">ExistsPage</a></td>
    <td class="label" style="width: 71%"><span class="auto-style1">Проверяет наличие страницы в описании документа</span>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ExportToExcel.html">ExportToExcel</a></td>
    <td class="label" style="width: 71%"><span class="auto-style1">Экспортирует содержимое документа в Excel</span>.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Flush.html">
	Flush</a></td>
    <td class="label" style="width: 71%">Oсуществляет 
	сброс тела документа в БД.</td>
  </tr>
    <tr>
    <td class="auto-style2" style="width: 29%"><a href="ASDOC/GetDialogFromPage.html">
	GetDialogFromPage</a></td>
    <td class="auto-style2" style="width: 71%">Добавляет диалог с реквизитами 
        заданных страниц документа.</td>
    </tr>
    <tr>
    <td class="auto-style2" style="width: 29%"><a href="ASDOC/GetDialogFromRekvs.html">
	GetDialogFromRekvs</a></td>
    <td class="auto-style2" style="width: 71%">Добавляет диалог с заданными 
        реквизитами документа.</td>
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/HiDelete.html">
	HiDelete</a></td>
    <td class="label" style="width: 71%">Удаляет все 
	проводки, документ-основанием которых является загруженный&nbsp; документ.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/HiParDelete.html">
	HiParDelete</a></td>
    <td class="label" style="width: 71%">Удаляет те 
	параметры из таблицы <a href="../Database/HiPar.html">HIPAR</a>, 
	документ-основанием которых является загруженный документ.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/LockControls.html">LockControls</a></td>
    <td class="label" style="width: 71%">Устанавливает для 
	всех реквизитов документа режим только для чтения</td>
  </tr>
  <tr>
    <td class="style1" style="width: 29%"><a href="ASDOC/PrintToFile.html">PrintToFile</a></td>
    <td class="style1" style="width: 71%">Сохраняет 
	печатную форму документа в файле.</td>
  </tr>
  <tr>
    <td class="auto-style3" style="width: 29%"><a href="ASDOC/ReFolder.html">
	ReFolder</a></td>
    <td class="auto-style3" style="width: 71%">Осуществляет переиндексацию документов в папках.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Refresh.html">
	Refresh</a></td>
    <td class="label" style="width: 71%">Обновляет 
	значение реквизита на форме документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/RefreshIm.html">
	RefreshIm</a></td>
    <td class="label" style="width: 71%">Обновляет 
	значение реквизита-изображения в форме документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/RefreshRekvs.html">
	RefreshRekvs</a></td>
    <td class="label" style="width: 71%">Обновляет 
	значение реквизитов на форме документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/RefreshTS.html">
	RefreshTS</a></td>
    <td class="label" style="width: 71%">Обновляет отметку последнего изменения документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Refuse.html">
	Refuse</a></td>
    <td class="label" style="width: 71%">Отклоняет визирование документа.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a
    href="ASDOC/RegistrFunction.html">RegistrFunction</a></td>
    <td class="label" style="width: 71%">Добавляет в 
	контекстное меню вызов пользовательской функции.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/RegistrNode.html">
	RegistrNode</a></td>
    <td class="label" style="width: 71%">Добавляет узел в 
	дерево вызовов пользовательских функций.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%">
    <a href="ASDOC/ReloadParents.html">ReloadParents</a></td>
    <td class="label" style="width: 71%">Перезагружает 
	коллекцию родителей документа. </td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Run.html">
	Run</a></td>
    <td class="label" style="width: 71%">Вызывает 
	скриптовую процедуру или функцию, описанную в документе.</td>
  </tr>
    <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/RunEx_Doc.html">
	RunEx</a></td>
    <td class="label" style="width: 71%">Вызывает 
	скриптовую процедуру или функцию, описанную в документе, с учетом возврата значений 
        ссылочных параметров(<em><strong>ByRef</strong></em>).</td>
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/SendMessage.html">
	SendMessage</a></td>
    <td class="label" style="width: 71%">Посылает 
	сообщение от текущего документа к документу-получателю с указанным ISN.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/SetFocus.html">
	SetFocus</a></td>
    <td class="label" style="width: 71%">Устанавливает 
	фокус на указанный реквизит документа, после чего он становится текущим 
	активным реквизитом документа. </td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Show.html">
	Show</a></td>
    <td class="label" style="width: 71%">Активизирует 
	документ выводя его на экран в указанном режиме.</td>
  </tr>
    <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/ShowModal.html">
	ShowModal</a></td>
    <td class="label" style="width: 71%">Показывает окно документа в 
    режиме Modal.</td>
    </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/Store.html">
	Store</a></td>
    <td class="label" style="width: 71%"><p class="label">
	Производит необходимые проверки и запоминает документ</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/StoreFact.html">
	StoreFact</a></td>
    <td class="label" style="width: 71%"><p class="label">
	Сохраняет проводку.</td>
  </tr>
  <tr>
    <td class="auto-style2" style="width: 29%"><a href="ASDOC/StoreInContract.html">
	StoreInContract</a></td>
    <td class="auto-style2" style="width: 71%">Сохраняет объект договора.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/StoreInFolder.html">
    face="Arial">StoreInFolder</a></td>
    <td class="label" style="width: 71%">Сохраняет элемент 
	папки.</td>
  </tr>
  <tr>
    <td class="auto-style2" style="width: 29%"><a href="ASDOC/StoreInTree.html">
	StoreInTree</a></td>
    <td class="auto-style2" style="width: 71%">Сохраняет элемент 
	дерева.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/UnLockControls.html">
	UnLockControls</a></td>
    <td class="label" style="width: 71%">Снимает со всех реквизитов документа режим только для чтения.</td>
  </tr>
  <tr>
    <td class="label" style="width: 29%"><a href="ASDOC/WriteLog.html">
	WriteLog</a></td>
    <td class="label" style="width: 71%">Добавляет новую 
	запись в журнал регистрации операций над документом.</td>
  </tr>
</table>
</body>
</html>