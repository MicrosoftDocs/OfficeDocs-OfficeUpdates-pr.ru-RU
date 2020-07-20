---
title: Заметки о выпусках Полугодового канала (предварительной корпоративной версии) в 2020 г.
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel (Targeted) для подписки "Приложения Microsoft 365" в 2020 г. для ИТ-специалистов.
ms.openlocfilehash: 838721b3bd587a03ddce1bc68bd13c06ae2fdc37
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138745"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="5d734-103">Заметки о выпусках Полугодового канала (предварительной корпоративной версии) в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="5d734-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="5d734-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (предварительная корпоративная версия) в 2020 г. для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="5d734-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="5d734-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="5d734-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="5d734-106">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="5d734-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-july-14"></a><span data-ttu-id="5d734-107">Версия 2002: 14 июля</span><span class="sxs-lookup"><span data-stu-id="5d734-107">Version 2002: July 14</span></span>
<span data-ttu-id="5d734-108">*Версия 2002 (сборка 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="5d734-108">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="5d734-109">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-111">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5d734-112">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-112">Excel</span></span>

- <span data-ttu-id="5d734-113">Ускорение загрузки файлов, доступных в локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="5d734-113">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="5d734-114">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="5d734-114">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="5d734-115">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, поэтому закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="5d734-115">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="5d734-116">Исправлена проблема, при которой книга могла быть скрыта при щелчке гиперссылки на определенное место в уже открытой книге.</span><span class="sxs-lookup"><span data-stu-id="5d734-116">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="5d734-117">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="5d734-117">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="5d734-118">Повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="5d734-118">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="5d734-119">Устранена проблема, из-за которой имена принтеров могли повторяться в списке принтеров в диалоговом окне "Печать".</span><span class="sxs-lookup"><span data-stu-id="5d734-119">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="5d734-120">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="5d734-120">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="5d734-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-121">Outlook</span></span>

- <span data-ttu-id="5d734-122">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="5d734-122">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="5d734-123">Устранена проблема, при которой повторяющиеся встречи или собрания отображались с ошибкой во времени при приближении изменений в определении часового пояса.</span><span class="sxs-lookup"><span data-stu-id="5d734-123">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="5d734-124">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="5d734-124">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="5d734-125">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="5d734-125">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="5d734-126">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="5d734-126">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="5d734-127">Устранена проблема, из-за которой представители видели разные иерархии папок общих почтовых ящиков на разных компьютерах.</span><span class="sxs-lookup"><span data-stu-id="5d734-127">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="5d734-128">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="5d734-128">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="5d734-129">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="5d734-129">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="5d734-130">Устранена проблема, вызывавшая сбой после того, как две надстройки добавляли кнопку в одну и ту же группу ленты.</span><span class="sxs-lookup"><span data-stu-id="5d734-130">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="5d734-131">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения по адресам из личного списка рассылки.</span><span class="sxs-lookup"><span data-stu-id="5d734-131">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="5d734-132">Устранена проблема, из-за которой нельзя было добавить ссылки в сообщения электронной почты с правильным клиентским разрешением по умолчанию, если для этого разрешения был установлен параметр "все".</span><span class="sxs-lookup"><span data-stu-id="5d734-132">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="5d734-133">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="5d734-133">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="5d734-134">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-134">Word</span></span>

- <span data-ttu-id="5d734-135">Исправлена проблема с совместной работой над документом при включении политики FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="5d734-135">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="5d734-136">Устранена проблема, при которой функция экспресс-блоков Word не работала при добавлении переименованного поля подстановки.</span><span class="sxs-lookup"><span data-stu-id="5d734-136">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d734-137">Набор Office</span><span class="sxs-lookup"><span data-stu-id="5d734-137">Office Suite</span></span>

- <span data-ttu-id="5d734-138">Исправлена проблема, из-за которой при совместной работе над объемными файлами PowerPoint чрезмерно повышалась нагрузка на сеть и ЦП.</span><span class="sxs-lookup"><span data-stu-id="5d734-138">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="5d734-139">Мы бэкпортировали новую версию AppV51, чтобы исправить регрессию в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="5d734-139">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="5d734-140">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="5d734-140">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-june-09"></a><span data-ttu-id="5d734-142">Версия 2002: 9 июня</span><span class="sxs-lookup"><span data-stu-id="5d734-142">Version 2002: June 09</span></span>
<span data-ttu-id="5d734-143">*Версия 2002 (сборка 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="5d734-143">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="5d734-144">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-144">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-146">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-146">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5d734-147">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-147">Excel</span></span>

- <span data-ttu-id="5d734-148">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="5d734-148">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="5d734-149">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="5d734-149">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="5d734-150">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="5d734-150">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="5d734-151">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="5d734-151">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="5d734-152">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="5d734-152">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="5d734-153">Исправлена проблема, из-за которой знак @ в начале формулы считался неявным оператором пересечения.</span><span class="sxs-lookup"><span data-stu-id="5d734-153">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="5d734-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-154">Outlook</span></span>

- <span data-ttu-id="5d734-155">Позволяет присоединиться к собранию в Teams непосредственно через собственный клиент Teams.</span><span class="sxs-lookup"><span data-stu-id="5d734-155">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="5d734-156">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="5d734-156">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="5d734-157">Исправлена проблема, из-за которой пользователи, имеющие неправильный параметр эмуляции браузера, не могли завершить запрос на проверку подлинности Gmail.</span><span class="sxs-lookup"><span data-stu-id="5d734-157">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="5d734-158">Исправлена проблема пользователей Outlook, использующих серверные операционные системы, приводившая к ошибке "Состояние защиты от вирусов: Недействительно.</span><span class="sxs-lookup"><span data-stu-id="5d734-158">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="5d734-159">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены", несмотря на то, что антивирусная программа настроена правильно.</span><span class="sxs-lookup"><span data-stu-id="5d734-159">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="5d734-160">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-160">Word</span></span>

- <span data-ttu-id="5d734-161">Исправлена проблема, из-за которой выравнивание слова в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="5d734-161">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d734-162">Набор Office</span><span class="sxs-lookup"><span data-stu-id="5d734-162">Office Suite</span></span>

- <span data-ttu-id="5d734-163">Эта проблема устранена с помощью замены имен каналов в представлении Backstage на новые в разветвлении января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="5d734-163">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="5d734-164">Исправлена проблема, из-за которой устройства регулируемые политикой не могли вызвать API аудитории DMS.</span><span class="sxs-lookup"><span data-stu-id="5d734-164">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="5d734-165">Исправлена проблема, из-за которой при добавлении и удалении приложений в одной транзакции выполнялось неполное удаление.</span><span class="sxs-lookup"><span data-stu-id="5d734-165">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="5d734-166">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="5d734-166">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="5d734-167">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="5d734-167">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-may-12"></a><span data-ttu-id="5d734-169">Версия 2002: 12 мая</span><span class="sxs-lookup"><span data-stu-id="5d734-169">Version 2002: May 12</span></span>
<span data-ttu-id="5d734-170">*Версия 2002 (сборка 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="5d734-170">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="5d734-171">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-171">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-173">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-173">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="5d734-174">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-174">Excel</span></span>

- <span data-ttu-id="5d734-175">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="5d734-175">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="5d734-176">В некоторых случаях открытие CSV-файлов занимало больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="5d734-176">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="5d734-177">В ряде случаев приложение Excel аварийно завершало работу при переключении между книгами с разным масштабом.</span><span class="sxs-lookup"><span data-stu-id="5d734-177">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="5d734-178">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="5d734-178">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="5d734-179">Данные, скопированные из столбца и отфильтрованные по цвету, иногда не вставлялись должным образом.</span><span class="sxs-lookup"><span data-stu-id="5d734-179">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="5d734-180">Устранена проблема, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="5d734-180">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="5d734-181">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="5d734-181">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="5d734-182">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="5d734-182">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="5d734-183">При использовании Range.Value и Range.Value2 (VBA) формулы вводились как динамические массивы.</span><span class="sxs-lookup"><span data-stu-id="5d734-183">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="5d734-184">OneNote</span><span class="sxs-lookup"><span data-stu-id="5d734-184">OneNote</span></span>

- <span data-ttu-id="5d734-185">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="5d734-185">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="5d734-186">Отображает уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="5d734-186">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="5d734-187">Улучшена синхронизация и стабильность службы путем временного уменьшения количества и частоты синхронизации страниц журнала версий в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="5d734-187">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="5d734-188">Улучшена синхронизация и стабильность службы путем временного отключения корзины в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="5d734-188">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="5d734-189">Если пользователь пытается удалить данные, которые обычно отправляются в корзину, ему будет предложено сохранить или окончательно удалить их.</span><span class="sxs-lookup"><span data-stu-id="5d734-189">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="5d734-190">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="5d734-190">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="5d734-191">Улучшена синхронизация и стабильность службы путем временного откладывания загрузки внедренных файлов и изображений в записных книжках в Интернете, пока пользователь не перейдет на страницу в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="5d734-191">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="5d734-192">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="5d734-192">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="5d734-193">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="5d734-193">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="5d734-194">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="5d734-194">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="5d734-195">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="5d734-195">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="5d734-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-196">Outlook</span></span>

- <span data-ttu-id="5d734-197">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="5d734-197">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="5d734-198">Устранена проблема, приводившая в сбою при попытке открытия файлов MSG и OFT после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="5d734-198">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="5d734-199">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="5d734-199">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="5d734-200">Это обновление исправляет проблему, из-за которой в Microsoft Outlook не отображается текущая метка конфиденциальности при просмотре или создании сообщений.</span><span class="sxs-lookup"><span data-stu-id="5d734-200">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="5d734-201">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения в личный список рассылки.</span><span class="sxs-lookup"><span data-stu-id="5d734-201">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5d734-202">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-202">PowerPoint</span></span>

- <span data-ttu-id="5d734-203">Устранена проблема с ретрансляцией точного текста сообщений для пользователей, которые открывают копию файла с улучшенными примечаниями.</span><span class="sxs-lookup"><span data-stu-id="5d734-203">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="5d734-204">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-204">Word</span></span>

- <span data-ttu-id="5d734-205">Решена проблема, из-за которой приложения Access и Publisher могли загружаться неправильно в зависимости от того, какие языки установлены.</span><span class="sxs-lookup"><span data-stu-id="5d734-205">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="5d734-206">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="5d734-206">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="5d734-207">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="5d734-207">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d734-208">Набор Office</span><span class="sxs-lookup"><span data-stu-id="5d734-208">Office Suite</span></span>

- <span data-ttu-id="5d734-209">Это исправление устраняет блокирование сети приложением Project при кэшировании файла в клиенте.</span><span class="sxs-lookup"><span data-stu-id="5d734-209">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="5d734-210">Решена проблема, из-за которой внутренняя операция вызывала исключение при сбое вместо ведения журнала и продолжения работы.</span><span class="sxs-lookup"><span data-stu-id="5d734-210">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="5d734-211">Для затронутых пользователей будет отменен запрет на получение обновлений.</span><span class="sxs-lookup"><span data-stu-id="5d734-211">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="5d734-212">Это изменение обеспечит правильную работу функции "Контур эскиза" на ленте.</span><span class="sxs-lookup"><span data-stu-id="5d734-212">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="5d734-213">Исправлена проблема при открытии файлов из локальных расположений с определенными настройками прокси.</span><span class="sxs-lookup"><span data-stu-id="5d734-213">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="5d734-214">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="5d734-214">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="5d734-215">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="5d734-215">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="5d734-216">Это обновление устраняет проблему в Microsoft Word, из-за которой текст длиной более 255 символов, вставленный при применении метки конфиденциальности, впоследствии не удавалось идентифицировать и удалить путем изменения или удаления метки, если в рамках политики меток был применен колонтитул или подложка.</span><span class="sxs-lookup"><span data-stu-id="5d734-216">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="5d734-217">Исправлена проблема, благодаря чему устранены сбои во время сеансов передачи Office и повышена надежность работы пользователей.</span><span class="sxs-lookup"><span data-stu-id="5d734-217">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="5d734-218">Это исправление обновляет конечную точку URL-адреса конфигурации усиленной безопасности (ECS).</span><span class="sxs-lookup"><span data-stu-id="5d734-218">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="5d734-219">В результате вызова этой новой конечной точки повышается успешность получения данных из ECS.</span><span class="sxs-lookup"><span data-stu-id="5d734-219">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-april-14"></a><span data-ttu-id="5d734-221">Версия 2002: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="5d734-221">Version 2002: April 14</span></span>
<span data-ttu-id="5d734-222">*Версия 2002 (сборка 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="5d734-222">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="5d734-223">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-223">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="5d734-224">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="5d734-224">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5d734-225">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-225">Excel</span></span>

- <span data-ttu-id="5d734-226">**Введите формулу, которая возвращает несколько значений:** Быстро введите формулу, которая возвращает несколько значений, и они автоматически попадут в соседние ячейки.</span><span class="sxs-lookup"><span data-stu-id="5d734-226">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="5d734-227">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-227">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="5d734-228">**Шесть мощных функций:** Мы добавили шесть новых функций, чтобы увеличить ваши электронные таблицы: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE и RANDARRAY.</span><span class="sxs-lookup"><span data-stu-id="5d734-228">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="5d734-229">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-229">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="5d734-230">**Посмотрите налево, посмотрите направо ... XLOOKUP здесь!:** Ряд за строкой, найдите все, что вам нужно в таблице или диапазоне с XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="5d734-230">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="5d734-231">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-231">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-233">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-233">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5d734-234">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-234">Excel</span></span>

- <span data-ttu-id="5d734-235">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="5d734-235">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="5d734-236">В некоторых случаях при сохранении в виде CSV-файла Excel мог объединять все столбцы в один столбец.</span><span class="sxs-lookup"><span data-stu-id="5d734-236">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="5d734-237">Использование Range.ClearContents для диапазона в защищенном листе могло занимать больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="5d734-237">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="5d734-238">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="5d734-238">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="5d734-239">Макросы VBA, взаимодействующие с лентой, могут неожиданно запускаться со значением True, присвоенным параметру ScreenUpdating.</span><span class="sxs-lookup"><span data-stu-id="5d734-239">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="5d734-240">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении (заполнение вниз, заполнение в стороны), если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="5d734-240">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="5d734-241">В некоторых случаях в VBA не работал метод Application.Evaluate для определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="5d734-241">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="5d734-242">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="5d734-242">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="5d734-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-243">Outlook</span></span>

- <span data-ttu-id="5d734-244">Исправлена проблема, приводившая к неожиданному увеличению заголовка группы в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="5d734-244">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="5d734-245">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="5d734-245">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="5d734-246">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="5d734-246">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="5d734-247">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="5d734-247">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5d734-248">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-248">PowerPoint</span></span>

- <span data-ttu-id="5d734-249">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="5d734-249">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="5d734-250">Project</span><span class="sxs-lookup"><span data-stu-id="5d734-250">Project</span></span>

- <span data-ttu-id="5d734-251">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="5d734-251">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="5d734-252">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="5d734-252">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="5d734-253">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-253">Word</span></span>

- <span data-ttu-id="5d734-254">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="5d734-254">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="5d734-255">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="5d734-255">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="5d734-256">Исправлена проблема, из-за которой вставляемые горизонтальные линии не укорачиваются и не располагаются по центру.</span><span class="sxs-lookup"><span data-stu-id="5d734-256">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-10"></a><span data-ttu-id="5d734-258">Версия 2002: 10 марта</span><span class="sxs-lookup"><span data-stu-id="5d734-258">Version 2002: March 10</span></span>
<span data-ttu-id="5d734-259">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="5d734-259">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="5d734-260">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-260">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="5d734-262">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="5d734-262">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="5d734-263">Access</span><span class="sxs-lookup"><span data-stu-id="5d734-263">Access</span></span>

- <span data-ttu-id="5d734-264">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="5d734-264">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="5d734-265">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-265">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="5d734-266">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-266">Excel</span></span>

- <span data-ttu-id="5d734-267">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="5d734-267">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="5d734-268">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-268">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="5d734-269">\*\*Найдите то, что ищете: \*\*Ищите команды, людей, файлы, фотографии, веб-статьи и многое другое.</span><span class="sxs-lookup"><span data-stu-id="5d734-269">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="5d734-270">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-270">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="5d734-271">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей книге.</span><span class="sxs-lookup"><span data-stu-id="5d734-271">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="5d734-272">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-272">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="5d734-273">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="5d734-273">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="5d734-274">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="5d734-274">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="5d734-275">**Сосредоточьтесь на оставшихся задачах.** Пометьте примечания как разрешенные, чтобы свернуть их и сделать открытые элементы более заметными.</span><span class="sxs-lookup"><span data-stu-id="5d734-275">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="5d734-276">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="5d734-276">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="5d734-277">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-277">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="5d734-278">**Преобразование файлов для расширения специальных возможностей.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="5d734-278">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="5d734-279">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="5d734-279">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="5d734-280">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-280">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="5d734-281">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="5d734-281">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="5d734-282">**Получите статистику в своей книге:** Статистика рабочей книги предоставляет обзор содержимого рабочей книги, чтобы упростить ее обнаружение.</span><span class="sxs-lookup"><span data-stu-id="5d734-282">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="5d734-283">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="5d734-283">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="5d734-284">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="5d734-284">Find them at Insert > Icons.</span></span> [<span data-ttu-id="5d734-285">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-285">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="5d734-286">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-286">Outlook</span></span>

- <span data-ttu-id="5d734-287">**Подключение к сети LinkedIn с помощью Outlook.** Безопасное подключение к учетным записям LinkedIn с помощью учетных записей Майкрософт для просмотра сведений из профилей LinkedIn прямо на карточках контактов.</span><span class="sxs-lookup"><span data-stu-id="5d734-287">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="5d734-288">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-288">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="5d734-p120">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты. [Подробнее](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="5d734-p120">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="5d734-291">\*\*Меню "Вставка ссылки" в Outlook вставляет ссылку с разрешениями, определенными администратором клиента. \*\* При выборе из списка последних использованных ссылок в Outlook вставляется ссылка, которая была доступна только пользователям, имеющим разрешение на доступ к ней.</span><span class="sxs-lookup"><span data-stu-id="5d734-291">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="5d734-292">Из-за этого пользователи часто посылали друг другу письма с просьбой предоставить доступ к документу.</span><span class="sxs-lookup"><span data-stu-id="5d734-292">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="5d734-293">Мы обновили этот опыт, поэтому теперь ссылка вставляется с разрешением по умолчанию, установленным администратором клиента. Для MSIT это «организация может редактировать», поэтому все внутренние пользователи, получившие ссылку, которой поделились таким образом, смогут получить к ней доступ.</span><span class="sxs-lookup"><span data-stu-id="5d734-293">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="5d734-294">**Поиск с правописанием проблем или опечаток:** Outlook найдет то, что вы ищете, даже если ваше правописание не соответствует.</span><span class="sxs-lookup"><span data-stu-id="5d734-294">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="5d734-295">**Фишинговые письма легко обнаружить:** спам и фишинговые сообщения выглядят по-разному, поэтому вы можете легко их идентифицировать и удалить из папки «Входящие».</span><span class="sxs-lookup"><span data-stu-id="5d734-295">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="5d734-296">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="5d734-296">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="5d734-297">**Рисование.** Рисуйте поверх изображений или добавьте полотно, чтобы отправить свои идеи с помощью рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="5d734-297">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="5d734-298">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-298">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="5d734-299">\*\*Получайте релевантные сообщения в результатах поиска. \*\*Outlook анализирует условия поиска и отображает наиболее релевантные сообщения электронной почты в верхней части результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="5d734-299">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="5d734-300">Кроме того, все результаты будут отображаться в разделе "Лучшие результаты" с сортировкой по дате.</span><span class="sxs-lookup"><span data-stu-id="5d734-300">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="5d734-301">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-301">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="5d734-302">**Получение предложений по расположению.** Начните вводить текст в поле "Место" при планировании встреч и собраний, и Outlook предложит помещения, адреса и другие недавние места.</span><span class="sxs-lookup"><span data-stu-id="5d734-302">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="5d734-303">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-303">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="5d734-304">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="5d734-304">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="5d734-305">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-305">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="5d734-306">\*\*Просмотр сообщений в другой освещенности. \*\* Используйте кнопку "СОЛНЦЕ/ЛУНА" для переключения между светлым и темным фоном в области чтения.</span><span class="sxs-lookup"><span data-stu-id="5d734-306">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="5d734-307">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-307">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="5d734-308">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="5d734-308">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="5d734-309">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="5d734-309">Find them at Insert > Icons.</span></span> [<span data-ttu-id="5d734-310">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-310">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="5d734-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-311">PowerPoint</span></span>

- <span data-ttu-id="5d734-312">**Быстрое взаимодействие в реальном времени в PowerPoint:** Быстрое сотрудничество в реальном времени в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-312">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="5d734-313">**Новые средства проверки правописания.** Не переживайте из-за слов.</span><span class="sxs-lookup"><span data-stu-id="5d734-313">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="5d734-314">В PowerPoint теперь отображаются предложения в отношении грамматики и написания.</span><span class="sxs-lookup"><span data-stu-id="5d734-314">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="5d734-315">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-315">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="5d734-316">**Субтитры в реальном времени.** Слова докладчика автоматически отображаются на экране в виде субтитров или переводятся в субтитры на выбранном языке.</span><span class="sxs-lookup"><span data-stu-id="5d734-316">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="5d734-317">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-317">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="5d734-p130">**Вы вычисляете, мы форматируем.** Рукописные математические выражения преобразуются в стандартные знаки. Просто воспользуйтесь функцией "Рукописный фрагмент в математические символы" и выберите рукописные примечания для начала работы. [Подробнее](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="5d734-p130">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="5d734-321">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="5d734-321">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="5d734-322">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-322">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="5d734-323">**Поиск и исправление пропущенных названий слайдов:** Названия слайдов добавляют удар к вашей подаче и делают ваши слайды доступными для пользователей всех способностей.</span><span class="sxs-lookup"><span data-stu-id="5d734-323">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="5d734-324">С помощью средства проверки читаемости можно определить, где отсутствуют заголовки, и сразу же добавить их.</span><span class="sxs-lookup"><span data-stu-id="5d734-324">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="5d734-325">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-325">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="5d734-326">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей презентации.</span><span class="sxs-lookup"><span data-stu-id="5d734-326">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="5d734-327">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-327">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="5d734-328">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="5d734-328">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="5d734-329">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="5d734-329">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="5d734-330">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="5d734-330">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="5d734-331">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-331">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="5d734-332">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="5d734-332">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="5d734-333">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="5d734-333">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="5d734-334">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-334">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="5d734-335">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="5d734-335">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="5d734-336">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-336">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="5d734-337">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="5d734-337">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="5d734-338">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="5d734-338">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="5d734-339">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="5d734-339">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="5d734-340">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="5d734-340">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="5d734-341">**Зачем изобретать заново, если вы можете использовать повторно ?:** Экономьте время, повторно используя слайды, которые вы создали или которыми другие поделились с вами.</span><span class="sxs-lookup"><span data-stu-id="5d734-341">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="5d734-342">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-342">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="5d734-343">**Измените рукописные чернила на фигуры, текст или математику в PowerPoint для Office 365:** Перейдите от чернил произвольной формы к фигурам, тексту или математическому выражению Office за пару движений.</span><span class="sxs-lookup"><span data-stu-id="5d734-343">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="5d734-344">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-344">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="5d734-345">**Рукописный ввод для создания отличного слайда.** Преобразуйте рукописный ввод в стандартные фигуры и текст, а затем находите изящные идеи оформления слайдов в конструкторе PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="5d734-345">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="5d734-346">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-346">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="5d734-347">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="5d734-347">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="5d734-348">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="5d734-348">Find them at Insert > Icons.</span></span> [<span data-ttu-id="5d734-349">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-349">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="5d734-350">Visio</span><span class="sxs-lookup"><span data-stu-id="5d734-350">Visio</span></span>

- <span data-ttu-id="5d734-351">**В сценах преступления:** Используйте новые трафареты «Доказательства», «В помещении» и «На улице» в шаблоне «Расследование места преступления», чтобы детально воссоздать места преступления.</span><span class="sxs-lookup"><span data-stu-id="5d734-351">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="5d734-352">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="5d734-352">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="5d734-353">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-353">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="5d734-354">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-354">Word</span></span>

- <span data-ttu-id="5d734-355">**Редактор для резюме присоединяется к LinkedIn Resume Assistant:** редактор для резюме предлагает выбор грамматических и стилевых проверок, специально предназначенных для резюме, чтобы сделать ваше письмо более точным и профессиональным.</span><span class="sxs-lookup"><span data-stu-id="5d734-355">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="5d734-356">**Исправление проблемы с повреждением документа, возникавшей при объединении 3D объектов.** Исправлена проблема с повреждением документа, возникавшая при объединении 3D объектов.</span><span class="sxs-lookup"><span data-stu-id="5d734-356">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="5d734-357">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="5d734-357">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="5d734-358">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-358">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="5d734-359">**Сотрудничайте в живом цвете:** комментарии и изменения имеют цветовую кодировку от участника, поэтому легко увидеть, кто есть кто среди ваших соавторов.</span><span class="sxs-lookup"><span data-stu-id="5d734-359">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="5d734-360">**Совместное редактирование документов с поддержкой макросов:** сохраняйте файлы документов в OneDrive для бизнеса и редактируйте их вместе с соавторами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="5d734-360">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="5d734-361">**Улучшенные возможности совместного редактирования**. Улучшено быстродействие Word при совместном редактировании в документах с отслеживанием исправлений.</span><span class="sxs-lookup"><span data-stu-id="5d734-361">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="5d734-362">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="5d734-362">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="5d734-363">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="5d734-363">Find them at Insert > Icons.</span></span> [<span data-ttu-id="5d734-364">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-364">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="5d734-365">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="5d734-365">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="5d734-366">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своем документе.</span><span class="sxs-lookup"><span data-stu-id="5d734-366">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="5d734-367">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-367">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="5d734-368">**Точное стирание.** Выберите один из двух размеров ластика, чтобы исправить небольшие недочеты рукописных фрагментов.</span><span class="sxs-lookup"><span data-stu-id="5d734-368">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="5d734-369">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-369">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="5d734-370">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="5d734-370">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="5d734-371">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="5d734-371">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="5d734-372">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-372">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="5d734-373">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="5d734-373">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="5d734-374">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="5d734-374">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="5d734-375">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-375">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="5d734-376">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="5d734-376">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="5d734-377">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="5d734-377">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="5d734-378">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-378">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="5d734-379">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="5d734-379">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="5d734-380">Подробнее</span><span class="sxs-lookup"><span data-stu-id="5d734-380">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-383">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-383">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5d734-384">Access</span><span class="sxs-lookup"><span data-stu-id="5d734-384">Access</span></span>

- <span data-ttu-id="5d734-385">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке &quot;Запрос поврежден&quot; при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="5d734-385">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="5d734-386">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="5d734-386">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="5d734-387">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="5d734-387">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="5d734-388">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="5d734-388">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="5d734-389">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="5d734-389">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="5d734-390">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="5d734-390">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="5d734-391">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-391">Excel</span></span>

- <span data-ttu-id="5d734-392">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="5d734-392">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="5d734-393">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="5d734-393">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="5d734-394">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="5d734-394">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="5d734-395">Это обновление устраняет проблему, из-за которой на панели формул текст отображался шрифтом, отличным от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="5d734-395">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="5d734-396">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="5d734-396">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="5d734-397">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="5d734-397">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="5d734-398">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="5d734-398">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="5d734-399">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="5d734-399">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="5d734-400">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="5d734-400">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="5d734-401">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="5d734-401">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="5d734-402">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="5d734-402">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="5d734-403">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="5d734-403">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="5d734-404">Исправлена проблема, которая могла возникнуть у некоторых пользователей со встроенными и связанными объектами (OLE).</span><span class="sxs-lookup"><span data-stu-id="5d734-404">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="5d734-405">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="5d734-405">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="5d734-406">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="5d734-406">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="5d734-407">Исправлена ошибка, из-за которой некоторые пользователи могли сталкиваться с несколькими всплывающими окнами при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="5d734-407">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="5d734-408">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="5d734-408">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="5d734-409">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="5d734-409">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="5d734-410">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="5d734-410">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="5d734-411">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-411">Outlook</span></span>

- <span data-ttu-id="5d734-412">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="5d734-412">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="5d734-413">Исправлена проблема, приводившая к зависаниям у пользователей в Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="5d734-413">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="5d734-414">Устранена проблема, которая приводила к неправильному выравниванию поля поиска в режиме высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="5d734-414">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="5d734-415">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="5d734-415">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="5d734-416">Исправлена проблема, из-за которой пользователи иногда наблюдали отправку сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="5d734-416">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="5d734-417">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="5d734-417">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="5d734-418">Исправлена проблема, которая не позволяла сохранять файлы в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="5d734-418">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="5d734-419">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="5d734-419">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="5d734-420">Устранена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="5d734-420">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="5d734-421">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой &quot;ОК&quot; при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="5d734-421">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="5d734-422">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="5d734-422">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="5d734-423">Устранена проблема, из-за которой Outlook неожиданно синхронизировал всю почту, даже если для ползунка синхронизации установлено меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="5d734-423">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="5d734-424">Устранена проблема, из-за которой пользователи с Black Theme видели выпадающий список &quot;От&quot;, отображающий белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="5d734-424">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="5d734-425">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="5d734-425">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="5d734-426">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="5d734-426">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="5d734-427">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="5d734-427">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="5d734-428">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение &quot;Правила на этом компьютере противоречат правилам Microsoft Exchange&quot;.</span><span class="sxs-lookup"><span data-stu-id="5d734-428">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="5d734-429">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="5d734-429">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="5d734-430">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="5d734-430">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="5d734-431">Устранена проблема, которая могла привести к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="5d734-431">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="5d734-432">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="5d734-432">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="5d734-433">Исправлена проблема, из-за которой пользователи не могли открывать некоторые вхождения повторяющихся элементов календаря.</span><span class="sxs-lookup"><span data-stu-id="5d734-433">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="5d734-434">Устранена проблема, из-за которой у пользователей с почтовыми ящиками на серверах Exchange 2010 возникали проблемы при добавлении вложений в элементы календаря.</span><span class="sxs-lookup"><span data-stu-id="5d734-434">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="5d734-435">Устранена проблема, из-за которой у пользователей возникали проблемы при ответе на сообщения с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="5d734-435">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="5d734-436">Исправлена проблема, из-за которой неожиданно обновлялось поле расположения в собраниях.</span><span class="sxs-lookup"><span data-stu-id="5d734-436">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="5d734-437">Устранена проблема, из-за которой запятые в поле местоположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="5d734-437">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="5d734-438">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="5d734-438">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="5d734-439">Решены вопросы, связанные со встречами и встречами, установленными в часовом поясе Бразилии.</span><span class="sxs-lookup"><span data-stu-id="5d734-439">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="5d734-440">Устранена проблема, из-за которой пользователи видели сообщения, неожиданно отправленные при нажатии клавиши &quot;S&quot;после закрытия панели проверки доступности.</span><span class="sxs-lookup"><span data-stu-id="5d734-440">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="5d734-441">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="5d734-441">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="5d734-442">Устранена проблема, из-за которой веб-надстройки обращались к сообщениям, управляемым цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="5d734-442">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="5d734-443">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="5d734-443">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="5d734-444">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="5d734-444">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5d734-445">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-445">PowerPoint</span></span>

- <span data-ttu-id="5d734-446">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="5d734-446">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="5d734-447">Устранена проблема, которая могла вызвать сбой при использовании контекстного меню в устаревших комментариях PPT.</span><span class="sxs-lookup"><span data-stu-id="5d734-447">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="5d734-448">Project</span><span class="sxs-lookup"><span data-stu-id="5d734-448">Project</span></span>

- <span data-ttu-id="5d734-449">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="5d734-449">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="5d734-450">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="5d734-450">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="5d734-451">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="5d734-451">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="5d734-452">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="5d734-452">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="5d734-453">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-453">Word</span></span>

- <span data-ttu-id="5d734-454">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="5d734-454">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="5d734-455">Диспетчер стандартных блоков может отображать неправильное оповещение: &quot;Были изменены стили, стандартные блоки&quot;.</span><span class="sxs-lookup"><span data-stu-id="5d734-455">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d734-456">Набор Office</span><span class="sxs-lookup"><span data-stu-id="5d734-456">Office Suite</span></span>

- <span data-ttu-id="5d734-457">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="5d734-457">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="5d734-458">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="5d734-458">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="5d734-459">Исправлена ошибка в настройке ODT и крайнего срока обновления GPO, когда относительный крайний срок работает только при первом его включении, исправление включает относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="5d734-459">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="5d734-460">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="5d734-460">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="5d734-461">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="5d734-461">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="5d734-463">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="5d734-463">Version 1908: February 11</span></span>
<span data-ttu-id="5d734-464">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="5d734-464">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="5d734-465">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-467">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-467">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5d734-468">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-468">Excel</span></span>

- <span data-ttu-id="5d734-469">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="5d734-469">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="5d734-470">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="5d734-470">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="5d734-471">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="5d734-471">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="5d734-472">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="5d734-472">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="5d734-473">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="5d734-473">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="5d734-474">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="5d734-474">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="5d734-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-475">Outlook</span></span>

- <span data-ttu-id="5d734-476">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="5d734-476">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="5d734-477">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="5d734-477">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="5d734-478">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="5d734-478">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="5d734-479">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="5d734-479">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="5d734-480">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="5d734-480">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="5d734-481">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="5d734-481">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="5d734-482">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="5d734-482">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5d734-483">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-483">PowerPoint</span></span>

- <span data-ttu-id="5d734-484">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="5d734-484">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="5d734-485">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="5d734-485">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="5d734-486">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="5d734-486">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="5d734-487">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="5d734-487">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="5d734-488">Project</span><span class="sxs-lookup"><span data-stu-id="5d734-488">Project</span></span>

- <span data-ttu-id="5d734-489">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="5d734-489">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="5d734-490">Word</span><span class="sxs-lookup"><span data-stu-id="5d734-490">Word</span></span>

- <span data-ttu-id="5d734-491">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="5d734-491">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d734-492">Набор Office</span><span class="sxs-lookup"><span data-stu-id="5d734-492">Office Suite</span></span>

- <span data-ttu-id="5d734-493">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="5d734-493">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="5d734-495">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="5d734-495">Version 1908: January 14</span></span>
<span data-ttu-id="5d734-496">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="5d734-496">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="5d734-497">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="5d734-497">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="5d734-499">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="5d734-499">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5d734-500">Excel</span><span class="sxs-lookup"><span data-stu-id="5d734-500">Excel</span></span>

- <span data-ttu-id="5d734-501">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="5d734-501">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="5d734-502">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="5d734-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="5d734-503">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытой надстройкой.</span><span class="sxs-lookup"><span data-stu-id="5d734-503">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="5d734-504">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d734-504">Outlook</span></span>

- <span data-ttu-id="5d734-505">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="5d734-505">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="5d734-506">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="5d734-506">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="5d734-507">Исправлена проблема, вызывавшая у пользователей периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="5d734-507">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5d734-508">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d734-508">PowerPoint</span></span>

- <span data-ttu-id="5d734-509">Исправлена проблема, из-за которой копирование слайда из одной презентации в другую могло создавать дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="5d734-509">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="5d734-510">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="5d734-510">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d734-511">Набор Office</span><span class="sxs-lookup"><span data-stu-id="5d734-511">Office Suite</span></span>

- <span data-ttu-id="5d734-512">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="5d734-512">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="5d734-513">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="5d734-513">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="5d734-514">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="5d734-514">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="5d734-516">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="5d734-516">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
