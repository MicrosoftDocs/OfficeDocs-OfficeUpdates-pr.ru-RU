---
title: Заметки о выпусках Полугодового канала (предварительной корпоративной версии) в 2020 г.
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel (Targeted) для подписки "Приложения Microsoft 365" в 2020 г. для ИТ-специалистов.
ms.openlocfilehash: 71bc9b10ba52a077ba5cb20e2ab916ef7190814c
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837630"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="591b0-103">Заметки о выпусках для Полугодового канала (предварительной корпоративной версии)</span><span class="sxs-lookup"><span data-stu-id="591b0-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="591b0-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (предварительная корпоративная версия) для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="591b0-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="591b0-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="591b0-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="591b0-106">Подробнее см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="591b0-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-january-12"></a><span data-ttu-id="591b0-107">Версия 2008: 12 января</span><span class="sxs-lookup"><span data-stu-id="591b0-107">Version 2008: January 12</span></span>
<span data-ttu-id="591b0-108">*Версия 2008 (сборка 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="591b0-108">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="591b0-109">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-111">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-112">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-112">Excel</span></span>

- <span data-ttu-id="591b0-113">Исправлена проблема, из-за которой при открытии книг только для чтения, было невозможно обновить данные сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="591b0-113">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="591b0-114">Это изменение позволяет устранить следующие проблемы: при вставке файла из локальной папки синхронизации OneDrive Excel не отображает правильный значок "Вставить объект".</span><span class="sxs-lookup"><span data-stu-id="591b0-114">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="591b0-115">Исправлена проблема, из-за которой клиенты не получали уведомлений о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="591b0-115">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="591b0-116">Исправлена проблема с редактированием, из-за которой использование редактора метода ввода в режиме перезаписи приводило к неправильному изменению дополнительных символов.</span><span class="sxs-lookup"><span data-stu-id="591b0-116">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="591b0-117">Исправлена проблема при использовании данных в режиме реального времени в сочетании с функцией многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="591b0-117">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="591b0-118">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="591b0-118">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="591b0-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-119">Outlook</span></span>

- <span data-ttu-id="591b0-120">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="591b0-120">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="591b0-121">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="591b0-121">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="591b0-122">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="591b0-122">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="591b0-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-123">PowerPoint</span></span>

- <span data-ttu-id="591b0-124">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="591b0-124">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="591b0-125">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="591b0-125">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="591b0-126">Project</span><span class="sxs-lookup"><span data-stu-id="591b0-126">Project</span></span>

- <span data-ttu-id="591b0-127">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="591b0-127">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="591b0-128">Skype</span><span class="sxs-lookup"><span data-stu-id="591b0-128">Skype</span></span>

- <span data-ttu-id="591b0-129">Устраняет проблему, из-за которой сертификат TLS-DSK пользователя обновлялся не в ожидаемое время, а только тогда, когда срок его действия оставался менее 12 часов.</span><span class="sxs-lookup"><span data-stu-id="591b0-129">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="591b0-130">Устраняет проблему, при которой пользовательский интерфейс Skype для бизнеса отображается как пустой после входа в систему, когда Office еще не лицензирован.</span><span class="sxs-lookup"><span data-stu-id="591b0-130">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="591b0-131">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-131">Office Suite</span></span>

- <span data-ttu-id="591b0-132">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="591b0-132">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="591b0-133">Это изменение решает проблему с резервным прокси-сервером SVG, в результате которого возникает нарушение прав доступа.</span><span class="sxs-lookup"><span data-stu-id="591b0-133">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-december-08"></a><span data-ttu-id="591b0-135">Версия 2008: 8 сентября</span><span class="sxs-lookup"><span data-stu-id="591b0-135">Version 2008: December 08</span></span>
<span data-ttu-id="591b0-136">*Версия 2008 (сборка 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="591b0-136">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="591b0-137">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-139">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-139">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="591b0-140">Access</span><span class="sxs-lookup"><span data-stu-id="591b0-140">Access</span></span>

- <span data-ttu-id="591b0-141">Исправлена ошибка, возникавшая при попытке использовать построитель DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="591b0-141">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="591b0-142">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-142">Excel</span></span>

- <span data-ttu-id="591b0-143">Исправлена ошибка, из-за которой не удавалось изменять сводные таблицы и сохранять книги, если они были экспортированы из плана Project.</span><span class="sxs-lookup"><span data-stu-id="591b0-143">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="591b0-144">Исправлена ошибка, из-за которой в некоторых случаях при открытии файла в режиме "только для чтения" отображалось несколько панелей сообщений.</span><span class="sxs-lookup"><span data-stu-id="591b0-144">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="591b0-145">Исправлена ошибка, из-за которой происходил сбой работы промежуточных итогов структуры при большом количестве повторяющихся значений заголовков столбцов.</span><span class="sxs-lookup"><span data-stu-id="591b0-145">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="591b0-146">Исправлена ошибка, из-за которой происходил сбой работы Excel при обновлении объекта групповой политики (например, с помощью удаленного обновления групповой политики) во время многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="591b0-146">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="591b0-147">Исправлена ошибка, из-за которой происходил сбой работы Excel при использовании функции промежуточных итогов в более чем 255 столбцах.</span><span class="sxs-lookup"><span data-stu-id="591b0-147">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="591b0-148">Улучшен кернинг текста в PowerPoint при копировании содержимого из Excel и его вставке в PowerPoint с помощью функции внедрения.</span><span class="sxs-lookup"><span data-stu-id="591b0-148">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="591b0-149">Исправлена ошибка, которая блокировала переключение из режима предварительного просмотра таблицы и редактора запросов в PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="591b0-149">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="591b0-150">Исправлена ошибка, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-150">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="591b0-151">Исправлена ошибка, из-за которой Power Pivot не мог распознавать разделитель вкладок.</span><span class="sxs-lookup"><span data-stu-id="591b0-151">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="591b0-152">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-152">Outlook</span></span>

- <span data-ttu-id="591b0-153">Исправлена ошибка, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="591b0-153">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="591b0-154">Исправлена ошибка, из-за которой происходил сбой события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="591b0-154">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="591b0-155">Исправлена ошибка, из-за которой приложение неожиданно закрывалось при отправке почты Outlook из других приложений.</span><span class="sxs-lookup"><span data-stu-id="591b0-155">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="591b0-156">Исправлена ошибка, из-за которой снижалась производительность при перемещении нескольких почтовых элементов между папками в интерактивном режиме.</span><span class="sxs-lookup"><span data-stu-id="591b0-156">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="591b0-157">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="591b0-157">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="591b0-158">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = параметры filetime исключены 1 = (по умолчанию) параметры filetime включены</span><span class="sxs-lookup"><span data-stu-id="591b0-158">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="591b0-159">Исправлена ошибка, из-за которой исчезали встроенные изображения при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="591b0-159">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="591b0-160">Исправлена ошибка, из-за которой имя пользователя отображалось как номер телефона при отправке голосовых сообщений, защищенных службой Azure, в результате чего пользователи классического приложения Outlook не могли открывать голосовые сообщения от внешних пользователей.</span><span class="sxs-lookup"><span data-stu-id="591b0-160">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="591b0-161">Исправлена ошибка, из-за которой при настройке конфигурации OME добавлялись лишние вложения в элемент электронной почты, в результате чего Outlook шифровал сообщение, даже если на стороне службы был настроен параметр DecryptAttachmentsForEncryptOnly.</span><span class="sxs-lookup"><span data-stu-id="591b0-161">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="591b0-162">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-162">PowerPoint</span></span>

- <span data-ttu-id="591b0-163">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="591b0-163">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="591b0-164">Исправлена ошибка, из-за которой функция "Рады видеть вас снова!</span><span class="sxs-lookup"><span data-stu-id="591b0-164">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="591b0-165">Продолжайте работу в Office с того места, на котором остановились" не работала в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-165">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="591b0-166">Visio</span><span class="sxs-lookup"><span data-stu-id="591b0-166">Visio</span></span>

- <span data-ttu-id="591b0-167">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="591b0-167">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="591b0-168">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-168">Word</span></span>

- <span data-ttu-id="591b0-169">Исправлена ошибка, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="591b0-169">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="591b0-170">Исправлена ошибка, из-за которой при ответе на родительский комментарий с неизвестным расширением в списке расширений ответ получал то же расширение.</span><span class="sxs-lookup"><span data-stu-id="591b0-170">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="591b0-171">Устранена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="591b0-171">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="591b0-172">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-172">Office Suite</span></span>

- <span data-ttu-id="591b0-173">Устранена проблема, из-за которой пользователи не могли импортировать списки SPO при отключенной ADAL.</span><span class="sxs-lookup"><span data-stu-id="591b0-173">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-november-10"></a><span data-ttu-id="591b0-175">Версия 2008: 10 ноября</span><span class="sxs-lookup"><span data-stu-id="591b0-175">Version 2008: November 10</span></span>
<span data-ttu-id="591b0-176">*Версия 2008 (сборка 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="591b0-176">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="591b0-177">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-179">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-179">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="591b0-180">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-180">Excel</span></span>

- <span data-ttu-id="591b0-181">Исправлена проблема, из-за которой некоторые функции выдавали неправильный результат после загрузки книги.</span><span class="sxs-lookup"><span data-stu-id="591b0-181">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="591b0-182">Исправлена проблема с неожиданным завершением работы приложения, которое было связано со ссылками и именованными диапазонами надстройки XLAM.</span><span class="sxs-lookup"><span data-stu-id="591b0-182">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="591b0-183">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="591b0-183">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="591b0-184">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="591b0-184">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="591b0-185">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="591b0-185">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="591b0-186">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="591b0-186">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-187">Outlook</span></span>

- <span data-ttu-id="591b0-188">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="591b0-188">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="591b0-189">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="591b0-189">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="591b0-190">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="591b0-190">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="591b0-191">Исправлена проблема, из-за которой поисковые запросы в календарях групп не возвращали никаких результатов.</span><span class="sxs-lookup"><span data-stu-id="591b0-191">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="591b0-192">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="591b0-192">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="591b0-193">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="591b0-193">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="591b0-194">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке искажались при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="591b0-194">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="591b0-195">Исправлена проблема, из-за которой необязательные сетевые функции блокировали загрузку веб-надстроек.</span><span class="sxs-lookup"><span data-stu-id="591b0-195">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="591b0-196">Дополнительные сведения см. в этой [публикации в блоге](https://developer.microsoft.com/ru-RU/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="591b0-196">See details in [blog post](https://developer.microsoft.com/ru-RU/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="591b0-197">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-197">PowerPoint</span></span>

- <span data-ttu-id="591b0-198">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="591b0-198">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="591b0-199">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-199">Office Suite</span></span>

- <span data-ttu-id="591b0-200">Исправлена проблема для коммерческих пользователей, применяющих System Center Configuration Manager или другие средства управления для обновления Office с использованием защиты от потери данных в конечной точке Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="591b0-200">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="591b0-201">Исправлена проблема с неработающим API сообщений для надстроек Office.</span><span class="sxs-lookup"><span data-stu-id="591b0-201">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-october-13"></a><span data-ttu-id="591b0-203">Версия 2008: 13 октября</span><span class="sxs-lookup"><span data-stu-id="591b0-203">Version 2008: October 13</span></span>
<span data-ttu-id="591b0-204">*Версия 2008 (сборка 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="591b0-204">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="591b0-205">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-205">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-207">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-207">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-208">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-208">Excel</span></span>

- <span data-ttu-id="591b0-209">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="591b0-209">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="591b0-210">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="591b0-210">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="591b0-211">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="591b0-211">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="591b0-212">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="591b0-212">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="591b0-213">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-213">Outlook</span></span>

- <span data-ttu-id="591b0-214">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="591b0-214">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="591b0-215">Исправлена проблема, из-за которой иногда не удавалось применить параметр "Включить улучшения общего календаря" к существующим общим календарям.</span><span class="sxs-lookup"><span data-stu-id="591b0-215">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="591b0-216">Исправлена проблема, из-за которой при открытии облачного вложения ошибка отображалась на странице безопасных ссылок, а не в открываемом документе.</span><span class="sxs-lookup"><span data-stu-id="591b0-216">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="591b0-217">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="591b0-217">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="591b0-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-218">PowerPoint</span></span>

- <span data-ttu-id="591b0-219">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="591b0-219">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="591b0-220">Исправление системы безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="591b0-220">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="591b0-221">Исправлена проблема в диалоговом окне "Параметры действия", из-за которой возникал сбой в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-221">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="591b0-222">Visio</span><span class="sxs-lookup"><span data-stu-id="591b0-222">Visio</span></span>

- <span data-ttu-id="591b0-223">Исправлена проблема, из-за которой возникал сбой динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="591b0-223">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="591b0-224">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-224">Word</span></span>

- <span data-ttu-id="591b0-225">Исправлена проблема, которая вызывала сбой при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="591b0-225">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="591b0-226">Исправлена проблема, из-за которой мог возникать сбой при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="591b0-226">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="591b0-227">Устранена проблема, которая могла вызвать сбой при загрузке Word.</span><span class="sxs-lookup"><span data-stu-id="591b0-227">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="591b0-228">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="591b0-228">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="591b0-229">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-229">Office Suite</span></span>

- <span data-ttu-id="591b0-230">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="591b0-230">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="591b0-231">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="591b0-231">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="591b0-232">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="591b0-232">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="591b0-233">Это изменение устраняет сбой при запуске приложений Office из-за невозможности загрузки d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="591b0-233">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-08"></a><span data-ttu-id="591b0-235">Версия 2008: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="591b0-235">Version 2008: September 08</span></span>
<span data-ttu-id="591b0-236">*Версия 2008 (сборка 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="591b0-236">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="591b0-237">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-237">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="591b0-239">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="591b0-239">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="591b0-240">Access</span><span class="sxs-lookup"><span data-stu-id="591b0-240">Access</span></span>

- <span data-ttu-id="591b0-241">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="591b0-241">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="591b0-242">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="591b0-242">Search and replace text in SQL View.</span></span> <span data-ttu-id="591b0-243">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="591b0-243">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="591b0-244">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="591b0-244">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="591b0-245">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-245">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="591b0-246">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-246">Excel</span></span>

- <span data-ttu-id="591b0-247">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="591b0-247">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="591b0-248">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-248">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="591b0-249">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="591b0-249">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="591b0-250">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="591b0-250">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="591b0-251">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="591b0-251">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="591b0-252">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="591b0-252">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="591b0-253">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="591b0-253">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="591b0-254">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-254">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="591b0-255">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="591b0-255">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="591b0-256">**Ваши любимые функции Excel теперь работают быстрее.** Функции СУММЕСЛИМН, СРЗНАЧЕСЛИМН, СЧЁТЕСЛИМН, МАКСЕСЛИМН и МИНЕСЛИМН теперь работают намного быстрее.</span><span class="sxs-lookup"><span data-stu-id="591b0-256">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="591b0-257">Быстрее переходите к итоговой строке.</span><span class="sxs-lookup"><span data-stu-id="591b0-257">Get to the bottom line more quickly.</span></span> <span data-ttu-id="591b0-258">Попробуйте уже сейчас.</span><span class="sxs-lookup"><span data-stu-id="591b0-258">Try one now.</span></span>

- <span data-ttu-id="591b0-259">**Улучшение функции Realtimedata (RTD):** В Office 365 версии 2002 канала Monthly channel или более поздних версиях функция Excel RealTimeData (ДРВ) работает гораздо быстрее, чем в вычисление данных в таблице в Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="591b0-259">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="591b0-260">Мы удалили узкие места в базовой памяти и структурах данных, а также обеспечили потокобезопасность, чтобы разрешить вычисление во всех доступных потоках многопоточного пересчета (MTR).</span><span class="sxs-lookup"><span data-stu-id="591b0-260">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-261">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-261">Outlook</span></span>

- <span data-ttu-id="591b0-262">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="591b0-262">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="591b0-263">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="591b0-263">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="591b0-264">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="591b0-264">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="591b0-265">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-265">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="591b0-266">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="591b0-266">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="591b0-267">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="591b0-267">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="591b0-268">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="591b0-268">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="591b0-269">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="591b0-269">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="591b0-270">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="591b0-270">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="591b0-271">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="591b0-271">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="591b0-272">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-272">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="591b0-273">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="591b0-273">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="591b0-274">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="591b0-274">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="591b0-275">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="591b0-275">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="591b0-276">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="591b0-276">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="591b0-277">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="591b0-277">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="591b0-278">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="591b0-278">See details in [blog post](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="591b0-279">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="591b0-279">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="591b0-280">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-280">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="591b0-281">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-281">PowerPoint</span></span>

- <span data-ttu-id="591b0-282">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="591b0-282">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="591b0-283">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-283">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="591b0-284">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="591b0-284">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="591b0-285">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-285">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="591b0-286">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="591b0-286">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="591b0-287">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-287">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="591b0-288">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-288">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="591b0-289">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="591b0-289">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="591b0-290">**Улучшенные диаграммы.** Более удобное создание диаграмм от руки за счет использования улучшенных соединителей и более совершенного процесса преобразования рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="591b0-290">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="591b0-291">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-291">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="591b0-292">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="591b0-292">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="591b0-293">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="591b0-293">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="591b0-294">**Комментарии.** Новые функций комментирования в PowerPoint позволяют быстро и легко находить и добавлять комментарии к документам.</span><span class="sxs-lookup"><span data-stu-id="591b0-294">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="591b0-295">Модернизируйте совместную работу с помощью новых функций, таких как привязка комментариев, сопоставление, задачи, улучшенные уведомления об упоминаниях и т. д.</span><span class="sxs-lookup"><span data-stu-id="591b0-295">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="591b0-296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-296">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="591b0-297">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="591b0-297">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="591b0-298">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-298">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="591b0-299">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="591b0-299">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="591b0-300">**Ссылка на слайд:** попросите коллег поучаствовать в создании презентации и направьте их прямо на нужный слайд.</span><span class="sxs-lookup"><span data-stu-id="591b0-300">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="591b0-301">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-301">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="591b0-302">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="591b0-302">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="591b0-303">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="591b0-303">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="591b0-304">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="591b0-304">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="591b0-305">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-305">Word</span></span>

- <span data-ttu-id="591b0-306">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="591b0-306">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="591b0-307">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-307">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="591b0-308">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="591b0-308">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="591b0-309">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="591b0-309">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="591b0-310">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-310">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="591b0-311">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="591b0-311">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="591b0-312">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="591b0-312">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="591b0-313">**Подтверждение действий в средстве чтения с экрана.** Подтверждение действий — это важное требование для обеспечения специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="591b0-313">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="591b0-314">С появлением нового API уведомлений из Windows мы можем оповещать пользователей средства чтения с экрана об успехе их действий.</span><span class="sxs-lookup"><span data-stu-id="591b0-314">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="591b0-315">Теперь пользователи экранного диктора в Word для Win32 уведомляются о вырезании, копировании, вставке, использовании полужирного шрифта, курсива или подчеркивания, отмене, повторе, автозамене и автоматическом использовании прописных букв.</span><span class="sxs-lookup"><span data-stu-id="591b0-315">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="591b0-316">Чтобы включить эту возможность, включите экранный диктор с помощью клавиш Windows+CTRL+ВВОД.</span><span class="sxs-lookup"><span data-stu-id="591b0-316">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="591b0-317">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="591b0-317">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-318">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-318">Office Suite</span></span>

- <span data-ttu-id="591b0-319">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="591b0-319">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-322">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-322">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="591b0-323">Доступ</span><span class="sxs-lookup"><span data-stu-id="591b0-323">Access</span></span>

- <span data-ttu-id="591b0-324">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="591b0-324">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="591b0-325">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="591b0-325">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="591b0-326">Исправлена проблема, препятствующая возможности вызова расширенного типа данных "Дата/время" без сбоев приложения.</span><span class="sxs-lookup"><span data-stu-id="591b0-326">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="591b0-327">Проблема исправлена, поэтому теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для управления и изменения типа данных Decimal.</span><span class="sxs-lookup"><span data-stu-id="591b0-327">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="591b0-328">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="591b0-328">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="591b0-329">Эта проблема исправлена в Access, но мы продолжаем изучать дополнительные интерфейсы, чтобы она не повторилась.</span><span class="sxs-lookup"><span data-stu-id="591b0-329">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="591b0-330">Команда сообщит о будущих обновлениях. Мы ценим ваше терпение.</span><span class="sxs-lookup"><span data-stu-id="591b0-330">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="591b0-331">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="591b0-331">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="591b0-332">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-332">Excel</span></span>

- <span data-ttu-id="591b0-333">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="591b0-333">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="591b0-334">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="591b0-334">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="591b0-335">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="591b0-335">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="591b0-336">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="591b0-336">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="591b0-337">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="591b0-337">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="591b0-338">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="591b0-338">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="591b0-339">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="591b0-339">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="591b0-340">Исправлена проблема, из-за которой в некоторых случаях при щелчке по гиперссылке внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="591b0-340">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="591b0-341">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="591b0-341">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="591b0-342">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="591b0-342">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="591b0-343">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="591b0-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="591b0-344">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="591b0-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="591b0-345">Это устраняет проблему, из-за которой при подключениях, созданных поставщиком данных SQL в более ранних версиях Office, параметры внутренних таблиц задавались не так, как в Office 365.</span><span class="sxs-lookup"><span data-stu-id="591b0-345">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="591b0-346">Это приводит к отключению раскрывающегося списка "Просмотр таблиц" или "Редактор запросов" для файлов с подключениями, созданными в более ранних версиях Office, когда они открывались с помощью Office 365.</span><span class="sxs-lookup"><span data-stu-id="591b0-346">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="591b0-347">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="591b0-347">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="591b0-348">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="591b0-348">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="591b0-349">OneNote</span><span class="sxs-lookup"><span data-stu-id="591b0-349">OneNote</span></span>

- <span data-ttu-id="591b0-350">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="591b0-350">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="591b0-351">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-351">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="591b0-352">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="591b0-352">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="591b0-353">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-353">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="591b0-354">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="591b0-354">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="591b0-355">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-355">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="591b0-356">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="591b0-356">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="591b0-357">Улучшена синхронизация и стабильность службы за счет временного изменения частоты создания журналов версий страниц.</span><span class="sxs-lookup"><span data-stu-id="591b0-357">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="591b0-358">Улучшена синхронизация и стабильность службы за счет временного отключения перемещения страниц в корзину.</span><span class="sxs-lookup"><span data-stu-id="591b0-358">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="591b0-359">Для пользователей, которым нужно удалить страницу, будет отображаться диалоговое окно с вопросом, нужно ли удалить страницу окончательно.</span><span class="sxs-lookup"><span data-stu-id="591b0-359">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-360">Outlook</span></span>

- <span data-ttu-id="591b0-361">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="591b0-361">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="591b0-362">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="591b0-362">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="591b0-363">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="591b0-363">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="591b0-364">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="591b0-364">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="591b0-365">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="591b0-365">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="591b0-366">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="591b0-366">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="591b0-367">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="591b0-367">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="591b0-368">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="591b0-368">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="591b0-369">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="591b0-369">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="591b0-370">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="591b0-370">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="591b0-371">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="591b0-371">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="591b0-372">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="591b0-372">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="591b0-373">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="591b0-373">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="591b0-374">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="591b0-374">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="591b0-375">Устранена проблема, которая в некоторых ситуациях приводила к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="591b0-375">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="591b0-376">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="591b0-376">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="591b0-377">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="591b0-377">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="591b0-378">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="591b0-378">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="591b0-379">Устранена проблема, из-за которой у пользователей возникали сбои в сторонних приложениях MAPI.</span><span class="sxs-lookup"><span data-stu-id="591b0-379">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="591b0-380">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="591b0-380">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="591b0-381">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="591b0-381">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="591b0-382">Устранена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="591b0-382">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="591b0-383">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="591b0-383">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="591b0-384">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="591b0-384">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="591b0-385">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="591b0-385">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="591b0-386">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="591b0-386">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="591b0-387">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="591b0-387">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="591b0-388">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="591b0-388">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="591b0-389">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="591b0-389">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="591b0-390">Устранена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="591b0-390">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="591b0-391">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="591b0-391">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="591b0-392">Исправлена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="591b0-392">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="591b0-393">Исправлена проблема, из-за которой возникали аномалии при использовании пользователями компактного представления.</span><span class="sxs-lookup"><span data-stu-id="591b0-393">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="591b0-394">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="591b0-394">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="591b0-395">Устранена проблема, из-за которой контекстное меню, вызываемое щелчком правой кнопки мыши, не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="591b0-395">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="591b0-396">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="591b0-396">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="591b0-397">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="591b0-397">Do you want to download them anyway?</span></span> <span data-ttu-id="591b0-398">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="591b0-398">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="591b0-399">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="591b0-399">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="591b0-400">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="591b0-400">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="591b0-401">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="591b0-401">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="591b0-402">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="591b0-402">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="591b0-403">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="591b0-403">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="591b0-404">Устранена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="591b0-404">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="591b0-405">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="591b0-405">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="591b0-406">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-406">PowerPoint</span></span>

- <span data-ttu-id="591b0-407">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="591b0-407">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="591b0-408">Устранена проблема со сбоем в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-408">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="591b0-409">Устранена проблема со сбоем панели предложений.</span><span class="sxs-lookup"><span data-stu-id="591b0-409">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="591b0-410">Project</span><span class="sxs-lookup"><span data-stu-id="591b0-410">Project</span></span>

- <span data-ttu-id="591b0-411">Устранена проблема, из-за которой при редактировании данных Предшественника / Преемника в представлении формы, запускалось дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="591b0-411">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="591b0-412">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="591b0-412">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="591b0-413">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="591b0-413">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="591b0-414">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="591b0-414">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="591b0-415">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="591b0-415">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="591b0-416">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="591b0-416">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="591b0-417">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="591b0-417">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="591b0-418">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="591b0-418">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="591b0-419">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="591b0-419">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="591b0-420">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="591b0-420">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="591b0-421">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-421">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="591b0-422">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="591b0-422">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="591b0-423">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="591b0-423">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="591b0-424">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="591b0-424">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="591b0-425">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-425">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="591b0-426">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="591b0-426">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="591b0-427">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="591b0-427">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="591b0-428">Skype</span><span class="sxs-lookup"><span data-stu-id="591b0-428">Skype</span></span>

- <span data-ttu-id="591b0-429">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="591b0-429">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="591b0-430">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="591b0-430">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="591b0-431">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="591b0-431">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="591b0-432">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="591b0-432">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-433">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-433">Word</span></span>

- <span data-ttu-id="591b0-434">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="591b0-434">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="591b0-435">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="591b0-435">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="591b0-436">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="591b0-436">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="591b0-437">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="591b0-437">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="591b0-438">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="591b0-438">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="591b0-439">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="591b0-439">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="591b0-440">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="591b0-440">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="591b0-441">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="591b0-441">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="591b0-442">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="591b0-442">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="591b0-443">Устранена проблема, которая могла вызвать сбой при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="591b0-443">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="591b0-444">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-444">Office Suite</span></span>

- <span data-ttu-id="591b0-445">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта.</span><span class="sxs-lookup"><span data-stu-id="591b0-445">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="591b0-446">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="591b0-446">This is now fixed.</span></span>

- <span data-ttu-id="591b0-447">Устранена проблема, из-за которой при закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="591b0-447">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="591b0-448">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="591b0-448">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="591b0-449">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="591b0-449">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="591b0-450">Исправлена проблема технологии "Нажми и работай", из-за которой происходил сбой обновления при попытке жесткой связи символьных ссылок.</span><span class="sxs-lookup"><span data-stu-id="591b0-450">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="591b0-451">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="591b0-451">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="591b0-452">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="591b0-452">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="591b0-453">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="591b0-453">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="591b0-454">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="591b0-454">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="591b0-455">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="591b0-455">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="591b0-456">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="591b0-456">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="591b0-457">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="591b0-457">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="591b0-458">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="591b0-458">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="591b0-459">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="591b0-459">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="591b0-460">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="591b0-460">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="591b0-461">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="591b0-461">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="591b0-462">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="591b0-462">This change would fix this issue.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-august-11"></a><span data-ttu-id="591b0-464">Версия 2002: 11 августа</span><span class="sxs-lookup"><span data-stu-id="591b0-464">Version 2002: August 11</span></span>
<span data-ttu-id="591b0-465">*Версия 2002 (сборка 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="591b0-465">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="591b0-466">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-466">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-468">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-469">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-469">Excel</span></span>

- <span data-ttu-id="591b0-470">Исправлена проблема, не позволявшая переключиться на редактирование файлов, открытых с использованием параметра "Рекомендовать доступ только для чтения".</span><span class="sxs-lookup"><span data-stu-id="591b0-470">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="591b0-471">OneNote</span><span class="sxs-lookup"><span data-stu-id="591b0-471">OneNote</span></span>

- <span data-ttu-id="591b0-472">Удалены лишние вызовы удостоверений, чтобы сократить использование ресурсов</span><span class="sxs-lookup"><span data-stu-id="591b0-472">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="591b0-473">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="591b0-473">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="591b0-474">Улучшена функция обнаружения ошибок и качество синхронизации.</span><span class="sxs-lookup"><span data-stu-id="591b0-474">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-475">Outlook</span></span>

- <span data-ttu-id="591b0-476">Исправлена ошибка, вызывавшая серьезную проблему с производительностью при запуске Outlook для некоторых клиентов.</span><span class="sxs-lookup"><span data-stu-id="591b0-476">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="591b0-477">Skype</span><span class="sxs-lookup"><span data-stu-id="591b0-477">Skype</span></span>

- <span data-ttu-id="591b0-478">Исправлена проблема, из-за которой запуск демонстрации экрана мог завершиться сбоем в 32-разрядном клиенте Skype для бизнеса после его работы в течение нескольких дней.</span><span class="sxs-lookup"><span data-stu-id="591b0-478">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-479">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-479">Office Suite</span></span>

- <span data-ttu-id="591b0-480">Исправлена проблема, из-за которой в случае отключения автосохранения с помощью групповой политики некоторые документы могли не отображать последнее содержимое сервера при открытии, пока пользователь не нажмет кнопку "Доступны обновления".</span><span class="sxs-lookup"><span data-stu-id="591b0-480">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-july-14"></a><span data-ttu-id="591b0-482">Версия 2002: 14 июля</span><span class="sxs-lookup"><span data-stu-id="591b0-482">Version 2002: July 14</span></span>
<span data-ttu-id="591b0-483">*Версия 2002 (сборка 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="591b0-483">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="591b0-484">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-484">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-486">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-486">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-487">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-487">Excel</span></span>

- <span data-ttu-id="591b0-488">Ускорение загрузки файлов, доступных в локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="591b0-488">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="591b0-489">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="591b0-489">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="591b0-490">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, поэтому закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="591b0-490">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="591b0-491">Исправлена проблема, при которой книга могла быть скрыта при щелчке гиперссылки на определенное место в уже открытой книге.</span><span class="sxs-lookup"><span data-stu-id="591b0-491">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="591b0-492">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="591b0-492">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="591b0-493">Повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="591b0-493">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="591b0-494">Устранена проблема, из-за которой имена принтеров могли повторяться в списке принтеров в диалоговом окне "Печать".</span><span class="sxs-lookup"><span data-stu-id="591b0-494">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="591b0-495">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="591b0-495">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="591b0-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-496">Outlook</span></span>

- <span data-ttu-id="591b0-497">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="591b0-497">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="591b0-498">Устранена проблема, при которой повторяющиеся встречи или собрания отображались с ошибкой во времени при приближении изменений в определении часового пояса.</span><span class="sxs-lookup"><span data-stu-id="591b0-498">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="591b0-499">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="591b0-499">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="591b0-500">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="591b0-500">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="591b0-501">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="591b0-501">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="591b0-502">Устранена проблема, из-за которой представители видели разные иерархии папок общих почтовых ящиков на разных компьютерах.</span><span class="sxs-lookup"><span data-stu-id="591b0-502">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="591b0-503">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="591b0-503">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="591b0-504">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="591b0-504">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="591b0-505">Устранена проблема, вызывавшая сбой после того, как две надстройки добавляли кнопку в одну и ту же группу ленты.</span><span class="sxs-lookup"><span data-stu-id="591b0-505">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="591b0-506">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения по адресам из личного списка рассылки.</span><span class="sxs-lookup"><span data-stu-id="591b0-506">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="591b0-507">Устранена проблема, из-за которой нельзя было добавить ссылки в сообщения электронной почты с правильным клиентским разрешением по умолчанию, если для этого разрешения был установлен параметр "все".</span><span class="sxs-lookup"><span data-stu-id="591b0-507">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="591b0-508">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="591b0-508">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-509">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-509">Word</span></span>

- <span data-ttu-id="591b0-510">Исправлена проблема с совместной работой над документом при включении политики FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="591b0-510">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="591b0-511">Устранена проблема, при которой функция экспресс-блоков Word не работала при добавлении переименованного поля подстановки.</span><span class="sxs-lookup"><span data-stu-id="591b0-511">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-512">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-512">Office Suite</span></span>

- <span data-ttu-id="591b0-513">Исправлена проблема, из-за которой при совместной работе над объемными файлами PowerPoint чрезмерно повышалась нагрузка на сеть и ЦП.</span><span class="sxs-lookup"><span data-stu-id="591b0-513">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="591b0-514">Мы отправили часть AppV51 на доработку, чтобы исправить в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="591b0-514">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="591b0-515">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="591b0-515">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-june-09"></a><span data-ttu-id="591b0-517">Версия 2002: 9 июня</span><span class="sxs-lookup"><span data-stu-id="591b0-517">Version 2002: June 09</span></span>
<span data-ttu-id="591b0-518">*Версия 2002 (сборка 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="591b0-518">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="591b0-519">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-519">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-521">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-521">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-522">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-522">Excel</span></span>

- <span data-ttu-id="591b0-523">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="591b0-523">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="591b0-524">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="591b0-524">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="591b0-525">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="591b0-525">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="591b0-526">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="591b0-526">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="591b0-527">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="591b0-527">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="591b0-528">Исправлена проблема, из-за которой знак @ в начале формулы считался неявным оператором пересечения.</span><span class="sxs-lookup"><span data-stu-id="591b0-528">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-529">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-529">Outlook</span></span>

- <span data-ttu-id="591b0-530">Позволяет присоединиться к собранию в Teams непосредственно через собственный клиент Teams.</span><span class="sxs-lookup"><span data-stu-id="591b0-530">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="591b0-531">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="591b0-531">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="591b0-532">Исправлена проблема, из-за которой пользователи, имеющие неправильный параметр эмуляции браузера, не могли завершить запрос на проверку подлинности Gmail.</span><span class="sxs-lookup"><span data-stu-id="591b0-532">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="591b0-533">Исправлена проблема пользователей Outlook, использующих серверные операционные системы, приводившая к ошибке "Состояние защиты от вирусов: Недействительно.</span><span class="sxs-lookup"><span data-stu-id="591b0-533">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="591b0-534">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены", несмотря на то, что антивирусная программа настроена правильно.</span><span class="sxs-lookup"><span data-stu-id="591b0-534">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-535">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-535">Word</span></span>

- <span data-ttu-id="591b0-536">Исправлена проблема, из-за которой выравнивание слова в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="591b0-536">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-537">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-537">Office Suite</span></span>

- <span data-ttu-id="591b0-538">Эта проблема устранена с помощью замены имен каналов в представлении Backstage на новые в разветвлении января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="591b0-538">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="591b0-539">Исправлена проблема, из-за которой устройства регулируемые политикой не могли вызвать API аудитории DMS.</span><span class="sxs-lookup"><span data-stu-id="591b0-539">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="591b0-540">Исправлена проблема, из-за которой при добавлении и удалении приложений в одной транзакции выполнялось неполное удаление.</span><span class="sxs-lookup"><span data-stu-id="591b0-540">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="591b0-541">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="591b0-541">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="591b0-542">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="591b0-542">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-may-12"></a><span data-ttu-id="591b0-544">Версия 2002: 12 мая</span><span class="sxs-lookup"><span data-stu-id="591b0-544">Version 2002: May 12</span></span>
<span data-ttu-id="591b0-545">*Версия 2002 (сборка 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="591b0-545">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="591b0-546">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-546">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-548">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-548">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="591b0-549">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-549">Excel</span></span>

- <span data-ttu-id="591b0-550">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="591b0-550">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="591b0-551">В некоторых случаях открытие CSV-файлов занимало больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="591b0-551">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="591b0-552">В ряде случаев приложение Excel аварийно завершало работу при переключении между книгами с разным масштабом.</span><span class="sxs-lookup"><span data-stu-id="591b0-552">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="591b0-553">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="591b0-553">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="591b0-554">Данные, скопированные из столбца и отфильтрованные по цвету, иногда не вставлялись должным образом.</span><span class="sxs-lookup"><span data-stu-id="591b0-554">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="591b0-555">Устранена проблема, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="591b0-555">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="591b0-556">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="591b0-556">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="591b0-557">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="591b0-557">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="591b0-558">При использовании Range.Value и Range.Value2 (VBA) формулы вводились как динамические массивы.</span><span class="sxs-lookup"><span data-stu-id="591b0-558">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="591b0-559">OneNote</span><span class="sxs-lookup"><span data-stu-id="591b0-559">OneNote</span></span>

- <span data-ttu-id="591b0-560">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="591b0-560">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="591b0-561">Отображает уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="591b0-561">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="591b0-562">Улучшена синхронизация и стабильность службы путем временного уменьшения количества и частоты синхронизации страниц журнала версий в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-562">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="591b0-563">Улучшена синхронизация и стабильность службы путем временного отключения корзины в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-563">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="591b0-564">Если пользователь пытается удалить данные, которые обычно отправляются в корзину, ему будет предложено сохранить или окончательно удалить их.</span><span class="sxs-lookup"><span data-stu-id="591b0-564">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="591b0-565">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-565">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="591b0-566">Улучшена синхронизация и стабильность службы путем временного откладывания загрузки внедренных файлов и изображений в записных книжках в Интернете, пока пользователь не перейдет на страницу в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-566">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="591b0-567">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-567">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="591b0-568">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="591b0-568">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="591b0-569">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="591b0-569">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="591b0-570">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="591b0-570">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-571">Outlook</span></span>

- <span data-ttu-id="591b0-572">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="591b0-572">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="591b0-573">Устранена проблема, приводившая в сбою при попытке открытия файлов MSG и OFT после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="591b0-573">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="591b0-574">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="591b0-574">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="591b0-575">Это обновление исправляет проблему, из-за которой в Microsoft Outlook не отображается текущая метка конфиденциальности при просмотре или создании сообщений.</span><span class="sxs-lookup"><span data-stu-id="591b0-575">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="591b0-576">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения в личный список рассылки.</span><span class="sxs-lookup"><span data-stu-id="591b0-576">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="591b0-577">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-577">PowerPoint</span></span>

- <span data-ttu-id="591b0-578">Устранена проблема с ретрансляцией точного текста сообщений для пользователей, которые открывают копию файла с улучшенными примечаниями.</span><span class="sxs-lookup"><span data-stu-id="591b0-578">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-579">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-579">Word</span></span>

- <span data-ttu-id="591b0-580">Решена проблема, из-за которой приложения Access и Publisher могли загружаться неправильно в зависимости от того, какие языки установлены.</span><span class="sxs-lookup"><span data-stu-id="591b0-580">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="591b0-581">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="591b0-581">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="591b0-582">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="591b0-582">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-583">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-583">Office Suite</span></span>

- <span data-ttu-id="591b0-584">Это исправление устраняет блокирование сети приложением Project при кэшировании файла в клиенте.</span><span class="sxs-lookup"><span data-stu-id="591b0-584">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="591b0-585">Решена проблема, из-за которой внутренняя операция вызывала исключение при сбое вместо ведения журнала и продолжения работы.</span><span class="sxs-lookup"><span data-stu-id="591b0-585">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="591b0-586">Для затронутых пользователей будет отменен запрет на получение обновлений.</span><span class="sxs-lookup"><span data-stu-id="591b0-586">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="591b0-587">Это изменение обеспечит правильную работу функции "Контур эскиза" на ленте.</span><span class="sxs-lookup"><span data-stu-id="591b0-587">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="591b0-588">Исправлена проблема при открытии файлов из локальных расположений с определенными настройками прокси.</span><span class="sxs-lookup"><span data-stu-id="591b0-588">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="591b0-589">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="591b0-589">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="591b0-590">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="591b0-590">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="591b0-591">Это обновление устраняет проблему в Microsoft Word, из-за которой текст длиной более 255 символов, вставленный при применении метки конфиденциальности, впоследствии не удавалось идентифицировать и удалить путем изменения или удаления метки, если в рамках политики меток был применен колонтитул или подложка.</span><span class="sxs-lookup"><span data-stu-id="591b0-591">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="591b0-592">Исправлена проблема, благодаря чему устранены сбои во время сеансов передачи Office и повышена надежность работы пользователей.</span><span class="sxs-lookup"><span data-stu-id="591b0-592">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="591b0-593">Это исправление обновляет конечную точку URL-адреса конфигурации усиленной безопасности (ECS).</span><span class="sxs-lookup"><span data-stu-id="591b0-593">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="591b0-594">В результате вызова этой новой конечной точки повышается успешность получения данных из ECS.</span><span class="sxs-lookup"><span data-stu-id="591b0-594">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-april-14"></a><span data-ttu-id="591b0-596">Версия 2002: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="591b0-596">Version 2002: April 14</span></span>
<span data-ttu-id="591b0-597">*Версия 2002 (сборка 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="591b0-597">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="591b0-598">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-598">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="591b0-599">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="591b0-599">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-600">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-600">Excel</span></span>

- <span data-ttu-id="591b0-601">**Ввод формулы, возвращающей несколько значений.** Теперь вы можете быстро ввести формулу, возвращающую несколько значений, которые автоматически переносятся в смежные ячейки.</span><span class="sxs-lookup"><span data-stu-id="591b0-601">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="591b0-602">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-602">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="591b0-603">**Шесть эффективных функций.** Добавлено шесть новых функций для улучшения электронных таблиц: ФИЛЬТР, СОРТ, СОРТПО, УНИК, ПОСЛЕДОВ и СЛУЧМАССИВ.</span><span class="sxs-lookup"><span data-stu-id="591b0-603">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="591b0-604">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-604">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="591b0-605">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="591b0-605">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="591b0-606">
  [Подробнее](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="591b0-606">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-608">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-608">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-609">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-609">Excel</span></span>

- <span data-ttu-id="591b0-610">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-610">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="591b0-611">В некоторых случаях при сохранении в виде CSV-файла Excel мог объединять все столбцы в один столбец.</span><span class="sxs-lookup"><span data-stu-id="591b0-611">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="591b0-612">Использование Range.ClearContents для диапазона в защищенном листе могло занимать больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="591b0-612">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="591b0-613">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="591b0-613">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="591b0-614">Макросы VBA, взаимодействующие с лентой, могут неожиданно запускаться со значением True, присвоенным параметру ScreenUpdating.</span><span class="sxs-lookup"><span data-stu-id="591b0-614">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="591b0-615">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении (заполнение вниз, заполнение в стороны), если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="591b0-615">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="591b0-616">В некоторых случаях в VBA не работал метод Application.Evaluate для определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="591b0-616">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="591b0-617">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="591b0-617">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="591b0-618">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-618">Outlook</span></span>

- <span data-ttu-id="591b0-619">Исправлена проблема, приводившая к неожиданному увеличению заголовка группы в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="591b0-619">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="591b0-620">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="591b0-620">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="591b0-621">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="591b0-621">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="591b0-622">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="591b0-622">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="591b0-623">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-623">PowerPoint</span></span>

- <span data-ttu-id="591b0-624">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="591b0-624">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="591b0-625">Project</span><span class="sxs-lookup"><span data-stu-id="591b0-625">Project</span></span>

- <span data-ttu-id="591b0-626">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="591b0-626">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="591b0-627">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="591b0-627">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-628">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-628">Word</span></span>

- <span data-ttu-id="591b0-629">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="591b0-629">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="591b0-630">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="591b0-630">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="591b0-631">Исправлена проблема, из-за которой вставляемые горизонтальные линии не укорачиваются и не располагаются по центру.</span><span class="sxs-lookup"><span data-stu-id="591b0-631">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-10"></a><span data-ttu-id="591b0-633">Версия 2002: 10 марта</span><span class="sxs-lookup"><span data-stu-id="591b0-633">Version 2002: March 10</span></span>
<span data-ttu-id="591b0-634">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="591b0-634">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="591b0-635">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-635">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="591b0-637">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="591b0-637">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="591b0-638">Access</span><span class="sxs-lookup"><span data-stu-id="591b0-638">Access</span></span>

- <span data-ttu-id="591b0-639">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="591b0-639">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="591b0-640">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-640">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="591b0-641">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-641">Excel</span></span>

- <span data-ttu-id="591b0-642">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="591b0-642">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="591b0-643">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-643">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="591b0-644">**Найдите то, что ищете:** Ищите команды, людей, файлы, фотографии, веб-статьи и многое другое.</span><span class="sxs-lookup"><span data-stu-id="591b0-644">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="591b0-645">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-645">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="591b0-646">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей книге.</span><span class="sxs-lookup"><span data-stu-id="591b0-646">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="591b0-647">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-647">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="591b0-648">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="591b0-648">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="591b0-649">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="591b0-649">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="591b0-650">**Сосредоточьтесь на оставшихся задачах.** Пометьте примечания как разрешенные, чтобы свернуть их и сделать открытые элементы более заметными.</span><span class="sxs-lookup"><span data-stu-id="591b0-650">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="591b0-651">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="591b0-651">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="591b0-652">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-652">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="591b0-653">**Преобразование файлов для расширения специальных возможностей.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="591b0-653">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="591b0-654">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="591b0-654">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="591b0-655">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-655">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="591b0-656">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="591b0-656">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="591b0-657">**Получите статистику в своей книге:** Статистика рабочей книги предоставляет обзор содержимого рабочей книги, чтобы упростить ее обнаружение.</span><span class="sxs-lookup"><span data-stu-id="591b0-657">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="591b0-658">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="591b0-658">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="591b0-659">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="591b0-659">Find them at Insert > Icons.</span></span> [<span data-ttu-id="591b0-660">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-660">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="591b0-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-661">Outlook</span></span>

- <span data-ttu-id="591b0-662">**Подключение к сети LinkedIn с помощью Outlook.** Безопасное подключение к учетным записям LinkedIn с помощью учетных записей Майкрософт для просмотра сведений из профилей LinkedIn прямо на карточках контактов.</span><span class="sxs-lookup"><span data-stu-id="591b0-662">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="591b0-663">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-663">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="591b0-p158">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты. [Подробнее](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="591b0-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="591b0-666">**Меню "Вставка ссылки" в Outlook вставляет ссылку с разрешениями, определенными администратором клиента.** При выборе из списка последних использованных ссылок в Outlook вставляется ссылка, которая была доступна только пользователям, имеющим разрешение на доступ к ней.</span><span class="sxs-lookup"><span data-stu-id="591b0-666">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="591b0-667">Из-за этого пользователи часто посылали друг другу письма с просьбой предоставить доступ к документу.</span><span class="sxs-lookup"><span data-stu-id="591b0-667">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="591b0-668">Мы обновили этот опыт, поэтому теперь ссылка вставляется с разрешением по умолчанию, установленным администратором клиента. Для MSIT это «организация может редактировать», поэтому все внутренние пользователи, получившие ссылку, которой поделились таким образом, смогут получить к ней доступ.</span><span class="sxs-lookup"><span data-stu-id="591b0-668">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="591b0-669">**Поиск с правописанием проблем или опечаток:** Outlook найдет то, что вы ищете, даже если ваше правописание не соответствует.</span><span class="sxs-lookup"><span data-stu-id="591b0-669">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="591b0-670">**Фишинговые письма легко обнаружить:** спам и фишинговые сообщения выглядят по-разному, поэтому вы можете легко их идентифицировать и удалить из папки «Входящие».</span><span class="sxs-lookup"><span data-stu-id="591b0-670">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="591b0-671">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="591b0-671">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="591b0-672">**Рисование.** Рисуйте поверх изображений или добавьте полотно, чтобы отправить свои идеи с помощью рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="591b0-672">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="591b0-673">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-673">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="591b0-674">**Получайте релевантные сообщения в результатах поиска.** Outlook анализирует условия поиска и отображает наиболее релевантные сообщения электронной почты в верхней части результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="591b0-674">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="591b0-675">Кроме того, все результаты будут отображаться в разделе "Лучшие результаты" с сортировкой по дате.</span><span class="sxs-lookup"><span data-stu-id="591b0-675">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="591b0-676">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-676">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="591b0-677">**Получение предложений по расположению.** Начните вводить текст в поле "Место" при планировании встреч и собраний, и Outlook предложит помещения, адреса и другие недавние места.</span><span class="sxs-lookup"><span data-stu-id="591b0-677">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="591b0-678">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-678">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="591b0-679">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="591b0-679">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="591b0-680">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-680">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="591b0-681">**Просмотр сообщений в другой освещенности.** Используйте кнопку "СОЛНЦЕ/ЛУНА" для переключения между светлым и темным фоном в области чтения.</span><span class="sxs-lookup"><span data-stu-id="591b0-681">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="591b0-682">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-682">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="591b0-683">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="591b0-683">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="591b0-684">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="591b0-684">Find them at Insert > Icons.</span></span> [<span data-ttu-id="591b0-685">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-685">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="591b0-686">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-686">PowerPoint</span></span>

- <span data-ttu-id="591b0-687">**Быстрое взаимодействие в реальном времени в PowerPoint:** Быстрое сотрудничество в реальном времени в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-687">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="591b0-688">**Новые средства проверки правописания.** Не переживайте из-за слов.</span><span class="sxs-lookup"><span data-stu-id="591b0-688">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="591b0-689">В PowerPoint теперь отображаются предложения в отношении грамматики и написания.</span><span class="sxs-lookup"><span data-stu-id="591b0-689">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="591b0-690">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-690">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="591b0-691">**Субтитры в реальном времени.** Слова докладчика автоматически отображаются на экране в виде субтитров или переводятся в субтитры на выбранном языке.</span><span class="sxs-lookup"><span data-stu-id="591b0-691">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="591b0-692">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-692">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="591b0-p168">**Вы вычисляете, мы форматируем.** Рукописные математические выражения преобразуются в стандартные знаки. Просто воспользуйтесь функцией "Рукописный фрагмент в математические символы" и выберите рукописные примечания для начала работы. [Подробнее](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="591b0-p168">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="591b0-696">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="591b0-696">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="591b0-697">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-697">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="591b0-698">**Поиск и исправление пропущенных названий слайдов:** Названия слайдов добавляют удар к вашей подаче и делают ваши слайды доступными для пользователей всех способностей.</span><span class="sxs-lookup"><span data-stu-id="591b0-698">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="591b0-699">С помощью средства проверки читаемости можно определить, где отсутствуют заголовки, и сразу же добавить их.</span><span class="sxs-lookup"><span data-stu-id="591b0-699">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="591b0-700">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-700">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="591b0-701">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей презентации.</span><span class="sxs-lookup"><span data-stu-id="591b0-701">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="591b0-702">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-702">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="591b0-703">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="591b0-703">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="591b0-704">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="591b0-704">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="591b0-705">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="591b0-705">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="591b0-706">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-706">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="591b0-707">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="591b0-707">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="591b0-708">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="591b0-708">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="591b0-709">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-709">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="591b0-710">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="591b0-710">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="591b0-711">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-711">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="591b0-712">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="591b0-712">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="591b0-713">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="591b0-713">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="591b0-714">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="591b0-714">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="591b0-715">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="591b0-715">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="591b0-716">**Зачем изобретать заново, если вы можете использовать повторно ?:** Экономьте время, повторно используя слайды, которые вы создали или которыми другие поделились с вами.</span><span class="sxs-lookup"><span data-stu-id="591b0-716">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="591b0-717">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-717">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="591b0-718">**Измените рукописные чернила на фигуры, текст или математику в PowerPoint для Office 365:** Перейдите от чернил произвольной формы к фигурам, тексту или математическому выражению Office за пару движений.</span><span class="sxs-lookup"><span data-stu-id="591b0-718">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="591b0-719">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-719">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="591b0-720">**Рукописный ввод для создания отличного слайда.** Преобразуйте рукописный ввод в стандартные фигуры и текст, а затем находите изящные идеи оформления слайдов в конструкторе PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-720">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="591b0-721">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-721">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="591b0-722">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="591b0-722">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="591b0-723">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="591b0-723">Find them at Insert > Icons.</span></span> [<span data-ttu-id="591b0-724">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-724">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="591b0-725">Visio</span><span class="sxs-lookup"><span data-stu-id="591b0-725">Visio</span></span>

- <span data-ttu-id="591b0-726">**В сценах преступления:** Используйте новые трафареты «Доказательства», «В помещении» и «На улице» в шаблоне «Расследование места преступления», чтобы детально воссоздать места преступления.</span><span class="sxs-lookup"><span data-stu-id="591b0-726">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="591b0-727">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="591b0-727">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="591b0-728">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-728">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="591b0-729">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-729">Word</span></span>

- <span data-ttu-id="591b0-730">**Редактор для резюме присоединяется к LinkedIn Resume Assistant:** редактор для резюме предлагает выбор грамматических и стилевых проверок, специально предназначенных для резюме, чтобы сделать ваше письмо более точным и профессиональным.</span><span class="sxs-lookup"><span data-stu-id="591b0-730">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="591b0-731">**Исправление проблемы с повреждением документа при объединении 3D объектов.** Исправлена проблема с повреждением документа, возникавшая при объединении 3D объектов.</span><span class="sxs-lookup"><span data-stu-id="591b0-731">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="591b0-732">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="591b0-732">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="591b0-733">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-733">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="591b0-734">**Сотрудничайте в живом цвете:** комментарии и изменения имеют цветовую кодировку от участника, поэтому легко увидеть, кто есть кто среди ваших соавторов.</span><span class="sxs-lookup"><span data-stu-id="591b0-734">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="591b0-735">**Совместное редактирование документов с поддержкой макросов:** сохраняйте файлы документов в OneDrive для бизнеса и редактируйте их вместе с соавторами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="591b0-735">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="591b0-736">**Улучшенные возможности совместного редактирования**. Улучшено быстродействие Word при совместном редактировании в документах с отслеживанием исправлений.</span><span class="sxs-lookup"><span data-stu-id="591b0-736">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="591b0-737">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="591b0-737">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="591b0-738">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="591b0-738">Find them at Insert > Icons.</span></span> [<span data-ttu-id="591b0-739">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-739">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="591b0-740">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="591b0-740">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="591b0-741">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своем документе.</span><span class="sxs-lookup"><span data-stu-id="591b0-741">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="591b0-742">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-742">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="591b0-743">**Точное стирание.** Выберите один из двух размеров ластика, чтобы исправить небольшие недочеты рукописных фрагментов.</span><span class="sxs-lookup"><span data-stu-id="591b0-743">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="591b0-744">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-744">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="591b0-745">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="591b0-745">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="591b0-746">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="591b0-746">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="591b0-747">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-747">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="591b0-748">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="591b0-748">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="591b0-749">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="591b0-749">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="591b0-750">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-750">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="591b0-751">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="591b0-751">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="591b0-752">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="591b0-752">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="591b0-753">Подробнее</span><span class="sxs-lookup"><span data-stu-id="591b0-753">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-756">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-756">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="591b0-757">Доступ</span><span class="sxs-lookup"><span data-stu-id="591b0-757">Access</span></span>

- <span data-ttu-id="591b0-758">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="591b0-758">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="591b0-759">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="591b0-759">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="591b0-760">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="591b0-760">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="591b0-761">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="591b0-761">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="591b0-762">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="591b0-762">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="591b0-763">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="591b0-763">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="591b0-764">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-764">Excel</span></span>

- <span data-ttu-id="591b0-765">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="591b0-765">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="591b0-766">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="591b0-766">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="591b0-767">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="591b0-767">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="591b0-768">Это обновление устраняет проблему, из-за которой на панели формул текст отображался шрифтом, отличным от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="591b0-768">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="591b0-769">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="591b0-769">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="591b0-770">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="591b0-770">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="591b0-771">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="591b0-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="591b0-772">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="591b0-772">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="591b0-773">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="591b0-773">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="591b0-774">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="591b0-774">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="591b0-775">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="591b0-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="591b0-776">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="591b0-776">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="591b0-777">Исправлена проблема, которая могла возникнуть у некоторых пользователей со встроенными и связанными объектами (OLE).</span><span class="sxs-lookup"><span data-stu-id="591b0-777">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="591b0-778">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="591b0-778">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="591b0-779">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="591b0-779">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="591b0-780">Исправлена ошибка, из-за которой некоторые пользователи могли сталкиваться с несколькими всплывающими окнами при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="591b0-780">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="591b0-781">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="591b0-781">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="591b0-782">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="591b0-782">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="591b0-783">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="591b0-783">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-784">Outlook</span></span>

- <span data-ttu-id="591b0-785">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="591b0-785">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="591b0-786">Исправлена проблема, приводившая к зависаниям у пользователей в Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="591b0-786">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="591b0-787">Устранена проблема, которая приводила к неправильному выравниванию поля поиска в режиме высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="591b0-787">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="591b0-788">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="591b0-788">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="591b0-789">Исправлена проблема, из-за которой пользователи иногда наблюдали отправку сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="591b0-789">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="591b0-790">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="591b0-790">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="591b0-791">Исправлена проблема, которая не позволяла сохранять файлы в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="591b0-791">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="591b0-792">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="591b0-792">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="591b0-793">Устранена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="591b0-793">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="591b0-794">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="591b0-794">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="591b0-795">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="591b0-795">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="591b0-796">Устранена проблема, из-за которой Outlook неожиданно синхронизировал всю почту, даже если для ползунка синхронизации установлено меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="591b0-796">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="591b0-797">Исправлена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке "От" отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="591b0-797">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="591b0-798">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="591b0-798">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="591b0-799">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="591b0-799">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="591b0-800">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="591b0-800">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="591b0-801">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="591b0-801">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="591b0-802">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="591b0-802">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="591b0-803">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="591b0-803">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="591b0-804">Устранена проблема, которая могла привести к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="591b0-804">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="591b0-805">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="591b0-805">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="591b0-806">Исправлена проблема, из-за которой пользователи не могли открывать некоторые вхождения повторяющихся элементов календаря.</span><span class="sxs-lookup"><span data-stu-id="591b0-806">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="591b0-807">Устранена проблема, из-за которой у пользователей с почтовыми ящиками на серверах Exchange 2010 возникали проблемы при добавлении вложений в элементы календаря.</span><span class="sxs-lookup"><span data-stu-id="591b0-807">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="591b0-808">Устранена проблема, из-за которой у пользователей возникали проблемы при ответе на сообщения с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="591b0-808">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="591b0-809">Исправлена проблема, из-за которой неожиданно обновлялось поле расположения в собраниях.</span><span class="sxs-lookup"><span data-stu-id="591b0-809">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="591b0-810">Устранена проблема, из-за которой запятые в поле местоположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="591b0-810">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="591b0-811">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="591b0-811">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="591b0-812">Решены вопросы, связанные со встречами и встречами, установленными в часовом поясе Бразилии.</span><span class="sxs-lookup"><span data-stu-id="591b0-812">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="591b0-813">Устранена проблема, из-за которой сообщения неожиданно отправлялись при нажатии клавиши "S" после закрытия панели проверки читаемости.</span><span class="sxs-lookup"><span data-stu-id="591b0-813">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="591b0-814">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="591b0-814">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="591b0-815">Устранена проблема, из-за которой веб-надстройки обращались к сообщениям, управляемым цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="591b0-815">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="591b0-816">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="591b0-816">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="591b0-817">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="591b0-817">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="591b0-818">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-818">PowerPoint</span></span>

- <span data-ttu-id="591b0-819">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="591b0-819">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="591b0-820">Устранена проблема, которая могла вызвать сбой при использовании контекстного меню в устаревших комментариях PPT.</span><span class="sxs-lookup"><span data-stu-id="591b0-820">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="591b0-821">Project</span><span class="sxs-lookup"><span data-stu-id="591b0-821">Project</span></span>

- <span data-ttu-id="591b0-822">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="591b0-822">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="591b0-823">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="591b0-823">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="591b0-824">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="591b0-824">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="591b0-825">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="591b0-825">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-826">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-826">Word</span></span>

- <span data-ttu-id="591b0-827">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="591b0-827">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="591b0-828">Диспетчер стандартных блоков может отображать неправильное оповещение: "Были изменены стили, стандартные блоки".</span><span class="sxs-lookup"><span data-stu-id="591b0-828">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-829">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-829">Office Suite</span></span>

- <span data-ttu-id="591b0-830">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="591b0-830">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="591b0-831">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="591b0-831">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="591b0-832">Исправлена ошибка в настройке ODT и крайнего срока обновления GPO, когда относительный крайний срок работает только при первом его включении, исправление включает относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="591b0-832">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="591b0-833">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="591b0-833">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="591b0-834">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="591b0-834">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="591b0-836">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="591b0-836">Version 1908: February 11</span></span>
<span data-ttu-id="591b0-837">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="591b0-837">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="591b0-838">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-840">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-840">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-841">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-841">Excel</span></span>

- <span data-ttu-id="591b0-842">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="591b0-842">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="591b0-843">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="591b0-843">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="591b0-844">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="591b0-844">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="591b0-845">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="591b0-845">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="591b0-846">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="591b0-846">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="591b0-847">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="591b0-847">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="591b0-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-848">Outlook</span></span>

- <span data-ttu-id="591b0-849">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="591b0-849">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="591b0-850">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="591b0-850">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="591b0-851">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="591b0-851">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="591b0-852">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="591b0-852">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="591b0-853">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="591b0-853">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="591b0-854">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="591b0-854">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="591b0-855">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="591b0-855">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="591b0-856">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-856">PowerPoint</span></span>

- <span data-ttu-id="591b0-857">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="591b0-857">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="591b0-858">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="591b0-858">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="591b0-859">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="591b0-859">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="591b0-860">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="591b0-860">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="591b0-861">Project</span><span class="sxs-lookup"><span data-stu-id="591b0-861">Project</span></span>

- <span data-ttu-id="591b0-862">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="591b0-862">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="591b0-863">Word</span><span class="sxs-lookup"><span data-stu-id="591b0-863">Word</span></span>

- <span data-ttu-id="591b0-864">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="591b0-864">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-865">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-865">Office Suite</span></span>

- <span data-ttu-id="591b0-866">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="591b0-866">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="591b0-868">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="591b0-868">Version 1908: January 14</span></span>
<span data-ttu-id="591b0-869">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="591b0-869">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="591b0-870">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="591b0-870">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="591b0-872">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="591b0-872">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="591b0-873">Excel</span><span class="sxs-lookup"><span data-stu-id="591b0-873">Excel</span></span>

- <span data-ttu-id="591b0-874">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="591b0-874">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="591b0-875">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="591b0-875">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="591b0-876">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытой надстройкой.</span><span class="sxs-lookup"><span data-stu-id="591b0-876">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="591b0-877">Outlook</span><span class="sxs-lookup"><span data-stu-id="591b0-877">Outlook</span></span>

- <span data-ttu-id="591b0-878">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="591b0-878">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="591b0-879">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="591b0-879">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="591b0-880">Исправлена проблема, вызывавшая у пользователей периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="591b0-880">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="591b0-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="591b0-881">PowerPoint</span></span>

- <span data-ttu-id="591b0-882">Исправлена проблема, из-за которой копирование слайда из одной презентации в другую могло создавать дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="591b0-882">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="591b0-883">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="591b0-883">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="591b0-884">Набор Office</span><span class="sxs-lookup"><span data-stu-id="591b0-884">Office Suite</span></span>

- <span data-ttu-id="591b0-885">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="591b0-885">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="591b0-886">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="591b0-886">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="591b0-887">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="591b0-887">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="591b0-889">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="591b0-889">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
