---
title: Заметки о выпусках Полугодового канала (корпоративный) в 2020 г.
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel для подписки "Приложения Microsoft 365" в 2020 г. для ИТ-специалистов.
ms.openlocfilehash: f7f3b39521132fb11226bc512f782e0adec5aba8
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453417"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="b6191-103">Заметки о выпусках Полугодового канала (корпоративный) в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="b6191-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="b6191-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (корпоративный) в 2020 г. для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="b6191-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="b6191-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="b6191-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="b6191-106">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="b6191-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="b6191-107">OneNote 2016 включается по умолчанию, если пользователь, для которого применяется Полугодовой канал (корпоративный), скачивает "Приложения Microsoft 365" на портале Office и устанавливает в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6191-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-october-13"></a><span data-ttu-id="b6191-109">Версия 2002: 13 октября</span><span class="sxs-lookup"><span data-stu-id="b6191-109">Version 2002: October 13</span></span>
<span data-ttu-id="b6191-110">*Версия 2002 (сборка 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="b6191-110">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="b6191-111">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-113">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-113">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b6191-114">Access</span><span class="sxs-lookup"><span data-stu-id="b6191-114">Access</span></span>

- <span data-ttu-id="b6191-115">Больше не должно появляться сообщение "Слишком сложный запрос" или ошибка о превышении ресурсов системы в 64-разрядной версии Access, если вы соблюдаете рекомендации и требования к базам данных Access.</span><span class="sxs-lookup"><span data-stu-id="b6191-115">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="b6191-116">Если вы примените функцию фильтрации после конструктора запросов, в базе данных больше не должен возникать сбой.</span><span class="sxs-lookup"><span data-stu-id="b6191-116">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="b6191-117">Выполните соответствующую проверку.</span><span class="sxs-lookup"><span data-stu-id="b6191-117">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="b6191-118">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-118">Excel</span></span>

- <span data-ttu-id="b6191-119">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="b6191-119">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b6191-120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-120">PowerPoint</span></span>

- <span data-ttu-id="b6191-121">Новые презентации, созданные из шаблона, могли наследовать параметр, мешавший удобному совместному редактированию.</span><span class="sxs-lookup"><span data-stu-id="b6191-121">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="b6191-122">Это исправление обеспечивает очистку этого параметра для данного случая.</span><span class="sxs-lookup"><span data-stu-id="b6191-122">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="b6191-123">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-123">Word</span></span>

- <span data-ttu-id="b6191-124">Исправлена проблема, из-за которой при открытии документов с разрывами страниц и столбцами могло появляться сообщение об ошибке "Превышено число страниц, максимально допустимое для приложения Microsoft Word или данный документ поврежден"</span><span class="sxs-lookup"><span data-stu-id="b6191-124">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="b6191-125">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="b6191-125">Office Suite</span></span>

- <span data-ttu-id="b6191-126">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="b6191-126">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="b6191-127">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="b6191-127">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-october-13"></a><span data-ttu-id="b6191-129">Версия 1908: 13 октября</span><span class="sxs-lookup"><span data-stu-id="b6191-129">Version 1908: October 13</span></span>
<span data-ttu-id="b6191-130">*Версия 1908 (сборка 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="b6191-130">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="b6191-131">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-131">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-133">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-133">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b6191-134">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="b6191-134">Office Suite</span></span>

- <span data-ttu-id="b6191-135">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="b6191-135">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="b6191-136">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="b6191-136">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-september-08"></a><span data-ttu-id="b6191-138">Версия 2002: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="b6191-138">Version 2002: September 08</span></span>
<span data-ttu-id="b6191-139">*Версия 2002 (сборка 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="b6191-139">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="b6191-140">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-140">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-142">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-142">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-143">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-143">Excel</span></span>

- <span data-ttu-id="b6191-144">Это устраняет проблему, из-за которой при подключениях, созданных поставщиком данных SQL в более ранних версиях Office, параметры внутренних таблиц задавались не так, как в Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6191-144">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="b6191-145">Это приводит к отключению раскрывающегося списка "Просмотр таблиц" или "Редактор запросов" для файлов с подключениями, созданными в более ранних версиях Office, когда они открывались с помощью Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6191-145">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="b6191-146">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="b6191-146">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="b6191-147">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-147">Outlook</span></span>

- <span data-ttu-id="b6191-148">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="b6191-148">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b6191-149">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-149">Office Suite</span></span>

- <span data-ttu-id="b6191-150">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="b6191-150">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-september-08"></a><span data-ttu-id="b6191-152">Версия 1908: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="b6191-152">Version 1908: September 08</span></span>
<span data-ttu-id="b6191-153">*Версия 1908 (сборка 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="b6191-153">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="b6191-154">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="b6191-155">Версия 2002: 11 августа</span><span class="sxs-lookup"><span data-stu-id="b6191-155">Version 2002: August 11</span></span>
<span data-ttu-id="b6191-156">*Версия 2002 (сборка 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="b6191-156">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="b6191-157">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-157">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-159">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-159">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-160">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-160">Excel</span></span>

- <span data-ttu-id="b6191-161">Исправлена проблема, не позволявшая переключиться на редактирование файлов, открытых с использованием параметра "Рекомендовать доступ только для чтения".</span><span class="sxs-lookup"><span data-stu-id="b6191-161">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="b6191-162">OneNote</span><span class="sxs-lookup"><span data-stu-id="b6191-162">OneNote</span></span>

- <span data-ttu-id="b6191-163">Удалены лишние вызовы удостоверений, чтобы сократить использование ресурсов</span><span class="sxs-lookup"><span data-stu-id="b6191-163">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="b6191-164">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="b6191-164">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="b6191-165">Улучшена функция обнаружения ошибок и качество синхронизации.</span><span class="sxs-lookup"><span data-stu-id="b6191-165">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-166">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-166">Outlook</span></span>

- <span data-ttu-id="b6191-167">Исправлена ошибка, вызывавшая серьезную проблему с производительностью при запуске Outlook для некоторых клиентов.</span><span class="sxs-lookup"><span data-stu-id="b6191-167">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="b6191-168">Skype</span><span class="sxs-lookup"><span data-stu-id="b6191-168">Skype</span></span>

- <span data-ttu-id="b6191-169">Исправлена проблема, из-за которой запуск демонстрации экрана мог завершиться сбоем в 32-разрядном клиенте Skype для бизнеса после его работы в течение нескольких дней.</span><span class="sxs-lookup"><span data-stu-id="b6191-169">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-170">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-170">Office Suite</span></span>

- <span data-ttu-id="b6191-171">Исправлена проблема, из-за которой в случае отключения автосохранения с помощью групповой политики некоторые документы могли не отображать последнее содержимое сервера при открытии, пока пользователь не нажмет кнопку "Доступны обновления".</span><span class="sxs-lookup"><span data-stu-id="b6191-171">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-august-11"></a><span data-ttu-id="b6191-173">Версия 1908: 11 августа</span><span class="sxs-lookup"><span data-stu-id="b6191-173">Version 1908: August 11</span></span>
<span data-ttu-id="b6191-174">*Версия 1908 (сборка 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="b6191-174">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="b6191-175">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-175">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="b6191-176">Версия 1902: 11 августа</span><span class="sxs-lookup"><span data-stu-id="b6191-176">Version 1902: August 11</span></span>
<span data-ttu-id="b6191-177">*Версия 1902 (сборка 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="b6191-177">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="b6191-178">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-178">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-july-14"></a><span data-ttu-id="b6191-181">Версия 2002: 14 июля</span><span class="sxs-lookup"><span data-stu-id="b6191-181">Version 2002: July 14</span></span>
<span data-ttu-id="b6191-182">*Версия 2002 (сборка 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="b6191-182">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="b6191-183">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-183">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="b6191-185">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="b6191-185">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b6191-186">Access</span><span class="sxs-lookup"><span data-stu-id="b6191-186">Access</span></span>

- <span data-ttu-id="b6191-187">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="b6191-187">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="b6191-188">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-188">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="b6191-189">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-189">Excel</span></span>

- <span data-ttu-id="b6191-190">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="b6191-190">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="b6191-191">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-191">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="b6191-192">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-192">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="b6191-193">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="b6191-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="b6191-194">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-194">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="b6191-195">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="b6191-195">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="b6191-196">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="b6191-196">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="b6191-197">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="b6191-197">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b6191-198">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-198">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="b6191-199">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="b6191-199">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="b6191-200">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="b6191-200">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="b6191-201">**Сосредоточьтесь на оставшихся задачах.** Пометьте примечания как разрешенные, чтобы свернуть их и сделать открытые элементы более заметными.</span><span class="sxs-lookup"><span data-stu-id="b6191-201">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="b6191-202">**Ввод формулы, возвращающей несколько значений.** Теперь вы можете быстро ввести формулу, возвращающую несколько значений, которые автоматически переносятся в смежные ячейки.</span><span class="sxs-lookup"><span data-stu-id="b6191-202">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="b6191-203">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-203">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="b6191-204">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="b6191-204">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="b6191-205">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="b6191-205">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="b6191-206">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей книге.</span><span class="sxs-lookup"><span data-stu-id="b6191-206">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="b6191-207">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-207">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="b6191-208">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="b6191-208">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="b6191-209">\*\*Найдите то, что ищете: \*\*Ищите команды, людей, файлы, фотографии, веб-статьи и многое другое.</span><span class="sxs-lookup"><span data-stu-id="b6191-209">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="b6191-210">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-210">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="b6191-211">**Шесть эффективных функций.** Добавлено шесть новых функций для улучшения электронных таблиц: ФИЛЬТР, СОРТ, СОРТПО, УНИК, ПОСЛЕДОВ и СЛУЧМАССИВ.</span><span class="sxs-lookup"><span data-stu-id="b6191-211">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="b6191-212">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-212">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="b6191-213">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="b6191-213">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="b6191-214">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-214">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="b6191-215">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="b6191-215">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="b6191-216">**Удобная работа с большими книгами.** Статистика книги предоставляет сведения о ячейках, формулах, диаграммах, таблицах и других элементах.</span><span class="sxs-lookup"><span data-stu-id="b6191-216">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="b6191-217">**Читайте и отвечайте на ходу.** Отвечайте на комментарии и упоминания непосредственно в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="b6191-217">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="b6191-218">**Привлечение внимания с помощью \@@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="b6191-218">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="b6191-219">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-219">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="b6191-220">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-220">Outlook</span></span>

- <span data-ttu-id="b6191-221">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="b6191-221">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="b6191-222">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-222">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="b6191-223">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="b6191-223">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="b6191-224">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="b6191-224">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b6191-225">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-225">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="b6191-226">**Рисование.** Рисуйте поверх изображений или добавьте полотно, чтобы отправить свои идеи с помощью рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="b6191-226">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="b6191-227">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-227">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="b6191-228">**Получение предложений по расположению.** Начните вводить текст в поле "Место" при планировании встреч и собраний, и Outlook предложит помещения, адреса и другие недавние места.</span><span class="sxs-lookup"><span data-stu-id="b6191-228">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="b6191-229">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-229">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="b6191-230">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="b6191-230">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="b6191-231">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="b6191-231">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="b6191-232">\*\*Меню "Вставка ссылки" в Outlook вставляет ссылку с разрешениями, определенными администратором клиента. \*\* При выборе из списка последних использованных ссылок в Outlook вставляется ссылка, которая была доступна только пользователям, имеющим разрешение на доступ к ней.</span><span class="sxs-lookup"><span data-stu-id="b6191-232">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="b6191-233">Из-за этого пользователи часто посылали друг другу письма с просьбой предоставить доступ к документу.</span><span class="sxs-lookup"><span data-stu-id="b6191-233">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="b6191-234">Мы обновили этот опыт, поэтому теперь ссылка вставляется с разрешением по умолчанию, установленным администратором клиента. Для MSIT это «организация может редактировать», поэтому все внутренние пользователи, получившие ссылку, которой поделились таким образом, смогут получить к ней доступ.</span><span class="sxs-lookup"><span data-stu-id="b6191-234">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="b6191-235">\*\*Просмотр сообщений в другой освещенности. \*\* Используйте кнопку "СОЛНЦЕ/ЛУНА" для переключения между светлым и темным фоном в области чтения.</span><span class="sxs-lookup"><span data-stu-id="b6191-235">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="b6191-236">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-236">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="b6191-237">**Фишинговые письма легко обнаружить:** спам и фишинговые сообщения выглядят по-разному, поэтому вы можете легко их идентифицировать и удалить из папки «Входящие».</span><span class="sxs-lookup"><span data-stu-id="b6191-237">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="b6191-p123">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты. [Подробнее](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="b6191-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="b6191-240">**Поиск с правописанием проблем или опечаток.** Outlook найдет то, что вы ищете, даже если запрос написан с ошибками.</span><span class="sxs-lookup"><span data-stu-id="b6191-240">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="b6191-241">**Подключение к сети LinkedIn с помощью Outlook.** Безопасное подключение к учетным записям LinkedIn с помощью учетных записей Майкрософт для просмотра сведений из профилей LinkedIn прямо на карточках контактов.</span><span class="sxs-lookup"><span data-stu-id="b6191-241">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="b6191-242">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-242">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="b6191-243">\*\*Получайте релевантные сообщения в результатах поиска. \*\*Outlook анализирует условия поиска и отображает наиболее релевантные сообщения электронной почты в верхней части результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="b6191-243">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="b6191-244">Кроме того, все результаты будут отображаться в разделе "Лучшие результаты" с сортировкой по дате.</span><span class="sxs-lookup"><span data-stu-id="b6191-244">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="b6191-245">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-245">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="b6191-246">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-246">PowerPoint</span></span>

- <span data-ttu-id="b6191-p126">**Вы вычисляете, мы форматируем.** Рукописные математические выражения преобразуются в стандартные знаки. Просто воспользуйтесь функцией "Рукописный фрагмент в математические символы" и выберите рукописные примечания для начала работы. [Подробнее](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="b6191-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="b6191-250">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="b6191-250">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="b6191-251">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-251">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="b6191-252">**Рукописный ввод для создания отличного слайда.** Преобразуйте рукописный ввод в стандартные фигуры и текст, а затем находите изящные идеи оформления слайдов в конструкторе PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-252">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="b6191-253">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-253">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="b6191-254">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей презентации.</span><span class="sxs-lookup"><span data-stu-id="b6191-254">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="b6191-255">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-255">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="b6191-256">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="b6191-256">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="b6191-257">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="b6191-257">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="b6191-258">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-258">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="b6191-259">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="b6191-259">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="b6191-260">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="b6191-260">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="b6191-261">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="b6191-261">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="b6191-262">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-262">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="b6191-263">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="b6191-263">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="b6191-264">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="b6191-264">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="b6191-265">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-265">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="b6191-266">**Поиск и исправление пропущенных названий слайдов:** Названия слайдов добавляют удар к вашей подаче и делают ваши слайды доступными для пользователей всех способностей.</span><span class="sxs-lookup"><span data-stu-id="b6191-266">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="b6191-267">С помощью средства проверки читаемости можно определить, где отсутствуют заголовки, и сразу же добавить их.</span><span class="sxs-lookup"><span data-stu-id="b6191-267">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="b6191-268">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-268">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="b6191-269">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="b6191-269">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="b6191-270">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="b6191-270">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="b6191-271">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="b6191-271">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="b6191-272">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="b6191-272">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b6191-273">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-273">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="b6191-274">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="b6191-274">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="b6191-275">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="b6191-275">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="b6191-276">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами непосредственно из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="b6191-276">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="b6191-277">**Быстрое взаимодействие в реальном времени в PowerPoint.** Быстрое сотрудничество в реальном времени в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-277">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="b6191-278">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="b6191-278">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="b6191-279">**Новые средства проверки правописания.** Не переживайте из-за слов.</span><span class="sxs-lookup"><span data-stu-id="b6191-279">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="b6191-280">В PowerPoint теперь отображаются предложения в отношении грамматики и написания.</span><span class="sxs-lookup"><span data-stu-id="b6191-280">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="b6191-281">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-281">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="b6191-282">**Субтитры в реальном времени.** Слова докладчика автоматически отображаются на экране в виде субтитров или переводятся в субтитры на выбранном языке.</span><span class="sxs-lookup"><span data-stu-id="b6191-282">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="b6191-283">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-283">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="b6191-284">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="b6191-284">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="b6191-285">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="b6191-285">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="b6191-286">**Зачем изобретать заново то, что можно использовать повторно?** Экономьте время, повторно используя слайды, которые вы создали или которыми другие поделились с вами.</span><span class="sxs-lookup"><span data-stu-id="b6191-286">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="b6191-287">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-287">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="b6191-288">Visio</span><span class="sxs-lookup"><span data-stu-id="b6191-288">Visio</span></span>

- <span data-ttu-id="b6191-289">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="b6191-289">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="b6191-290">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-290">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="b6191-291">**В сценах преступления:** Используйте новые трафареты «Доказательства», «В помещении» и «На улице» в шаблоне «Расследование места преступления», чтобы детально воссоздать места преступления.</span><span class="sxs-lookup"><span data-stu-id="b6191-291">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-292">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-292">Word</span></span>

- <span data-ttu-id="b6191-293">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="b6191-293">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="b6191-294">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-294">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="b6191-295">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="b6191-295">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="b6191-296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-296">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="b6191-297">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="b6191-297">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="b6191-298">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами непосредственно из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="b6191-298">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="b6191-299">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="b6191-299">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="b6191-300">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="b6191-300">Find them at Insert > Icons.</span></span> [<span data-ttu-id="b6191-301">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-301">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="b6191-302">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="b6191-302">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="b6191-303">**Точное стирание.** Выберите один из двух размеров ластика, чтобы исправить небольшие недочеты рукописных фрагментов.</span><span class="sxs-lookup"><span data-stu-id="b6191-303">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="b6191-304">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-304">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="b6191-305">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="b6191-305">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="b6191-306">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="b6191-306">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="b6191-307">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своем документе.</span><span class="sxs-lookup"><span data-stu-id="b6191-307">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="b6191-308">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-308">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="b6191-309">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="b6191-309">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="b6191-310">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="b6191-310">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="b6191-311">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-311">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="b6191-312">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="b6191-312">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="b6191-313">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-313">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="b6191-314">**Редактор для резюме присоединяется к LinkedIn Resume Assistant:** редактор для резюме предлагает выбор грамматических и стилевых проверок, специально предназначенных для резюме, чтобы сделать ваше письмо более точным и профессиональным.</span><span class="sxs-lookup"><span data-stu-id="b6191-314">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="b6191-315">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="b6191-315">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="b6191-316">**Исправление проблемы с повреждением документа при объединении 3D объектов.** Исправлена проблема с повреждением документа, возникавшая при объединении 3D объектов.</span><span class="sxs-lookup"><span data-stu-id="b6191-316">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="b6191-317">**Улучшенные возможности совместного редактирования**. Улучшено быстродействие Word при совместном редактировании в документах с отслеживанием исправлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-317">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="b6191-318">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="b6191-318">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="b6191-319">**Сотрудничайте в живом цвете:** комментарии и изменения имеют цветовую кодировку от участника, поэтому легко увидеть, кто есть кто среди ваших соавторов.</span><span class="sxs-lookup"><span data-stu-id="b6191-319">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="b6191-320">**Совместное редактирование документов с поддержкой макросов:** сохраняйте файлы документов в OneDrive для бизнеса и редактируйте их вместе с соавторами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="b6191-320">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-321">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-321">Office Suite</span></span>

- <span data-ttu-id="b6191-322">**Измените рукописные чернила на фигуры, текст или математику в PowerPoint для Office 365:** Перейдите от чернил произвольной формы к фигурам, тексту или математическому выражению Office за пару движений.</span><span class="sxs-lookup"><span data-stu-id="b6191-322">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="b6191-323">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-323">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-326">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-326">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b6191-327">Access</span><span class="sxs-lookup"><span data-stu-id="b6191-327">Access</span></span>

- <span data-ttu-id="b6191-328">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="b6191-328">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="b6191-329">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="b6191-329">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="b6191-330">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="b6191-330">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="b6191-331">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="b6191-331">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="b6191-332">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="b6191-332">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="b6191-333">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="b6191-333">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b6191-334">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-334">Excel</span></span>

- <span data-ttu-id="b6191-335">Ускорение загрузки файлов, доступных в локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="b6191-335">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="b6191-336">Устранена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неправильный результат.</span><span class="sxs-lookup"><span data-stu-id="b6191-336">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="b6191-337">Устранена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-337">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b6191-338">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-338">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="b6191-339">Устранена проблема, из-за которой не отображались команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="b6191-339">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="b6191-340">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="b6191-340">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="b6191-341">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="b6191-341">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b6191-342">Устранена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-342">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="b6191-343">В некоторых случаях при сохранении в виде CSV-файла Excel мог объединять все столбцы в один столбец.</span><span class="sxs-lookup"><span data-stu-id="b6191-343">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="b6191-344">Использование Range.ClearContents для диапазона в защищенном листе могло занимать больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-344">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="b6191-345">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-345">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="b6191-346">Макросы VBA, взаимодействующие с лентой, могут неожиданно запускаться со значением True, присвоенным параметру ScreenUpdating.</span><span class="sxs-lookup"><span data-stu-id="b6191-346">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="b6191-347">Устранена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="b6191-347">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="b6191-348">В некоторых случаях открытие CSV-файлов занимало больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-348">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="b6191-349">В ряде случаев приложение Excel аварийно завершало работу при переключении между книгами с разным масштабом.</span><span class="sxs-lookup"><span data-stu-id="b6191-349">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="b6191-350">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-350">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="b6191-351">Данные, скопированные из столбца и отфильтрованные по цвету, иногда не вставлялись должным образом.</span><span class="sxs-lookup"><span data-stu-id="b6191-351">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="b6191-352">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-352">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="b6191-353">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении (заполнение вниз, заполнение в стороны), если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="b6191-353">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="b6191-354">Устранена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="b6191-354">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="b6191-355">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-355">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b6191-356">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-356">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="b6191-357">Устранена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="b6191-357">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="b6191-358">Повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="b6191-358">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="b6191-359">Устранена проблема, из-за которой имена принтеров могли повторяться в списке принтеров в диалоговом окне "Печать".</span><span class="sxs-lookup"><span data-stu-id="b6191-359">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="b6191-360">Устранена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="b6191-360">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="b6191-361">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-361">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b6191-362">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="b6191-362">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="b6191-363">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-363">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="b6191-364">Устранена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="b6191-364">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="b6191-365">Устранена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, поэтому закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="b6191-365">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="b6191-366">Устранена проблема, из-за которой книга могла быть скрыта при щелчке гиперссылки на определенное место в уже открытой книге.</span><span class="sxs-lookup"><span data-stu-id="b6191-366">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="b6191-367">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-367">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="b6191-368">В некоторых случаях при использовании приложения VBA не работала оценка пользовательских функций.</span><span class="sxs-lookup"><span data-stu-id="b6191-368">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b6191-369">Устранена проблема, которая могла возникнуть у некоторых пользователей со встроенными и связанными объектами (OLE).</span><span class="sxs-lookup"><span data-stu-id="b6191-369">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="b6191-370">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="b6191-370">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b6191-371">Это обновление устраняет проблему, из-за которой на панели формул текст отображался со шрифтом, отличным от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="b6191-371">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="b6191-372">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="b6191-372">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b6191-373">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="b6191-373">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b6191-374">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="b6191-374">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="b6191-375">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-375">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b6191-376">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="b6191-376">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="b6191-377">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="b6191-377">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="b6191-378">Устранена проблема, из-за которой у некоторых пользователей могли возникать ошибки при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="b6191-378">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="b6191-379">При использовании Range.Value и Range.Value2 (VBA) формулы вводились как динамические массивы.</span><span class="sxs-lookup"><span data-stu-id="b6191-379">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="b6191-380">Устранена проблема, из-за которой знак @ в начале формулы считался неявным оператором пересечения.</span><span class="sxs-lookup"><span data-stu-id="b6191-380">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="b6191-381">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="b6191-381">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="b6191-382">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="b6191-382">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b6191-383">Устранена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="b6191-383">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="b6191-384">OneNote</span><span class="sxs-lookup"><span data-stu-id="b6191-384">OneNote</span></span>

- <span data-ttu-id="b6191-385">Улучшены синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-385">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="b6191-386">Улучшены синхронизация и стабильность службы путем временного откладывания загрузки внедренных файлов и изображений в записных книжках в Интернете, пока пользователь не перейдет на страницу в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-386">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="b6191-387">Улучшены синхронизация и стабильность службы путем временного отключения корзины в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-387">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="b6191-388">Если пользователь пытается удалить данные, которые обычно отправляются в корзину, ему будет предложено сохранить или окончательно удалить их.</span><span class="sxs-lookup"><span data-stu-id="b6191-388">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="b6191-389">Улучшены синхронизация и стабильность службы путем временного уменьшения количества и частоты синхронизации страниц журнала версий в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-389">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="b6191-390">Отображает уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="b6191-390">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="b6191-391">Улучшены синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-391">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="b6191-392">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="b6191-392">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="b6191-393">Улучшены синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-393">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="b6191-394">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="b6191-394">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="b6191-395">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="b6191-395">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-396">Outlook</span></span>

- <span data-ttu-id="b6191-397">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="b6191-397">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="b6191-398">Устранена проблема, из-за которой Outlook иногда давал сбой.</span><span class="sxs-lookup"><span data-stu-id="b6191-398">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="b6191-399">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="b6191-399">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b6191-400">Устранена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="b6191-400">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="b6191-401">Устранена проблема, при которой повторяющиеся встречи или собрания отображались с ошибкой во времени при приближении изменений в определении часового пояса.</span><span class="sxs-lookup"><span data-stu-id="b6191-401">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="b6191-402">При использовании часового пояса Бразилии в 2019 г. повторяющиеся собрания и встречи на 2020 г. отображаются в неправильном временном интервале.</span><span class="sxs-lookup"><span data-stu-id="b6191-402">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="b6191-403">Это изменение существенно для клиентов в часовом поясе Бразилии, а также для собраний и встреч в этом часовом поясе.</span><span class="sxs-lookup"><span data-stu-id="b6191-403">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="b6191-404">Это изменение дает приложению Outlook возможность переопределять некоторые параметры часового пояса, которые оно использует.</span><span class="sxs-lookup"><span data-stu-id="b6191-404">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="b6191-405">Чтобы вызвать переопределение часового пояса, необходимо задать раздел реестра для текущего пользователя.</span><span class="sxs-lookup"><span data-stu-id="b6191-405">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="b6191-406">Имя раздела реестра должно совпадать со внутренним именем часового пояса.</span><span class="sxs-lookup"><span data-stu-id="b6191-406">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="b6191-407">Это значение указывает год для правила часового пояса, который будет использоваться вместо текущего года.</span><span class="sxs-lookup"><span data-stu-id="b6191-407">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="b6191-408">Например, приведенное ниже значение для переопределения раздела реестра активирует правило бразильского часового пояса для 2020 года.</span><span class="sxs-lookup"><span data-stu-id="b6191-408">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="b6191-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"</span><span class="sxs-lookup"><span data-stu-id="b6191-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="b6191-410">Восточное Ю-Ам. время (зима)"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="b6191-410">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="b6191-411">Устранена проблема, из-за которой пользователи наблюдали неожиданное изменение поля расположения в собрании.</span><span class="sxs-lookup"><span data-stu-id="b6191-411">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="b6191-412">Устранена проблема, из-за которой неожиданно обновлялось поле расположения в собраниях.</span><span class="sxs-lookup"><span data-stu-id="b6191-412">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="b6191-413">Устранена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="b6191-413">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="b6191-414">Устранена проблема, из-за которой запятые в поле места проведения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="b6191-414">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="b6191-415">Позволяет присоединиться к собранию в Teams непосредственно через собственный клиент Teams.</span><span class="sxs-lookup"><span data-stu-id="b6191-415">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="b6191-416">Устранена проблема, из-за которой у пользователей с почтовыми ящиками на серверах Exchange 2010 возникали проблемы при добавлении вложений в элементы календаря.</span><span class="sxs-lookup"><span data-stu-id="b6191-416">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="b6191-417">Устранена проблема, из-за которой у пользователей возникали проблемы при ответе на сообщения с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="b6191-417">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="b6191-418">Устранена проблема, из-за которой пользователи не могли открывать некоторые вхождения повторяющихся элементов календаря.</span><span class="sxs-lookup"><span data-stu-id="b6191-418">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="b6191-419">Устранена проблема, приводившая к неожиданному увеличению заголовка группы в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="b6191-419">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="b6191-420">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="b6191-420">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="b6191-421">Устранена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="b6191-421">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="b6191-422">Устранена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="b6191-422">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b6191-423">Устранена проблема, которая могла приводить к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="b6191-423">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="b6191-424">Устранена проблема, из-за которой при обновлении этих правил в Outlook появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="b6191-424">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="b6191-425">Устранена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-425">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b6191-426">Устранена проблема, из-за которой у пользователей возникал сбой при указании неправильного адреса "От".</span><span class="sxs-lookup"><span data-stu-id="b6191-426">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b6191-427">Устранена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="b6191-427">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b6191-428">Устранена проблема, из-за которой параметр отключения выделения помеченных элементов не учитывался в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="b6191-428">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="b6191-429">Устранена проблема, из-за которой сообщения неожиданно отправлялись при нажатии клавиши S после закрытия панели проверки читаемости.</span><span class="sxs-lookup"><span data-stu-id="b6191-429">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="b6191-430">Устранена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="b6191-430">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="b6191-431">Устранена проблема, которая приводила к сбою пользователей при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="b6191-431">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="b6191-432">Устранена проблема, из-за которой приложение Outlook неожиданно синхронизировало всю почту, даже если ползунок синхронизации настроен на меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="b6191-432">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="b6191-433">Устранена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке "От" отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="b6191-433">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="b6191-434">Устранена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="b6191-434">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="b6191-435">Устранена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="b6191-435">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b6191-436">Устранена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="b6191-436">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b6191-437">Исправлена проблема, из-за которой сторонние приложения не могли отправлять электронные сообщения.</span><span class="sxs-lookup"><span data-stu-id="b6191-437">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="b6191-438">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="b6191-438">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="b6191-439">Устранена проблема, из-за которой у пользователей Outlook, использующих серверные операционные системы, возникала ошибка "Состояние антивирусной защиты: не действует</span><span class="sxs-lookup"><span data-stu-id="b6191-439">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="b6191-440">Данная версия Windows поддерживает обнаружение антивирусных программ, но ни одной программы не найдено", несмотря на то что антивирусная программа настроена правильно.</span><span class="sxs-lookup"><span data-stu-id="b6191-440">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="b6191-441">Устранена проблема, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="b6191-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="b6191-442">Устранена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="b6191-442">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="b6191-443">Устранена проблема, из-за которой пользователи, у которых неправильно задан параметр эмуляции браузера, не могли завершить запрос на проверку подлинности Gmail.</span><span class="sxs-lookup"><span data-stu-id="b6191-443">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="b6191-444">Устранена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="b6191-444">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="b6191-445">Устранена проблема, приводившая в сбою при попытке открытия файлов MSG и OFT после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="b6191-445">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="b6191-446">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки X на мыши.</span><span class="sxs-lookup"><span data-stu-id="b6191-446">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="b6191-447">Устранена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="b6191-447">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="b6191-448">Устранена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="b6191-448">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b6191-449">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="b6191-449">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="b6191-450">Устранена проблема, вызывавшая сбой после того, как две надстройки добавляли кнопку в одну и ту же группу ленты.</span><span class="sxs-lookup"><span data-stu-id="b6191-450">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="b6191-451">Устранена проблема, из-за которой не удавалось добавить ссылки в сообщения электронной почты с правильным клиентским разрешением по умолчанию, если для этого разрешения был установлен параметр "Все".</span><span class="sxs-lookup"><span data-stu-id="b6191-451">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="b6191-452">Устранена проблема, из-за которой пользователи не могли отправлять электронные сообщения по адресам из личного списка рассылки.</span><span class="sxs-lookup"><span data-stu-id="b6191-452">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="b6191-453">Устранена проблема, из-за которой текст сообщения усекался при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="b6191-453">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b6191-454">Устранена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="b6191-454">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b6191-455">Устранена проблема, из-за которой не удавалось сохранять файлы в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="b6191-455">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="b6191-456">Устранена проблема, из-за которой пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="b6191-456">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="b6191-457">Устранена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="b6191-457">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="b6191-458">Устранена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-458">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b6191-459">Исправлена проблема, из-за которой пользователи иногда наблюдали отправку сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="b6191-459">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="b6191-460">Устранена проблема, которая приводила к неправильному выравниванию поля поиска в режиме высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="b6191-460">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="b6191-461">Устранена проблема, приводившая к зависанию Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="b6191-461">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="b6191-462">Устранена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="b6191-462">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b6191-463">Устранена проблема, из-за которой Outlook иногда давал сбой.</span><span class="sxs-lookup"><span data-stu-id="b6191-463">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="b6191-464">Устранена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="b6191-464">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="b6191-465">Устранена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="b6191-465">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="b6191-466">Устранена проблема, из-за которой Outlook иногда давал сбой.</span><span class="sxs-lookup"><span data-stu-id="b6191-466">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b6191-467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-467">PowerPoint</span></span>

- <span data-ttu-id="b6191-468">Устранена проблема, которая могла вызвать сбой при использовании контекстного меню в устаревших комментариях PPT.</span><span class="sxs-lookup"><span data-stu-id="b6191-468">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="b6191-469">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="b6191-469">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="b6191-470">Устранена проблема с ретрансляцией точного текста сообщений для пользователей, которые открывают копию файла с улучшенными примечаниями.</span><span class="sxs-lookup"><span data-stu-id="b6191-470">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="b6191-471">Project</span><span class="sxs-lookup"><span data-stu-id="b6191-471">Project</span></span>

- <span data-ttu-id="b6191-472">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="b6191-472">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="b6191-473">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="b6191-473">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b6191-474">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, была ли задача деактивирована или активирована с помощью кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="b6191-474">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="b6191-475">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="b6191-475">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="b6191-476">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения</span><span class="sxs-lookup"><span data-stu-id="b6191-476">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="b6191-477">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="b6191-477">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-478">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-478">Word</span></span>

- <span data-ttu-id="b6191-479">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки X на мыши.</span><span class="sxs-lookup"><span data-stu-id="b6191-479">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="b6191-480">Устранена проблема, из-за которой выравнивание слова в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="b6191-480">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="b6191-481">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="b6191-481">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="b6191-482">Исправлена проблема, из-за которой вставляемые горизонтальные линии не укорачиваются и не располагаются по центру.</span><span class="sxs-lookup"><span data-stu-id="b6191-482">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="b6191-483">Диспетчер стандартных блоков может отображать неправильное оповещение: "Были изменены стили, стандартные блоки".</span><span class="sxs-lookup"><span data-stu-id="b6191-483">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="b6191-484">Устранена проблема с совместной работой над документом при включении политики FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="b6191-484">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="b6191-485">Устранена проблема, при которой функция экспресс-блоков Word не работала при добавлении переименованного поля подстановки.</span><span class="sxs-lookup"><span data-stu-id="b6191-485">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="b6191-486">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="b6191-486">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b6191-487">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="b6191-487">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="b6191-488">Это обновление устраняет проблему в Microsoft Word, из-за которой текст длиной более 255 символов, вставленный при применении метки конфиденциальности, впоследствии не удавалось идентифицировать и удалить путем изменения или удаления метки, если в рамках политики меток был применен колонтитул или подложка.</span><span class="sxs-lookup"><span data-stu-id="b6191-488">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-489">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-489">Office Suite</span></span>

- <span data-ttu-id="b6191-490">Устранена проблема, из-за которой при совместной работе над объемными файлами PowerPoint чрезмерно повышалась нагрузка на сеть и ЦП.</span><span class="sxs-lookup"><span data-stu-id="b6191-490">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="b6191-491">Это исправление устраняет блокирование сети приложением Project при кэшировании файла в клиенте.</span><span class="sxs-lookup"><span data-stu-id="b6191-491">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="b6191-492">Эта проблема устранена с помощью замены имен каналов в представлении Backstage на новые в ответвлении за январь 2020 г.</span><span class="sxs-lookup"><span data-stu-id="b6191-492">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="b6191-493">Устранена проблема, из-за которой устройства, регулируемые политикой не могли вызвать API аудитории DMS.</span><span class="sxs-lookup"><span data-stu-id="b6191-493">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="b6191-494">Устранена проблема, из-за которой при добавлении и удалении приложений в одной транзакции выполнялось неполное удаление.</span><span class="sxs-lookup"><span data-stu-id="b6191-494">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="b6191-495">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-495">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b6191-496">Решена проблема, из-за которой обновления Office могли неожиданно скачивать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b6191-496">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b6191-497">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-497">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b6191-498">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="b6191-498">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="b6191-499">Решена проблема, из-за которой внутренняя операция вызывала исключение при сбое вместо ведения журнала и продолжения работы.</span><span class="sxs-lookup"><span data-stu-id="b6191-499">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="b6191-500">Для затронутых пользователей будет отменен запрет на получение обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-500">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="b6191-501">Наша команда добавила в клиент поддержку отчетов телеметрии на доменах CDN Office на Полугодовом канале (предварительная корпоративная версия).</span><span class="sxs-lookup"><span data-stu-id="b6191-501">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="b6191-502">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="b6191-502">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="b6191-503">Это изменение обеспечит правильную работу функции "Контур эскиза" на ленте.</span><span class="sxs-lookup"><span data-stu-id="b6191-503">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="b6191-504">Исправлена проблема при открытии файлов из локальных расположений с определенными настройками прокси.</span><span class="sxs-lookup"><span data-stu-id="b6191-504">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="b6191-505">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="b6191-505">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="b6191-506">Исправлена проблема, благодаря чему устранены сбои во время сеансов передачи Office и повышена надежность работы пользователей.</span><span class="sxs-lookup"><span data-stu-id="b6191-506">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="b6191-507">Это исправление обновляет конечную точку URL-адреса конфигурации усиленной безопасности (ECS).</span><span class="sxs-lookup"><span data-stu-id="b6191-507">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="b6191-508">В результате вызова этой новой конечной точки повышается успешность получения данных из ECS.</span><span class="sxs-lookup"><span data-stu-id="b6191-508">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="b6191-509">Это обновление устраняет проблему, из-за которой в Microsoft Outlook не отображается текущая метка конфиденциальности при просмотре или создании сообщений.</span><span class="sxs-lookup"><span data-stu-id="b6191-509">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="b6191-510">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="b6191-510">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="b6191-511">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="b6191-511">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="b6191-512">Аварийное завершение работы узла Office в Windows при активации надстройки, если для раздела реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth задано значение "0".</span><span class="sxs-lookup"><span data-stu-id="b6191-512">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="b6191-513">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="b6191-513">This change would fix this issue.</span></span>

- <span data-ttu-id="b6191-514">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="b6191-514">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="b6191-515">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="b6191-515">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="b6191-516">Устранена проблема, из-за которой приложения Access и Publisher могли загружаться неправильно в зависимости от того, какие языки установлены.</span><span class="sxs-lookup"><span data-stu-id="b6191-516">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)





[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-july-14"></a><span data-ttu-id="b6191-519">Версия 1908: 14 июля</span><span class="sxs-lookup"><span data-stu-id="b6191-519">Version 1908: July 14</span></span>
<span data-ttu-id="b6191-520">*Версия 1908 (сборка 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="b6191-520">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="b6191-521">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-521">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-523">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-523">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b6191-524">Access</span><span class="sxs-lookup"><span data-stu-id="b6191-524">Access</span></span>

- <span data-ttu-id="b6191-525">Это обновление исправляет проблему, из-за которой агрегатная функция, например, Sum, может обрезать результат до целого значения.</span><span class="sxs-lookup"><span data-stu-id="b6191-525">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="b6191-526">Это обновление исправляет проблему, из-за которой запрос на объединение, включающий ссылки на удаленные таблицы (например, таблицы SQL Server), может приводить к закрытию и перезапуску Access.</span><span class="sxs-lookup"><span data-stu-id="b6191-526">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="b6191-527">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="b6191-527">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b6191-528">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-528">Excel</span></span>

- <span data-ttu-id="b6191-529">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="b6191-529">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="b6191-530">Устранена проблема в Excel, из-за которой при выполнении макросов, присвоенных фигурам или элементам управления формы, выводятся неправильные сообщения об ошибке или эти макросы работают в неправильном целевом диапазоне.</span><span class="sxs-lookup"><span data-stu-id="b6191-530">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="b6191-531">Решена проблема, при которой содержимое диалогового окна "Поиск и замена" изменялось, если курсор находился в нем после нахождения первого элемента.</span><span class="sxs-lookup"><span data-stu-id="b6191-531">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="b6191-532">Исправлена проблема, из-за которой изменение способа сортировки сводной таблицы и ее обновление в сеансе совместного редактирования с другими пользователями могло приводить к сбою.</span><span class="sxs-lookup"><span data-stu-id="b6191-532">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="b6191-533">Исправлена проблема, при которой для фильтра сводной таблицы OLAP было задано значение, удаленное из куба.</span><span class="sxs-lookup"><span data-stu-id="b6191-533">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="b6191-534">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="b6191-534">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="b6191-535">Устранена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов</span><span class="sxs-lookup"><span data-stu-id="b6191-535">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="b6191-536">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм.</span><span class="sxs-lookup"><span data-stu-id="b6191-536">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="b6191-537">Устранена проблема, приводившая к нарушению синхронизации каскадных и воронкообразных диаграмм с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="b6191-537">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="b6191-538">Исправлена проблема с конфликтом слияния в Excel, из-за которой пользователям предлагалось повторно открыть книгу, чтобы внести изменения.</span><span class="sxs-lookup"><span data-stu-id="b6191-538">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="b6191-539">Исправлена проблема, которая была причиной ошибки времени выполнения макроса при активации свернутых окон.</span><span class="sxs-lookup"><span data-stu-id="b6191-539">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="b6191-540">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-540">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b6191-541">Устранена проблема, из-за которой вырезание и вставка в таблице не выполняются при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="b6191-541">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="b6191-542">Решена проблема, вызывавшая прерывание совместного редактирования при изменении настраиваемых свойств с помощью макросов.</span><span class="sxs-lookup"><span data-stu-id="b6191-542">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="b6191-543">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытом надстройкой.</span><span class="sxs-lookup"><span data-stu-id="b6191-543">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="b6191-544">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="b6191-544">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b6191-545">Устранена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-545">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="b6191-546">Устранена проблема, из-за которой у некоторых пользователей появлялось несколько всплывающих окон при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="b6191-546">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="b6191-547">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="b6191-547">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b6191-548">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-548">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="b6191-549">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-549">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="b6191-550">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-550">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b6191-551">Исправлена проблема, приводившая к снижению производительности при удалении столбцов, содержащих объединенные ячейки.</span><span class="sxs-lookup"><span data-stu-id="b6191-551">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="b6191-552">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-552">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="b6191-553">При копировании данных, отфильтрованных по цвету, в столбец с другой шириной, значения не вставляются.</span><span class="sxs-lookup"><span data-stu-id="b6191-553">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="b6191-554">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="b6191-554">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="b6191-555">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-555">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b6191-556">Устранена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-556">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="b6191-557">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="b6191-557">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="b6191-558">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="b6191-558">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="b6191-559">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="b6191-559">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="b6191-560">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="b6191-560">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b6191-561">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="b6191-561">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="b6191-562">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="b6191-562">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="b6191-563">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="b6191-563">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="b6191-564">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="b6191-564">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b6191-565">Исправлена проблема, из-за которой функция Lookup может возвращать ошибку.</span><span class="sxs-lookup"><span data-stu-id="b6191-565">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="b6191-566">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="b6191-566">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="b6191-567">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="b6191-567">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="b6191-568">Проблема низкой производительности при нажатии кнопки "Цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="b6191-568">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="b6191-569">Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-569">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="b6191-570">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-570">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b6191-571">Значительно повышена производительность фильтрации по цвету.</span><span class="sxs-lookup"><span data-stu-id="b6191-571">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="b6191-572">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office.</span><span class="sxs-lookup"><span data-stu-id="b6191-572">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="b6191-573">Поддерживается отображение более 16 надстроек при просмотре в диспетчере надстроек.</span><span class="sxs-lookup"><span data-stu-id="b6191-573">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="b6191-574">Устранена проблема, которая препятствовала вставке гиперссылок в некоторых защищенных листах.</span><span class="sxs-lookup"><span data-stu-id="b6191-574">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="b6191-575">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="b6191-575">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b6191-576">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-576">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-577">Это обновление устраняет ошибку, из-за которой документы Office могут не отправляться в OneDrive для бизнеса и приходит сообщение "Не удалось выполнить отправку".</span><span class="sxs-lookup"><span data-stu-id="b6191-577">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="b6191-578">Устранена проблема в функции "Идеи" для Excel, приводившая к ошибке при загрузке надстройки путем нажатия на кнопку "Идеи" в клиенте Win32.</span><span class="sxs-lookup"><span data-stu-id="b6191-578">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="b6191-579">OneNote</span><span class="sxs-lookup"><span data-stu-id="b6191-579">OneNote</span></span>

- <span data-ttu-id="b6191-580">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="b6191-580">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-581">Outlook</span></span>

- <span data-ttu-id="b6191-582">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-582">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-583">Исправлена проблема, из-за которой обновление в почтовых ящиках пользователей обычной проверки подлинности до современной приводило к привязыванию неправильной учетной записи к профилю Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-583">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="b6191-584">Устранена проблема, которая была причиной доступа веб-надстроек к сообщениям с управлением цифровыми правами, когда это не предполагалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-584">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="b6191-585">Устранена проблема, из-за которой URL-адреса не открывались при простом наведении на некоторые безопасные ссылки.</span><span class="sxs-lookup"><span data-stu-id="b6191-585">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="b6191-586">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="b6191-586">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b6191-587">В этой статье описана проблема, из-за которой у подмножества пользователей POP3 сообщения электронной почты выводятся в виде обычного текста, независимо от настроек.</span><span class="sxs-lookup"><span data-stu-id="b6191-587">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="b6191-588">Это исправление восстановит сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="b6191-588">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="b6191-589">Устранена проблема, из-за которой возникала ошибка доступа при копировании элементов из основного календаря в календарь группы.</span><span class="sxs-lookup"><span data-stu-id="b6191-589">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="b6191-590">Устранена проблема, из-за которой пользователям были недоступны предложения расположений при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="b6191-590">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="b6191-591">Устранена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="b6191-591">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b6191-592">Устранена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-592">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b6191-593">Устранена проблема, из-за которой у пользователей возникал сбой при указании неправильного адреса "От".</span><span class="sxs-lookup"><span data-stu-id="b6191-593">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b6191-594">Устранена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="b6191-594">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b6191-595">Устранена проблема, которая приводила к сбою в Outlook при взаимодействии пользователей с определенными безопасными ссылками.</span><span class="sxs-lookup"><span data-stu-id="b6191-595">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="b6191-596">В этой статье описана проблема, из-за которой менеджеры не могли установить, ответил ли участник на приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="b6191-596">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="b6191-597">Устранена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="b6191-597">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b6191-598">Устранена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="b6191-598">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b6191-599">Это изменение позволяет администраторам включать политику, предпочитающую указанную учетную запись электронной почты в запросах проверки подлинности службы автообнаружения вместо имени участника-пользователя (UPN).</span><span class="sxs-lookup"><span data-stu-id="b6191-599">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="b6191-600">По умолчанию при автообнаружении предпочтение отдается UPN учетной записи (при наличии).</span><span class="sxs-lookup"><span data-stu-id="b6191-600">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="b6191-601">Устранена проблема, вызывавшая сбой поиска в современных группах.</span><span class="sxs-lookup"><span data-stu-id="b6191-601">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="b6191-602">Устранена проблема, приводившая к зависанию пользователей Outlook в состоянии "Требуется пароль" в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="b6191-602">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="b6191-603">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="b6191-603">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="b6191-604">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="b6191-604">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="b6191-605">Устранена проблема, из-за которой мог зависать экран загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-605">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="b6191-606">Устранена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="b6191-606">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="b6191-607">Устранена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="b6191-607">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b6191-608">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="b6191-608">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="b6191-609">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="b6191-609">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="b6191-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = по умолчанию; 1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="b6191-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="b6191-611">Устранена проблема, из-за которой пользователи сталкивались со сбоем при закрытии Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-611">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="b6191-612">Устранена проблема, приводившая к отображению пустого списка помещений в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="b6191-612">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="b6191-613">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-613">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="b6191-614">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="b6191-614">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="b6191-615">Устранена проблема, приводившая к сбоям при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="b6191-615">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="b6191-616">Вот отдельная [статья базы знаний, где эта проблема задокументирована в описаниях предыдущих версий](https://support.microsoft.com/ru-RU/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen).</span><span class="sxs-lookup"><span data-stu-id="b6191-616">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/ru-RU/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="b6191-617">Устранена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="b6191-617">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b6191-618">Устранена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="b6191-618">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="b6191-619">Устранена проблема, из-за которой пользователям предлагались помещения для собраний, проводимых в то время, когда эти помещения недоступны.</span><span class="sxs-lookup"><span data-stu-id="b6191-619">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="b6191-620">Устранена проблема для неанглоязычных пользователей, из-за которой строка темы в почте была очень маленькой.</span><span class="sxs-lookup"><span data-stu-id="b6191-620">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="b6191-621">Устранена проблема, приводившая к сбою при попытке создать правило на основе сообщения о пропущенной беседе.</span><span class="sxs-lookup"><span data-stu-id="b6191-621">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="b6191-622">Устранена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="b6191-622">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="b6191-623">Устранена проблема, из-за которой текст сообщения усекался при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="b6191-623">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b6191-624">Устранена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-624">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b6191-625">Устранена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="b6191-625">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="b6191-626">Устранена проблема, которая приводила к периодическому сбою поиска в текущей папке.</span><span class="sxs-lookup"><span data-stu-id="b6191-626">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="b6191-627">Устранена проблема, из-за которой некоторые пользователи сталкивались с ошибками проверки подлинности при попытке получить свои облачные параметры для Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-627">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="b6191-628">Устранена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="b6191-628">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b6191-629">Устранена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="b6191-629">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b6191-630">Устранена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="b6191-630">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b6191-631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-631">PowerPoint</span></span>

- <span data-ttu-id="b6191-632">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-632">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-633">Это изменение восстанавливает доступное имя для элементов управления видео в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-633">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="b6191-634">Устранена проблема, из-за которой не запускались некоторые эффекты анимации</span><span class="sxs-lookup"><span data-stu-id="b6191-634">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="b6191-635">Устранена проблема, из-за которой при копировании слайда из одной презентации в другую могли появляться дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="b6191-635">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="b6191-636">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="b6191-636">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="b6191-637">Устранена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="b6191-637">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="b6191-638">При открытии файлы с новыми современными примечаниями в неподдерживаемой версии отображается желтое предупреждение.</span><span class="sxs-lookup"><span data-stu-id="b6191-638">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="b6191-639">Устранена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="b6191-639">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="b6191-640">Исправление проблем с надежностью. Устранена проблема, из-за которой надстройка стороннего поставщика могла вызывать сбой PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-640">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="b6191-641">Устранена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="b6191-641">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="b6191-642">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="b6191-642">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="b6191-643">Мы устранили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-643">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="b6191-644">Устранена проблема, из-за которой некоторые надстройки создавали непредвиденные ошибки вокруг фигур в диаграммах.</span><span class="sxs-lookup"><span data-stu-id="b6191-644">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="b6191-645">Это исправление помогает пользователям PowerPoint избежать ошибки при попытке онлайн-презентации.</span><span class="sxs-lookup"><span data-stu-id="b6191-645">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="b6191-646">Project</span><span class="sxs-lookup"><span data-stu-id="b6191-646">Project</span></span>

- <span data-ttu-id="b6191-647">Исправлена проблема, чтобы разрешить пользователям в Windows 7 открывать проекты из Project Web App и сайтов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-647">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="b6191-648">Обнаружена проблема, из-за которой пользователи могли получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="b6191-648">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="b6191-649">Команда "Выровнять все" не устраняет должным образом превышение доступности ресурсов.</span><span class="sxs-lookup"><span data-stu-id="b6191-649">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="b6191-650">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="b6191-650">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="b6191-651">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="b6191-651">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="b6191-652">Skype</span><span class="sxs-lookup"><span data-stu-id="b6191-652">Skype</span></span>

- <span data-ttu-id="b6191-653">Исправлено название вкладки беседы при наличии нескольких активных бесед.</span><span class="sxs-lookup"><span data-stu-id="b6191-653">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="b6191-654">Visio</span><span class="sxs-lookup"><span data-stu-id="b6191-654">Visio</span></span>

- <span data-ttu-id="b6191-655">Экспорт в формате SVG из Visio не работал для различных фигур.</span><span class="sxs-lookup"><span data-stu-id="b6191-655">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-656">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-656">Word</span></span>

- <span data-ttu-id="b6191-657">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-657">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-658">Устранена проблема, которая могла приводить к ошибкам с масштабированием при печати на принтерах Deskjet</span><span class="sxs-lookup"><span data-stu-id="b6191-658">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="b6191-659">Устранена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="b6191-659">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="b6191-660">Устранена проблема с отслеживанием изменений, которые иногда переходят в режим бесконечного цикла. </span><span class="sxs-lookup"><span data-stu-id="b6191-660">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="b6191-661">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="b6191-661">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="b6191-662">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="b6191-662">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b6191-663">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="b6191-663">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="b6191-664">Устранены различные проблемы, из-за которых приложение могло зависнуть при завершении работы.</span><span class="sxs-lookup"><span data-stu-id="b6191-664">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="b6191-665">Также исправлены некоторые ошибки, связанные с надстройками.</span><span class="sxs-lookup"><span data-stu-id="b6191-665">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-666">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-666">Office Suite</span></span>

- <span data-ttu-id="b6191-667">Исправлена проблема с неправильным определением названия новой эры "Рэйва" в хирагана и кандзи как выражения с опечаткой или грамматической ошибкой.</span><span class="sxs-lookup"><span data-stu-id="b6191-667">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="b6191-668">Исправлена проблема, из-за которой пользователи получали сообщение "Не удалось предоставить общий доступ" при попытке поделиться файлами, хранящимися в SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-668">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="b6191-669">Исправлена проблема, которая могла приводить к потере данных в сеансах, включающих как совместное редактирование, так и редактирование в автономном режиме в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-669">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="b6191-670">Исправлена проблема, из-за которой мог произойти сбой при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-670">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="b6191-671">В некоторых случаях файл SharePoint, сохраненный с помощью модуля синхронизации, отображал состояние "Сохранено", но в действительности изменения не сохранялись. Это приводило к потере данных.</span><span class="sxs-lookup"><span data-stu-id="b6191-671">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="b6191-672">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-672">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="b6191-673">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как диалоговое окно", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="b6191-673">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="b6191-674">Устранен сбой в Word благодаря отказу от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="b6191-674">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="b6191-675">Устранена проблема, из-за которой не удавалось правильно повернуть полуширинные знаки катаканы при использовании вертикальных текстовых полей в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-675">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="b6191-676">Устранена проблема с быстродействием Win7, из-за которой вставленная коллекция фигур с ленты во всех приложениях отображалась примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="b6191-676">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="b6191-677">Исправлена ошибка, из-за которой сведения о специальных возможностях не отображались в области сведений представления Backstage.</span><span class="sxs-lookup"><span data-stu-id="b6191-677">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="b6191-678">Повышена надежность процесса обновления Office в отношении целостности реестра.</span><span class="sxs-lookup"><span data-stu-id="b6191-678">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="b6191-679">Имена каналов для разветвлений января и июля 2019 г. обновлены.</span><span class="sxs-lookup"><span data-stu-id="b6191-679">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="b6191-680">Устранена проблема, из-за которой обновления могли неожиданно блокироваться в сетях с лимитным тарифным планом.</span><span class="sxs-lookup"><span data-stu-id="b6191-680">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="b6191-681">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-681">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b6191-682">При определенных обстоятельствах ярлыки Office могут исчезнуть после обновления.</span><span class="sxs-lookup"><span data-stu-id="b6191-682">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="b6191-683">Это обновление повышает надежность при публикации ярлыков Office.</span><span class="sxs-lookup"><span data-stu-id="b6191-683">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="b6191-684">Решена проблема, из-за которой обновления Office могли неожиданно скачивать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b6191-684">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b6191-685">Устранена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="b6191-685">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="b6191-686">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="b6191-686">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="b6191-687">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="b6191-687">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="b6191-688">Повышена надежность при скачивании обновлений Office путем продолжения скачивания, которое ранее могло прерываться.</span><span class="sxs-lookup"><span data-stu-id="b6191-688">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="b6191-689">Устранены проблемы, связанные со свойством автоподбора размера текстовых полей и фигур в сторонних подключаемых модулях.</span><span class="sxs-lookup"><span data-stu-id="b6191-689">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="b6191-690">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-690">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="b6191-691">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="b6191-691">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="b6191-692">Устранена проблема, из-за которой представление в виде большого дерева могло привести к сбою</span><span class="sxs-lookup"><span data-stu-id="b6191-692">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="b6191-693">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="b6191-693">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="b6191-694">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="b6191-694">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="b6191-695">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="b6191-695">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-july-14"></a><span data-ttu-id="b6191-697">Версия 1902: 14 июля</span><span class="sxs-lookup"><span data-stu-id="b6191-697">Version 1902: July 14</span></span>
<span data-ttu-id="b6191-698">*Версия 1902 (сборка 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="b6191-698">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="b6191-699">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-699">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="b6191-700">Версия 1908: 09 июля</span><span class="sxs-lookup"><span data-stu-id="b6191-700">Version 1908: June 09</span></span>
<span data-ttu-id="b6191-701">*Версия 1908 (сборка 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="b6191-701">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="b6191-702">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-702">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-704">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-704">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-705">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-705">Excel</span></span>

- <span data-ttu-id="b6191-706">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="b6191-706">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="b6191-707">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-707">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b6191-708">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="b6191-708">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-709">Outlook</span></span>

- <span data-ttu-id="b6191-710">Устранена проблема, из-за которой пользователи видели текст сообщения неполностью при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="b6191-710">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-711">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-711">Office Suite</span></span>

- <span data-ttu-id="b6191-712">Имена каналов для разветвлений января и июля 2019 г. обновлены.</span><span class="sxs-lookup"><span data-stu-id="b6191-712">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-june-09"></a><span data-ttu-id="b6191-714">Версия 1902: 09 июня</span><span class="sxs-lookup"><span data-stu-id="b6191-714">Version 1902: June 09</span></span>
<span data-ttu-id="b6191-715">*Версия 1902 (сборка 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="b6191-715">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="b6191-716">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-716">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-718">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-718">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b6191-719">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-719">Office Suite</span></span>

- <span data-ttu-id="b6191-720">Имена каналов для разветвлений января и июля 2019 г. обновлены.</span><span class="sxs-lookup"><span data-stu-id="b6191-720">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="b6191-721">Устаревшие ссылки удалены из базовых файлов, которые разрушали сборку C2R.</span><span class="sxs-lookup"><span data-stu-id="b6191-721">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-may-12"></a><span data-ttu-id="b6191-723">Версия 1908: 12 мая</span><span class="sxs-lookup"><span data-stu-id="b6191-723">Version 1908: May 12</span></span>
<span data-ttu-id="b6191-724">*Версия 1908 (сборка 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="b6191-724">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="b6191-725">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-725">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-727">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-727">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-728">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-728">Excel</span></span>

- <span data-ttu-id="b6191-729">При копировании данных, отфильтрованных по цвету, в столбец с другой шириной, значения не вставляются.</span><span class="sxs-lookup"><span data-stu-id="b6191-729">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-730">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-730">Outlook</span></span>

- <span data-ttu-id="b6191-731">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="b6191-731">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-732">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-732">Word</span></span>

- <span data-ttu-id="b6191-733">Исправлена проблема с объединением двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="b6191-733">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b6191-734">Исправлена проблема с функцией сравнения для документов, защищенных для редактирования.</span><span class="sxs-lookup"><span data-stu-id="b6191-734">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-may-12"></a><span data-ttu-id="b6191-736">Версия 1902: 12 мая</span><span class="sxs-lookup"><span data-stu-id="b6191-736">Version 1902: May 12</span></span>
<span data-ttu-id="b6191-737">*Версия 1902 (сборка 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="b6191-737">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="b6191-738">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-738">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-740">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b6191-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-741">Outlook</span></span>

- <span data-ttu-id="b6191-742">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="b6191-742">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="b6191-743">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="b6191-743">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="b6191-744">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="b6191-744">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="b6191-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="b6191-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="b6191-746">0 = по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="b6191-746">0 = Default.</span></span>  <span data-ttu-id="b6191-747">1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="b6191-747">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-may-04"></a><span data-ttu-id="b6191-749">Версия 1908: 04 мая</span><span class="sxs-lookup"><span data-stu-id="b6191-749">Version 1908: May 04</span></span>
<span data-ttu-id="b6191-750">*Версия 1908 (сборка 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="b6191-750">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="b6191-751">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b6191-752">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-752">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b6191-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-753">Outlook</span></span>

- <span data-ttu-id="b6191-754">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="b6191-754">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="b6191-755">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="b6191-755">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b6191-756">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="b6191-756">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="b6191-757"> Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="b6191-757"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="b6191-758"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="b6191-758"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="b6191-759">0 = по умолчанию 1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="b6191-759"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-760">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-760">Office Suite</span></span>

- <span data-ttu-id="b6191-761">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="b6191-761">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="b6191-762">Версия 1902: 04 мая</span><span class="sxs-lookup"><span data-stu-id="b6191-762">Version 1902: May 04</span></span>
<span data-ttu-id="b6191-763">*Версия 1902 (сборка 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="b6191-763">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b6191-764">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-764">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b6191-765">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-765">Office Suite</span></span>

- <span data-ttu-id="b6191-766">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="b6191-766">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="b6191-767">Версия 1908: 26 апреля</span><span class="sxs-lookup"><span data-stu-id="b6191-767">Version 1908: April 26</span></span>
<span data-ttu-id="b6191-768">*Версия 1908 (сборка 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="b6191-768">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="b6191-769">Обновления системы безопасности и исправления перечислены  [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates).</span><span class="sxs-lookup"><span data-stu-id="b6191-769">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b6191-770">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-770">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-771">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-771">Excel</span></span>

- <span data-ttu-id="b6191-772">Устранена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="b6191-772">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b6191-773">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-773">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="b6191-774">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-774">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="b6191-775">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-775">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="b6191-776">OneNote</span><span class="sxs-lookup"><span data-stu-id="b6191-776">OneNote</span></span>

- <span data-ttu-id="b6191-777">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="b6191-777">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="b6191-778">Версия 1908: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="b6191-778">Version 1908: April 14</span></span>
<span data-ttu-id="b6191-779">*Версия 1908 (сборка 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="b6191-779">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="b6191-780">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-780">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-782">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-782">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-783">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-783">Excel</span></span>

- <span data-ttu-id="b6191-784">Исправлена проблема, приводившая к снижению производительности при удалении столбцов, содержащих объединенные ячейки.</span><span class="sxs-lookup"><span data-stu-id="b6191-784">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="b6191-785">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-785">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="b6191-786">Skype</span><span class="sxs-lookup"><span data-stu-id="b6191-786">Skype</span></span>

- <span data-ttu-id="b6191-787">Исправлено название вкладки беседы при наличии нескольких активных бесед.</span><span class="sxs-lookup"><span data-stu-id="b6191-787">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-788">Outlook</span></span>

- <span data-ttu-id="b6191-789">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при закрытии Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-789">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="b6191-790">Исправлена проблема, приводившая к отображению пустого списка помещений в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="b6191-790">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b6191-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-791">PowerPoint</span></span>

- <span data-ttu-id="b6191-792">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="b6191-792">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-793">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-793">Word</span></span>

- <span data-ttu-id="b6191-794">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="b6191-794">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="b6191-795">Версия 1902: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="b6191-795">Version 1902: April 14</span></span>
<span data-ttu-id="b6191-796">*Версия 1902 (сборка 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="b6191-796">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="b6191-797">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-797">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-march-10"></a><span data-ttu-id="b6191-799">Версия 1908: 10 марта</span><span class="sxs-lookup"><span data-stu-id="b6191-799">Version 1908: March 10</span></span>
<span data-ttu-id="b6191-800">*Версия 1908 (сборка 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="b6191-800">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="b6191-801">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-801">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-803">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-803">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-804">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-804">Excel</span></span>

- <span data-ttu-id="b6191-805">Исправлена проблема, из-за которой у некоторых пользователей появлялось несколько всплывающих окон при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="b6191-805">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="b6191-806">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="b6191-806">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="b6191-807">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="b6191-807">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b6191-808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-808">PowerPoint</span></span>

- <span data-ttu-id="b6191-809">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="b6191-809">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="b6191-810">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-810">Word</span></span>

- <span data-ttu-id="b6191-811">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="b6191-811">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b6191-812">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-812">Office Suite</span></span>

- <span data-ttu-id="b6191-813">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="b6191-813">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="b6191-814">Версия 1902: 10 марта</span><span class="sxs-lookup"><span data-stu-id="b6191-814">Version 1902: March 10</span></span>
<span data-ttu-id="b6191-815">*Версия 1902 (сборка 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="b6191-815">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="b6191-816">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-816">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="b6191-818">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="b6191-818">Version 1908: February 11</span></span>
<span data-ttu-id="b6191-819">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="b6191-819">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="b6191-820">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-820">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-822">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-822">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-823">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-823">Excel</span></span>

- <span data-ttu-id="b6191-824">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="b6191-824">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="b6191-825">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-825">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="b6191-826">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="b6191-826">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="b6191-827">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="b6191-827">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="b6191-828">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="b6191-828">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="b6191-829">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="b6191-829">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="b6191-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-830">Outlook</span></span>

- <span data-ttu-id="b6191-831">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="b6191-831">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="b6191-832">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="b6191-832">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="b6191-833">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-833">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="b6191-834">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-834">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="b6191-835">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="b6191-835">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="b6191-836">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="b6191-836">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="b6191-837">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="b6191-837">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b6191-838">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-838">PowerPoint</span></span>

- <span data-ttu-id="b6191-839">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="b6191-839">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="b6191-840">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="b6191-840">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="b6191-841">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="b6191-841">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="b6191-842">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-842">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="b6191-843">Project</span><span class="sxs-lookup"><span data-stu-id="b6191-843">Project</span></span>

- <span data-ttu-id="b6191-844">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="b6191-844">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-845">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-845">Word</span></span>

- <span data-ttu-id="b6191-846">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="b6191-846">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-847">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-847">Office Suite</span></span>

- <span data-ttu-id="b6191-848">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-848">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-february-11"></a><span data-ttu-id="b6191-850">Версия 1902: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="b6191-850">Version 1902: February 11</span></span>
<span data-ttu-id="b6191-851">*Версия 1902 (сборка 11328,20526)*</span><span class="sxs-lookup"><span data-stu-id="b6191-851">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="b6191-852">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-852">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-854">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-854">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b6191-855">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-855">Outlook</span></span>

- <span data-ttu-id="b6191-856">Решает проблему, из-за которой пользователи сталкивались с алгоритмом шифрования, не поддерживаются ошибки при отправке зашифрованных писем.</span><span class="sxs-lookup"><span data-stu-id="b6191-856">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="b6191-857">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-857">Word</span></span>

- <span data-ttu-id="b6191-858">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="b6191-858">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-1808-february-11"></a><span data-ttu-id="b6191-861">Версия 1808: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="b6191-861">Version 1808: February 11</span></span>
<span data-ttu-id="b6191-862">*Версия 1808 (сборка 10730,20438)*</span><span class="sxs-lookup"><span data-stu-id="b6191-862">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="b6191-863">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-863">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="b6191-865">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="b6191-865">Version 1908: January 14</span></span>
<span data-ttu-id="b6191-866">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="b6191-866">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="b6191-867">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-867">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="b6191-869">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="b6191-869">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b6191-870">Access</span><span class="sxs-lookup"><span data-stu-id="b6191-870">Access</span></span>

- <span data-ttu-id="b6191-871">**Отслеживание объектов базы данных.** Не теряйте из виду активную вкладку, легко перетаскивайте вкладки для изменения их порядка и закрывайте объекты базы данных одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="b6191-871">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="b6191-872">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="b6191-872">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b6191-873">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="b6191-873">Switching between them has never been easier.</span></span> [<span data-ttu-id="b6191-874">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-874">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b6191-875">**Изменение масштаба стало удобнее.** Увеличивайте поле масштаба и меняйте шрифт — все эти параметры сохранятся.</span><span class="sxs-lookup"><span data-stu-id="b6191-875">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="b6191-876">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-876">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="b6191-877">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-877">Excel</span></span>

- <span data-ttu-id="b6191-878">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="b6191-878">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b6191-879">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="b6191-879">Switching between them has never been easier.</span></span> [<span data-ttu-id="b6191-880">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-880">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b6191-881">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="b6191-881">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="b6191-882">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="b6191-882">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b6191-883">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="b6191-883">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b6191-884">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="b6191-884">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b6191-885">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="b6191-885">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b6191-886">**Добавление живых красок в таблицы.** Вставляйте в книгу анимированные трехмерные изображения, чтобы показать, как бьется сердце, вращается планета или рычит тираннозавр.</span><span class="sxs-lookup"><span data-stu-id="b6191-886">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="b6191-887">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-887">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="b6191-p175">**Узнайте больше о своих данных.** Новая кнопка "Идеи" позволяет находить закономерности в данных и предлагает интеллектуальные, индивидуальные решения на их основе. [Подробнее](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="b6191-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="b6191-890">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="b6191-890">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="b6191-891">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="b6191-891">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="b6191-892">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-892">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="b6191-893">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="b6191-893">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="b6191-894">Также можно легко находить функции, столбцы и параметры.</span><span class="sxs-lookup"><span data-stu-id="b6191-894">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="b6191-895">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="b6191-895">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b6191-896">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="b6191-896">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b6191-897">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-897">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="b6191-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-898">Outlook</span></span>

- <span data-ttu-id="b6191-899">**Мы обновили интерфейс Outlook для вас.** Упрощенный интерфейс, ранее доступный для предпросмотра с помощью функции "Ожидается в ближайшее время", чтобы вы могли сосредоточиться на самом важном.</span><span class="sxs-lookup"><span data-stu-id="b6191-899">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="b6191-900">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-900">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="b6191-901">**Упрощенная лента с возможностью настройки.** Наслаждайтесь одной упрощенной строкой, содержащей наиболее часто используемые кнопки.</span><span class="sxs-lookup"><span data-stu-id="b6191-901">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="b6191-902">Легко переключайтесь между классическим и упрощенным представлением, а также закрепляйте и открепляйте команды.</span><span class="sxs-lookup"><span data-stu-id="b6191-902">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="b6191-903">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-903">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="b6191-904">**Продолжение работы при перемещении сообщений.** Outlook теперь перемещает сообщения в фоновом режиме, чтобы вы могли продолжать работу во время перемещения большого количества сообщений между папками.</span><span class="sxs-lookup"><span data-stu-id="b6191-904">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="b6191-905">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время окончания собрания на 5–10 минут раньше по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="b6191-905">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="b6191-906">**Выбор избранного действия.** Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="b6191-906">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="b6191-907">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="b6191-907">How about Archive or Mark as Read?</span></span> <span data-ttu-id="b6191-908">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="b6191-908">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="b6191-p182">**Все смогут понять, что вы имели в виду.** Если текста или статических изображений недостаточно, воспользуйтесь файлами GIF с анимацией, чтобы донести свою идею. [Подробнее](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="b6191-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="b6191-911">**Быстрое добавление учетных записей.** Благодаря улучшениям в настройке учетных записей теперь еще проще добавлять учетные записи Outlook.com и Gmail, использующие 2-факторную проверку подлинности в Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-911">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="b6191-912">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-912">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="b6191-913">**Забудьте об ограничениях синхронизации.** Улучшения Outlook устраняют ограничение для папок, позволяя синхронизировать общие почтовые ящики.</span><span class="sxs-lookup"><span data-stu-id="b6191-913">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="b6191-914">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="b6191-914">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b6191-915">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="b6191-915">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b6191-916">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-916">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="b6191-917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-917">PowerPoint</span></span>

- <span data-ttu-id="b6191-918">**Улучшенное изменение формы.** Назовите свои фигуры, чтобы лучше управлять их трансформацией.</span><span class="sxs-lookup"><span data-stu-id="b6191-918">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="b6191-919">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-919">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="b6191-920">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="b6191-920">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b6191-921">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="b6191-921">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b6191-922">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="b6191-922">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="b6191-923">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="b6191-923">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b6191-924">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="b6191-924">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b6191-925">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="b6191-925">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b6191-926">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="b6191-926">Switching between them has never been easier.</span></span> [<span data-ttu-id="b6191-927">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-927">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b6191-928">**Новое расположение для видео из Интернета.** Сохраняйте видео в Microsoft Stream, чтобы его могли просматривать все пользователи организации.</span><span class="sxs-lookup"><span data-stu-id="b6191-928">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="b6191-929">Вставьте ссылку на видео и наслаждайтесь мультимедийной презентацией, размер которой составляет лишь часть от размера файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-929">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="b6191-930">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-930">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="b6191-931">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-931">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b6191-p190">**Тест или опрос для аудитории.** Добавьте на слайд тест или опрос. Набор Office соберет и сохранит все ответы. [Подробнее](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="b6191-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="b6191-p191">**Вставлять видео из Интернета стало еще проще.** Хотите разместить на своем слайде видео из Vimeo или YouTube? Вам потребуется лишь ссылка на страницу с видео. [Подробнее](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="b6191-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="b6191-938">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="b6191-938">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b6191-939">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="b6191-939">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b6191-940">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-940">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="b6191-941">Project</span><span class="sxs-lookup"><span data-stu-id="b6191-941">Project</span></span>

- <span data-ttu-id="b6191-942">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="b6191-942">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b6191-943">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="b6191-943">Switching between them has never been easier.</span></span> [<span data-ttu-id="b6191-944">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-944">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="b6191-945">Visio</span><span class="sxs-lookup"><span data-stu-id="b6191-945">Visio</span></span>

- <span data-ttu-id="b6191-946">**Экспорт схем процессов в Word.** Автоматически добавляйте содержимое схем, например фигуры и метаданные, в документ Word.</span><span class="sxs-lookup"><span data-stu-id="b6191-946">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="b6191-947">Затем настройте документ для создания руководств по обработке и использованию.</span><span class="sxs-lookup"><span data-stu-id="b6191-947">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="b6191-948">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-948">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="b6191-949">**Переосмысление блок-схем данных.** Замечательные новые макеты для блок-схем визуализатора данных просты, лаконичны и удобны для понимания.</span><span class="sxs-lookup"><span data-stu-id="b6191-949">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="b6191-950">Для выбора перейдите на вкладку "Конструктор".</span><span class="sxs-lookup"><span data-stu-id="b6191-950">Click the Design tab for options.</span></span>

- <span data-ttu-id="b6191-951">**Встроенные наборы элементов Azure.** Разрабатывайте облачное приложение или планируйте архитектуру с помощью множества наборов элементов Azure.</span><span class="sxs-lookup"><span data-stu-id="b6191-951">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="b6191-952">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-952">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="b6191-p197">**Попрощайтесь с неработающими ссылками Excel.** Не удается найти книгу Excel, связанную со схемой визуализатора данных? Свяжите ее повторно и продолжайте работу. [Подробнее](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="b6191-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="b6191-956">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="b6191-956">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b6191-957">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="b6191-957">Switching between them has never been easier.</span></span> [<span data-ttu-id="b6191-958">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-958">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b6191-959">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="b6191-959">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="b6191-960">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-960">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="b6191-961">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-961">Word</span></span>

- <span data-ttu-id="b6191-962">**Поддержка дополнительных цветов страниц в режиме средств обучения.** Теперь средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="b6191-962">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="b6191-963">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="b6191-963">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="b6191-p201">**Естественное редактирование с помощью Правок от руки.** Разделяйте и объединяйте слова, добавляйте новые строки и вставляйте текст одним движением пера. [Подробнее](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="b6191-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="b6191-p202">**Преобразуйте статические документы.** Преобразуйте документы в интерактивные веб-страницы, которые прекрасно выглядят на любом устройстве и которыми легко делиться. [Подробнее](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="b6191-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="b6191-968">**Расширение доступа к содержимому.** Нужно сделать документы доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="b6191-968">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="b6191-969">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="b6191-969">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="b6191-970">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="b6191-970">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="b6191-971">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="b6191-971">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b6191-972">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="b6191-972">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="b6191-973">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="b6191-973">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="b6191-974">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="b6191-974">Switching between them has never been easier.</span></span> [<span data-ttu-id="b6191-975">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-975">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="b6191-p206">**Улучшение восприятия с помощью выделения строк.** Перемещайтесь по документу построчно, ни на что не отвлекаясь. Настройте выделение одной, трех или пяти строк одновременно. [Подробнее](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="b6191-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="b6191-979">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-979">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b6191-980">**Привлечение внимания с помощью \@@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="b6191-980">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="b6191-981">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-981">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="b6191-982">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="b6191-982">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="b6191-983">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="b6191-983">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="b6191-984">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-984">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="b6191-985">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-985">Office Suite</span></span>

- <span data-ttu-id="b6191-986">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="b6191-986">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="b6191-987">Просто воспользуйтесь полем поиска на вкладке "Файл" > "Открыть", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="b6191-987">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="b6191-988">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-988">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="b6191-989">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="b6191-989">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="b6191-990">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-990">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="b6191-991">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="b6191-991">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="b6191-992">**Установка Microsoft Teams.** Microsoft Teams по умолчанию устанавливается для существующих экземпляров Office 365 профессиональный плюс.</span><span class="sxs-lookup"><span data-stu-id="b6191-992">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="b6191-993">Подробнее</span><span class="sxs-lookup"><span data-stu-id="b6191-993">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-996">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-996">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b6191-997">Access</span><span class="sxs-lookup"><span data-stu-id="b6191-997">Access</span></span>

- <span data-ttu-id="b6191-998">Это обновление исправляет проблему, из-за которой агрегатная функция, например, Sum, может обрезать результат до целого значения.</span><span class="sxs-lookup"><span data-stu-id="b6191-998">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="b6191-999">Это обновление исправляет проблему, из-за которой запрос на объединение, включающий ссылки на удаленные таблицы (например, таблицы SQL Server), может приводить к закрытию и перезапуску Access.</span><span class="sxs-lookup"><span data-stu-id="b6191-999">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="b6191-1000">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке &quot;Запрос поврежден&quot; при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="b6191-1000">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="b6191-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-1001">Excel</span></span>

- <span data-ttu-id="b6191-1002">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="b6191-1002">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="b6191-1003">Устранена проблема в Excel, из-за которой при выполнении макросов, присвоенных фигурам или элементам управления формы, выводятся неправильные сообщения об ошибке или эти макросы работают в неправильном целевом диапазоне.</span><span class="sxs-lookup"><span data-stu-id="b6191-1003">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="b6191-1004">Решена проблема, при которой содержимое диалогового окна "Поиск и замена" изменялось, если курсор находился в нем после нахождения первого элемента.</span><span class="sxs-lookup"><span data-stu-id="b6191-1004">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="b6191-1005">Исправлена проблема, из-за которой изменение способа сортировки сводной таблицы и ее обновление в сеансе совместного редактирования с другими пользователями могло приводить к сбою.</span><span class="sxs-lookup"><span data-stu-id="b6191-1005">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="b6191-1006">Исправлена проблема, при которой для фильтра сводной таблицы OLAP было задано значение, удаленное из куба.</span><span class="sxs-lookup"><span data-stu-id="b6191-1006">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="b6191-1007">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм.</span><span class="sxs-lookup"><span data-stu-id="b6191-1007">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="b6191-1008">Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="b6191-1008">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="b6191-1009">Устранена проблема, приводившая к нарушению синхронизации каскадных и воронкообразных диаграмм с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="b6191-1009">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="b6191-1010">Исправлена проблема с конфликтом слияния в Excel, из-за которой пользователям предлагалось повторно открыть книгу, чтобы внести изменения.</span><span class="sxs-lookup"><span data-stu-id="b6191-1010">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="b6191-1011">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-1011">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b6191-1012">Исправлена проблема, которая была причиной ошибки времени выполнения макроса при активации свернутых окон.</span><span class="sxs-lookup"><span data-stu-id="b6191-1012">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="b6191-1013">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-1013">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="b6191-1014">Устранена проблема, из-за которой вырезание и вставка в таблице не выполняются при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="b6191-1014">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="b6191-1015">Решена проблема, вызывавшая прерывание совместного редактирования при изменении настраиваемых свойств с помощью макросов.</span><span class="sxs-lookup"><span data-stu-id="b6191-1015">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="b6191-1016">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытом надстройкой.</span><span class="sxs-lookup"><span data-stu-id="b6191-1016">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="b6191-1017">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="b6191-1017">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="b6191-1018">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="b6191-1018">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="b6191-1019">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="b6191-1019">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="b6191-1020">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="b6191-1020">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="b6191-1021">Исправлена проблема, из-за которой функция Lookup может возвращать ошибку.</span><span class="sxs-lookup"><span data-stu-id="b6191-1021">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="b6191-1022">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office.</span><span class="sxs-lookup"><span data-stu-id="b6191-1022">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="b6191-1023">Проблема низкой производительности при нажатии кнопки "Цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="b6191-1023">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="b6191-1024">Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати.</span><span class="sxs-lookup"><span data-stu-id="b6191-1024">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="b6191-1025">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="b6191-1025">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="b6191-1026">Значительно повышена производительность фильтрации по цвету.</span><span class="sxs-lookup"><span data-stu-id="b6191-1026">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="b6191-1027">Устранена проблема, мешавшая вставке гиперссылок в некоторых защищенных листах.</span><span class="sxs-lookup"><span data-stu-id="b6191-1027">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="b6191-1028">Поддерживается отображение более 16 надстроек при просмотре в диспетчере надстроек.</span><span class="sxs-lookup"><span data-stu-id="b6191-1028">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="b6191-1029">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="b6191-1029">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="b6191-1030">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-1030">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-1031">Это обновление устраняет ошибку, из-за которой документы Office могут не отправляться в OneDrive для бизнеса и приходит сообщение "Не удалось выполнить отправку".</span><span class="sxs-lookup"><span data-stu-id="b6191-1031">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="b6191-1032">Устранена проблема в функции "Идеи" для Excel, приводившая к ошибке при загрузке надстройки путем нажатия на кнопку "Идеи" в клиенте Win32.</span><span class="sxs-lookup"><span data-stu-id="b6191-1032">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-1033">Outlook</span></span>

- <span data-ttu-id="b6191-1034">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-1034">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-1035">Исправлена проблема, из-за которой обновление в почтовых ящиках пользователей обычной проверки подлинности до современной приводило к привязыванию неправильной учетной записи к профилю Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-1035">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="b6191-1036">Исправлена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами, когда это не предполагалось.</span><span class="sxs-lookup"><span data-stu-id="b6191-1036">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="b6191-1037">Исправлена проблема, из-за которой URL-адреса не открывались при простом наведении на некоторые безопасные ссылки.</span><span class="sxs-lookup"><span data-stu-id="b6191-1037">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="b6191-1038">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="b6191-1038">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="b6191-1039">Исправлена проблема, из-за которой у подмножества пользователей POP3 сообщения электронной почты выводятся в виде обычного текста, независимо от настроек.</span><span class="sxs-lookup"><span data-stu-id="b6191-1039">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="b6191-1040">Это исправление восстановит сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="b6191-1040">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="b6191-1041">Решена проблема, из-за которой возникала ошибка доступа при копировании элементов из основного календаря в календарь группы.</span><span class="sxs-lookup"><span data-stu-id="b6191-1041">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="b6191-1042">Исправлена проблема, из-за которой пользователям были недоступны предложения расположений при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="b6191-1042">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="b6191-1043">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="b6191-1043">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="b6191-1044">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-1044">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="b6191-1045">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="b6191-1045">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="b6191-1046">Решена проблема, вызывавшая сбой в Outlook при взаимодействии пользователей с определенными безопасными ссылками.</span><span class="sxs-lookup"><span data-stu-id="b6191-1046">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="b6191-1047">Исправлена проблема, из-за которой менеджеры не могли установить, ответил ли участник на предоставленное приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="b6191-1047">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="b6191-1048">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="b6191-1048">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b6191-1049">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="b6191-1049">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="b6191-1050">Это изменение позволяет администраторам включать политику, предпочитающую указанную учетную запись электронной почты в запросах проверки подлинности службы автообнаружения вместо имени участника-пользователя (UPN).</span><span class="sxs-lookup"><span data-stu-id="b6191-1050">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="b6191-1051">По умолчанию при автообнаружении предпочтение отдается UPN учетной записи (при наличии).</span><span class="sxs-lookup"><span data-stu-id="b6191-1051">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="b6191-1052">Исправлена проблема, вызывавшая сбой поиска в современных группах.</span><span class="sxs-lookup"><span data-stu-id="b6191-1052">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="b6191-1053">Исправлена проблема, приводившая к зависанию пользователей Outlook в состоянии "Требуется пароль" в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="b6191-1053">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="b6191-1054">Исправлена проблема, из-за которой пользователям предлагались помещения для собраний, проводимых в период времени, когда эти помещения недоступны.</span><span class="sxs-lookup"><span data-stu-id="b6191-1054">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="b6191-1055">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="b6191-1055">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="b6191-1056">Исправлена проблема для неанглоязычных пользователей, из-за которой строка темы в почте отображалась очень маленькой.</span><span class="sxs-lookup"><span data-stu-id="b6191-1056">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="b6191-1057">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="b6191-1057">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="b6191-1058">Исправлена проблема, приводившая к сбою при попытке пользователей создать правило на основе сообщения о пропущенной беседе.</span><span class="sxs-lookup"><span data-stu-id="b6191-1058">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="b6191-1059">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="b6191-1059">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="b6191-1060">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="b6191-1060">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="b6191-1061">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-1061">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="b6191-1062">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="b6191-1062">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="b6191-1063">Устранена проблема, которая приводила к периодическому сбою поиска в текущей папке.</span><span class="sxs-lookup"><span data-stu-id="b6191-1063">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="b6191-1064">Исправлена проблема, из-за которой некоторые пользователи сталкивались с ошибками проверки подлинности при попытке получить свои облачные параметры для Outlook.</span><span class="sxs-lookup"><span data-stu-id="b6191-1064">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="b6191-1065">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="b6191-1065">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="b6191-1066">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="b6191-1066">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="b6191-1067">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="b6191-1067">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b6191-1068">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-1068">PowerPoint</span></span>

- <span data-ttu-id="b6191-1069">Устранена проблема, из-за которой некоторые надстройки создавали непредвиденные ошибки вокруг фигур в диаграммах.</span><span class="sxs-lookup"><span data-stu-id="b6191-1069">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="b6191-1070">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-1070">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-1071">Это изменение восстанавливает доступное имя для элементов управления видео в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-1071">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="b6191-1072">Исправлена проблема, из-за которой мог блокироваться запуск некоторых анимаций.</span><span class="sxs-lookup"><span data-stu-id="b6191-1072">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="b6191-1073">Исправлена проблема, из-за которой при копировании слайда из одной презентации в другую могли появляться дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="b6191-1073">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="b6191-1074">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="b6191-1074">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="b6191-1075">Исправление проблем с надежностью. Устранена проблема, из-за которой надстройка стороннего поставщика могла вызывать сбой PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-1075">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="b6191-1076">Исправлена проблема, из-за которой не удавалось правильно повернуть полуширинные знаки катаканы при использовании вертикальных текстовых полей в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-1076">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="b6191-1077">Project</span><span class="sxs-lookup"><span data-stu-id="b6191-1077">Project</span></span>

- <span data-ttu-id="b6191-1078">Исправлена проблема, чтобы разрешить пользователям в Windows 7 открывать проекты из Project Web App и сайтов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-1078">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="b6191-1079">Обнаружена проблема, из-за которой пользователи могли получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="b6191-1079">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="b6191-1080">Команда "Выровнять все" не устраняет должным образом превышение доступности ресурсов.</span><span class="sxs-lookup"><span data-stu-id="b6191-1080">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="b6191-1081">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="b6191-1081">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="b6191-1082">Visio</span><span class="sxs-lookup"><span data-stu-id="b6191-1082">Visio</span></span>

- <span data-ttu-id="b6191-1083">Экспорт в формате SVG из Visio не работал для различных фигур.</span><span class="sxs-lookup"><span data-stu-id="b6191-1083">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-1084">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-1084">Word</span></span>

- <span data-ttu-id="b6191-1085">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="b6191-1085">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="b6191-1086">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="b6191-1086">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="b6191-1087">Исправлена проблема, из-за которой могли возникать проблемы с масштабированием при печати на принтерах Deskjet.</span><span class="sxs-lookup"><span data-stu-id="b6191-1087">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="b6191-1088">Исправлена проблема с отслеживанием изменений, которые иногда переходят в режим бесконечного цикла. </span><span class="sxs-lookup"><span data-stu-id="b6191-1088">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="b6191-1089">Исправлены различные проблемы, из-за которых приложение может зависнуть при завершении работы.</span><span class="sxs-lookup"><span data-stu-id="b6191-1089">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="b6191-1090">Также исправлены некоторые ошибки, связанные с надстройками.</span><span class="sxs-lookup"><span data-stu-id="b6191-1090">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b6191-1091">Набор Office</span><span class="sxs-lookup"><span data-stu-id="b6191-1091">Office Suite</span></span>

- <span data-ttu-id="b6191-1092">Исправлена проблема с неправильным определением названия новой эры "Рэйва" в хирагана и кандзи как выражения с опечаткой или грамматической ошибкой.</span><span class="sxs-lookup"><span data-stu-id="b6191-1092">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="b6191-1093">Исправлена проблема, из-за которой пользователи получали сообщение "Не удалось предоставить общий доступ" при попытке поделиться файлами, хранящимися в SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="b6191-1093">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="b6191-1094">Исправлена проблема, которая могла приводить к потере данных в сеансах, включающих как совместное редактирование, так и редактирование в автономном режиме в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-1094">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="b6191-1095">Исправлена проблема, из-за которой мог произойти сбой при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="b6191-1095">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="b6191-1096">Исправление позволяет пользователям PowerPoint избежать ошибки при попытке онлайн-презентации.</span><span class="sxs-lookup"><span data-stu-id="b6191-1096">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="b6191-1097">В некоторых случаях файл SharePoint, сохраненный с помощью модуля синхронизации, отображал состояние "Сохранено", но в действительности изменения не сохранялись. Это приводило к потере данных.</span><span class="sxs-lookup"><span data-stu-id="b6191-1097">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="b6191-1098">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="b6191-1098">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="b6191-1099">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как диалоговое окно", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="b6191-1099">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="b6191-1100">Устранена проблема с быстродействием Win7, из-за которой вставленная коллекция фигур с ленты во всех приложениях отображалась примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="b6191-1100">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="b6191-1101">Исправлена ошибка, из-за которой сведения о специальных возможностях не отображались в области сведений представления Backstage.</span><span class="sxs-lookup"><span data-stu-id="b6191-1101">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="b6191-1102">Повышена надежность процесса обновления Office в отношении целостности реестра.</span><span class="sxs-lookup"><span data-stu-id="b6191-1102">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="b6191-1103">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b6191-1103">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="b6191-1104">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="b6191-1104">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="b6191-1105">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="b6191-1105">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="b6191-1106">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="b6191-1106">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="b6191-1107">При определенных обстоятельствах ярлыки Office могут исчезнуть после обновления.</span><span class="sxs-lookup"><span data-stu-id="b6191-1107">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="b6191-1108">Это обновление повышает надежность при публикации ярлыков Office.</span><span class="sxs-lookup"><span data-stu-id="b6191-1108">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="b6191-1109">Исправлена проблема, из-за которой обновления могли неожиданно блокироваться в сетях с лимитным тарифным планом.</span><span class="sxs-lookup"><span data-stu-id="b6191-1109">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="b6191-1110">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="b6191-1110">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="b6191-1111">Повышена надежность при скачивании обновлений Office путем продолжения скачивания, которое ранее могло прерываться.</span><span class="sxs-lookup"><span data-stu-id="b6191-1111">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="b6191-1112">Устранены проблемы, связанные со свойством автоподбора размера текстовых полей и фигур в сторонних подключаемых модулях.</span><span class="sxs-lookup"><span data-stu-id="b6191-1112">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="b6191-1113">Исправлена проблема, из-за которой крупные представления в виде дерева приводили к сбою.</span><span class="sxs-lookup"><span data-stu-id="b6191-1113">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="b6191-1114">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="b6191-1114">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-january-14"></a><span data-ttu-id="b6191-1116">Версия 1902: 14 января</span><span class="sxs-lookup"><span data-stu-id="b6191-1116">Version 1902: January 14</span></span>
<span data-ttu-id="b6191-1117">*Версия 1902 (сборка 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="b6191-1117">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="b6191-1118">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-1118">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="b6191-1120">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="b6191-1120">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b6191-1121">Excel</span><span class="sxs-lookup"><span data-stu-id="b6191-1121">Excel</span></span>

- <span data-ttu-id="b6191-1122">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="b6191-1122">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="b6191-1123">Outlook</span><span class="sxs-lookup"><span data-stu-id="b6191-1123">Outlook</span></span>

- <span data-ttu-id="b6191-1124">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="b6191-1124">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b6191-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b6191-1125">PowerPoint</span></span>

- <span data-ttu-id="b6191-1126">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="b6191-1126">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="b6191-1127">Word</span><span class="sxs-lookup"><span data-stu-id="b6191-1127">Word</span></span>

- <span data-ttu-id="b6191-1128">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="b6191-1128">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1808-january-14"></a><span data-ttu-id="b6191-1130">Версия 1808: 14 января</span><span class="sxs-lookup"><span data-stu-id="b6191-1130">Version 1808: January 14</span></span>
<span data-ttu-id="b6191-1131">*Версия 1808 (сборка 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="b6191-1131">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="b6191-1132">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="b6191-1132">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="b6191-1134">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="b6191-1134">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
