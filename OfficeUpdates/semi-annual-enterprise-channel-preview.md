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
ms.openlocfilehash: d6c48db35445d15503c246506bc7d03da3ca0548
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/13/2021
ms.locfileid: "51748967"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="96f0a-103">Заметки о выпусках для Полугодового канала (предварительной корпоративной версии)</span><span class="sxs-lookup"><span data-stu-id="96f0a-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="96f0a-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (предварительная корпоративная версия) для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="96f0a-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="96f0a-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="96f0a-106">Подробнее см. в [этой статье](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="96f0a-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="96f0a-107">Версия 2102: 13 апреля</span><span class="sxs-lookup"><span data-stu-id="96f0a-107">Version 2102: April 13</span></span>
<span data-ttu-id="96f0a-108">*Версия 2102 (сборка 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="96f0a-109">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="96f0a-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-111">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-112">Access</span><span class="sxs-lookup"><span data-stu-id="96f0a-112">Access</span></span>

- <span data-ttu-id="96f0a-113">Исправлена проблема, из-за которой в некоторых случаях при выполнении запроса к серверу SQL Server могло возникать сообщение об ошибке, указывающее на "недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="96f0a-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="96f0a-114">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-114">Excel</span></span>

- <span data-ttu-id="96f0a-115">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="96f0a-116">Исправлена проблема, из-за которой проверка данных могла неожиданно применяться к ячейкам после добавления строк в таблицу на другом листе.</span><span class="sxs-lookup"><span data-stu-id="96f0a-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="96f0a-117">Исправлена проблема, из-за которой функция отображения DialogSheets не работала в 32-битных версиях Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-118">Outlook</span></span>

- <span data-ttu-id="96f0a-119">Исправлена проблема, которая вызывала сбой Outlook при простое.</span><span class="sxs-lookup"><span data-stu-id="96f0a-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="96f0a-120">Исправлена проблема, из-за которой пользовательские параметры функции "Параметры облака" менялись на значения по умолчанию после настройки Outlook на новом устройстве.</span><span class="sxs-lookup"><span data-stu-id="96f0a-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="96f0a-121">Исправлена проблема, из-за которой пользователи видели больше подписей, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-122">PowerPoint</span></span>

- <span data-ttu-id="96f0a-123">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="96f0a-124">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-124">Word</span></span>

- <span data-ttu-id="96f0a-125">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="96f0a-126">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="96f0a-127">Исправлена проблема, из-за которой набор текста в конце скрытого абзаца мог привести к зависанию приложения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-128">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-128">Office Suite</span></span>

- <span data-ttu-id="96f0a-129">Исправлена проблема, из-за которой пользователи не могли сохранить файл при открытии ранее открывавшегося файла с несохраненными правками, когда файл уже удален.</span><span class="sxs-lookup"><span data-stu-id="96f0a-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="96f0a-130">После исправления пользователи получат понятное сообщение о том, что файл удален, поэтому можно отменить изменения или сохранить файл с помощью функции "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="96f0a-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="96f0a-131">Исправлена ошибка переименования при открытии файла SyncBacked в автономном режиме, а затем переименовании файла в приложении перед сохранением файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="96f0a-132">Исправлена проблема, из-за которой для пользователей GCC была отключена Диктовка</span><span class="sxs-lookup"><span data-stu-id="96f0a-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="96f0a-133">Исправлена проблема, которая делала текст в Outlook прозрачным и поэтому невидимым.</span><span class="sxs-lookup"><span data-stu-id="96f0a-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-09"></a><span data-ttu-id="96f0a-135">Версия 2102: 9 марта</span><span class="sxs-lookup"><span data-stu-id="96f0a-135">Version 2102: March 09</span></span>
<span data-ttu-id="96f0a-136">*Версия 2102 (сборка 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="96f0a-137">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="96f0a-139">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="96f0a-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-140">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-140">Excel</span></span>

- <span data-ttu-id="96f0a-141">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="96f0a-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="96f0a-142">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="96f0a-143">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="96f0a-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="96f0a-144">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="96f0a-145">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="96f0a-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="96f0a-146">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="96f0a-147">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="96f0a-148">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="96f0a-149">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="96f0a-150">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="96f0a-151">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="96f0a-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="96f0a-152">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="96f0a-153">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="96f0a-154">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="96f0a-155">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 / Microsoft 365 и планом обслуживания Power BI Pro.</span><span class="sxs-lookup"><span data-stu-id="96f0a-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="96f0a-156">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="96f0a-157">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="96f0a-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="96f0a-158">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="96f0a-159">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="96f0a-160">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="96f0a-161">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="96f0a-161">No conversion required.</span></span><br /><span data-ttu-id="96f0a-162">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="96f0a-162">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="96f0a-163">**Создание профессиональных схем Visio в Excel.** Создавайте на листе схемы, основанные на данных, например блок-схемы или организационные диаграммы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="96f0a-164">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="96f0a-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-165">Outlook</span></span>

- <span data-ttu-id="96f0a-166">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="96f0a-167">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="96f0a-168">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="96f0a-169">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="96f0a-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="96f0a-170">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="96f0a-171">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="96f0a-171">No conversion required.</span></span><br /><span data-ttu-id="96f0a-172">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="96f0a-172">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="96f0a-173">**Новая функция "Поиск помещений".** Поиск конференц-залов с учетом различных возможностей. </span><span class="sxs-lookup"><span data-stu-id="96f0a-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="96f0a-174">**Поиск естественными фразами.** Используйте обычные фразы, например "запись к ветеринару на прошлой неделе", чтобы отфильтровать и сузить область поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="96f0a-175">**Быстрое повторное открытие элементов из предыдущего сеанса Outlook.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="96f0a-176">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/automatically-restore-windows-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="96f0a-176">See details in [blog post](https://insider.office.com/ru-RU/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="96f0a-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-177">PowerPoint</span></span>

- <span data-ttu-id="96f0a-178">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="96f0a-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="96f0a-179">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="96f0a-180">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="96f0a-181">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="96f0a-182">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="96f0a-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="96f0a-183">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="96f0a-184">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="96f0a-185">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="96f0a-186">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="96f0a-187">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="96f0a-187">No conversion required.</span></span><br /><span data-ttu-id="96f0a-188">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="96f0a-188">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="96f0a-189">Visio</span><span class="sxs-lookup"><span data-stu-id="96f0a-189">Visio</span></span>

- <span data-ttu-id="96f0a-190">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="96f0a-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="96f0a-191">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="96f0a-192">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-192">Word</span></span>

- <span data-ttu-id="96f0a-193">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="96f0a-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="96f0a-194">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="96f0a-195">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="96f0a-196">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="96f0a-197">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="96f0a-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="96f0a-198">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="96f0a-199">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="96f0a-200">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="96f0a-201">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="96f0a-202">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="96f0a-202">No conversion required.</span></span><br /><span data-ttu-id="96f0a-203">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="96f0a-203">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-204">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-204">Office Suite</span></span>

- <span data-ttu-id="96f0a-205">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="96f0a-206">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="96f0a-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="96f0a-207">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-210">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-211">Доступ</span><span class="sxs-lookup"><span data-stu-id="96f0a-211">Access</span></span>

- <span data-ttu-id="96f0a-212">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="96f0a-213">Исправлена проблема, из-за которой пользователям отображалось диалоговое окно "Недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="96f0a-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="96f0a-214">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-214">Excel</span></span>

- <span data-ttu-id="96f0a-215">Исправлена проблема, нарушавшая работу некоторых устаревших макросов Excel 4.0 и Excel 5.0, а также некоторых вызовов VBA в dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="96f0a-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="96f0a-216">Исправлена проблема, из-за которой Excel мог неожиданно закрываться при использовании меню "Дополнительные вычисления" для сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="96f0a-217">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="96f0a-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="96f0a-218">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании функции "Вставить связанный рисунок".</span><span class="sxs-lookup"><span data-stu-id="96f0a-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="96f0a-219">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="96f0a-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="96f0a-220">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="96f0a-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="96f0a-221">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="96f0a-222">Исправлена проблема, из-за которой для некоторых пользователей неверно отображалась панель сообщений, уведомляющая о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="96f0a-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="96f0a-223">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="96f0a-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="96f0a-224">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="96f0a-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="96f0a-225">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-226">Outlook</span></span>

- <span data-ttu-id="96f0a-227">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="96f0a-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="96f0a-228">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось в определенных сценариях поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="96f0a-229">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="96f0a-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="96f0a-230">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="96f0a-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="96f0a-231">Исправлена проблема, из-за которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="96f0a-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="96f0a-232">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="96f0a-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="96f0a-233">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="96f0a-234">Исправлена проблема, приводившая к зависаниям у некоторых пользователей при загрузке их календарей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="96f0a-235">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="96f0a-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="96f0a-236">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="96f0a-237">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="96f0a-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="96f0a-238">Исправлена проблема, из-за которой новые календари не появлялись в области навигации, пока пользователь не перезапустит Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="96f0a-239">Исправлена проблема, из-за которой при поиске в некэшированных общих календарях не возвращались никакие результаты.</span><span class="sxs-lookup"><span data-stu-id="96f0a-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="96f0a-240">Исправлена проблема, из-за которой у некоторых пользователей приложение закрывалось при закрытии окон сообщений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="96f0a-241">Исправлена проблема, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="96f0a-242">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="96f0a-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="96f0a-243">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при выполнении определенных сценариев поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="96f0a-244">Исправлена проблема, из-за которой приложение иногда неожиданно закрывалось, когда пользователи выполняли поиск в Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="96f0a-245">Исправлена проблема, приводившая к зависанию у пользователей облачных параметров при обновлении настроек.</span><span class="sxs-lookup"><span data-stu-id="96f0a-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="96f0a-246">Исправлена проблема, из-за которой не удавалось сохранить измененную подпись после предложения пользователю этого действия.</span><span class="sxs-lookup"><span data-stu-id="96f0a-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="96f0a-247">Исправлена проблема, из-за которой некоторые пользователи не видели подписей в раскрывающемся списке подписей, хотя у них настроена одна или несколько подписей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="96f0a-248">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="96f0a-249">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="96f0a-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="96f0a-250">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="96f0a-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="96f0a-251">Исправлена проблема, из-за которой возникали проблемы с отображением правильной подписи по умолчанию в OWA.</span><span class="sxs-lookup"><span data-stu-id="96f0a-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="96f0a-252">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="96f0a-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="96f0a-253">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="96f0a-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="96f0a-254">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="96f0a-255">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="96f0a-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="96f0a-256">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="96f0a-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="96f0a-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="96f0a-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="96f0a-258">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="96f0a-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="96f0a-259">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="96f0a-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="96f0a-260">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="96f0a-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="96f0a-261">Исправлена проблема, приводившая к исчезновению встроенных изображений при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="96f0a-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="96f0a-262">Исправлена проблема, из-за которой значок шифрования не отображался в сообщениях, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="96f0a-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="96f0a-263">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-264">PowerPoint</span></span>

- <span data-ttu-id="96f0a-265">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="96f0a-266">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="96f0a-267">Это изменение устраняет проблему с заливками путей при объединений фигур определенных геометрий.</span><span class="sxs-lookup"><span data-stu-id="96f0a-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="96f0a-268">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="96f0a-269">Это изменение устраняет проблему с обработкой ошибок, которые могут возникнуть во время загрузки видео.</span><span class="sxs-lookup"><span data-stu-id="96f0a-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="96f0a-270">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="96f0a-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="96f0a-271">Исправлена проблема, из-за которой команда размера шрифта, добавленная в QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="96f0a-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="96f0a-272">Исправлена проблема, приводившая к ошибке при сохранении файла после дублирования слайда, содержащего недавно записанный звук.</span><span class="sxs-lookup"><span data-stu-id="96f0a-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="96f0a-273">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="96f0a-274">Исправлена проблема с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="96f0a-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="96f0a-275">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="96f0a-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="96f0a-276">Исправление для устранения проблемы с использованием IRM/защищенных документов при возникновении ошибки слияния.</span><span class="sxs-lookup"><span data-stu-id="96f0a-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="96f0a-277">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="96f0a-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="96f0a-278">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="96f0a-279">Исправлена проблема, из-за которой в некоторых сценариях выбор идеи оформления удаляет метку классификации данных в презентации.</span><span class="sxs-lookup"><span data-stu-id="96f0a-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="96f0a-280">Project</span><span class="sxs-lookup"><span data-stu-id="96f0a-280">Project</span></span>

- <span data-ttu-id="96f0a-281">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="96f0a-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="96f0a-282">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="96f0a-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="96f0a-283">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="96f0a-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="96f0a-284">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="96f0a-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="96f0a-285">Устранена проблема, при которой отдельные проекты могли открываться при наличии проблемы в какой-либо части загрузки файла проекта.</span><span class="sxs-lookup"><span data-stu-id="96f0a-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="96f0a-286">Исправлена проблема, из-за которой границы не отображались для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="96f0a-287">Исправлена проблема, из-за которой не работало перетаскивание для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="96f0a-288">Устранена проблема, из-за которой сведение базовых затрат выполнялось неправильно, если затратный ресурс был назначен задаче-вехе.</span><span class="sxs-lookup"><span data-stu-id="96f0a-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="96f0a-289">Visio</span><span class="sxs-lookup"><span data-stu-id="96f0a-289">Visio</span></span>

- <span data-ttu-id="96f0a-290">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="96f0a-291">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-291">Word</span></span>

- <span data-ttu-id="96f0a-292">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="96f0a-293">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="96f0a-294">Это изменение исправляет проблему, связанную с курсором при редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="96f0a-295">Исправлена проблема с применением цветовой гаммы к значкам и изображениям SVG с трехмерными эффектами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="96f0a-296">Исправлена проблема, из-за которой диктор иногда пропускает абзац.</span><span class="sxs-lookup"><span data-stu-id="96f0a-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="96f0a-297">Исправлена проблема с элементами управления форматированным текстом.</span><span class="sxs-lookup"><span data-stu-id="96f0a-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="96f0a-298">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="96f0a-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="96f0a-299">Устранена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="96f0a-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="96f0a-300">Исправлена ошибка, из-за которой стили документов заменялись другими стилями из шаблона.</span><span class="sxs-lookup"><span data-stu-id="96f0a-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="96f0a-301">Исправление ошибки утверждения, вызываемой оптимизированными шлюзами, затрагивающими Word.</span><span class="sxs-lookup"><span data-stu-id="96f0a-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-302">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-302">Office Suite</span></span>

- <span data-ttu-id="96f0a-303">Исправлена проблема, вызывавшая сбой при попытке сохранить файлы, перешедшие из состояния "синхронизировано" в состояние "только для сервера".</span><span class="sxs-lookup"><span data-stu-id="96f0a-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="96f0a-304">Исправлена проблема, из-за которой попытка выполнить действие "Сохранить как" завершалась неудачей в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="96f0a-305">Исправлена проблема, из-за которой параметр SaveRequestManagerCam приводил к закрытию приложения, а не возвращал ошибку.</span><span class="sxs-lookup"><span data-stu-id="96f0a-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="96f0a-306">Исправлена последовательность закрытия файлов. Теперь все независимые компоненты закрываются правильно.</span><span class="sxs-lookup"><span data-stu-id="96f0a-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="96f0a-307">Исправлена ​​проблема, из-за которой файл открывался со статусом НЕ SyncBacked, если URL-адрес из кэша и URL-адрес из OneDrive НЕ совпадали.</span><span class="sxs-lookup"><span data-stu-id="96f0a-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="96f0a-308">Исправлена ошибка, из-за которой при копировании и вставке сообщений в Skype для бизнеса отображалось диалоговое окно "Произошла ошибка при вставке содержимого".</span><span class="sxs-lookup"><span data-stu-id="96f0a-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="96f0a-309">Устранена проблема, из-за которой возникала ошибка при копировании и вставке текста из комментария в Excel.</span><span class="sxs-lookup"><span data-stu-id="96f0a-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="96f0a-310">Исправлен сбой, который иногда возникал при использовании диктора в тексте с математическими уравнениями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="96f0a-311">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="96f0a-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="96f0a-312">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="96f0a-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="96f0a-313">Исправлена проблема, из-за которой установка более новой версии Office поверх некоторых старых версий могла приводить к ухудшению функциональности (например, невозможности использовать Power Query) из-за отсутствия записей в реестре.</span><span class="sxs-lookup"><span data-stu-id="96f0a-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="96f0a-314">Исправлена проблема, из-за которой защита от потери данных в конечной точке Microsoft 365 не могла классифицировать документы Office на диске.</span><span class="sxs-lookup"><span data-stu-id="96f0a-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="96f0a-315">Исправлена проблема, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="96f0a-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="96f0a-316">Устранена проблема, связанная с уведомлениями о событиях контроллера мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="96f0a-317">Устранена проблема, связанная с расчетом времени в обработчике проигрывателя мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="96f0a-318">Оптимизированный размер двоичного файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-318">Optimized binary size.</span></span>


- <span data-ttu-id="96f0a-319">Anaheim WebView пока не поддерживает службу Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="96f0a-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="96f0a-320">С этим исправлением платформа надстроек Office откатывается на веб-представление уровнем ниже в среде с поддержкой WIP.</span><span class="sxs-lookup"><span data-stu-id="96f0a-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="96f0a-321">Это может быть Edge Spartan WebView или Trident WebView в зависимости от среды на компьютере пользователя.</span><span class="sxs-lookup"><span data-stu-id="96f0a-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="96f0a-322">Оба веб-представления уровнем ниже поддерживают WIP.</span><span class="sxs-lookup"><span data-stu-id="96f0a-322">Both down level WebViews support WIP.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-february-09"></a><span data-ttu-id="96f0a-324">Версия 2008: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="96f0a-324">Version 2008: February 09</span></span>
<span data-ttu-id="96f0a-325">*Версия 2008 (сборка 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="96f0a-326">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-328">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-329">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-329">Excel</span></span>

- <span data-ttu-id="96f0a-330">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="96f0a-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="96f0a-331">Исправлена проблема, из-за которой не осуществлялся перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="96f0a-332">Исправлена проблема, из-за которой производительность выполнения макроса, включающего форматирование диапазона сводной таблицы, снижалась при каждом его выполнении.</span><span class="sxs-lookup"><span data-stu-id="96f0a-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="96f0a-333">Исправлена проблема, из-за которой удалялись правила условного форматирования при копировании или перемещении листов в другую книгу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="96f0a-334">Исправлена проблема, из-за которой пользователи не могли применять метки конфиденциальности к файлам Excel, если при загрузке приложения был отключен начальный экран.</span><span class="sxs-lookup"><span data-stu-id="96f0a-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="96f0a-335">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="96f0a-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-336">Outlook</span></span>

- <span data-ttu-id="96f0a-337">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-338">PowerPoint</span></span>

- <span data-ttu-id="96f0a-339">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="96f0a-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="96f0a-340">Исправлена проблема, из-за которой при копировании и вставке слайда с использованием параметра "Сохранить исходное форматирование" иногда неожиданно выполнялось копирование поверх нового образца слайдов</span><span class="sxs-lookup"><span data-stu-id="96f0a-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="96f0a-341">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-341">Word</span></span>

- <span data-ttu-id="96f0a-342">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="96f0a-343">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="96f0a-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-344">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-344">Office Suite</span></span>

- <span data-ttu-id="96f0a-345">Исправлена проблема, не позволявшая открыть файл в Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="96f0a-346">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-january-12"></a><span data-ttu-id="96f0a-348">Версия 2008: 12 января</span><span class="sxs-lookup"><span data-stu-id="96f0a-348">Version 2008: January 12</span></span>
<span data-ttu-id="96f0a-349">*Версия 2008 (сборка 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="96f0a-350">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-352">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-353">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-353">Excel</span></span>

- <span data-ttu-id="96f0a-354">Исправлена проблема, из-за которой при открытии книг только для чтения, было невозможно обновить данные сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="96f0a-355">Это изменение позволяет устранить следующие проблемы: при вставке файла из локальной папки синхронизации OneDrive Excel не отображает правильный значок "Вставить объект".</span><span class="sxs-lookup"><span data-stu-id="96f0a-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="96f0a-356">Исправлена проблема, из-за которой клиенты не получали уведомлений о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="96f0a-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="96f0a-357">Исправлена проблема с редактированием, из-за которой использование редактора метода ввода в режиме перезаписи приводило к неправильному изменению дополнительных символов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="96f0a-358">Исправлена проблема при использовании данных в режиме реального времени в сочетании с функцией многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="96f0a-359">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="96f0a-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-360">Outlook</span></span>

- <span data-ttu-id="96f0a-361">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="96f0a-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="96f0a-362">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="96f0a-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="96f0a-363">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="96f0a-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-364">PowerPoint</span></span>

- <span data-ttu-id="96f0a-365">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="96f0a-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="96f0a-366">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="96f0a-367">Project</span><span class="sxs-lookup"><span data-stu-id="96f0a-367">Project</span></span>

- <span data-ttu-id="96f0a-368">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="96f0a-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="96f0a-369">Skype</span><span class="sxs-lookup"><span data-stu-id="96f0a-369">Skype</span></span>

- <span data-ttu-id="96f0a-370">Устраняет проблему, из-за которой сертификат TLS-DSK пользователя обновлялся не в ожидаемое время, а только тогда, когда срок его действия оставался менее 12 часов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="96f0a-371">Устраняет проблему, при которой пользовательский интерфейс Skype для бизнеса отображается как пустой после входа в систему, когда Office еще не лицензирован.</span><span class="sxs-lookup"><span data-stu-id="96f0a-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-372">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-372">Office Suite</span></span>

- <span data-ttu-id="96f0a-373">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="96f0a-374">Это изменение решает проблему с резервным прокси-сервером SVG, в результате которого возникает нарушение прав доступа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-december-08"></a><span data-ttu-id="96f0a-376">Версия 2008: 8 сентября</span><span class="sxs-lookup"><span data-stu-id="96f0a-376">Version 2008: December 08</span></span>
<span data-ttu-id="96f0a-377">*Версия 2008 (сборка 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-377">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="96f0a-378">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-378">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-380">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-380">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-381">Access</span><span class="sxs-lookup"><span data-stu-id="96f0a-381">Access</span></span>

- <span data-ttu-id="96f0a-382">Исправлена ошибка, возникавшая при попытке использовать построитель DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="96f0a-382">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="96f0a-383">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-383">Excel</span></span>

- <span data-ttu-id="96f0a-384">Исправлена ошибка, из-за которой не удавалось изменять сводные таблицы и сохранять книги, если они были экспортированы из плана Project.</span><span class="sxs-lookup"><span data-stu-id="96f0a-384">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="96f0a-385">Исправлена ошибка, из-за которой в некоторых случаях при открытии файла в режиме "только для чтения" отображалось несколько панелей сообщений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-385">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="96f0a-386">Исправлена ошибка, из-за которой происходил сбой работы промежуточных итогов структуры при большом количестве повторяющихся значений заголовков столбцов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-386">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="96f0a-387">Исправлена ошибка, из-за которой происходил сбой работы Excel при обновлении объекта групповой политики (например, с помощью удаленного обновления групповой политики) во время многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-387">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="96f0a-388">Исправлена ошибка, из-за которой происходил сбой работы Excel при использовании функции промежуточных итогов в более чем 255 столбцах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-388">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="96f0a-389">Улучшен кернинг текста в PowerPoint при копировании содержимого из Excel и его вставке в PowerPoint с помощью функции внедрения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-389">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="96f0a-390">Исправлена ошибка, которая блокировала переключение из режима предварительного просмотра таблицы и редактора запросов в PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="96f0a-390">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="96f0a-391">Исправлена ошибка, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-391">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="96f0a-392">Исправлена ошибка, из-за которой Power Pivot не мог распознавать разделитель вкладок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-392">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-393">Outlook</span></span>

- <span data-ttu-id="96f0a-394">Исправлена ошибка, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-394">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="96f0a-395">Исправлена ошибка, из-за которой происходил сбой события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="96f0a-395">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="96f0a-396">Исправлена ошибка, из-за которой приложение неожиданно закрывалось при отправке почты Outlook из других приложений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-396">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="96f0a-397">Исправлена ошибка, из-за которой снижалась производительность при перемещении нескольких почтовых элементов между папками в интерактивном режиме.</span><span class="sxs-lookup"><span data-stu-id="96f0a-397">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="96f0a-398">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="96f0a-398">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="96f0a-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = параметры filetime исключены 1 = (по умолчанию) параметры filetime включены</span><span class="sxs-lookup"><span data-stu-id="96f0a-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="96f0a-400">Исправлена ошибка, из-за которой исчезали встроенные изображения при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="96f0a-400">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="96f0a-401">Исправлена ошибка, из-за которой имя пользователя отображалось как номер телефона при отправке голосовых сообщений, защищенных службой Azure, в результате чего пользователи классического приложения Outlook не могли открывать голосовые сообщения от внешних пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-401">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="96f0a-402">Исправлена ошибка, из-за которой при настройке конфигурации OME добавлялись лишние вложения в элемент электронной почты, в результате чего Outlook шифровал сообщение, даже если на стороне службы был настроен параметр DecryptAttachmentsForEncryptOnly.</span><span class="sxs-lookup"><span data-stu-id="96f0a-402">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-403">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-403">PowerPoint</span></span>

- <span data-ttu-id="96f0a-404">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="96f0a-404">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="96f0a-405">Исправлена ошибка, из-за которой функция "Рады видеть вас снова!</span><span class="sxs-lookup"><span data-stu-id="96f0a-405">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="96f0a-406">Продолжайте работу в Office с того места, на котором остановились" не работала в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-406">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="96f0a-407">Visio</span><span class="sxs-lookup"><span data-stu-id="96f0a-407">Visio</span></span>

- <span data-ttu-id="96f0a-408">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-408">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="96f0a-409">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-409">Word</span></span>

- <span data-ttu-id="96f0a-410">Исправлена ошибка, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="96f0a-410">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="96f0a-411">Исправлена ошибка, из-за которой при ответе на родительский комментарий с неизвестным расширением в списке расширений ответ получал то же расширение.</span><span class="sxs-lookup"><span data-stu-id="96f0a-411">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="96f0a-412">Устранена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-412">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-413">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-413">Office Suite</span></span>

- <span data-ttu-id="96f0a-414">Устранена проблема, из-за которой пользователи не могли импортировать списки SPO при отключенной ADAL.</span><span class="sxs-lookup"><span data-stu-id="96f0a-414">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-november-10"></a><span data-ttu-id="96f0a-416">Версия 2008: 10 ноября</span><span class="sxs-lookup"><span data-stu-id="96f0a-416">Version 2008: November 10</span></span>
<span data-ttu-id="96f0a-417">*Версия 2008 (сборка 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-417">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="96f0a-418">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-418">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-420">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-420">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="96f0a-421">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-421">Excel</span></span>

- <span data-ttu-id="96f0a-422">Исправлена проблема, из-за которой некоторые функции выдавали неправильный результат после загрузки книги.</span><span class="sxs-lookup"><span data-stu-id="96f0a-422">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="96f0a-423">Исправлена проблема с неожиданным завершением работы приложения, которое было связано со ссылками и именованными диапазонами надстройки XLAM.</span><span class="sxs-lookup"><span data-stu-id="96f0a-423">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="96f0a-424">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="96f0a-424">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="96f0a-425">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="96f0a-425">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="96f0a-426">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-426">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="96f0a-427">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="96f0a-427">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-428">Outlook</span></span>

- <span data-ttu-id="96f0a-429">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-429">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="96f0a-430">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="96f0a-430">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="96f0a-431">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-431">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="96f0a-432">Исправлена проблема, из-за которой поисковые запросы в календарях групп не возвращали никаких результатов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-432">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="96f0a-433">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="96f0a-433">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="96f0a-434">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="96f0a-434">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="96f0a-435">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке искажались при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-435">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="96f0a-436">Исправлена проблема, из-за которой необязательные сетевые функции блокировали загрузку веб-надстроек.</span><span class="sxs-lookup"><span data-stu-id="96f0a-436">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="96f0a-437">Дополнительные сведения см. в этой [публикации в блоге](https://developer.microsoft.com/ru-RU/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-437">See details in [blog post](https://developer.microsoft.com/ru-RU/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-438">PowerPoint</span></span>

- <span data-ttu-id="96f0a-439">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-439">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-440">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-440">Office Suite</span></span>

- <span data-ttu-id="96f0a-441">Исправлена проблема для коммерческих пользователей, применяющих System Center Configuration Manager или другие средства управления для обновления Office с использованием защиты от потери данных в конечной точке Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="96f0a-441">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="96f0a-442">Исправлена проблема с неработающим API сообщений для надстроек Office.</span><span class="sxs-lookup"><span data-stu-id="96f0a-442">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-october-13"></a><span data-ttu-id="96f0a-444">Версия 2008: 13 октября</span><span class="sxs-lookup"><span data-stu-id="96f0a-444">Version 2008: October 13</span></span>
<span data-ttu-id="96f0a-445">*Версия 2008 (сборка 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-445">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="96f0a-446">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-446">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-448">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-449">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-449">Excel</span></span>

- <span data-ttu-id="96f0a-450">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-450">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="96f0a-451">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="96f0a-451">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="96f0a-452">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-452">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="96f0a-453">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="96f0a-453">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-454">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-454">Outlook</span></span>

- <span data-ttu-id="96f0a-455">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-455">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="96f0a-456">Исправлена проблема, из-за которой иногда не удавалось применить параметр "Включить улучшения общего календаря" к существующим общим календарям.</span><span class="sxs-lookup"><span data-stu-id="96f0a-456">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="96f0a-457">Исправлена проблема, из-за которой при открытии облачного вложения ошибка отображалась на странице безопасных ссылок, а не в открываемом документе.</span><span class="sxs-lookup"><span data-stu-id="96f0a-457">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="96f0a-458">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-458">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-459">PowerPoint</span></span>

- <span data-ttu-id="96f0a-460">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="96f0a-460">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="96f0a-461">Исправление системы безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="96f0a-461">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="96f0a-462">Исправлена проблема в диалоговом окне "Параметры действия", из-за которой возникал сбой в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-462">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="96f0a-463">Visio</span><span class="sxs-lookup"><span data-stu-id="96f0a-463">Visio</span></span>

- <span data-ttu-id="96f0a-464">Исправлена проблема, из-за которой возникал сбой динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="96f0a-464">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="96f0a-465">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-465">Word</span></span>

- <span data-ttu-id="96f0a-466">Исправлена проблема, которая вызывала сбой при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="96f0a-466">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="96f0a-467">Исправлена проблема, из-за которой мог возникать сбой при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="96f0a-467">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="96f0a-468">Устранена проблема, которая могла вызвать сбой при загрузке Word.</span><span class="sxs-lookup"><span data-stu-id="96f0a-468">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="96f0a-469">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="96f0a-469">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-470">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-470">Office Suite</span></span>

- <span data-ttu-id="96f0a-471">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="96f0a-471">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="96f0a-472">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="96f0a-472">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="96f0a-473">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="96f0a-473">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="96f0a-474">Это изменение устраняет сбой при запуске приложений Office из-за невозможности загрузки d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="96f0a-474">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-08"></a><span data-ttu-id="96f0a-476">Версия 2008: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="96f0a-476">Version 2008: September 08</span></span>
<span data-ttu-id="96f0a-477">*Версия 2008 (сборка 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-477">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="96f0a-478">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-478">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="96f0a-480">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="96f0a-480">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-481">Access</span><span class="sxs-lookup"><span data-stu-id="96f0a-481">Access</span></span>

- <span data-ttu-id="96f0a-482">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="96f0a-482">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="96f0a-483">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="96f0a-483">Search and replace text in SQL View.</span></span> <span data-ttu-id="96f0a-484">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="96f0a-484">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="96f0a-485">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-485">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="96f0a-486">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-486">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="96f0a-487">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-487">Excel</span></span>

- <span data-ttu-id="96f0a-488">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="96f0a-488">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="96f0a-489">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-489">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="96f0a-490">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="96f0a-490">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="96f0a-491">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-491">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="96f0a-492">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="96f0a-492">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="96f0a-493">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="96f0a-493">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="96f0a-494">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="96f0a-494">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="96f0a-495">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-495">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="96f0a-496">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-496">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="96f0a-497">**Ваши любимые функции Excel теперь работают быстрее.** Функции СУММЕСЛИМН, СРЗНАЧЕСЛИМН, СЧЁТЕСЛИМН, МАКСЕСЛИМН и МИНЕСЛИМН теперь работают намного быстрее.</span><span class="sxs-lookup"><span data-stu-id="96f0a-497">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="96f0a-498">Быстрее переходите к итоговой строке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-498">Get to the bottom line more quickly.</span></span> <span data-ttu-id="96f0a-499">Попробуйте уже сейчас.</span><span class="sxs-lookup"><span data-stu-id="96f0a-499">Try one now.</span></span>

- <span data-ttu-id="96f0a-500">**Улучшение функции Realtimedata (RTD):** В Office 365 версии 2002 канала Monthly channel или более поздних версиях функция Excel RealTimeData (ДРВ) работает гораздо быстрее, чем в вычисление данных в таблице в Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="96f0a-500">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="96f0a-501">Мы удалили узкие места в базовой памяти и структурах данных, а также обеспечили потокобезопасность, чтобы разрешить вычисление во всех доступных потоках многопоточного пересчета (MTR).</span><span class="sxs-lookup"><span data-stu-id="96f0a-501">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-502">Outlook</span></span>

- <span data-ttu-id="96f0a-503">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="96f0a-503">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="96f0a-504">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-504">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="96f0a-505">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="96f0a-505">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="96f0a-506">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-506">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="96f0a-507">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="96f0a-507">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="96f0a-508">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-508">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="96f0a-509">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="96f0a-509">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="96f0a-510">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-510">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="96f0a-511">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-511">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="96f0a-512">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="96f0a-512">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="96f0a-513">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-513">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="96f0a-514">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-514">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="96f0a-515">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="96f0a-515">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="96f0a-516">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="96f0a-516">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="96f0a-517">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-517">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="96f0a-518">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="96f0a-518">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="96f0a-519">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="96f0a-519">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="96f0a-520">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="96f0a-520">See details in [blog post](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="96f0a-521">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="96f0a-521">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="96f0a-522">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-522">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="96f0a-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-523">PowerPoint</span></span>

- <span data-ttu-id="96f0a-524">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="96f0a-524">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="96f0a-525">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-525">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="96f0a-526">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="96f0a-526">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="96f0a-527">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-527">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="96f0a-528">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="96f0a-528">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="96f0a-529">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-529">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="96f0a-530">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-530">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="96f0a-531">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-531">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="96f0a-532">**Улучшенные диаграммы.** Более удобное создание диаграмм от руки за счет использования улучшенных соединителей и более совершенного процесса преобразования рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="96f0a-532">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="96f0a-533">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-533">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="96f0a-534">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="96f0a-534">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="96f0a-535">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-535">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="96f0a-536">**Комментарии.** Новые функций комментирования в PowerPoint позволяют быстро и легко находить и добавлять комментарии к документам.</span><span class="sxs-lookup"><span data-stu-id="96f0a-536">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="96f0a-537">Модернизируйте совместную работу с помощью новых функций, таких как привязка комментариев, сопоставление, задачи, улучшенные уведомления об упоминаниях и т. д.</span><span class="sxs-lookup"><span data-stu-id="96f0a-537">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="96f0a-538">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-538">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="96f0a-539">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-539">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="96f0a-540">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-540">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="96f0a-541">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-541">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="96f0a-542">**Ссылка на слайд:** попросите коллег поучаствовать в создании презентации и направьте их прямо на нужный слайд.</span><span class="sxs-lookup"><span data-stu-id="96f0a-542">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="96f0a-543">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-543">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="96f0a-544">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-544">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="96f0a-545">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="96f0a-545">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="96f0a-546">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="96f0a-546">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="96f0a-547">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-547">Word</span></span>

- <span data-ttu-id="96f0a-548">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="96f0a-548">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="96f0a-549">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-549">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="96f0a-550">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-550">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="96f0a-551">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="96f0a-551">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="96f0a-552">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-552">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="96f0a-553">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="96f0a-553">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="96f0a-554">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-554">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="96f0a-555">**Подтверждение действий в средстве чтения с экрана.** Подтверждение действий — это важное требование для обеспечения специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-555">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="96f0a-556">С появлением нового API уведомлений из Windows мы можем оповещать пользователей средства чтения с экрана об успехе их действий.</span><span class="sxs-lookup"><span data-stu-id="96f0a-556">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="96f0a-557">Теперь пользователи экранного диктора в Word для Win32 уведомляются о вырезании, копировании, вставке, использовании полужирного шрифта, курсива или подчеркивания, отмене, повторе, автозамене и автоматическом использовании прописных букв.</span><span class="sxs-lookup"><span data-stu-id="96f0a-557">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="96f0a-558">Чтобы включить эту возможность, включите экранный диктор с помощью клавиш Windows+CTRL+ВВОД.</span><span class="sxs-lookup"><span data-stu-id="96f0a-558">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="96f0a-559">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="96f0a-559">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-560">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-560">Office Suite</span></span>

- <span data-ttu-id="96f0a-561">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-561">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-564">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-564">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-565">Доступ</span><span class="sxs-lookup"><span data-stu-id="96f0a-565">Access</span></span>

- <span data-ttu-id="96f0a-566">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="96f0a-566">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="96f0a-567">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-567">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="96f0a-568">Исправлена проблема, препятствующая возможности вызова расширенного типа данных "Дата/время" без сбоев приложения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-568">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="96f0a-569">Проблема исправлена, поэтому теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для управления и изменения типа данных Decimal.</span><span class="sxs-lookup"><span data-stu-id="96f0a-569">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="96f0a-570">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="96f0a-570">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="96f0a-571">Эта проблема исправлена в Access, но мы продолжаем изучать дополнительные интерфейсы, чтобы она не повторилась.</span><span class="sxs-lookup"><span data-stu-id="96f0a-571">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="96f0a-572">Команда сообщит о будущих обновлениях. Мы ценим ваше терпение.</span><span class="sxs-lookup"><span data-stu-id="96f0a-572">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="96f0a-573">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="96f0a-573">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="96f0a-574">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-574">Excel</span></span>

- <span data-ttu-id="96f0a-575">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-575">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="96f0a-576">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-576">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="96f0a-577">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="96f0a-577">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="96f0a-578">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="96f0a-578">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="96f0a-579">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-579">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="96f0a-580">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="96f0a-580">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="96f0a-581">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="96f0a-581">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="96f0a-582">Исправлена проблема, из-за которой в некоторых случаях при щелчке по гиперссылке внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="96f0a-582">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="96f0a-583">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="96f0a-583">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="96f0a-584">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-584">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="96f0a-585">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="96f0a-585">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="96f0a-586">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-586">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="96f0a-587">Это устраняет проблему, из-за которой при подключениях, созданных поставщиком данных SQL в более ранних версиях Office, параметры внутренних таблиц задавались не так, как в Office 365.</span><span class="sxs-lookup"><span data-stu-id="96f0a-587">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="96f0a-588">Это приводит к отключению раскрывающегося списка "Просмотр таблиц" или "Редактор запросов" для файлов с подключениями, созданными в более ранних версиях Office, когда они открывались с помощью Office 365.</span><span class="sxs-lookup"><span data-stu-id="96f0a-588">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="96f0a-589">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="96f0a-589">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="96f0a-590">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-590">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="96f0a-591">OneNote</span><span class="sxs-lookup"><span data-stu-id="96f0a-591">OneNote</span></span>

- <span data-ttu-id="96f0a-592">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="96f0a-592">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="96f0a-593">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-593">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="96f0a-594">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="96f0a-594">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="96f0a-595">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-595">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="96f0a-596">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="96f0a-596">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="96f0a-597">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-597">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="96f0a-598">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-598">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="96f0a-599">Улучшена синхронизация и стабильность службы за счет временного изменения частоты создания журналов версий страниц.</span><span class="sxs-lookup"><span data-stu-id="96f0a-599">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="96f0a-600">Улучшена синхронизация и стабильность службы за счет временного отключения перемещения страниц в корзину.</span><span class="sxs-lookup"><span data-stu-id="96f0a-600">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="96f0a-601">Для пользователей, которым нужно удалить страницу, будет отображаться диалоговое окно с вопросом, нужно ли удалить страницу окончательно.</span><span class="sxs-lookup"><span data-stu-id="96f0a-601">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-602">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-602">Outlook</span></span>

- <span data-ttu-id="96f0a-603">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="96f0a-603">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="96f0a-604">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="96f0a-604">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="96f0a-605">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="96f0a-605">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="96f0a-606">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="96f0a-606">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="96f0a-607">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-607">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="96f0a-608">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="96f0a-608">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="96f0a-609">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="96f0a-609">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="96f0a-610">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="96f0a-610">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="96f0a-611">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-611">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="96f0a-612">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="96f0a-612">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="96f0a-613">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-613">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="96f0a-614">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="96f0a-614">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="96f0a-615">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-615">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="96f0a-616">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="96f0a-616">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="96f0a-617">Устранена проблема, которая в некоторых ситуациях приводила к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="96f0a-617">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="96f0a-618">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="96f0a-618">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="96f0a-619">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-619">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="96f0a-620">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-620">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="96f0a-621">Устранена проблема, из-за которой у пользователей возникали сбои в сторонних приложениях MAPI.</span><span class="sxs-lookup"><span data-stu-id="96f0a-621">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="96f0a-622">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-622">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="96f0a-623">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-623">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="96f0a-624">Устранена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="96f0a-624">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="96f0a-625">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="96f0a-625">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="96f0a-626">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-626">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="96f0a-627">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-627">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="96f0a-628">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="96f0a-628">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="96f0a-629">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="96f0a-629">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="96f0a-630">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="96f0a-630">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="96f0a-631">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="96f0a-631">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="96f0a-632">Устранена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-632">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="96f0a-633">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="96f0a-633">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="96f0a-634">Исправлена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-634">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="96f0a-635">Исправлена проблема, из-за которой возникали аномалии при использовании пользователями компактного представления.</span><span class="sxs-lookup"><span data-stu-id="96f0a-635">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="96f0a-636">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-636">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="96f0a-637">Устранена проблема, из-за которой контекстное меню, вызываемое щелчком правой кнопки мыши, не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="96f0a-637">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="96f0a-638">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="96f0a-638">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="96f0a-639">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="96f0a-639">Do you want to download them anyway?</span></span> <span data-ttu-id="96f0a-640">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="96f0a-640">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="96f0a-641">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-641">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="96f0a-642">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-642">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="96f0a-643">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-643">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="96f0a-644">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="96f0a-644">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="96f0a-645">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-645">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="96f0a-646">Устранена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-646">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="96f0a-647">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-647">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-648">PowerPoint</span></span>

- <span data-ttu-id="96f0a-649">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="96f0a-649">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="96f0a-650">Устранена проблема со сбоем в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-650">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="96f0a-651">Устранена проблема со сбоем панели предложений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-651">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="96f0a-652">Project</span><span class="sxs-lookup"><span data-stu-id="96f0a-652">Project</span></span>

- <span data-ttu-id="96f0a-653">Устранена проблема, из-за которой при редактировании данных Предшественника / Преемника в представлении формы, запускалось дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="96f0a-653">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="96f0a-654">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="96f0a-654">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="96f0a-655">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="96f0a-655">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="96f0a-656">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="96f0a-656">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="96f0a-657">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="96f0a-657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="96f0a-658">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-658">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="96f0a-659">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="96f0a-659">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="96f0a-660">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="96f0a-660">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="96f0a-661">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="96f0a-661">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="96f0a-662">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="96f0a-662">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="96f0a-663">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-663">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="96f0a-664">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="96f0a-664">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="96f0a-665">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-665">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="96f0a-666">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="96f0a-666">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="96f0a-667">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-667">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="96f0a-668">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="96f0a-668">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="96f0a-669">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="96f0a-669">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="96f0a-670">Skype</span><span class="sxs-lookup"><span data-stu-id="96f0a-670">Skype</span></span>

- <span data-ttu-id="96f0a-671">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="96f0a-671">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="96f0a-672">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-672">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="96f0a-673">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="96f0a-673">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="96f0a-674">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="96f0a-674">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-675">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-675">Word</span></span>

- <span data-ttu-id="96f0a-676">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="96f0a-676">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="96f0a-677">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="96f0a-677">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="96f0a-678">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-678">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="96f0a-679">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="96f0a-679">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="96f0a-680">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-680">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="96f0a-681">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="96f0a-681">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="96f0a-682">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="96f0a-682">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="96f0a-683">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="96f0a-683">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="96f0a-684">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-684">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="96f0a-685">Устранена проблема, которая могла вызвать сбой при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-685">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="96f0a-686">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-686">Office Suite</span></span>

- <span data-ttu-id="96f0a-687">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта.</span><span class="sxs-lookup"><span data-stu-id="96f0a-687">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="96f0a-688">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="96f0a-688">This is now fixed.</span></span>

- <span data-ttu-id="96f0a-689">Устранена проблема, из-за которой при закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="96f0a-689">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="96f0a-690">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="96f0a-690">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="96f0a-691">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="96f0a-691">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="96f0a-692">Исправлена проблема технологии "Нажми и работай", из-за которой происходил сбой обновления при попытке жесткой связи символьных ссылок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-692">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="96f0a-693">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="96f0a-693">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="96f0a-694">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-694">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="96f0a-695">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="96f0a-695">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="96f0a-696">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-696">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="96f0a-697">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="96f0a-697">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="96f0a-698">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="96f0a-698">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="96f0a-699">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="96f0a-699">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="96f0a-700">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-700">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="96f0a-701">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="96f0a-701">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="96f0a-702">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="96f0a-702">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="96f0a-703">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="96f0a-703">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="96f0a-704">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="96f0a-704">This change would fix this issue.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-august-11"></a><span data-ttu-id="96f0a-706">Версия 2002: 11 августа</span><span class="sxs-lookup"><span data-stu-id="96f0a-706">Version 2002: August 11</span></span>
<span data-ttu-id="96f0a-707">*Версия 2002 (сборка 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-707">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="96f0a-708">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-708">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-710">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-710">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-711">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-711">Excel</span></span>

- <span data-ttu-id="96f0a-712">Исправлена проблема, не позволявшая переключиться на редактирование файлов, открытых с использованием параметра "Рекомендовать доступ только для чтения".</span><span class="sxs-lookup"><span data-stu-id="96f0a-712">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="96f0a-713">OneNote</span><span class="sxs-lookup"><span data-stu-id="96f0a-713">OneNote</span></span>

- <span data-ttu-id="96f0a-714">Удалены лишние вызовы удостоверений, чтобы сократить использование ресурсов</span><span class="sxs-lookup"><span data-stu-id="96f0a-714">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="96f0a-715">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="96f0a-715">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="96f0a-716">Улучшена функция обнаружения ошибок и качество синхронизации.</span><span class="sxs-lookup"><span data-stu-id="96f0a-716">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-717">Outlook</span></span>

- <span data-ttu-id="96f0a-718">Исправлена ошибка, вызывавшая серьезную проблему с производительностью при запуске Outlook для некоторых клиентов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-718">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="96f0a-719">Skype</span><span class="sxs-lookup"><span data-stu-id="96f0a-719">Skype</span></span>

- <span data-ttu-id="96f0a-720">Исправлена проблема, из-за которой запуск демонстрации экрана мог завершиться сбоем в 32-разрядном клиенте Skype для бизнеса после его работы в течение нескольких дней.</span><span class="sxs-lookup"><span data-stu-id="96f0a-720">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-721">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-721">Office Suite</span></span>

- <span data-ttu-id="96f0a-722">Исправлена проблема, из-за которой в случае отключения автосохранения с помощью групповой политики некоторые документы могли не отображать последнее содержимое сервера при открытии, пока пользователь не нажмет кнопку "Доступны обновления".</span><span class="sxs-lookup"><span data-stu-id="96f0a-722">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-july-14"></a><span data-ttu-id="96f0a-724">Версия 2002: 14 июля</span><span class="sxs-lookup"><span data-stu-id="96f0a-724">Version 2002: July 14</span></span>
<span data-ttu-id="96f0a-725">*Версия 2002 (сборка 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-725">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="96f0a-726">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-726">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-728">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-728">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-729">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-729">Excel</span></span>

- <span data-ttu-id="96f0a-730">Ускорение загрузки файлов, доступных в локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="96f0a-730">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="96f0a-731">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="96f0a-731">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="96f0a-732">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, поэтому закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-732">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="96f0a-733">Исправлена проблема, при которой книга могла быть скрыта при щелчке гиперссылки на определенное место в уже открытой книге.</span><span class="sxs-lookup"><span data-stu-id="96f0a-733">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="96f0a-734">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-734">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="96f0a-735">Повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="96f0a-735">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="96f0a-736">Устранена проблема, из-за которой имена принтеров могли повторяться в списке принтеров в диалоговом окне "Печать".</span><span class="sxs-lookup"><span data-stu-id="96f0a-736">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="96f0a-737">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-737">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-738">Outlook</span></span>

- <span data-ttu-id="96f0a-739">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-739">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="96f0a-740">Устранена проблема, при которой повторяющиеся встречи или собрания отображались с ошибкой во времени при приближении изменений в определении часового пояса.</span><span class="sxs-lookup"><span data-stu-id="96f0a-740">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="96f0a-741">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="96f0a-741">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="96f0a-742">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-742">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="96f0a-743">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="96f0a-743">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="96f0a-744">Устранена проблема, из-за которой представители видели разные иерархии папок общих почтовых ящиков на разных компьютерах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-744">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="96f0a-745">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-745">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="96f0a-746">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-746">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="96f0a-747">Устранена проблема, вызывавшая сбой после того, как две надстройки добавляли кнопку в одну и ту же группу ленты.</span><span class="sxs-lookup"><span data-stu-id="96f0a-747">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="96f0a-748">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения по адресам из личного списка рассылки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-748">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="96f0a-749">Устранена проблема, из-за которой нельзя было добавить ссылки в сообщения электронной почты с правильным клиентским разрешением по умолчанию, если для этого разрешения был установлен параметр "все".</span><span class="sxs-lookup"><span data-stu-id="96f0a-749">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="96f0a-750">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="96f0a-750">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-751">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-751">Word</span></span>

- <span data-ttu-id="96f0a-752">Исправлена проблема с совместной работой над документом при включении политики FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="96f0a-752">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="96f0a-753">Устранена проблема, при которой функция экспресс-блоков Word не работала при добавлении переименованного поля подстановки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-753">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-754">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-754">Office Suite</span></span>

- <span data-ttu-id="96f0a-755">Исправлена проблема, из-за которой при совместной работе над объемными файлами PowerPoint чрезмерно повышалась нагрузка на сеть и ЦП.</span><span class="sxs-lookup"><span data-stu-id="96f0a-755">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="96f0a-756">Мы отправили часть AppV51 на доработку, чтобы исправить в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="96f0a-756">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="96f0a-757">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="96f0a-757">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-june-09"></a><span data-ttu-id="96f0a-759">Версия 2002: 9 июня</span><span class="sxs-lookup"><span data-stu-id="96f0a-759">Version 2002: June 09</span></span>
<span data-ttu-id="96f0a-760">*Версия 2002 (сборка 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-760">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="96f0a-761">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-761">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-763">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-763">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-764">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-764">Excel</span></span>

- <span data-ttu-id="96f0a-765">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="96f0a-765">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="96f0a-766">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="96f0a-766">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="96f0a-767">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="96f0a-767">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="96f0a-768">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="96f0a-768">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="96f0a-769">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-769">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="96f0a-770">Исправлена проблема, из-за которой знак @ в начале формулы считался неявным оператором пересечения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-770">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-771">Outlook</span></span>

- <span data-ttu-id="96f0a-772">Позволяет присоединиться к собранию в Teams непосредственно через собственный клиент Teams.</span><span class="sxs-lookup"><span data-stu-id="96f0a-772">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="96f0a-773">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="96f0a-773">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="96f0a-774">Исправлена проблема, из-за которой пользователи, имеющие неправильный параметр эмуляции браузера, не могли завершить запрос на проверку подлинности Gmail.</span><span class="sxs-lookup"><span data-stu-id="96f0a-774">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="96f0a-775">Исправлена проблема пользователей Outlook, использующих серверные операционные системы, приводившая к ошибке "Состояние защиты от вирусов: Недействительно.</span><span class="sxs-lookup"><span data-stu-id="96f0a-775">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="96f0a-776">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены", несмотря на то, что антивирусная программа настроена правильно.</span><span class="sxs-lookup"><span data-stu-id="96f0a-776">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-777">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-777">Word</span></span>

- <span data-ttu-id="96f0a-778">Исправлена проблема, из-за которой выравнивание слова в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="96f0a-778">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-779">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-779">Office Suite</span></span>

- <span data-ttu-id="96f0a-780">Эта проблема устранена с помощью замены имен каналов в представлении Backstage на новые в разветвлении января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="96f0a-780">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="96f0a-781">Исправлена проблема, из-за которой устройства регулируемые политикой не могли вызвать API аудитории DMS.</span><span class="sxs-lookup"><span data-stu-id="96f0a-781">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="96f0a-782">Исправлена проблема, из-за которой при добавлении и удалении приложений в одной транзакции выполнялось неполное удаление.</span><span class="sxs-lookup"><span data-stu-id="96f0a-782">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="96f0a-783">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="96f0a-783">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="96f0a-784">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="96f0a-784">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-may-12"></a><span data-ttu-id="96f0a-786">Версия 2002: 12 мая</span><span class="sxs-lookup"><span data-stu-id="96f0a-786">Version 2002: May 12</span></span>
<span data-ttu-id="96f0a-787">*Версия 2002 (сборка 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-787">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="96f0a-788">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-788">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-790">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-790">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="96f0a-791">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-791">Excel</span></span>

- <span data-ttu-id="96f0a-792">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-792">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="96f0a-793">В некоторых случаях открытие CSV-файлов занимало больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-793">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="96f0a-794">В ряде случаев приложение Excel аварийно завершало работу при переключении между книгами с разным масштабом.</span><span class="sxs-lookup"><span data-stu-id="96f0a-794">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="96f0a-795">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-795">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="96f0a-796">Данные, скопированные из столбца и отфильтрованные по цвету, иногда не вставлялись должным образом.</span><span class="sxs-lookup"><span data-stu-id="96f0a-796">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="96f0a-797">Устранена проблема, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-797">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="96f0a-798">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="96f0a-798">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="96f0a-799">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-799">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="96f0a-800">При использовании Range.Value и Range.Value2 (VBA) формулы вводились как динамические массивы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-800">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="96f0a-801">OneNote</span><span class="sxs-lookup"><span data-stu-id="96f0a-801">OneNote</span></span>

- <span data-ttu-id="96f0a-802">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-802">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="96f0a-803">Отображает уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-803">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="96f0a-804">Улучшена синхронизация и стабильность службы путем временного уменьшения количества и частоты синхронизации страниц журнала версий в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-804">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="96f0a-805">Улучшена синхронизация и стабильность службы путем временного отключения корзины в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-805">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="96f0a-806">Если пользователь пытается удалить данные, которые обычно отправляются в корзину, ему будет предложено сохранить или окончательно удалить их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-806">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="96f0a-807">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-807">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="96f0a-808">Улучшена синхронизация и стабильность службы путем временного откладывания загрузки внедренных файлов и изображений в записных книжках в Интернете, пока пользователь не перейдет на страницу в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-808">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="96f0a-809">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-809">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="96f0a-810">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-810">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="96f0a-811">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="96f0a-811">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="96f0a-812">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="96f0a-812">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-813">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-813">Outlook</span></span>

- <span data-ttu-id="96f0a-814">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-814">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="96f0a-815">Устранена проблема, приводившая в сбою при попытке открытия файлов MSG и OFT после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-815">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="96f0a-816">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="96f0a-816">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="96f0a-817">Это обновление исправляет проблему, из-за которой в Microsoft Outlook не отображается текущая метка конфиденциальности при просмотре или создании сообщений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-817">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="96f0a-818">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения в личный список рассылки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-818">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="96f0a-819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-819">PowerPoint</span></span>

- <span data-ttu-id="96f0a-820">Устранена проблема с ретрансляцией точного текста сообщений для пользователей, которые открывают копию файла с улучшенными примечаниями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-820">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-821">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-821">Word</span></span>

- <span data-ttu-id="96f0a-822">Решена проблема, из-за которой приложения Access и Publisher могли загружаться неправильно в зависимости от того, какие языки установлены.</span><span class="sxs-lookup"><span data-stu-id="96f0a-822">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="96f0a-823">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="96f0a-823">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="96f0a-824">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="96f0a-824">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-825">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-825">Office Suite</span></span>

- <span data-ttu-id="96f0a-826">Это исправление устраняет блокирование сети приложением Project при кэшировании файла в клиенте.</span><span class="sxs-lookup"><span data-stu-id="96f0a-826">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="96f0a-827">Решена проблема, из-за которой внутренняя операция вызывала исключение при сбое вместо ведения журнала и продолжения работы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-827">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="96f0a-828">Для затронутых пользователей будет отменен запрет на получение обновлений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-828">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="96f0a-829">Это изменение обеспечит правильную работу функции "Контур эскиза" на ленте.</span><span class="sxs-lookup"><span data-stu-id="96f0a-829">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="96f0a-830">Исправлена проблема при открытии файлов из локальных расположений с определенными настройками прокси.</span><span class="sxs-lookup"><span data-stu-id="96f0a-830">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="96f0a-831">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-831">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="96f0a-832">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="96f0a-832">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="96f0a-833">Это обновление устраняет проблему в Microsoft Word, из-за которой текст длиной более 255 символов, вставленный при применении метки конфиденциальности, впоследствии не удавалось идентифицировать и удалить путем изменения или удаления метки, если в рамках политики меток был применен колонтитул или подложка.</span><span class="sxs-lookup"><span data-stu-id="96f0a-833">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="96f0a-834">Исправлена проблема, благодаря чему устранены сбои во время сеансов передачи Office и повышена надежность работы пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-834">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="96f0a-835">Это исправление обновляет конечную точку URL-адреса конфигурации усиленной безопасности (ECS).</span><span class="sxs-lookup"><span data-stu-id="96f0a-835">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="96f0a-836">В результате вызова этой новой конечной точки повышается успешность получения данных из ECS.</span><span class="sxs-lookup"><span data-stu-id="96f0a-836">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-april-14"></a><span data-ttu-id="96f0a-838">Версия 2002: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="96f0a-838">Version 2002: April 14</span></span>
<span data-ttu-id="96f0a-839">*Версия 2002 (сборка 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-839">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="96f0a-840">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-840">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="96f0a-841">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="96f0a-841">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-842">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-842">Excel</span></span>

- <span data-ttu-id="96f0a-843">**Ввод формулы, возвращающей несколько значений.** Теперь вы можете быстро ввести формулу, возвращающую несколько значений, которые автоматически переносятся в смежные ячейки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-843">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="96f0a-844">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-844">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="96f0a-845">**Шесть эффективных функций.** Добавлено шесть новых функций для улучшения электронных таблиц: ФИЛЬТР, СОРТ, СОРТПО, УНИК, ПОСЛЕДОВ и СЛУЧМАССИВ.</span><span class="sxs-lookup"><span data-stu-id="96f0a-845">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="96f0a-846">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-846">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="96f0a-847">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="96f0a-847">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="96f0a-848">
  [Подробнее](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="96f0a-848">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-850">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-850">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-851">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-851">Excel</span></span>

- <span data-ttu-id="96f0a-852">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-852">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="96f0a-853">В некоторых случаях при сохранении в виде CSV-файла Excel мог объединять все столбцы в один столбец.</span><span class="sxs-lookup"><span data-stu-id="96f0a-853">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="96f0a-854">Использование Range.ClearContents для диапазона в защищенном листе могло занимать больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="96f0a-854">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="96f0a-855">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="96f0a-855">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="96f0a-856">Макросы VBA, взаимодействующие с лентой, могут неожиданно запускаться со значением True, присвоенным параметру ScreenUpdating.</span><span class="sxs-lookup"><span data-stu-id="96f0a-856">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="96f0a-857">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении (заполнение вниз, заполнение в стороны), если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="96f0a-857">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="96f0a-858">В некоторых случаях в VBA не работал метод Application.Evaluate для определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="96f0a-858">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="96f0a-859">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-859">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-860">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-860">Outlook</span></span>

- <span data-ttu-id="96f0a-861">Исправлена проблема, приводившая к неожиданному увеличению заголовка группы в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-861">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="96f0a-862">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-862">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="96f0a-863">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="96f0a-863">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="96f0a-864">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-864">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="96f0a-865">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-865">PowerPoint</span></span>

- <span data-ttu-id="96f0a-866">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="96f0a-866">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="96f0a-867">Project</span><span class="sxs-lookup"><span data-stu-id="96f0a-867">Project</span></span>

- <span data-ttu-id="96f0a-868">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="96f0a-868">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="96f0a-869">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="96f0a-869">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-870">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-870">Word</span></span>

- <span data-ttu-id="96f0a-871">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="96f0a-871">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="96f0a-872">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="96f0a-872">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="96f0a-873">Исправлена проблема, из-за которой вставляемые горизонтальные линии не укорачиваются и не располагаются по центру.</span><span class="sxs-lookup"><span data-stu-id="96f0a-873">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-10"></a><span data-ttu-id="96f0a-875">Версия 2002: 10 марта</span><span class="sxs-lookup"><span data-stu-id="96f0a-875">Version 2002: March 10</span></span>
<span data-ttu-id="96f0a-876">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-876">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="96f0a-877">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-877">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="96f0a-879">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="96f0a-879">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-880">Access</span><span class="sxs-lookup"><span data-stu-id="96f0a-880">Access</span></span>

- <span data-ttu-id="96f0a-881">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="96f0a-881">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="96f0a-882">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-882">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="96f0a-883">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-883">Excel</span></span>

- <span data-ttu-id="96f0a-884">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="96f0a-884">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="96f0a-885">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-885">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="96f0a-886">**Найдите то, что ищете:** Ищите команды, людей, файлы, фотографии, веб-статьи и многое другое.</span><span class="sxs-lookup"><span data-stu-id="96f0a-886">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="96f0a-887">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-887">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="96f0a-888">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей книге.</span><span class="sxs-lookup"><span data-stu-id="96f0a-888">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="96f0a-889">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-889">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="96f0a-890">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-890">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="96f0a-891">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="96f0a-891">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="96f0a-892">**Сосредоточьтесь на оставшихся задачах.** Пометьте примечания как разрешенные, чтобы свернуть их и сделать открытые элементы более заметными.</span><span class="sxs-lookup"><span data-stu-id="96f0a-892">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="96f0a-893">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="96f0a-893">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="96f0a-894">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-894">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="96f0a-895">**Преобразование файлов для расширения специальных возможностей.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-895">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="96f0a-896">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="96f0a-896">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="96f0a-897">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-897">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="96f0a-898">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-898">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="96f0a-899">**Получите статистику в своей книге:** Статистика рабочей книги предоставляет обзор содержимого рабочей книги, чтобы упростить ее обнаружение.</span><span class="sxs-lookup"><span data-stu-id="96f0a-899">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="96f0a-900">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-900">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="96f0a-901">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="96f0a-901">Find them at Insert > Icons.</span></span> [<span data-ttu-id="96f0a-902">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-902">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="96f0a-903">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-903">Outlook</span></span>

- <span data-ttu-id="96f0a-904">**Подключение к сети LinkedIn с помощью Outlook.** Безопасное подключение к учетным записям LinkedIn с помощью учетных записей Майкрософт для просмотра сведений из профилей LinkedIn прямо на карточках контактов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-904">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="96f0a-905">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-905">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="96f0a-p176">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты. [Подробнее](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="96f0a-p176">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="96f0a-908">**Меню "Вставка ссылки" в Outlook вставляет ссылку с разрешениями, определенными администратором клиента.** При выборе из списка последних использованных ссылок в Outlook вставляется ссылка, которая была доступна только пользователям, имеющим разрешение на доступ к ней.</span><span class="sxs-lookup"><span data-stu-id="96f0a-908">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="96f0a-909">Из-за этого пользователи часто посылали друг другу письма с просьбой предоставить доступ к документу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-909">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="96f0a-910">Мы обновили этот опыт, поэтому теперь ссылка вставляется с разрешением по умолчанию, установленным администратором клиента. Для MSIT это «организация может редактировать», поэтому все внутренние пользователи, получившие ссылку, которой поделились таким образом, смогут получить к ней доступ.</span><span class="sxs-lookup"><span data-stu-id="96f0a-910">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="96f0a-911">**Поиск с правописанием проблем или опечаток:** Outlook найдет то, что вы ищете, даже если ваше правописание не соответствует.</span><span class="sxs-lookup"><span data-stu-id="96f0a-911">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="96f0a-912">**Фишинговые письма легко обнаружить:** спам и фишинговые сообщения выглядят по-разному, поэтому вы можете легко их идентифицировать и удалить из папки «Входящие».</span><span class="sxs-lookup"><span data-stu-id="96f0a-912">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="96f0a-913">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="96f0a-913">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="96f0a-914">**Рисование.** Рисуйте поверх изображений или добавьте полотно, чтобы отправить свои идеи с помощью рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="96f0a-914">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="96f0a-915">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-915">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="96f0a-916">**Получайте релевантные сообщения в результатах поиска.** Outlook анализирует условия поиска и отображает наиболее релевантные сообщения электронной почты в верхней части результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="96f0a-916">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="96f0a-917">Кроме того, все результаты будут отображаться в разделе "Лучшие результаты" с сортировкой по дате.</span><span class="sxs-lookup"><span data-stu-id="96f0a-917">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="96f0a-918">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-918">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="96f0a-919">**Получение предложений по расположению.** Начните вводить текст в поле "Место" при планировании встреч и собраний, и Outlook предложит помещения, адреса и другие недавние места.</span><span class="sxs-lookup"><span data-stu-id="96f0a-919">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="96f0a-920">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-920">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="96f0a-921">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="96f0a-921">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="96f0a-922">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-922">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="96f0a-923">**Просмотр сообщений в другой освещенности.** Используйте кнопку "СОЛНЦЕ/ЛУНА" для переключения между светлым и темным фоном в области чтения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-923">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="96f0a-924">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-924">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="96f0a-925">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-925">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="96f0a-926">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="96f0a-926">Find them at Insert > Icons.</span></span> [<span data-ttu-id="96f0a-927">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-927">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="96f0a-928">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-928">PowerPoint</span></span>

- <span data-ttu-id="96f0a-929">**Быстрое взаимодействие в реальном времени в PowerPoint:** Быстрое сотрудничество в реальном времени в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-929">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="96f0a-930">**Новые средства проверки правописания.** Не переживайте из-за слов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-930">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="96f0a-931">В PowerPoint теперь отображаются предложения в отношении грамматики и написания.</span><span class="sxs-lookup"><span data-stu-id="96f0a-931">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="96f0a-932">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-932">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="96f0a-933">**Субтитры в реальном времени.** Слова докладчика автоматически отображаются на экране в виде субтитров или переводятся в субтитры на выбранном языке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-933">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="96f0a-934">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-934">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="96f0a-p186">**Вы вычисляете, мы форматируем.** Рукописные математические выражения преобразуются в стандартные знаки. Просто воспользуйтесь функцией "Рукописный фрагмент в математические символы" и выберите рукописные примечания для начала работы. [Подробнее](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="96f0a-p186">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="96f0a-938">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="96f0a-938">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="96f0a-939">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-939">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="96f0a-940">**Поиск и исправление пропущенных названий слайдов:** Названия слайдов добавляют удар к вашей подаче и делают ваши слайды доступными для пользователей всех способностей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-940">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="96f0a-941">С помощью средства проверки читаемости можно определить, где отсутствуют заголовки, и сразу же добавить их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-941">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="96f0a-942">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-942">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="96f0a-943">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей презентации.</span><span class="sxs-lookup"><span data-stu-id="96f0a-943">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="96f0a-944">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-944">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="96f0a-945">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-945">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="96f0a-946">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="96f0a-946">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="96f0a-947">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="96f0a-947">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="96f0a-948">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-948">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="96f0a-949">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-949">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="96f0a-950">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-950">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="96f0a-951">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-951">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="96f0a-952">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-952">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="96f0a-953">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-953">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="96f0a-954">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="96f0a-954">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="96f0a-955">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="96f0a-955">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="96f0a-956">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-956">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="96f0a-957">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-957">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="96f0a-958">**Зачем изобретать заново, если вы можете использовать повторно ?:** Экономьте время, повторно используя слайды, которые вы создали или которыми другие поделились с вами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-958">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="96f0a-959">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-959">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="96f0a-960">**Измените рукописные чернила на фигуры, текст или математику в PowerPoint для Office 365:** Перейдите от чернил произвольной формы к фигурам, тексту или математическому выражению Office за пару движений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-960">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="96f0a-961">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-961">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="96f0a-962">**Рукописный ввод для создания отличного слайда.** Преобразуйте рукописный ввод в стандартные фигуры и текст, а затем находите изящные идеи оформления слайдов в конструкторе PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-962">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="96f0a-963">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-963">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="96f0a-964">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-964">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="96f0a-965">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="96f0a-965">Find them at Insert > Icons.</span></span> [<span data-ttu-id="96f0a-966">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-966">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="96f0a-967">Visio</span><span class="sxs-lookup"><span data-stu-id="96f0a-967">Visio</span></span>

- <span data-ttu-id="96f0a-968">**В сценах преступления:** Используйте новые трафареты «Доказательства», «В помещении» и «На улице» в шаблоне «Расследование места преступления», чтобы детально воссоздать места преступления.</span><span class="sxs-lookup"><span data-stu-id="96f0a-968">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="96f0a-969">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="96f0a-969">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="96f0a-970">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-970">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="96f0a-971">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-971">Word</span></span>

- <span data-ttu-id="96f0a-972">**Редактор для резюме присоединяется к LinkedIn Resume Assistant:** редактор для резюме предлагает выбор грамматических и стилевых проверок, специально предназначенных для резюме, чтобы сделать ваше письмо более точным и профессиональным.</span><span class="sxs-lookup"><span data-stu-id="96f0a-972">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="96f0a-973">**Исправление проблемы с повреждением документа при объединении 3D объектов.** Исправлена проблема с повреждением документа, возникавшая при объединении 3D объектов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-973">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="96f0a-974">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="96f0a-974">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="96f0a-975">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-975">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="96f0a-976">**Сотрудничайте в живом цвете:** комментарии и изменения имеют цветовую кодировку от участника, поэтому легко увидеть, кто есть кто среди ваших соавторов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-976">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="96f0a-977">**Совместное редактирование документов с поддержкой макросов:** сохраняйте файлы документов в OneDrive для бизнеса и редактируйте их вместе с соавторами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="96f0a-977">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="96f0a-978">**Улучшенные возможности совместного редактирования**. Улучшено быстродействие Word при совместном редактировании в документах с отслеживанием исправлений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-978">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="96f0a-979">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="96f0a-979">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="96f0a-980">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="96f0a-980">Find them at Insert > Icons.</span></span> [<span data-ttu-id="96f0a-981">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-981">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="96f0a-982">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="96f0a-982">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="96f0a-983">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своем документе.</span><span class="sxs-lookup"><span data-stu-id="96f0a-983">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="96f0a-984">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-984">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="96f0a-985">**Точное стирание.** Выберите один из двух размеров ластика, чтобы исправить небольшие недочеты рукописных фрагментов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-985">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="96f0a-986">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-986">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="96f0a-987">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="96f0a-987">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="96f0a-988">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="96f0a-988">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="96f0a-989">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-989">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="96f0a-990">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="96f0a-990">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="96f0a-991">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="96f0a-991">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="96f0a-992">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-992">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="96f0a-993">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="96f0a-993">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="96f0a-994">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="96f0a-994">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="96f0a-995">Подробнее</span><span class="sxs-lookup"><span data-stu-id="96f0a-995">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-998">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-998">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="96f0a-999">Доступ</span><span class="sxs-lookup"><span data-stu-id="96f0a-999">Access</span></span>

- <span data-ttu-id="96f0a-1000">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1000">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="96f0a-1001">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1001">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="96f0a-1002">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="96f0a-1002">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="96f0a-1003">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1003">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="96f0a-1004">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1004">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="96f0a-1005">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1005">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="96f0a-1006">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-1006">Excel</span></span>

- <span data-ttu-id="96f0a-1007">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1007">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="96f0a-1008">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1008">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="96f0a-1009">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1009">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="96f0a-1010">Это обновление устраняет проблему, из-за которой на панели формул текст отображался шрифтом, отличным от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1010">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="96f0a-1011">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1011">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="96f0a-1012">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1012">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="96f0a-1013">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1013">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="96f0a-1014">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1014">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="96f0a-1015">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1015">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="96f0a-1016">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1016">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="96f0a-1017">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1017">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="96f0a-1018">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1018">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="96f0a-1019">Исправлена проблема, которая могла возникнуть у некоторых пользователей со встроенными и связанными объектами (OLE).</span><span class="sxs-lookup"><span data-stu-id="96f0a-1019">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="96f0a-1020">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="96f0a-1020">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="96f0a-1021">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1021">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="96f0a-1022">Исправлена ошибка, из-за которой некоторые пользователи могли сталкиваться с несколькими всплывающими окнами при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1022">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="96f0a-1023">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1023">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="96f0a-1024">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1024">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="96f0a-1025">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1025">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-1026">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-1026">Outlook</span></span>

- <span data-ttu-id="96f0a-1027">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="96f0a-1027">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="96f0a-1028">Исправлена проблема, приводившая к зависаниям у пользователей в Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1028">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="96f0a-1029">Устранена проблема, которая приводила к неправильному выравниванию поля поиска в режиме высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1029">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="96f0a-1030">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1030">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="96f0a-1031">Исправлена проблема, из-за которой пользователи иногда наблюдали отправку сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1031">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="96f0a-1032">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1032">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="96f0a-1033">Исправлена проблема, которая не позволяла сохранять файлы в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1033">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="96f0a-1034">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1034">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="96f0a-1035">Устранена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1035">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="96f0a-1036">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1036">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="96f0a-1037">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1037">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="96f0a-1038">Устранена проблема, из-за которой Outlook неожиданно синхронизировал всю почту, даже если для ползунка синхронизации установлено меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1038">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="96f0a-1039">Исправлена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке "От" отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1039">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="96f0a-1040">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1040">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="96f0a-1041">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1041">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="96f0a-1042">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1042">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="96f0a-1043">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="96f0a-1043">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="96f0a-1044">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1044">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="96f0a-1045">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1045">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="96f0a-1046">Устранена проблема, которая могла привести к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1046">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="96f0a-1047">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1047">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="96f0a-1048">Исправлена проблема, из-за которой пользователи не могли открывать некоторые вхождения повторяющихся элементов календаря.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1048">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="96f0a-1049">Устранена проблема, из-за которой у пользователей с почтовыми ящиками на серверах Exchange 2010 возникали проблемы при добавлении вложений в элементы календаря.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1049">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="96f0a-1050">Устранена проблема, из-за которой у пользователей возникали проблемы при ответе на сообщения с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1050">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="96f0a-1051">Исправлена проблема, из-за которой неожиданно обновлялось поле расположения в собраниях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1051">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="96f0a-1052">Устранена проблема, из-за которой запятые в поле местоположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1052">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="96f0a-1053">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1053">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="96f0a-1054">Решены вопросы, связанные со встречами и встречами, установленными в часовом поясе Бразилии.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1054">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="96f0a-1055">Устранена проблема, из-за которой сообщения неожиданно отправлялись при нажатии клавиши "S" после закрытия панели проверки читаемости.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1055">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="96f0a-1056">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="96f0a-1057">Устранена проблема, из-за которой веб-надстройки обращались к сообщениям, управляемым цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1057">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="96f0a-1058">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1058">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="96f0a-1059">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1059">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="96f0a-1060">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-1060">PowerPoint</span></span>

- <span data-ttu-id="96f0a-1061">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1061">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="96f0a-1062">Устранена проблема, которая могла вызвать сбой при использовании контекстного меню в устаревших комментариях PPT.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1062">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="96f0a-1063">Project</span><span class="sxs-lookup"><span data-stu-id="96f0a-1063">Project</span></span>

- <span data-ttu-id="96f0a-1064">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1064">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="96f0a-1065">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1065">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="96f0a-1066">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1066">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="96f0a-1067">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1067">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-1068">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-1068">Word</span></span>

- <span data-ttu-id="96f0a-1069">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1069">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="96f0a-1070">Диспетчер стандартных блоков может отображать неправильное оповещение: "Были изменены стили, стандартные блоки".</span><span class="sxs-lookup"><span data-stu-id="96f0a-1070">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-1071">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-1071">Office Suite</span></span>

- <span data-ttu-id="96f0a-1072">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1072">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="96f0a-1073">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1073">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="96f0a-1074">Исправлена ошибка в настройке ODT и крайнего срока обновления GPO, когда относительный крайний срок работает только при первом его включении, исправление включает относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1074">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="96f0a-1075">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1075">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="96f0a-1076">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1076">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="96f0a-1078">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="96f0a-1078">Version 1908: February 11</span></span>
<span data-ttu-id="96f0a-1079">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-1079">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="96f0a-1080">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-1080">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-1082">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-1082">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-1083">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-1083">Excel</span></span>

- <span data-ttu-id="96f0a-1084">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1084">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="96f0a-1085">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1085">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="96f0a-1086">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1086">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="96f0a-1087">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1087">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="96f0a-1088">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1088">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="96f0a-1089">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1089">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="96f0a-1090">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-1090">Outlook</span></span>

- <span data-ttu-id="96f0a-1091">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1091">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="96f0a-1092">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1092">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="96f0a-1093">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1093">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="96f0a-1094">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1094">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="96f0a-1095">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1095">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="96f0a-1096">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1096">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="96f0a-1097">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1097">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="96f0a-1098">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-1098">PowerPoint</span></span>

- <span data-ttu-id="96f0a-1099">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1099">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="96f0a-1100">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1100">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="96f0a-1101">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1101">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="96f0a-1102">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1102">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="96f0a-1103">Project</span><span class="sxs-lookup"><span data-stu-id="96f0a-1103">Project</span></span>

- <span data-ttu-id="96f0a-1104">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1104">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="96f0a-1105">Word</span><span class="sxs-lookup"><span data-stu-id="96f0a-1105">Word</span></span>

- <span data-ttu-id="96f0a-1106">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1106">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-1107">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-1107">Office Suite</span></span>

- <span data-ttu-id="96f0a-1108">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1108">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="96f0a-1110">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="96f0a-1110">Version 1908: January 14</span></span>
<span data-ttu-id="96f0a-1111">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="96f0a-1111">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="96f0a-1112">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="96f0a-1112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="96f0a-1114">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="96f0a-1114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="96f0a-1115">Excel</span><span class="sxs-lookup"><span data-stu-id="96f0a-1115">Excel</span></span>

- <span data-ttu-id="96f0a-1116">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1116">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="96f0a-1117">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1117">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="96f0a-1118">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытой надстройкой.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1118">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="96f0a-1119">Outlook</span><span class="sxs-lookup"><span data-stu-id="96f0a-1119">Outlook</span></span>

- <span data-ttu-id="96f0a-1120">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1120">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="96f0a-1121">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1121">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="96f0a-1122">Исправлена проблема, вызывавшая у пользователей периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1122">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="96f0a-1123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="96f0a-1123">PowerPoint</span></span>

- <span data-ttu-id="96f0a-1124">Исправлена проблема, из-за которой копирование слайда из одной презентации в другую могло создавать дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1124">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="96f0a-1125">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="96f0a-1125">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="96f0a-1126">Набор Office</span><span class="sxs-lookup"><span data-stu-id="96f0a-1126">Office Suite</span></span>

- <span data-ttu-id="96f0a-1127">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1127">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="96f0a-1128">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1128">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="96f0a-1129">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="96f0a-1129">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="96f0a-1131">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="96f0a-1131">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
