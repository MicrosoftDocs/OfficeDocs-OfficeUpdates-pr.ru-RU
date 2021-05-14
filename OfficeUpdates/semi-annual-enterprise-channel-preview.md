---
title: Заметки о выпусках Полугодового канала (предварительной корпоративной версии) в 2021 г.
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel (Targeted) для подписки "Приложения Microsoft 365" в 2021 г. для ИТ-специалистов.
ms.openlocfilehash: e602a1e45b465ff40b034098a118ed75466c03f0
ms.sourcegitcommit: 8841de32b2d66cec6c0b07e7bc87faab0248c019
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/11/2021
ms.locfileid: "52322489"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="ecdc7-103">Заметки о выпусках для Полугодового канала (предварительной корпоративной версии)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="ecdc7-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (предварительная корпоративная версия) для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


## <a name="version-2102-may-11"></a><span data-ttu-id="ecdc7-105">Версия 2102: 11 мая</span><span class="sxs-lookup"><span data-stu-id="ecdc7-105">Version 2102: May 11</span></span>
<span data-ttu-id="ecdc7-106">*Версия 2102 (сборка 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="ecdc7-106">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="ecdc7-107">Обновления для системы безопасности перечислены [здесь](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-107">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ecdc7-109">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ecdc7-109">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ecdc7-110">Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-110">Excel</span></span>

- <span data-ttu-id="ecdc7-111">Исправлена проблема, из-за которой не загружались некоторые надстройки для автоматизации Excel.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-111">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="ecdc7-112">Исправлена проблема, из-за которой форматирование даты отображалось неправильно на некоторых языках при использовании надстроек.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-112">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="ecdc7-113">Исправлена проблема, из-за которой не удавалось вставлять формулы на защищенном листе.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-113">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="ecdc7-114">Outlook</span><span class="sxs-lookup"><span data-stu-id="ecdc7-114">Outlook</span></span>

- <span data-ttu-id="ecdc7-115">Это позволяет пользователям настраивать Outlook для добавления собрания по сети к каждому собранию, которое они создают.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-115">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ecdc7-116">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ecdc7-116">PowerPoint</span></span>

- <span data-ttu-id="ecdc7-117">Исправлена проблема со связанным рисунками.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-117">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="ecdc7-118">Word</span><span class="sxs-lookup"><span data-stu-id="ecdc7-118">Word</span></span>

- <span data-ttu-id="ecdc7-119">Исправлена ошибка в Wordmail, из-за которой некоторые пользователи не могли отправить сообщение, если 2084-й символ в ссылке был управляющим.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-119">Fixed an issue in Wordmail where someone cannot send an item when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ecdc7-120">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ecdc7-120">Office Suite</span></span>

- <span data-ttu-id="ecdc7-121">Исправлена проблема, из-за которой шаблоны Office включались даже при запросе на отключение, размещенном GPO.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-121">Fixed an issue where Office templates turned on even with GPO placed disable request.</span></span>


- <span data-ttu-id="ecdc7-122">Исправлена проблема, из-за которой Word неожиданно закрывался при печати больших документов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-122">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>



[//]: # (НЕ УДАЛЯЙТЕ СВЕДЕНИЯ ОБ ОШИБКАХ (КОНЕЦ СОДЕРЖИМОГО))

## <a name="version-2102-april-13"></a><span data-ttu-id="ecdc7-124">Версия 2102: 13 апреля</span><span class="sxs-lookup"><span data-stu-id="ecdc7-124">Version 2102: April 13</span></span>
<span data-ttu-id="ecdc7-125">*Версия 2102 (сборка 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="ecdc7-125">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="ecdc7-126">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-126">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ecdc7-128">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ecdc7-128">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ecdc7-129">Access</span><span class="sxs-lookup"><span data-stu-id="ecdc7-129">Access</span></span>

- <span data-ttu-id="ecdc7-130">Исправлена проблема, из-за которой в некоторых случаях при выполнении запроса к серверу SQL Server могло возникать сообщение об ошибке, указывающее на "недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-130">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="ecdc7-131">Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-131">Excel</span></span>

- <span data-ttu-id="ecdc7-132">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-132">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="ecdc7-133">Исправлена проблема, из-за которой проверка данных могла неожиданно применяться к ячейкам после добавления строк в таблицу на другом листе.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-133">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="ecdc7-134">Исправлена проблема, из-за которой функция отображения DialogSheets не работала в 32-битных версиях Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-134">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="ecdc7-135">Outlook</span><span class="sxs-lookup"><span data-stu-id="ecdc7-135">Outlook</span></span>

- <span data-ttu-id="ecdc7-136">Исправлена проблема, которая вызывала сбой Outlook при простое.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-136">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="ecdc7-137">Исправлена проблема, из-за которой пользовательские параметры функции "Параметры облака" менялись на значения по умолчанию после настройки Outlook на новом устройстве.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-137">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="ecdc7-138">Исправлена проблема, из-за которой пользователи видели больше подписей, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-138">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ecdc7-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ecdc7-139">PowerPoint</span></span>

- <span data-ttu-id="ecdc7-140">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-140">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="ecdc7-141">Word</span><span class="sxs-lookup"><span data-stu-id="ecdc7-141">Word</span></span>

- <span data-ttu-id="ecdc7-142">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-142">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="ecdc7-143">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-143">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="ecdc7-144">Исправлена проблема, из-за которой набор текста в конце скрытого абзаца мог привести к зависанию приложения.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-144">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ecdc7-145">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ecdc7-145">Office Suite</span></span>

- <span data-ttu-id="ecdc7-146">Исправлена проблема, из-за которой пользователи не могли сохранить файл при открытии ранее открывавшегося файла с несохраненными правками, когда файл уже удален.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-146">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="ecdc7-147">После исправления пользователи получат понятное сообщение о том, что файл удален, поэтому можно отменить изменения или сохранить файл с помощью функции "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-147">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="ecdc7-148">Исправлена ошибка переименования при открытии файла SyncBacked в автономном режиме, а затем переименовании файла в приложении перед сохранением файла.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-148">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="ecdc7-149">Исправлена проблема, из-за которой для пользователей GCC была отключена Диктовка</span><span class="sxs-lookup"><span data-stu-id="ecdc7-149">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="ecdc7-150">Исправлена проблема, которая делала текст в Outlook прозрачным и поэтому невидимым.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-150">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-09"></a><span data-ttu-id="ecdc7-152">Версия 2102: 9 марта</span><span class="sxs-lookup"><span data-stu-id="ecdc7-152">Version 2102: March 09</span></span>
<span data-ttu-id="ecdc7-153">*Версия 2102 (сборка 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="ecdc7-153">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="ecdc7-154">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-154">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ecdc7-156">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ecdc7-156">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ecdc7-157">Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-157">Excel</span></span>

- <span data-ttu-id="ecdc7-158">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-158">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="ecdc7-159">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-159">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="ecdc7-160">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-160">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="ecdc7-161">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-161">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="ecdc7-162">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-162">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="ecdc7-163">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-163">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="ecdc7-164">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-164">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="ecdc7-165">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-165">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="ecdc7-166">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-166">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="ecdc7-167">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-167">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="ecdc7-168">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-168">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="ecdc7-169">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-169">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="ecdc7-170">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-170">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="ecdc7-171">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-171">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="ecdc7-172">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 / Microsoft 365 и планом обслуживания Power BI Pro.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-172">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="ecdc7-173">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-173">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="ecdc7-174">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-174">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="ecdc7-175">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-175">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="ecdc7-176">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-176">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="ecdc7-177">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-177">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ecdc7-178">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-178">No conversion required.</span></span><br /><span data-ttu-id="ecdc7-179">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-179">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="ecdc7-180">**Создание профессиональных схем Visio в Excel.** Создавайте на листе схемы, основанные на данных, например блок-схемы или организационные диаграммы.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-180">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="ecdc7-181">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-181">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="ecdc7-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="ecdc7-182">Outlook</span></span>

- <span data-ttu-id="ecdc7-183">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-183">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="ecdc7-184">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-184">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="ecdc7-185">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-185">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="ecdc7-186">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-186">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="ecdc7-187">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-187">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ecdc7-188">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-188">No conversion required.</span></span><br /><span data-ttu-id="ecdc7-189">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-189">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="ecdc7-190">**Новая функция "Поиск помещений".** Поиск конференц-залов с учетом различных возможностей. </span><span class="sxs-lookup"><span data-stu-id="ecdc7-190">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="ecdc7-191">**Поиск естественными фразами.** Используйте обычные фразы, например "запись к ветеринару на прошлой неделе", чтобы отфильтровать и сузить область поиска.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-191">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="ecdc7-192">**Быстрое повторное открытие элементов из предыдущего сеанса Outlook.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-192">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="ecdc7-193">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/automatically-restore-windows-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-193">See details in [blog post](https://insider.office.com/ru-RU/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ecdc7-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ecdc7-194">PowerPoint</span></span>

- <span data-ttu-id="ecdc7-195">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-195">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="ecdc7-196">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-196">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="ecdc7-197">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-197">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="ecdc7-198">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-198">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="ecdc7-199">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-199">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="ecdc7-200">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-200">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="ecdc7-201">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-201">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="ecdc7-202">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-202">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="ecdc7-203">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-203">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ecdc7-204">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-204">No conversion required.</span></span><br /><span data-ttu-id="ecdc7-205">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-205">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="ecdc7-206">Visio</span><span class="sxs-lookup"><span data-stu-id="ecdc7-206">Visio</span></span>

- <span data-ttu-id="ecdc7-207">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-207">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="ecdc7-208">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-208">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="ecdc7-209">Word</span><span class="sxs-lookup"><span data-stu-id="ecdc7-209">Word</span></span>

- <span data-ttu-id="ecdc7-210">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-210">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="ecdc7-211">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-211">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="ecdc7-212">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-212">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="ecdc7-213">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-213">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="ecdc7-214">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-214">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="ecdc7-215">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-215">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="ecdc7-216">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ecdc7-216">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="ecdc7-217">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-217">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="ecdc7-218">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-218">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ecdc7-219">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-219">No conversion required.</span></span><br /><span data-ttu-id="ecdc7-220">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-220">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="ecdc7-221">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ecdc7-221">Office Suite</span></span>

- <span data-ttu-id="ecdc7-222">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-222">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="ecdc7-223">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-223">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="ecdc7-224">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-224">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ecdc7-227">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ecdc7-227">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ecdc7-228">Доступ</span><span class="sxs-lookup"><span data-stu-id="ecdc7-228">Access</span></span>

- <span data-ttu-id="ecdc7-229">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-229">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="ecdc7-230">Исправлена проблема, из-за которой пользователям отображалось диалоговое окно "Недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-230">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="ecdc7-231">Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-231">Excel</span></span>

- <span data-ttu-id="ecdc7-232">Исправлена проблема, нарушавшая работу некоторых устаревших макросов Excel 4.0 и Excel 5.0, а также некоторых вызовов VBA в dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-232">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="ecdc7-233">Исправлена проблема, из-за которой Excel мог неожиданно закрываться при использовании меню "Дополнительные вычисления" для сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-233">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="ecdc7-234">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-234">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="ecdc7-235">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании функции "Вставить связанный рисунок".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-235">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="ecdc7-236">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-236">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="ecdc7-237">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-237">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="ecdc7-238">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-238">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="ecdc7-239">Исправлена проблема, из-за которой для некоторых пользователей неверно отображалась панель сообщений, уведомляющая о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-239">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="ecdc7-240">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-240">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="ecdc7-241">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-241">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="ecdc7-242">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-242">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="ecdc7-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="ecdc7-243">Outlook</span></span>

- <span data-ttu-id="ecdc7-244">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-244">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="ecdc7-245">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось в определенных сценариях поиска.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-245">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="ecdc7-246">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-246">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="ecdc7-247">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-247">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="ecdc7-248">Исправлена проблема, из-за которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-248">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="ecdc7-249">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-249">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="ecdc7-250">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-250">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="ecdc7-251">Исправлена проблема, приводившая к зависаниям у некоторых пользователей при загрузке их календарей.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-251">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="ecdc7-252">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-252">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="ecdc7-253">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-253">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="ecdc7-254">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-254">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="ecdc7-255">Исправлена проблема, из-за которой новые календари не появлялись в области навигации, пока пользователь не перезапустит Outlook.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-255">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="ecdc7-256">Исправлена проблема, из-за которой при поиске в некэшированных общих календарях не возвращались никакие результаты.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-256">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="ecdc7-257">Исправлена проблема, из-за которой у некоторых пользователей приложение закрывалось при закрытии окон сообщений.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-257">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="ecdc7-258">Исправлена проблема, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-258">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="ecdc7-259">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-259">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="ecdc7-260">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при выполнении определенных сценариев поиска.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-260">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="ecdc7-261">Исправлена проблема, из-за которой приложение иногда неожиданно закрывалось, когда пользователи выполняли поиск в Outlook.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-261">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="ecdc7-262">Исправлена проблема, приводившая к зависанию у пользователей облачных параметров при обновлении настроек.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-262">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="ecdc7-263">Исправлена проблема, из-за которой не удавалось сохранить измененную подпись после предложения пользователю этого действия.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-263">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="ecdc7-264">Исправлена проблема, из-за которой некоторые пользователи не видели подписей в раскрывающемся списке подписей, хотя у них настроена одна или несколько подписей.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-264">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="ecdc7-265">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-265">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="ecdc7-266">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-266">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="ecdc7-267">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-267">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="ecdc7-268">Исправлена проблема, из-за которой возникали проблемы с отображением правильной подписи по умолчанию в OWA.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-268">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="ecdc7-269">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-269">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="ecdc7-270">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-270">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="ecdc7-271">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-271">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="ecdc7-272">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-272">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="ecdc7-273">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-273">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="ecdc7-274">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-274">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="ecdc7-275">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-275">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="ecdc7-276">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-276">0 = filetimes are excluded.</span></span>  <span data-ttu-id="ecdc7-277">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-277">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="ecdc7-278">Исправлена проблема, приводившая к исчезновению встроенных изображений при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-278">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="ecdc7-279">Исправлена проблема, из-за которой значок шифрования не отображался в сообщениях, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-279">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="ecdc7-280">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-280">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ecdc7-281">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ecdc7-281">PowerPoint</span></span>

- <span data-ttu-id="ecdc7-282">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-282">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="ecdc7-283">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-283">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="ecdc7-284">Это изменение устраняет проблему с заливками путей при объединений фигур определенных геометрий.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-284">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="ecdc7-285">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-285">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="ecdc7-286">Это изменение устраняет проблему с обработкой ошибок, которые могут возникнуть во время загрузки видео.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-286">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="ecdc7-287">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-287">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="ecdc7-288">Исправлена проблема, из-за которой команда размера шрифта, добавленная в QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-288">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="ecdc7-289">Исправлена проблема, приводившая к ошибке при сохранении файла после дублирования слайда, содержащего недавно записанный звук.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-289">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="ecdc7-290">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-290">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="ecdc7-291">Исправлена проблема с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-291">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="ecdc7-292">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-292">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="ecdc7-293">Исправление для устранения проблемы с использованием IRM/защищенных документов при возникновении ошибки слияния.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-293">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="ecdc7-294">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-294">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="ecdc7-295">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-295">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="ecdc7-296">Исправлена проблема, из-за которой в некоторых сценариях выбор идеи оформления удаляет метку классификации данных в презентации.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-296">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="ecdc7-297">Project</span><span class="sxs-lookup"><span data-stu-id="ecdc7-297">Project</span></span>

- <span data-ttu-id="ecdc7-298">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-298">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="ecdc7-299">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-299">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="ecdc7-300">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-300">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="ecdc7-301">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-301">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="ecdc7-302">Устранена проблема, при которой отдельные проекты могли открываться при наличии проблемы в какой-либо части загрузки файла проекта.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-302">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="ecdc7-303">Исправлена проблема, из-за которой границы не отображались для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-303">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="ecdc7-304">Исправлена проблема, из-за которой не работало перетаскивание для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-304">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="ecdc7-305">Устранена проблема, из-за которой сведение базовых затрат выполнялось неправильно, если затратный ресурс был назначен задаче-вехе.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-305">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="ecdc7-306">Visio</span><span class="sxs-lookup"><span data-stu-id="ecdc7-306">Visio</span></span>

- <span data-ttu-id="ecdc7-307">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-307">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="ecdc7-308">Word</span><span class="sxs-lookup"><span data-stu-id="ecdc7-308">Word</span></span>

- <span data-ttu-id="ecdc7-309">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-309">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="ecdc7-310">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-310">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="ecdc7-311">Это изменение исправляет проблему, связанную с курсором при редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-311">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="ecdc7-312">Исправлена проблема с применением цветовой гаммы к значкам и изображениям SVG с трехмерными эффектами.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-312">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="ecdc7-313">Исправлена проблема, из-за которой диктор иногда пропускает абзац.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-313">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="ecdc7-314">Исправлена проблема с элементами управления форматированным текстом.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-314">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="ecdc7-315">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-315">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="ecdc7-316">Устранена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-316">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="ecdc7-317">Исправлена ошибка, из-за которой стили документов заменялись другими стилями из шаблона.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-317">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="ecdc7-318">Исправление ошибки утверждения, вызываемой оптимизированными шлюзами, затрагивающими Word.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-318">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ecdc7-319">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ecdc7-319">Office Suite</span></span>

- <span data-ttu-id="ecdc7-320">Исправлена проблема, вызывавшая сбой при попытке сохранить файлы, перешедшие из состояния "синхронизировано" в состояние "только для сервера".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-320">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="ecdc7-321">Исправлена проблема, из-за которой попытка выполнить действие "Сохранить как" завершалась неудачей в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-321">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="ecdc7-322">Исправлена проблема, из-за которой параметр SaveRequestManagerCam приводил к закрытию приложения, а не возвращал ошибку.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-322">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="ecdc7-323">Исправлена последовательность закрытия файлов. Теперь все независимые компоненты закрываются правильно.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-323">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="ecdc7-324">Исправлена ​​проблема, из-за которой файл открывался со статусом НЕ SyncBacked, если URL-адрес из кэша и URL-адрес из OneDrive НЕ совпадали.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-324">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="ecdc7-325">Исправлена ошибка, из-за которой при копировании и вставке сообщений в Skype для бизнеса отображалось диалоговое окно "Произошла ошибка при вставке содержимого".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-325">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="ecdc7-326">Устранена проблема, из-за которой возникала ошибка при копировании и вставке текста из комментария в Excel.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-326">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="ecdc7-327">Исправлен сбой, который иногда возникал при использовании диктора в тексте с математическими уравнениями.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-327">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="ecdc7-p117">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах тонера нет в принципе. Сообщение было изменено и теперь гласит: "Мало чернил или тонера" и "Нет чернил или тонера".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-p117">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="ecdc7-330">Исправлена проблема, из-за которой установка более новой версии Office поверх некоторых старых версий могла приводить к ухудшению функциональности (например, невозможности использовать Power Query) из-за отсутствия записей в реестре.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-330">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="ecdc7-331">Исправлена проблема, из-за которой защита от потери данных в конечной точке Microsoft 365 не могла классифицировать документы Office на диске.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-331">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="ecdc7-332">Исправлена проблема, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-332">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="ecdc7-333">Устранена проблема, связанная с уведомлениями о событиях контроллера мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-333">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="ecdc7-334">Устранена проблема, связанная с расчетом времени в обработчике проигрывателя мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-334">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="ecdc7-335">Оптимизированный размер двоичного файла.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-335">Optimized binary size.</span></span>


- <span data-ttu-id="ecdc7-336">Anaheim WebView пока не поддерживает службу Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-336">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="ecdc7-337">С этим исправлением платформа надстроек Office откатывается на веб-представление уровнем ниже в среде с поддержкой WIP.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-337">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="ecdc7-338">Это может быть Edge Spartan WebView или Trident WebView в зависимости от среды на компьютере пользователя.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-338">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="ecdc7-339">Оба веб-представления уровнем ниже поддерживают WIP.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-339">Both down level WebViews support WIP.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-february-09"></a><span data-ttu-id="ecdc7-341">Версия 2008: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="ecdc7-341">Version 2008: February 09</span></span>
<span data-ttu-id="ecdc7-342">*Версия 2008 (сборка 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="ecdc7-342">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="ecdc7-343">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-343">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ecdc7-345">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ecdc7-345">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ecdc7-346">Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-346">Excel</span></span>

- <span data-ttu-id="ecdc7-347">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-347">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="ecdc7-348">Исправлена проблема, из-за которой не осуществлялся перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-348">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="ecdc7-349">Исправлена проблема, из-за которой производительность выполнения макроса, включающего форматирование диапазона сводной таблицы, снижалась при каждом его выполнении.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-349">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="ecdc7-350">Исправлена проблема, из-за которой удалялись правила условного форматирования при копировании или перемещении листов в другую книгу.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-350">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="ecdc7-351">Исправлена проблема, из-за которой пользователи не могли применять метки конфиденциальности к файлам Excel, если при загрузке приложения был отключен начальный экран.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-351">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="ecdc7-352">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-352">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="ecdc7-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="ecdc7-353">Outlook</span></span>

- <span data-ttu-id="ecdc7-354">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-354">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ecdc7-355">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ecdc7-355">PowerPoint</span></span>

- <span data-ttu-id="ecdc7-356">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-356">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="ecdc7-357">Исправлена проблема, из-за которой при копировании и вставке слайда с использованием параметра "Сохранить исходное форматирование" иногда неожиданно выполнялось копирование поверх нового образца слайдов</span><span class="sxs-lookup"><span data-stu-id="ecdc7-357">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="ecdc7-358">Word</span><span class="sxs-lookup"><span data-stu-id="ecdc7-358">Word</span></span>

- <span data-ttu-id="ecdc7-359">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-359">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="ecdc7-360">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-360">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ecdc7-361">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ecdc7-361">Office Suite</span></span>

- <span data-ttu-id="ecdc7-362">Исправлена проблема, не позволявшая открыть файл в Office.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-362">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="ecdc7-363">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-363">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-january-12"></a><span data-ttu-id="ecdc7-365">Версия 2008: 12 января</span><span class="sxs-lookup"><span data-stu-id="ecdc7-365">Version 2008: January 12</span></span>
<span data-ttu-id="ecdc7-366">*Версия 2008 (сборка 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="ecdc7-366">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="ecdc7-367">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="ecdc7-367">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ecdc7-369">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ecdc7-369">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ecdc7-370">Excel</span><span class="sxs-lookup"><span data-stu-id="ecdc7-370">Excel</span></span>

- <span data-ttu-id="ecdc7-371">Исправлена проблема, из-за которой при открытии книг только для чтения, было невозможно обновить данные сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-371">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="ecdc7-372">Это изменение позволяет устранить следующие проблемы: при вставке файла из локальной папки синхронизации OneDrive Excel не отображает правильный значок "Вставить объект".</span><span class="sxs-lookup"><span data-stu-id="ecdc7-372">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="ecdc7-373">Исправлена проблема, из-за которой клиенты не получали уведомлений о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-373">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="ecdc7-374">Исправлена проблема с редактированием, из-за которой использование редактора метода ввода в режиме перезаписи приводило к неправильному изменению дополнительных символов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-374">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="ecdc7-375">Исправлена проблема при использовании данных в режиме реального времени в сочетании с функцией многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-375">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="ecdc7-376">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-376">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="ecdc7-377">Outlook</span><span class="sxs-lookup"><span data-stu-id="ecdc7-377">Outlook</span></span>

- <span data-ttu-id="ecdc7-378">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-378">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="ecdc7-379">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-379">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="ecdc7-380">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-380">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ecdc7-381">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ecdc7-381">PowerPoint</span></span>

- <span data-ttu-id="ecdc7-382">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-382">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="ecdc7-383">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-383">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="ecdc7-384">Project</span><span class="sxs-lookup"><span data-stu-id="ecdc7-384">Project</span></span>

- <span data-ttu-id="ecdc7-385">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-385">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="ecdc7-386">Skype</span><span class="sxs-lookup"><span data-stu-id="ecdc7-386">Skype</span></span>

- <span data-ttu-id="ecdc7-387">Устраняет проблему, из-за которой сертификат TLS-DSK пользователя обновлялся не в ожидаемое время, а только тогда, когда срок его действия оставался менее 12 часов.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-387">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="ecdc7-388">Устраняет проблему, при которой пользовательский интерфейс Skype для бизнеса отображается как пустой после входа в систему, когда Office еще не лицензирован.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-388">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ecdc7-389">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ecdc7-389">Office Suite</span></span>

- <span data-ttu-id="ecdc7-390">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-390">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="ecdc7-391">Это изменение решает проблему с резервным прокси-сервером SVG, в результате которого возникает нарушение прав доступа.</span><span class="sxs-lookup"><span data-stu-id="ecdc7-391">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="ecdc7-394">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="ecdc7-394">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20638|version-2102-may-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
