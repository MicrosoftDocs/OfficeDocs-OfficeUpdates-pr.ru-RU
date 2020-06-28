---
title: Заметки о выпуске для канала бета-версии
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с ранним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: 55d62bf10375c72a09f93369c20f7f5b6d1b963f
ms.sourcegitcommit: f9bf47d0d27e084205311ab6e844d044da83f252
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/26/2020
ms.locfileid: "44906914"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="a3d30-103">Заметки о выпуске для канала бета-версии</span><span class="sxs-lookup"><span data-stu-id="a3d30-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="a3d30-104">В этой статье содержатся заметки о выпусках для бета-версий маркетинговых сборок для настольных систем Word, Excel, PowerPoint, Outlook, Access и Project для Windows.</span><span class="sxs-lookup"><span data-stu-id="a3d30-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a3d30-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="a3d30-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a3d30-106">Обратите внимание, что мы часто выгрузим компоненты бета-версии (а иногда и даже исправления) на канал бета-версии в течение определенного периода времени.</span><span class="sxs-lookup"><span data-stu-id="a3d30-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="a3d30-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="a3d30-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a3d30-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="a3d30-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="a3d30-109">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (ежемесячный корпоративный канал) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="a3d30-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a3d30-110">Подробнее см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="a3d30-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="a3d30-111">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок.</span><span class="sxs-lookup"><span data-stu-id="a3d30-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="a3d30-112">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="a3d30-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2007-june-26"></a><span data-ttu-id="a3d30-115">Версия 2007:26 июня</span><span class="sxs-lookup"><span data-stu-id="a3d30-115">Version 2007: June 26</span></span>
<span data-ttu-id="a3d30-116">*Версия 2007 (сборка 13020,20004)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-116">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-118">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-118">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a3d30-119">Access</span><span class="sxs-lookup"><span data-stu-id="a3d30-119">Access</span></span>

- <span data-ttu-id="a3d30-120">Исправлена ошибка, в результате которой диспетчер связанных таблиц запрашивает первичный ключ при обновлении связанной таблицы SQL.</span><span class="sxs-lookup"><span data-stu-id="a3d30-120">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="a3d30-121">Исправлена ошибка, из – за которой запросы в редакторе запросов прокручены из области просмотра.</span><span class="sxs-lookup"><span data-stu-id="a3d30-121">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="a3d30-122">Мы выполнили устранение неполадок, в результате которых выполнение запроса заняло примерно вдвое больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a3d30-122">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-123">Outlook</span></span>

- <span data-ttu-id="a3d30-124">Исправлена ошибка, из – за которой пользователям не удалось отправить сообщение "Отправить как" или "Отправить от имени" в списке рассылки.</span><span class="sxs-lookup"><span data-stu-id="a3d30-124">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="a3d30-125">Исправлена ошибка, в результате которой вставляется изображение в сообщении, а затем при сохранении сообщения в качестве черновика будет изменен размер изображения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-125">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="a3d30-126">Мы выполнили Устранение ошибки, которая привела к изменению текста сообщения отчета о недоставке в формат ASCII после редактирования темы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-126">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-127">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-127">Project</span></span>

- <span data-ttu-id="a3d30-128">Исправлена ошибка, из – за которой в облачных средах сообщества сообщества были отключены ссылки на планировщик проекта.</span><span class="sxs-lookup"><span data-stu-id="a3d30-128">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-129">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-129">Office Suite</span></span>

- <span data-ttu-id="a3d30-130">Исправлена ошибка, из-за которой текст, вставленный в масштабируемый векторный графический объект (SVG), был иллегибле после вставки в файл Word, Excel или PowerPoint, сохраненный и закрывающий файл, а затем повторно открыт файл.</span><span class="sxs-lookup"><span data-stu-id="a3d30-130">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-19"></a><span data-ttu-id="a3d30-132">Версия 2007:19 июня</span><span class="sxs-lookup"><span data-stu-id="a3d30-132">Version 2007: June 19</span></span>
<span data-ttu-id="a3d30-133">*Версия 2007 (сборка 13012,20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-133">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-135">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-136">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-136">Excel</span></span>

- <span data-ttu-id="a3d30-137">Исправлена ошибка, из-за которой при сохранении книги в SharePoint или OneDrive была удалена пользовательская вкладка ленты.</span><span class="sxs-lookup"><span data-stu-id="a3d30-137">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="a3d30-138">Исправлена ошибка, из-за которой книги были доступны только для чтения, только если файл имеет доступ только для чтения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-138">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-139">Outlook</span></span>

- <span data-ttu-id="a3d30-140">Исправлена ошибка, из-за которой окно редактора метода ввода (IME) перекроет основной текст, вводимый с помощью IME при использовании нескольких мониторов с разными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="a3d30-140">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="a3d30-141">Исправлена ошибка, из-за которой пользователи могут увидеть следующую ошибку при закрытии ранее сохраненной встречи: "не удается сохранить элемент, так как он был изменен другим пользователем или в другом окне.</span><span class="sxs-lookup"><span data-stu-id="a3d30-141">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="a3d30-142">Вы хотите создать копию в папке по умолчанию для элемента? "</span><span class="sxs-lookup"><span data-stu-id="a3d30-142">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="a3d30-143">Исправлена ошибка, из-за которой не удалось отобразить даты в мини-календаре полужирным шрифтом для пользователей в Японии.</span><span class="sxs-lookup"><span data-stu-id="a3d30-143">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="a3d30-144">Мы выполнили устранение неполадок, которые не позволили напоминаниям календаря отобразить точное время для собраний, которые поступают менее чем за неделю.</span><span class="sxs-lookup"><span data-stu-id="a3d30-144">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-145">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-145">PowerPoint</span></span>

- <span data-ttu-id="a3d30-146">Исправлена ошибка, в результате которой во время совместного сеанса совместной работы не обновлялся индикатор цвета присутствия пользователя в коллекции совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="a3d30-146">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-147">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-147">Project</span></span>

- <span data-ttu-id="a3d30-148">Исправлена ошибка, из-за которой при фиксированной длительности в 100% завершено, но фактическое окончание не указано, для задачи% завершения отображается значение меньше 100%.</span><span class="sxs-lookup"><span data-stu-id="a3d30-148">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-149">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-149">Word</span></span>

- <span data-ttu-id="a3d30-150">Исправлена ошибка, из-за которой не был правильно отображен цвет HTML-гиперссылки.</span><span class="sxs-lookup"><span data-stu-id="a3d30-150">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-151">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-151">Office Suite</span></span>

- <span data-ttu-id="a3d30-152">Исправлена ошибка, из-за которой URL-адреса, которые не использовали протокол HTTP или HTTPS, не отображались в списке последних использованных.</span><span class="sxs-lookup"><span data-stu-id="a3d30-152">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-12"></a><span data-ttu-id="a3d30-154">Версия 2007:12 июня</span><span class="sxs-lookup"><span data-stu-id="a3d30-154">Version 2007: June 12</span></span>
<span data-ttu-id="a3d30-155">*Версия 2007 (сборка 13006,20002)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-155">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-157">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-157">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-158">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-158">Excel</span></span>

- <span data-ttu-id="a3d30-159">**Получение данных Организации из Power BI с использованием типов данных:** Теперь типы данных Excel из Power BI развертываются в организациях с Office 365 в ~/A5 или с помощью Microsoft 365 "A5/A5".</span><span class="sxs-lookup"><span data-stu-id="a3d30-159">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="a3d30-160">Получить необходимую информацию и легко обновлять ее очень важно для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="a3d30-160">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="a3d30-161">Мы предоставляем вам доступ к информации о компании или организации из Power BI как типа данных в Excel, что расширяет возможности по внедрению связанных данных в электронные таблицы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-161">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="a3d30-162">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-162">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="a3d30-163">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="a3d30-163">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-166">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-166">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a3d30-167">Access</span><span class="sxs-lookup"><span data-stu-id="a3d30-167">Access</span></span>

- <span data-ttu-id="a3d30-168">Исправлена ошибка, из — за которой Microsoft Access не удалось определить столбец идентификаторов в связанной таблице SQL Server, что может привести к неправильному удалению строк.</span><span class="sxs-lookup"><span data-stu-id="a3d30-168">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-169">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-169">Excel</span></span>

- <span data-ttu-id="a3d30-170">Исправлена ошибка, из – за которой не удалось правильно отформатировать основные линии сетки лепестковой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-170">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-171">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-171">Project</span></span>

- <span data-ttu-id="a3d30-172">Исправлена ошибка, из-за которой событие Прожектбефоретаскчанже не вызвано при изменении суммарной задачи проекта, либо в поле Начало проекта, либо в поле задачи.</span><span class="sxs-lookup"><span data-stu-id="a3d30-172">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="a3d30-173">Исправлена ошибка, из-за которой запланированный сброс или обновление могут изменить повременные бюджетные затраты/трудозатраты, а базовый план может отражать неправильные значения бюджета.</span><span class="sxs-lookup"><span data-stu-id="a3d30-173">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-174">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-174">Word</span></span>

- <span data-ttu-id="a3d30-175">Исправлена ошибка, из – за которой не работает возможность очистить форматирование в области примечаний с помощью кнопки Очистить форматирование на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="a3d30-175">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="a3d30-176">Исправлена ошибка, из-за которой изменение размера таблицы, когда линейка не отображается, привела к тому, что другие приложения, работающие в фоновом режиме, начинают мигать.</span><span class="sxs-lookup"><span data-stu-id="a3d30-176">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="a3d30-177">Исправлена ошибка, в результате которой в режиме совместного редактирования ответы на комментарии иногда не отображаются в области примечаний, но отображаются в области исправлений.</span><span class="sxs-lookup"><span data-stu-id="a3d30-177">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="a3d30-178">Исправлена ошибка, в результате которой в Word имелся список из более 50 часто открытых документов, а затем после сохранения и открытия документа отображается журнал изменений, несмотря на то, что в этот документ не было внесено никаких изменений.</span><span class="sxs-lookup"><span data-stu-id="a3d30-178">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-05"></a><span data-ttu-id="a3d30-180">Версия 2006: Июнь 05</span><span class="sxs-lookup"><span data-stu-id="a3d30-180">Version 2006: June 05</span></span>
<span data-ttu-id="a3d30-181">*Версия 2006 (сборка 13001,20002)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-181">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-183">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-183">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-184">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-184">Excel</span></span>

- <span data-ttu-id="a3d30-185">**Сортировка и фильтрация при работе в Excel:** Теперь вы можете сортировать и фильтровать файл Excel при совместной работе с другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="a3d30-185">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="a3d30-186">Эта новая функция предотвращает влияние других пользователей на сортировку и фильтры при совместном редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="a3d30-186">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="a3d30-187">**Создание сводных таблиц из наборов данных в Power BI в Excel:** Вы можете создавать сводные таблицы в Excel, которые подключены к наборам данных, хранящимся в Power BI, с несколькими щелчками мышью.</span><span class="sxs-lookup"><span data-stu-id="a3d30-187">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="a3d30-188">Это позволяет получить лучшие из сводных таблиц и Power BI.</span><span class="sxs-lookup"><span data-stu-id="a3d30-188"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="a3d30-189">Расчет, сведение и анализ данных со сводными таблицами из наборов данных безопасного Power BI.</span><span class="sxs-lookup"><span data-stu-id="a3d30-189">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="a3d30-190">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-190">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="a3d30-191">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-191">Outlook</span></span>

- <span data-ttu-id="a3d30-192">**Быстрое повторное открытие элементов из предыдущего сеанса:** Мы добавили возможность быстрого повторного открытия элементов из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="a3d30-192">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="a3d30-193">Независимо от того, удается ли Outlook завершить работу или закрыть его, вы можете быстро перезапустить элементы при повторном открытии приложения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-193">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="a3d30-194">По умолчанию эта функция включена.</span><span class="sxs-lookup"><span data-stu-id="a3d30-194">This feature is on by default.</span></span> <span data-ttu-id="a3d30-195">Чтобы отключить этот параметр, перейдите в раздел Параметры > общие > запусков.</span><span class="sxs-lookup"><span data-stu-id="a3d30-195">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-198">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-199">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-199">Excel</span></span>

- <span data-ttu-id="a3d30-200">Исправлена ошибка, в результате которой настраиваемые значения на оси диаграммы не были применены правильно.</span><span class="sxs-lookup"><span data-stu-id="a3d30-200">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="a3d30-201">Исправлена ошибка, в результате которой листы, содержащие несколько формул с заданными именами, были длительное время при сохранении файлов.</span><span class="sxs-lookup"><span data-stu-id="a3d30-201">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-202">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-202">Outlook</span></span>

- <span data-ttu-id="a3d30-203">Исправлена ошибка, из-за которой окно IME (редактор способов ввода) перекроет основной текст, вводимый с помощью IME при использовании нескольких мониторов с разными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="a3d30-203">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="a3d30-204">Исправлена ошибка, в результате которой при создании нового сообщения электронной почты произойдет сбой.</span><span class="sxs-lookup"><span data-stu-id="a3d30-204">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="a3d30-205">Исправлена ошибка, в результате которой пользователи не могли получить доступ к общедоступным папкам 2010 после Outlook версии 1911.</span><span class="sxs-lookup"><span data-stu-id="a3d30-205">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="a3d30-206">Исправлена ошибка, из – за которой в ленте Office отключена кнопка категории для календарей группировки.</span><span class="sxs-lookup"><span data-stu-id="a3d30-206">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="a3d30-207">Исправлена ошибка, из — за которой пользователи с конфликтующими контактами могут столкнуться со сбоями в Outlook.</span><span class="sxs-lookup"><span data-stu-id="a3d30-207">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="a3d30-208">Исправлена ошибка, которая привела к раскрывающимся меню "Интернет-Архив" в свойствах папки для пользователей на мониторах с высоким разрешением.</span><span class="sxs-lookup"><span data-stu-id="a3d30-208">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="a3d30-209">Мы выполнили устранение неполадок, которые приводили к сбою в Outlook при работе с гиперссылками в формате обычного текста.</span><span class="sxs-lookup"><span data-stu-id="a3d30-209">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="a3d30-210">Исправлена ошибка, из – за которой Outlook не удалось выполнить синтаксический анализ длинных имен файлов, закодированных с помощью RFC2231.</span><span class="sxs-lookup"><span data-stu-id="a3d30-210">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="a3d30-211">Мы выполнили устранение неполадок, которые приводили к тому, что при использовании средств чтения с экрана пользователи Outlook испытывают периодические зависания.</span><span class="sxs-lookup"><span data-stu-id="a3d30-211">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-212">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-212">PowerPoint</span></span>

- <span data-ttu-id="a3d30-213">Исправлена ошибка, связанная с открытием файлов, настроенных на сервере, с проверкой подлинности на основе форм.</span><span class="sxs-lookup"><span data-stu-id="a3d30-213">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="a3d30-214">Исправлена ошибка, из-за которой файлы PowerPoint с внедренными диаграммами и книгами могут привести к сбоям при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-214">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="a3d30-215">Исправлена ошибка, в результате которой область примечаний, закрытая пользователем, будет повторно открыта автоматически.</span><span class="sxs-lookup"><span data-stu-id="a3d30-215">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="a3d30-216">Исправлена ошибка, в результате которой редактор слайдов из одного слайда может пересекаться со следующим слайдом.</span><span class="sxs-lookup"><span data-stu-id="a3d30-216">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-217">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-217">Project</span></span>

- <span data-ttu-id="a3d30-218">Мы выполнили устранение неполадок, которые не позволили удалить или повторно назначить потерянные задачи после удаления родительского плана.</span><span class="sxs-lookup"><span data-stu-id="a3d30-218">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-219">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-219">Word</span></span>

- <span data-ttu-id="a3d30-220">Исправлена ошибка, в которой метки времени в панелях комментариев не основаны времени национальной настройки системы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-220">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="a3d30-221">Исправлена ошибка, из-за которой комментарии между веб-приложением и настольным приложением не синхронизированы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-221">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version2006may29"></a><span data-ttu-id="a3d30-223">Версия 2006:29 мая</span><span class="sxs-lookup"><span data-stu-id="a3d30-223">Version 2006: May 29</span></span>
<span data-ttu-id="a3d30-224">*Версия 2006 (сборка 12920,20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-224">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="a3d30-225">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-225">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-226">Outlook</span></span>

- <span data-ttu-id="a3d30-227">**Дополнительные кнопки, добавленные в всплывающие уведомления Outlook:** Кнопки быстрого действия теперь отображаются в всплывающих уведомлениях Outlook при запуске Outlook в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a3d30-227">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-228">PowerPoint</span></span>

- <span data-ttu-id="a3d30-229">**Улучшенная производительность потокового видео в PowerPoint:** Мы внесли улучшения в производительность воспроизведения видеороликов, чтобы свести к минимуму время загрузки видео и создать плавный просмотр.</span><span class="sxs-lookup"><span data-stu-id="a3d30-229">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="a3d30-230">Используйте свои корпоративные видео из Microsoft Stream, чтобы создавать более совершенные презентации.</span><span class="sxs-lookup"><span data-stu-id="a3d30-230">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolvedissues"></a><span data-ttu-id="a3d30-233">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-233">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-234">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-234">Excel</span></span>

- <span data-ttu-id="a3d30-235">Исправлена ошибка, в результате которой приложение Excel иногда завершает работу при создании OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a3d30-235">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="a3d30-236">Исправлена ошибка, в результате которой при нажатии гиперссылки в рамках одной книги книга будет скрыта.</span><span class="sxs-lookup"><span data-stu-id="a3d30-236">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="a3d30-237">Исправлена ошибка, в связи с которой некоторые копии и вставленные связи с диаграммами используют сопоставленные адреса, а не универсальные адреса.</span><span class="sxs-lookup"><span data-stu-id="a3d30-237">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="a3d30-238">Исправлена ошибка, из – за которой при нажатии клавиш CTRL + SHIFT + клавиша со стрелками выполняется прокрутка, когда окно Excel было предоставлено в Teams.</span><span class="sxs-lookup"><span data-stu-id="a3d30-238">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-239">PowerPoint</span></span>

- <span data-ttu-id="a3d30-240">Исправлена ошибка, в результате которой слайды не были центрированы после масштабирования с помощью колесика мыши.</span><span class="sxs-lookup"><span data-stu-id="a3d30-240">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-241">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-241">Word</span></span>

- <span data-ttu-id="a3d30-242">Исправлена ошибка, из – за которой не отображается копирование и вставку текста в область примечаний.</span><span class="sxs-lookup"><span data-stu-id="a3d30-242">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="a3d30-243">Исправлена ошибка, из – за которой подсказка с комментарием появлялась размытием при масштабе 100%.</span><span class="sxs-lookup"><span data-stu-id="a3d30-243">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="a3d30-244">Исправлена ошибка, в результате которой Word 2007 и более поздние двоичные документы и шаблоны могут привести к сбою некоторых совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="a3d30-244">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="a3d30-245">Исправлена ошибка, из-за которой файлы с длинными именами путей (более 32 КБ) не будут открываться, а соответствующее сообщение об ошибке не отображалось.</span><span class="sxs-lookup"><span data-stu-id="a3d30-245">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="a3d30-246">Версия 2006:22 мая</span><span class="sxs-lookup"><span data-stu-id="a3d30-246">Version 2006: May 22</span></span>
<span data-ttu-id="a3d30-247">*Версия 2006 (сборка 12914,20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-247">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-249">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-249">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-250">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-250">Excel</span></span>

- <span data-ttu-id="a3d30-251">**Сохранить в закрепленных папках:** Закрепление папок упрощает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="a3d30-251">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a3d30-252">Мы получили отзыв о том, что пользователям нужен больший контроль над папками, доступными при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-252">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a3d30-253">Мы очень рады новым возможностям: закрепите папки в диалоговом окне сохранения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-253">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a3d30-254">Эта новая возможность позволит упростить сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-254">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a3d30-255">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a3d30-255">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-256">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-256">PowerPoint</span></span>

- <span data-ttu-id="a3d30-257">**Сохранить в закрепленных папках:** Закрепление папок упрощает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="a3d30-257">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a3d30-258">Мы получили отзыв о том, что пользователям нужен больший контроль над папками, доступными при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-258">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a3d30-259">Мы очень рады новым возможностям: закрепите папки в диалоговом окне сохранения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-259">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a3d30-260">Эта новая возможность позволит упростить сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-260">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a3d30-261">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a3d30-261">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-262">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-262">Word</span></span>

- <span data-ttu-id="a3d30-263">**Сохранить в закрепленных папках:** Закрепление папок упрощает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="a3d30-263">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a3d30-264">Мы получили отзыв о том, что пользователям нужен больший контроль над папками, доступными при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-264">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a3d30-265">Мы очень рады новым возможностям: закрепите папки в диалоговом окне сохранения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-265">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a3d30-266">Эта новая возможность позволит упростить сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-266">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a3d30-267">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a3d30-267">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-270">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-270">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-271">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-271">Excel</span></span>

- <span data-ttu-id="a3d30-272">Устранена проблема, из-за которой сообщение об ошибке: "Эта книга в данный момент ссылается на эту книгу и не может быть закрыта", так как надстройки загружались в алфавитном порядке, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="a3d30-272">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="a3d30-273">Исправлена ошибка, из – за которой повреждение памяти при управлении шрифтами между Excel и другими технологическими приложениями сторонних производителей.</span><span class="sxs-lookup"><span data-stu-id="a3d30-273">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="a3d30-274">Исправлена ошибка, из – за которой при запросе надстройки в надстройках запрашиваются ведущие элементы на листах, содержащих фигуры с блокировками с параметром "Select".</span><span class="sxs-lookup"><span data-stu-id="a3d30-274">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-275">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-275">Outlook</span></span>

- <span data-ttu-id="a3d30-276">Исправлена ошибка, из – за которой событие Folder. Бефореитеммове не было вызвано при перемещении пользователем элементов между папками.</span><span class="sxs-lookup"><span data-stu-id="a3d30-276">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="a3d30-277">Исправлена ошибка, в результате которой пользователи видели элементы календаря, в которых пороговое пороговое значение задается как события на целый день.</span><span class="sxs-lookup"><span data-stu-id="a3d30-277">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="a3d30-278">Устранена ошибка, из – за которой в Outlook произошел сбой, когда две надстройки добавили кнопку в ту же группу на ленте.</span><span class="sxs-lookup"><span data-stu-id="a3d30-278">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="a3d30-279">Исправлена ошибка, в результате которой пользователи не могут предоставить общий доступ к календарю пользователю гостя.</span><span class="sxs-lookup"><span data-stu-id="a3d30-279">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-280">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-280">PowerPoint</span></span>

- <span data-ttu-id="a3d30-281">Исправлена ошибка, в результате которой масштабирование и уменьшение масштаба из области презентации привело к разрыву между выделенной областью масштабирования и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="a3d30-281">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-282">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-282">Project</span></span>

- <span data-ttu-id="a3d30-283">Исправлена ошибка, из – за которой происходит сбой Project после щелчка по параметрам.</span><span class="sxs-lookup"><span data-stu-id="a3d30-283">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-284">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-284">Word</span></span>

- <span data-ttu-id="a3d30-285">Исправлена ошибка, из – за которой гиперссылки в комментариях не работали.</span><span class="sxs-lookup"><span data-stu-id="a3d30-285">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="a3d30-286">Исправлена ошибка, в результате которой масштабирование и уменьшение масштаба из области презентации привело к разрыву между выделенной областью масштабирования и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="a3d30-286">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="a3d30-287">Исправлена ошибка, из-за которой при вставке HTML в WordMail для календаря не работал.</span><span class="sxs-lookup"><span data-stu-id="a3d30-287">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="a3d30-288">Исправлена ошибка, в результате которой при ответе на комментарии в совместном сеансе иногда может потребоваться заморозить Word.</span><span class="sxs-lookup"><span data-stu-id="a3d30-288">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-may-15"></a><span data-ttu-id="a3d30-290">Версия 2006:15 мая</span><span class="sxs-lookup"><span data-stu-id="a3d30-290">Version 2006: May 15</span></span>
<span data-ttu-id="a3d30-291">*Версия 2006 (сборка 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-291">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-293">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-293">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-294">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-294">Excel</span></span>

- <span data-ttu-id="a3d30-295">**Создание PDF-подключения:** Подключение, импорт, обновление данных из PDF-файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-295">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="a3d30-296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-296">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="a3d30-297">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-297">Outlook</span></span>

- <span data-ttu-id="a3d30-298">**Найдите только то, что вам нужно:** Ограничьте область поиска, используя такие параметры, как папка, отправитель, Дата, сведения о вложениях и многое другое.</span><span class="sxs-lookup"><span data-stu-id="a3d30-298">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-299">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-299">PowerPoint</span></span>

- <span data-ttu-id="a3d30-300">**Отсутствие необходимости для щелчка: вы еарбудс:** Используйте Еарбудс поверхности для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-300">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="a3d30-301">Важно! чтобы использовать жесты для управления презентациями, необходимо связать Еарбудс поверхности в приложении Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a3d30-301">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="a3d30-302">Инструкции по началу работы с приложением Surface Audio в Windows 10 доступны здесь.</span><span class="sxs-lookup"><span data-stu-id="a3d30-302">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="a3d30-303">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-303">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="a3d30-304">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-304">Word</span></span>

- <span data-ttu-id="a3d30-305">**Автоматически применять или рекомендовать метки конфиденциальности:** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального контента.</span><span class="sxs-lookup"><span data-stu-id="a3d30-305">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-308">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-308">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-309">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-309">Excel</span></span>
- <span data-ttu-id="a3d30-310">Исправлена ошибка, которая привела к увеличению времени на производительность пользователей при удалении Объединенных столбцов.</span><span class="sxs-lookup"><span data-stu-id="a3d30-310">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="a3d30-311">Исправлена ошибка, из – за которой имена принтеров дублируются в списке доступных принтеров.</span><span class="sxs-lookup"><span data-stu-id="a3d30-311">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-312">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-312">PowerPoint</span></span>
- <span data-ttu-id="a3d30-313">Исправлена ошибка, из-за которой сочетания клавиш и проверка орфографии не работают должным образом при использовании клавиатуры на английском языке (КВЕРТЗ).</span><span class="sxs-lookup"><span data-stu-id="a3d30-313">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-314">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-314">Word</span></span>
- <span data-ttu-id="a3d30-315">Исправлена ошибка, из-за которой при добавлении нового комментария в пустом документе ничего не происходит.</span><span class="sxs-lookup"><span data-stu-id="a3d30-315">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="a3d30-316">Исправлена ошибка, в результате которой при вставке или обновлении индекса в документе, содержащем более ста записей, произойдет сбой приложения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-316">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="a3d30-317">Исправлена ошибка, из-за которой файлы с пользовательскими XML-значениями открывались очень медленно.</span><span class="sxs-lookup"><span data-stu-id="a3d30-317">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-318">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-318">Office Suite</span></span>
- <span data-ttu-id="a3d30-319">Исправлена ошибка в Visual Basic для приложений в Microsoft Office, где некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или в пути к библиотеке, будут отображаться приложением Office как повреждено при загрузке.</span><span class="sxs-lookup"><span data-stu-id="a3d30-319">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-may-08"></a><span data-ttu-id="a3d30-322">Версия 2006: 8 мая</span><span class="sxs-lookup"><span data-stu-id="a3d30-322">Version 2006: May 08</span></span>
<span data-ttu-id="a3d30-323">*Версия 2006 (сборка 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-323">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-325">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-325">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-326">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-326">Excel</span></span>

- <span data-ttu-id="a3d30-327">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="a3d30-327">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-328">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-328">Outlook</span></span>

- <span data-ttu-id="a3d30-329">\*\*Лучшие результаты - в одно мгновение: \*\*мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="a3d30-329">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="a3d30-330">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-330">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="a3d30-331">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="a3d30-331">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-332">PowerPoint</span></span>

- <span data-ttu-id="a3d30-333">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="a3d30-333">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="a3d30-334">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-334">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="a3d30-335">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-335">Word</span></span>

- <span data-ttu-id="a3d30-336">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="a3d30-336">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-339">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-339">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="a3d30-340">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-340">Office Suite</span></span>

- <span data-ttu-id="a3d30-341">Мы изучили и устранили проблему, из-за которой развертывание Office 365 профессиональный плюс с помощью InTune было приостановлено после завершения работы ОС.</span><span class="sxs-lookup"><span data-stu-id="a3d30-341">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-01"></a><span data-ttu-id="a3d30-343">Версия 2005: 1 мая</span><span class="sxs-lookup"><span data-stu-id="a3d30-343">Version 2005: May 01</span></span>
<span data-ttu-id="a3d30-344">*Версия 2005 (сборка 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-344">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-346">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-346">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-347">Outlook</span></span>

- <span data-ttu-id="a3d30-348">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-348">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="a3d30-349">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="a3d30-349">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="a3d30-350">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-350">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-353">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-353">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-354">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-354">Excel</span></span>

- <span data-ttu-id="a3d30-355">Исправлена проблема, из-за которой в таблице данных диаграммы неправильно отображались значения оси дат.</span><span class="sxs-lookup"><span data-stu-id="a3d30-355">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="a3d30-356">Исправлена проблема, из-за которой разрывы страниц не удавалось отключить после перехода в режим макета страницы или страничный режим.</span><span class="sxs-lookup"><span data-stu-id="a3d30-356">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="a3d30-357">Исправлена проблема, из-за которой стили линий диаграммы могли пропадать после скрытия и повторного отображения столбцов с рядами данных.</span><span class="sxs-lookup"><span data-stu-id="a3d30-357">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="a3d30-358">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="a3d30-358">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="a3d30-359">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="a3d30-359">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="a3d30-360">Исправлена проблема, из-за которой пользовательское форматирование в сводных диаграммах не сохранялось при включенном параметре "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="a3d30-360">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="a3d30-361">Исправлена проблема, из-за которой пользовательское форматирование одной точки данных в сводной диаграмме не сохранялось, если был выбран параметр "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="a3d30-361">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="a3d30-362">Это исправление устраняет проблему, из-за которой символ "@", отправленный в CSV-файл, приводил к преобразованию строки после символа "@" в формулу.</span><span class="sxs-lookup"><span data-stu-id="a3d30-362">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="a3d30-363">Исправлена проблема, из-за которой десятичные значения в функции ПОСЛЕДОВ округлялись неправильно.</span><span class="sxs-lookup"><span data-stu-id="a3d30-363">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-364">Outlook</span></span>

- <span data-ttu-id="a3d30-365">Исправлена проблема, приводившая к сбою загрузки очень длинных безопасных ссылок (из-за усечения), при переходе по ним в классическом клиенте Outlook.</span><span class="sxs-lookup"><span data-stu-id="a3d30-365">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="a3d30-366">Исправлена проблема, из-за которой папки Outlook с именами, содержащими двухбайтовые знаки (DBCS), периодически исчезали при синхронизации с сервером.</span><span class="sxs-lookup"><span data-stu-id="a3d30-366">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="a3d30-367">Чтобы это происходило, Outlook должен быть настроен с использованием учетной записи IMAP и работать в системе, языком которой выбран японский.</span><span class="sxs-lookup"><span data-stu-id="a3d30-367">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-368">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-368">PowerPoint</span></span>

- <span data-ttu-id="a3d30-369">Исправлена следующая проблема: если пользователь создавал комментарий, не публикуя его, и закрывал область комментариев, затем открывал новое окно, просматривал несколько слайдов, закрывал окно и повторно открывал область комментариев в исходной презентации, черновик комментария был недоступен.</span><span class="sxs-lookup"><span data-stu-id="a3d30-369">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-370">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-370">Project</span></span>

- <span data-ttu-id="a3d30-371">Исправлена проблема, из-за которой при подключении Project к Project Web App и использовании запятой в качестве десятичного разделителя метод добавления объектов TaskDependencies завершался сбоем, если добавлен параметр Lag.</span><span class="sxs-lookup"><span data-stu-id="a3d30-371">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-372">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-372">Word</span></span>

- <span data-ttu-id="a3d30-373">Исправлена проблема, из-за которой иногда не удавалось вставить комментарии в документ в режиме совместной работы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-373">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="a3d30-374">Это изменение исправляет ошибку, из-за которой карточка "Люди" мерцала при щелчке по @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="a3d30-374">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="a3d30-375">Исправлена следующая проблема: пользователю, закрывавшему документ с черновиком комментариев, предлагалось подтвердить закрытие без сохранения черновика комментариев,</span><span class="sxs-lookup"><span data-stu-id="a3d30-375">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="a3d30-376">и при отмене запроса документ закрывался, а не оставался открытым.</span><span class="sxs-lookup"><span data-stu-id="a3d30-376">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="a3d30-377">Исправлена проблема, из-за которой при переводе опубликованного комментария возникала ошибка "Сбой вставки переведенного текста".</span><span class="sxs-lookup"><span data-stu-id="a3d30-377">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="a3d30-378">В веб-представлении или иммерсивном средстве чтения щелчок по подсказке приводил к прокручиванию в верхнюю часть представления, хотя она уже была просмотрена.</span><span class="sxs-lookup"><span data-stu-id="a3d30-378">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="a3d30-379">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="a3d30-379">This has been fixed.</span></span>
- <span data-ttu-id="a3d30-380">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="a3d30-380">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2005-april-24"></a><span data-ttu-id="a3d30-382">Версия 2005: 24 апреля</span><span class="sxs-lookup"><span data-stu-id="a3d30-382">Version 2005: April 24</span></span>
<span data-ttu-id="a3d30-383">*Версия 2005 (сборка 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-383">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-385">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-386">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-386">Excel</span></span>
- <span data-ttu-id="a3d30-387">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="a3d30-387">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="a3d30-388">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="a3d30-388">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-389">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-389">Outlook</span></span>
- <span data-ttu-id="a3d30-390">Устранена проблема, из-за которой была отключена кнопка "Классифицировать" для календарей группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="a3d30-390">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="a3d30-391">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="a3d30-391">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-392">PowerPoint</span></span>
- <span data-ttu-id="a3d30-393">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="a3d30-393">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-394">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-394">Word</span></span>
- <span data-ttu-id="a3d30-395">При включении параметра "Показывать закладки" закладки не отображались.</span><span class="sxs-lookup"><span data-stu-id="a3d30-395">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="a3d30-396">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="a3d30-396">This has been fixed.</span></span>
- <span data-ttu-id="a3d30-397">Это изменение устраняет проблему, из-за которой при включении параметра "Показывать коды полей вместо их значений" текст с гиперссылками может не отображаться.</span><span class="sxs-lookup"><span data-stu-id="a3d30-397">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2005-april-17"></a><span data-ttu-id="a3d30-399">Версия 2005: 17 апреля</span><span class="sxs-lookup"><span data-stu-id="a3d30-399">Version 2005: April 17</span></span>
<span data-ttu-id="a3d30-400">*Версия 2005 (сборка 12810,20002)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-400">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-402">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-402">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-403">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-403">Excel</span></span>
- <span data-ttu-id="a3d30-404">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="a3d30-404">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="a3d30-405">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="a3d30-405">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="a3d30-406">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="a3d30-406">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="a3d30-407">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="a3d30-407">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="a3d30-408">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="a3d30-408">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a3d30-409">OneNote</span><span class="sxs-lookup"><span data-stu-id="a3d30-409">OneNote</span></span>
- <span data-ttu-id="a3d30-410">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="a3d30-410">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-411">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-411">Outlook</span></span>
- <span data-ttu-id="a3d30-412">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="a3d30-412">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="a3d30-413">Решает проблему, из-за которой собрания, для которых прошло более 2 месяцев, не отображали тему собрания в Помощнике по планированию.</span><span class="sxs-lookup"><span data-stu-id="a3d30-413">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="a3d30-414">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="a3d30-414">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="a3d30-415">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="a3d30-415">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="a3d30-416">Решена проблема, из-за которой правила удаления, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, стали недействительными.</span><span class="sxs-lookup"><span data-stu-id="a3d30-416">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="a3d30-417">Решает проблему, которая приводила к удалению вложений при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-417">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-418">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-418">Project</span></span>
- <span data-ttu-id="a3d30-419">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="a3d30-419">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="a3d30-420">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-420">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="a3d30-421">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="a3d30-421">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2004-april-10"></a><span data-ttu-id="a3d30-423">Версия 2004: 10 апреля</span><span class="sxs-lookup"><span data-stu-id="a3d30-423">Version 2004: April 10</span></span>
<span data-ttu-id="a3d30-424">*Версия 2004 (сборка 12730,20024)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-424">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-426">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-426">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a3d30-427">Access</span><span class="sxs-lookup"><span data-stu-id="a3d30-427">Access</span></span>

- <span data-ttu-id="a3d30-428">**Пропустите диалоговое окно «Показать таблицу», перейдите непосредственно к панели задач и упростите добавление таблиц к отношениям и запросам.:** Добавьте таблицы и запросы, щелкнув четыре вкладки, выбрав несколько имен, выполнив поиск по тексту и перетащив из области задач, которая остается открой пока ты работаешь.</span><span class="sxs-lookup"><span data-stu-id="a3d30-428">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-429">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-429">Excel</span></span>

- <span data-ttu-id="a3d30-430">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="a3d30-430">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a3d30-431">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a3d30-431">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-432">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-432">Outlook</span></span>

- <span data-ttu-id="a3d30-433">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="a3d30-433">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a3d30-434">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a3d30-434">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a3d30-435">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a3d30-435">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-436">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-436">PowerPoint</span></span>

- <span data-ttu-id="a3d30-437">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="a3d30-437">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a3d30-438">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a3d30-438">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a3d30-439">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="a3d30-439">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-440">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-440">Word</span></span>

- <span data-ttu-id="a3d30-441">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="a3d30-441">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a3d30-442">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a3d30-442">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a3d30-443">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="a3d30-443">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="a3d30-444">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="a3d30-444">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-447">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-447">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a3d30-448">Access</span><span class="sxs-lookup"><span data-stu-id="a3d30-448">Access</span></span>

- <span data-ttu-id="a3d30-449">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="a3d30-449">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-450">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-450">Excel</span></span>

- <span data-ttu-id="a3d30-451">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="a3d30-451">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="a3d30-452">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="a3d30-452">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="a3d30-453">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-453">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="a3d30-454">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="a3d30-454">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="a3d30-455">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="a3d30-455">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-456">Outlook</span></span>

- <span data-ttu-id="a3d30-457">Решает проблему, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a3d30-457">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a3d30-458">Решает проблему, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="a3d30-458">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a3d30-459">Устраняет проблему, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-459">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="a3d30-460">Решает проблему, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="a3d30-460">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-461">PowerPoint</span></span>

- <span data-ttu-id="a3d30-462">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-462">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a3d30-463">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="a3d30-463">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="a3d30-464">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="a3d30-464">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-465">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-465">Project</span></span>

- <span data-ttu-id="a3d30-466">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="a3d30-466">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-467">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-467">Word</span></span>

- <span data-ttu-id="a3d30-468">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="a3d30-468">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="a3d30-469">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="a3d30-469">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="a3d30-470">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-470">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a3d30-471">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="a3d30-471">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="a3d30-472">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="a3d30-472">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-27"></a><span data-ttu-id="a3d30-474">Версия 2004: 27 марта</span><span class="sxs-lookup"><span data-stu-id="a3d30-474">Version 2004: March 27</span></span>
<span data-ttu-id="a3d30-475">*Версия 2004 (сборка 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-475">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-477">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-477">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-478">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-478">Outlook</span></span>

- <span data-ttu-id="a3d30-479">**Новый параметр, позволяющий отключить предложения для @упоминаний при создании сообщений.** Считаете ли вы средство выбора @упоминаний скорее раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="a3d30-479">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="a3d30-480">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="a3d30-480">Now you can turn it off if you prefer.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-483">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-483">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-484">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-484">Outlook</span></span>
- <span data-ttu-id="a3d30-485">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="a3d30-485">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="a3d30-486">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="a3d30-486">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="a3d30-487">Исправлена проблема, из-за которой пользователи не могли добавить дополнительные вложения из расположения в Интернете в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="a3d30-487">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-488">PowerPoint</span></span>
- <span data-ttu-id="a3d30-489">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="a3d30-489">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-490">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-490">Project</span></span>
- <span data-ttu-id="a3d30-491">Исправлена проблема, из-за которой при выполнении "CustomFieldValueListGetItem" и отсутствии таблицы подстановки для настраиваемого поля создается пустая таблица подстановки, хотя этого быть не должно.</span><span class="sxs-lookup"><span data-stu-id="a3d30-491">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-492">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-492">Word</span></span>
- <span data-ttu-id="a3d30-493">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="a3d30-493">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-20"></a><span data-ttu-id="a3d30-495">Версия 2004: 20 марта</span><span class="sxs-lookup"><span data-stu-id="a3d30-495">Version 2004: March 20</span></span>
<span data-ttu-id="a3d30-496">*Версия 2004 (сборка 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-496">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-498">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-498">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-499">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-499">Outlook</span></span>

- <span data-ttu-id="a3d30-500">**Обновление внешнего вида календаря.** В прошлом году мы обновили интерфейс почты, а сейчас пришло время улучшить внешний вид календаря!</span><span class="sxs-lookup"><span data-stu-id="a3d30-500">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="a3d30-501">Обновления придали интерфейсу свежести, но он остался вполне узнаваемым, поэтому вам, как опытному пользователю Outlook, будет легко освоить его на ходу и сразу повысить свою продуктивность.</span><span class="sxs-lookup"><span data-stu-id="a3d30-501">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="a3d30-502">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-502">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-503">PowerPoint</span></span>

- <span data-ttu-id="a3d30-504">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="a3d30-504">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-507">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-507">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-508">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-508">Excel</span></span>

- <span data-ttu-id="a3d30-509">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="a3d30-509">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-510">Outlook</span></span>

- <span data-ttu-id="a3d30-511">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="a3d30-511">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a3d30-512">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a3d30-512">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="a3d30-513">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="a3d30-513">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="a3d30-514">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="a3d30-514">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="a3d30-515">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="a3d30-515">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-516">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-516">Project</span></span>

- <span data-ttu-id="a3d30-517">Исправлена проблема, из-за которой событие 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) при нажатии пользователем кнопки "Деактивировать" на ленте задач группировки "Планирование" не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="a3d30-517">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="a3d30-518">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="a3d30-518">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="a3d30-519">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="a3d30-519">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="a3d30-520">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="a3d30-520">This behavior has been fixed.</span></span>

- <span data-ttu-id="a3d30-521">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="a3d30-521">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="a3d30-522">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="a3d30-522">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="a3d30-523">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="a3d30-523">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="a3d30-524">Исправлена проблема, из-за которой при печати временной шкалы с использованием календаря Hijri в представлении для печати пропускался или дублировался месяц.</span><span class="sxs-lookup"><span data-stu-id="a3d30-524">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="a3d30-525">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="a3d30-525">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-526">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-526">Word</span></span>

- <span data-ttu-id="a3d30-527">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="a3d30-527">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="a3d30-528">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="a3d30-528">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a3d30-529">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="a3d30-529">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="a3d30-530">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="a3d30-530">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="a3d30-531">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="a3d30-531">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-13"></a><span data-ttu-id="a3d30-533">Версия 2004: 13 марта</span><span class="sxs-lookup"><span data-stu-id="a3d30-533">Version 2004: March 13</span></span>
<span data-ttu-id="a3d30-534">*Версия 2004 (сборка 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-534">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-536">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-536">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-537">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-537">Excel</span></span>
- <span data-ttu-id="a3d30-538">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="a3d30-538">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a3d30-539">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-539">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="a3d30-540">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-540">PowerPoint</span></span>
- <span data-ttu-id="a3d30-541">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="a3d30-541">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a3d30-542">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-542">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="a3d30-543">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-543">Word</span></span>
- <span data-ttu-id="a3d30-544">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="a3d30-544">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a3d30-545">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-545">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-548">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-548">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="a3d30-549">Access</span><span class="sxs-lookup"><span data-stu-id="a3d30-549">Access</span></span>
- <span data-ttu-id="a3d30-550">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="a3d30-550">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-551">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-551">Excel</span></span>
- <span data-ttu-id="a3d30-552">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="a3d30-552">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="a3d30-553">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="a3d30-553">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-554">Outlook</span></span>
- <span data-ttu-id="a3d30-555">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="a3d30-555">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="a3d30-556">Исправлена проблема, из-за которой не начинался поиск при нажатии клавиши ВВОД в развернутой области поиска, и требовалось вместо этого щелкать кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="a3d30-556">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="a3d30-557">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="a3d30-557">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="a3d30-558">Project</span><span class="sxs-lookup"><span data-stu-id="a3d30-558">Project</span></span>
- <span data-ttu-id="a3d30-559">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="a3d30-559">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="a3d30-560">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="a3d30-560">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-561">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-561">Word</span></span>
- <span data-ttu-id="a3d30-562">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="a3d30-562">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="a3d30-563">Исправлена проблема, из-за которой выравнивание слов в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="a3d30-563">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="a3d30-564">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="a3d30-564">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="a3d30-565">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="a3d30-565">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-06"></a><span data-ttu-id="a3d30-567">Версия 2003: 6 марта</span><span class="sxs-lookup"><span data-stu-id="a3d30-567">Version 2003: March 06</span></span>
<span data-ttu-id="a3d30-568">*Версия 2003 (сборка 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-568">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-570">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-570">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-571">Outlook</span></span>

- <span data-ttu-id="a3d30-572">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не было сохранено на сервере Exchange Server и возник конфликт.</span><span class="sxs-lookup"><span data-stu-id="a3d30-572">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="a3d30-573">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="a3d30-573">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="a3d30-574">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="a3d30-574">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-575">PowerPoint</span></span>

- <span data-ttu-id="a3d30-576">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="a3d30-576">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a3d30-577">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-577">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-578">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-578">Word</span></span>

- <span data-ttu-id="a3d30-579">Исправлена проблема с функцией сравнения для документов, защищенных для редактирования.</span><span class="sxs-lookup"><span data-stu-id="a3d30-579">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-580">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-580">Office Suite</span></span>

- <span data-ttu-id="a3d30-581">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-581">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a3d30-582">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="a3d30-582">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2003-february-28"></a><span data-ttu-id="a3d30-585">Версия 2003: 28 февраля</span><span class="sxs-lookup"><span data-stu-id="a3d30-585">Version 2003: February 28</span></span>
<span data-ttu-id="a3d30-586">*Версия 2003 (сборка 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-586">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-588">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-588">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-589">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-589">Outlook</span></span>

- <span data-ttu-id="a3d30-590">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="a3d30-590">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="a3d30-591">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-591">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="a3d30-592">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-592">PowerPoint</span></span>

- <span data-ttu-id="a3d30-593">**Улучшенный рукописный ввод для работы со схемами.** Создавайте отличные схемы и преобразуйте их в объекты Office, которыми можно управлять. [Подробнее](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="a3d30-593">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-596">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-596">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a3d30-597">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-597">Excel</span></span>

- <span data-ttu-id="a3d30-598">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="a3d30-598">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-599">Outlook</span></span>

- <span data-ttu-id="a3d30-600">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="a3d30-600">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-601">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-601">Word</span></span>

- <span data-ttu-id="a3d30-602">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="a3d30-602">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a3d30-603">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="a3d30-603">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a3d30-604">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="a3d30-604">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-605">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-605">Office Suite</span></span>

- <span data-ttu-id="a3d30-606">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="a3d30-606">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-21"></a><span data-ttu-id="a3d30-608">Версия 2003: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="a3d30-608">Version 2003: February 21</span></span>
<span data-ttu-id="a3d30-609">*Версия 2003 (сборка 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-609">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-611">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-611">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="a3d30-612">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-612">Office Suite</span></span>

- <span data-ttu-id="a3d30-613">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="a3d30-613">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-616">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-616">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-617">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-617">Excel</span></span>
- <span data-ttu-id="a3d30-618">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="a3d30-618">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="a3d30-619">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="a3d30-619">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="a3d30-620">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="a3d30-620">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="a3d30-621">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="a3d30-621">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="a3d30-622">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="a3d30-622">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-623">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-623">Outlook</span></span>
- <span data-ttu-id="a3d30-624">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="a3d30-624">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="a3d30-625">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="a3d30-625">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="a3d30-626">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="a3d30-626">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-627">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-627">Word</span></span>
- <span data-ttu-id="a3d30-628">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="a3d30-628">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="a3d30-629">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега.</span><span class="sxs-lookup"><span data-stu-id="a3d30-629">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a3d30-630">Эта проблема исправлена.</span><span class="sxs-lookup"><span data-stu-id="a3d30-630">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-631">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-631">Office Suite</span></span>
- <span data-ttu-id="a3d30-632">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="a3d30-632">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a3d30-633">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="a3d30-633">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a3d30-634">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="a3d30-634">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-14"></a><span data-ttu-id="a3d30-636">Версия 2003: 14 февраля</span><span class="sxs-lookup"><span data-stu-id="a3d30-636">Version 2003: February 14</span></span>
<span data-ttu-id="a3d30-637">*Версия 2003 (сборка 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-637">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-639">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-639">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-640">Outlook</span></span>

- <span data-ttu-id="a3d30-641">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="a3d30-641">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a3d30-642">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="a3d30-642">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-643">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-643">Word</span></span>

- <span data-ttu-id="a3d30-644">**Правки от руки в инструментах рисования.** Нажмите "Рисование" и выберите перо Правки от руки, чтобы редактировать документ с помощью пальца или цифрового пера.</span><span class="sxs-lookup"><span data-stu-id="a3d30-644">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="a3d30-645">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-645">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="a3d30-646">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-646">Office Suite</span></span>

- <span data-ttu-id="a3d30-647">**Более понятные значки строки состояния.** Значки строки состояния стали понятнее</span><span class="sxs-lookup"><span data-stu-id="a3d30-647">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-650">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-650">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a3d30-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-651">Outlook</span></span>

- <span data-ttu-id="a3d30-652">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря "Параметры доступности".</span><span class="sxs-lookup"><span data-stu-id="a3d30-652">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="a3d30-653">Исправлена проблема, которая могла привести к появлению оповещения "К сожалению, не удалось открыть элемент" при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="a3d30-653">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a3d30-654">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="a3d30-654">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a3d30-655">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="a3d30-655">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-656">PowerPoint</span></span>

- <span data-ttu-id="a3d30-657">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="a3d30-657">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-658">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-658">Word</span></span>

- <span data-ttu-id="a3d30-659">Исправлена проблема, из-за которой изображения в документах теряли прозрачность при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="a3d30-659">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-07"></a><span data-ttu-id="a3d30-661">Версия 2002: 7 февраля</span><span class="sxs-lookup"><span data-stu-id="a3d30-661">Version 2002: February 07</span></span>
<span data-ttu-id="a3d30-662">*Версия 2002 (сборка 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="a3d30-662">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a3d30-664">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a3d30-664">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a3d30-665">Доступ</span><span class="sxs-lookup"><span data-stu-id="a3d30-665">Access</span></span>

- <span data-ttu-id="a3d30-666">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="a3d30-666">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a3d30-667">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="a3d30-667">Search and replace text in SQL View.</span></span> <span data-ttu-id="a3d30-668">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="a3d30-668">Select multiple tables in the Relationships window.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a3d30-671">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a3d30-671">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a3d30-672">Access</span><span class="sxs-lookup"><span data-stu-id="a3d30-672">Access</span></span>

- <span data-ttu-id="a3d30-673">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="a3d30-673">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a3d30-674">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="a3d30-674">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a3d30-675">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="a3d30-675">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a3d30-676">Excel</span><span class="sxs-lookup"><span data-stu-id="a3d30-676">Excel</span></span>

- <span data-ttu-id="a3d30-677">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="a3d30-677">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a3d30-678">Outlook</span><span class="sxs-lookup"><span data-stu-id="a3d30-678">Outlook</span></span>

- <span data-ttu-id="a3d30-679">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="a3d30-679">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a3d30-680">Решена проблема, приводившая к сбоям при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="a3d30-680">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a3d30-681">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a3d30-681">PowerPoint</span></span>

- <span data-ttu-id="a3d30-682">Исправлена проблема, из-за которой после закрытия файла приложение PowerPoint не удаляет его сразу из коллекции презентаций, если запущены обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="a3d30-682">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a3d30-683">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a3d30-683">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="a3d30-684">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="a3d30-684">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="a3d30-685">Word</span><span class="sxs-lookup"><span data-stu-id="a3d30-685">Word</span></span>

- <span data-ttu-id="a3d30-686">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="a3d30-686">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="a3d30-687">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="a3d30-687">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="a3d30-688">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="a3d30-688">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="a3d30-689">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="a3d30-689">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="a3d30-690">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="a3d30-690">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="a3d30-691">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="a3d30-691">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a3d30-692">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a3d30-692">Office Suite</span></span>

- <span data-ttu-id="a3d30-693">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="a3d30-693">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)
