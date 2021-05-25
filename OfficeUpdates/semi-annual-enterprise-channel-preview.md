---
title: Заметки о выпусках Полугодового канала (предварительной корпоративной версии) в 2021 г.
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel (Targeted) для подписки "Приложения Microsoft 365" в 2021 г. для ИТ-специалистов.
ms.openlocfilehash: ca32e509ccce9a52e1efb67fe05275eb65a2b64e
ms.sourcegitcommit: c615a8b353e967222e6a75121fa6aea3d673b28b
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/24/2021
ms.locfileid: "52625934"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="75216-103">Заметки о выпусках для Полугодового канала (предварительной корпоративной версии)</span><span class="sxs-lookup"><span data-stu-id="75216-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="75216-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (предварительная корпоративная версия) для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="75216-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


## <a name="version-2102-may-11"></a><span data-ttu-id="75216-105">Версия 2102: 11 мая</span><span class="sxs-lookup"><span data-stu-id="75216-105">Version 2102: May 11</span></span>
<span data-ttu-id="75216-106">*Версия 2102 (сборка 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="75216-106">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="75216-107">Список обновлений для системы безопасности см. в статье: [Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft Office](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="75216-107">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="75216-109">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="75216-109">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="75216-110">Excel</span><span class="sxs-lookup"><span data-stu-id="75216-110">Excel</span></span>

- <span data-ttu-id="75216-111">Исправлена проблема, из-за которой не загружались некоторые надстройки для автоматизации Excel.</span><span class="sxs-lookup"><span data-stu-id="75216-111">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="75216-112">Исправлена проблема, из-за которой форматирование даты отображалось неправильно на некоторых языках при использовании надстроек.</span><span class="sxs-lookup"><span data-stu-id="75216-112">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="75216-113">Исправлена проблема, из-за которой не удавалось вставлять формулы на защищенном листе.</span><span class="sxs-lookup"><span data-stu-id="75216-113">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="75216-114">Outlook</span><span class="sxs-lookup"><span data-stu-id="75216-114">Outlook</span></span>

- <span data-ttu-id="75216-115">Это позволяет пользователям настраивать Outlook для добавления собрания по сети к каждому собранию, которое они создают.</span><span class="sxs-lookup"><span data-stu-id="75216-115">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="75216-116">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="75216-116">PowerPoint</span></span>

- <span data-ttu-id="75216-117">Исправлена проблема со связанным рисунками.</span><span class="sxs-lookup"><span data-stu-id="75216-117">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="75216-118">Word</span><span class="sxs-lookup"><span data-stu-id="75216-118">Word</span></span>

- <span data-ttu-id="75216-119">Исправлена ошибка в Wordmail, из-за которой некоторые пользователи не могли отправить сообщение, если 2084-й символ в ссылке был управляющим.</span><span class="sxs-lookup"><span data-stu-id="75216-119">Fixed an issue in Wordmail where someone cannot send an item when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="75216-120">Набор Office</span><span class="sxs-lookup"><span data-stu-id="75216-120">Office Suite</span></span>

- <span data-ttu-id="75216-121">Исправлена проблема, из-за которой шаблоны Office включались даже при запросе на отключение, размещенном GPO.</span><span class="sxs-lookup"><span data-stu-id="75216-121">Fixed an issue where Office templates turned on even with GPO placed disable request.</span></span>


- <span data-ttu-id="75216-122">Исправлена проблема, из-за которой Word неожиданно закрывался при печати больших документов.</span><span class="sxs-lookup"><span data-stu-id="75216-122">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>



[//]: # (НЕ УДАЛЯЙТЕ СВЕДЕНИЯ ОБ ОШИБКАХ (КОНЕЦ СОДЕРЖИМОГО))

## <a name="version-2102-april-13"></a><span data-ttu-id="75216-124">Версия 2102: 13 апреля</span><span class="sxs-lookup"><span data-stu-id="75216-124">Version 2102: April 13</span></span>
<span data-ttu-id="75216-125">*Версия 2102 (сборка 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="75216-125">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="75216-126">Список обновлений для системы безопасности см. в статье: [Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft Office](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="75216-126">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="75216-128">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="75216-128">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="75216-129">Access</span><span class="sxs-lookup"><span data-stu-id="75216-129">Access</span></span>

- <span data-ttu-id="75216-130">Исправлена проблема, из-за которой в некоторых случаях при выполнении запроса к серверу SQL Server могло возникать сообщение об ошибке, указывающее на "недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="75216-130">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="75216-131">Excel</span><span class="sxs-lookup"><span data-stu-id="75216-131">Excel</span></span>

- <span data-ttu-id="75216-132">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="75216-132">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="75216-133">Исправлена проблема, из-за которой проверка данных могла неожиданно применяться к ячейкам после добавления строк в таблицу на другом листе.</span><span class="sxs-lookup"><span data-stu-id="75216-133">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="75216-134">Исправлена проблема, из-за которой функция отображения DialogSheets не работала в 32-битных версиях Excel</span><span class="sxs-lookup"><span data-stu-id="75216-134">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="75216-135">Outlook</span><span class="sxs-lookup"><span data-stu-id="75216-135">Outlook</span></span>

- <span data-ttu-id="75216-136">Исправлена проблема, которая вызывала сбой Outlook при простое.</span><span class="sxs-lookup"><span data-stu-id="75216-136">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="75216-137">Исправлена проблема, из-за которой пользовательские параметры функции "Параметры облака" менялись на значения по умолчанию после настройки Outlook на новом устройстве.</span><span class="sxs-lookup"><span data-stu-id="75216-137">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="75216-138">Исправлена проблема, из-за которой пользователи видели больше подписей, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="75216-138">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="75216-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="75216-139">PowerPoint</span></span>

- <span data-ttu-id="75216-140">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="75216-140">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="75216-141">Word</span><span class="sxs-lookup"><span data-stu-id="75216-141">Word</span></span>

- <span data-ttu-id="75216-142">Исправлена проблема, из-за которой в отключенных командах на ленте Office становился серым значок, но не текст в теме Office темно-серого цвета.</span><span class="sxs-lookup"><span data-stu-id="75216-142">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="75216-143">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="75216-143">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="75216-144">Исправлена проблема, из-за которой набор текста в конце скрытого абзаца мог привести к зависанию приложения.</span><span class="sxs-lookup"><span data-stu-id="75216-144">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="75216-145">Набор Office</span><span class="sxs-lookup"><span data-stu-id="75216-145">Office Suite</span></span>

- <span data-ttu-id="75216-146">Исправлена проблема, из-за которой пользователи не могли сохранить файл при открытии ранее открывавшегося файла с несохраненными правками, когда файл уже удален.</span><span class="sxs-lookup"><span data-stu-id="75216-146">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="75216-147">После исправления пользователи получат понятное сообщение о том, что файл удален, поэтому можно отменить изменения или сохранить файл с помощью функции "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="75216-147">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="75216-148">Исправлена ошибка переименования при открытии файла SyncBacked в автономном режиме, а затем переименовании файла в приложении перед сохранением файла.</span><span class="sxs-lookup"><span data-stu-id="75216-148">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="75216-149">Исправлена проблема, из-за которой для пользователей GCC была отключена Диктовка</span><span class="sxs-lookup"><span data-stu-id="75216-149">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="75216-150">Исправлена проблема, которая делала текст в Outlook прозрачным и поэтому невидимым.</span><span class="sxs-lookup"><span data-stu-id="75216-150">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-09"></a><span data-ttu-id="75216-152">Версия 2102: 9 марта</span><span class="sxs-lookup"><span data-stu-id="75216-152">Version 2102: March 09</span></span>
<span data-ttu-id="75216-153">*Версия 2102 (сборка 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="75216-153">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="75216-154">Список обновлений для системы безопасности см. в статье: [Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft Office](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="75216-154">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="75216-156">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="75216-156">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="75216-157">Excel</span><span class="sxs-lookup"><span data-stu-id="75216-157">Excel</span></span>

- <span data-ttu-id="75216-158">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="75216-158">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="75216-159">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="75216-159">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="75216-160">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="75216-160">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="75216-161">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-161">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="75216-162">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="75216-162">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="75216-163">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="75216-163">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="75216-164">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-164">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="75216-165">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="75216-165">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="75216-166">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="75216-166">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="75216-167">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="75216-167">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="75216-168">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="75216-168">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="75216-169">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="75216-169">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="75216-170">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-170">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="75216-171">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="75216-171">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="75216-172">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 / Microsoft 365 и планом обслуживания Power BI Pro.</span><span class="sxs-lookup"><span data-stu-id="75216-172">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="75216-173">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="75216-173">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="75216-174">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="75216-174">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="75216-175">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-175">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="75216-176">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="75216-176">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="75216-177">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="75216-177">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="75216-178">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="75216-178">No conversion required.</span></span><br /><span data-ttu-id="75216-179">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="75216-179">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="75216-180">**Создание профессиональных схем Visio в Excel.** Создавайте на листе схемы, основанные на данных, например блок-схемы или организационные диаграммы.</span><span class="sxs-lookup"><span data-stu-id="75216-180">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="75216-181">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-181">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


- <span data-ttu-id="75216-182">**Интеграция AMSI с Office для работы с XLM-макросами:** AMSI представляет собой открытый интерфейс, доступный в Windows 10 и позволяющий приложениям запрашивать во время своей работы синхронное сканирование буфера памяти установленной антивирусной программой или решением в сфере безопасности.</span><span class="sxs-lookup"><span data-stu-id="75216-182">**AMSI integration with Office for XLM macros:** AMSI is an open interface available on Windows 10 for applications to request, at runtime, a synchronous scan of a memory buffer by an installed antivirus or security solution.</span></span> <span data-ttu-id="75216-183">При выявлении вредоносных действий пользователь получает уведомление от Excel, и сеанс приложения закрывается во избежание дальнейшего ущерба.</span><span class="sxs-lookup"><span data-stu-id="75216-183">When malicious activity is detected, the user is notified by Excel, and the application session is shut down to avoid any further damage.</span></span> <span data-ttu-id="75216-184">Это может остановить осуществляемую атаку и защитить как устройство, так и пользователя.</span><span class="sxs-lookup"><span data-stu-id="75216-184">This can stop an attack in its tracks, protecting both the device and user.</span></span> <span data-ttu-id="75216-185">Дополнительные сведения см. в этой [записи блога](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/).</span><span class="sxs-lookup"><span data-stu-id="75216-185">See details in [blog post](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/).</span></span>

### <a name="outlook"></a><span data-ttu-id="75216-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="75216-186">Outlook</span></span>

- <span data-ttu-id="75216-187">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="75216-187">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="75216-188">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="75216-188">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="75216-189">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-189">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="75216-190">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="75216-190">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="75216-191">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="75216-191">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="75216-192">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="75216-192">No conversion required.</span></span><br /><span data-ttu-id="75216-193">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="75216-193">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="75216-194">**Новая функция "Поиск помещений".** Поиск конференц-залов с учетом различных возможностей. </span><span class="sxs-lookup"><span data-stu-id="75216-194">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="75216-195">**Поиск естественными фразами.** Используйте обычные фразы, например "запись к ветеринару на прошлой неделе", чтобы отфильтровать и сузить область поиска.</span><span class="sxs-lookup"><span data-stu-id="75216-195">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="75216-196">**Быстрое повторное открытие элементов из предыдущего сеанса Outlook.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="75216-196">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="75216-197">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/automatically-restore-windows-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="75216-197">See details in [blog post](https://insider.office.com/ru-RU/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="75216-198">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="75216-198">PowerPoint</span></span>

- <span data-ttu-id="75216-199">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="75216-199">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="75216-200">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="75216-200">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="75216-201">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="75216-201">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="75216-202">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="75216-202">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="75216-203">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="75216-203">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="75216-204">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="75216-204">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="75216-205">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-205">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="75216-206">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="75216-206">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="75216-207">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="75216-207">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="75216-208">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="75216-208">No conversion required.</span></span><br /><span data-ttu-id="75216-209">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="75216-209">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="75216-210">Visio</span><span class="sxs-lookup"><span data-stu-id="75216-210">Visio</span></span>

- <span data-ttu-id="75216-211">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="75216-211">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="75216-212">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-212">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="75216-213">Word</span><span class="sxs-lookup"><span data-stu-id="75216-213">Word</span></span>

- <span data-ttu-id="75216-214">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="75216-214">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="75216-215">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="75216-215">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="75216-216">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="75216-216">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="75216-217">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="75216-217">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="75216-218">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="75216-218">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="75216-219">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="75216-219">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="75216-220">Подробнее</span><span class="sxs-lookup"><span data-stu-id="75216-220">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="75216-221">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="75216-221">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="75216-222">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="75216-222">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="75216-223">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="75216-223">No conversion required.</span></span><br /><span data-ttu-id="75216-224">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="75216-224">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="75216-225">Набор Office</span><span class="sxs-lookup"><span data-stu-id="75216-225">Office Suite</span></span>

- <span data-ttu-id="75216-226">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="75216-226">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="75216-227">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="75216-227">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="75216-228">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="75216-228">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="75216-231">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="75216-231">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="75216-232">Доступ</span><span class="sxs-lookup"><span data-stu-id="75216-232">Access</span></span>

- <span data-ttu-id="75216-233">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="75216-233">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="75216-234">Исправлена проблема, из-за которой пользователям отображалось диалоговое окно "Недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="75216-234">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="75216-235">Excel</span><span class="sxs-lookup"><span data-stu-id="75216-235">Excel</span></span>

- <span data-ttu-id="75216-236">Исправлена проблема, нарушавшая работу некоторых устаревших макросов Excel 4.0 и Excel 5.0, а также некоторых вызовов VBA в dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="75216-236">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="75216-237">Исправлена проблема, из-за которой Excel мог неожиданно закрываться при использовании меню "Дополнительные вычисления" для сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="75216-237">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="75216-238">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="75216-238">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="75216-239">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании функции "Вставить связанный рисунок".</span><span class="sxs-lookup"><span data-stu-id="75216-239">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="75216-240">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="75216-240">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="75216-241">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="75216-241">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="75216-242">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="75216-242">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="75216-243">Исправлена проблема, из-за которой для некоторых пользователей неверно отображалась панель сообщений, уведомляющая о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="75216-243">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="75216-244">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="75216-244">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="75216-245">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="75216-245">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="75216-246">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="75216-246">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="75216-247">Outlook</span><span class="sxs-lookup"><span data-stu-id="75216-247">Outlook</span></span>

- <span data-ttu-id="75216-248">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="75216-248">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="75216-249">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось в определенных сценариях поиска.</span><span class="sxs-lookup"><span data-stu-id="75216-249">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="75216-250">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="75216-250">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="75216-251">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="75216-251">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="75216-252">Исправлена проблема, из-за которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="75216-252">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="75216-253">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="75216-253">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="75216-254">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="75216-254">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="75216-255">Исправлена проблема, приводившая к зависаниям у некоторых пользователей при загрузке их календарей.</span><span class="sxs-lookup"><span data-stu-id="75216-255">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="75216-256">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="75216-256">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="75216-257">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="75216-257">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="75216-258">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="75216-258">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="75216-259">Исправлена проблема, из-за которой новые календари не появлялись в области навигации, пока пользователь не перезапустит Outlook.</span><span class="sxs-lookup"><span data-stu-id="75216-259">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="75216-260">Исправлена проблема, из-за которой при поиске в некэшированных общих календарях не возвращались никакие результаты.</span><span class="sxs-lookup"><span data-stu-id="75216-260">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="75216-261">Исправлена проблема, из-за которой у некоторых пользователей приложение закрывалось при закрытии окон сообщений.</span><span class="sxs-lookup"><span data-stu-id="75216-261">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="75216-262">Исправлена проблема, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="75216-262">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="75216-263">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="75216-263">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="75216-264">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при выполнении определенных сценариев поиска.</span><span class="sxs-lookup"><span data-stu-id="75216-264">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="75216-265">Исправлена проблема, из-за которой приложение иногда неожиданно закрывалось, когда пользователи выполняли поиск в Outlook.</span><span class="sxs-lookup"><span data-stu-id="75216-265">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="75216-266">Исправлена проблема, приводившая к зависанию у пользователей облачных параметров при обновлении настроек.</span><span class="sxs-lookup"><span data-stu-id="75216-266">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="75216-267">Исправлена проблема, из-за которой не удавалось сохранить измененную подпись после предложения пользователю этого действия.</span><span class="sxs-lookup"><span data-stu-id="75216-267">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="75216-268">Исправлена проблема, из-за которой некоторые пользователи не видели подписей в раскрывающемся списке подписей, хотя у них настроена одна или несколько подписей.</span><span class="sxs-lookup"><span data-stu-id="75216-268">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="75216-269">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="75216-269">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="75216-270">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="75216-270">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="75216-271">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="75216-271">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="75216-272">Исправлена проблема, из-за которой возникали проблемы с отображением правильной подписи по умолчанию в OWA.</span><span class="sxs-lookup"><span data-stu-id="75216-272">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="75216-273">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="75216-273">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="75216-274">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="75216-274">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="75216-275">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="75216-275">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="75216-276">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="75216-276">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="75216-277">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="75216-277">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="75216-278">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="75216-278">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="75216-279">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="75216-279">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="75216-280">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="75216-280">0 = filetimes are excluded.</span></span>  <span data-ttu-id="75216-281">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="75216-281">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="75216-282">Исправлена проблема, приводившая к исчезновению встроенных изображений при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="75216-282">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="75216-283">Исправлена проблема, из-за которой значок шифрования не отображался в сообщениях, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="75216-283">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="75216-284">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="75216-284">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="75216-285">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="75216-285">PowerPoint</span></span>

- <span data-ttu-id="75216-286">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="75216-286">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="75216-287">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="75216-287">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="75216-288">Это изменение устраняет проблему с заливками путей при объединений фигур определенных геометрий.</span><span class="sxs-lookup"><span data-stu-id="75216-288">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="75216-289">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="75216-289">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="75216-290">Это изменение устраняет проблему с обработкой ошибок, которые могут возникнуть во время загрузки видео.</span><span class="sxs-lookup"><span data-stu-id="75216-290">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="75216-291">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="75216-291">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="75216-292">Исправлена проблема, из-за которой команда размера шрифта, добавленная в QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="75216-292">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="75216-293">Исправлена проблема, приводившая к ошибке при сохранении файла после дублирования слайда, содержащего недавно записанный звук.</span><span class="sxs-lookup"><span data-stu-id="75216-293">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="75216-294">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="75216-294">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="75216-295">Исправлена проблема с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="75216-295">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="75216-296">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="75216-296">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="75216-297">Исправление для устранения проблемы с использованием IRM/защищенных документов при возникновении ошибки слияния.</span><span class="sxs-lookup"><span data-stu-id="75216-297">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="75216-298">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="75216-298">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="75216-299">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="75216-299">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="75216-300">Исправлена проблема, из-за которой в некоторых сценариях выбор идеи оформления удаляет метку классификации данных в презентации.</span><span class="sxs-lookup"><span data-stu-id="75216-300">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="75216-301">Project</span><span class="sxs-lookup"><span data-stu-id="75216-301">Project</span></span>

- <span data-ttu-id="75216-302">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="75216-302">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="75216-303">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="75216-303">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="75216-304">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="75216-304">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="75216-305">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="75216-305">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="75216-306">Устранена проблема, при которой отдельные проекты могли открываться при наличии проблемы в какой-либо части загрузки файла проекта.</span><span class="sxs-lookup"><span data-stu-id="75216-306">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="75216-307">Исправлена проблема, из-за которой границы не отображались для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="75216-307">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="75216-308">Исправлена проблема, из-за которой не работало перетаскивание для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="75216-308">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="75216-309">Устранена проблема, из-за которой сведение базовых затрат выполнялось неправильно, если затратный ресурс был назначен задаче-вехе.</span><span class="sxs-lookup"><span data-stu-id="75216-309">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="75216-310">Visio</span><span class="sxs-lookup"><span data-stu-id="75216-310">Visio</span></span>

- <span data-ttu-id="75216-311">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="75216-311">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="75216-312">Word</span><span class="sxs-lookup"><span data-stu-id="75216-312">Word</span></span>

- <span data-ttu-id="75216-313">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="75216-313">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="75216-314">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="75216-314">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="75216-315">Это изменение исправляет проблему, связанную с курсором при редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="75216-315">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="75216-316">Исправлена проблема с применением цветовой гаммы к значкам и изображениям SVG с трехмерными эффектами.</span><span class="sxs-lookup"><span data-stu-id="75216-316">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="75216-317">Исправлена проблема, из-за которой диктор иногда пропускает абзац.</span><span class="sxs-lookup"><span data-stu-id="75216-317">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="75216-318">Исправлена проблема с элементами управления форматированным текстом.</span><span class="sxs-lookup"><span data-stu-id="75216-318">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="75216-319">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="75216-319">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="75216-320">Устранена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="75216-320">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="75216-321">Исправлена ошибка, из-за которой стили документов заменялись другими стилями из шаблона.</span><span class="sxs-lookup"><span data-stu-id="75216-321">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="75216-322">Исправление ошибки утверждения, вызываемой оптимизированными шлюзами, затрагивающими Word.</span><span class="sxs-lookup"><span data-stu-id="75216-322">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="75216-323">Набор Office</span><span class="sxs-lookup"><span data-stu-id="75216-323">Office Suite</span></span>

- <span data-ttu-id="75216-324">Исправлена проблема, вызывавшая сбой при попытке сохранить файлы, перешедшие из состояния "синхронизировано" в состояние "только для сервера".</span><span class="sxs-lookup"><span data-stu-id="75216-324">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="75216-325">Исправлена проблема, из-за которой попытка выполнить действие "Сохранить как" завершалась неудачей в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="75216-325">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="75216-326">Исправлена проблема, из-за которой параметр SaveRequestManagerCam приводил к закрытию приложения, а не возвращал ошибку.</span><span class="sxs-lookup"><span data-stu-id="75216-326">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="75216-327">Исправлена последовательность закрытия файлов. Теперь все независимые компоненты закрываются правильно.</span><span class="sxs-lookup"><span data-stu-id="75216-327">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="75216-328">Исправлена ​​проблема, из-за которой файл открывался со статусом НЕ SyncBacked, если URL-адрес из кэша и URL-адрес из OneDrive НЕ совпадали.</span><span class="sxs-lookup"><span data-stu-id="75216-328">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="75216-329">Исправлена ошибка, из-за которой при копировании и вставке сообщений в Skype для бизнеса отображалось диалоговое окно "Произошла ошибка при вставке содержимого".</span><span class="sxs-lookup"><span data-stu-id="75216-329">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="75216-330">Устранена проблема, из-за которой возникала ошибка при копировании и вставке текста из комментария в Excel.</span><span class="sxs-lookup"><span data-stu-id="75216-330">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="75216-331">Исправлен сбой, который иногда возникал при использовании диктора в тексте с математическими уравнениями.</span><span class="sxs-lookup"><span data-stu-id="75216-331">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="75216-p118">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах тонера нет в принципе. Сообщение было изменено и теперь гласит: "Мало чернил или тонера" и "Нет чернил или тонера".</span><span class="sxs-lookup"><span data-stu-id="75216-p118">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="75216-334">Исправлена проблема, из-за которой установка более новой версии Office поверх некоторых старых версий могла приводить к ухудшению функциональности (например, невозможности использовать Power Query) из-за отсутствия записей в реестре.</span><span class="sxs-lookup"><span data-stu-id="75216-334">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="75216-335">Исправлена проблема, из-за которой защита от потери данных в конечной точке Microsoft 365 не могла классифицировать документы Office на диске.</span><span class="sxs-lookup"><span data-stu-id="75216-335">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="75216-336">Исправлена проблема, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="75216-336">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="75216-337">Устранена проблема, связанная с уведомлениями о событиях контроллера мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="75216-337">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="75216-338">Устранена проблема, связанная с расчетом времени в обработчике проигрывателя мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="75216-338">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="75216-339">Оптимизированный размер двоичного файла.</span><span class="sxs-lookup"><span data-stu-id="75216-339">Optimized binary size.</span></span>


- <span data-ttu-id="75216-340">Anaheim WebView пока не поддерживает службу Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="75216-340">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="75216-341">С этим исправлением платформа надстроек Office откатывается на веб-представление уровнем ниже в среде с поддержкой WIP.</span><span class="sxs-lookup"><span data-stu-id="75216-341">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="75216-342">Это может быть Edge Spartan WebView или Trident WebView в зависимости от среды на компьютере пользователя.</span><span class="sxs-lookup"><span data-stu-id="75216-342">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="75216-343">Оба веб-представления уровнем ниже поддерживают WIP.</span><span class="sxs-lookup"><span data-stu-id="75216-343">Both down level WebViews support WIP.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-february-09"></a><span data-ttu-id="75216-345">Версия 2008: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="75216-345">Version 2008: February 09</span></span>
<span data-ttu-id="75216-346">*Версия 2008 (сборка 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="75216-346">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="75216-347">Список обновлений для системы безопасности см. в статье: [Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft Office](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="75216-347">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="75216-349">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="75216-349">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="75216-350">Excel</span><span class="sxs-lookup"><span data-stu-id="75216-350">Excel</span></span>

- <span data-ttu-id="75216-351">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="75216-351">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="75216-352">Исправлена проблема, из-за которой не осуществлялся перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="75216-352">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="75216-353">Исправлена проблема, из-за которой производительность выполнения макроса, включающего форматирование диапазона сводной таблицы, снижалась при каждом его выполнении.</span><span class="sxs-lookup"><span data-stu-id="75216-353">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="75216-354">Исправлена проблема, из-за которой удалялись правила условного форматирования при копировании или перемещении листов в другую книгу.</span><span class="sxs-lookup"><span data-stu-id="75216-354">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="75216-355">Исправлена проблема, из-за которой пользователи не могли применять метки конфиденциальности к файлам Excel, если при загрузке приложения был отключен начальный экран.</span><span class="sxs-lookup"><span data-stu-id="75216-355">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="75216-356">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="75216-356">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="75216-357">Outlook</span><span class="sxs-lookup"><span data-stu-id="75216-357">Outlook</span></span>

- <span data-ttu-id="75216-358">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="75216-358">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="75216-359">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="75216-359">PowerPoint</span></span>

- <span data-ttu-id="75216-360">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="75216-360">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="75216-361">Исправлена проблема, из-за которой при копировании и вставке слайда с использованием параметра "Сохранить исходное форматирование" иногда неожиданно выполнялось копирование поверх нового образца слайдов</span><span class="sxs-lookup"><span data-stu-id="75216-361">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="75216-362">Word</span><span class="sxs-lookup"><span data-stu-id="75216-362">Word</span></span>

- <span data-ttu-id="75216-363">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="75216-363">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="75216-364">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="75216-364">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="75216-365">Набор Office</span><span class="sxs-lookup"><span data-stu-id="75216-365">Office Suite</span></span>

- <span data-ttu-id="75216-366">Исправлена проблема, не позволявшая открыть файл в Office.</span><span class="sxs-lookup"><span data-stu-id="75216-366">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="75216-367">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="75216-367">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-january-12"></a><span data-ttu-id="75216-369">Версия 2008: 12 января</span><span class="sxs-lookup"><span data-stu-id="75216-369">Version 2008: January 12</span></span>
<span data-ttu-id="75216-370">*Версия 2008 (сборка 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="75216-370">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="75216-371">Список обновлений для системы безопасности см. в статье: [Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft Office](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="75216-371">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="75216-373">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="75216-373">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="75216-374">Excel</span><span class="sxs-lookup"><span data-stu-id="75216-374">Excel</span></span>

- <span data-ttu-id="75216-375">Исправлена проблема, из-за которой при открытии книг только для чтения, было невозможно обновить данные сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="75216-375">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="75216-376">Это изменение позволяет устранить следующие проблемы: при вставке файла из локальной папки синхронизации OneDrive Excel не отображает правильный значок "Вставить объект".</span><span class="sxs-lookup"><span data-stu-id="75216-376">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="75216-377">Исправлена проблема, из-за которой клиенты не получали уведомлений о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="75216-377">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="75216-378">Исправлена проблема с редактированием, из-за которой использование редактора метода ввода в режиме перезаписи приводило к неправильному изменению дополнительных символов.</span><span class="sxs-lookup"><span data-stu-id="75216-378">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="75216-379">Исправлена проблема при использовании данных в режиме реального времени в сочетании с функцией многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="75216-379">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="75216-380">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="75216-380">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="75216-381">Outlook</span><span class="sxs-lookup"><span data-stu-id="75216-381">Outlook</span></span>

- <span data-ttu-id="75216-382">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="75216-382">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="75216-383">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="75216-383">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="75216-384">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="75216-384">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="75216-385">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="75216-385">PowerPoint</span></span>

- <span data-ttu-id="75216-386">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="75216-386">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="75216-387">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="75216-387">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="75216-388">Project</span><span class="sxs-lookup"><span data-stu-id="75216-388">Project</span></span>

- <span data-ttu-id="75216-389">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="75216-389">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="75216-390">Skype</span><span class="sxs-lookup"><span data-stu-id="75216-390">Skype</span></span>

- <span data-ttu-id="75216-391">Устраняет проблему, из-за которой сертификат TLS-DSK пользователя обновлялся не в ожидаемое время, а только тогда, когда срок его действия оставался менее 12 часов.</span><span class="sxs-lookup"><span data-stu-id="75216-391">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="75216-392">Устраняет проблему, при которой пользовательский интерфейс Skype для бизнеса отображается как пустой после входа в систему, когда Office еще не лицензирован.</span><span class="sxs-lookup"><span data-stu-id="75216-392">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="75216-393">Набор Office</span><span class="sxs-lookup"><span data-stu-id="75216-393">Office Suite</span></span>

- <span data-ttu-id="75216-394">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="75216-394">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="75216-395">Это изменение решает проблему с резервным прокси-сервером SVG, в результате которого возникает нарушение прав доступа.</span><span class="sxs-lookup"><span data-stu-id="75216-395">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="75216-398">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="75216-398">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


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
