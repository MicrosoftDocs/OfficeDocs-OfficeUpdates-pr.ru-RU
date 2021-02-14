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
ms.openlocfilehash: 6b50195e2e84292b0b4b1e259254592f2c4a591b
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173658"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="1d334-103">Заметки о выпусках Полугодового канала (корпоративный)</span><span class="sxs-lookup"><span data-stu-id="1d334-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="1d334-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (корпоративный) для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="1d334-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="1d334-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="1d334-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="1d334-106">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="1d334-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="1d334-107">OneNote 2016 включается по умолчанию, если пользователь, для которого применяется Полугодовой канал (корпоративный), скачивает "Приложения Microsoft 365" на портале Office и устанавливает в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="1d334-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-february-09"></a><span data-ttu-id="1d334-109">Версия 2008: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="1d334-109">Version 2008: February 09</span></span>
<span data-ttu-id="1d334-110">*Версия 2008 (сборка 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="1d334-110">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="1d334-111">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-113">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-114">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-114">Excel</span></span>

- <span data-ttu-id="1d334-115">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="1d334-115">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="1d334-116">Исправлена проблема, из-за которой не осуществлялся перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-116">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="1d334-117">Исправлена проблема, из-за которой производительность выполнения макроса, включающего форматирование диапазона сводной таблицы, снижалась при каждом его выполнении.</span><span class="sxs-lookup"><span data-stu-id="1d334-117">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="1d334-118">Исправлена проблема, из-за которой удалялись правила условного форматирования при копировании или перемещении листов в другую книгу.</span><span class="sxs-lookup"><span data-stu-id="1d334-118">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="1d334-119">Исправлена проблема, из-за которой пользователи не могли применять метки конфиденциальности к файлам Excel, если при загрузке приложения был отключен начальный экран.</span><span class="sxs-lookup"><span data-stu-id="1d334-119">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="1d334-120">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-120">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="1d334-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-121">Outlook</span></span>

- <span data-ttu-id="1d334-122">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="1d334-122">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1d334-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-123">PowerPoint</span></span>

- <span data-ttu-id="1d334-124">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="1d334-124">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="1d334-125">Исправлена проблема, из-за которой при копировании и вставке слайда с использованием параметра "Сохранить исходное форматирование" иногда неожиданно выполнялось копирование поверх нового образца слайдов</span><span class="sxs-lookup"><span data-stu-id="1d334-125">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="1d334-126">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-126">Word</span></span>

- <span data-ttu-id="1d334-127">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="1d334-127">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="1d334-128">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-128">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1d334-129">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-129">Office Suite</span></span>

- <span data-ttu-id="1d334-130">Исправлена проблема, не позволявшая открыть файл в Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-130">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="1d334-131">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="1d334-131">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-09"></a><span data-ttu-id="1d334-133">Версия 2002: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="1d334-133">Version 2002: February 09</span></span>
<span data-ttu-id="1d334-134">*Версия 2002 (сборка 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="1d334-134">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="1d334-135">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-135">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-137">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-137">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1d334-138">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-138">Office Suite</span></span>

- <span data-ttu-id="1d334-139">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="1d334-139">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-09"></a><span data-ttu-id="1d334-141">Версия 1908: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="1d334-141">Version 1908: February 09</span></span>
<span data-ttu-id="1d334-142">*Версия 1908 (сборка 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="1d334-142">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="1d334-143">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-143">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="1d334-144">Версия 2008: 12 января</span><span class="sxs-lookup"><span data-stu-id="1d334-144">Version 2008: January 12</span></span>
<span data-ttu-id="1d334-145">*Версия 2008 (сборка 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="1d334-145">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="1d334-146">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="1d334-148">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="1d334-148">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="1d334-149">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-149">Access</span></span>

- <span data-ttu-id="1d334-150">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="1d334-150">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="1d334-151">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="1d334-151">Search and replace text in SQL View.</span></span> <span data-ttu-id="1d334-152">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="1d334-152">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="1d334-153">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="1d334-153">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="1d334-154">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-154">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="1d334-155">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-155">Excel</span></span>

- <span data-ttu-id="1d334-156">**Ваши любимые функции Excel теперь работают быстрее.** Функции СУММЕСЛИМН, СРЗНАЧЕСЛИМН, СЧЁТЕСЛИМН, МАКСЕСЛИМН и МИНЕСЛИМН теперь работают намного быстрее.</span><span class="sxs-lookup"><span data-stu-id="1d334-156">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="1d334-157">Быстрее переходите к итоговой строке.</span><span class="sxs-lookup"><span data-stu-id="1d334-157">Get to the bottom line more quickly.</span></span> <span data-ttu-id="1d334-158">Попробуйте уже сейчас.</span><span class="sxs-lookup"><span data-stu-id="1d334-158">Try one now.</span></span>

- <span data-ttu-id="1d334-159">**Улучшение функции Realtimedata (RTD):** В Office 365 версии 2002 канала Monthly channel или более поздних версиях функция Excel RealTimeData (ДРВ) работает гораздо быстрее, чем в вычисление данных в таблице в Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="1d334-159">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="1d334-160">Мы удалили узкие места в базовой памяти и структурах данных, а также обеспечили потокобезопасность, чтобы разрешить вычисление во всех доступных потоках многопоточного пересчета (MTR).</span><span class="sxs-lookup"><span data-stu-id="1d334-160">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="1d334-161">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="1d334-161">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="1d334-162">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-162">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="1d334-163">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="1d334-163">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="1d334-164">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="1d334-164">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="1d334-165">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="1d334-165">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="1d334-166">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="1d334-166">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="1d334-167">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="1d334-167">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="1d334-168">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-168">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="1d334-169">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="1d334-169">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-170">Outlook</span></span>

- <span data-ttu-id="1d334-171">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="1d334-171">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="1d334-172">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="1d334-172">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="1d334-173">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="1d334-173">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="1d334-174">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-174">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="1d334-175">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="1d334-175">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="1d334-176">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="1d334-176">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="1d334-177">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="1d334-177">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="1d334-178">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="1d334-178">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="1d334-179">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="1d334-179">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="1d334-180">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="1d334-180">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="1d334-181">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="1d334-181">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="1d334-182">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="1d334-182">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="1d334-183">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-183">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="1d334-184">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="1d334-184">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="1d334-185">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="1d334-185">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="1d334-186">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="1d334-186">See details in [blog post](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="1d334-187">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="1d334-187">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="1d334-188">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-188">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="1d334-189">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="1d334-189">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="1d334-190">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-190">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="1d334-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-191">PowerPoint</span></span>

- <span data-ttu-id="1d334-192">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="1d334-192">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="1d334-193">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-193">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="1d334-194">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-194">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="1d334-195">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="1d334-195">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="1d334-196">**Ссылка на слайд:** попросите коллег поучаствовать в создании презентации и направьте их прямо на нужный слайд.</span><span class="sxs-lookup"><span data-stu-id="1d334-196">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="1d334-197">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-197">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="1d334-198">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="1d334-198">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="1d334-199">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="1d334-199">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="1d334-200">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="1d334-200">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="1d334-201">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="1d334-201">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="1d334-202">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-202">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="1d334-203">**Улучшенные диаграммы.** Более удобное создание диаграмм от руки за счет использования улучшенных соединителей и более совершенного процесса преобразования рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="1d334-203">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="1d334-204">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-204">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="1d334-205">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="1d334-205">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="1d334-206">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="1d334-206">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="1d334-207">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="1d334-207">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="1d334-208">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-208">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="1d334-209">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="1d334-209">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="1d334-210">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-210">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="1d334-211">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="1d334-211">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="1d334-212">**Комментарии.** Новые функций комментирования в PowerPoint позволяют быстро и легко находить и добавлять комментарии к документам.</span><span class="sxs-lookup"><span data-stu-id="1d334-212">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="1d334-213">Модернизируйте совместную работу с помощью новых функций, таких как привязка комментариев, сопоставление, задачи, улучшенные уведомления об упоминаниях и т. д.</span><span class="sxs-lookup"><span data-stu-id="1d334-213">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="1d334-214">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-214">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="1d334-215">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-215">Word</span></span>

- <span data-ttu-id="1d334-216">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="1d334-216">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="1d334-217">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="1d334-217">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="1d334-218">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-218">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="1d334-219">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="1d334-219">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="1d334-220">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="1d334-220">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="1d334-221">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="1d334-221">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="1d334-222">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-222">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="1d334-223">**Подтверждение действий в средстве чтения с экрана.** Подтверждение действий — это важное требование для обеспечения специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="1d334-223">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="1d334-224">С появлением нового API уведомлений из Windows мы можем оповещать пользователей средства чтения с экрана об успехе их действий.</span><span class="sxs-lookup"><span data-stu-id="1d334-224">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="1d334-225">Теперь пользователи экранного диктора в Word для Win32 уведомляются о вырезании, копировании, вставке, использовании полужирного шрифта, курсива или подчеркивания, отмене, повторе, автозамене и автоматическом использовании прописных букв.</span><span class="sxs-lookup"><span data-stu-id="1d334-225">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="1d334-226">Чтобы включить эту возможность, включите экранный диктор с помощью клавиш Windows+CTRL+ВВОД.</span><span class="sxs-lookup"><span data-stu-id="1d334-226">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="1d334-227">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="1d334-227">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-228">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-228">Office Suite</span></span>

- <span data-ttu-id="1d334-229">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="1d334-229">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-232">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1d334-233">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-233">Access</span></span>

- <span data-ttu-id="1d334-234">Исправлена проблема, из-за которой приложение неожиданно завершало работу при использовании окна "Масштаб".</span><span class="sxs-lookup"><span data-stu-id="1d334-234">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="1d334-235">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="1d334-235">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="1d334-236">Это исправление исправляет проблему, из-за которой Access мог аварийно завершать работу при запуске функции Масштаб (Shift + F2) для редактирования текста.</span><span class="sxs-lookup"><span data-stu-id="1d334-236">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="1d334-237">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="1d334-237">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="1d334-238">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-238">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="1d334-239">Исправлена проблема, препятствующая возможности вызова расширенного типа данных "Дата/время" без сбоев приложения.</span><span class="sxs-lookup"><span data-stu-id="1d334-239">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="1d334-240">Проблема исправлена, поэтому теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для управления и изменения типа данных Decimal.</span><span class="sxs-lookup"><span data-stu-id="1d334-240">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="1d334-241">Исправлена ошибка, возникавшая при попытке использовать построитель DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="1d334-241">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="1d334-242">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="1d334-242">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="1d334-243">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-243">Excel</span></span>

- <span data-ttu-id="1d334-244">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="1d334-244">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="1d334-245">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="1d334-245">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="1d334-246">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="1d334-246">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="1d334-247">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="1d334-247">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="1d334-248">Исправлена ошибка, из-за которой не удавалось изменять сводные таблицы и сохранять книги, если они были экспортированы из плана Project.</span><span class="sxs-lookup"><span data-stu-id="1d334-248">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="1d334-249">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="1d334-249">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="1d334-250">Исправлена ошибка, из-за которой в некоторых случаях при открытии файла в режиме "только для чтения" отображалось несколько панелей сообщений.</span><span class="sxs-lookup"><span data-stu-id="1d334-250">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="1d334-251">Исправлена ошибка, из-за которой происходил сбой работы промежуточных итогов структуры при большом количестве повторяющихся значений заголовков столбцов.</span><span class="sxs-lookup"><span data-stu-id="1d334-251">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="1d334-252">Исправлена проблема, из-за которой при открытии книг только для чтения, было невозможно обновить данные сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="1d334-252">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="1d334-253">Это изменение позволяет устранить следующие проблемы: при вставке файла из локальной папки синхронизации OneDrive Excel не отображает правильный значок "Вставить объект".</span><span class="sxs-lookup"><span data-stu-id="1d334-253">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="1d334-254">Исправлена ошибка, из-за которой происходил сбой работы Excel при обновлении объекта групповой политики (например, с помощью удаленного обновления групповой политики) во время многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="1d334-254">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="1d334-255">Исправлена ошибка, из-за которой происходил сбой работы Excel при использовании функции промежуточных итогов в более чем 255 столбцах.</span><span class="sxs-lookup"><span data-stu-id="1d334-255">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="1d334-256">Улучшен кернинг текста в PowerPoint при копировании содержимого из Excel и его вставке в PowerPoint с помощью функции внедрения.</span><span class="sxs-lookup"><span data-stu-id="1d334-256">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="1d334-257">Исправлена ошибка, которая блокировала переключение из режима предварительного просмотра таблицы и редактора запросов в PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="1d334-257">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="1d334-258">Исправлена ошибка, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-258">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="1d334-259">Исправлена проблема, из-за которой клиенты не получали уведомлений о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="1d334-259">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="1d334-260">Исправлена проблема с редактированием, из-за которой использование редактора метода ввода в режиме перезаписи приводило к неправильному изменению дополнительных символов.</span><span class="sxs-lookup"><span data-stu-id="1d334-260">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="1d334-261">Исправлена проблема при использовании данных в режиме реального времени в сочетании с функцией многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="1d334-261">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="1d334-262">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck)</span><span class="sxs-lookup"><span data-stu-id="1d334-262">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="1d334-263">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="1d334-263">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="1d334-264">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="1d334-264">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="1d334-265">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="1d334-265">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="1d334-266">Исправлена проблема, из-за которой некоторые функции выдавали неправильный результат после загрузки книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-266">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="1d334-267">Исправлена проблема с неожиданным завершением работы приложения, которое было связано со ссылками и именованными диапазонами надстройки XLAM.</span><span class="sxs-lookup"><span data-stu-id="1d334-267">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="1d334-268">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="1d334-268">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="1d334-269">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="1d334-269">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="1d334-270">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="1d334-270">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="1d334-271">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="1d334-271">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="1d334-272">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-272">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="1d334-273">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="1d334-273">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="1d334-274">Исправлена проблема, из-за которой в некоторых случаях при щелчке по гиперссылке внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="1d334-274">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="1d334-275">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="1d334-275">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="1d334-276">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-276">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="1d334-277">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="1d334-277">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="1d334-278">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="1d334-278">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="1d334-279">Исправлена проблема, из-за которой использование данных в реальном времени в сочетании с функцией многопоточного пересчета могло привести к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="1d334-279">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="1d334-280">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="1d334-280">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="1d334-281">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="1d334-281">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="1d334-282">Исправлена ошибка, из-за которой Power Pivot не мог распознавать разделитель вкладок.</span><span class="sxs-lookup"><span data-stu-id="1d334-282">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="1d334-283">OneNote</span><span class="sxs-lookup"><span data-stu-id="1d334-283">OneNote</span></span>

- <span data-ttu-id="1d334-284">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="1d334-284">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="1d334-285">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-285">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="1d334-286">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="1d334-286">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="1d334-287">Улучшена синхронизация и стабильность службы за счет временного изменения частоты создания журналов версий страниц.</span><span class="sxs-lookup"><span data-stu-id="1d334-287">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="1d334-288">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-288">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="1d334-289">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="1d334-289">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="1d334-290">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-290">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="1d334-291">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="1d334-291">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="1d334-292">Улучшена синхронизация и стабильность службы за счет временного отключения перемещения страниц в корзину.</span><span class="sxs-lookup"><span data-stu-id="1d334-292">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="1d334-293">Для пользователей, которым нужно удалить страницу, будет отображаться диалоговое окно с вопросом, нужно ли удалить страницу окончательно.</span><span class="sxs-lookup"><span data-stu-id="1d334-293">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="1d334-294">Была исправлена проблема, из-за которой не загружалось меню проверки орфографии.</span><span class="sxs-lookup"><span data-stu-id="1d334-294">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="1d334-295">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-295">Outlook</span></span>

- <span data-ttu-id="1d334-296">Исправлена проблема, из-за которой необязательные сетевые функции блокировали загрузку веб-надстроек.</span><span class="sxs-lookup"><span data-stu-id="1d334-296">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="1d334-297">Подробнее об этом см. здесь: https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="1d334-297">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="1d334-298">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-298">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="1d334-299">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="1d334-299">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="1d334-300">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="1d334-300">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="1d334-301">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="1d334-301">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="1d334-302">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="1d334-302">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="1d334-303">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="1d334-303">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="1d334-304">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="1d334-304">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="1d334-305">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="1d334-305">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="1d334-306">Исправлена проблема, из-за которой иногда не удавалось применить параметр "Включить улучшения общего календаря" к существующим общим календарям.</span><span class="sxs-lookup"><span data-stu-id="1d334-306">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="1d334-307">Исправлена проблема, из-за которой поисковые запросы в календарях групп не возвращали никаких результатов.</span><span class="sxs-lookup"><span data-stu-id="1d334-307">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="1d334-308">Исправлена проблема, из-за которой возникало случайное закрытие при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="1d334-308">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="1d334-309">Устранена проблема, из-за которой пользователи CLP могут столкнуться с закрытием при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="1d334-309">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="1d334-310">Исправлена проблема, из-за которой при открытии облачного вложения ошибка отображалась на странице безопасных ссылок, а не в открываемом документе.</span><span class="sxs-lookup"><span data-stu-id="1d334-310">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="1d334-311">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="1d334-311">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="1d334-312">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="1d334-312">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="1d334-313">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="1d334-313">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="1d334-314">Исправлена ошибка, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="1d334-314">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="1d334-315">Исправлена ошибка, из-за которой происходил сбой события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="1d334-315">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="1d334-316">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="1d334-316">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="1d334-317">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="1d334-317">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="1d334-318">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="1d334-318">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="1d334-319">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="1d334-319">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="1d334-320">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="1d334-320">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="1d334-321">Устранена проблема, которая в некоторых ситуациях приводила к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="1d334-321">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="1d334-322">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="1d334-322">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="1d334-323">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="1d334-323">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="1d334-324">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="1d334-324">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="1d334-325">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="1d334-325">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="1d334-326">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="1d334-326">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="1d334-327">Устранена проблема, из-за которой у пользователей возникали сбои в сторонних приложениях MAPI.</span><span class="sxs-lookup"><span data-stu-id="1d334-327">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="1d334-328">Исправлена проблема, приводившая к неожиданному закрытию Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-328">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="1d334-329">Устранена проблема, приводившая к неожиданному закрытию Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-329">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="1d334-330">Устранена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="1d334-330">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="1d334-331">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="1d334-331">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="1d334-332">Исправлена ошибка, из-за которой приложение неожиданно закрывалось при отправке почты Outlook из других приложений.</span><span class="sxs-lookup"><span data-stu-id="1d334-332">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="1d334-333">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="1d334-333">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="1d334-334">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="1d334-334">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="1d334-335">Устранена проблема, из-за которой иногда происходило неожиданное закрытие при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="1d334-335">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="1d334-336">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="1d334-336">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="1d334-337">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке искажались при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="1d334-337">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="1d334-338">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="1d334-338">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="1d334-339">Устранена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="1d334-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="1d334-340">Исправлена ошибка, из-за которой снижалась производительность при перемещении нескольких почтовых элементов между папками в интерактивном режиме.</span><span class="sxs-lookup"><span data-stu-id="1d334-340">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="1d334-341">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="1d334-341">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="1d334-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = параметры filetime исключены 1 = (по умолчанию) параметры filetime включены</span><span class="sxs-lookup"><span data-stu-id="1d334-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="1d334-343">Исправлена ошибка, из-за которой исчезали встроенные изображения при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="1d334-343">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="1d334-344">Исправлена ошибка, из-за которой имя пользователя отображалось как номер телефона при отправке голосовых сообщений, защищенных службой Azure, в результате чего пользователи классического приложения Outlook не могли открывать голосовые сообщения от внешних пользователей.</span><span class="sxs-lookup"><span data-stu-id="1d334-344">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="1d334-345">Исправлена ошибка, из-за которой при настройке конфигурации OME добавлялись лишние вложения в элемент электронной почты, в результате чего Outlook шифровал сообщение, даже если на стороне службы был настроен параметр DecryptAttachmentsForEncryptOnly.</span><span class="sxs-lookup"><span data-stu-id="1d334-345">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="1d334-346">Исправлена проблема, из-за которой параметры "Только шифрование" и "Не пересылать" оставались включенными в некоторых сценариях, несмотря на то, что они были отключены политикой.</span><span class="sxs-lookup"><span data-stu-id="1d334-346">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="1d334-347">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="1d334-347">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="1d334-348">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="1d334-348">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="1d334-349">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="1d334-349">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="1d334-350">Устранена проблема, которая иногда приводила к неожиданному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="1d334-350">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="1d334-351">Исправлена проблема, из-за которой происходило неожиданное завершение работы при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="1d334-351">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="1d334-352">Исправлена проблема, из-за которой возникали аномалии при использовании пользователями компактного представления.</span><span class="sxs-lookup"><span data-stu-id="1d334-352">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="1d334-353">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="1d334-353">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="1d334-354">Устранена проблема, из-за которой контекстное меню, вызываемое щелчком правой кнопки мыши, не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="1d334-354">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="1d334-355">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="1d334-355">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="1d334-356">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="1d334-356">Do you want to download them anyway?</span></span> <span data-ttu-id="1d334-357">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="1d334-357">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="1d334-358">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-358">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="1d334-359">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="1d334-359">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="1d334-360">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="1d334-360">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="1d334-361">Устранена проблема, из-за которой у пользователей происходило неожиданное завершение работы при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="1d334-361">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="1d334-362">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="1d334-362">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1d334-363">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-363">PowerPoint</span></span>

- <span data-ttu-id="1d334-364">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="1d334-364">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="1d334-365">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="1d334-365">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="1d334-366">Исправление системы безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="1d334-366">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="1d334-367">Исправлена проблема VBA, приводившая к неожиданному завершению работы Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="1d334-367">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="1d334-368">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-368">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="1d334-369">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="1d334-369">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="1d334-370">Исправлена проблема с панелью предложений, которая могла вызвать неожиданное завершение работы приложения.</span><span class="sxs-lookup"><span data-stu-id="1d334-370">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="1d334-371">Исправлена проблема в диалоговом окне "Параметры действия", которая приводила к неожиданному завершению работы приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-371">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="1d334-372">Исправлена проблема с приложением PowerPoint, которая приводила к неожиданному завершению работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-372">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="1d334-373">Исправлена ошибка, из-за которой функция "Рады видеть вас снова!</span><span class="sxs-lookup"><span data-stu-id="1d334-373">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="1d334-374">Продолжайте работу в Office с того места, на котором остановились" не работала в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-374">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="1d334-375">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="1d334-375">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="1d334-376">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="1d334-376">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="1d334-377">Исправлена проблема, из-за которой слайд-шоу в режиме защищенного просмотра не работало.</span><span class="sxs-lookup"><span data-stu-id="1d334-377">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="1d334-378">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-378">Project</span></span>

- <span data-ttu-id="1d334-379">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="1d334-379">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="1d334-380">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="1d334-380">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="1d334-381">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-381">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="1d334-382">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="1d334-382">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="1d334-383">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="1d334-383">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="1d334-384">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="1d334-384">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="1d334-385">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="1d334-385">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="1d334-386">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="1d334-386">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="1d334-387">Устранена проблема, из-за которой при редактировании данных Предшественника или Преемника в представлении формы, запускалось дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="1d334-387">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="1d334-388">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="1d334-388">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="1d334-389">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="1d334-389">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="1d334-390">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-390">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="1d334-391">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="1d334-391">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="1d334-392">Устранена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="1d334-392">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="1d334-393">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="1d334-393">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="1d334-394">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="1d334-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="1d334-395">Исправлена проблема, из-за которой Project мог неожиданно завершать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="1d334-395">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="1d334-396">Skype</span><span class="sxs-lookup"><span data-stu-id="1d334-396">Skype</span></span>

- <span data-ttu-id="1d334-397">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="1d334-397">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="1d334-398">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="1d334-398">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="1d334-399">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="1d334-399">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="1d334-400">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="1d334-400">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="1d334-401">Устраняет проблему, из-за которой сертификат TLS-DSK пользователя обновлялся не в ожидаемое время, а только тогда, когда срок его действия оставался менее 12 часов.</span><span class="sxs-lookup"><span data-stu-id="1d334-401">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="1d334-402">Устраняет проблему, при которой пользовательский интерфейс Skype для бизнеса отображается как пустой после входа в систему, когда Office еще не лицензирован.</span><span class="sxs-lookup"><span data-stu-id="1d334-402">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="1d334-403">Visio</span><span class="sxs-lookup"><span data-stu-id="1d334-403">Visio</span></span>

- <span data-ttu-id="1d334-404">Исправлена проблема, которая приводила к неожиданному завершению работы в режиме динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="1d334-404">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="1d334-405">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="1d334-405">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="1d334-406">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-406">Word</span></span>

- <span data-ttu-id="1d334-407">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="1d334-407">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="1d334-408">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="1d334-408">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="1d334-409">Устранена проблема, которая приводила к неожиданному завершению работы у пользователя при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="1d334-409">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="1d334-410">Устранена проблема, из-за которой иногда происходило неожиданное закрытие при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="1d334-410">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="1d334-411">Исправлена проблема, которая приводила к неожиданному завершению работы при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="1d334-411">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="1d334-412">Исправлена проблема, из-за которой при вставке пронумерованных заголовков появлялся дополнительный отступ.</span><span class="sxs-lookup"><span data-stu-id="1d334-412">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="1d334-413">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="1d334-413">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="1d334-414">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="1d334-414">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="1d334-415">Исправлена проблема, которая приводила к неожиданному завершению работы при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="1d334-415">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="1d334-416">Исправлена проблема, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="1d334-416">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="1d334-417">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="1d334-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="1d334-418">Исправлена ошибка с расширениями комментариев, когда ответ на комментарий имел такое же расширение, что и родительский комментарий.</span><span class="sxs-lookup"><span data-stu-id="1d334-418">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="1d334-419">Исправлена ошибка, из-за которой при ответе на родительский комментарий с неизвестным расширением в списке расширений ответ получал то же расширение.</span><span class="sxs-lookup"><span data-stu-id="1d334-419">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="1d334-420">Решена проблема, из-за которой приложение могло неожиданно закрываться при загрузке.</span><span class="sxs-lookup"><span data-stu-id="1d334-420">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="1d334-421">Исправлена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-421">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="1d334-422">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="1d334-422">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="1d334-423">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec</span><span class="sxs-lookup"><span data-stu-id="1d334-423">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="1d334-424">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-424">Office Suite</span></span>

- <span data-ttu-id="1d334-425">Исправлена проблема для старой области общего доступа, не основанной на веб-службе, из-за которой при закрытии документа при открытой области общего доступа приложение могло неожиданно закрыться.</span><span class="sxs-lookup"><span data-stu-id="1d334-425">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="1d334-426">Исправлена проблема с синхронизацией, из-за которой приложение могло неожиданно завершать работу при закрытии файлов office.</span><span class="sxs-lookup"><span data-stu-id="1d334-426">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="1d334-427">Устранена проблема, из-за которой пользователи не могли импортировать списки SPO при отключенной ADAL.</span><span class="sxs-lookup"><span data-stu-id="1d334-427">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="1d334-428">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="1d334-428">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="1d334-429">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="1d334-429">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="1d334-430">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="1d334-430">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="1d334-431">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="1d334-431">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="1d334-432">Исправлена проблема технологии "Нажми и работай", из-за которой происходил сбой обновления при попытке жесткой связи символьных ссылок.</span><span class="sxs-lookup"><span data-stu-id="1d334-432">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="1d334-433">Исправлена проблема для коммерческих пользователей, применяющих System Center Configuration Manager или другие средства управления для обновления Office с использованием защиты от потери данных в конечной точке Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="1d334-433">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="1d334-434">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="1d334-434">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="1d334-435">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="1d334-435">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="1d334-436">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="1d334-436">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="1d334-437">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="1d334-437">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="1d334-438">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="1d334-438">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="1d334-439">Это изменение решает проблему с резервным прокси-сервером SVG, в результате которого возникает нарушение прав доступа.</span><span class="sxs-lookup"><span data-stu-id="1d334-439">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="1d334-440">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="1d334-440">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="1d334-441">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="1d334-441">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="1d334-442">Это изменение решает проблему при запуске приложений Office из-за невозможности загрузки d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="1d334-442">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="1d334-443">Узел office неожиданно завершал работу в Windows при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="1d334-443">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="1d334-444">Это изменение исправит эту проблему.</span><span class="sxs-lookup"><span data-stu-id="1d334-444">This change would fix this issue.</span></span>


- <span data-ttu-id="1d334-445">Исправлена проблема с неработающим API сообщений для надстроек Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-445">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="1d334-446">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="1d334-446">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="1d334-447">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="1d334-447">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="1d334-448">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="1d334-448">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="1d334-449">Устранена проблема, которая могла приводить к неожиданному завершению работу при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="1d334-449">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-january-12"></a><span data-ttu-id="1d334-451">Версия 2002: 12 января</span><span class="sxs-lookup"><span data-stu-id="1d334-451">Version 2002: January 12</span></span>
<span data-ttu-id="1d334-452">*Версия 2002 (сборка 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="1d334-452">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="1d334-453">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-453">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-455">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-455">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-456">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-456">Excel</span></span>

- <span data-ttu-id="1d334-457">Исправлена проблема, из-за которой использование данных в реальном времени в сочетании с функцией многопоточного пересчета могло привести к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="1d334-457">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1d334-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-458">PowerPoint</span></span>

- <span data-ttu-id="1d334-459">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="1d334-459">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="1d334-460">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-460">Word</span></span>

- <span data-ttu-id="1d334-461">Исправлена ошибка с расширениями комментариев, когда ответ на комментарий имел такое же расширение, что и родительский комментарий.</span><span class="sxs-lookup"><span data-stu-id="1d334-461">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-12"></a><span data-ttu-id="1d334-463">Версия 1908: 12 января</span><span class="sxs-lookup"><span data-stu-id="1d334-463">Version 1908: January 12</span></span>
<span data-ttu-id="1d334-464">*Версия 1908 (сборка 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="1d334-464">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="1d334-465">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-467">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-467">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1d334-468">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-468">Office Suite</span></span>

- <span data-ttu-id="1d334-469">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="1d334-469">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-december-08"></a><span data-ttu-id="1d334-471">Версия 2002: 08 декабря</span><span class="sxs-lookup"><span data-stu-id="1d334-471">Version 2002: December 08</span></span>
<span data-ttu-id="1d334-472">*Версия 2002 (сборка 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="1d334-472">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="1d334-473">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-473">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-475">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-475">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-476">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-476">Excel</span></span>

- <span data-ttu-id="1d334-477">Улучшен кернинг текста в PowerPoint при копировании содержимого из Excel и его вставке в PowerPoint с помощью функции внедрения.</span><span class="sxs-lookup"><span data-stu-id="1d334-477">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="1d334-478">Исправлена проблема, из-за которой происходил сбой работы Excel во время пересчета.</span><span class="sxs-lookup"><span data-stu-id="1d334-478">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="1d334-479">Исправлена проблема, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-479">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="1d334-480">Исправлена проблема, которая блокировала переключение из режима предварительного просмотра таблицы и редактора запросов в PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="1d334-480">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="1d334-481">Улучшена производительность файлов, использующих многие из недавно выпущенных функций.</span><span class="sxs-lookup"><span data-stu-id="1d334-481">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="1d334-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-482">Outlook</span></span>

- <span data-ttu-id="1d334-483">Исправлена проблема, из-за которой при настройке конфигурации OME добавлялись лишние вложения в элемент электронной почты, в результате чего Outlook шифровал сообщение, даже если на стороне службы был настроен параметр DecryptAttachmentsForEncryptOnly.</span><span class="sxs-lookup"><span data-stu-id="1d334-483">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1d334-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-484">PowerPoint</span></span>

- <span data-ttu-id="1d334-485">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-485">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="1d334-486">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-486">Project</span></span>

- <span data-ttu-id="1d334-487">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="1d334-487">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-december-08"></a><span data-ttu-id="1d334-489">Версия 1908: 08 декабря</span><span class="sxs-lookup"><span data-stu-id="1d334-489">Version 1908: December 08</span></span>
<span data-ttu-id="1d334-490">*Версия 1908 (сборка 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="1d334-490">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="1d334-491">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="1d334-492">Версия 2002: 10 ноября</span><span class="sxs-lookup"><span data-stu-id="1d334-492">Version 2002: November 10</span></span>
<span data-ttu-id="1d334-493">*Версия 2002 (сборка 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="1d334-493">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="1d334-494">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-494">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-496">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-496">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-497">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-497">Excel</span></span>

- <span data-ttu-id="1d334-498">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="1d334-498">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="1d334-499">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="1d334-499">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="1d334-500">Исправлена ошибка, из-за которой некоторые функции выдавали неправильный результат после загрузки книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-500">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="1d334-501">Исправлена проблема с неожиданным завершением работы приложения, что было связано со ссылками и именованными диапазонами надстройки XLAM.</span><span class="sxs-lookup"><span data-stu-id="1d334-501">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="1d334-502">Исправлена проблема, из-за которой при запуске макроса расширенного фильтра ошибочно выводились сообщения об ошибках.</span><span class="sxs-lookup"><span data-stu-id="1d334-502">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="1d334-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-503">Outlook</span></span>

- <span data-ttu-id="1d334-504">Исправлена проблема, приводившая к неожиданному отключению внутренних надстроек, если были отключены необязательные сетевые функции.</span><span class="sxs-lookup"><span data-stu-id="1d334-504">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="1d334-505">Исправлена проблема, из-за которой пользователи не могли отправить письмо от имени списка рассылки, скрытого в общей адресной книге.</span><span class="sxs-lookup"><span data-stu-id="1d334-505">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-november-10"></a><span data-ttu-id="1d334-507">Версия 1908: 10 ноября</span><span class="sxs-lookup"><span data-stu-id="1d334-507">Version 1908: November 10</span></span>
<span data-ttu-id="1d334-508">*Версия 1908 (сборка 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="1d334-508">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="1d334-509">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="1d334-510">Версия 2002: 13 октября</span><span class="sxs-lookup"><span data-stu-id="1d334-510">Version 2002: October 13</span></span>
<span data-ttu-id="1d334-511">*Версия 2002 (сборка 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="1d334-511">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="1d334-512">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-514">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-514">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1d334-515">Доступ</span><span class="sxs-lookup"><span data-stu-id="1d334-515">Access</span></span>

- <span data-ttu-id="1d334-516">Больше не должно появляться сообщение "Слишком сложный запрос" или ошибка о превышении ресурсов системы в 64-разрядной версии Access, если вы соблюдаете рекомендации и требования к базам данных Access.</span><span class="sxs-lookup"><span data-stu-id="1d334-516">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="1d334-517">Если вы примените функцию фильтрации после конструктора запросов, в базе данных больше не должен возникать сбой.</span><span class="sxs-lookup"><span data-stu-id="1d334-517">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="1d334-518">Выполните соответствующую проверку.</span><span class="sxs-lookup"><span data-stu-id="1d334-518">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="1d334-519">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-519">Excel</span></span>

- <span data-ttu-id="1d334-520">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="1d334-520">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1d334-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-521">PowerPoint</span></span>

- <span data-ttu-id="1d334-522">Новые презентации, созданные из шаблона, могли наследовать параметр, мешавший удобному совместному редактированию.</span><span class="sxs-lookup"><span data-stu-id="1d334-522">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="1d334-523">Это исправление обеспечивает очистку этого параметра для данного случая.</span><span class="sxs-lookup"><span data-stu-id="1d334-523">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="1d334-524">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-524">Word</span></span>

- <span data-ttu-id="1d334-525">Исправлена проблема, из-за которой при открытии документов с разрывами страниц и столбцами могло появляться сообщение об ошибке "Превышено число страниц, максимально допустимое для приложения Microsoft Word или данный документ поврежден"</span><span class="sxs-lookup"><span data-stu-id="1d334-525">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="1d334-526">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="1d334-526">Office Suite</span></span>

- <span data-ttu-id="1d334-527">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="1d334-527">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="1d334-528">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="1d334-528">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-october-13"></a><span data-ttu-id="1d334-530">Версия 1908: 13 октября</span><span class="sxs-lookup"><span data-stu-id="1d334-530">Version 1908: October 13</span></span>
<span data-ttu-id="1d334-531">*Версия 1908 (сборка 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="1d334-531">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="1d334-532">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-534">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1d334-535">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-535">Office Suite</span></span>

- <span data-ttu-id="1d334-536">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="1d334-536">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="1d334-537">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="1d334-537">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-september-08"></a><span data-ttu-id="1d334-539">Версия 2002: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="1d334-539">Version 2002: September 08</span></span>
<span data-ttu-id="1d334-540">*Версия 2002 (сборка 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="1d334-540">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="1d334-541">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-541">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-543">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-543">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-544">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-544">Excel</span></span>

- <span data-ttu-id="1d334-545">Это устраняет проблему, из-за которой при подключениях, созданных поставщиком данных SQL в более ранних версиях Office, параметры внутренних таблиц задавались не так, как в Office 365.</span><span class="sxs-lookup"><span data-stu-id="1d334-545">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="1d334-546">Это приводит к отключению раскрывающегося списка "Просмотр таблиц" или "Редактор запросов" для файлов с подключениями, созданными в более ранних версиях Office, когда они открывались с помощью Office 365.</span><span class="sxs-lookup"><span data-stu-id="1d334-546">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="1d334-547">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="1d334-547">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="1d334-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-548">Outlook</span></span>

- <span data-ttu-id="1d334-549">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="1d334-549">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1d334-550">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-550">Office Suite</span></span>

- <span data-ttu-id="1d334-551">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="1d334-551">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-september-08"></a><span data-ttu-id="1d334-553">Версия 1908: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="1d334-553">Version 1908: September 08</span></span>
<span data-ttu-id="1d334-554">*Версия 1908 (сборка 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="1d334-554">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="1d334-555">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-555">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="1d334-556">Версия 2002: 11 августа</span><span class="sxs-lookup"><span data-stu-id="1d334-556">Version 2002: August 11</span></span>
<span data-ttu-id="1d334-557">*Версия 2002 (сборка 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="1d334-557">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="1d334-558">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-558">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-560">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-560">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-561">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-561">Excel</span></span>

- <span data-ttu-id="1d334-562">Исправлена проблема, не позволявшая переключиться на редактирование файлов, открытых с использованием параметра "Рекомендовать доступ только для чтения".</span><span class="sxs-lookup"><span data-stu-id="1d334-562">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="1d334-563">OneNote</span><span class="sxs-lookup"><span data-stu-id="1d334-563">OneNote</span></span>

- <span data-ttu-id="1d334-564">Удалены лишние вызовы удостоверений, чтобы сократить использование ресурсов</span><span class="sxs-lookup"><span data-stu-id="1d334-564">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="1d334-565">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="1d334-565">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="1d334-566">Улучшена функция обнаружения ошибок и качество синхронизации.</span><span class="sxs-lookup"><span data-stu-id="1d334-566">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-567">Outlook</span></span>

- <span data-ttu-id="1d334-568">Исправлена ошибка, вызывавшая серьезную проблему с производительностью при запуске Outlook для некоторых клиентов.</span><span class="sxs-lookup"><span data-stu-id="1d334-568">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="1d334-569">Skype</span><span class="sxs-lookup"><span data-stu-id="1d334-569">Skype</span></span>

- <span data-ttu-id="1d334-570">Исправлена проблема, из-за которой запуск демонстрации экрана мог завершиться сбоем в 32-разрядном клиенте Skype для бизнеса после его работы в течение нескольких дней.</span><span class="sxs-lookup"><span data-stu-id="1d334-570">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-571">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-571">Office Suite</span></span>

- <span data-ttu-id="1d334-572">Исправлена проблема, из-за которой в случае отключения автосохранения с помощью групповой политики некоторые документы могли не отображать последнее содержимое сервера при открытии, пока пользователь не нажмет кнопку "Доступны обновления".</span><span class="sxs-lookup"><span data-stu-id="1d334-572">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-august-11"></a><span data-ttu-id="1d334-574">Версия 1908: 11 августа</span><span class="sxs-lookup"><span data-stu-id="1d334-574">Version 1908: August 11</span></span>
<span data-ttu-id="1d334-575">*Версия 1908 (сборка 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="1d334-575">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="1d334-576">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-576">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="1d334-577">Версия 1902: 11 августа</span><span class="sxs-lookup"><span data-stu-id="1d334-577">Version 1902: August 11</span></span>
<span data-ttu-id="1d334-578">*Версия 1902 (сборка 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="1d334-578">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="1d334-579">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-july-14"></a><span data-ttu-id="1d334-582">Версия 2002: 14 июля</span><span class="sxs-lookup"><span data-stu-id="1d334-582">Version 2002: July 14</span></span>
<span data-ttu-id="1d334-583">*Версия 2002 (сборка 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="1d334-583">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="1d334-584">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-584">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="1d334-586">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="1d334-586">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="1d334-587">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-587">Access</span></span>

- <span data-ttu-id="1d334-588">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="1d334-588">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="1d334-589">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-589">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="1d334-590">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-590">Excel</span></span>

- <span data-ttu-id="1d334-591">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="1d334-591">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="1d334-592">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-592">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="1d334-593">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-593">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="1d334-594">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="1d334-594">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="1d334-595">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-595">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="1d334-596">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="1d334-596">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="1d334-597">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="1d334-597">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="1d334-598">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="1d334-598">Find them at Insert > Icons.</span></span> [<span data-ttu-id="1d334-599">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-599">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="1d334-600">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="1d334-600">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="1d334-601">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="1d334-601">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="1d334-602">**Сосредоточьтесь на оставшихся задачах.** Пометьте примечания как разрешенные, чтобы свернуть их и сделать открытые элементы более заметными.</span><span class="sxs-lookup"><span data-stu-id="1d334-602">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="1d334-603">**Ввод формулы, возвращающей несколько значений.** Теперь вы можете быстро ввести формулу, возвращающую несколько значений, которые автоматически переносятся в смежные ячейки.</span><span class="sxs-lookup"><span data-stu-id="1d334-603">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="1d334-604">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-604">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="1d334-605">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="1d334-605">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="1d334-606">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="1d334-606">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="1d334-607">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей книге.</span><span class="sxs-lookup"><span data-stu-id="1d334-607">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="1d334-608">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-608">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="1d334-609">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="1d334-609">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="1d334-610">**Найдите то, что ищете:** Ищите команды, людей, файлы, фотографии, веб-статьи и многое другое.</span><span class="sxs-lookup"><span data-stu-id="1d334-610">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="1d334-611">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-611">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="1d334-612">**Шесть эффективных функций.** Добавлено шесть новых функций для улучшения электронных таблиц: ФИЛЬТР, СОРТ, СОРТПО, УНИК, ПОСЛЕДОВ и СЛУЧМАССИВ.</span><span class="sxs-lookup"><span data-stu-id="1d334-612">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="1d334-613">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-613">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="1d334-614">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="1d334-614">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="1d334-615">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-615">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="1d334-616">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="1d334-616">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="1d334-617">**Удобная работа с большими книгами.** Статистика книги предоставляет сведения о ячейках, формулах, диаграммах, таблицах и других элементах.</span><span class="sxs-lookup"><span data-stu-id="1d334-617">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="1d334-618">**Читайте и отвечайте на ходу.** Отвечайте на комментарии и упоминания непосредственно в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="1d334-618">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="1d334-619">**Привлечение внимания с помощью \@@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="1d334-619">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="1d334-620">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-620">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="1d334-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-621">Outlook</span></span>

- <span data-ttu-id="1d334-622">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="1d334-622">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="1d334-623">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-623">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="1d334-624">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="1d334-624">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="1d334-625">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="1d334-625">Find them at Insert > Icons.</span></span> [<span data-ttu-id="1d334-626">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-626">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="1d334-627">**Рисование.** Рисуйте поверх изображений или добавьте полотно, чтобы отправить свои идеи с помощью рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="1d334-627">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="1d334-628">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-628">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="1d334-629">**Получение предложений по расположению.** Начните вводить текст в поле "Место" при планировании встреч и собраний, и Outlook предложит помещения, адреса и другие недавние места.</span><span class="sxs-lookup"><span data-stu-id="1d334-629">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="1d334-630">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-630">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="1d334-631">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="1d334-631">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="1d334-632">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="1d334-632">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="1d334-633">**Меню "Вставка ссылки" в Outlook вставляет ссылку с разрешениями, определенными администратором клиента.** При выборе из списка последних использованных ссылок в Outlook вставляется ссылка, которая была доступна только пользователям, имеющим разрешение на доступ к ней.</span><span class="sxs-lookup"><span data-stu-id="1d334-633">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="1d334-634">Из-за этого пользователи часто посылали друг другу письма с просьбой предоставить доступ к документу.</span><span class="sxs-lookup"><span data-stu-id="1d334-634">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="1d334-635">Мы обновили этот опыт, поэтому теперь ссылка вставляется с разрешением по умолчанию, установленным администратором клиента. Для MSIT это «организация может редактировать», поэтому все внутренние пользователи, получившие ссылку, которой поделились таким образом, смогут получить к ней доступ.</span><span class="sxs-lookup"><span data-stu-id="1d334-635">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="1d334-636">**Просмотр сообщений в другой освещенности.** Используйте кнопку "СОЛНЦЕ/ЛУНА" для переключения между светлым и темным фоном в области чтения.</span><span class="sxs-lookup"><span data-stu-id="1d334-636">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="1d334-637">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-637">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="1d334-638">**Фишинговые письма легко обнаружить:** спам и фишинговые сообщения выглядят по-разному, поэтому вы можете легко их идентифицировать и удалить из папки «Входящие».</span><span class="sxs-lookup"><span data-stu-id="1d334-638">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="1d334-p159">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты. [Подробнее](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="1d334-p159">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="1d334-641">**Поиск с правописанием проблем или опечаток.** Outlook найдет то, что вы ищете, даже если запрос написан с ошибками.</span><span class="sxs-lookup"><span data-stu-id="1d334-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="1d334-642">**Подключение к сети LinkedIn с помощью Outlook.** Безопасное подключение к учетным записям LinkedIn с помощью учетных записей Майкрософт для просмотра сведений из профилей LinkedIn прямо на карточках контактов.</span><span class="sxs-lookup"><span data-stu-id="1d334-642">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="1d334-643">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-643">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="1d334-644">**Получайте релевантные сообщения в результатах поиска.** Outlook анализирует условия поиска и отображает наиболее релевантные сообщения электронной почты в верхней части результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="1d334-644">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="1d334-645">Кроме того, все результаты будут отображаться в разделе "Лучшие результаты" с сортировкой по дате.</span><span class="sxs-lookup"><span data-stu-id="1d334-645">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="1d334-646">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-646">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="1d334-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-647">PowerPoint</span></span>

- <span data-ttu-id="1d334-p162">**Вы вычисляете, мы форматируем.** Рукописные математические выражения преобразуются в стандартные знаки. Просто воспользуйтесь функцией "Рукописный фрагмент в математические символы" и выберите рукописные примечания для начала работы. [Подробнее](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="1d334-p162">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="1d334-651">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="1d334-651">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="1d334-652">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-652">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="1d334-653">**Рукописный ввод для создания отличного слайда.** Преобразуйте рукописный ввод в стандартные фигуры и текст, а затем находите изящные идеи оформления слайдов в конструкторе PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-653">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="1d334-654">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-654">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="1d334-655">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей презентации.</span><span class="sxs-lookup"><span data-stu-id="1d334-655">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="1d334-656">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-656">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="1d334-657">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="1d334-657">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="1d334-658">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="1d334-658">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="1d334-659">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-659">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="1d334-660">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="1d334-660">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="1d334-661">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="1d334-661">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="1d334-662">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="1d334-662">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="1d334-663">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-663">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="1d334-664">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="1d334-664">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="1d334-665">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="1d334-665">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="1d334-666">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-666">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="1d334-667">**Поиск и исправление пропущенных названий слайдов:** Названия слайдов добавляют удар к вашей подаче и делают ваши слайды доступными для пользователей всех способностей.</span><span class="sxs-lookup"><span data-stu-id="1d334-667">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="1d334-668">С помощью средства проверки читаемости можно определить, где отсутствуют заголовки, и сразу же добавить их.</span><span class="sxs-lookup"><span data-stu-id="1d334-668">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="1d334-669">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-669">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="1d334-670">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="1d334-670">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="1d334-671">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="1d334-671">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="1d334-672">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="1d334-672">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="1d334-673">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="1d334-673">Find them at Insert > Icons.</span></span> [<span data-ttu-id="1d334-674">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-674">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="1d334-675">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="1d334-675">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="1d334-676">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="1d334-676">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="1d334-677">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами непосредственно из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="1d334-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="1d334-678">**Быстрое взаимодействие в реальном времени в PowerPoint.** Быстрое сотрудничество в реальном времени в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-678">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="1d334-679">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="1d334-679">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="1d334-680">**Новые средства проверки правописания.** Не переживайте из-за слов.</span><span class="sxs-lookup"><span data-stu-id="1d334-680">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="1d334-681">В PowerPoint теперь отображаются предложения в отношении грамматики и написания.</span><span class="sxs-lookup"><span data-stu-id="1d334-681">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="1d334-682">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-682">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="1d334-683">**Субтитры в реальном времени.** Слова докладчика автоматически отображаются на экране в виде субтитров или переводятся в субтитры на выбранном языке.</span><span class="sxs-lookup"><span data-stu-id="1d334-683">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="1d334-684">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-684">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="1d334-685">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="1d334-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="1d334-686">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="1d334-686">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="1d334-687">**Зачем изобретать заново то, что можно использовать повторно?** Экономьте время, повторно используя слайды, которые вы создали или которыми другие поделились с вами.</span><span class="sxs-lookup"><span data-stu-id="1d334-687">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="1d334-688">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-688">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="1d334-689">Visio</span><span class="sxs-lookup"><span data-stu-id="1d334-689">Visio</span></span>

- <span data-ttu-id="1d334-690">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="1d334-690">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="1d334-691">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="1d334-692">**В сценах преступления:** Используйте новые трафареты «Доказательства», «В помещении» и «На улице» в шаблоне «Расследование места преступления», чтобы детально воссоздать места преступления.</span><span class="sxs-lookup"><span data-stu-id="1d334-692">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-693">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-693">Word</span></span>

- <span data-ttu-id="1d334-694">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="1d334-694">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="1d334-695">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-695">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="1d334-696">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="1d334-696">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="1d334-697">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-697">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="1d334-698">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="1d334-698">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="1d334-699">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами непосредственно из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="1d334-699">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="1d334-700">**Больше иконок в соответствии с вашим настроением:** мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="1d334-700">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="1d334-701">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="1d334-701">Find them at Insert > Icons.</span></span> [<span data-ttu-id="1d334-702">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-702">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="1d334-703">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="1d334-703">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="1d334-704">**Точное стирание.** Выберите один из двух размеров ластика, чтобы исправить небольшие недочеты рукописных фрагментов.</span><span class="sxs-lookup"><span data-stu-id="1d334-704">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="1d334-705">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-705">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="1d334-706">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="1d334-706">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="1d334-707">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="1d334-707">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="1d334-708">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своем документе.</span><span class="sxs-lookup"><span data-stu-id="1d334-708">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="1d334-709">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-709">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="1d334-710">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="1d334-710">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="1d334-711">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="1d334-711">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="1d334-712">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-712">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="1d334-713">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="1d334-713">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="1d334-714">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-714">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="1d334-715">**Редактор для резюме присоединяется к LinkedIn Resume Assistant:** редактор для резюме предлагает выбор грамматических и стилевых проверок, специально предназначенных для резюме, чтобы сделать ваше письмо более точным и профессиональным.</span><span class="sxs-lookup"><span data-stu-id="1d334-715">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="1d334-716">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="1d334-716">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="1d334-717">**Исправление проблемы с повреждением документа при объединении 3D объектов.** Исправлена проблема с повреждением документа, возникавшая при объединении 3D объектов.</span><span class="sxs-lookup"><span data-stu-id="1d334-717">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="1d334-718">**Улучшенные возможности совместного редактирования**. Улучшено быстродействие Word при совместном редактировании в документах с отслеживанием исправлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-718">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="1d334-719">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="1d334-719">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="1d334-720">**Сотрудничайте в живом цвете:** комментарии и изменения имеют цветовую кодировку от участника, поэтому легко увидеть, кто есть кто среди ваших соавторов.</span><span class="sxs-lookup"><span data-stu-id="1d334-720">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="1d334-721">**Совместное редактирование документов с поддержкой макросов:** сохраняйте файлы документов в OneDrive для бизнеса и редактируйте их вместе с соавторами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="1d334-721">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-722">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-722">Office Suite</span></span>

- <span data-ttu-id="1d334-723">**Измените рукописные чернила на фигуры, текст или математику в PowerPoint для Office 365:** Перейдите от чернил произвольной формы к фигурам, тексту или математическому выражению Office за пару движений.</span><span class="sxs-lookup"><span data-stu-id="1d334-723">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="1d334-724">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-724">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-727">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-727">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1d334-728">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-728">Access</span></span>

- <span data-ttu-id="1d334-729">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="1d334-729">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="1d334-730">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="1d334-730">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="1d334-731">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="1d334-731">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="1d334-732">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="1d334-732">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="1d334-733">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="1d334-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="1d334-734">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="1d334-734">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="1d334-735">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-735">Excel</span></span>

- <span data-ttu-id="1d334-736">Ускорение загрузки файлов, доступных в локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-736">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="1d334-737">Устранена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неправильный результат.</span><span class="sxs-lookup"><span data-stu-id="1d334-737">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="1d334-738">Устранена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-738">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="1d334-739">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-739">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="1d334-740">Устранена проблема, из-за которой не отображались команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="1d334-740">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="1d334-741">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="1d334-741">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="1d334-742">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="1d334-742">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="1d334-743">Устранена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-743">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="1d334-744">В некоторых случаях при сохранении в виде CSV-файла Excel мог объединять все столбцы в один столбец.</span><span class="sxs-lookup"><span data-stu-id="1d334-744">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="1d334-745">Использование Range.ClearContents для диапазона в защищенном листе могло занимать больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-745">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="1d334-746">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-746">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="1d334-747">Макросы VBA, взаимодействующие с лентой, могут неожиданно запускаться со значением True, присвоенным параметру ScreenUpdating.</span><span class="sxs-lookup"><span data-stu-id="1d334-747">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="1d334-748">Устранена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="1d334-748">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="1d334-749">В некоторых случаях открытие CSV-файлов занимало больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-749">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="1d334-750">В ряде случаев приложение Excel аварийно завершало работу при переключении между книгами с разным масштабом.</span><span class="sxs-lookup"><span data-stu-id="1d334-750">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="1d334-751">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-751">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="1d334-752">Данные, скопированные из столбца и отфильтрованные по цвету, иногда не вставлялись должным образом.</span><span class="sxs-lookup"><span data-stu-id="1d334-752">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="1d334-753">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-753">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="1d334-754">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении (заполнение вниз, заполнение в стороны), если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="1d334-754">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="1d334-755">Устранена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="1d334-755">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="1d334-756">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-756">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="1d334-757">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-757">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="1d334-758">Устранена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="1d334-758">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="1d334-759">Повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="1d334-759">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="1d334-760">Устранена проблема, из-за которой имена принтеров могли повторяться в списке принтеров в диалоговом окне "Печать".</span><span class="sxs-lookup"><span data-stu-id="1d334-760">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="1d334-761">Устранена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="1d334-761">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="1d334-762">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-762">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="1d334-763">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="1d334-763">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="1d334-764">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-764">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="1d334-765">Устранена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="1d334-765">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="1d334-766">Устранена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, поэтому закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="1d334-766">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="1d334-767">Устранена проблема, из-за которой книга могла быть скрыта при щелчке гиперссылки на определенное место в уже открытой книге.</span><span class="sxs-lookup"><span data-stu-id="1d334-767">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="1d334-768">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-768">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="1d334-769">В некоторых случаях при использовании приложения VBA не работала оценка пользовательских функций.</span><span class="sxs-lookup"><span data-stu-id="1d334-769">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="1d334-770">Устранена проблема, которая могла возникнуть у некоторых пользователей со встроенными и связанными объектами (OLE).</span><span class="sxs-lookup"><span data-stu-id="1d334-770">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="1d334-771">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="1d334-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="1d334-772">Это обновление устраняет проблему, из-за которой на панели формул текст отображался со шрифтом, отличным от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="1d334-772">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="1d334-773">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="1d334-773">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="1d334-774">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="1d334-774">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="1d334-775">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="1d334-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="1d334-776">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-776">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="1d334-777">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="1d334-777">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="1d334-778">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="1d334-778">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="1d334-779">Устранена проблема, из-за которой у некоторых пользователей могли возникать ошибки при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="1d334-779">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="1d334-780">При использовании Range.Value и Range.Value2 (VBA) формулы вводились как динамические массивы.</span><span class="sxs-lookup"><span data-stu-id="1d334-780">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="1d334-781">Устранена проблема, из-за которой знак @ в начале формулы считался неявным оператором пересечения.</span><span class="sxs-lookup"><span data-stu-id="1d334-781">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="1d334-782">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="1d334-782">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="1d334-783">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="1d334-783">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="1d334-784">Устранена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="1d334-784">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="1d334-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="1d334-785">OneNote</span></span>

- <span data-ttu-id="1d334-786">Улучшены синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-786">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="1d334-787">Улучшены синхронизация и стабильность службы путем временного откладывания загрузки внедренных файлов и изображений в записных книжках в Интернете, пока пользователь не перейдет на страницу в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-787">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="1d334-788">Улучшены синхронизация и стабильность службы путем временного отключения корзины в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-788">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="1d334-789">Если пользователь пытается удалить данные, которые обычно отправляются в корзину, ему будет предложено сохранить или окончательно удалить их.</span><span class="sxs-lookup"><span data-stu-id="1d334-789">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="1d334-790">Улучшены синхронизация и стабильность службы путем временного уменьшения количества и частоты синхронизации страниц журнала версий в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-790">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="1d334-791">Отображает уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="1d334-791">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="1d334-792">Улучшены синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-792">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="1d334-793">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="1d334-793">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="1d334-794">Улучшены синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-794">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="1d334-795">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="1d334-795">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="1d334-796">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="1d334-796">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-797">Outlook</span></span>

- <span data-ttu-id="1d334-798">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="1d334-798">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="1d334-799">Устранена проблема, из-за которой Outlook иногда давал сбой.</span><span class="sxs-lookup"><span data-stu-id="1d334-799">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="1d334-800">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="1d334-800">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="1d334-801">Устранена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="1d334-801">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="1d334-802">Устранена проблема, при которой повторяющиеся встречи или собрания отображались с ошибкой во времени при приближении изменений в определении часового пояса.</span><span class="sxs-lookup"><span data-stu-id="1d334-802">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="1d334-803">При использовании часового пояса Бразилии в 2019 г. повторяющиеся собрания и встречи на 2020 г. отображаются в неправильном временном интервале.</span><span class="sxs-lookup"><span data-stu-id="1d334-803">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="1d334-804">Это изменение существенно для клиентов в часовом поясе Бразилии, а также для собраний и встреч в этом часовом поясе.</span><span class="sxs-lookup"><span data-stu-id="1d334-804">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="1d334-805">Это изменение дает приложению Outlook возможность переопределять некоторые параметры часового пояса, которые оно использует.</span><span class="sxs-lookup"><span data-stu-id="1d334-805">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="1d334-806">Чтобы вызвать переопределение часового пояса, необходимо задать раздел реестра для текущего пользователя.</span><span class="sxs-lookup"><span data-stu-id="1d334-806">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="1d334-807">Имя раздела реестра должно совпадать со внутренним именем часового пояса.</span><span class="sxs-lookup"><span data-stu-id="1d334-807">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="1d334-808">Это значение указывает год для правила часового пояса, который будет использоваться вместо текущего года.</span><span class="sxs-lookup"><span data-stu-id="1d334-808">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="1d334-809">Например, приведенное ниже значение для переопределения раздела реестра активирует правило бразильского часового пояса для 2020 года.</span><span class="sxs-lookup"><span data-stu-id="1d334-809">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="1d334-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"</span><span class="sxs-lookup"><span data-stu-id="1d334-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="1d334-811">Восточное Ю-Ам. время (зима)"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="1d334-811">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="1d334-812">Устранена проблема, из-за которой пользователи наблюдали неожиданное изменение поля расположения в собрании.</span><span class="sxs-lookup"><span data-stu-id="1d334-812">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="1d334-813">Устранена проблема, из-за которой неожиданно обновлялось поле расположения в собраниях.</span><span class="sxs-lookup"><span data-stu-id="1d334-813">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="1d334-814">Устранена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="1d334-814">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="1d334-815">Устранена проблема, из-за которой запятые в поле места проведения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="1d334-815">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="1d334-816">Позволяет присоединиться к собранию в Teams непосредственно через собственный клиент Teams.</span><span class="sxs-lookup"><span data-stu-id="1d334-816">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="1d334-817">Устранена проблема, из-за которой у пользователей с почтовыми ящиками на серверах Exchange 2010 возникали проблемы при добавлении вложений в элементы календаря.</span><span class="sxs-lookup"><span data-stu-id="1d334-817">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="1d334-818">Устранена проблема, из-за которой у пользователей возникали проблемы при ответе на сообщения с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="1d334-818">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="1d334-819">Устранена проблема, из-за которой пользователи не могли открывать некоторые вхождения повторяющихся элементов календаря.</span><span class="sxs-lookup"><span data-stu-id="1d334-819">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="1d334-820">Устранена проблема, приводившая к неожиданному увеличению заголовка группы в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="1d334-820">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="1d334-821">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="1d334-821">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="1d334-822">Устранена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="1d334-822">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="1d334-823">Устранена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="1d334-823">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="1d334-824">Устранена проблема, которая могла приводить к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="1d334-824">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="1d334-825">Устранена проблема, из-за которой при обновлении этих правил в Outlook появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="1d334-825">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="1d334-826">Устранена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-826">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="1d334-827">Устранена проблема, из-за которой у пользователей возникал сбой при указании неправильного адреса "От".</span><span class="sxs-lookup"><span data-stu-id="1d334-827">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="1d334-828">Устранена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="1d334-828">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="1d334-829">Устранена проблема, из-за которой параметр отключения выделения помеченных элементов не учитывался в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="1d334-829">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="1d334-830">Устранена проблема, из-за которой сообщения неожиданно отправлялись при нажатии клавиши S после закрытия панели проверки читаемости.</span><span class="sxs-lookup"><span data-stu-id="1d334-830">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="1d334-831">Устранена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="1d334-831">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="1d334-832">Устранена проблема, которая приводила к сбою пользователей при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="1d334-832">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="1d334-833">Устранена проблема, из-за которой приложение Outlook неожиданно синхронизировало всю почту, даже если ползунок синхронизации настроен на меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="1d334-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="1d334-834">Устранена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке "От" отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="1d334-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="1d334-835">Устранена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="1d334-835">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="1d334-836">Устранена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="1d334-836">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="1d334-837">Устранена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="1d334-837">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="1d334-838">Исправлена проблема, из-за которой сторонние приложения не могли отправлять электронные сообщения.</span><span class="sxs-lookup"><span data-stu-id="1d334-838">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="1d334-839">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="1d334-839">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="1d334-840">Устранена проблема, из-за которой у пользователей Outlook, использующих серверные операционные системы, возникала ошибка "Состояние антивирусной защиты: не действует</span><span class="sxs-lookup"><span data-stu-id="1d334-840">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="1d334-841">Данная версия Windows поддерживает обнаружение антивирусных программ, но ни одной программы не найдено", несмотря на то что антивирусная программа настроена правильно.</span><span class="sxs-lookup"><span data-stu-id="1d334-841">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="1d334-842">Устранена проблема, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="1d334-842">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="1d334-843">Устранена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="1d334-843">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="1d334-844">Устранена проблема, из-за которой пользователи, у которых неправильно задан параметр эмуляции браузера, не могли завершить запрос на проверку подлинности Gmail.</span><span class="sxs-lookup"><span data-stu-id="1d334-844">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="1d334-845">Устранена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="1d334-845">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="1d334-846">Устранена проблема, приводившая в сбою при попытке открытия файлов MSG и OFT после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-846">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="1d334-847">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки X на мыши.</span><span class="sxs-lookup"><span data-stu-id="1d334-847">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="1d334-848">Устранена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="1d334-848">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="1d334-849">Устранена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="1d334-849">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="1d334-850">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="1d334-850">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="1d334-851">Устранена проблема, вызывавшая сбой после того, как две надстройки добавляли кнопку в одну и ту же группу ленты.</span><span class="sxs-lookup"><span data-stu-id="1d334-851">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="1d334-852">Устранена проблема, из-за которой не удавалось добавить ссылки в сообщения электронной почты с правильным клиентским разрешением по умолчанию, если для этого разрешения был установлен параметр "Все".</span><span class="sxs-lookup"><span data-stu-id="1d334-852">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="1d334-853">Устранена проблема, из-за которой пользователи не могли отправлять электронные сообщения по адресам из личного списка рассылки.</span><span class="sxs-lookup"><span data-stu-id="1d334-853">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="1d334-854">Устранена проблема, из-за которой текст сообщения усекался при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="1d334-854">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="1d334-855">Устранена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="1d334-855">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="1d334-856">Устранена проблема, из-за которой не удавалось сохранять файлы в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="1d334-856">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="1d334-857">Устранена проблема, из-за которой пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="1d334-857">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="1d334-858">Устранена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="1d334-858">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="1d334-859">Устранена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-859">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="1d334-860">Исправлена проблема, из-за которой пользователи иногда наблюдали отправку сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="1d334-860">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="1d334-861">Устранена проблема, которая приводила к неправильному выравниванию поля поиска в режиме высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="1d334-861">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="1d334-862">Устранена проблема, приводившая к зависанию Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="1d334-862">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="1d334-863">Устранена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="1d334-863">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="1d334-864">Устранена проблема, из-за которой Outlook иногда давал сбой.</span><span class="sxs-lookup"><span data-stu-id="1d334-864">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="1d334-865">Устранена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="1d334-865">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="1d334-866">Устранена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="1d334-866">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="1d334-867">Устранена проблема, из-за которой Outlook иногда давал сбой.</span><span class="sxs-lookup"><span data-stu-id="1d334-867">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1d334-868">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-868">PowerPoint</span></span>

- <span data-ttu-id="1d334-869">Устранена проблема, которая могла вызвать сбой при использовании контекстного меню в устаревших комментариях PPT.</span><span class="sxs-lookup"><span data-stu-id="1d334-869">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="1d334-870">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="1d334-870">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="1d334-871">Устранена проблема с ретрансляцией точного текста сообщений для пользователей, которые открывают копию файла с улучшенными примечаниями.</span><span class="sxs-lookup"><span data-stu-id="1d334-871">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="1d334-872">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-872">Project</span></span>

- <span data-ttu-id="1d334-873">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="1d334-873">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="1d334-874">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="1d334-874">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="1d334-875">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, была ли задача деактивирована или активирована с помощью кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="1d334-875">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="1d334-876">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="1d334-876">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="1d334-877">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения</span><span class="sxs-lookup"><span data-stu-id="1d334-877">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="1d334-878">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="1d334-878">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-879">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-879">Word</span></span>

- <span data-ttu-id="1d334-880">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки X на мыши.</span><span class="sxs-lookup"><span data-stu-id="1d334-880">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="1d334-881">Устранена проблема, из-за которой выравнивание слова в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="1d334-881">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="1d334-882">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="1d334-882">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="1d334-883">Исправлена проблема, из-за которой вставляемые горизонтальные линии не укорачиваются и не располагаются по центру.</span><span class="sxs-lookup"><span data-stu-id="1d334-883">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="1d334-884">Диспетчер стандартных блоков может отображать неправильное оповещение: "Были изменены стили, стандартные блоки".</span><span class="sxs-lookup"><span data-stu-id="1d334-884">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="1d334-885">Устранена проблема с совместной работой над документом при включении политики FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="1d334-885">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="1d334-886">Устранена проблема, при которой функция экспресс-блоков Word не работала при добавлении переименованного поля подстановки.</span><span class="sxs-lookup"><span data-stu-id="1d334-886">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="1d334-887">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="1d334-887">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="1d334-888">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="1d334-888">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="1d334-889">Это обновление устраняет проблему в Microsoft Word, из-за которой текст длиной более 255 символов, вставленный при применении метки конфиденциальности, впоследствии не удавалось идентифицировать и удалить путем изменения или удаления метки, если в рамках политики меток был применен колонтитул или подложка.</span><span class="sxs-lookup"><span data-stu-id="1d334-889">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-890">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-890">Office Suite</span></span>

- <span data-ttu-id="1d334-891">Устранена проблема, из-за которой при совместной работе над объемными файлами PowerPoint чрезмерно повышалась нагрузка на сеть и ЦП.</span><span class="sxs-lookup"><span data-stu-id="1d334-891">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="1d334-892">Это исправление устраняет блокирование сети приложением Project при кэшировании файла в клиенте.</span><span class="sxs-lookup"><span data-stu-id="1d334-892">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="1d334-893">Эта проблема устранена с помощью замены имен каналов в представлении Backstage на новые в ответвлении за январь 2020 г.</span><span class="sxs-lookup"><span data-stu-id="1d334-893">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="1d334-894">Устранена проблема, из-за которой устройства, регулируемые политикой не могли вызвать API аудитории DMS.</span><span class="sxs-lookup"><span data-stu-id="1d334-894">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="1d334-895">Устранена проблема, из-за которой при добавлении и удалении приложений в одной транзакции выполнялось неполное удаление.</span><span class="sxs-lookup"><span data-stu-id="1d334-895">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="1d334-896">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-896">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="1d334-897">Решена проблема, из-за которой обновления Office могли неожиданно скачивать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="1d334-897">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="1d334-898">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-898">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="1d334-899">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="1d334-899">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="1d334-900">Решена проблема, из-за которой внутренняя операция вызывала исключение при сбое вместо ведения журнала и продолжения работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-900">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="1d334-901">Для затронутых пользователей будет отменен запрет на получение обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-901">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="1d334-902">Наша команда добавила в клиент поддержку отчетов телеметрии на доменах CDN Office на Полугодовом канале (предварительная корпоративная версия).</span><span class="sxs-lookup"><span data-stu-id="1d334-902">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="1d334-903">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="1d334-903">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="1d334-904">Это изменение обеспечит правильную работу функции "Контур эскиза" на ленте.</span><span class="sxs-lookup"><span data-stu-id="1d334-904">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="1d334-905">Исправлена проблема при открытии файлов из локальных расположений с определенными настройками прокси.</span><span class="sxs-lookup"><span data-stu-id="1d334-905">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="1d334-906">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="1d334-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="1d334-907">Исправлена проблема, благодаря чему устранены сбои во время сеансов передачи Office и повышена надежность работы пользователей.</span><span class="sxs-lookup"><span data-stu-id="1d334-907">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="1d334-908">Это исправление обновляет конечную точку URL-адреса конфигурации усиленной безопасности (ECS).</span><span class="sxs-lookup"><span data-stu-id="1d334-908">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="1d334-909">В результате вызова этой новой конечной точки повышается успешность получения данных из ECS.</span><span class="sxs-lookup"><span data-stu-id="1d334-909">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="1d334-910">Это обновление устраняет проблему, из-за которой в Microsoft Outlook не отображается текущая метка конфиденциальности при просмотре или создании сообщений.</span><span class="sxs-lookup"><span data-stu-id="1d334-910">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="1d334-911">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="1d334-911">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="1d334-912">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="1d334-912">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="1d334-913">Узел office завершал работу в Windows при активации надстройки, если раздел реестра  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="1d334-913">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="1d334-914">Это изменение исправит эту проблему.</span><span class="sxs-lookup"><span data-stu-id="1d334-914">This change would fix this issue.</span></span>

- <span data-ttu-id="1d334-915">Устранена проблема, из-за которой приложения Access и Publisher могли загружаться неправильно в зависимости от того, какие языки установлены.</span><span class="sxs-lookup"><span data-stu-id="1d334-915">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)





[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-july-14"></a><span data-ttu-id="1d334-918">Версия 1908: 14 июля</span><span class="sxs-lookup"><span data-stu-id="1d334-918">Version 1908: July 14</span></span>
<span data-ttu-id="1d334-919">*Версия 1908 (сборка 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="1d334-919">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="1d334-920">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-920">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-922">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1d334-923">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-923">Access</span></span>

- <span data-ttu-id="1d334-924">Это обновление исправляет проблему, из-за которой агрегатная функция, например, Sum, может обрезать результат до целого значения.</span><span class="sxs-lookup"><span data-stu-id="1d334-924">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="1d334-925">Это обновление исправляет проблему, из-за которой запрос на объединение, включающий ссылки на удаленные таблицы (например, таблицы SQL Server), может приводить к закрытию и перезапуску Access.</span><span class="sxs-lookup"><span data-stu-id="1d334-925">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="1d334-926">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="1d334-926">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="1d334-927">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-927">Excel</span></span>

- <span data-ttu-id="1d334-928">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="1d334-928">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="1d334-929">Устранена проблема в Excel, из-за которой при выполнении макросов, присвоенных фигурам или элементам управления формы, выводятся неправильные сообщения об ошибке или эти макросы работают в неправильном целевом диапазоне.</span><span class="sxs-lookup"><span data-stu-id="1d334-929">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="1d334-930">Решена проблема, при которой содержимое диалогового окна "Поиск и замена" изменялось, если курсор находился в нем после нахождения первого элемента.</span><span class="sxs-lookup"><span data-stu-id="1d334-930">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="1d334-931">Исправлена проблема, из-за которой изменение способа сортировки сводной таблицы и ее обновление в сеансе совместного редактирования с другими пользователями могло приводить к сбою.</span><span class="sxs-lookup"><span data-stu-id="1d334-931">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="1d334-932">Исправлена проблема, при которой для фильтра сводной таблицы OLAP было задано значение, удаленное из куба.</span><span class="sxs-lookup"><span data-stu-id="1d334-932">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="1d334-933">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="1d334-933">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="1d334-934">Устранена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов</span><span class="sxs-lookup"><span data-stu-id="1d334-934">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="1d334-935">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм.</span><span class="sxs-lookup"><span data-stu-id="1d334-935">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="1d334-936">Устранена проблема, приводившая к нарушению синхронизации каскадных и воронкообразных диаграмм с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="1d334-936">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="1d334-937">Исправлена проблема с конфликтом слияния в Excel, из-за которой пользователям предлагалось повторно открыть книгу, чтобы внести изменения.</span><span class="sxs-lookup"><span data-stu-id="1d334-937">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="1d334-938">Исправлена проблема, которая была причиной ошибки времени выполнения макроса при активации свернутых окон.</span><span class="sxs-lookup"><span data-stu-id="1d334-938">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="1d334-939">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-939">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="1d334-940">Устранена проблема, из-за которой вырезание и вставка в таблице не выполняются при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="1d334-940">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="1d334-941">Решена проблема, вызывавшая прерывание совместного редактирования при изменении настраиваемых свойств с помощью макросов.</span><span class="sxs-lookup"><span data-stu-id="1d334-941">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="1d334-942">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытом надстройкой.</span><span class="sxs-lookup"><span data-stu-id="1d334-942">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="1d334-943">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="1d334-943">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="1d334-944">Устранена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-944">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="1d334-945">Устранена проблема, из-за которой у некоторых пользователей появлялось несколько всплывающих окон при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="1d334-945">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="1d334-946">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="1d334-946">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="1d334-947">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-947">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="1d334-948">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-948">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="1d334-949">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-949">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="1d334-950">Исправлена проблема, приводившая к снижению производительности при удалении столбцов, содержащих объединенные ячейки.</span><span class="sxs-lookup"><span data-stu-id="1d334-950">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="1d334-951">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-951">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="1d334-952">При копировании данных, отфильтрованных по цвету, в столбец с другой шириной, значения не вставляются.</span><span class="sxs-lookup"><span data-stu-id="1d334-952">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="1d334-953">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="1d334-953">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="1d334-954">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-954">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="1d334-955">Устранена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-955">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="1d334-956">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="1d334-956">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="1d334-957">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="1d334-957">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="1d334-958">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="1d334-958">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="1d334-959">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="1d334-959">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="1d334-960">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="1d334-960">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="1d334-961">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="1d334-961">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="1d334-962">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="1d334-962">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="1d334-963">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="1d334-963">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="1d334-964">Исправлена проблема, из-за которой функция Lookup может возвращать ошибку.</span><span class="sxs-lookup"><span data-stu-id="1d334-964">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="1d334-965">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="1d334-965">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="1d334-966">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="1d334-966">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="1d334-967">Проблема низкой производительности при нажатии кнопки "Цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="1d334-967">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="1d334-968">Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-968">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="1d334-969">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-969">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="1d334-970">Значительно повышена производительность фильтрации по цвету.</span><span class="sxs-lookup"><span data-stu-id="1d334-970">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="1d334-971">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-971">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="1d334-972">Поддерживается отображение более 16 надстроек при просмотре в диспетчере надстроек.</span><span class="sxs-lookup"><span data-stu-id="1d334-972">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="1d334-973">Устранена проблема, которая препятствовала вставке гиперссылок в некоторых защищенных листах.</span><span class="sxs-lookup"><span data-stu-id="1d334-973">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="1d334-974">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="1d334-974">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="1d334-975">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-975">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-976">Это обновление устраняет ошибку, из-за которой документы Office могут не отправляться в OneDrive для бизнеса и приходит сообщение "Не удалось выполнить отправку".</span><span class="sxs-lookup"><span data-stu-id="1d334-976">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="1d334-977">Устранена проблема в функции "Идеи" для Excel, приводившая к ошибке при загрузке надстройки путем нажатия на кнопку "Идеи" в клиенте Win32.</span><span class="sxs-lookup"><span data-stu-id="1d334-977">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="1d334-978">OneNote</span><span class="sxs-lookup"><span data-stu-id="1d334-978">OneNote</span></span>

- <span data-ttu-id="1d334-979">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="1d334-979">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-980">Outlook</span></span>

- <span data-ttu-id="1d334-981">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-981">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-982">Исправлена проблема, из-за которой обновление в почтовых ящиках пользователей обычной проверки подлинности до современной приводило к привязыванию неправильной учетной записи к профилю Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-982">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="1d334-983">Устранена проблема, которая была причиной доступа веб-надстроек к сообщениям с управлением цифровыми правами, когда это не предполагалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-983">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="1d334-984">Устранена проблема, из-за которой URL-адреса не открывались при простом наведении на некоторые безопасные ссылки.</span><span class="sxs-lookup"><span data-stu-id="1d334-984">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="1d334-985">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="1d334-985">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="1d334-986">В этой статье описана проблема, из-за которой у подмножества пользователей POP3 сообщения электронной почты выводятся в виде обычного текста, независимо от настроек.</span><span class="sxs-lookup"><span data-stu-id="1d334-986">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="1d334-987">Это исправление восстановит сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="1d334-987">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="1d334-988">Устранена проблема, из-за которой возникала ошибка доступа при копировании элементов из основного календаря в календарь группы.</span><span class="sxs-lookup"><span data-stu-id="1d334-988">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="1d334-989">Устранена проблема, из-за которой пользователям были недоступны предложения расположений при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="1d334-989">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="1d334-990">Устранена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="1d334-990">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="1d334-991">Устранена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-991">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="1d334-992">Устранена проблема, из-за которой у пользователей возникал сбой при указании неправильного адреса "От".</span><span class="sxs-lookup"><span data-stu-id="1d334-992">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="1d334-993">Устранена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="1d334-993">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="1d334-994">Устранена проблема, которая приводила к сбою в Outlook при взаимодействии пользователей с определенными безопасными ссылками.</span><span class="sxs-lookup"><span data-stu-id="1d334-994">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="1d334-995">В этой статье описана проблема, из-за которой менеджеры не могли установить, ответил ли участник на приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="1d334-995">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="1d334-996">Устранена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="1d334-996">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="1d334-997">Устранена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="1d334-997">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="1d334-998">Это изменение позволяет администраторам включать политику, предпочитающую указанную учетную запись электронной почты в запросах проверки подлинности службы автообнаружения вместо имени участника-пользователя (UPN).</span><span class="sxs-lookup"><span data-stu-id="1d334-998">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="1d334-999">По умолчанию при автообнаружении предпочтение отдается UPN учетной записи (при наличии).</span><span class="sxs-lookup"><span data-stu-id="1d334-999">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="1d334-1000">Устранена проблема, вызывавшая сбой поиска в современных группах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1000">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="1d334-1001">Устранена проблема, приводившая к зависанию пользователей Outlook в состоянии "Требуется пароль" в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1001">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="1d334-1002">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1002">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="1d334-1003">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-1003">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="1d334-1004">Устранена проблема, из-за которой мог зависать экран загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1004">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="1d334-1005">Устранена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="1d334-1005">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="1d334-1006">Устранена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="1d334-1006">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="1d334-1007">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="1d334-1007">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="1d334-1008">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="1d334-1008">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="1d334-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = по умолчанию; 1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="1d334-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="1d334-1010">Устранена проблема, из-за которой пользователи сталкивались со сбоем при закрытии Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1010">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="1d334-1011">Устранена проблема, приводившая к отображению пустого списка помещений в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1011">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="1d334-1012">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1012">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="1d334-1013">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="1d334-1013">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="1d334-1014">Устранена проблема, приводившая к сбоям при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="1d334-1014">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="1d334-1015">Вот отдельная [статья базы знаний, где эта проблема задокументирована в описаниях предыдущих версий](https://support.microsoft.com/ru-RU/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen).</span><span class="sxs-lookup"><span data-stu-id="1d334-1015">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/ru-RU/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="1d334-1016">Устранена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="1d334-1016">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="1d334-1017">Устранена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="1d334-1017">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="1d334-1018">Устранена проблема, из-за которой пользователям предлагались помещения для собраний, проводимых в то время, когда эти помещения недоступны.</span><span class="sxs-lookup"><span data-stu-id="1d334-1018">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="1d334-1019">Устранена проблема для неанглоязычных пользователей, из-за которой строка темы в почте была очень маленькой.</span><span class="sxs-lookup"><span data-stu-id="1d334-1019">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="1d334-1020">Устранена проблема, приводившая к сбою при попытке создать правило на основе сообщения о пропущенной беседе.</span><span class="sxs-lookup"><span data-stu-id="1d334-1020">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="1d334-1021">Устранена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="1d334-1021">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="1d334-1022">Устранена проблема, из-за которой текст сообщения усекался при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="1d334-1022">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="1d334-1023">Устранена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1023">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="1d334-1024">Устранена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="1d334-1024">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="1d334-1025">Устранена проблема, которая приводила к периодическому сбою поиска в текущей папке.</span><span class="sxs-lookup"><span data-stu-id="1d334-1025">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="1d334-1026">Устранена проблема, из-за которой некоторые пользователи сталкивались с ошибками проверки подлинности при попытке получить свои облачные параметры для Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1026">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="1d334-1027">Устранена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="1d334-1027">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="1d334-1028">Устранена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1028">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="1d334-1029">Устранена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="1d334-1029">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1d334-1030">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1030">PowerPoint</span></span>

- <span data-ttu-id="1d334-1031">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-1031">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-1032">Это изменение восстанавливает доступное имя для элементов управления видео в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1032">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="1d334-1033">Устранена проблема, из-за которой не запускались некоторые эффекты анимации</span><span class="sxs-lookup"><span data-stu-id="1d334-1033">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="1d334-1034">Устранена проблема, из-за которой при копировании слайда из одной презентации в другую могли появляться дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="1d334-1034">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="1d334-1035">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="1d334-1035">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="1d334-1036">Устранена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="1d334-1036">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="1d334-1037">При открытии файлы с новыми современными примечаниями в неподдерживаемой версии отображается желтое предупреждение.</span><span class="sxs-lookup"><span data-stu-id="1d334-1037">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="1d334-1038">Устранена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1038">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="1d334-1039">Исправление проблем с надежностью. Устранена проблема, из-за которой надстройка стороннего поставщика могла вызывать сбой PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1039">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="1d334-1040">Устранена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="1d334-1040">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="1d334-1041">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="1d334-1041">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="1d334-1042">Мы устранили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1042">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="1d334-1043">Устранена проблема, из-за которой некоторые надстройки создавали непредвиденные ошибки вокруг фигур в диаграммах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1043">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="1d334-1044">Это исправление помогает пользователям PowerPoint избежать ошибки при попытке онлайн-презентации.</span><span class="sxs-lookup"><span data-stu-id="1d334-1044">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="1d334-1045">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-1045">Project</span></span>

- <span data-ttu-id="1d334-1046">Исправлена проблема, чтобы разрешить пользователям в Windows 7 открывать проекты из Project Web App и сайтов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1046">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="1d334-1047">Обнаружена проблема, из-за которой пользователи могли получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1047">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="1d334-1048">Команда "Выровнять все" не устраняет должным образом превышение доступности ресурсов.</span><span class="sxs-lookup"><span data-stu-id="1d334-1048">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="1d334-1049">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="1d334-1049">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="1d334-1050">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="1d334-1050">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="1d334-1051">Skype</span><span class="sxs-lookup"><span data-stu-id="1d334-1051">Skype</span></span>

- <span data-ttu-id="1d334-1052">Исправлено название вкладки беседы при наличии нескольких активных бесед.</span><span class="sxs-lookup"><span data-stu-id="1d334-1052">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="1d334-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="1d334-1053">Visio</span></span>

- <span data-ttu-id="1d334-1054">Экспорт в формате SVG из Visio не работал для различных фигур.</span><span class="sxs-lookup"><span data-stu-id="1d334-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-1055">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1055">Word</span></span>

- <span data-ttu-id="1d334-1056">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-1056">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-1057">Устранена проблема, которая могла приводить к ошибкам с масштабированием при печати на принтерах Deskjet</span><span class="sxs-lookup"><span data-stu-id="1d334-1057">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="1d334-1058">Устранена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="1d334-1058">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="1d334-1059">Устранена проблема с отслеживанием изменений, которые иногда переходят в режим бесконечного цикла. </span><span class="sxs-lookup"><span data-stu-id="1d334-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="1d334-1060">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="1d334-1060">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="1d334-1061">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="1d334-1061">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="1d334-1062">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="1d334-1062">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="1d334-1063">Устранены различные проблемы, из-за которых приложение могло зависнуть при завершении работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1063">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="1d334-1064">Также исправлены некоторые ошибки, связанные с надстройками.</span><span class="sxs-lookup"><span data-stu-id="1d334-1064">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-1065">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1065">Office Suite</span></span>

- <span data-ttu-id="1d334-1066">Исправлена проблема с неправильным определением названия новой эры "Рэйва" в хирагана и кандзи как выражения с опечаткой или грамматической ошибкой.</span><span class="sxs-lookup"><span data-stu-id="1d334-1066">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="1d334-1067">Исправлена проблема, из-за которой пользователи получали сообщение "Не удалось предоставить общий доступ" при попытке поделиться файлами, хранящимися в SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-1067">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="1d334-1068">Исправлена проблема, которая могла приводить к потере данных в сеансах, включающих как совместное редактирование, так и редактирование в автономном режиме в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1068">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="1d334-1069">Исправлена проблема, из-за которой мог произойти сбой при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-1069">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="1d334-1070">В некоторых случаях файл SharePoint, сохраненный с помощью модуля синхронизации, отображал состояние "Сохранено", но в действительности изменения не сохранялись. Это приводило к потере данных.</span><span class="sxs-lookup"><span data-stu-id="1d334-1070">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="1d334-1071">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1071">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="1d334-1072">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как диалоговое окно", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="1d334-1072">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="1d334-1073">Устранен сбой в Word благодаря отказу от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="1d334-1073">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="1d334-1074">Устранена проблема, из-за которой не удавалось правильно повернуть полуширинные знаки катаканы при использовании вертикальных текстовых полей в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1074">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="1d334-1075">Устранена проблема с быстродействием Win7, из-за которой вставленная коллекция фигур с ленты во всех приложениях отображалась примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="1d334-1075">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="1d334-1076">Исправлена ошибка, из-за которой сведения о специальных возможностях не отображались в области сведений представления Backstage.</span><span class="sxs-lookup"><span data-stu-id="1d334-1076">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="1d334-1077">Повышена надежность процесса обновления Office в отношении целостности реестра.</span><span class="sxs-lookup"><span data-stu-id="1d334-1077">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="1d334-1078">Имена каналов для разветвлений января и июля 2019 г. обновлены.</span><span class="sxs-lookup"><span data-stu-id="1d334-1078">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="1d334-1079">Устранена проблема, из-за которой обновления могли неожиданно блокироваться в сетях с лимитным тарифным планом.</span><span class="sxs-lookup"><span data-stu-id="1d334-1079">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="1d334-1080">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1080">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="1d334-1081">При определенных обстоятельствах ярлыки Office могут исчезнуть после обновления.</span><span class="sxs-lookup"><span data-stu-id="1d334-1081">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="1d334-1082">Это обновление повышает надежность при публикации ярлыков Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-1082">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="1d334-1083">Решена проблема, из-за которой обновления Office могли неожиданно скачивать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="1d334-1083">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="1d334-1084">Устранена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="1d334-1084">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="1d334-1085">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="1d334-1085">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="1d334-1086">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-1086">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="1d334-1087">Повышена надежность при скачивании обновлений Office путем продолжения скачивания, которое ранее могло прерываться.</span><span class="sxs-lookup"><span data-stu-id="1d334-1087">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="1d334-1088">Устранены проблемы, связанные со свойством автоподбора размера текстовых полей и фигур в сторонних подключаемых модулях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1088">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="1d334-1089">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-1089">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="1d334-1090">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="1d334-1090">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="1d334-1091">Устранена проблема, из-за которой представление в виде большого дерева могло привести к сбою</span><span class="sxs-lookup"><span data-stu-id="1d334-1091">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="1d334-1092">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="1d334-1092">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="1d334-1093">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="1d334-1093">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="1d334-1094">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="1d334-1094">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-july-14"></a><span data-ttu-id="1d334-1096">Версия 1902: 14 июля</span><span class="sxs-lookup"><span data-stu-id="1d334-1096">Version 1902: July 14</span></span>
<span data-ttu-id="1d334-1097">*Версия 1902 (сборка 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1097">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="1d334-1098">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1098">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="1d334-1099">Версия 1908: 09 июля</span><span class="sxs-lookup"><span data-stu-id="1d334-1099">Version 1908: June 09</span></span>
<span data-ttu-id="1d334-1100">*Версия 1908 (сборка 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1100">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="1d334-1101">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1101">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1103">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1103">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1104">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1104">Excel</span></span>

- <span data-ttu-id="1d334-1105">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="1d334-1105">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="1d334-1106">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-1106">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="1d334-1107">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="1d334-1107">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-1108">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1108">Outlook</span></span>

- <span data-ttu-id="1d334-1109">Устранена проблема, из-за которой пользователи видели текст сообщения неполностью при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="1d334-1109">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-1110">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1110">Office Suite</span></span>

- <span data-ttu-id="1d334-1111">Имена каналов для разветвлений января и июля 2019 г. обновлены.</span><span class="sxs-lookup"><span data-stu-id="1d334-1111">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-june-09"></a><span data-ttu-id="1d334-1113">Версия 1902: 09 июня</span><span class="sxs-lookup"><span data-stu-id="1d334-1113">Version 1902: June 09</span></span>
<span data-ttu-id="1d334-1114">*Версия 1902 (сборка 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1114">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="1d334-1115">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1117">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1117">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1d334-1118">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1118">Office Suite</span></span>

- <span data-ttu-id="1d334-1119">Имена каналов для разветвлений января и июля 2019 г. обновлены.</span><span class="sxs-lookup"><span data-stu-id="1d334-1119">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="1d334-1120">Устаревшие ссылки удалены из базовых файлов, которые разрушали сборку C2R.</span><span class="sxs-lookup"><span data-stu-id="1d334-1120">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-may-12"></a><span data-ttu-id="1d334-1122">Версия 1908: 12 мая</span><span class="sxs-lookup"><span data-stu-id="1d334-1122">Version 1908: May 12</span></span>
<span data-ttu-id="1d334-1123">*Версия 1908 (сборка 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1123">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="1d334-1124">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1124">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1126">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1126">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1127">Excel</span></span>

- <span data-ttu-id="1d334-1128">При копировании данных, отфильтрованных по цвету, в столбец с другой шириной, значения не вставляются.</span><span class="sxs-lookup"><span data-stu-id="1d334-1128">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1129">Outlook</span></span>

- <span data-ttu-id="1d334-1130">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-1130">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-1131">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1131">Word</span></span>

- <span data-ttu-id="1d334-1132">Исправлена проблема с объединением двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="1d334-1132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="1d334-1133">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="1d334-1133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-may-12"></a><span data-ttu-id="1d334-1135">Версия 1902: 12 мая</span><span class="sxs-lookup"><span data-stu-id="1d334-1135">Version 1902: May 12</span></span>
<span data-ttu-id="1d334-1136">*Версия 1902 (сборка 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="1d334-1137">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1139">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="1d334-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1140">Outlook</span></span>

- <span data-ttu-id="1d334-1141">Устранена проблема, приводившая в сбою при открытии файлов MSG и OFT после применения последнего обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-1141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="1d334-1142">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="1d334-1142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="1d334-1143">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="1d334-1143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="1d334-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="1d334-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="1d334-1145">0 = по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="1d334-1145">0 = Default.</span></span>  <span data-ttu-id="1d334-1146">1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="1d334-1146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-may-04"></a><span data-ttu-id="1d334-1148">Версия 1908: 04 мая</span><span class="sxs-lookup"><span data-stu-id="1d334-1148">Version 1908: May 04</span></span>
<span data-ttu-id="1d334-1149">*Версия 1908 (сборка 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1149">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="1d334-1150">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1151">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1151">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="1d334-1152">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1152">Outlook</span></span>

- <span data-ttu-id="1d334-1153">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="1d334-1153">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="1d334-1154">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="1d334-1154">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="1d334-1155">По умолчанию метки политики хранения отображают срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="1d334-1155">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="1d334-1156">Благодаря этому в разделе реестра администраторы могут указать, что должно отображаться только имя политики.</span><span class="sxs-lookup"><span data-stu-id="1d334-1156">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="1d334-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="1d334-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="1d334-1158">0 = по умолчанию 1 = для параметра "Текст политики хранения" будет отображаться только PolicyName.</span><span class="sxs-lookup"><span data-stu-id="1d334-1158">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-1159">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1159">Office Suite</span></span>

- <span data-ttu-id="1d334-1160">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="1d334-1160">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="1d334-1161">Версия 1902: 04 мая</span><span class="sxs-lookup"><span data-stu-id="1d334-1161">Version 1902: May 04</span></span>
<span data-ttu-id="1d334-1162">*Версия 1902 (сборка 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1162">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1163">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1163">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="1d334-1164">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1164">Office Suite</span></span>

- <span data-ttu-id="1d334-1165">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="1d334-1165">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="1d334-1166">Версия 1908: 26 апреля</span><span class="sxs-lookup"><span data-stu-id="1d334-1166">Version 1908: April 26</span></span>
<span data-ttu-id="1d334-1167">*Версия 1908 (сборка 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1167">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="1d334-1168">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1168">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1169">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1170">Excel</span></span>

- <span data-ttu-id="1d334-1171">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="1d334-1171">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="1d334-1172">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-1172">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="1d334-1173">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-1173">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="1d334-1174">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-1174">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="1d334-1175">OneNote</span><span class="sxs-lookup"><span data-stu-id="1d334-1175">OneNote</span></span>

- <span data-ttu-id="1d334-1176">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1176">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="1d334-1177">Версия 1908: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="1d334-1177">Version 1908: April 14</span></span>
<span data-ttu-id="1d334-1178">*Версия 1908 (сборка 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1178">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="1d334-1179">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1181">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1182">Excel</span></span>

- <span data-ttu-id="1d334-1183">Исправлена проблема, приводившая к снижению производительности при удалении столбцов, содержащих объединенные ячейки.</span><span class="sxs-lookup"><span data-stu-id="1d334-1183">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="1d334-1184">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-1184">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="1d334-1185">Skype</span><span class="sxs-lookup"><span data-stu-id="1d334-1185">Skype</span></span>

- <span data-ttu-id="1d334-1186">Исправлено название вкладки беседы при наличии нескольких активных бесед.</span><span class="sxs-lookup"><span data-stu-id="1d334-1186">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1187">Outlook</span></span>

- <span data-ttu-id="1d334-1188">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при закрытии Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1188">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="1d334-1189">Исправлена проблема, приводившая к отображению пустого списка помещений в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1189">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1d334-1190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1190">PowerPoint</span></span>

- <span data-ttu-id="1d334-1191">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="1d334-1191">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-1192">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1192">Word</span></span>

- <span data-ttu-id="1d334-1193">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="1d334-1193">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="1d334-1194">Версия 1902: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="1d334-1194">Version 1902: April 14</span></span>
<span data-ttu-id="1d334-1195">*Версия 1902 (сборка 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1195">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="1d334-1196">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-march-10"></a><span data-ttu-id="1d334-1198">Версия 1908: 10 марта</span><span class="sxs-lookup"><span data-stu-id="1d334-1198">Version 1908: March 10</span></span>
<span data-ttu-id="1d334-1199">*Версия 1908 (сборка 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1199">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="1d334-1200">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1202">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1203">Excel</span></span>

- <span data-ttu-id="1d334-1204">Исправлена проблема, из-за которой у некоторых пользователей появлялось несколько всплывающих окон при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="1d334-1204">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="1d334-1205">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1205">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="1d334-1206">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="1d334-1206">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1d334-1207">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1207">PowerPoint</span></span>

- <span data-ttu-id="1d334-1208">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="1d334-1208">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="1d334-1209">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1209">Word</span></span>

- <span data-ttu-id="1d334-1210">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="1d334-1210">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="1d334-1211">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1211">Office Suite</span></span>

- <span data-ttu-id="1d334-1212">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="1d334-1212">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="1d334-1213">Версия 1902: 10 марта</span><span class="sxs-lookup"><span data-stu-id="1d334-1213">Version 1902: March 10</span></span>
<span data-ttu-id="1d334-1214">*Версия 1902 (сборка 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1214">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="1d334-1215">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1215">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="1d334-1217">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="1d334-1217">Version 1908: February 11</span></span>
<span data-ttu-id="1d334-1218">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1218">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="1d334-1219">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1219">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1221">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1222">Excel</span></span>

- <span data-ttu-id="1d334-1223">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1223">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="1d334-1224">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-1224">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="1d334-1225">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="1d334-1225">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="1d334-1226">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="1d334-1226">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="1d334-1227">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="1d334-1227">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="1d334-1228">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="1d334-1228">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="1d334-1229">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1229">Outlook</span></span>

- <span data-ttu-id="1d334-1230">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="1d334-1230">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="1d334-1231">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1231">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="1d334-1232">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1232">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="1d334-1233">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1233">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="1d334-1234">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="1d334-1234">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="1d334-1235">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1235">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="1d334-1236">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="1d334-1236">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="1d334-1237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1237">PowerPoint</span></span>

- <span data-ttu-id="1d334-1238">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="1d334-1238">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="1d334-1239">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1239">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="1d334-1240">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="1d334-1240">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="1d334-1241">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1241">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="1d334-1242">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-1242">Project</span></span>

- <span data-ttu-id="1d334-1243">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="1d334-1243">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-1244">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1244">Word</span></span>

- <span data-ttu-id="1d334-1245">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="1d334-1245">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-1246">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1246">Office Suite</span></span>

- <span data-ttu-id="1d334-1247">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-1247">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-february-11"></a><span data-ttu-id="1d334-1249">Версия 1902: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="1d334-1249">Version 1902: February 11</span></span>
<span data-ttu-id="1d334-1250">*Версия 1902 (сборка 11328,20526)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1250">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="1d334-1251">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1251">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1253">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1253">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="1d334-1254">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1254">Outlook</span></span>

- <span data-ttu-id="1d334-1255">Решает проблему, из-за которой пользователи сталкивались с алгоритмом шифрования, не поддерживаются ошибки при отправке зашифрованных писем.</span><span class="sxs-lookup"><span data-stu-id="1d334-1255">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="1d334-1256">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1256">Word</span></span>

- <span data-ttu-id="1d334-1257">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="1d334-1257">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-1808-february-11"></a><span data-ttu-id="1d334-1260">Версия 1808: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="1d334-1260">Version 1808: February 11</span></span>
<span data-ttu-id="1d334-1261">*Версия 1808 (сборка 10730,20438)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1261">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="1d334-1262">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1262">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="1d334-1264">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="1d334-1264">Version 1908: January 14</span></span>
<span data-ttu-id="1d334-1265">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1265">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="1d334-1266">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1266">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="1d334-1268">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="1d334-1268">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="1d334-1269">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-1269">Access</span></span>

- <span data-ttu-id="1d334-1270">**Отслеживание объектов базы данных.** Не теряйте из виду активную вкладку, легко перетаскивайте вкладки для изменения их порядка и закрывайте объекты базы данных одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="1d334-1270">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="1d334-1271">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="1d334-1271">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1d334-1272">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="1d334-1272">Switching between them has never been easier.</span></span> [<span data-ttu-id="1d334-1273">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1273">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1d334-1274">**Изменение масштаба стало удобнее.** Увеличивайте поле масштаба и меняйте шрифт — все эти параметры сохранятся.</span><span class="sxs-lookup"><span data-stu-id="1d334-1274">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="1d334-1275">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1275">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="1d334-1276">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1276">Excel</span></span>

- <span data-ttu-id="1d334-1277">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="1d334-1277">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1d334-1278">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="1d334-1278">Switching between them has never been easier.</span></span> [<span data-ttu-id="1d334-1279">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1279">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1d334-1280">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="1d334-1280">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="1d334-1281">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="1d334-1281">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="1d334-1282">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="1d334-1282">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="1d334-1283">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="1d334-1283">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1d334-1284">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="1d334-1284">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="1d334-1285">**Добавление живых красок в таблицы.** Вставляйте в книгу анимированные трехмерные изображения, чтобы показать, как бьется сердце, вращается планета или рычит тираннозавр.</span><span class="sxs-lookup"><span data-stu-id="1d334-1285">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="1d334-1286">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1286">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="1d334-p211">**Узнайте больше о своих данных.** Новая кнопка "Идеи" позволяет находить закономерности в данных и предлагает интеллектуальные, индивидуальные решения на их основе. [Подробнее](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="1d334-p211">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="1d334-1289">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1289">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="1d334-1290">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="1d334-1290">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="1d334-1291">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1291">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="1d334-1292">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="1d334-1292">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="1d334-1293">Также можно легко находить функции, столбцы и параметры.</span><span class="sxs-lookup"><span data-stu-id="1d334-1293">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="1d334-1294">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="1d334-1294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1d334-1295">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="1d334-1295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1d334-1296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="1d334-1297">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1297">Outlook</span></span>

- <span data-ttu-id="1d334-1298">**Мы обновили интерфейс Outlook для вас.** Упрощенный интерфейс, ранее доступный для предпросмотра с помощью функции "Ожидается в ближайшее время", чтобы вы могли сосредоточиться на самом важном.</span><span class="sxs-lookup"><span data-stu-id="1d334-1298">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="1d334-1299">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1299">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="1d334-1300">**Упрощенная лента с возможностью настройки.** Наслаждайтесь одной упрощенной строкой, содержащей наиболее часто используемые кнопки.</span><span class="sxs-lookup"><span data-stu-id="1d334-1300">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="1d334-1301">Легко переключайтесь между классическим и упрощенным представлением, а также закрепляйте и открепляйте команды.</span><span class="sxs-lookup"><span data-stu-id="1d334-1301">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="1d334-1302">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1302">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="1d334-1303">**Продолжение работы при перемещении сообщений.** Outlook теперь перемещает сообщения в фоновом режиме, чтобы вы могли продолжать работу во время перемещения большого количества сообщений между папками.</span><span class="sxs-lookup"><span data-stu-id="1d334-1303">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="1d334-1304">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время окончания собрания на 5–10 минут раньше по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="1d334-1304">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="1d334-1305">**Выбор избранного действия.** Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="1d334-1305">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="1d334-1306">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="1d334-1306">How about Archive or Mark as Read?</span></span> <span data-ttu-id="1d334-1307">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="1d334-1307">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="1d334-p218">**Все смогут понять, что вы имели в виду.** Если текста или статических изображений недостаточно, воспользуйтесь файлами GIF с анимацией, чтобы донести свою идею. [Подробнее](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="1d334-p218">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="1d334-1310">**Быстрое добавление учетных записей.** Благодаря улучшениям в настройке учетных записей теперь еще проще добавлять учетные записи Outlook.com и Gmail, использующие 2-факторную проверку подлинности в Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1310">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="1d334-1311">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1311">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="1d334-1312">**Забудьте об ограничениях синхронизации.** Улучшения Outlook устраняют ограничение для папок, позволяя синхронизировать общие почтовые ящики.</span><span class="sxs-lookup"><span data-stu-id="1d334-1312">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="1d334-1313">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="1d334-1313">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1d334-1314">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="1d334-1314">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1d334-1315">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1315">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="1d334-1316">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1316">PowerPoint</span></span>

- <span data-ttu-id="1d334-1317">**Улучшенное изменение формы.** Назовите свои фигуры, чтобы лучше управлять их трансформацией.</span><span class="sxs-lookup"><span data-stu-id="1d334-1317">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="1d334-1318">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1318">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="1d334-1319">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="1d334-1319">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1d334-1320">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="1d334-1320">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="1d334-1321">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="1d334-1321">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="1d334-1322">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="1d334-1322">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="1d334-1323">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="1d334-1323">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="1d334-1324">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="1d334-1324">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1d334-1325">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="1d334-1325">Switching between them has never been easier.</span></span> [<span data-ttu-id="1d334-1326">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1326">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1d334-1327">**Новое расположение для видео из Интернета.** Сохраняйте видео в Microsoft Stream, чтобы его могли просматривать все пользователи организации.</span><span class="sxs-lookup"><span data-stu-id="1d334-1327">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="1d334-1328">Вставьте ссылку на видео и наслаждайтесь мультимедийной презентацией, размер которой составляет лишь часть от размера файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-1328">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="1d334-1329">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1329">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="1d334-1330">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1330">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="1d334-p226">**Тест или опрос для аудитории.** Добавьте на слайд тест или опрос. Набор Office соберет и сохранит все ответы. [Подробнее](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="1d334-p226">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="1d334-p227">**Вставлять видео из Интернета стало еще проще.** Хотите разместить на своем слайде видео из Vimeo или YouTube? Вам потребуется лишь ссылка на страницу с видео. [Подробнее](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="1d334-p227">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="1d334-1337">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="1d334-1337">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1d334-1338">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="1d334-1338">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1d334-1339">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1339">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="1d334-1340">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-1340">Project</span></span>

- <span data-ttu-id="1d334-1341">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="1d334-1341">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1d334-1342">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="1d334-1342">Switching between them has never been easier.</span></span> [<span data-ttu-id="1d334-1343">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1343">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="1d334-1344">Visio</span><span class="sxs-lookup"><span data-stu-id="1d334-1344">Visio</span></span>

- <span data-ttu-id="1d334-1345">**Экспорт схем процессов в Word.** Автоматически добавляйте содержимое схем, например фигуры и метаданные, в документ Word.</span><span class="sxs-lookup"><span data-stu-id="1d334-1345">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="1d334-1346">Затем настройте документ для создания руководств по обработке и использованию.</span><span class="sxs-lookup"><span data-stu-id="1d334-1346">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="1d334-1347">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1347">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="1d334-1348">**Переосмысление блок-схем данных.** Замечательные новые макеты для блок-схем визуализатора данных просты, лаконичны и удобны для понимания.</span><span class="sxs-lookup"><span data-stu-id="1d334-1348">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="1d334-1349">Для выбора перейдите на вкладку "Конструктор".</span><span class="sxs-lookup"><span data-stu-id="1d334-1349">Click the Design tab for options.</span></span>

- <span data-ttu-id="1d334-1350">**Встроенные наборы элементов Azure.** Разрабатывайте облачное приложение или планируйте архитектуру с помощью множества наборов элементов Azure.</span><span class="sxs-lookup"><span data-stu-id="1d334-1350">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="1d334-1351">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1351">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="1d334-p233">**Попрощайтесь с неработающими ссылками Excel.** Не удается найти книгу Excel, связанную со схемой визуализатора данных? Свяжите ее повторно и продолжайте работу. [Подробнее](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="1d334-p233">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="1d334-1355">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="1d334-1355">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1d334-1356">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="1d334-1356">Switching between them has never been easier.</span></span> [<span data-ttu-id="1d334-1357">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1357">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1d334-1358">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="1d334-1358">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="1d334-1359">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1359">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="1d334-1360">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1360">Word</span></span>

- <span data-ttu-id="1d334-1361">**Поддержка дополнительных цветов страниц в режиме средств обучения.** Теперь средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1361">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="1d334-1362">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="1d334-1362">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="1d334-p237">**Естественное редактирование с помощью Правок от руки.** Разделяйте и объединяйте слова, добавляйте новые строки и вставляйте текст одним движением пера. [Подробнее](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="1d334-p237">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="1d334-p238">**Преобразуйте статические документы.** Преобразуйте документы в интерактивные веб-страницы, которые прекрасно выглядят на любом устройстве и которыми легко делиться. [Подробнее](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="1d334-p238">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="1d334-1367">**Расширение доступа к содержимому.** Нужно сделать документы доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="1d334-1367">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="1d334-1368">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="1d334-1368">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="1d334-1369">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="1d334-1369">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="1d334-1370">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="1d334-1370">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1d334-1371">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="1d334-1371">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="1d334-1372">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="1d334-1372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="1d334-1373">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="1d334-1373">Switching between them has never been easier.</span></span> [<span data-ttu-id="1d334-1374">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="1d334-p242">**Улучшение восприятия с помощью выделения строк.** Перемещайтесь по документу построчно, ни на что не отвлекаясь. Настройте выделение одной, трех или пяти строк одновременно. [Подробнее](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="1d334-p242">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="1d334-1378">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1378">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="1d334-1379">**Привлечение внимания с помощью \@@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="1d334-1379">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="1d334-1380">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1380">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="1d334-1381">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="1d334-1381">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="1d334-1382">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="1d334-1382">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="1d334-1383">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1383">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="1d334-1384">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1384">Office Suite</span></span>

- <span data-ttu-id="1d334-1385">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="1d334-1385">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="1d334-1386">Просто воспользуйтесь полем поиска на вкладке "Файл" > "Открыть", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="1d334-1386">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="1d334-1387">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1387">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="1d334-1388">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="1d334-1388">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="1d334-1389">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1389">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="1d334-1390">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-1390">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="1d334-1391">**Установка Microsoft Teams.** Microsoft Teams по умолчанию устанавливается для существующих экземпляров Office 365 профессиональный плюс.</span><span class="sxs-lookup"><span data-stu-id="1d334-1391">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="1d334-1392">Подробнее</span><span class="sxs-lookup"><span data-stu-id="1d334-1392">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1395">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1395">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="1d334-1396">Access</span><span class="sxs-lookup"><span data-stu-id="1d334-1396">Access</span></span>

- <span data-ttu-id="1d334-1397">Это обновление исправляет проблему, из-за которой агрегатная функция, например, Sum, может обрезать результат до целого значения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1397">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="1d334-1398">Это обновление исправляет проблему, из-за которой запрос на объединение, включающий ссылки на удаленные таблицы (например, таблицы SQL Server), может приводить к закрытию и перезапуску Access.</span><span class="sxs-lookup"><span data-stu-id="1d334-1398">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="1d334-1399">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке &quot;Запрос поврежден&quot; при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="1d334-1399">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="1d334-1400">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1400">Excel</span></span>

- <span data-ttu-id="1d334-1401">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="1d334-1401">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="1d334-1402">Устранена проблема в Excel, из-за которой при выполнении макросов, присвоенных фигурам или элементам управления формы, выводятся неправильные сообщения об ошибке или эти макросы работают в неправильном целевом диапазоне.</span><span class="sxs-lookup"><span data-stu-id="1d334-1402">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="1d334-1403">Решена проблема, при которой содержимое диалогового окна "Поиск и замена" изменялось, если курсор находился в нем после нахождения первого элемента.</span><span class="sxs-lookup"><span data-stu-id="1d334-1403">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="1d334-1404">Исправлена проблема, из-за которой изменение способа сортировки сводной таблицы и ее обновление в сеансе совместного редактирования с другими пользователями могло приводить к сбою.</span><span class="sxs-lookup"><span data-stu-id="1d334-1404">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="1d334-1405">Исправлена проблема, при которой для фильтра сводной таблицы OLAP было задано значение, удаленное из куба.</span><span class="sxs-lookup"><span data-stu-id="1d334-1405">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="1d334-1406">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм.</span><span class="sxs-lookup"><span data-stu-id="1d334-1406">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="1d334-1407">Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="1d334-1407">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="1d334-1408">Устранена проблема, приводившая к нарушению синхронизации каскадных и воронкообразных диаграмм с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="1d334-1408">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="1d334-1409">Исправлена проблема с конфликтом слияния в Excel, из-за которой пользователям предлагалось повторно открыть книгу, чтобы внести изменения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1409">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="1d334-1410">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-1410">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="1d334-1411">Исправлена проблема, которая была причиной ошибки времени выполнения макроса при активации свернутых окон.</span><span class="sxs-lookup"><span data-stu-id="1d334-1411">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="1d334-1412">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-1412">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="1d334-1413">Устранена проблема, из-за которой вырезание и вставка в таблице не выполняются при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="1d334-1413">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="1d334-1414">Решена проблема, вызывавшая прерывание совместного редактирования при изменении настраиваемых свойств с помощью макросов.</span><span class="sxs-lookup"><span data-stu-id="1d334-1414">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="1d334-1415">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытом надстройкой.</span><span class="sxs-lookup"><span data-stu-id="1d334-1415">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="1d334-1416">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="1d334-1416">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="1d334-1417">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="1d334-1417">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="1d334-1418">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="1d334-1418">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="1d334-1419">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="1d334-1419">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="1d334-1420">Исправлена проблема, из-за которой функция Lookup может возвращать ошибку.</span><span class="sxs-lookup"><span data-stu-id="1d334-1420">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="1d334-1421">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-1421">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="1d334-1422">Проблема низкой производительности при нажатии кнопки "Цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="1d334-1422">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="1d334-1423">Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати.</span><span class="sxs-lookup"><span data-stu-id="1d334-1423">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="1d334-1424">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="1d334-1424">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="1d334-1425">Значительно повышена производительность фильтрации по цвету.</span><span class="sxs-lookup"><span data-stu-id="1d334-1425">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="1d334-1426">Устранена проблема, мешавшая вставке гиперссылок в некоторых защищенных листах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1426">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="1d334-1427">Поддерживается отображение более 16 надстроек при просмотре в диспетчере надстроек.</span><span class="sxs-lookup"><span data-stu-id="1d334-1427">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="1d334-1428">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="1d334-1428">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="1d334-1429">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-1429">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-1430">Это обновление устраняет ошибку, из-за которой документы Office могут не отправляться в OneDrive для бизнеса и приходит сообщение "Не удалось выполнить отправку".</span><span class="sxs-lookup"><span data-stu-id="1d334-1430">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="1d334-1431">Устранена проблема в функции "Идеи" для Excel, приводившая к ошибке при загрузке надстройки путем нажатия на кнопку "Идеи" в клиенте Win32.</span><span class="sxs-lookup"><span data-stu-id="1d334-1431">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-1432">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1432">Outlook</span></span>

- <span data-ttu-id="1d334-1433">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-1433">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-1434">Исправлена проблема, из-за которой обновление в почтовых ящиках пользователей обычной проверки подлинности до современной приводило к привязыванию неправильной учетной записи к профилю Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1434">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="1d334-1435">Исправлена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами, когда это не предполагалось.</span><span class="sxs-lookup"><span data-stu-id="1d334-1435">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="1d334-1436">Исправлена проблема, из-за которой URL-адреса не открывались при простом наведении на некоторые безопасные ссылки.</span><span class="sxs-lookup"><span data-stu-id="1d334-1436">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="1d334-1437">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="1d334-1437">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="1d334-1438">Исправлена проблема, из-за которой у подмножества пользователей POP3 сообщения электронной почты выводятся в виде обычного текста, независимо от настроек.</span><span class="sxs-lookup"><span data-stu-id="1d334-1438">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="1d334-1439">Это исправление восстановит сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="1d334-1439">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="1d334-1440">Решена проблема, из-за которой возникала ошибка доступа при копировании элементов из основного календаря в календарь группы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1440">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="1d334-1441">Исправлена проблема, из-за которой пользователям были недоступны предложения расположений при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="1d334-1441">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="1d334-1442">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="1d334-1442">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="1d334-1443">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1443">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="1d334-1444">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="1d334-1444">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="1d334-1445">Решена проблема, вызывавшая сбой в Outlook при взаимодействии пользователей с определенными безопасными ссылками.</span><span class="sxs-lookup"><span data-stu-id="1d334-1445">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="1d334-1446">Исправлена проблема, из-за которой менеджеры не могли установить, ответил ли участник на предоставленное приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="1d334-1446">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="1d334-1447">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1447">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="1d334-1448">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="1d334-1448">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="1d334-1449">Это изменение позволяет администраторам включать политику, предпочитающую указанную учетную запись электронной почты в запросах проверки подлинности службы автообнаружения вместо имени участника-пользователя (UPN).</span><span class="sxs-lookup"><span data-stu-id="1d334-1449">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="1d334-1450">По умолчанию при автообнаружении предпочтение отдается UPN учетной записи (при наличии).</span><span class="sxs-lookup"><span data-stu-id="1d334-1450">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="1d334-1451">Исправлена проблема, вызывавшая сбой поиска в современных группах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1451">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="1d334-1452">Исправлена проблема, приводившая к зависанию пользователей Outlook в состоянии "Требуется пароль" в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1452">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="1d334-1453">Исправлена проблема, из-за которой пользователям предлагались помещения для собраний, проводимых в период времени, когда эти помещения недоступны.</span><span class="sxs-lookup"><span data-stu-id="1d334-1453">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="1d334-1454">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="1d334-1454">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="1d334-1455">Исправлена проблема для неанглоязычных пользователей, из-за которой строка темы в почте отображалась очень маленькой.</span><span class="sxs-lookup"><span data-stu-id="1d334-1455">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="1d334-1456">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="1d334-1456">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="1d334-1457">Исправлена проблема, приводившая к сбою при попытке пользователей создать правило на основе сообщения о пропущенной беседе.</span><span class="sxs-lookup"><span data-stu-id="1d334-1457">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="1d334-1458">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="1d334-1458">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="1d334-1459">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="1d334-1459">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="1d334-1460">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1460">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="1d334-1461">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="1d334-1461">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="1d334-1462">Устранена проблема, которая приводила к периодическому сбою поиска в текущей папке.</span><span class="sxs-lookup"><span data-stu-id="1d334-1462">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="1d334-1463">Исправлена проблема, из-за которой некоторые пользователи сталкивались с ошибками проверки подлинности при попытке получить свои облачные параметры для Outlook.</span><span class="sxs-lookup"><span data-stu-id="1d334-1463">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="1d334-1464">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="1d334-1464">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="1d334-1465">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1465">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="1d334-1466">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="1d334-1466">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1d334-1467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1467">PowerPoint</span></span>

- <span data-ttu-id="1d334-1468">Устранена проблема, из-за которой некоторые надстройки создавали непредвиденные ошибки вокруг фигур в диаграммах.</span><span class="sxs-lookup"><span data-stu-id="1d334-1468">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="1d334-1469">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-1469">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-1470">Это изменение восстанавливает доступное имя для элементов управления видео в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1470">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="1d334-1471">Исправлена проблема, из-за которой мог блокироваться запуск некоторых анимаций.</span><span class="sxs-lookup"><span data-stu-id="1d334-1471">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="1d334-1472">Исправлена проблема, из-за которой при копировании слайда из одной презентации в другую могли появляться дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="1d334-1472">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="1d334-1473">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="1d334-1473">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="1d334-1474">Исправление проблем с надежностью. Устранена проблема, из-за которой надстройка стороннего поставщика могла вызывать сбой PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1474">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="1d334-1475">Исправлена проблема, из-за которой не удавалось правильно повернуть полуширинные знаки катаканы при использовании вертикальных текстовых полей в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1475">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="1d334-1476">Project</span><span class="sxs-lookup"><span data-stu-id="1d334-1476">Project</span></span>

- <span data-ttu-id="1d334-1477">Исправлена проблема, чтобы разрешить пользователям в Windows 7 открывать проекты из Project Web App и сайтов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1477">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="1d334-1478">Обнаружена проблема, из-за которой пользователи могли получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="1d334-1478">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="1d334-1479">Команда "Выровнять все" не устраняет должным образом превышение доступности ресурсов.</span><span class="sxs-lookup"><span data-stu-id="1d334-1479">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="1d334-1480">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="1d334-1480">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="1d334-1481">Visio</span><span class="sxs-lookup"><span data-stu-id="1d334-1481">Visio</span></span>

- <span data-ttu-id="1d334-1482">Экспорт в формате SVG из Visio не работал для различных фигур.</span><span class="sxs-lookup"><span data-stu-id="1d334-1482">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-1483">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1483">Word</span></span>

- <span data-ttu-id="1d334-1484">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="1d334-1484">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="1d334-1485">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="1d334-1485">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="1d334-1486">Исправлена проблема, из-за которой могли возникать проблемы с масштабированием при печати на принтерах Deskjet.</span><span class="sxs-lookup"><span data-stu-id="1d334-1486">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="1d334-1487">Исправлена проблема с отслеживанием изменений, которые иногда переходят в режим бесконечного цикла. </span><span class="sxs-lookup"><span data-stu-id="1d334-1487">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="1d334-1488">Исправлены различные проблемы, из-за которых приложение может зависнуть при завершении работы.</span><span class="sxs-lookup"><span data-stu-id="1d334-1488">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="1d334-1489">Также исправлены некоторые ошибки, связанные с надстройками.</span><span class="sxs-lookup"><span data-stu-id="1d334-1489">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="1d334-1490">Набор Office</span><span class="sxs-lookup"><span data-stu-id="1d334-1490">Office Suite</span></span>

- <span data-ttu-id="1d334-1491">Исправлена проблема с неправильным определением названия новой эры "Рэйва" в хирагана и кандзи как выражения с опечаткой или грамматической ошибкой.</span><span class="sxs-lookup"><span data-stu-id="1d334-1491">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="1d334-1492">Исправлена проблема, из-за которой пользователи получали сообщение "Не удалось предоставить общий доступ" при попытке поделиться файлами, хранящимися в SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="1d334-1492">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="1d334-1493">Исправлена проблема, которая могла приводить к потере данных в сеансах, включающих как совместное редактирование, так и редактирование в автономном режиме в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1493">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="1d334-1494">Исправлена проблема, из-за которой мог произойти сбой при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="1d334-1494">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="1d334-1495">Исправление позволяет пользователям PowerPoint избежать ошибки при попытке онлайн-презентации.</span><span class="sxs-lookup"><span data-stu-id="1d334-1495">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="1d334-1496">В некоторых случаях файл SharePoint, сохраненный с помощью модуля синхронизации, отображал состояние "Сохранено", но в действительности изменения не сохранялись. Это приводило к потере данных.</span><span class="sxs-lookup"><span data-stu-id="1d334-1496">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="1d334-1497">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="1d334-1497">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="1d334-1498">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как диалоговое окно", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="1d334-1498">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="1d334-1499">Устранена проблема с быстродействием Win7, из-за которой вставленная коллекция фигур с ленты во всех приложениях отображалась примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="1d334-1499">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="1d334-1500">Исправлена ошибка, из-за которой сведения о специальных возможностях не отображались в области сведений представления Backstage.</span><span class="sxs-lookup"><span data-stu-id="1d334-1500">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="1d334-1501">Повышена надежность процесса обновления Office в отношении целостности реестра.</span><span class="sxs-lookup"><span data-stu-id="1d334-1501">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="1d334-1502">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="1d334-1502">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="1d334-1503">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="1d334-1503">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="1d334-1504">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="1d334-1504">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="1d334-1505">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="1d334-1505">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="1d334-1506">При определенных обстоятельствах ярлыки Office могут исчезнуть после обновления.</span><span class="sxs-lookup"><span data-stu-id="1d334-1506">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="1d334-1507">Это обновление повышает надежность при публикации ярлыков Office.</span><span class="sxs-lookup"><span data-stu-id="1d334-1507">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="1d334-1508">Исправлена проблема, из-за которой обновления могли неожиданно блокироваться в сетях с лимитным тарифным планом.</span><span class="sxs-lookup"><span data-stu-id="1d334-1508">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="1d334-1509">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="1d334-1509">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="1d334-1510">Повышена надежность при скачивании обновлений Office путем продолжения скачивания, которое ранее могло прерываться.</span><span class="sxs-lookup"><span data-stu-id="1d334-1510">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="1d334-1511">Устранены проблемы, связанные со свойством автоподбора размера текстовых полей и фигур в сторонних подключаемых модулях.</span><span class="sxs-lookup"><span data-stu-id="1d334-1511">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="1d334-1512">Исправлена проблема, из-за которой крупные представления в виде дерева приводили к сбою.</span><span class="sxs-lookup"><span data-stu-id="1d334-1512">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="1d334-1513">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="1d334-1513">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-january-14"></a><span data-ttu-id="1d334-1515">Версия 1902: 14 января</span><span class="sxs-lookup"><span data-stu-id="1d334-1515">Version 1902: January 14</span></span>
<span data-ttu-id="1d334-1516">*Версия 1902 (сборка 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1516">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="1d334-1517">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="1d334-1519">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="1d334-1519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="1d334-1520">Excel</span><span class="sxs-lookup"><span data-stu-id="1d334-1520">Excel</span></span>

- <span data-ttu-id="1d334-1521">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="1d334-1521">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="1d334-1522">Outlook</span><span class="sxs-lookup"><span data-stu-id="1d334-1522">Outlook</span></span>

- <span data-ttu-id="1d334-1523">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="1d334-1523">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="1d334-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="1d334-1524">PowerPoint</span></span>

- <span data-ttu-id="1d334-1525">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="1d334-1525">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="1d334-1526">Word</span><span class="sxs-lookup"><span data-stu-id="1d334-1526">Word</span></span>

- <span data-ttu-id="1d334-1527">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="1d334-1527">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1808-january-14"></a><span data-ttu-id="1d334-1529">Версия 1808: 14 января</span><span class="sxs-lookup"><span data-stu-id="1d334-1529">Version 1808: January 14</span></span>
<span data-ttu-id="1d334-1530">*Версия 1808 (сборка 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="1d334-1530">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="1d334-1531">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="1d334-1531">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="1d334-1533">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="1d334-1533">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|DC|Production| |16.0.12527.21416|version-2002-december-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
