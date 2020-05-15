---
title: Заметки о выпусках Semi-Annual Channel в 2020 г.
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel для подписки "Приложения Microsoft 365" в 2020 г. для ИТ-специалистов.
ms.openlocfilehash: 6619411170491543c4853e6db56fa845a7adc6e3
ms.sourcegitcommit: fb97680a81c7d96b0f0f539dc3e3c8c28ad654e9
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/13/2020
ms.locfileid: "44222082"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="c75ab-103">Заметки о выпусках Semi-Annual Channel в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="c75ab-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="c75ab-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Semi-Annual Channel в 2020 г. для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="c75ab-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c75ab-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="c75ab-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="c75ab-106">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="c75ab-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="c75ab-107">OneNote 2016 включается по умолчанию, если пользователь, для которого применяется Semi-Annual Channel, скачивает "Приложения Microsoft 365" на портале Office и устанавливает в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c75ab-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-may-12"></a><span data-ttu-id="c75ab-109">Версия 1908: 12 мая</span><span class="sxs-lookup"><span data-stu-id="c75ab-109">Version 1908: May 12</span></span>
<span data-ttu-id="c75ab-110">*Версия 1908 (сборка 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-110">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="c75ab-111">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-113">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-113">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="c75ab-114">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-114">Excel</span></span>

- <span data-ttu-id="c75ab-115">При копировании данных, отфильтрованных по цвету, в столбец с другой шириной, значения не вставляются.</span><span class="sxs-lookup"><span data-stu-id="c75ab-115">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="c75ab-116">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="c75ab-116">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="c75ab-117">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="c75ab-117">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c75ab-118">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="c75ab-118">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c75ab-119">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="c75ab-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

### <a name="onenote"></a><span data-ttu-id="c75ab-120">OneNote</span><span class="sxs-lookup"><span data-stu-id="c75ab-120">OneNote</span></span>

- <span data-ttu-id="c75ab-121">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-121">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="c75ab-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-122">Outlook</span></span>

- <span data-ttu-id="c75ab-123">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="c75ab-123">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="c75ab-124">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="c75ab-124">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c75ab-125">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="c75ab-125">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c75ab-126">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="c75ab-126">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c75ab-127">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="c75ab-127">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c75ab-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="c75ab-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="c75ab-129">0 = по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="c75ab-129">0 = Default.</span></span>  <span data-ttu-id="c75ab-130">1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="c75ab-130">1 = we will only show the PolicyName for Retention policy text.</span></span>


### <a name="word"></a><span data-ttu-id="c75ab-131">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-131">Word</span></span>

- <span data-ttu-id="c75ab-132">Исправлена проблема с объединением двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="c75ab-132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c75ab-133">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="c75ab-133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-may-12"></a><span data-ttu-id="c75ab-135">Версия 1902: 12 мая</span><span class="sxs-lookup"><span data-stu-id="c75ab-135">Version 1902: May 12</span></span>
<span data-ttu-id="c75ab-136">*Версия 1902 (сборка 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="c75ab-137">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-139">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c75ab-140">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-140">Outlook</span></span>

- <span data-ttu-id="c75ab-141">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="c75ab-141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="c75ab-142">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="c75ab-142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c75ab-143">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="c75ab-143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c75ab-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="c75ab-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="c75ab-145">0 = по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="c75ab-145">0 = Default.</span></span>  <span data-ttu-id="c75ab-146">1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="c75ab-146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-may-04"></a><span data-ttu-id="c75ab-148">Версия 1908: 04 мая</span><span class="sxs-lookup"><span data-stu-id="c75ab-148">Version 1908: May 04</span></span>
<span data-ttu-id="c75ab-149">*Версия 1908 (сборка 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-149">*Version 1908 (Build 11929.20752)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-150">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-150">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c75ab-151">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c75ab-151">Office Suite</span></span>

- <span data-ttu-id="c75ab-152">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="c75ab-152">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="c75ab-153">Версия 1902: 04 мая</span><span class="sxs-lookup"><span data-stu-id="c75ab-153">Version 1902: May 04</span></span>
<span data-ttu-id="c75ab-154">*Версия 1902 (сборка 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-154">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-155">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-155">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c75ab-156">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c75ab-156">Office Suite</span></span>

- <span data-ttu-id="c75ab-157">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="c75ab-157">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-14"></a><span data-ttu-id="c75ab-158">Версия 1908: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="c75ab-158">Version 1908: April 14</span></span>
<span data-ttu-id="c75ab-159">*Версия 1908 (сборка 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-159">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="c75ab-160">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-162">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-162">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c75ab-163">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-163">Excel</span></span>

- <span data-ttu-id="c75ab-164">Исправлена проблема, приводившая к снижению производительности при удалении столбцов, содержащих объединенные ячейки.</span><span class="sxs-lookup"><span data-stu-id="c75ab-164">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="c75ab-165">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="c75ab-165">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="c75ab-166">Skype</span><span class="sxs-lookup"><span data-stu-id="c75ab-166">Skype</span></span>

- <span data-ttu-id="c75ab-167">Исправлено название вкладки беседы при наличии нескольких активных бесед.</span><span class="sxs-lookup"><span data-stu-id="c75ab-167">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="c75ab-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-168">Outlook</span></span>

- <span data-ttu-id="c75ab-169">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при закрытии Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-169">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="c75ab-170">Исправлена проблема, приводившая к отображению пустого списка помещений в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="c75ab-170">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c75ab-171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c75ab-171">PowerPoint</span></span>

- <span data-ttu-id="c75ab-172">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="c75ab-172">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="c75ab-173">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-173">Word</span></span>

- <span data-ttu-id="c75ab-174">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="c75ab-174">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="c75ab-175">Версия 1902: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="c75ab-175">Version 1902: April 14</span></span>
<span data-ttu-id="c75ab-176">*Версия 1902 (сборка 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-176">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="c75ab-177">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-march-10"></a><span data-ttu-id="c75ab-179">Версия 1908: 10 марта</span><span class="sxs-lookup"><span data-stu-id="c75ab-179">Version 1908: March 10</span></span>
<span data-ttu-id="c75ab-180">*Версия 1908 (сборка 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-180">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="c75ab-181">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-181">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-183">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-183">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c75ab-184">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-184">Excel</span></span>

- <span data-ttu-id="c75ab-185">Исправлена проблема, из-за которой у некоторых пользователей появлялось несколько всплывающих окон при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="c75ab-185">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="c75ab-186">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="c75ab-186">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="c75ab-187">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="c75ab-187">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c75ab-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c75ab-188">PowerPoint</span></span>

- <span data-ttu-id="c75ab-189">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="c75ab-189">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="c75ab-190">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-190">Word</span></span>

- <span data-ttu-id="c75ab-191">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="c75ab-191">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c75ab-192">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c75ab-192">Office Suite</span></span>

- <span data-ttu-id="c75ab-193">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="c75ab-193">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="c75ab-194">Версия 1902: 10 марта</span><span class="sxs-lookup"><span data-stu-id="c75ab-194">Version 1902: March 10</span></span>
<span data-ttu-id="c75ab-195">*Версия 1902 (сборка 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-195">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="c75ab-196">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="c75ab-198">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="c75ab-198">Version 1908: February 11</span></span>
<span data-ttu-id="c75ab-199">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-199">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="c75ab-200">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-202">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c75ab-203">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-203">Excel</span></span>

- <span data-ttu-id="c75ab-204">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-204">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="c75ab-205">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="c75ab-205">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="c75ab-206">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="c75ab-206">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c75ab-207">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="c75ab-207">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="c75ab-208">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="c75ab-208">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="c75ab-209">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="c75ab-209">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="c75ab-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-210">Outlook</span></span>

- <span data-ttu-id="c75ab-211">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="c75ab-211">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c75ab-212">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="c75ab-212">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="c75ab-213">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-213">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="c75ab-214">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="c75ab-214">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="c75ab-215">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="c75ab-215">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="c75ab-216">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="c75ab-216">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="c75ab-217">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="c75ab-217">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c75ab-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c75ab-218">PowerPoint</span></span>

- <span data-ttu-id="c75ab-219">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="c75ab-219">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="c75ab-220">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-220">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="c75ab-221">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="c75ab-221">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="c75ab-222">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-222">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c75ab-223">Project</span><span class="sxs-lookup"><span data-stu-id="c75ab-223">Project</span></span>

- <span data-ttu-id="c75ab-224">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="c75ab-224">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="c75ab-225">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-225">Word</span></span>

- <span data-ttu-id="c75ab-226">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="c75ab-226">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c75ab-227">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c75ab-227">Office Suite</span></span>

- <span data-ttu-id="c75ab-228">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="c75ab-228">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-february-11"></a><span data-ttu-id="c75ab-230">Версия 1902: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="c75ab-230">Version 1902: February 11</span></span>
<span data-ttu-id="c75ab-231">*Версия 1902 (сборка 11328,20526)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-231">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="c75ab-232">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-232">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-234">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c75ab-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-235">Outlook</span></span>

- <span data-ttu-id="c75ab-236">Решает проблему, из-за которой пользователи сталкивались с алгоритмом шифрования, не поддерживаются ошибки при отправке зашифрованных писем.</span><span class="sxs-lookup"><span data-stu-id="c75ab-236">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="c75ab-237">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-237">Word</span></span>

- <span data-ttu-id="c75ab-238">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="c75ab-238">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-1808-february-11"></a><span data-ttu-id="c75ab-241">Версия 1808: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="c75ab-241">Version 1808: February 11</span></span>
<span data-ttu-id="c75ab-242">*Версия 1808 (сборка 10730,20438)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-242">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="c75ab-243">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-243">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="c75ab-245">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="c75ab-245">Version 1908: January 14</span></span>
<span data-ttu-id="c75ab-246">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-246">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="c75ab-247">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-247">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c75ab-249">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c75ab-249">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c75ab-250">Access</span><span class="sxs-lookup"><span data-stu-id="c75ab-250">Access</span></span>

- <span data-ttu-id="c75ab-251">**Отслеживание объектов базы данных.** Не теряйте из виду активную вкладку, легко перетаскивайте вкладки для изменения их порядка и закрывайте объекты базы данных одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="c75ab-251">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="c75ab-252">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="c75ab-252">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c75ab-253">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="c75ab-253">Switching between them has never been easier.</span></span> [<span data-ttu-id="c75ab-254">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-254">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c75ab-255">**Изменение масштаба стало удобнее.** Увеличивайте поле масштаба и меняйте шрифт — все эти параметры сохранятся.</span><span class="sxs-lookup"><span data-stu-id="c75ab-255">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="c75ab-256">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-256">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="c75ab-257">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-257">Excel</span></span>

- <span data-ttu-id="c75ab-258">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="c75ab-258">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c75ab-259">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="c75ab-259">Switching between them has never been easier.</span></span> [<span data-ttu-id="c75ab-260">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-260">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c75ab-261">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="c75ab-261">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c75ab-262">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="c75ab-262">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c75ab-263">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="c75ab-263">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c75ab-264">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="c75ab-264">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c75ab-265">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="c75ab-265">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c75ab-266">**Добавление живых красок в таблицы.** Вставляйте в книгу анимированные трехмерные изображения, чтобы показать, как бьется сердце, вращается планета или рычит тираннозавр.</span><span class="sxs-lookup"><span data-stu-id="c75ab-266">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="c75ab-267">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-267">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="c75ab-p111">**Узнайте больше о своих данных.** Новая кнопка "Идеи" позволяет находить закономерности в данных и предлагает интеллектуальные, индивидуальные решения на их основе. [Подробнее](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p111">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="c75ab-270">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-270">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="c75ab-271">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="c75ab-271">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="c75ab-272">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-272">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="c75ab-273">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="c75ab-273">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="c75ab-274">Также можно легко находить функции, столбцы и параметры.</span><span class="sxs-lookup"><span data-stu-id="c75ab-274">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="c75ab-275">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="c75ab-275">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c75ab-276">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="c75ab-276">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c75ab-277">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-277">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="c75ab-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-278">Outlook</span></span>

- <span data-ttu-id="c75ab-279">**Мы обновили интерфейс Outlook для вас.** Упрощенный интерфейс, ранее доступный для предпросмотра с помощью функции "Ожидается в ближайшее время", чтобы вы могли сосредоточиться на самом важном.</span><span class="sxs-lookup"><span data-stu-id="c75ab-279">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="c75ab-280">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-280">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="c75ab-281">**Упрощенная лента с возможностью настройки.** Наслаждайтесь одной упрощенной строкой, содержащей наиболее часто используемые кнопки.</span><span class="sxs-lookup"><span data-stu-id="c75ab-281">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="c75ab-282">Легко переключайтесь между классическим и упрощенным представлением, а также закрепляйте и открепляйте команды.</span><span class="sxs-lookup"><span data-stu-id="c75ab-282">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="c75ab-283">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-283">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="c75ab-284">**Продолжение работы при перемещении сообщений.** Outlook теперь перемещает сообщения в фоновом режиме, чтобы вы могли продолжать работу во время перемещения большого количества сообщений между папками.</span><span class="sxs-lookup"><span data-stu-id="c75ab-284">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="c75ab-285">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время окончания собрания на 5–10 минут раньше по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="c75ab-285">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="c75ab-286">**Выбор избранного действия.** Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="c75ab-286">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="c75ab-287">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="c75ab-287">How about Archive or Mark as Read?</span></span> <span data-ttu-id="c75ab-288">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="c75ab-288">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="c75ab-p118">**Все смогут понять, что вы имели в виду.** Если текста или статических изображений недостаточно, воспользуйтесь файлами GIF с анимацией, чтобы донести свою идею. [Подробнее](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="c75ab-291">**Быстрое добавление учетных записей.** Благодаря улучшениям в настройке учетных записей теперь еще проще добавлять учетные записи Outlook.com и Gmail, использующие 2-факторную проверку подлинности в Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-291">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="c75ab-292">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-292">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="c75ab-293">**Забудьте об ограничениях синхронизации.** Улучшения Outlook устраняют ограничение для папок, позволяя синхронизировать общие почтовые ящики.</span><span class="sxs-lookup"><span data-stu-id="c75ab-293">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="c75ab-294">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="c75ab-294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c75ab-295">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="c75ab-295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c75ab-296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="c75ab-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c75ab-297">PowerPoint</span></span>

- <span data-ttu-id="c75ab-298">**Улучшенное изменение формы.** Назовите свои фигуры, чтобы лучше управлять их трансформацией.</span><span class="sxs-lookup"><span data-stu-id="c75ab-298">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="c75ab-299">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-299">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="c75ab-300">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="c75ab-300">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c75ab-301">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="c75ab-301">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c75ab-302">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="c75ab-302">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c75ab-303">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="c75ab-303">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c75ab-304">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="c75ab-304">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c75ab-305">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="c75ab-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c75ab-306">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="c75ab-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="c75ab-307">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c75ab-308">**Новое расположение для видео из Интернета.** Сохраняйте видео в Microsoft Stream, чтобы его могли просматривать все пользователи организации.</span><span class="sxs-lookup"><span data-stu-id="c75ab-308">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="c75ab-309">Вставьте ссылку на видео и наслаждайтесь мультимедийной презентацией, размер которой составляет лишь часть от размера файла.</span><span class="sxs-lookup"><span data-stu-id="c75ab-309">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="c75ab-310">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-310">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="c75ab-311">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="c75ab-311">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c75ab-p126">**Тест или опрос для аудитории.** Добавьте на слайд тест или опрос. Набор Office соберет и сохранит все ответы. [Подробнее](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p126">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="c75ab-p127">**Вставлять видео из Интернета стало еще проще.** Хотите разместить на своем слайде видео из Vimeo или YouTube? Вам потребуется лишь ссылка на страницу с видео. [Подробнее](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p127">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="c75ab-318">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="c75ab-318">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c75ab-319">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="c75ab-319">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c75ab-320">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-320">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="c75ab-321">Project</span><span class="sxs-lookup"><span data-stu-id="c75ab-321">Project</span></span>

- <span data-ttu-id="c75ab-322">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="c75ab-322">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c75ab-323">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="c75ab-323">Switching between them has never been easier.</span></span> [<span data-ttu-id="c75ab-324">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-324">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="c75ab-325">Visio</span><span class="sxs-lookup"><span data-stu-id="c75ab-325">Visio</span></span>

- <span data-ttu-id="c75ab-326">**Экспорт схем процессов в Word.** Автоматически добавляйте содержимое схем, например фигуры и метаданные, в документ Word.</span><span class="sxs-lookup"><span data-stu-id="c75ab-326">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="c75ab-327">Затем настройте документ для создания руководств по обработке и использованию.</span><span class="sxs-lookup"><span data-stu-id="c75ab-327">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="c75ab-328">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-328">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="c75ab-329">**Переосмысление блок-схем данных.** Замечательные новые макеты для блок-схем визуализатора данных просты, лаконичны и удобны для понимания.</span><span class="sxs-lookup"><span data-stu-id="c75ab-329">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="c75ab-330">Для выбора перейдите на вкладку "Конструктор".</span><span class="sxs-lookup"><span data-stu-id="c75ab-330">Click the Design tab for options.</span></span>

- <span data-ttu-id="c75ab-331">**Встроенные наборы элементов Azure.** Разрабатывайте облачное приложение или планируйте архитектуру с помощью множества наборов элементов Azure.</span><span class="sxs-lookup"><span data-stu-id="c75ab-331">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="c75ab-332">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-332">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="c75ab-p133">**Попрощайтесь с неработающими ссылками Excel.** Не удается найти книгу Excel, связанную со схемой визуализатора данных? Свяжите ее повторно и продолжайте работу. [Подробнее](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="c75ab-336">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="c75ab-336">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c75ab-337">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="c75ab-337">Switching between them has never been easier.</span></span> [<span data-ttu-id="c75ab-338">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-338">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c75ab-339">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="c75ab-339">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="c75ab-340">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-340">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="c75ab-341">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-341">Word</span></span>

- <span data-ttu-id="c75ab-342">**Поддержка дополнительных цветов страниц в режиме средств обучения.** Теперь средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-342">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="c75ab-343">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="c75ab-343">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="c75ab-p137">**Естественное редактирование с помощью Правок от руки.** Разделяйте и объединяйте слова, добавляйте новые строки и вставляйте текст одним движением пера. [Подробнее](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p137">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="c75ab-p138">**Преобразуйте статические документы.** Преобразуйте документы в интерактивные веб-страницы, которые прекрасно выглядят на любом устройстве и которыми легко делиться. [Подробнее](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p138">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="c75ab-348">**Расширение доступа к содержимому.** Нужно сделать документы доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="c75ab-348">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="c75ab-349">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="c75ab-349">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c75ab-350">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="c75ab-350">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c75ab-351">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="c75ab-351">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c75ab-352">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="c75ab-352">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c75ab-353">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="c75ab-353">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c75ab-354">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="c75ab-354">Switching between them has never been easier.</span></span> [<span data-ttu-id="c75ab-355">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-355">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c75ab-p142">**Улучшение восприятия с помощью выделения строк.** Перемещайтесь по документу построчно, ни на что не отвлекаясь. Настройте выделение одной, трех или пяти строк одновременно. [Подробнее](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="c75ab-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="c75ab-359">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="c75ab-359">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c75ab-360">**Привлечение внимания с помощью \@@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="c75ab-360">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="c75ab-361">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-361">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="c75ab-362">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="c75ab-362">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c75ab-363">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="c75ab-363">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c75ab-364">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-364">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="c75ab-365">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c75ab-365">Office Suite</span></span>

- <span data-ttu-id="c75ab-366">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="c75ab-366">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c75ab-367">Просто воспользуйтесь полем поиска на вкладке "Файл" > "Открыть", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="c75ab-367">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="c75ab-368">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="c75ab-368">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c75ab-369">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="c75ab-369">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="c75ab-370">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-370">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="c75ab-371">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="c75ab-371">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="c75ab-372">**Установка Microsoft Teams.** Microsoft Teams по умолчанию устанавливается для существующих экземпляров Office 365 профессиональный плюс.</span><span class="sxs-lookup"><span data-stu-id="c75ab-372">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="c75ab-373">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c75ab-373">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-376">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-376">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c75ab-377">Access</span><span class="sxs-lookup"><span data-stu-id="c75ab-377">Access</span></span>

- <span data-ttu-id="c75ab-378">Это обновление исправляет проблему, из-за которой агрегатная функция, например, Sum, может обрезать результат до целого значения.</span><span class="sxs-lookup"><span data-stu-id="c75ab-378">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="c75ab-379">Это обновление исправляет проблему, из-за которой запрос на объединение, включающий ссылки на удаленные таблицы (например, таблицы SQL Server), может приводить к закрытию и перезапуску Access.</span><span class="sxs-lookup"><span data-stu-id="c75ab-379">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="c75ab-380">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке &quot;Запрос поврежден&quot; при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="c75ab-380">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c75ab-381">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-381">Excel</span></span>

- <span data-ttu-id="c75ab-382">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="c75ab-382">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="c75ab-383">Устранена проблема в Excel, из-за которой при выполнении макросов, присвоенных фигурам или элементам управления формы, выводятся неправильные сообщения об ошибке или эти макросы работают в неправильном целевом диапазоне.</span><span class="sxs-lookup"><span data-stu-id="c75ab-383">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="c75ab-384">Решена проблема, при которой содержимое диалогового окна "Поиск и замена" изменялось, если курсор находился в нем после нахождения первого элемента.</span><span class="sxs-lookup"><span data-stu-id="c75ab-384">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="c75ab-385">Исправлена проблема, из-за которой изменение способа сортировки сводной таблицы и ее обновление в сеансе совместного редактирования с другими пользователями могло приводить к сбою.</span><span class="sxs-lookup"><span data-stu-id="c75ab-385">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="c75ab-386">Исправлена проблема, при которой для фильтра сводной таблицы OLAP было задано значение, удаленное из куба.</span><span class="sxs-lookup"><span data-stu-id="c75ab-386">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="c75ab-387">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм.</span><span class="sxs-lookup"><span data-stu-id="c75ab-387">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="c75ab-388">Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="c75ab-388">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="c75ab-389">Устранена проблема, приводившая к нарушению синхронизации каскадных и воронкообразных диаграмм с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="c75ab-389">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="c75ab-390">Исправлена проблема с конфликтом слияния в Excel, из-за которой пользователям предлагалось повторно открыть книгу, чтобы внести изменения.</span><span class="sxs-lookup"><span data-stu-id="c75ab-390">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="c75ab-391">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="c75ab-391">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c75ab-392">Исправлена проблема, которая была причиной ошибки времени выполнения макроса при активации свернутых окон.</span><span class="sxs-lookup"><span data-stu-id="c75ab-392">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="c75ab-393">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="c75ab-393">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c75ab-394">Устранена проблема, из-за которой вырезание и вставка в таблице не выполняются при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="c75ab-394">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="c75ab-395">Решена проблема, вызывавшая прерывание совместного редактирования при изменении настраиваемых свойств с помощью макросов.</span><span class="sxs-lookup"><span data-stu-id="c75ab-395">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="c75ab-396">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытом надстройкой.</span><span class="sxs-lookup"><span data-stu-id="c75ab-396">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="c75ab-397">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="c75ab-397">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c75ab-398">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="c75ab-398">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="c75ab-399">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="c75ab-399">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="c75ab-400">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="c75ab-400">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c75ab-401">Исправлена проблема, из-за которой функция Lookup может возвращать ошибку.</span><span class="sxs-lookup"><span data-stu-id="c75ab-401">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="c75ab-402">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office.</span><span class="sxs-lookup"><span data-stu-id="c75ab-402">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="c75ab-403">Проблема низкой производительности при нажатии кнопки "Цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="c75ab-403">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="c75ab-404">Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати.</span><span class="sxs-lookup"><span data-stu-id="c75ab-404">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="c75ab-405">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="c75ab-405">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c75ab-406">Значительно повышена производительность фильтрации по цвету.</span><span class="sxs-lookup"><span data-stu-id="c75ab-406">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="c75ab-407">Устранена проблема, мешавшая вставке гиперссылок в некоторых защищенных листах.</span><span class="sxs-lookup"><span data-stu-id="c75ab-407">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="c75ab-408">Поддерживается отображение более 16 надстроек при просмотре в диспетчере надстроек.</span><span class="sxs-lookup"><span data-stu-id="c75ab-408">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="c75ab-409">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="c75ab-409">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c75ab-410">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="c75ab-410">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c75ab-411">Это обновление устраняет ошибку, из-за которой документы Office могут не отправляться в OneDrive для бизнеса и приходит сообщение "Не удалось выполнить отправку".</span><span class="sxs-lookup"><span data-stu-id="c75ab-411">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="c75ab-412">Устранена проблема в функции "Идеи" для Excel, приводившая к ошибке при загрузке надстройки путем нажатия на кнопку "Идеи" в клиенте Win32.</span><span class="sxs-lookup"><span data-stu-id="c75ab-412">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="c75ab-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-413">Outlook</span></span>

- <span data-ttu-id="c75ab-414">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="c75ab-414">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c75ab-415">Исправлена проблема, из-за которой обновление в почтовых ящиках пользователей обычной проверки подлинности до современной приводило к привязыванию неправильной учетной записи к профилю Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-415">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="c75ab-416">Исправлена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами, когда это не предполагалось.</span><span class="sxs-lookup"><span data-stu-id="c75ab-416">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="c75ab-417">Исправлена проблема, из-за которой URL-адреса не открывались при простом наведении на некоторые безопасные ссылки.</span><span class="sxs-lookup"><span data-stu-id="c75ab-417">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="c75ab-418">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="c75ab-418">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c75ab-419">Исправлена проблема, из-за которой у подмножества пользователей POP3 сообщения электронной почты выводятся в виде обычного текста, независимо от настроек.</span><span class="sxs-lookup"><span data-stu-id="c75ab-419">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="c75ab-420">Это исправление восстановит сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="c75ab-420">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="c75ab-421">Решена проблема, из-за которой возникала ошибка доступа при копировании элементов из основного календаря в календарь группы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-421">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="c75ab-422">Исправлена проблема, из-за которой пользователям были недоступны предложения расположений при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="c75ab-422">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="c75ab-423">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="c75ab-423">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c75ab-424">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-424">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c75ab-425">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="c75ab-425">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c75ab-426">Решена проблема, вызывавшая сбой в Outlook при взаимодействии пользователей с определенными безопасными ссылками.</span><span class="sxs-lookup"><span data-stu-id="c75ab-426">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="c75ab-427">Исправлена проблема, из-за которой менеджеры не могли установить, ответил ли участник на предоставленное приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="c75ab-427">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="c75ab-428">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="c75ab-428">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c75ab-429">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="c75ab-429">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c75ab-430">Это изменение позволяет администраторам включать политику, предпочитающую указанную учетную запись электронной почты в запросах проверки подлинности службы автообнаружения вместо имени участника-пользователя (UPN).</span><span class="sxs-lookup"><span data-stu-id="c75ab-430">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="c75ab-431">По умолчанию при автообнаружении предпочтение отдается UPN учетной записи (при наличии).</span><span class="sxs-lookup"><span data-stu-id="c75ab-431">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="c75ab-432">Исправлена проблема, вызывавшая сбой поиска в современных группах.</span><span class="sxs-lookup"><span data-stu-id="c75ab-432">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="c75ab-433">Исправлена проблема, приводившая к зависанию пользователей Outlook в состоянии "Требуется пароль" в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="c75ab-433">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="c75ab-434">Исправлена проблема, из-за которой пользователям предлагались помещения для собраний, проводимых в период времени, когда эти помещения недоступны.</span><span class="sxs-lookup"><span data-stu-id="c75ab-434">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="c75ab-435">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="c75ab-435">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="c75ab-436">Исправлена проблема для неанглоязычных пользователей, из-за которой строка темы в почте отображалась очень маленькой.</span><span class="sxs-lookup"><span data-stu-id="c75ab-436">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="c75ab-437">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="c75ab-437">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="c75ab-438">Исправлена проблема, приводившая к сбою при попытке пользователей создать правило на основе сообщения о пропущенной беседе.</span><span class="sxs-lookup"><span data-stu-id="c75ab-438">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="c75ab-439">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="c75ab-439">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c75ab-440">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="c75ab-440">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="c75ab-441">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-441">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c75ab-442">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="c75ab-442">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="c75ab-443">Устранена проблема, которая приводила к периодическому сбою поиска в текущей папке.</span><span class="sxs-lookup"><span data-stu-id="c75ab-443">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="c75ab-444">Исправлена проблема, из-за которой некоторые пользователи сталкивались с ошибками проверки подлинности при попытке получить свои облачные параметры для Outlook.</span><span class="sxs-lookup"><span data-stu-id="c75ab-444">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="c75ab-445">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="c75ab-445">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c75ab-446">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="c75ab-446">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c75ab-447">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="c75ab-447">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c75ab-448">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c75ab-448">PowerPoint</span></span>

- <span data-ttu-id="c75ab-449">Устранена проблема, из-за которой некоторые надстройки создавали непредвиденные ошибки вокруг фигур в диаграммах.</span><span class="sxs-lookup"><span data-stu-id="c75ab-449">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="c75ab-450">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="c75ab-450">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c75ab-451">Это изменение восстанавливает доступное имя для элементов управления видео в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-451">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="c75ab-452">Исправлена проблема, из-за которой мог блокироваться запуск некоторых анимаций.</span><span class="sxs-lookup"><span data-stu-id="c75ab-452">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="c75ab-453">Исправлена проблема, из-за которой при копировании слайда из одной презентации в другую могли появляться дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="c75ab-453">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="c75ab-454">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="c75ab-454">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="c75ab-455">Исправление проблем с надежностью. Устранена проблема, из-за которой надстройка стороннего поставщика могла вызывать сбой PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-455">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="c75ab-456">Исправлена проблема, из-за которой не удавалось правильно повернуть полуширинные знаки катаканы при использовании вертикальных текстовых полей в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-456">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c75ab-457">Project</span><span class="sxs-lookup"><span data-stu-id="c75ab-457">Project</span></span>

- <span data-ttu-id="c75ab-458">Исправлена проблема, чтобы разрешить пользователям в Windows 7 открывать проекты из Project Web App и сайтов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-458">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="c75ab-459">Обнаружена проблема, из-за которой пользователи могли получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="c75ab-459">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="c75ab-460">Команда "Выровнять все" не устраняет должным образом превышение доступности ресурсов.</span><span class="sxs-lookup"><span data-stu-id="c75ab-460">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="c75ab-461">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="c75ab-461">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="c75ab-462">Visio</span><span class="sxs-lookup"><span data-stu-id="c75ab-462">Visio</span></span>

- <span data-ttu-id="c75ab-463">Экспорт в формате SVG из Visio не работал для различных фигур.</span><span class="sxs-lookup"><span data-stu-id="c75ab-463">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="c75ab-464">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-464">Word</span></span>

- <span data-ttu-id="c75ab-465">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="c75ab-465">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="c75ab-466">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="c75ab-466">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c75ab-467">Исправлена проблема, из-за которой могли возникать проблемы с масштабированием при печати на принтерах Deskjet.</span><span class="sxs-lookup"><span data-stu-id="c75ab-467">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="c75ab-468">Исправлена проблема с отслеживанием изменений, которые иногда переходят в режим бесконечного цикла. </span><span class="sxs-lookup"><span data-stu-id="c75ab-468">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="c75ab-469">Исправлены различные проблемы, из-за которых приложение может зависнуть при завершении работы.</span><span class="sxs-lookup"><span data-stu-id="c75ab-469">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="c75ab-470">Также исправлены некоторые ошибки, связанные с надстройками.</span><span class="sxs-lookup"><span data-stu-id="c75ab-470">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c75ab-471">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c75ab-471">Office Suite</span></span>

- <span data-ttu-id="c75ab-472">Исправлена проблема с неправильным определением названия новой эры "Рэйва" в хирагана и кандзи как выражения с опечаткой или грамматической ошибкой.</span><span class="sxs-lookup"><span data-stu-id="c75ab-472">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="c75ab-473">Исправлена проблема, из-за которой пользователи получали сообщение "Не удалось предоставить общий доступ" при попытке поделиться файлами, хранящимися в SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="c75ab-473">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="c75ab-474">Исправлена проблема, которая могла приводить к потере данных в сеансах, включающих как совместное редактирование, так и редактирование в автономном режиме в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-474">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="c75ab-475">Исправлена проблема, из-за которой мог произойти сбой при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="c75ab-475">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="c75ab-476">Исправление позволяет пользователям PowerPoint избежать ошибки при попытке онлайн-презентации.</span><span class="sxs-lookup"><span data-stu-id="c75ab-476">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="c75ab-477">В некоторых случаях файл SharePoint, сохраненный с помощью модуля синхронизации, отображал состояние "Сохранено", но в действительности изменения не сохранялись. Это приводило к потере данных.</span><span class="sxs-lookup"><span data-stu-id="c75ab-477">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="c75ab-478">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c75ab-478">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="c75ab-479">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как диалоговое окно", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="c75ab-479">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="c75ab-480">Устранена проблема с быстродействием Win7, из-за которой вставленная коллекция фигур с ленты во всех приложениях отображалась примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="c75ab-480">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="c75ab-481">Исправлена ошибка, из-за которой сведения о специальных возможностях не отображались в области сведений представления Backstage.</span><span class="sxs-lookup"><span data-stu-id="c75ab-481">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="c75ab-482">Повышена надежность процесса обновления Office в отношении целостности реестра.</span><span class="sxs-lookup"><span data-stu-id="c75ab-482">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="c75ab-483">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="c75ab-483">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c75ab-484">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="c75ab-484">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c75ab-485">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="c75ab-485">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="c75ab-486">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="c75ab-486">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="c75ab-487">При определенных обстоятельствах ярлыки Office могут исчезнуть после обновления.</span><span class="sxs-lookup"><span data-stu-id="c75ab-487">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="c75ab-488">Это обновление повышает надежность при публикации ярлыков Office.</span><span class="sxs-lookup"><span data-stu-id="c75ab-488">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="c75ab-489">Исправлена проблема, из-за которой обновления могли неожиданно блокироваться в сетях с лимитным тарифным планом.</span><span class="sxs-lookup"><span data-stu-id="c75ab-489">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="c75ab-490">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="c75ab-490">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c75ab-491">Повышена надежность при скачивании обновлений Office путем продолжения скачивания, которое ранее могло прерываться.</span><span class="sxs-lookup"><span data-stu-id="c75ab-491">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="c75ab-492">Устранены проблемы, связанные со свойством автоподбора размера текстовых полей и фигур в сторонних подключаемых модулях.</span><span class="sxs-lookup"><span data-stu-id="c75ab-492">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="c75ab-493">Исправлена проблема, из-за которой крупные представления в виде дерева приводили к сбою.</span><span class="sxs-lookup"><span data-stu-id="c75ab-493">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="c75ab-494">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="c75ab-494">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-january-14"></a><span data-ttu-id="c75ab-496">Версия 1902: 14 января</span><span class="sxs-lookup"><span data-stu-id="c75ab-496">Version 1902: January 14</span></span>
<span data-ttu-id="c75ab-497">*Версия 1902 (сборка 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-497">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="c75ab-498">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-498">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c75ab-500">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c75ab-500">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c75ab-501">Excel</span><span class="sxs-lookup"><span data-stu-id="c75ab-501">Excel</span></span>

- <span data-ttu-id="c75ab-502">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="c75ab-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c75ab-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="c75ab-503">Outlook</span></span>

- <span data-ttu-id="c75ab-504">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="c75ab-504">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c75ab-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c75ab-505">PowerPoint</span></span>

- <span data-ttu-id="c75ab-506">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="c75ab-506">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="c75ab-507">Word</span><span class="sxs-lookup"><span data-stu-id="c75ab-507">Word</span></span>

- <span data-ttu-id="c75ab-508">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="c75ab-508">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1808-january-14"></a><span data-ttu-id="c75ab-510">Версия 1808: 14 января</span><span class="sxs-lookup"><span data-stu-id="c75ab-510">Version 1808: January 14</span></span>
<span data-ttu-id="c75ab-511">*Версия 1808 (сборка 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="c75ab-511">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="c75ab-512">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c75ab-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="c75ab-514">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="c75ab-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
