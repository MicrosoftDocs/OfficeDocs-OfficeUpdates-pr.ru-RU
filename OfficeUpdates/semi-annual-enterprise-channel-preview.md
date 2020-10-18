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
ms.openlocfilehash: 18637bac9ff51237a2afe97136febbd20cb46512
ms.sourcegitcommit: f906906efeaa6b3d35d324a70303ed4c79771552
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/14/2020
ms.locfileid: "48466117"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="a109d-103">Заметки о выпусках Полугодового канала (предварительной корпоративной версии) в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a109d-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="a109d-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (предварительная корпоративная версия) в 2020 г. для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="a109d-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="a109d-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="a109d-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a109d-106">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="a109d-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-october-13"></a><span data-ttu-id="a109d-107">Версия 2008: 13 октября</span><span class="sxs-lookup"><span data-stu-id="a109d-107">Version 2008: October 13</span></span>
<span data-ttu-id="a109d-108">*Версия 2008 (сборка 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="a109d-108">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="a109d-109">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-111">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-112">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-112">Excel</span></span>

- <span data-ttu-id="a109d-113">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="a109d-113">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="a109d-114">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="a109d-114">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="a109d-115">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="a109d-115">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="a109d-116">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="a109d-116">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="a109d-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-117">Outlook</span></span>

- <span data-ttu-id="a109d-118">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="a109d-118">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="a109d-119">Исправлена проблема, из-за которой иногда не удавалось применить параметр "Включить улучшения общего календаря" к существующим общим календарям.</span><span class="sxs-lookup"><span data-stu-id="a109d-119">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="a109d-120">Исправлена проблема, из-за которой при открытии облачного вложения ошибка отображалась на странице безопасных ссылок, а не в открываемом документе.</span><span class="sxs-lookup"><span data-stu-id="a109d-120">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="a109d-121">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="a109d-121">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a109d-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-122">PowerPoint</span></span>

- <span data-ttu-id="a109d-123">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="a109d-123">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="a109d-124">Исправление системы безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="a109d-124">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="a109d-125">Исправлена проблема в диалоговом окне "Параметры действия", из-за которой возникал сбой в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-125">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="a109d-126">Visio</span><span class="sxs-lookup"><span data-stu-id="a109d-126">Visio</span></span>

- <span data-ttu-id="a109d-127">Исправлена проблема, из-за которой возникал сбой динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="a109d-127">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="a109d-128">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-128">Word</span></span>

- <span data-ttu-id="a109d-129">Исправлена проблема, которая вызывала сбой при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a109d-129">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="a109d-130">Исправлена проблема, из-за которой мог возникать сбой при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="a109d-130">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="a109d-131">Устранена проблема, которая могла вызвать сбой при загрузке Word.</span><span class="sxs-lookup"><span data-stu-id="a109d-131">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="a109d-132">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="a109d-132">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a109d-133">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a109d-133">Office Suite</span></span>

- <span data-ttu-id="a109d-134">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="a109d-134">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="a109d-135">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="a109d-135">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="a109d-136">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="a109d-136">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="a109d-137">Это изменение устраняет сбой при запуске приложений Office из-за невозможности загрузки d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="a109d-137">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-08"></a><span data-ttu-id="a109d-139">Версия 2008: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="a109d-139">Version 2008: September 08</span></span>
<span data-ttu-id="a109d-140">*Версия 2008 (сборка 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="a109d-140">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="a109d-141">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-141">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a109d-143">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a109d-143">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a109d-144">Access</span><span class="sxs-lookup"><span data-stu-id="a109d-144">Access</span></span>

- <span data-ttu-id="a109d-145">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="a109d-145">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a109d-146">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="a109d-146">Search and replace text in SQL View.</span></span> <span data-ttu-id="a109d-147">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="a109d-147">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="a109d-148">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="a109d-148">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="a109d-149">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-149">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="a109d-150">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-150">Excel</span></span>

- <span data-ttu-id="a109d-151">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="a109d-151">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="a109d-152">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-152">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="a109d-153">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="a109d-153">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="a109d-154">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="a109d-154">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="a109d-155">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="a109d-155">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="a109d-156">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="a109d-156"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="a109d-157">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="a109d-157">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="a109d-158">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-158">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="a109d-159">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="a109d-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="a109d-160">**Ваши любимые функции Excel теперь работают быстрее.** Функции СУММЕСЛИМН, СРЗНАЧЕСЛИМН, СЧЁТЕСЛИМН, МАКСЕСЛИМН и МИНЕСЛИМН теперь работают намного быстрее.</span><span class="sxs-lookup"><span data-stu-id="a109d-160">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="a109d-161">Быстрее переходите к итоговой строке.</span><span class="sxs-lookup"><span data-stu-id="a109d-161">Get to the bottom line more quickly.</span></span> <span data-ttu-id="a109d-162">Попробуйте уже сейчас.</span><span class="sxs-lookup"><span data-stu-id="a109d-162">Try one now.</span></span>

- <span data-ttu-id="a109d-163">**Улучшение функции Realtimedata (RTD):** В Office 365 версии 2002 канала Monthly channel или более поздних версиях функция Excel RealTimeData (ДРВ) работает гораздо быстрее, чем в вычисление данных в таблице в Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="a109d-163">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="a109d-164">Мы удалили узкие места в базовой памяти и структурах данных, а также обеспечили потокобезопасность, чтобы разрешить вычисление во всех доступных потоках многопоточного пересчета (MTR).</span><span class="sxs-lookup"><span data-stu-id="a109d-164">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-165">Outlook</span></span>

- <span data-ttu-id="a109d-166">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="a109d-166">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="a109d-167">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="a109d-167">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="a109d-168">\*\*Лучшие результаты - в одно мгновение: \*\*мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="a109d-168">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="a109d-169">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-169">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="a109d-170">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="a109d-170">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="a109d-171">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="a109d-171">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="a109d-172">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="a109d-172">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="a109d-173">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="a109d-173">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="a109d-174">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="a109d-174">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="a109d-175">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="a109d-175">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="a109d-176">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-176">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="a109d-177">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="a109d-177">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="a109d-178">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="a109d-178">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="a109d-179">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="a109d-179">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="a109d-180">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="a109d-180">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a109d-181">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="a109d-181">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="a109d-182">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="a109d-182">See details in [blog post](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="a109d-183">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a109d-183">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="a109d-184">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-184">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="a109d-185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-185">PowerPoint</span></span>

- <span data-ttu-id="a109d-186">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="a109d-186">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="a109d-187">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-187">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="a109d-188">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="a109d-188">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="a109d-189">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-189">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="a109d-190">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="a109d-190">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="a109d-191">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-191">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="a109d-192">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-192">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="a109d-193">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="a109d-193">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="a109d-194">**Улучшенные диаграммы.** Более удобное создание диаграмм от руки за счет использования улучшенных соединителей и более совершенного процесса преобразования рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="a109d-194">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="a109d-195">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-195">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="a109d-196">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="a109d-196">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="a109d-197">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="a109d-197">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="a109d-198">**Комментарии.** Новые функций комментирования в PowerPoint позволяют быстро и легко находить и добавлять комментарии к документам.</span><span class="sxs-lookup"><span data-stu-id="a109d-198">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="a109d-199">Модернизируйте совместную работу с помощью новых функций, таких как привязка комментариев, сопоставление, задачи, улучшенные уведомления об упоминаниях и т. д.</span><span class="sxs-lookup"><span data-stu-id="a109d-199">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="a109d-200">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-200">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="a109d-201">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="a109d-201">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="a109d-202">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-202">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="a109d-203">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="a109d-203">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="a109d-204">**Ссылка на слайд:** попросите коллег поучаствовать в создании презентации и направьте их прямо на нужный слайд.</span><span class="sxs-lookup"><span data-stu-id="a109d-204">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="a109d-205">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-205">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="a109d-206">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="a109d-206">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="a109d-207">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="a109d-207">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="a109d-208">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="a109d-208">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="a109d-209">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-209">Word</span></span>

- <span data-ttu-id="a109d-210">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="a109d-210">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="a109d-211">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-211">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="a109d-212">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="a109d-212">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="a109d-213">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="a109d-213">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="a109d-214">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-214">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="a109d-215">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="a109d-215">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="a109d-216">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="a109d-216">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="a109d-217">**Подтверждение действий в средстве чтения с экрана.** Подтверждение действий — это важное требование для обеспечения специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="a109d-217">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="a109d-218">С появлением нового API уведомлений из Windows мы можем оповещать пользователей средства чтения с экрана об успехе их действий.</span><span class="sxs-lookup"><span data-stu-id="a109d-218">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="a109d-219">Теперь пользователи экранного диктора в Word для Win32 уведомляются о вырезании, копировании, вставке, использовании полужирного шрифта, курсива или подчеркивания, отмене, повторе, автозамене и автоматическом использовании прописных букв.</span><span class="sxs-lookup"><span data-stu-id="a109d-219">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="a109d-220">Чтобы включить эту возможность, включите экранный диктор с помощью клавиш Windows+CTRL+ВВОД.</span><span class="sxs-lookup"><span data-stu-id="a109d-220">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="a109d-221">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="a109d-221">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-222">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-222">Office Suite</span></span>

- <span data-ttu-id="a109d-223">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="a109d-223">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-226">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-226">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a109d-227">Доступ</span><span class="sxs-lookup"><span data-stu-id="a109d-227">Access</span></span>

- <span data-ttu-id="a109d-228">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="a109d-228">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="a109d-229">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a109d-229">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="a109d-230">Исправлена проблема, препятствующая возможности вызова расширенного типа данных "Дата/время" без сбоев приложения.</span><span class="sxs-lookup"><span data-stu-id="a109d-230">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="a109d-231">Проблема исправлена, поэтому теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для управления и изменения типа данных Decimal.</span><span class="sxs-lookup"><span data-stu-id="a109d-231">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="a109d-232">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="a109d-232">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="a109d-233">Эта проблема исправлена в Access, но мы продолжаем изучать дополнительные интерфейсы, чтобы она не повторилась.</span><span class="sxs-lookup"><span data-stu-id="a109d-233">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="a109d-234">Команда сообщит о будущих обновлениях. Мы ценим ваше терпение.</span><span class="sxs-lookup"><span data-stu-id="a109d-234">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="a109d-235">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="a109d-235">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="a109d-236">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-236">Excel</span></span>

- <span data-ttu-id="a109d-237">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="a109d-237">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="a109d-238">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="a109d-238">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="a109d-239">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="a109d-239">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="a109d-240">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="a109d-240">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="a109d-241">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="a109d-241">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="a109d-242">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a109d-242">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="a109d-243">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="a109d-243">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="a109d-244">Исправлена проблема, из-за которой в некоторых случаях при щелчке по гиперссылке внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="a109d-244">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="a109d-245">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="a109d-245">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="a109d-246">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="a109d-246">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="a109d-247">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="a109d-247">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a109d-248">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="a109d-248">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="a109d-249">Это устраняет проблему, из-за которой при подключениях, созданных поставщиком данных SQL в более ранних версиях Office, параметры внутренних таблиц задавались не так, как в Office 365.</span><span class="sxs-lookup"><span data-stu-id="a109d-249">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="a109d-250">Это приводит к отключению раскрывающегося списка "Просмотр таблиц" или "Редактор запросов" для файлов с подключениями, созданными в более ранних версиях Office, когда они открывались с помощью Office 365.</span><span class="sxs-lookup"><span data-stu-id="a109d-250">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="a109d-251">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="a109d-251">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="a109d-252">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="a109d-252">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="a109d-253">OneNote</span><span class="sxs-lookup"><span data-stu-id="a109d-253">OneNote</span></span>

- <span data-ttu-id="a109d-254">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="a109d-254">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="a109d-255">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-255">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="a109d-256">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="a109d-256">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="a109d-257">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-257">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="a109d-258">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="a109d-258">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="a109d-259">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-259">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="a109d-260">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="a109d-260">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="a109d-261">Улучшена синхронизация и стабильность службы за счет временного изменения частоты создания журналов версий страниц.</span><span class="sxs-lookup"><span data-stu-id="a109d-261">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="a109d-262">Улучшена синхронизация и стабильность службы за счет временного отключения перемещения страниц в корзину.</span><span class="sxs-lookup"><span data-stu-id="a109d-262">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="a109d-263">Для пользователей, которым нужно удалить страницу, будет отображаться диалоговое окно с вопросом, нужно ли удалить страницу окончательно.</span><span class="sxs-lookup"><span data-stu-id="a109d-263">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-264">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-264">Outlook</span></span>

- <span data-ttu-id="a109d-265">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="a109d-265">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="a109d-266">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="a109d-266">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="a109d-267">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="a109d-267">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="a109d-268">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="a109d-268">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="a109d-269">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="a109d-269">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="a109d-270">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="a109d-270">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="a109d-271">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="a109d-271">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="a109d-272">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="a109d-272">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="a109d-273">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="a109d-273">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="a109d-274">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="a109d-274">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="a109d-275">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="a109d-275">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="a109d-276">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="a109d-276">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="a109d-277">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="a109d-277">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="a109d-278">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="a109d-278">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="a109d-279">Устранена проблема, которая в некоторых ситуациях приводила к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="a109d-279">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="a109d-280">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="a109d-280">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="a109d-281">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="a109d-281">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="a109d-282">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="a109d-282">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="a109d-283">Устранена проблема, из-за которой у пользователей возникали сбои в сторонних приложениях MAPI.</span><span class="sxs-lookup"><span data-stu-id="a109d-283">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="a109d-284">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="a109d-284">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="a109d-285">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="a109d-285">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="a109d-286">Устранена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="a109d-286">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="a109d-287">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="a109d-287">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="a109d-288">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="a109d-288">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="a109d-289">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="a109d-289">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="a109d-290">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="a109d-290">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="a109d-291">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="a109d-291">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="a109d-292">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="a109d-292">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="a109d-293">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="a109d-293">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="a109d-294">Устранена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="a109d-294">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="a109d-295">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="a109d-295">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="a109d-296">Исправлена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="a109d-296">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="a109d-297">Исправлена проблема, из-за которой возникали аномалии при использовании компактного представления.</span><span class="sxs-lookup"><span data-stu-id="a109d-297">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="a109d-298">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="a109d-298">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="a109d-299">Устранена проблема, из-за которой контекстное меню не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="a109d-299">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="a109d-300">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="a109d-300">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="a109d-301">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="a109d-301">Do you want to download them anyway?</span></span> <span data-ttu-id="a109d-302">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="a109d-302">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="a109d-303">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="a109d-303">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="a109d-304">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="a109d-304">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="a109d-305">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="a109d-305">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="a109d-306">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="a109d-306">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="a109d-307">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="a109d-307">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="a109d-308">Устранена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="a109d-308">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="a109d-309">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="a109d-309">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a109d-310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-310">PowerPoint</span></span>

- <span data-ttu-id="a109d-311">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="a109d-311">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="a109d-312">Устранена проблема со сбоем в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-312">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="a109d-313">Устранена проблема со сбоем панели предложений.</span><span class="sxs-lookup"><span data-stu-id="a109d-313">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="a109d-314">Project</span><span class="sxs-lookup"><span data-stu-id="a109d-314">Project</span></span>

- <span data-ttu-id="a109d-315">Устранена проблема, из-за которой при редактировании данных Предшественника / Преемника в представлении формы, запускалось дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="a109d-315">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="a109d-316">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="a109d-316">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="a109d-317">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="a109d-317">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="a109d-318">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="a109d-318">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="a109d-319">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="a109d-319">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="a109d-320">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="a109d-320">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="a109d-321">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="a109d-321">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="a109d-322">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="a109d-322">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="a109d-323">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="a109d-323">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="a109d-324">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="a109d-324">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="a109d-325">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-325">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="a109d-326">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="a109d-326">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="a109d-327">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="a109d-327">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="a109d-328">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="a109d-328">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="a109d-329">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-329">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="a109d-330">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="a109d-330">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="a109d-331">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="a109d-331">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="a109d-332">Skype</span><span class="sxs-lookup"><span data-stu-id="a109d-332">Skype</span></span>

- <span data-ttu-id="a109d-333">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="a109d-333">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="a109d-334">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="a109d-334">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="a109d-335">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="a109d-335">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="a109d-336">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="a109d-336">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-337">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-337">Word</span></span>

- <span data-ttu-id="a109d-338">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="a109d-338">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="a109d-339">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="a109d-339">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="a109d-340">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="a109d-340">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="a109d-341">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="a109d-341">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="a109d-342">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="a109d-342">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="a109d-343">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="a109d-343">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="a109d-344">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="a109d-344">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="a109d-345">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="a109d-345">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="a109d-346">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="a109d-346">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="a109d-347">Устранена проблема, которая могла вызвать сбой при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="a109d-347">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a109d-348">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-348">Office Suite</span></span>

- <span data-ttu-id="a109d-349">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта.</span><span class="sxs-lookup"><span data-stu-id="a109d-349">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="a109d-350">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="a109d-350">This is now fixed.</span></span>

- <span data-ttu-id="a109d-351">Устранена проблема, из-за которой при закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="a109d-351">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="a109d-352">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="a109d-352">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="a109d-353">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="a109d-353">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="a109d-354">Исправлена проблема технологии "Нажми и работай", из-за которой происходил сбой обновления при попытке жесткой связи символьных ссылок.</span><span class="sxs-lookup"><span data-stu-id="a109d-354">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="a109d-355">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="a109d-355">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="a109d-356">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="a109d-356">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="a109d-357">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="a109d-357">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="a109d-358">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="a109d-358">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="a109d-359">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="a109d-359">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="a109d-360">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="a109d-360">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="a109d-361">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="a109d-361">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="a109d-362">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="a109d-362">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="a109d-363">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="a109d-363">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="a109d-364">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="a109d-364">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="a109d-365">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="a109d-365">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="a109d-366">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="a109d-366">This change would fix this issue.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-august-11"></a><span data-ttu-id="a109d-368">Версия 2002: 11 августа</span><span class="sxs-lookup"><span data-stu-id="a109d-368">Version 2002: August 11</span></span>
<span data-ttu-id="a109d-369">*Версия 2002 (сборка 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="a109d-369">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="a109d-370">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-370">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-372">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-372">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-373">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-373">Excel</span></span>

- <span data-ttu-id="a109d-374">Исправлена проблема, не позволявшая переключиться на редактирование файлов, открытых с использованием параметра "Рекомендовать доступ только для чтения".</span><span class="sxs-lookup"><span data-stu-id="a109d-374">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="a109d-375">OneNote</span><span class="sxs-lookup"><span data-stu-id="a109d-375">OneNote</span></span>

- <span data-ttu-id="a109d-376">Удалены лишние вызовы удостоверений, чтобы сократить использование ресурсов</span><span class="sxs-lookup"><span data-stu-id="a109d-376">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="a109d-377">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="a109d-377">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="a109d-378">Улучшена функция обнаружения ошибок и качество синхронизации.</span><span class="sxs-lookup"><span data-stu-id="a109d-378">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-379">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-379">Outlook</span></span>

- <span data-ttu-id="a109d-380">Исправлена ошибка, вызывавшая серьезную проблему с производительностью при запуске Outlook для некоторых клиентов.</span><span class="sxs-lookup"><span data-stu-id="a109d-380">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="a109d-381">Skype</span><span class="sxs-lookup"><span data-stu-id="a109d-381">Skype</span></span>

- <span data-ttu-id="a109d-382">Исправлена проблема, из-за которой запуск демонстрации экрана мог завершиться сбоем в 32-разрядном клиенте Skype для бизнеса после его работы в течение нескольких дней.</span><span class="sxs-lookup"><span data-stu-id="a109d-382">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-383">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-383">Office Suite</span></span>

- <span data-ttu-id="a109d-384">Исправлена проблема, из-за которой в случае отключения автосохранения с помощью групповой политики некоторые документы могли не отображать последнее содержимое сервера при открытии, пока пользователь не нажмет кнопку "Доступны обновления".</span><span class="sxs-lookup"><span data-stu-id="a109d-384">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-july-14"></a><span data-ttu-id="a109d-386">Версия 2002: 14 июля</span><span class="sxs-lookup"><span data-stu-id="a109d-386">Version 2002: July 14</span></span>
<span data-ttu-id="a109d-387">*Версия 2002 (сборка 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="a109d-387">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="a109d-388">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-388">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-390">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-390">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-391">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-391">Excel</span></span>

- <span data-ttu-id="a109d-392">Ускорение загрузки файлов, доступных в локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a109d-392">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="a109d-393">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a109d-393">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="a109d-394">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, поэтому закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="a109d-394">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="a109d-395">Исправлена проблема, при которой книга могла быть скрыта при щелчке гиперссылки на определенное место в уже открытой книге.</span><span class="sxs-lookup"><span data-stu-id="a109d-395">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="a109d-396">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="a109d-396">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="a109d-397">Повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="a109d-397">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="a109d-398">Устранена проблема, из-за которой имена принтеров могли повторяться в списке принтеров в диалоговом окне "Печать".</span><span class="sxs-lookup"><span data-stu-id="a109d-398">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="a109d-399">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="a109d-399">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="a109d-400">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-400">Outlook</span></span>

- <span data-ttu-id="a109d-401">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="a109d-401">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="a109d-402">Устранена проблема, при которой повторяющиеся встречи или собрания отображались с ошибкой во времени при приближении изменений в определении часового пояса.</span><span class="sxs-lookup"><span data-stu-id="a109d-402">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="a109d-403">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="a109d-403">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="a109d-404">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="a109d-404">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="a109d-405">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a109d-405">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a109d-406">Устранена проблема, из-за которой представители видели разные иерархии папок общих почтовых ящиков на разных компьютерах.</span><span class="sxs-lookup"><span data-stu-id="a109d-406">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a109d-407">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="a109d-407">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="a109d-408">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="a109d-408">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="a109d-409">Устранена проблема, вызывавшая сбой после того, как две надстройки добавляли кнопку в одну и ту же группу ленты.</span><span class="sxs-lookup"><span data-stu-id="a109d-409">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="a109d-410">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения по адресам из личного списка рассылки.</span><span class="sxs-lookup"><span data-stu-id="a109d-410">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="a109d-411">Устранена проблема, из-за которой нельзя было добавить ссылки в сообщения электронной почты с правильным клиентским разрешением по умолчанию, если для этого разрешения был установлен параметр "все".</span><span class="sxs-lookup"><span data-stu-id="a109d-411">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="a109d-412">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="a109d-412">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-413">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-413">Word</span></span>

- <span data-ttu-id="a109d-414">Исправлена проблема с совместной работой над документом при включении политики FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="a109d-414">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="a109d-415">Устранена проблема, при которой функция экспресс-блоков Word не работала при добавлении переименованного поля подстановки.</span><span class="sxs-lookup"><span data-stu-id="a109d-415">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-416">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-416">Office Suite</span></span>

- <span data-ttu-id="a109d-417">Исправлена проблема, из-за которой при совместной работе над объемными файлами PowerPoint чрезмерно повышалась нагрузка на сеть и ЦП.</span><span class="sxs-lookup"><span data-stu-id="a109d-417">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="a109d-418">Мы бэкпортировали новую версию AppV51, чтобы исправить регрессию в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="a109d-418">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="a109d-419">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="a109d-419">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-june-09"></a><span data-ttu-id="a109d-421">Версия 2002: 9 июня</span><span class="sxs-lookup"><span data-stu-id="a109d-421">Version 2002: June 09</span></span>
<span data-ttu-id="a109d-422">*Версия 2002 (сборка 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="a109d-422">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="a109d-423">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-423">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-425">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-425">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-426">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-426">Excel</span></span>

- <span data-ttu-id="a109d-427">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="a109d-427">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="a109d-428">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="a109d-428">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="a109d-429">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="a109d-429">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="a109d-430">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="a109d-430">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="a109d-431">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a109d-431">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="a109d-432">Исправлена проблема, из-за которой знак @ в начале формулы считался неявным оператором пересечения.</span><span class="sxs-lookup"><span data-stu-id="a109d-432">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-433">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-433">Outlook</span></span>

- <span data-ttu-id="a109d-434">Позволяет присоединиться к собранию в Teams непосредственно через собственный клиент Teams.</span><span class="sxs-lookup"><span data-stu-id="a109d-434">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="a109d-435">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="a109d-435">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="a109d-436">Исправлена проблема, из-за которой пользователи, имеющие неправильный параметр эмуляции браузера, не могли завершить запрос на проверку подлинности Gmail.</span><span class="sxs-lookup"><span data-stu-id="a109d-436">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="a109d-437">Исправлена проблема пользователей Outlook, использующих серверные операционные системы, приводившая к ошибке "Состояние защиты от вирусов: Недействительно.</span><span class="sxs-lookup"><span data-stu-id="a109d-437">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="a109d-438">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены", несмотря на то, что антивирусная программа настроена правильно.</span><span class="sxs-lookup"><span data-stu-id="a109d-438">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-439">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-439">Word</span></span>

- <span data-ttu-id="a109d-440">Исправлена проблема, из-за которой выравнивание слова в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="a109d-440">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-441">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-441">Office Suite</span></span>

- <span data-ttu-id="a109d-442">Эта проблема устранена с помощью замены имен каналов в представлении Backstage на новые в разветвлении января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a109d-442">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="a109d-443">Исправлена проблема, из-за которой устройства регулируемые политикой не могли вызвать API аудитории DMS.</span><span class="sxs-lookup"><span data-stu-id="a109d-443">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="a109d-444">Исправлена проблема, из-за которой при добавлении и удалении приложений в одной транзакции выполнялось неполное удаление.</span><span class="sxs-lookup"><span data-stu-id="a109d-444">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="a109d-445">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="a109d-445">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="a109d-446">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="a109d-446">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-may-12"></a><span data-ttu-id="a109d-448">Версия 2002: 12 мая</span><span class="sxs-lookup"><span data-stu-id="a109d-448">Version 2002: May 12</span></span>
<span data-ttu-id="a109d-449">*Версия 2002 (сборка 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="a109d-449">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="a109d-450">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-450">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-452">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-452">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a109d-453">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-453">Excel</span></span>

- <span data-ttu-id="a109d-454">Открытие книги со ссылками на ряд других книг, особенно в скрытых окнах, выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a109d-454">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="a109d-455">В некоторых случаях открытие CSV-файлов занимало больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a109d-455">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="a109d-456">В ряде случаев приложение Excel аварийно завершало работу при переключении между книгами с разным масштабом.</span><span class="sxs-lookup"><span data-stu-id="a109d-456">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="a109d-457">Устранена проблема с VBA, из-за которой внесение значений в диапазон выполнялось медленнее, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a109d-457">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="a109d-458">Данные, скопированные из столбца и отфильтрованные по цвету, иногда не вставлялись должным образом.</span><span class="sxs-lookup"><span data-stu-id="a109d-458">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="a109d-459">Устранена проблема, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="a109d-459">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="a109d-460">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись могла быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="a109d-460">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="a109d-461">Устранена проблема, которая приводила к неожиданному изменению свойства "Пересекает в значении" на оси диаграммы при сохранении и повторном открытии файла.</span><span class="sxs-lookup"><span data-stu-id="a109d-461">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="a109d-462">При использовании Range.Value и Range.Value2 (VBA) формулы вводились как динамические массивы.</span><span class="sxs-lookup"><span data-stu-id="a109d-462">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="a109d-463">OneNote</span><span class="sxs-lookup"><span data-stu-id="a109d-463">OneNote</span></span>

- <span data-ttu-id="a109d-464">Локализует уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="a109d-464">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="a109d-465">Отображает уведомление, позволяющее пользователю получить дополнительные сведения о временных мерах, которые используются при работе с OneNote для улучшения синхронизации и стабильности службы.</span><span class="sxs-lookup"><span data-stu-id="a109d-465">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="a109d-466">Улучшена синхронизация и стабильность службы путем временного уменьшения количества и частоты синхронизации страниц журнала версий в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-466">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="a109d-467">Улучшена синхронизация и стабильность службы путем временного отключения корзины в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-467">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="a109d-468">Если пользователь пытается удалить данные, которые обычно отправляются в корзину, ему будет предложено сохранить или окончательно удалить их.</span><span class="sxs-lookup"><span data-stu-id="a109d-468">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="a109d-469">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-469">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="a109d-470">Улучшена синхронизация и стабильность службы путем временного откладывания загрузки внедренных файлов и изображений в записных книжках в Интернете, пока пользователь не перейдет на страницу в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-470">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="a109d-471">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-471">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="a109d-472">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="a109d-472">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="a109d-473">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="a109d-473">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="a109d-474">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="a109d-474">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-475">Outlook</span></span>

- <span data-ttu-id="a109d-476">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="a109d-476">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="a109d-477">Устранена проблема, приводившая в сбою при попытке открытия файлов MSG и OFT после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="a109d-477">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="a109d-478">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="a109d-478">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="a109d-479">Это обновление исправляет проблему, из-за которой в Microsoft Outlook не отображается текущая метка конфиденциальности при просмотре или создании сообщений.</span><span class="sxs-lookup"><span data-stu-id="a109d-479">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="a109d-480">Исправлена проблема, из-за которой пользователи не могли отправлять электронные сообщения в личный список рассылки.</span><span class="sxs-lookup"><span data-stu-id="a109d-480">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a109d-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-481">PowerPoint</span></span>

- <span data-ttu-id="a109d-482">Устранена проблема с ретрансляцией точного текста сообщений для пользователей, которые открывают копию файла с улучшенными примечаниями.</span><span class="sxs-lookup"><span data-stu-id="a109d-482">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-483">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-483">Word</span></span>

- <span data-ttu-id="a109d-484">Решена проблема, из-за которой приложения Access и Publisher могли загружаться неправильно в зависимости от того, какие языки установлены.</span><span class="sxs-lookup"><span data-stu-id="a109d-484">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="a109d-485">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="a109d-485">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="a109d-486">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="a109d-486">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-487">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-487">Office Suite</span></span>

- <span data-ttu-id="a109d-488">Это исправление устраняет блокирование сети приложением Project при кэшировании файла в клиенте.</span><span class="sxs-lookup"><span data-stu-id="a109d-488">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="a109d-489">Решена проблема, из-за которой внутренняя операция вызывала исключение при сбое вместо ведения журнала и продолжения работы.</span><span class="sxs-lookup"><span data-stu-id="a109d-489">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="a109d-490">Для затронутых пользователей будет отменен запрет на получение обновлений.</span><span class="sxs-lookup"><span data-stu-id="a109d-490">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="a109d-491">Это изменение обеспечит правильную работу функции "Контур эскиза" на ленте.</span><span class="sxs-lookup"><span data-stu-id="a109d-491">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="a109d-492">Исправлена проблема при открытии файлов из локальных расположений с определенными настройками прокси.</span><span class="sxs-lookup"><span data-stu-id="a109d-492">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="a109d-493">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="a109d-493">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="a109d-494">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="a109d-494">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="a109d-495">Это обновление устраняет проблему в Microsoft Word, из-за которой текст длиной более 255 символов, вставленный при применении метки конфиденциальности, впоследствии не удавалось идентифицировать и удалить путем изменения или удаления метки, если в рамках политики меток был применен колонтитул или подложка.</span><span class="sxs-lookup"><span data-stu-id="a109d-495">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="a109d-496">Исправлена проблема, благодаря чему устранены сбои во время сеансов передачи Office и повышена надежность работы пользователей.</span><span class="sxs-lookup"><span data-stu-id="a109d-496">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="a109d-497">Это исправление обновляет конечную точку URL-адреса конфигурации усиленной безопасности (ECS).</span><span class="sxs-lookup"><span data-stu-id="a109d-497">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="a109d-498">В результате вызова этой новой конечной точки повышается успешность получения данных из ECS.</span><span class="sxs-lookup"><span data-stu-id="a109d-498">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-april-14"></a><span data-ttu-id="a109d-500">Версия 2002: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="a109d-500">Version 2002: April 14</span></span>
<span data-ttu-id="a109d-501">*Версия 2002 (сборка 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="a109d-501">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="a109d-502">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-502">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="a109d-503">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a109d-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-504">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-504">Excel</span></span>

- <span data-ttu-id="a109d-505">**Введите формулу, которая возвращает несколько значений:** Быстро введите формулу, которая возвращает несколько значений, и они автоматически попадут в соседние ячейки.</span><span class="sxs-lookup"><span data-stu-id="a109d-505">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="a109d-506">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-506">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="a109d-507">**Шесть мощных функций:** Мы добавили шесть новых функций, чтобы увеличить ваши электронные таблицы: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE и RANDARRAY.</span><span class="sxs-lookup"><span data-stu-id="a109d-507">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="a109d-508">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-508">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="a109d-509">**Посмотрите налево, посмотрите направо ... XLOOKUP здесь!:** Ряд за строкой, найдите все, что вам нужно в таблице или диапазоне с XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="a109d-509">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="a109d-510">
  [Подробнее](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="a109d-510">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-512">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-512">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-513">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-513">Excel</span></span>

- <span data-ttu-id="a109d-514">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-514">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="a109d-515">В некоторых случаях при сохранении в виде CSV-файла Excel мог объединять все столбцы в один столбец.</span><span class="sxs-lookup"><span data-stu-id="a109d-515">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="a109d-516">Использование Range.ClearContents для диапазона в защищенном листе могло занимать больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a109d-516">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="a109d-517">Исправлена проблема с масштабированием текста в элементах управления формами при их отображении в режиме предварительного просмотра печати.</span><span class="sxs-lookup"><span data-stu-id="a109d-517">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="a109d-518">Макросы VBA, взаимодействующие с лентой, могут неожиданно запускаться со значением True, присвоенным параметру ScreenUpdating.</span><span class="sxs-lookup"><span data-stu-id="a109d-518">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="a109d-519">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении (заполнение вниз, заполнение в стороны), если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="a109d-519">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="a109d-520">В некоторых случаях в VBA не работал метод Application.Evaluate для определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="a109d-520">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="a109d-521">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="a109d-521">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="a109d-522">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-522">Outlook</span></span>

- <span data-ttu-id="a109d-523">Исправлена проблема, приводившая к неожиданному увеличению заголовка группы в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="a109d-523">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="a109d-524">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при выборе определенных результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="a109d-524">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="a109d-525">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="a109d-525">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="a109d-526">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="a109d-526">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a109d-527">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-527">PowerPoint</span></span>

- <span data-ttu-id="a109d-528">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="a109d-528">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="a109d-529">Project</span><span class="sxs-lookup"><span data-stu-id="a109d-529">Project</span></span>

- <span data-ttu-id="a109d-530">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="a109d-530">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="a109d-531">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="a109d-531">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-532">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-532">Word</span></span>

- <span data-ttu-id="a109d-533">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="a109d-533">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="a109d-534">Исправлена проблема с размещением текста в таблице.</span><span class="sxs-lookup"><span data-stu-id="a109d-534">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="a109d-535">Исправлена проблема, из-за которой вставляемые горизонтальные линии не укорачиваются и не располагаются по центру.</span><span class="sxs-lookup"><span data-stu-id="a109d-535">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-10"></a><span data-ttu-id="a109d-537">Версия 2002: 10 марта</span><span class="sxs-lookup"><span data-stu-id="a109d-537">Version 2002: March 10</span></span>
<span data-ttu-id="a109d-538">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="a109d-538">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="a109d-539">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-539">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a109d-541">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a109d-541">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a109d-542">Access</span><span class="sxs-lookup"><span data-stu-id="a109d-542">Access</span></span>

- <span data-ttu-id="a109d-543">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="a109d-543">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="a109d-544">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-544">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="a109d-545">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-545">Excel</span></span>

- <span data-ttu-id="a109d-546">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="a109d-546">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="a109d-547">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-547">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="a109d-548">\*\*Найдите то, что ищете: \*\*Ищите команды, людей, файлы, фотографии, веб-статьи и многое другое.</span><span class="sxs-lookup"><span data-stu-id="a109d-548">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="a109d-549">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-549">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="a109d-550">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей книге.</span><span class="sxs-lookup"><span data-stu-id="a109d-550">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="a109d-551">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-551">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="a109d-552">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="a109d-552">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="a109d-553">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="a109d-553">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="a109d-554">**Сосредоточьтесь на оставшихся задачах.** Пометьте примечания как разрешенные, чтобы свернуть их и сделать открытые элементы более заметными.</span><span class="sxs-lookup"><span data-stu-id="a109d-554">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="a109d-555">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="a109d-555">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="a109d-556">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-556">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="a109d-557">**Преобразование файлов для расширения специальных возможностей.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="a109d-557">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="a109d-558">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="a109d-558">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="a109d-559">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-559">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="a109d-560">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="a109d-560">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="a109d-561">**Получите статистику в своей книге:** Статистика рабочей книги предоставляет обзор содержимого рабочей книги, чтобы упростить ее обнаружение.</span><span class="sxs-lookup"><span data-stu-id="a109d-561">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="a109d-562">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="a109d-562">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="a109d-563">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="a109d-563">Find them at Insert > Icons.</span></span> [<span data-ttu-id="a109d-564">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-564">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="a109d-565">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-565">Outlook</span></span>

- <span data-ttu-id="a109d-566">**Подключение к сети LinkedIn с помощью Outlook.** Безопасное подключение к учетным записям LinkedIn с помощью учетных записей Майкрософт для просмотра сведений из профилей LinkedIn прямо на карточках контактов.</span><span class="sxs-lookup"><span data-stu-id="a109d-566">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="a109d-567">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-567">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="a109d-p156">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты. [Подробнее](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="a109d-p156">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="a109d-570">\*\*Меню "Вставка ссылки" в Outlook вставляет ссылку с разрешениями, определенными администратором клиента. \*\* При выборе из списка последних использованных ссылок в Outlook вставляется ссылка, которая была доступна только пользователям, имеющим разрешение на доступ к ней.</span><span class="sxs-lookup"><span data-stu-id="a109d-570">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="a109d-571">Из-за этого пользователи часто посылали друг другу письма с просьбой предоставить доступ к документу.</span><span class="sxs-lookup"><span data-stu-id="a109d-571">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="a109d-572">Мы обновили этот опыт, поэтому теперь ссылка вставляется с разрешением по умолчанию, установленным администратором клиента. Для MSIT это «организация может редактировать», поэтому все внутренние пользователи, получившие ссылку, которой поделились таким образом, смогут получить к ней доступ.</span><span class="sxs-lookup"><span data-stu-id="a109d-572">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="a109d-573">**Поиск с правописанием проблем или опечаток:** Outlook найдет то, что вы ищете, даже если ваше правописание не соответствует.</span><span class="sxs-lookup"><span data-stu-id="a109d-573">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="a109d-574">**Фишинговые письма легко обнаружить:** спам и фишинговые сообщения выглядят по-разному, поэтому вы можете легко их идентифицировать и удалить из папки «Входящие».</span><span class="sxs-lookup"><span data-stu-id="a109d-574">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="a109d-575">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="a109d-575">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="a109d-576">**Рисование.** Рисуйте поверх изображений или добавьте полотно, чтобы отправить свои идеи с помощью рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="a109d-576">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="a109d-577">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-577">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="a109d-578">\*\*Получайте релевантные сообщения в результатах поиска. \*\*Outlook анализирует условия поиска и отображает наиболее релевантные сообщения электронной почты в верхней части результатов поиска.</span><span class="sxs-lookup"><span data-stu-id="a109d-578">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="a109d-579">Кроме того, все результаты будут отображаться в разделе "Лучшие результаты" с сортировкой по дате.</span><span class="sxs-lookup"><span data-stu-id="a109d-579">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="a109d-580">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-580">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="a109d-581">**Получение предложений по расположению.** Начните вводить текст в поле "Место" при планировании встреч и собраний, и Outlook предложит помещения, адреса и другие недавние места.</span><span class="sxs-lookup"><span data-stu-id="a109d-581">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="a109d-582">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-582">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="a109d-583">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="a109d-583">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="a109d-584">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-584">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="a109d-585">\*\*Просмотр сообщений в другой освещенности. \*\* Используйте кнопку "СОЛНЦЕ/ЛУНА" для переключения между светлым и темным фоном в области чтения.</span><span class="sxs-lookup"><span data-stu-id="a109d-585">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="a109d-586">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-586">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="a109d-587">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="a109d-587">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="a109d-588">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="a109d-588">Find them at Insert > Icons.</span></span> [<span data-ttu-id="a109d-589">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-589">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="a109d-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-590">PowerPoint</span></span>

- <span data-ttu-id="a109d-591">**Быстрое взаимодействие в реальном времени в PowerPoint:** Быстрое сотрудничество в реальном времени в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-591">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="a109d-592">**Новые средства проверки правописания.** Не переживайте из-за слов.</span><span class="sxs-lookup"><span data-stu-id="a109d-592">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="a109d-593">В PowerPoint теперь отображаются предложения в отношении грамматики и написания.</span><span class="sxs-lookup"><span data-stu-id="a109d-593">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="a109d-594">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-594">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="a109d-595">**Субтитры в реальном времени.** Слова докладчика автоматически отображаются на экране в виде субтитров или переводятся в субтитры на выбранном языке.</span><span class="sxs-lookup"><span data-stu-id="a109d-595">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="a109d-596">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-596">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="a109d-p166">**Вы вычисляете, мы форматируем.** Рукописные математические выражения преобразуются в стандартные знаки. Просто воспользуйтесь функцией "Рукописный фрагмент в математические символы" и выберите рукописные примечания для начала работы. [Подробнее](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="a109d-p166">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="a109d-600">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="a109d-600">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="a109d-601">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-601">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="a109d-602">**Поиск и исправление пропущенных названий слайдов:** Названия слайдов добавляют удар к вашей подаче и делают ваши слайды доступными для пользователей всех способностей.</span><span class="sxs-lookup"><span data-stu-id="a109d-602">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="a109d-603">С помощью средства проверки читаемости можно определить, где отсутствуют заголовки, и сразу же добавить их.</span><span class="sxs-lookup"><span data-stu-id="a109d-603">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="a109d-604">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-604">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="a109d-605">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своей презентации.</span><span class="sxs-lookup"><span data-stu-id="a109d-605">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="a109d-606">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-606">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="a109d-607">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="a109d-607">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="a109d-608">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="a109d-608">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="a109d-609">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="a109d-609">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="a109d-610">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-610">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="a109d-611">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="a109d-611">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="a109d-612">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="a109d-612">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="a109d-613">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-613">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="a109d-614">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="a109d-614">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="a109d-615">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-615">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="a109d-616">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="a109d-616">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="a109d-617">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="a109d-617">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="a109d-618">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="a109d-618">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="a109d-619">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="a109d-619">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="a109d-620">**Зачем изобретать заново, если вы можете использовать повторно ?:** Экономьте время, повторно используя слайды, которые вы создали или которыми другие поделились с вами.</span><span class="sxs-lookup"><span data-stu-id="a109d-620">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="a109d-621">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-621">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="a109d-622">**Измените рукописные чернила на фигуры, текст или математику в PowerPoint для Office 365:** Перейдите от чернил произвольной формы к фигурам, тексту или математическому выражению Office за пару движений.</span><span class="sxs-lookup"><span data-stu-id="a109d-622">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="a109d-623">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-623">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="a109d-624">**Рукописный ввод для создания отличного слайда.** Преобразуйте рукописный ввод в стандартные фигуры и текст, а затем находите изящные идеи оформления слайдов в конструкторе PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-624">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="a109d-625">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-625">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="a109d-626">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="a109d-626">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="a109d-627">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="a109d-627">Find them at Insert > Icons.</span></span> [<span data-ttu-id="a109d-628">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-628">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="a109d-629">Visio</span><span class="sxs-lookup"><span data-stu-id="a109d-629">Visio</span></span>

- <span data-ttu-id="a109d-630">**В сценах преступления:** Используйте новые трафареты «Доказательства», «В помещении» и «На улице» в шаблоне «Расследование места преступления», чтобы детально воссоздать места преступления.</span><span class="sxs-lookup"><span data-stu-id="a109d-630">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="a109d-631">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="a109d-631">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="a109d-632">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-632">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="a109d-633">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-633">Word</span></span>

- <span data-ttu-id="a109d-634">**Редактор для резюме присоединяется к LinkedIn Resume Assistant:** редактор для резюме предлагает выбор грамматических и стилевых проверок, специально предназначенных для резюме, чтобы сделать ваше письмо более точным и профессиональным.</span><span class="sxs-lookup"><span data-stu-id="a109d-634">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="a109d-635">**Исправление проблемы с повреждением документа при объединении 3D объектов.** Исправлена проблема с повреждением документа, возникавшая при объединении 3D объектов.</span><span class="sxs-lookup"><span data-stu-id="a109d-635">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="a109d-636">**Найдите то, что вы ищете:** используйте окно поиска, чтобы найти текст, команды, помощь и многое другое.</span><span class="sxs-lookup"><span data-stu-id="a109d-636">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="a109d-637">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-637">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="a109d-638">**Сотрудничайте в живом цвете:** комментарии и изменения имеют цветовую кодировку от участника, поэтому легко увидеть, кто есть кто среди ваших соавторов.</span><span class="sxs-lookup"><span data-stu-id="a109d-638">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="a109d-639">**Совместное редактирование документов с поддержкой макросов:** сохраняйте файлы документов в OneDrive для бизнеса и редактируйте их вместе с соавторами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="a109d-639">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="a109d-640">**Улучшенные возможности совместного редактирования**. Улучшено быстродействие Word при совместном редактировании в документах с отслеживанием исправлений.</span><span class="sxs-lookup"><span data-stu-id="a109d-640">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="a109d-641">\*\*Больше иконок в соответствии с вашим настроением: \*\*мы добавили более 300 новых иконок.</span><span class="sxs-lookup"><span data-stu-id="a109d-641">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="a109d-642">Их можно найти, выбрав элементы "Вставка" > "Значки".</span><span class="sxs-lookup"><span data-stu-id="a109d-642">Find them at Insert > Icons.</span></span> [<span data-ttu-id="a109d-643">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-643">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="a109d-644">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="a109d-644">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="a109d-645">**Стиль наброска.** Применяйте свободное оформление в виде наброска от руки к фигурам Office в своем документе.</span><span class="sxs-lookup"><span data-stu-id="a109d-645">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="a109d-646">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-646">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="a109d-647">**Точное стирание.** Выберите один из двух размеров ластика, чтобы исправить небольшие недочеты рукописных фрагментов.</span><span class="sxs-lookup"><span data-stu-id="a109d-647">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="a109d-648">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-648">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="a109d-649">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="a109d-649">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="a109d-650">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="a109d-650">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="a109d-651">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-651">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="a109d-652">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="a109d-652">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="a109d-653">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="a109d-653">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="a109d-654">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-654">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="a109d-655">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="a109d-655">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="a109d-656">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="a109d-656">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="a109d-657">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a109d-657">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-660">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-660">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a109d-661">Доступ</span><span class="sxs-lookup"><span data-stu-id="a109d-661">Access</span></span>

- <span data-ttu-id="a109d-662">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке "Запрос поврежден" при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="a109d-662">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="a109d-663">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="a109d-663">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="a109d-664">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="a109d-664">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a109d-665">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="a109d-665">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a109d-666">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="a109d-666">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="a109d-667">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="a109d-667">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="a109d-668">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-668">Excel</span></span>

- <span data-ttu-id="a109d-669">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="a109d-669">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="a109d-670">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="a109d-670">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="a109d-671">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="a109d-671">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="a109d-672">Это обновление устраняет проблему, из-за которой на панели формул текст отображался шрифтом, отличным от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="a109d-672">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="a109d-673">Функциональность Text to Column может не работать в некоторых локациях.</span><span class="sxs-lookup"><span data-stu-id="a109d-673">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="a109d-674">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="a109d-674">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="a109d-675">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="a109d-675">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="a109d-676">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="a109d-676">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="a109d-677">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="a109d-677">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="a109d-678">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="a109d-678">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="a109d-679">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="a109d-679">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="a109d-680">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="a109d-680">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="a109d-681">Исправлена проблема, которая могла возникнуть у некоторых пользователей со встроенными и связанными объектами (OLE).</span><span class="sxs-lookup"><span data-stu-id="a109d-681">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="a109d-682">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="a109d-682">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="a109d-683">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="a109d-683">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="a109d-684">Исправлена ошибка, из-за которой некоторые пользователи могли сталкиваться с несколькими всплывающими окнами при наличии внешних ссылок в книге.</span><span class="sxs-lookup"><span data-stu-id="a109d-684">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="a109d-685">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="a109d-685">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="a109d-686">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="a109d-686">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="a109d-687">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="a109d-687">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-688">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-688">Outlook</span></span>

- <span data-ttu-id="a109d-689">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="a109d-689">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="a109d-690">Исправлена проблема, приводившая к зависаниям у пользователей в Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="a109d-690">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="a109d-691">Устранена проблема, которая приводила к неправильному выравниванию поля поиска в режиме высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="a109d-691">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="a109d-692">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="a109d-692">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="a109d-693">Исправлена проблема, из-за которой пользователи иногда наблюдали отправку сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="a109d-693">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="a109d-694">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="a109d-694">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="a109d-695">Исправлена проблема, которая не позволяла сохранять файлы в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="a109d-695">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="a109d-696">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="a109d-696">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="a109d-697">Устранена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="a109d-697">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="a109d-698">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="a109d-698">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="a109d-699">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="a109d-699">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="a109d-700">Устранена проблема, из-за которой Outlook неожиданно синхронизировал всю почту, даже если для ползунка синхронизации установлено меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="a109d-700">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="a109d-701">Исправлена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке "От" отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="a109d-701">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="a109d-702">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="a109d-702">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="a109d-703">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="a109d-703">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="a109d-704">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="a109d-704">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="a109d-705">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="a109d-705">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="a109d-706">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="a109d-706">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="a109d-707">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="a109d-707">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="a109d-708">Устранена проблема, которая могла привести к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="a109d-708">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="a109d-709">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="a109d-709">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="a109d-710">Исправлена проблема, из-за которой пользователи не могли открывать некоторые вхождения повторяющихся элементов календаря.</span><span class="sxs-lookup"><span data-stu-id="a109d-710">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="a109d-711">Устранена проблема, из-за которой у пользователей с почтовыми ящиками на серверах Exchange 2010 возникали проблемы при добавлении вложений в элементы календаря.</span><span class="sxs-lookup"><span data-stu-id="a109d-711">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="a109d-712">Устранена проблема, из-за которой у пользователей возникали проблемы при ответе на сообщения с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="a109d-712">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="a109d-713">Исправлена проблема, из-за которой неожиданно обновлялось поле расположения в собраниях.</span><span class="sxs-lookup"><span data-stu-id="a109d-713">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="a109d-714">Устранена проблема, из-за которой запятые в поле местоположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="a109d-714">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="a109d-715">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="a109d-715">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="a109d-716">Решены вопросы, связанные со встречами и встречами, установленными в часовом поясе Бразилии.</span><span class="sxs-lookup"><span data-stu-id="a109d-716">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="a109d-717">Устранена проблема, из-за которой сообщения неожиданно отправлялись при нажатии клавиши "S" после закрытия панели проверки читаемости.</span><span class="sxs-lookup"><span data-stu-id="a109d-717">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="a109d-718">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="a109d-718">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="a109d-719">Устранена проблема, из-за которой веб-надстройки обращались к сообщениям, управляемым цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="a109d-719">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="a109d-720">Исправлена проблема, из-за которой пользователи сталкивались со сбоем при создании профиля.</span><span class="sxs-lookup"><span data-stu-id="a109d-720">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="a109d-721">Устранена проблема, из-за которой у пользователей возникали сбои при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="a109d-721">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a109d-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-722">PowerPoint</span></span>

- <span data-ttu-id="a109d-723">Мы исправили проблему с методом Shape.Paste: когда пользователь копирует и вставляет фигуру с помощью метода Shape.Paste, он меняет выделение на вставленную фигуру.</span><span class="sxs-lookup"><span data-stu-id="a109d-723">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="a109d-724">Устранена проблема, которая могла вызвать сбой при использовании контекстного меню в устаревших комментариях PPT.</span><span class="sxs-lookup"><span data-stu-id="a109d-724">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="a109d-725">Project</span><span class="sxs-lookup"><span data-stu-id="a109d-725">Project</span></span>

- <span data-ttu-id="a109d-726">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="a109d-726">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="a109d-727">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="a109d-727">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="a109d-728">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="a109d-728">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="a109d-729">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="a109d-729">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-730">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-730">Word</span></span>

- <span data-ttu-id="a109d-731">Мы исправили проблему, при которой в некоторых случаях сохранение существующего файла всегда вызывает диалоговое окно «Сохранить как», а файл фактически не сохраняется.</span><span class="sxs-lookup"><span data-stu-id="a109d-731">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="a109d-732">Диспетчер стандартных блоков может отображать неправильное оповещение: "Были изменены стили, стандартные блоки".</span><span class="sxs-lookup"><span data-stu-id="a109d-732">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-733">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-733">Office Suite</span></span>

- <span data-ttu-id="a109d-734">Это изменение касается медленного рендеринга некоторых точечных диаграмм с маркерами.</span><span class="sxs-lookup"><span data-stu-id="a109d-734">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="a109d-735">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="a109d-735">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="a109d-736">Исправлена ошибка в настройке ODT и крайнего срока обновления GPO, когда относительный крайний срок работает только при первом его включении, исправление включает относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="a109d-736">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="a109d-737">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="a109d-737">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="a109d-738">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="a109d-738">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-11"></a><span data-ttu-id="a109d-740">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="a109d-740">Version 1908: February 11</span></span>
<span data-ttu-id="a109d-741">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="a109d-741">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="a109d-742">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-742">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-744">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-744">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-745">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-745">Excel</span></span>

- <span data-ttu-id="a109d-746">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="a109d-746">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="a109d-747">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="a109d-747">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="a109d-748">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="a109d-748">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="a109d-749">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="a109d-749">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="a109d-750">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="a109d-750">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="a109d-751">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="a109d-751">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="a109d-752">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-752">Outlook</span></span>

- <span data-ttu-id="a109d-753">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="a109d-753">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="a109d-754">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="a109d-754">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="a109d-755">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="a109d-755">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="a109d-756">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="a109d-756">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="a109d-757">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="a109d-757">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="a109d-758">[Здесь](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="a109d-758">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="a109d-759">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="a109d-759">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a109d-760">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-760">PowerPoint</span></span>

- <span data-ttu-id="a109d-761">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="a109d-761">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="a109d-762">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="a109d-762">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="a109d-763">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="a109d-763">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="a109d-764">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a109d-764">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="a109d-765">Project</span><span class="sxs-lookup"><span data-stu-id="a109d-765">Project</span></span>

- <span data-ttu-id="a109d-766">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="a109d-766">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="a109d-767">Word</span><span class="sxs-lookup"><span data-stu-id="a109d-767">Word</span></span>

- <span data-ttu-id="a109d-768">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="a109d-768">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-769">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-769">Office Suite</span></span>

- <span data-ttu-id="a109d-770">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="a109d-770">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="a109d-772">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="a109d-772">Version 1908: January 14</span></span>
<span data-ttu-id="a109d-773">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="a109d-773">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="a109d-774">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="a109d-774">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a109d-776">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a109d-776">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a109d-777">Excel</span><span class="sxs-lookup"><span data-stu-id="a109d-777">Excel</span></span>

- <span data-ttu-id="a109d-778">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="a109d-778">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="a109d-779">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="a109d-779">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="a109d-780">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытой надстройкой.</span><span class="sxs-lookup"><span data-stu-id="a109d-780">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="a109d-781">Outlook</span><span class="sxs-lookup"><span data-stu-id="a109d-781">Outlook</span></span>

- <span data-ttu-id="a109d-782">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="a109d-782">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="a109d-783">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="a109d-783">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="a109d-784">Исправлена проблема, вызывавшая у пользователей периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="a109d-784">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a109d-785">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a109d-785">PowerPoint</span></span>

- <span data-ttu-id="a109d-786">Исправлена проблема, из-за которой копирование слайда из одной презентации в другую могло создавать дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="a109d-786">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="a109d-787">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="a109d-787">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="a109d-788">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a109d-788">Office Suite</span></span>

- <span data-ttu-id="a109d-789">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="a109d-789">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="a109d-790">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="a109d-790">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="a109d-791">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="a109d-791">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="a109d-793">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="a109d-793">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
