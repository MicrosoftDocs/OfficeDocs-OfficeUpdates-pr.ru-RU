---
title: Заметки о выпуске Актуального канала (предварительная версия)
ms.author: anankani
author: v-lislo
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставление участникам программы предварительной оценки с поздним доступом последнего списка новых функций, исправлений или известных проблем
ms.openlocfilehash: 5bd71abc819924012ecbaf37563b24e4e6220f6a
ms.sourcegitcommit: d108f8a732dfede6326d9726c09c667b5d084131
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/30/2021
ms.locfileid: "51440714"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="02809-103">Заметки о выпуске Актуального канала Office (предварительная версия)</span><span class="sxs-lookup"><span data-stu-id="02809-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="02809-104">Эта статья содержит заметки о выпуске для сборок Актуального канала (предварительная версия) приложений Word, Excel, PowerPoint, Outlook, Access, Project и Teams для Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="02809-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="02809-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="02809-106">Обратите внимание, что развертывание возможностей (а иногда даже исправлений) в Актуальном канале (предварительная версия) зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="02809-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="02809-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="02809-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="02809-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="02809-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="02809-109">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="02809-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="02809-110">Дополнительные сведения см. в [этой статье](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="02809-110">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="02809-111">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="02809-111">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="02809-112">Функции Microsoft Teams могут отличаться от последних версий Актуального канала (предварительная версия), поскольку они выпускаются чаще.</span><span class="sxs-lookup"><span data-stu-id="02809-112">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

## <a name="version-2103-march-30"></a><span data-ttu-id="02809-114">Версия 2103: 30 марта</span><span class="sxs-lookup"><span data-stu-id="02809-114">Version 2103: March 30</span></span>
<span data-ttu-id="02809-115">*Версия 2103 (сборка 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="02809-115">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="02809-116">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-116">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="02809-117">Версия 2103: 28 марта</span><span class="sxs-lookup"><span data-stu-id="02809-117">Version 2103: March 28</span></span>
<span data-ttu-id="02809-118">*Версия 2103 (сборка 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="02809-118">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-120">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-120">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-121">Outlook</span></span>

- <span data-ttu-id="02809-122">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при синхронизации изменений в иерархии папок.</span><span class="sxs-lookup"><span data-stu-id="02809-122">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="02809-123">Исправлена проблема, из-за которой у некоторых пользователей основной и дополнительный календари менялись местами в области навигации.</span><span class="sxs-lookup"><span data-stu-id="02809-123">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-22"></a><span data-ttu-id="02809-125">Версия 2103: 22 марта</span><span class="sxs-lookup"><span data-stu-id="02809-125">Version 2103: March 22</span></span>
<span data-ttu-id="02809-126">*Версия 2103 (сборка 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="02809-126">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-128">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-128">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-129">Outlook</span></span>

- <span data-ttu-id="02809-130">Исправлена проблема, из-за которой пользователи видели больше подписей, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="02809-130">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-15"></a><span data-ttu-id="02809-132">Версия 2103: 15 марта</span><span class="sxs-lookup"><span data-stu-id="02809-132">Version 2103: March 15</span></span>
<span data-ttu-id="02809-133">*Версия 2103 (сборка 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="02809-133">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-135">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-135">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="02809-136">Project</span><span class="sxs-lookup"><span data-stu-id="02809-136">Project</span></span>

- <span data-ttu-id="02809-137">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="02809-137">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="02809-138">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-138">Visio</span></span>

- <span data-ttu-id="02809-139">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="02809-139">Fixed an issue where Visio could stop working during close.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-12"></a><span data-ttu-id="02809-141">Версия 2103: 12 марта</span><span class="sxs-lookup"><span data-stu-id="02809-141">Version 2103: March 12</span></span>
<span data-ttu-id="02809-142">*Версия 2103 (сборка 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="02809-142">*Version 2103 (Build 13901.20148)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-144">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-144">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="02809-145">Teams</span><span class="sxs-lookup"><span data-stu-id="02809-145">Teams</span></span>

- <span data-ttu-id="02809-146">**Статус “Нет на месте”** Оставьте уведомление, чтобы при отправке сообщений в чате другие знали, что вы недоступны или в отпуске и не сможете ответить.</span><span class="sxs-lookup"><span data-stu-id="02809-146">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="02809-147">Ваш статус “Нет на месте” также синхронизируется с автоматическими ответами в календаре Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-147">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

[//]: # (НЕ УДАЛЯТЬ)


## <a name="version-2103-march-11"></a><span data-ttu-id="02809-149">Версия 2103: 11 марта</span><span class="sxs-lookup"><span data-stu-id="02809-149">Version 2103: March 11</span></span>
<span data-ttu-id="02809-150">*Версия 2103 (сборка 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="02809-150">*Version 2103 (Build 13901.20148)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-152">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-152">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-153">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-153">Excel</span></span>

- <span data-ttu-id="02809-154">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="02809-154">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="02809-155">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="02809-155">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="02809-156">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="02809-156">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-157">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-157">Outlook</span></span>

- <span data-ttu-id="02809-158">**Новые возможности резервирования конференц-залов и рабочей области:** обновлен процесс резервирования конференц-залов и добавлены возможности для планирования отдельных рабочих областей.</span><span class="sxs-lookup"><span data-stu-id="02809-158">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-159">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-159">PowerPoint</span></span>

- <span data-ttu-id="02809-160">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="02809-160">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="02809-161">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="02809-161">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="02809-162">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="02809-162">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="visio"></a><span data-ttu-id="02809-163">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-163">Visio</span></span>

- <span data-ttu-id="02809-164">**Новый дизайн значков Office:** дизайн значков продукта изменен, чтобы показать простой, функциональный и удобный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="02809-164">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="02809-165">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-165">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="02809-166">Word</span><span class="sxs-lookup"><span data-stu-id="02809-166">Word</span></span>

- <span data-ttu-id="02809-167">**Темный режим для документов Word:** темный режим помогает снизить нагрузку на глаза и учитывает светочувствительность при работе с документами.</span><span class="sxs-lookup"><span data-stu-id="02809-167">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="02809-168">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="02809-168">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="02809-169">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="02809-169">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="02809-170">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="02809-170">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-173">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-173">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-174">Access</span><span class="sxs-lookup"><span data-stu-id="02809-174">Access</span></span>

- <span data-ttu-id="02809-175">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-175">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="02809-176">Исправлена проблема, из-за которой невозможно было завершить работу до разблокировки указателя, когда внешнее приложение запрашивало интерфейс со специальными возможностями.</span><span class="sxs-lookup"><span data-stu-id="02809-176">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="02809-177">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-177">Excel</span></span>

- <span data-ttu-id="02809-178">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-178">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="02809-179">Устранена проблема, из-за которой Excel иногда неожиданно закрывался при попытке показать карточку типов данных, поскольку не мог получить изображение.</span><span class="sxs-lookup"><span data-stu-id="02809-179">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="02809-180">Исправлена проблема, из-за которой шрифт неожиданно менялся при использовании знака умножения или деления с японским шрифтом.</span><span class="sxs-lookup"><span data-stu-id="02809-180">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="02809-181">Теперь продолжится использование того же шрифта, если он поддерживает символ.</span><span class="sxs-lookup"><span data-stu-id="02809-181">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="02809-182">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="02809-182">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="02809-183">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании функции "Вставить связанный рисунок".</span><span class="sxs-lookup"><span data-stu-id="02809-183">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="02809-184">Исправлена проблема потери некоторого форматирования при копировании листа во время совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="02809-184">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="02809-185">Исправлена проблема, из-за которой неожиданно отображались некоторые заметки при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="02809-185">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="02809-186">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="02809-186">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-187">Outlook</span></span>

- <span data-ttu-id="02809-188">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-188">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="02809-189">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="02809-189">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="02809-190">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="02809-190">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="02809-191">Исправлена проблема, из-за которой новые календари не появлялись в области навигации, пока пользователь не перезапустит Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-191">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="02809-192">Исправлена проблема, из-за которой символы, отличные от ASCII, некорректно экспортировались в CSV-файл.</span><span class="sxs-lookup"><span data-stu-id="02809-192">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="02809-193">Исправлена проблема, из-за которой некоторые пользователи не могли получить доступ к подписям, связанным с дополнительными учетными записями почты.</span><span class="sxs-lookup"><span data-stu-id="02809-193">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="02809-194">Исправлена проблема, из-за которой пользовательские параметры функции "Параметры облака" менялись на значения по умолчанию после настройки Outlook на новом устройстве.</span><span class="sxs-lookup"><span data-stu-id="02809-194">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="02809-195">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="02809-195">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="02809-196">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="02809-196">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="02809-197">Исправлена проблема, из-за которой дублировались вложения при удалении защиты DRM.</span><span class="sxs-lookup"><span data-stu-id="02809-197">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="02809-198">Исправлена проблема, из-за которой пользователи не могли найти группу контактов с помощью проверки имен при создании сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-198">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-199">PowerPoint</span></span>

- <span data-ttu-id="02809-200">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-200">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="02809-201">Исправлена проблема, из-за которой стрелки на графиках отображались неправильно в режиме слайд-шоу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-201">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="02809-202">Устранена проблема с повторением анимаций и звуковыми закладками.</span><span class="sxs-lookup"><span data-stu-id="02809-202">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="02809-203">Project</span><span class="sxs-lookup"><span data-stu-id="02809-203">Project</span></span>

- <span data-ttu-id="02809-204">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="02809-204">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="02809-205">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-205">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="02809-206">Устранена проблема, из-за которой задача, выполненная на 100%, могла вернуться к выполнению на 99%.</span><span class="sxs-lookup"><span data-stu-id="02809-206">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="02809-207">Устранена проблема, из-за которой Project иногда неожиданно закрывался при запуске JAWS и переходе в диалоговое окно сведений о задаче.</span><span class="sxs-lookup"><span data-stu-id="02809-207">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="02809-208">Исправлена проблема, из-за которой при вырезании суммарной задачи не появлялось предупреждение об удалении подзадач, если столбец индикатора отсутствовал в первом столбце.</span><span class="sxs-lookup"><span data-stu-id="02809-208">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="02809-209">Исправлена проблема, из-за которой в создаваемом назначении могли применяться неправильные единицы доступности ресурса, если пользователь выбирал функцию "Добавление себя в задачу" в своем расписании.</span><span class="sxs-lookup"><span data-stu-id="02809-209">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="02809-210">Исправлена проблема, из-за которой при сохранении проекта из веб-приложения Project в локальный файл могли неправильно создаваться разбиения задач.</span><span class="sxs-lookup"><span data-stu-id="02809-210">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="02809-211">Это могло происходить при использовании календаря задач с нестандартным рабочим временем.</span><span class="sxs-lookup"><span data-stu-id="02809-211">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="02809-212">Publisher</span><span class="sxs-lookup"><span data-stu-id="02809-212">Publisher</span></span>

- <span data-ttu-id="02809-213">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-213">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="02809-214">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-214">Visio</span></span>

- <span data-ttu-id="02809-215">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="02809-215">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="02809-216">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-216">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="02809-217">Word</span><span class="sxs-lookup"><span data-stu-id="02809-217">Word</span></span>

- <span data-ttu-id="02809-218">Исправлена проблема, из-за которой открытие файла, защищенного с помощью метки Microsoft Information Protection (MIP), могло зависать на неопределенное время, если пользователь не вошел в систему с удостоверением, имеющим доступ к защищенной метке MIP.</span><span class="sxs-lookup"><span data-stu-id="02809-218">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="02809-219">Открытие будет принудительно отменено, чтобы отобразить запрос на вход. Только после этого получится открыть файл.</span><span class="sxs-lookup"><span data-stu-id="02809-219">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="02809-220">Устранение этой проблемы возможно путем отображения запроса на вход во время открытия или загрузки.</span><span class="sxs-lookup"><span data-stu-id="02809-220">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="02809-221">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="02809-221">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="02809-222">Исправлена проблема при использовании диктофона в новой версии комментирования Word. Теперь кнопка диктофона правильно включается и отключается в карточке комментария.</span><span class="sxs-lookup"><span data-stu-id="02809-222">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="02809-223">При совместной работе над документом активный черновик не очищается при смене порядка комментариев.</span><span class="sxs-lookup"><span data-stu-id="02809-223">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="02809-224">Исправлена проблема, из-за которой при диктовке в документе между словами не вставлялись пробелы.</span><span class="sxs-lookup"><span data-stu-id="02809-224">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="02809-225">Исправлена проблема в конвейере отрисовки, связанная со слоями прокрутки, содержащими анимации прокрутки или масштабирования.</span><span class="sxs-lookup"><span data-stu-id="02809-225">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="02809-226">Исправлена проблема с применением цветовой гаммы к значкам и изображениям SVG с трехмерными эффектами.</span><span class="sxs-lookup"><span data-stu-id="02809-226">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="02809-227">Исправлена проблема с автосохранением.</span><span class="sxs-lookup"><span data-stu-id="02809-227">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="02809-228">Исправлена проблема со сносками.</span><span class="sxs-lookup"><span data-stu-id="02809-228">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="02809-229">Исправлена проблема при публикации многострочных комментариев, введенных справа налево, из-за которой вторая и последующие строки выравнивались по левому краю, а не по правому.</span><span class="sxs-lookup"><span data-stu-id="02809-229">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="02809-230">Исправлена проблема с выравниванием нескольких комментариев.</span><span class="sxs-lookup"><span data-stu-id="02809-230">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="02809-231">Исправлена проблема с сочетаниями клавиш области задач "Прочесть вслух".</span><span class="sxs-lookup"><span data-stu-id="02809-231">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="02809-232">Исправлена проблема, из-за которой экранный диктор иногда пропускает абзац.</span><span class="sxs-lookup"><span data-stu-id="02809-232">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="02809-233">Исправлена проблема, из-за которой проверка орфографии переключалась между двумя разными контекстными меню проверки орфографии.</span><span class="sxs-lookup"><span data-stu-id="02809-233">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="02809-234">Исправлена проблема с элементами управления форматированным текстом.</span><span class="sxs-lookup"><span data-stu-id="02809-234">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="02809-235">Исправлена проблема, из-за которой набор текста в конце скрытого абзаца мог привести к зависанию приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-235">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="02809-236">Исправлена проблема, из-за которой в столбцах мог быть перекрывающийся текст.</span><span class="sxs-lookup"><span data-stu-id="02809-236">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="02809-237">Исправлена проблема, связанная с закладкой.</span><span class="sxs-lookup"><span data-stu-id="02809-237">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="02809-238">Исправлена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="02809-238">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-239">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-239">Office Suite</span></span>

- <span data-ttu-id="02809-240">Места в OneDrive теперь фильтруются в соответствии с настройками групповой политики.</span><span class="sxs-lookup"><span data-stu-id="02809-240">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="02809-241">Исправлена проблема, которая возникала при использовании экранного диктора в тексте с математическими уравнениями.</span><span class="sxs-lookup"><span data-stu-id="02809-241">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="02809-242">Исправлена проблема надежности, связанная с поддержкой приложений Office, работающих в сеансе 0.</span><span class="sxs-lookup"><span data-stu-id="02809-242">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="02809-243">Исправлена проблема надежности, связанная с поддержкой приложений Office, работающих в сеансе 0.</span><span class="sxs-lookup"><span data-stu-id="02809-243">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="02809-244">Исправлена проблема, связанная с отсутствием отклика при загрузке изображений EMF.</span><span class="sxs-lookup"><span data-stu-id="02809-244">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-03"></a><span data-ttu-id="02809-246">Версия 2102: 3 марта</span><span class="sxs-lookup"><span data-stu-id="02809-246">Version 2102: March 03</span></span>
<span data-ttu-id="02809-247">*Версия 2102 (сборка 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="02809-247">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-249">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-249">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="02809-250">Word</span><span class="sxs-lookup"><span data-stu-id="02809-250">Word</span></span>

- <span data-ttu-id="02809-251">Исправлена проблема с информацией о теме, примененной к значкам и изображениям SVG.</span><span class="sxs-lookup"><span data-stu-id="02809-251">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-01"></a><span data-ttu-id="02809-253">Версия 2102: 1 марта</span><span class="sxs-lookup"><span data-stu-id="02809-253">Version 2102: March 01</span></span>
<span data-ttu-id="02809-254">*Версия 2102 (сборка 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="02809-254">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-256">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-256">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-257">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-257">Outlook</span></span>

- <span data-ttu-id="02809-258">**Поделиться в Teams.** Поделитесь сообщениями из Outlook с пользователем или каналом в Teams.</span><span class="sxs-lookup"><span data-stu-id="02809-258">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-261">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-261">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-262">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-262">Outlook</span></span>

- <span data-ttu-id="02809-263">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="02809-263">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="02809-264">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="02809-264">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="02809-265">Исправлена проблема, из-за которой у некоторых пользователей закрывалось приложение при закрытии окон сообщений.</span><span class="sxs-lookup"><span data-stu-id="02809-265">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="02809-266">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="02809-266">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="02809-267">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="02809-267">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-february-21"></a><span data-ttu-id="02809-269">Версия 2102: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-269">Version 2102: February 21</span></span>
<span data-ttu-id="02809-270">*Версия 2102 (сборка 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="02809-270">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-272">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-272">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-273">Outlook</span></span>

- <span data-ttu-id="02809-274">**Создать сообщения с помощью голоса.** Используйте новую панель инструментов для диктовки, голосовые команды, автоматическую пунктуацию и многое другое для создания сообщений.</span><span class="sxs-lookup"><span data-stu-id="02809-274">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="02809-275">Word</span><span class="sxs-lookup"><span data-stu-id="02809-275">Word</span></span>

- <span data-ttu-id="02809-276">**Создать документ с помощью голоса.** Используйте новую панель инструментов для диктовки, голосовые команды и автоматическую пунктуацию для создания документов.</span><span class="sxs-lookup"><span data-stu-id="02809-276">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-279">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-279">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-280">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-280">Excel</span></span>

- <span data-ttu-id="02809-281">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании параметра "Вставка связанного рисунка".</span><span class="sxs-lookup"><span data-stu-id="02809-281">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-february-16"></a><span data-ttu-id="02809-283">Версия 2102: 16 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-283">Version 2102: February 16</span></span>
<span data-ttu-id="02809-284">*Версия 2102 (сборка 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="02809-284">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="02809-285">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-285">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="02809-286">Версия 2102: 15 января</span><span class="sxs-lookup"><span data-stu-id="02809-286">Version 2102: February 15</span></span>
<span data-ttu-id="02809-287">*Версия 2102 (сборка 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="02809-287">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-289">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-289">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-290">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-290">Outlook</span></span>

- <span data-ttu-id="02809-291">**Диктовка доступна на большем количестве языков.** Теперь диктовка поддерживает семь новых языков: хинди, русский, польский, португальский (Португалия), корейский, тайский и китайский (Тайвань).</span><span class="sxs-lookup"><span data-stu-id="02809-291">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="02809-292">Word</span><span class="sxs-lookup"><span data-stu-id="02809-292">Word</span></span>

- <span data-ttu-id="02809-293">**Диктовка доступна на большем количестве языков.** Теперь диктовка поддерживает семь новых языков: хинди, русский, польский, португальский (Португалия), корейский, тайский и китайский (Тайвань).</span><span class="sxs-lookup"><span data-stu-id="02809-293">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-296">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-296">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-297">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-297">Excel</span></span>

- <span data-ttu-id="02809-298">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="02809-298">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="02809-299">Word</span><span class="sxs-lookup"><span data-stu-id="02809-299">Word</span></span>

- <span data-ttu-id="02809-300">Устранена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="02809-300">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2102-february-11"></a><span data-ttu-id="02809-302">Версия 2102: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-302">Version 2102: February 11</span></span>
<span data-ttu-id="02809-303">*Версия 2102 (сборка 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="02809-303">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-305">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-305">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="02809-306">Teams</span><span class="sxs-lookup"><span data-stu-id="02809-306">Teams</span></span>

- <span data-ttu-id="02809-307">**Видео 2x2 в браузерах Microsoft Edge и Chrome для Windows и Mac** Пользователи могут видеть до 4 участников на видео-собраниях Teams в браузерах Microsoft Edge и Chrome для Windows и Mac.</span><span class="sxs-lookup"><span data-stu-id="02809-307">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="02809-308">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-308">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="02809-310">Версия 2102: 8 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-310">Version 2102: February 08</span></span>
<span data-ttu-id="02809-311">*Версия 2102 (сборка 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="02809-311">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-313">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-313">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-314">Outlook</span></span>

- <span data-ttu-id="02809-315">**Создание предложений (Кому\Копия\СК) на основе Поиска (Майкрософт):** добавление пользователей в строку "Кому"\"Копия" теперь выполняется на платформе Поиска (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="02809-315">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-318">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-318">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-319">Access</span><span class="sxs-lookup"><span data-stu-id="02809-319">Access</span></span>

- <span data-ttu-id="02809-320">Теперь выбранные вкладки будут отображаться четче в Access.</span><span class="sxs-lookup"><span data-stu-id="02809-320">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="02809-321">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-321">Excel</span></span>

- <span data-ttu-id="02809-322">Исправляет проблемы, при которых определенные диаграммы, в которых используются несмежные диапазоны ячеек, не будут загружаться при повторном открытии файлов.</span><span class="sxs-lookup"><span data-stu-id="02809-322">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="02809-323">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="02809-323">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="02809-324">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="02809-324">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="02809-325">Исправлена проблема, из-за которой приложение Excel неожиданно завершало работу при добавлении имени в диалоговом окне "Присвоение имени".</span><span class="sxs-lookup"><span data-stu-id="02809-325">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="02809-326">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="02809-326">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-327">Outlook</span></span>

- <span data-ttu-id="02809-328">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="02809-328">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="02809-329">Исправлена проблема, из-за которой значок шифрования не отображался для сообщений, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="02809-329">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-330">PowerPoint</span></span>

- <span data-ttu-id="02809-331">Исправлена проблема, связанная с отображением эмодзи в цвете.</span><span class="sxs-lookup"><span data-stu-id="02809-331">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="02809-332">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="02809-332">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="02809-333">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-333">Visio</span></span>

- <span data-ttu-id="02809-334">Эта проблема с отрисовкой фигур из наборов элементов САПР исправлена.</span><span class="sxs-lookup"><span data-stu-id="02809-334">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="02809-335">Проблема устранена для пользователей в последней сборке.</span><span class="sxs-lookup"><span data-stu-id="02809-335">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="02809-336">Word</span><span class="sxs-lookup"><span data-stu-id="02809-336">Word</span></span>

- <span data-ttu-id="02809-337">Это исправление проблемы, из-за которой был невозможен ввод в режиме реального времени и восстановление присутствия после потери подключения к Интернету в течение определенного периода времени.</span><span class="sxs-lookup"><span data-stu-id="02809-337">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="02809-338">Когда пользователь выбирает текст в примечании, Word теперь отменяет выделение текста в других примечаниях.</span><span class="sxs-lookup"><span data-stu-id="02809-338">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="02809-339">Теперь Word позволяет копировать текст примечаний в Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-339">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="02809-340">Исправлена проблема, из-за которой возникал сбой при запуске макроса VBA ExportAsFixedFormat2 с ошибкой "Недопустимое значение презентации (неизвестный участник)".</span><span class="sxs-lookup"><span data-stu-id="02809-340">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="02809-341">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="02809-341">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="02809-342">Устранена проблема, из-за которой примечание может быть обрезано с ссылками.</span><span class="sxs-lookup"><span data-stu-id="02809-342">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="02809-343">Устранена проблема с сохранением в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="02809-343">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="02809-344">Устранена проблема с экспортом документов Word в PDF.</span><span class="sxs-lookup"><span data-stu-id="02809-344">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="02809-345">Исправлена проблема с автовосстановлением.</span><span class="sxs-lookup"><span data-stu-id="02809-345">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="02809-346">Исправлена проблема с совместным редактированием файлов, защищенных с помощью DRM</span><span class="sxs-lookup"><span data-stu-id="02809-346">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-347">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-347">Office Suite</span></span>

- <span data-ttu-id="02809-348">Исправлена ошибка в PowerPoint, из-за которой вставка маркеров в виде изображений приводила к исчезновению маркеров.</span><span class="sxs-lookup"><span data-stu-id="02809-348">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="02809-349">Это исправление повышает надежность их отрисовки.</span><span class="sxs-lookup"><span data-stu-id="02809-349">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="02809-350">Устранена проблема, из-за которой в некоторых случаях в Office отображались метки конфиденциальности для одной учетной записи, в которую был выполнен вход, тогда как нужно было для другой.</span><span class="sxs-lookup"><span data-stu-id="02809-350">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-february-03"></a><span data-ttu-id="02809-352">Версия 2101: 3 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-352">Version 2101: February 03</span></span>
<span data-ttu-id="02809-353">*Версия 2101 (сборка 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="02809-353">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-355">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-355">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-356">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-356">Outlook</span></span>

- <span data-ttu-id="02809-357">Исправлена проблема, из-за которой возникали проблемы с отображением правильной подписи по умолчанию в OWA.</span><span class="sxs-lookup"><span data-stu-id="02809-357">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="02809-358">Исправлена проблема, из-за которой значок шифрования не отображался в сообщениях, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="02809-358">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-february-02"></a><span data-ttu-id="02809-360">Версия 2101: 2 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-360">Version 2101: February 02</span></span>
<span data-ttu-id="02809-361">*Версия 2101 (сборка 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="02809-361">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-363">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-363">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-364">Outlook</span></span>

- <span data-ttu-id="02809-365">Исправлена проблема, приводившая к зависанию у пользователей облачных параметров при обновлении настроек.</span><span class="sxs-lookup"><span data-stu-id="02809-365">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-25"></a><span data-ttu-id="02809-367">Версия 2101: 25 января</span><span class="sxs-lookup"><span data-stu-id="02809-367">Version 2101: January 25</span></span>
<span data-ttu-id="02809-368">*Версия 2101 (сборка 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="02809-368">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-370">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-370">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-371">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-371">Excel</span></span>

- <span data-ttu-id="02809-372">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="02809-372">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="02809-373">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-373">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="02809-374">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-374">Outlook</span></span>

- <span data-ttu-id="02809-375">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="02809-375">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="02809-376">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-376">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="02809-377">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-377">PowerPoint</span></span>

- <span data-ttu-id="02809-378">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="02809-378">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="02809-379">[Подробнее](/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="02809-379">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="02809-380">Word</span><span class="sxs-lookup"><span data-stu-id="02809-380">Word</span></span>

- <span data-ttu-id="02809-381">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="02809-381">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="02809-382">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-382">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="02809-383">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-383">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-384">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-384">Outlook</span></span>

- <span data-ttu-id="02809-385">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="02809-385">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



## <a name="version-2101-january-18"></a><span data-ttu-id="02809-387">Версия 2101: 18 января</span><span class="sxs-lookup"><span data-stu-id="02809-387">Version 2101: January 18</span></span>
<span data-ttu-id="02809-388">*Версия 2101 (сборка 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="02809-388">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-392">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-392">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="02809-393">Project</span><span class="sxs-lookup"><span data-stu-id="02809-393">Project</span></span>

- <span data-ttu-id="02809-394">Исправлена проблема, из-за которой границы не отображались для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="02809-394">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="02809-395">Исправлена проблема, из-за которой не работало перетаскивание для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="02809-395">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-13"></a><span data-ttu-id="02809-397">Версия 2101: 13 января</span><span class="sxs-lookup"><span data-stu-id="02809-397">Version 2101: January 13</span></span>
<span data-ttu-id="02809-398">*Версия 2101 (сборка 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="02809-398">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
### <a name="feature-updates"></a><span data-ttu-id="02809-400">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-400">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="02809-401">Teams</span><span class="sxs-lookup"><span data-stu-id="02809-401">Teams</span></span>
- <span data-ttu-id="02809-402">**Дополнительные темы**. Новые темы теперь доступны для классических и веб-клиентов.</span><span class="sxs-lookup"><span data-stu-id="02809-402">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="02809-403">**Общий доступ в PPT**. Режим докладчика в Teams. После выбора файла PowerPoint на панели общего доступа Teams автоматически открывается режим докладчика.</span><span class="sxs-lookup"><span data-stu-id="02809-403">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="02809-404">Вы увидите текущий слайд, заметки к слайду и ряд эскизов всех слайдов в колоде для удобной навигации по слайдам.</span><span class="sxs-lookup"><span data-stu-id="02809-404">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="02809-405">Этот режим работает в фоновом режиме, является личным под управлением выступающего.</span><span class="sxs-lookup"><span data-stu-id="02809-405">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="02809-406">Аудитория может только просматривать текущий слайд (выделенный в красном квадратике) или слайд, к которому они будут переходить (если навигация аудитории не заблокирована).</span><span class="sxs-lookup"><span data-stu-id="02809-406">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="02809-407">**Включить звук компьютера при демонстрации рабочего стола или окна на компьютере Mac** Когда вы демонстрируете рабочий стол или окно в Teams для Mac, теперь можно включить звук компьютера, чтобы люди, присоединившись к собранию, могли слышать звук из вашего компьютера.</span><span class="sxs-lookup"><span data-stu-id="02809-407">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="02809-409">Версия 2101: 9 января</span><span class="sxs-lookup"><span data-stu-id="02809-409">Version 2101: January 09</span></span>
<span data-ttu-id="02809-410">*Версия 2101 (сборка 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="02809-410">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-412">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-412">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-413">Outlook</span></span>

- <span data-ttu-id="02809-414">**Быстрые рекомендации по стилю.** Применяйте рекомендации литературной правки одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="02809-414">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="02809-415">Корректор исправляет правописание и предлагает идеи по уточнению текста.</span><span class="sxs-lookup"><span data-stu-id="02809-415">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="02809-416">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-416">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="02809-417">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/microsoft-editor-gets-an-upgrade)</span><span class="sxs-lookup"><span data-stu-id="02809-417">See details in [blog post](https://insider.office.com/ru-RU/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-420">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-420">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-421">Outlook</span></span>

- <span data-ttu-id="02809-422">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось в определенных сценариях поиска.</span><span class="sxs-lookup"><span data-stu-id="02809-422">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-07"></a><span data-ttu-id="02809-424">Версия 2101: 7 января</span><span class="sxs-lookup"><span data-stu-id="02809-424">Version 2101: January 07</span></span>
<span data-ttu-id="02809-425">*Версия 2101 (сборка 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="02809-425">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-427">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-427">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-428">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-428">Excel</span></span>

- <span data-ttu-id="02809-429">**Отображение нескольких листов одновременно.** Больше не нужно отображать листы по одному. Отображайте несколько скрытых листов одновременно.</span><span class="sxs-lookup"><span data-stu-id="02809-429">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="02809-430">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-430">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="02809-431">**Улучшенные диалоговые окна условного форматирования.** Теперь размеры диалоговых окон условного форматирования можно изменять, и вы можете дублировать правило одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="02809-431">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="02809-432">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-432">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-435">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-435">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-436">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-436">Excel</span></span>

- <span data-ttu-id="02809-437">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="02809-437">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="02809-438">Исправлена проблема с переключением разделителей после вызова Selection.Parent.Copy.</span><span class="sxs-lookup"><span data-stu-id="02809-438">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="02809-439">Улучшена производительность при применении стилей форматирования для сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="02809-439">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="02809-440">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="02809-440">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="02809-441">Обновление, чтобы обеспечить перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word</span><span class="sxs-lookup"><span data-stu-id="02809-441">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="02809-442">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="02809-442">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="02809-443">Исправлена проблема, которая приводит к появлению предупреждения о нехватке ресурсов при использовании функции "ИСТОРИЯАКЦИЙ".</span><span class="sxs-lookup"><span data-stu-id="02809-443">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="02809-444">Добавлена библиотека DLL FuzzyClustering в список библиотек DLL PQ.</span><span class="sxs-lookup"><span data-stu-id="02809-444">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="02809-445">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="02809-445">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="02809-446">Исправлена проблема, из-за которой предварительный просмотр внедренного диапазона Excel в PowerPoint показывает неверный размер.</span><span class="sxs-lookup"><span data-stu-id="02809-446">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="02809-447">OneNote</span><span class="sxs-lookup"><span data-stu-id="02809-447">OneNote</span></span>

- <span data-ttu-id="02809-448">Это исправление устраняет проблему отрисовки, влияющую на OneNote.</span><span class="sxs-lookup"><span data-stu-id="02809-448">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-449">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-449">Outlook</span></span>

- <span data-ttu-id="02809-450">Исправлена проблема, из-за которой пользователи не могли указать, на какой срок нужно разрешить доступ при начале слияния из Word, что приводило к получению избыточных запросов.</span><span class="sxs-lookup"><span data-stu-id="02809-450">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="02809-451">Это изменение позволяет Outlook использовать параметр Exchange Server, предотвращающий отображение архивного почтового ящика Exchange Online для конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="02809-451">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="02809-452">Исправлена проблема, из-за которой Outlook неожиданно закрывался у пользователей надстроек на основе Redemption. </span><span class="sxs-lookup"><span data-stu-id="02809-452">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="02809-453">Устранена проблема, из-за которой пользователи не могли выбрать больше одной категории для поиска.</span><span class="sxs-lookup"><span data-stu-id="02809-453">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="02809-454">Устранена проблема, из-за которой время начала для некоторых элементов календаря неожиданно изменялось при копировании события из другой встречи. </span><span class="sxs-lookup"><span data-stu-id="02809-454">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="02809-455">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="02809-455">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-456">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-456">PowerPoint</span></span>

- <span data-ttu-id="02809-457">Это изменение исправляет проблему с объединением фигур при работе с текстом.</span><span class="sxs-lookup"><span data-stu-id="02809-457">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="02809-458">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="02809-458">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="02809-459">Это изменение исправляет проблему с циклическим воспроизведением фоновых видео в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="02809-459">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="02809-460">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="02809-460">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="02809-461">Project</span><span class="sxs-lookup"><span data-stu-id="02809-461">Project</span></span>

- <span data-ttu-id="02809-462">Исправлена ​​проблема, из-за которой максимальное количество единиц ресурса не всегда отражало последнее обновление.</span><span class="sxs-lookup"><span data-stu-id="02809-462">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="02809-463">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-463">Visio</span></span>

- <span data-ttu-id="02809-464">Эта проблема возникла из-за недавней регрессии.</span><span class="sxs-lookup"><span data-stu-id="02809-464">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="02809-465">Мы устранили эту проблему.</span><span class="sxs-lookup"><span data-stu-id="02809-465">We have resolved the issue.</span></span> <span data-ttu-id="02809-466">В диалоговом окне "Сохранить как веб-страницу" поля будут правильно заполнены в соответствии с вводом пользователя, и пользователи могут легко сохранять свои файлы как веб-страницы.</span><span class="sxs-lookup"><span data-stu-id="02809-466">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="02809-467">Эта проблема исправлена.</span><span class="sxs-lookup"><span data-stu-id="02809-467">This issue has been fixed.</span></span> <span data-ttu-id="02809-468">Теперь можно внедрять файлы Visio как объекты в другие приложения Office, такие как PowerPoint и Word, а также использовать их в этих приложениях.</span><span class="sxs-lookup"><span data-stu-id="02809-468">You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="02809-469">Word</span><span class="sxs-lookup"><span data-stu-id="02809-469">Word</span></span>

- <span data-ttu-id="02809-470">Исправлена проблема, из-за которой на компьютерах с настраиваемыми параметрами хеша наблюдались проблемы во время сеанса совместной работы с параметрами хеша, отличным от sha512.</span><span class="sxs-lookup"><span data-stu-id="02809-470">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="02809-471">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="02809-471">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="02809-472">Исправлена проблема при редактировании записи примечания с @упоминанием.</span><span class="sxs-lookup"><span data-stu-id="02809-472">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="02809-473">Исправлена проблема для повышения функциональности современных примечаний. </span><span class="sxs-lookup"><span data-stu-id="02809-473">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="02809-474">Исправлена проблема с удалением современных примечаний в элементе управления содержимым, который помечен как нередактирумый.</span><span class="sxs-lookup"><span data-stu-id="02809-474">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="02809-475">Исправлена проблема с анимацией при вводе текста в нижней части карточки комментария.</span><span class="sxs-lookup"><span data-stu-id="02809-475">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="02809-476">Исправлена проблема, из-за которой поле ответа в карточке примечания располагалось вне экрана.</span><span class="sxs-lookup"><span data-stu-id="02809-476">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="02809-477">Исправлена проблема с картой примечаний, отображаемой в верхней части страницы.</span><span class="sxs-lookup"><span data-stu-id="02809-477">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="02809-478">Исправлена ошибка в примечаниях, из-за которой текст пропадал при прокручивании.</span><span class="sxs-lookup"><span data-stu-id="02809-478">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="02809-479">Исправлена проблема со встроенными полосами прокрутки в области примечаний.</span><span class="sxs-lookup"><span data-stu-id="02809-479">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="02809-480">Черновики примечаний исчезают при создании нового экземпляра Word.</span><span class="sxs-lookup"><span data-stu-id="02809-480">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="02809-481">Устранена проблема, из-за которой Word зависал при сохранении документа в формате PDF со скрытым текстом.</span><span class="sxs-lookup"><span data-stu-id="02809-481">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-january-04"></a><span data-ttu-id="02809-483">Версия 2012: 4 января</span><span class="sxs-lookup"><span data-stu-id="02809-483">Version 2012: January 04</span></span>
<span data-ttu-id="02809-484">*Версия 2012 (сборка 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="02809-484">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="02809-485">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-485">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-487">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-487">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-488">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-488">Excel</span></span>

- <span data-ttu-id="02809-489">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="02809-489">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-490">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-490">PowerPoint</span></span>

- <span data-ttu-id="02809-491">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="02809-491">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="02809-492">Word</span><span class="sxs-lookup"><span data-stu-id="02809-492">Word</span></span>

- <span data-ttu-id="02809-493">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="02809-493">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-28"></a><span data-ttu-id="02809-495">Версия 2012: 28 декабря</span><span class="sxs-lookup"><span data-stu-id="02809-495">Version 2012: December 28</span></span>
<span data-ttu-id="02809-496">*Версия 2012 (сборка 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="02809-496">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-498">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-498">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-499">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-499">Outlook</span></span>

- <span data-ttu-id="02809-500">Исправлена проблема, приводившая к зависаниям у некоторых пользователей при загрузке их календарей.</span><span class="sxs-lookup"><span data-stu-id="02809-500">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-21"></a><span data-ttu-id="02809-502">Версия 2012: 21 декабря</span><span class="sxs-lookup"><span data-stu-id="02809-502">Version 2012: December 21</span></span>
<span data-ttu-id="02809-503">*Версия 2012 (сборка 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="02809-503">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-505">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-505">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-506">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-506">Excel</span></span>

- <span data-ttu-id="02809-507">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="02809-507">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="02809-508">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="02809-508">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-509">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-509">Outlook</span></span>

- <span data-ttu-id="02809-510">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время начала собрания на 5–10 минут позже по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="02809-510">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="02809-511">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-511">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="02809-512">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="02809-512">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="02809-513">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="02809-513">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-514">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-514">PowerPoint</span></span>

- <span data-ttu-id="02809-515">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="02809-515">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="02809-516">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="02809-516">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="02809-517">Word</span><span class="sxs-lookup"><span data-stu-id="02809-517">Word</span></span>

- <span data-ttu-id="02809-518">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="02809-518">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="02809-519">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="02809-519">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-522">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-522">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-523">PowerPoint</span></span>

- <span data-ttu-id="02809-524">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="02809-524">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-14"></a><span data-ttu-id="02809-526">Версия 2012: 14 декабря</span><span class="sxs-lookup"><span data-stu-id="02809-526">Version 2012: December 14</span></span>
<span data-ttu-id="02809-527">*Версия 2012 (сборка 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="02809-527">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-529">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-529">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-530">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-530">Outlook</span></span>

- <span data-ttu-id="02809-531">**Ваши параметры Outlook в облаке.** Выберите свои параметры Outlook для Windows, например автоматические ответы, сортировку почты и конфиденциальность, и получайте их на любом компьютере.</span><span class="sxs-lookup"><span data-stu-id="02809-531">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-534">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="02809-535">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-535">Office Suite</span></span>

- <span data-ttu-id="02809-536">Оптимизированный размер двоичного файла.</span><span class="sxs-lookup"><span data-stu-id="02809-536">Optimized binary size.</span></span>


- <span data-ttu-id="02809-537">Anaheim WebView пока не поддерживает службу Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="02809-537">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="02809-538">С этим исправлением платформа надстроек Office откатывается на веб-представление уровнем ниже в среде с поддержкой WIP.</span><span class="sxs-lookup"><span data-stu-id="02809-538">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="02809-539">Это может быть Edge Spartan WebView или Trident WebView в зависимости от среды на компьютере пользователя.</span><span class="sxs-lookup"><span data-stu-id="02809-539">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="02809-540">Оба веб-представления уровнем ниже поддерживают WIP.</span><span class="sxs-lookup"><span data-stu-id="02809-540">Both down level WebViews support WIP.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-07"></a><span data-ttu-id="02809-542">Версия 2012: 7 декабря</span><span class="sxs-lookup"><span data-stu-id="02809-542">Version 2012: December 07</span></span>
<span data-ttu-id="02809-543">*Версия 2012 (сборка 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="02809-543">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-545">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-545">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="02809-546">Teams</span><span class="sxs-lookup"><span data-stu-id="02809-546">Teams</span></span>

- <span data-ttu-id="02809-547">**В Teams теперь поддерживаются встроенные уведомления Windows:** Теперь пользователи могут выбирать предпочитаемый способ доставки уведомлений, используя команды, встроенные в баннеры Teams или встроенные баннеры Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-547">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="02809-548">**Представление галереи 2x2 для собраний Teams в VDI Citrix и VMware:** Функция представления галереи 2x2 в VDI в Teams позволяет просматривать до четырех участников в представлении галереи 2x2 на клиентах VDI от Citrix, VMWare при использовании клиента Teams в оптимизированном режиме для VDI.</span><span class="sxs-lookup"><span data-stu-id="02809-548">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="02809-549">**Реакции на собраниях:**  Реакции на собраниях — новый способ взаимодействия на собраниях.</span><span class="sxs-lookup"><span data-stu-id="02809-549">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="02809-550">Участники могут отправлять реакции, которые будут показаны в виде потока на контенте, к которому предоставляется доступ, а также на пользователе, отправившем реакцию, если они отображаются на сцене собрания.</span><span class="sxs-lookup"><span data-stu-id="02809-550">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="02809-551">**Режим "Вместе" и Большая галерея для веб-собраний** С помощью Большой галереи можно просматривать видео до 49 других пользователей одновременно.</span><span class="sxs-lookup"><span data-stu-id="02809-551">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="02809-552">Этот параметр доступен, если камеры включены не менее чем у десяти участников.</span><span class="sxs-lookup"><span data-stu-id="02809-552">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="02809-553">Режим "Вместе" создает ощущение, что вы и все участники собрания находитесь в одном и том же месте.</span><span class="sxs-lookup"><span data-stu-id="02809-553">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="02809-554">Режим "Вместе" доступен, если на собрании присутствует не менее пяти участников.</span><span class="sxs-lookup"><span data-stu-id="02809-554">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="02809-555">**Объединение звонков** Функция объединения звонков позволяет пользователям объединять новый звонок или новый входящий вызов с их личным или групповым звонком.</span><span class="sxs-lookup"><span data-stu-id="02809-555">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="02809-556">Она используется для вызовов VOIP и звонков по ТСОП в Teams.</span><span class="sxs-lookup"><span data-stu-id="02809-556">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="02809-557">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-557">Visio</span></span>

- <span data-ttu-id="02809-558">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="02809-558">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="02809-559">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-559">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-562">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-562">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-563">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-563">Excel</span></span>

- <span data-ttu-id="02809-564">Исправлена проблема, из-за которой некоторые элементы не был локализованы на китайском языке (упрощенное письмо).</span><span class="sxs-lookup"><span data-stu-id="02809-564">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="02809-565">Исправлена проблема, из-за которой приложение Excel неожиданно прекращало работу при обновлении.</span><span class="sxs-lookup"><span data-stu-id="02809-565">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="02809-566">Исправлена проблема, из-за которой команда "Вставить объект" не отображала соответствующий значок при вставке файла из локальной папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="02809-566">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="02809-567">Исправлена проблема, из-за которой правка на языках, требующих использования IME, не работала должным образом, если правка выполнялась в режиме перезаписи.</span><span class="sxs-lookup"><span data-stu-id="02809-567">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="02809-568">Исправлена проблема, из-за которой для некоторых пользователей неверно отображалась панель сообщений, уведомляющая о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="02809-568">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="02809-569">Устранена проблема, вызывавшая неожиданное закрытие Excel при копировании и вставке данных в представлении формулы.</span><span class="sxs-lookup"><span data-stu-id="02809-569">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="02809-570">Восстановлена нарушенная ссылка на справочную статью в оповещении, возникающем при отключении автосохранения.</span><span class="sxs-lookup"><span data-stu-id="02809-570">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="02809-571">Исправлена проблема, из-за которой приложение Excel переставало работать, если выполнялся ввод данных при запуске Excel в определенных языках.</span><span class="sxs-lookup"><span data-stu-id="02809-571">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="02809-572">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="02809-572">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="02809-573">Исправлена проблема, из-за которой Power Pivot не мог правильно импортировать текстовый файл с разделителями (табуляциями).</span><span class="sxs-lookup"><span data-stu-id="02809-573">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-574">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-574">Outlook</span></span>

- <span data-ttu-id="02809-575">Исправлена проблема, из-за которой поле "Кому:" было пустым в отчетах о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-575">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="02809-576">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="02809-576">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="02809-577">Исправлена проблема, из-за которой у пользователей возникали ошибки при отправке почты Outlook из приложений, отличных от Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-577">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="02809-578">Исправлена проблема, из-за которой терялось форматирование смарт-ссылок при сохранении в черновике.</span><span class="sxs-lookup"><span data-stu-id="02809-578">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="02809-579">Исправлена проблема, из-за которой не удавалось добавить вложение в сообщение, открытое из ZIP-файла.</span><span class="sxs-lookup"><span data-stu-id="02809-579">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-580">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-580">PowerPoint</span></span>

- <span data-ttu-id="02809-581">Исправлена ошибка при копировании и вставке уравнения из Word в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-581">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="02809-582">Это изменение устраняет проблему, связанную с таймаутами при анализе рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="02809-582">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="02809-583">Это изменение устраняет грамматическую ошибку в пользовательском интерфейсе создания GIF с анимацией.</span><span class="sxs-lookup"><span data-stu-id="02809-583">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="02809-584">Это изменение устраняет проблему с заливками путей при объединений фигур определенных геометрий.</span><span class="sxs-lookup"><span data-stu-id="02809-584">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="02809-585">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="02809-585">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="02809-586">Это изменение устраняет проблему с обработкой ошибок, которые могут возникнуть во время загрузки видео.</span><span class="sxs-lookup"><span data-stu-id="02809-586">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="02809-587">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="02809-587">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="02809-588">Исправлена проблема, из-за которой индикатор присутствия неизвестного соавтора не обновлялся полностью при получении дополнительных сведений о соавторе.</span><span class="sxs-lookup"><span data-stu-id="02809-588">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="02809-589">Исправлено удаление ссылки на пустой указатель при изменении размера представления слайда с включенной линейкой.</span><span class="sxs-lookup"><span data-stu-id="02809-589">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="02809-590">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="02809-590">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="02809-591">Project</span><span class="sxs-lookup"><span data-stu-id="02809-591">Project</span></span>

- <span data-ttu-id="02809-592">Исправлена проблема, из-за которой отсутствовали изменения при открытии пользователями проектов, сохраненных с измененными сведениями.</span><span class="sxs-lookup"><span data-stu-id="02809-592">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="02809-593">Исправлена проблема, из-за которой не удавалось удалить зависимости в конечных результатах, если сайт SharePoint, с которым были связаны конечные результаты, больше не существовал.</span><span class="sxs-lookup"><span data-stu-id="02809-593">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="02809-594">Исправлена проблема, из-за которой открытие проекта с большим количеством ресурсов занимало много времени.</span><span class="sxs-lookup"><span data-stu-id="02809-594">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="02809-595">Исправлена проблема, из-за которой могли отображаться многочисленные неназначенные задания, связанные с задачей.</span><span class="sxs-lookup"><span data-stu-id="02809-595">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="02809-596">Исправлена проблема, из-за которой в крупных проектах имя задачи могло вводиться очень медленно.</span><span class="sxs-lookup"><span data-stu-id="02809-596">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="02809-597">Исправлена проблема, из-за которой могли открываться определенные проекты, если имелась проблема с файлом проекта в определенной части загрузки.</span><span class="sxs-lookup"><span data-stu-id="02809-597">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="02809-598">Word</span><span class="sxs-lookup"><span data-stu-id="02809-598">Word</span></span>

- <span data-ttu-id="02809-599">Вставка в виде обычного текста часто бывает предпочтительнее вставки форматированного текста.</span><span class="sxs-lookup"><span data-stu-id="02809-599">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="02809-600">Это исправленное контекстное меню позволяет пользователю выполнять вставку в виде обычного текста.</span><span class="sxs-lookup"><span data-stu-id="02809-600">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="02809-601">В противном случае пользователю потребовалось бы копировать в редактор обычного текста, например Блокнот, а затем копировать из Блокнота в нужное приложение</span><span class="sxs-lookup"><span data-stu-id="02809-601">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="02809-602">Исправлена ошибка при копировании и вставке уравнения из Word в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-602">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="02809-603">Это изменение исправляет проблему, связанную с курсором при редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="02809-603">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="02809-604">Исправлена проблема, из-за которой изображения становились размытыми при изменении масштаба.</span><span class="sxs-lookup"><span data-stu-id="02809-604">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="02809-605">Исправлена проблема, из-за которой длинные гиперссылки усекались.</span><span class="sxs-lookup"><span data-stu-id="02809-605">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-606">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-606">Office Suite</span></span>

- <span data-ttu-id="02809-607">В наборе Office исправлена проблема, из-за которой установка более новой версии Office поверх некоторых старых версий могла приводить к ухудшению функциональности (например, невозможности использовать Power Query) из-за отсутствия записей в реестре.</span><span class="sxs-lookup"><span data-stu-id="02809-607">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-december-01"></a><span data-ttu-id="02809-609">Версия 2011: 1 декабря</span><span class="sxs-lookup"><span data-stu-id="02809-609">Version 2011: December 01</span></span>
<span data-ttu-id="02809-610">*Версия 2011 (сборка 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="02809-610">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-612">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-612">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-613">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-613">Outlook</span></span>

- <span data-ttu-id="02809-614">**Все собрания по сети.** Упростите планирование собраний по сети с помощью нового параметра, который переводит все собрания в онлайн по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="02809-614">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-617">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-617">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-618">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-618">Outlook</span></span>

- <span data-ttu-id="02809-619">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="02809-619">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="02809-620">Исправлена проблема, из-за которой некоторые пользователи не видели подписей в раскрывающемся списке подписей, хотя у них настроена одна или несколько подписей.</span><span class="sxs-lookup"><span data-stu-id="02809-620">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="02809-621">Project</span><span class="sxs-lookup"><span data-stu-id="02809-621">Project</span></span>

- <span data-ttu-id="02809-622">Исправлена проблема, из-за которой могли открываться определенные проекты, если имелась проблема с файлом проекта в определенной части загрузки.</span><span class="sxs-lookup"><span data-stu-id="02809-622">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-24"></a><span data-ttu-id="02809-624">Версия 2011: 24 ноября</span><span class="sxs-lookup"><span data-stu-id="02809-624">Version 2011: November 24</span></span>
<span data-ttu-id="02809-625">*Версия 2011 (сборка 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="02809-625">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-627">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-627">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="02809-628">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-628">Office Suite</span></span>

- <span data-ttu-id="02809-629">Исправлена ошибка при копировании и вставке уравнения из Word в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-629">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-21"></a><span data-ttu-id="02809-631">Версия 2011: 21 ноября</span><span class="sxs-lookup"><span data-stu-id="02809-631">Version 2011: November 21</span></span>
<span data-ttu-id="02809-632">*Версия 2011 (сборка 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="02809-632">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-634">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-634">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-635">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-635">PowerPoint</span></span>

- <span data-ttu-id="02809-636">**Библиотека видео.** Улучшайте свои документы с помощью библиотеки специально отобранных бесплатных видеоматериалов, доступных в приложении</span><span class="sxs-lookup"><span data-stu-id="02809-636">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-639">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-639">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-640">Outlook</span></span>

- <span data-ttu-id="02809-641">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="02809-641">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="02809-642">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="02809-642">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="02809-643">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="02809-643">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="02809-644">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="02809-644">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="02809-645">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="02809-645">0 = filetimes are excluded.</span></span> <span data-ttu-id="02809-646">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="02809-646">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="02809-647">Исправлена проблема, приводившая к исчезновению встроенных изображений при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="02809-647">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-18"></a><span data-ttu-id="02809-649">Версия 2011: 18 ноября</span><span class="sxs-lookup"><span data-stu-id="02809-649">Version 2011: November 18</span></span>
<span data-ttu-id="02809-650">*Версия 2011 (сборка 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="02809-650">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="02809-651">Исправления различных ошибок и проблем производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-651">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="02809-652">Версия 2011: 16 октября</span><span class="sxs-lookup"><span data-stu-id="02809-652">Version 2011: November 16</span></span>
<span data-ttu-id="02809-653">*Версия 2011 (сборка 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="02809-653">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-655">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-655">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-656">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-656">Outlook</span></span>

- <span data-ttu-id="02809-657">**Одна подпись на всех устройствах.** Ваша подпись хранится в облаке.</span><span class="sxs-lookup"><span data-stu-id="02809-657">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="02809-658">Создайте ее один раз и используйте везде, где применяете Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-658">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-661">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-661">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-662">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-662">Outlook</span></span>

- <span data-ttu-id="02809-663">Исправлена проблема, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-663">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-664">PowerPoint</span></span>

- <span data-ttu-id="02809-665">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="02809-665">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-09"></a><span data-ttu-id="02809-667">Версия 2011: 9 ноября</span><span class="sxs-lookup"><span data-stu-id="02809-667">Version 2011: November 09</span></span>
<span data-ttu-id="02809-668">*Версия 2011 (сборка 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="02809-668">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-670">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-670">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-671">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-671">Excel</span></span>

- <span data-ttu-id="02809-672">**Создание потоков данных Power Platform из запросов:** теперь можно экспортировать запросы в шаблоны Power Query, которые можно использовать для создания новых потоков данных Power Platform.</span><span class="sxs-lookup"><span data-stu-id="02809-672">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-675">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-675">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-676">Доступ</span><span class="sxs-lookup"><span data-stu-id="02809-676">Access</span></span>

- <span data-ttu-id="02809-677">Исправлена проблема, из-за которой для некоторых пользователей отображалась ошибка "Недостаточно системных ресурсов", когда они пытались экспортировать запрос из своей синхронизированной папки OneDrive.</span><span class="sxs-lookup"><span data-stu-id="02809-677">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="02809-678">Исправлена проблема, из-за которой автоматическое переключение между окнами форм приводило к переключению на другую форму.</span><span class="sxs-lookup"><span data-stu-id="02809-678">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="02809-679">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-679">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="02809-680">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-680">Excel</span></span>

- <span data-ttu-id="02809-681">Устранена проблема, из-за которой имя файла не изменялось после операции SaveAs с включенными надстройками COM.</span><span class="sxs-lookup"><span data-stu-id="02809-681">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="02809-682">Исправлена проблема с Power Pivot при использовании подключения к базе данных Oracle.</span><span class="sxs-lookup"><span data-stu-id="02809-682">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="02809-683">Устранена проблема, вызывавшая сбой при автоматическом сохранении с неверным или ошибочным сообщением об ошибке, если в модели данных Excel было неверное определение меры.</span><span class="sxs-lookup"><span data-stu-id="02809-683">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="02809-684">Исправлена проблема, вызывавшая неожиданное прекращение работы Excel при запуске вычисления MTR и обновления объекта групповой политики (например, с помощью удаленного обновления групповой политики).</span><span class="sxs-lookup"><span data-stu-id="02809-684">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="02809-685">Исправлена проблема, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="02809-685">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="02809-686">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-686">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="02809-687">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="02809-687">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-688">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-688">Outlook</span></span>

- <span data-ttu-id="02809-689">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="02809-689">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="02809-690">Устранена проблема, из-за которой быстрая печать вложенных изображений вызывала ошибку: "Не удалось найти изображение.</span><span class="sxs-lookup"><span data-stu-id="02809-690">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="02809-691">Проверьте путь и повторите попытку."</span><span class="sxs-lookup"><span data-stu-id="02809-691">Check the location, and then try again".</span></span>


- <span data-ttu-id="02809-692">Исправлена проблема, из-за которой у некоторых пользователей Outlook запускался в автономном состоянии, пока они не выбирали сетевой режим работы вручную.</span><span class="sxs-lookup"><span data-stu-id="02809-692">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="02809-693">Исправлена проблема, из-за которой при вставке URL-адреса, скопированного из расположения собрания, в другое место (например, в браузер) URL-адрес содержал в конце точку с запятой.</span><span class="sxs-lookup"><span data-stu-id="02809-693">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="02809-694">Исправлена проблема, из-за которой пользователи не могли удалять встречи в календаре групп Microsoft 365 при обычной проверке подлинности.</span><span class="sxs-lookup"><span data-stu-id="02809-694">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="02809-695">Исправлена проблема, вызывавшая сбой запуска Outlook при загрузке кэша псевдонимов.</span><span class="sxs-lookup"><span data-stu-id="02809-695">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="02809-696">Исправлена проблема, из-за которой владелец почтового ящика не мог управлять разрешением общего доступа для своего календаря, так как этот параметр был затенен.</span><span class="sxs-lookup"><span data-stu-id="02809-696">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="02809-697">Исправлена проблема, из-за которой приложение Outlook не могло создать сообщение с ограниченным разрешением.</span><span class="sxs-lookup"><span data-stu-id="02809-697">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="02809-698">Исправлена проблема, из-за которой сохранение шаблонов электронной почты в виде OFT-файлов приводило к изменению китайских иероглифов на вопросительные знаки.</span><span class="sxs-lookup"><span data-stu-id="02809-698">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-699">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-699">PowerPoint</span></span>

- <span data-ttu-id="02809-700">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-700">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="02809-701">Исправлена проблема, из-за которой в значке заполнителя содержимого рядом с "Изображениями" не было всплывающих подсказок.</span><span class="sxs-lookup"><span data-stu-id="02809-701">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="02809-702">Исправлена проблема, из-за которой при защищенном просмотре слайд-шоу, демонстрируемом в файле pptsx, можно было сделать снимок экрана документа, защищенного IRM.</span><span class="sxs-lookup"><span data-stu-id="02809-702">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="02809-703">Исправлена проблема, из-за которой линии сетки смещались со слайдов при закрытии области конструктора.</span><span class="sxs-lookup"><span data-stu-id="02809-703">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="02809-704">Исправлена проблема, из-за которой при дублировании слайд-шоу на второй монитор оно могло быть скрыто за другим окном.</span><span class="sxs-lookup"><span data-stu-id="02809-704">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="02809-705">Исправлена проблема, из-за которой полоса прокрутки на слайде начинала двигаться самостоятельно после прекращения записи экрана с открытой областью выбора.</span><span class="sxs-lookup"><span data-stu-id="02809-705">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="02809-706">Project</span><span class="sxs-lookup"><span data-stu-id="02809-706">Project</span></span>

- <span data-ttu-id="02809-707">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChagne имело неправильное значение в случае изменения задержки в представлении типа "Форма задач".</span><span class="sxs-lookup"><span data-stu-id="02809-707">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="02809-708">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="02809-708">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="02809-709">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="02809-709">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="02809-710">Исправлена проблема, из-за которой задействование ресурсов выполняло поиск ресурса по имени, а не по GUID, что приводило к проблемам при наличии нескольких ресурсов с одинаковым именем.</span><span class="sxs-lookup"><span data-stu-id="02809-710">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="02809-711">Устранена проблема, из-за которой после группирования списка задач на сайте проекта нельзя было быстро изменить список задач.</span><span class="sxs-lookup"><span data-stu-id="02809-711">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="02809-712">Исправлена проблема, при которой после обновления корпоративного ресурса с помощью CSOM максимальные единицы для ресурса могли быть потеряны.</span><span class="sxs-lookup"><span data-stu-id="02809-712">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="02809-713">Word</span><span class="sxs-lookup"><span data-stu-id="02809-713">Word</span></span>

- <span data-ttu-id="02809-714">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-714">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="02809-715">Исправлена проблема, из-за которой щелчок по маркеру примечания не приводил к уменьшению масштаба для отображения карточки примечания в представлении.</span><span class="sxs-lookup"><span data-stu-id="02809-715">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="02809-716">Исправлена проблема макета, из-за которой могла смещаться линия между столбцами.</span><span class="sxs-lookup"><span data-stu-id="02809-716">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="02809-717">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="02809-717">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="02809-718">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="02809-718">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="02809-719">Исправлена проблема печати, из-за которой применялась метка конфиденциальности с подложками.</span><span class="sxs-lookup"><span data-stu-id="02809-719">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-720">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-720">Office Suite</span></span>

- <span data-ttu-id="02809-721">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="02809-721">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="02809-722">Устранена проблема, из-за которой при интерактивном входе в SSO API возвращался код ошибки.</span><span class="sxs-lookup"><span data-stu-id="02809-722">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-november-06"></a><span data-ttu-id="02809-724">Версия 2010: 6 ноября</span><span class="sxs-lookup"><span data-stu-id="02809-724">Version 2010: November 06</span></span>
<span data-ttu-id="02809-725">*Версия 2010 (сборка 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="02809-725">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="02809-726">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-726">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-november-04"></a><span data-ttu-id="02809-729">Версия 2010: 4 ноября</span><span class="sxs-lookup"><span data-stu-id="02809-729">Version 2010: November 04</span></span>
<span data-ttu-id="02809-730">*Версия 2010 (сборка 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="02809-730">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-732">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-732">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-733">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-733">Excel</span></span>

- <span data-ttu-id="02809-734">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-734">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="02809-735">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-735">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="02809-736">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-736">Outlook</span></span>

- <span data-ttu-id="02809-737">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-737">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="02809-738">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-738">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="02809-739">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-739">PowerPoint</span></span>

- <span data-ttu-id="02809-740">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-740">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="02809-741">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-741">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="02809-742">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="02809-742">See details in [blog post](https://insider.office.com/ru-RU/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="02809-743">**Создание GIF с прозрачным фоном:** при экспорте в GIF с анимацией новый параметр позволит сделать фон прозрачным.</span><span class="sxs-lookup"><span data-stu-id="02809-743">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="02809-744">Дополнительные сведения см. в этой [записи блога](https://insider.office.com/ru-RU/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="02809-744">See details in [blog post](https://insider.office.com/ru-RU/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="02809-745">**Экспорт GIF с анимацией в диапазоне:** выберите диапазон слайдов при экспорте в GIF с анимацией</span><span class="sxs-lookup"><span data-stu-id="02809-745">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="02809-746">Word</span><span class="sxs-lookup"><span data-stu-id="02809-746">Word</span></span>

- <span data-ttu-id="02809-747">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-747">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="02809-748">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-748">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-751">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-751">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-752">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-752">Outlook</span></span>

- <span data-ttu-id="02809-753">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="02809-753">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-754">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-754">Office Suite</span></span>

- <span data-ttu-id="02809-755">Исправлена проблема, вызывавшая сбой при попытке сохранить файлы, перешедшие из состояния "синхронизировано" в состояние "только для сервера".</span><span class="sxs-lookup"><span data-stu-id="02809-755">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-27"></a><span data-ttu-id="02809-757">Версия 2010: 27 октября</span><span class="sxs-lookup"><span data-stu-id="02809-757">Version 2010: October 27</span></span>
<span data-ttu-id="02809-758">*Версия 2010 (сборка 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="02809-758">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-762">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-762">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-763">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-763">Outlook</span></span>

- <span data-ttu-id="02809-764">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="02809-764">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="02809-765">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="02809-765">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-24"></a><span data-ttu-id="02809-767">Версия 2010: 24 октября</span><span class="sxs-lookup"><span data-stu-id="02809-767">Version 2010: October 24</span></span>
<span data-ttu-id="02809-768">*Версия 2010 (сборка 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="02809-768">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-772">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-772">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-773">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-773">Outlook</span></span>

- <span data-ttu-id="02809-774">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="02809-774">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="02809-775">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="02809-775">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="02809-776">Project</span><span class="sxs-lookup"><span data-stu-id="02809-776">Project</span></span>

- <span data-ttu-id="02809-777">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="02809-777">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="02809-778">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="02809-778">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-19"></a><span data-ttu-id="02809-780">Версия 2010: 19 октября</span><span class="sxs-lookup"><span data-stu-id="02809-780">Version 2010: October 19</span></span>
<span data-ttu-id="02809-781">*Версия 2010 (сборка 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="02809-781">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-783">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-783">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-784">Outlook</span></span>

- <span data-ttu-id="02809-785">**Экономия времени при создании сообщений:** в Outlook отображаются предложения по литературной правке, помогающие быстро создавать сообщения.</span><span class="sxs-lookup"><span data-stu-id="02809-785">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="02809-786">Чтобы принять предложение, используйте клавишу TAB.</span><span class="sxs-lookup"><span data-stu-id="02809-786">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="02809-787">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/text-predictions-in-word-outlook)</span><span class="sxs-lookup"><span data-stu-id="02809-787">See details in [blog post](https://insider.office.com/ru-RU/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="02809-788">**Преодолейте языковый барьер с помощью встроенного переводчика.** Надстройки для перевода больше не нужны!</span><span class="sxs-lookup"><span data-stu-id="02809-788">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="02809-789">В сообщении щелкните правой кнопкой мыши, чтобы перевести определенные слова, фразы или весь текст.</span><span class="sxs-lookup"><span data-stu-id="02809-789">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="02809-790">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-790">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="02809-791">**Обновления для задач пользовательского интерфейса:** визуальное обновление элементов задач</span><span class="sxs-lookup"><span data-stu-id="02809-791">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-792">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-792">PowerPoint</span></span>

- <span data-ttu-id="02809-793">**Отрепетируйте презентацию с помощью тренера выступлений.** Получите подсказки, которые помогут удержать аудиторию, в том числе об использовании темпа речи, чрезмерного употребления слов, языка тела и т. д.</span><span class="sxs-lookup"><span data-stu-id="02809-793">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="02809-794">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-794">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="02809-795">Word</span><span class="sxs-lookup"><span data-stu-id="02809-795">Word</span></span>

- <span data-ttu-id="02809-796">**Обновление области "Корректор" (Майкрософт) в классическом приложении Word:** мы обновили текущий интерфейс области "Корректор" в классическом приложении Word.</span><span class="sxs-lookup"><span data-stu-id="02809-796">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="02809-797">**Мгновенные предложения по написанию.** Применяйте рукописный ввод одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="02809-797">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="02809-798">Обновленная панель редактора позволяет легко переходить между предложениями.</span><span class="sxs-lookup"><span data-stu-id="02809-798">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-801">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-801">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-802">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-802">PowerPoint</span></span>

- <span data-ttu-id="02809-803">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="02809-803">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-11"></a><span data-ttu-id="02809-805">Версия 2010: 11 октября</span><span class="sxs-lookup"><span data-stu-id="02809-805">Version 2010: October 11</span></span>
<span data-ttu-id="02809-806">*Версия 2010 (сборка 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="02809-806">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-808">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-808">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-809">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-809">Excel</span></span>

- <span data-ttu-id="02809-810">**Защита данных от вредоносных файлов.** Application Guard помогает защитить вас от вредоносных программ, позволяя читать, печатать и сохранять файлы Office в изолированном контейнере.</span><span class="sxs-lookup"><span data-stu-id="02809-810">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="02809-811">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-811">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="02809-812">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-812">PowerPoint</span></span>

- <span data-ttu-id="02809-813">**Защита данных от вредоносных файлов.** Application Guard помогает защитить вас от вредоносных программ, позволяя читать, печатать и сохранять файлы Office в изолированном контейнере.</span><span class="sxs-lookup"><span data-stu-id="02809-813">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="02809-814">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-814">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="02809-815">Word</span><span class="sxs-lookup"><span data-stu-id="02809-815">Word</span></span>

- <span data-ttu-id="02809-816">**Защита данных от вредоносных файлов.** Application Guard помогает защитить вас от вредоносных программ, позволяя читать, печатать и сохранять файлы Office в изолированном контейнере.</span><span class="sxs-lookup"><span data-stu-id="02809-816">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="02809-817">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-817">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-820">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-820">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-821">Access</span><span class="sxs-lookup"><span data-stu-id="02809-821">Access</span></span>

- <span data-ttu-id="02809-822">Исправлена проблема, из-за которой не удавалось правильно задать положение полосы прокрутки при загрузке окна запроса или схемы данных, сохраненных во время прокрутки.</span><span class="sxs-lookup"><span data-stu-id="02809-822">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="02809-823">Исправлена проблема, из-за которой в области задач "Добавить таблицу" неправильно отображались имена, содержащие '&'.</span><span class="sxs-lookup"><span data-stu-id="02809-823">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="02809-824">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-824">Excel</span></span>

- <span data-ttu-id="02809-825">Исправлена проблема, из-за которой в диаграммах не работал многоуровневый ручной интервал категорий.</span><span class="sxs-lookup"><span data-stu-id="02809-825">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="02809-826">Исправлена проблема с 2D-диаграммами с картами, когда нельзя было задать цвета для максимального, среднего и минимального значений ряда данных с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="02809-826">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="02809-827">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="02809-827">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="02809-828">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="02809-828">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="02809-829">Исправлена проблема, из-за которой при переключении между листами с большим объемом данных могла возникать заметная задержка, если был включен страничный режим.</span><span class="sxs-lookup"><span data-stu-id="02809-829">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="02809-830">Исправлена проблема, из-за которой при добавлении в таблицу, используемую для проверки данных, не обновлялись параметры для всех листов в книге.</span><span class="sxs-lookup"><span data-stu-id="02809-830">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="02809-831">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="02809-831">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="02809-832">Исправлена проблема, которая в некоторых случаях приводила к сбою на листе диаграммы при вводе формулы в строке формул.</span><span class="sxs-lookup"><span data-stu-id="02809-832">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="02809-833">Исправлена проблема с панелью формул Excel, которая не отображалась полностью после отключения от устройства, например с подключении или отклчючении от уадаленного сеанса или при смене монитора.</span><span class="sxs-lookup"><span data-stu-id="02809-833">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="02809-834">OneNote</span><span class="sxs-lookup"><span data-stu-id="02809-834">OneNote</span></span>

- <span data-ttu-id="02809-835">Исправлена проблема, из-за которой пользователь не мог выбрать и скопировать URL-адрес записной книжки из текстового поля в разделе "Файл OutSpace > Сведения".</span><span class="sxs-lookup"><span data-stu-id="02809-835">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="02809-836">Исправлена проблема, из-за которой при наведении указателя мыши на зеленый цвет в селекторе цветов записной книжки появлялось всплывающее окно "красный мел".</span><span class="sxs-lookup"><span data-stu-id="02809-836">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="02809-837">Исправлена проблема, из-за которой OneNote не поддерживал высокую контрастность цветов в полотне для пользовательских тем.</span><span class="sxs-lookup"><span data-stu-id="02809-837">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-838">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-838">Outlook</span></span>

- <span data-ttu-id="02809-839">Исправлена проблема, из-за которой автоматически созданные сообщения отправлялись пустые, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="02809-839">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="02809-840">Исправлена проблема с кэшированием неправильного GUID для папок.</span><span class="sxs-lookup"><span data-stu-id="02809-840">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="02809-841">При копировании и вставке адреса электронной почты в поле "получатель" с отображаемым именем адрес электронной почты не всегда распознается правильно и появляется сообщение о недействительном адресе.</span><span class="sxs-lookup"><span data-stu-id="02809-841">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="02809-842">Эта проблема устранена, то есть имя и адрес электронной почты распознаются правильно, а предупреждение больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="02809-842">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="02809-843">Исправлена проблема, из-за которой общие сетевые папки не возвращали имя родительской папки.</span><span class="sxs-lookup"><span data-stu-id="02809-843">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="02809-844">Вместо сбоя они возвращали пустой путь, который ошибочно отправлялся в основную учетную запись.</span><span class="sxs-lookup"><span data-stu-id="02809-844">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="02809-845">Исправлена проблема, из-за которой параметр "Сохранить как" был недоступен для классических вложений.</span><span class="sxs-lookup"><span data-stu-id="02809-845">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="02809-846">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="02809-846">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="02809-847">Исправлена проблема, из-за которой после повторного открытия черновика в области просмотра "Только для чтения" включалось отслеживание изменений.</span><span class="sxs-lookup"><span data-stu-id="02809-847">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="02809-848">Исправлена проблема, из-за которой сообщения электронной почты скрывались после отключения сортировки почты и выполнения сортировки.</span><span class="sxs-lookup"><span data-stu-id="02809-848">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="02809-849">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="02809-849">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-850">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-850">PowerPoint</span></span>

- <span data-ttu-id="02809-851">Исправлена проблема, из-за которой PowerPoint не экспортировал маркеры списка в виде прямоугольников при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="02809-851">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="02809-852">Исправлена проблема, из-за которой изображение GIF анимировалось только один раз в редакторе и слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="02809-852">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="02809-853">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="02809-853">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="02809-854">Исправлена проблема, из-за которой диалоговое окно завершения сеанса отображалось на странице сводки, если вы переходили с последнего слайда к следующему после нажатия кнопки "Завершить сеанс" и до появления сводки.</span><span class="sxs-lookup"><span data-stu-id="02809-854">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="02809-855">Project</span><span class="sxs-lookup"><span data-stu-id="02809-855">Project</span></span>

- <span data-ttu-id="02809-856">Исправлена проблема, из-за которой метод VBA ConsolidateProjects мог выполнять регистрацию, если вы пытались добавить один проект несколько раз и присвоили параметру AttachToSources значение false.</span><span class="sxs-lookup"><span data-stu-id="02809-856">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="02809-857">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="02809-857">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="02809-858">Исправлена проблема, из-за которой метод VBA ConsolidateProjects мог выполнять регистрацию, если вы пытались добавить один проект несколько раз и присвоили параметру AttachToSources значение false.</span><span class="sxs-lookup"><span data-stu-id="02809-858">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="02809-859">Исправлена проблема, из-за которой могли возникать задержки при переключении представлений и открытии сведений о задаче или проекте при наличии настраиваемых полей с формулами и использовании освоенного объема.</span><span class="sxs-lookup"><span data-stu-id="02809-859">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="02809-860">Исправлена проблема, из-за которой Project мог аварийно завершить работу, если вы применяли группу с помощью представления "Использование ресурсов" или "Лист ресурсов", а затем вставляли столбец.</span><span class="sxs-lookup"><span data-stu-id="02809-860">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="02809-861">Word</span><span class="sxs-lookup"><span data-stu-id="02809-861">Word</span></span>

- <span data-ttu-id="02809-862">Исправлена проблема, из-за которой ссылки на файлы, поддерживающие рабочий процесс, не открывались должным образом.</span><span class="sxs-lookup"><span data-stu-id="02809-862">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="02809-863">Исправлена проблема, из-за после прикосновения к исправлению (вставке или удалению) появлялось всплывающее примечание.</span><span class="sxs-lookup"><span data-stu-id="02809-863">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="02809-864">Исправлена проблема с удалением выносок примечаний в Word.</span><span class="sxs-lookup"><span data-stu-id="02809-864">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="02809-865">Исправлена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-865">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="02809-866">Исправлена проблема с сохранением документа Word, содержащего ссылку и формулу.</span><span class="sxs-lookup"><span data-stu-id="02809-866">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="02809-867">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="02809-867">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-868">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-868">Office Suite</span></span>

- <span data-ttu-id="02809-869">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="02809-869">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="02809-870">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="02809-870">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-october-07"></a><span data-ttu-id="02809-872">Версия 2009: 7 октября</span><span class="sxs-lookup"><span data-stu-id="02809-872">Version 2009: October 07</span></span>
<span data-ttu-id="02809-873">*Версия 2009 (сборка 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="02809-873">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-875">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-875">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-876">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-876">Excel</span></span>

- <span data-ttu-id="02809-877">**Создание типов данных с помощью Power Query:** создание насыщенных типов данных с помощью Power Query из любого источника данных</span><span class="sxs-lookup"><span data-stu-id="02809-877">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-878">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-878">Outlook</span></span>

- <span data-ttu-id="02809-879">**Вам помогает проверка грамматики:** Outlook помечает грамматические ошибки по мере ввода текста, так что вы можете применять исправления одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="02809-879">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="02809-880">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="02809-880">See details in [blog post](https://insider.office.com/ru-RU/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-883">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-883">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-884">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-884">Outlook</span></span>

- <span data-ttu-id="02809-885">Решает проблему, в результате которой при поиске в некэшированных общих календарях не возвращалось результатов.</span><span class="sxs-lookup"><span data-stu-id="02809-885">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="02809-886">Решает проблему, при которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="02809-886">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="02809-887">Решает проблему, которая приводила к появлению периодических отказов при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="02809-887">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-888">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-888">PowerPoint</span></span>

- <span data-ttu-id="02809-889">Установка исправления безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="02809-889">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-890">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="02809-890">Office Suite</span></span>

- <span data-ttu-id="02809-891">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="02809-891">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="02809-892">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="02809-892">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-26"></a><span data-ttu-id="02809-894">Версия 2009: 26 сентября</span><span class="sxs-lookup"><span data-stu-id="02809-894">Version 2009: September 26</span></span>
<span data-ttu-id="02809-895">*Версия 2009 (сборка 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="02809-895">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-897">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-897">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-898">Outlook</span></span>

- <span data-ttu-id="02809-899">Решает проблему, из-за которой некоторые автоматически созданные сообщения электронной почты отправляются без текста сообщения если в строке темы письма она не указана.</span><span class="sxs-lookup"><span data-stu-id="02809-899">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="02809-900">Project</span><span class="sxs-lookup"><span data-stu-id="02809-900">Project</span></span>

- <span data-ttu-id="02809-901">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="02809-901">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-21"></a><span data-ttu-id="02809-903">Версия 2009: 21 сентября</span><span class="sxs-lookup"><span data-stu-id="02809-903">Version 2009: September 21</span></span>
<span data-ttu-id="02809-904">*Версия 2009 (сборка 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="02809-904">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-906">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-906">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="02809-907">Access</span><span class="sxs-lookup"><span data-stu-id="02809-907">Access</span></span>

- <span data-ttu-id="02809-908">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-908">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-909">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-909">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-910">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-910">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="02809-911">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-911">Excel</span></span>

- <span data-ttu-id="02809-912">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="02809-912">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="02809-913">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="02809-913">No conversion required.</span></span><br /><span data-ttu-id="02809-914">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="02809-914">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="02809-915">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-915">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-916">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-916">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-917">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-917">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="02809-918">OneNote</span><span class="sxs-lookup"><span data-stu-id="02809-918">OneNote</span></span>

- <span data-ttu-id="02809-919">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-919">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-920">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-920">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-921">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-921">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="02809-922">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-922">Outlook</span></span>

- <span data-ttu-id="02809-923">**Удаление беседы владельцем сообщения.** Эта функция позволяет удалять беседы владельцу сообщения.</span><span class="sxs-lookup"><span data-stu-id="02809-923">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="02809-924">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="02809-924">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="02809-925">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="02809-925">No conversion required.</span></span><br /><span data-ttu-id="02809-926">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="02809-926">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="02809-927">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-927">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-928">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-928">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-929">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-929">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="02809-930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-930">PowerPoint</span></span>

- <span data-ttu-id="02809-931">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="02809-931">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="02809-932">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="02809-932">No conversion required.</span></span><br /><span data-ttu-id="02809-933">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="02809-933">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="02809-934">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-934">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-935">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-935">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-936">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-936">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="02809-937">Project</span><span class="sxs-lookup"><span data-stu-id="02809-937">Project</span></span>

- <span data-ttu-id="02809-938">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-938">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-939">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-939">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-940">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-940">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="02809-941">Publisher</span><span class="sxs-lookup"><span data-stu-id="02809-941">Publisher</span></span>

- <span data-ttu-id="02809-942">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-942">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-943">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-943">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-944">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-944">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="02809-945">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-945">Visio</span></span>

- <span data-ttu-id="02809-946">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-946">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-947">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-947">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-948">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-948">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="02809-949">Word</span><span class="sxs-lookup"><span data-stu-id="02809-949">Word</span></span>

- <span data-ttu-id="02809-950">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="02809-950">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="02809-951">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="02809-951">No conversion required.</span></span><br /><span data-ttu-id="02809-952">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="02809-952">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="02809-953">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-953">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="02809-954">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="02809-954">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="02809-955">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-955">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-958">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-958">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-959">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-959">PowerPoint</span></span>

- <span data-ttu-id="02809-960">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="02809-960">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-14"></a><span data-ttu-id="02809-962">Версия 2009: 14 сентября</span><span class="sxs-lookup"><span data-stu-id="02809-962">Version 2009: September 14</span></span>
<span data-ttu-id="02809-963">*Версия 2009 (сборка 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="02809-963">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="02809-964">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-964">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-10"></a><span data-ttu-id="02809-967">Версия 2009: 10 сентября</span><span class="sxs-lookup"><span data-stu-id="02809-967">Version 2009: September 10</span></span>
<span data-ttu-id="02809-968">*Версия 2009 (сборка 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="02809-968">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-970">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-970">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-971">Access</span><span class="sxs-lookup"><span data-stu-id="02809-971">Access</span></span>

- <span data-ttu-id="02809-972">Эта проблема уже устранена и больше не должна вызывать сбой.</span><span class="sxs-lookup"><span data-stu-id="02809-972">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="02809-973">Исправлена проблема, из-за которой подключения к базе данных ODBC не работали со сторонними приложениями.</span><span class="sxs-lookup"><span data-stu-id="02809-973">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="02809-974">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-974">Excel</span></span>

- <span data-ttu-id="02809-975">Мы устранили проблему, из-за которой при открытии файла с функцией ПУСТЬ появлялось сообщение: "Обнаружена проблема в содержимом файла "ваш_файл.xlsx".</span><span class="sxs-lookup"><span data-stu-id="02809-975">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="02809-976">Хотите восстановить все, что возможно?</span><span class="sxs-lookup"><span data-stu-id="02809-976">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="02809-977">Если вы доверяете источнику этой книги, выберите Да".</span><span class="sxs-lookup"><span data-stu-id="02809-977">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="02809-978">Исправлена проблема, из-за которой при вводе имени формулы со скобками и вызове справки с помощью клавиши F1 не отображался раздел справки, относящийся к этой формуле.</span><span class="sxs-lookup"><span data-stu-id="02809-978">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="02809-979">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="02809-979">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="02809-980">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="02809-980">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="02809-981">Исправлен сбой, связанный со ссылками на надстройки XLAM и именованными диапазонами.</span><span class="sxs-lookup"><span data-stu-id="02809-981">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="02809-982">Исправлена проблема, при которой при назначении пользователем настраиваемого стиля динамическому массиву появлялась ошибка: "Изменение части массива недопустимо".</span><span class="sxs-lookup"><span data-stu-id="02809-982">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="02809-983">Это устаревшее ограничение, которое следовало убрать.</span><span class="sxs-lookup"><span data-stu-id="02809-983">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="02809-984">Исправлена проблема, из-за которой макросы, назначенные кнопкам, не работали после восстановления более ранней версии файла.</span><span class="sxs-lookup"><span data-stu-id="02809-984">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="02809-985">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="02809-985">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-986">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-986">Outlook</span></span>

- <span data-ttu-id="02809-987">Исправлена проблема, которая обеспечивала включение/отключение параметров входа по умолчанию через групповые политики.</span><span class="sxs-lookup"><span data-stu-id="02809-987">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="02809-988">Исправлена проблема, при которой устаревшее имя домена для отправителя сообщения электронной почты с правами помощника или менеджера сохранялось и показывалось при перемещении черновика письма между папками.</span><span class="sxs-lookup"><span data-stu-id="02809-988">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="02809-989">Исправлена проблем, из-за которой у некоторых пользователей Outlook запускался в автономном состоянии, пока они не выбирали сетевой режим работы вручную.</span><span class="sxs-lookup"><span data-stu-id="02809-989">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="02809-990">Исправлена проблема, когда при запуске кода VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") после включения однострочной ленты (SLR) выдавалась ошибка среды выполнения.</span><span class="sxs-lookup"><span data-stu-id="02809-990">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="02809-991">Исправлена проблема, при которой кнопки "OK" и "Отмена" в диалогах с автоматическими ответами были не видны в системах с высоким разрешением (например, 1750 x 1920), если выбран большой размер текста (например, 175%).</span><span class="sxs-lookup"><span data-stu-id="02809-991">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="02809-992">Исправлена проблема, при которой в результате отправки приглашения на собрание из пустой группы контактов в другую группу контактов появлялась ошибка.</span><span class="sxs-lookup"><span data-stu-id="02809-992">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="02809-993">Исправлена проблема, которая вызывала сбой при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-993">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="02809-994">Исправлена ошибка, при которой в случае, когда требуется, чтобы в групповой политике всегда была активна надстройка, надстройка мониторинга становится недоступной, чтобы не дать пользователям отключить надстройку.</span><span class="sxs-lookup"><span data-stu-id="02809-994">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="02809-995">Исправлена проблема, из-за которой пользователи могли отправлять содержимое письма, к которому применена политика "Не пересылать", в OneNote, если выбрано несколько сообщений.</span><span class="sxs-lookup"><span data-stu-id="02809-995">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="02809-996">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="02809-996">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="02809-997">Исправлена проблема, из-за которой атрибуты учетной записи пользователя в Active Directory для "otherTelephone" и "otherHomePhone" не сопоставлялись с соответствующими атрибутами LDAP Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-997">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="02809-998">Это изменение исправляет проблему, из-за которой страница "Собрание" продолжала отображаться после того, как пользователь переключал вкладки со страницы "Собрание" на страницу "Помощник по планированию".</span><span class="sxs-lookup"><span data-stu-id="02809-998">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-999">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-999">PowerPoint</span></span>

- <span data-ttu-id="02809-1000">Исправлена проблема, из-за которой при определенных условиях пользователи не видели ленту/заголовок окна.</span><span class="sxs-lookup"><span data-stu-id="02809-1000">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="02809-1001">Исправлена ошибка, при которой после загрузки PowerPoint, вставки слайда, открытия и закрытия панели комментариев, слайды в области эскизов отображались с наложением.</span><span class="sxs-lookup"><span data-stu-id="02809-1001">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="02809-1002">Исправлена проблема с отключенной функцией вставки видео.</span><span class="sxs-lookup"><span data-stu-id="02809-1002">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="02809-1003">Исправлена проблема, из-за которой видео не воспроизводились автоматически в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="02809-1003">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="02809-1004">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1004">Project</span></span>

- <span data-ttu-id="02809-1005">Исправлена проблема, при которой оставшиеся затраты не подсчитываются правильно, если у ресурса есть несколько таблиц норм затрат.</span><span class="sxs-lookup"><span data-stu-id="02809-1005">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="02809-1006">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1006">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="02809-1007">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-1007">Visio</span></span>

- <span data-ttu-id="02809-1008">Пользователи сообщают о сбоях динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="02809-1008">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="02809-1009">Самый распространенный сбой в вилке за июль.</span><span class="sxs-lookup"><span data-stu-id="02809-1009">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="02809-1010">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1010">Word</span></span>

- <span data-ttu-id="02809-1011">Исправлена проблема, из-за которой при нажатии пользователя на комментарий вокруг комментария отображалась граница.</span><span class="sxs-lookup"><span data-stu-id="02809-1011">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="02809-1012">Исправлена проблема, из-за которой неправильно отображался значок маркера.</span><span class="sxs-lookup"><span data-stu-id="02809-1012">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="02809-1013">Исправлена проблема, из-за которой пользователь не мог выйти из колонтитулов при выборе примечания.</span><span class="sxs-lookup"><span data-stu-id="02809-1013">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="02809-1014">Исправлена проблема, из-за которой Word мог аварийно завершить работу после удаления примечаний.</span><span class="sxs-lookup"><span data-stu-id="02809-1014">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="02809-1015">Исправлена проблема, из-за которой при создании черновика комментария и привязки его к линии, на которой уже есть комментарии, то черновик имел неверный порядок по отношению к выделенному комментарию в SideTrack.</span><span class="sxs-lookup"><span data-stu-id="02809-1015">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="02809-1016">Исправлена проблема, при которой фокус не переходил на панели комментариев, если масштаб документа был 160% или более, а панель комментариев была не видна.</span><span class="sxs-lookup"><span data-stu-id="02809-1016">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="02809-1017">Исправлена проблема, не позволявшая пользователям просматривать цепочки примечаний, выходивших за границы ответвления, так как прокрутка в ответвлении не работала.</span><span class="sxs-lookup"><span data-stu-id="02809-1017">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="02809-1018">Исправлена проблема, из-за которой поиск разрешенных примечаний в панели ответвления не работал.</span><span class="sxs-lookup"><span data-stu-id="02809-1018">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="02809-1019">Исправлена проблема, при которой комментарии для одного документа показывались в других открытых документах после переключения между открытыми документами.</span><span class="sxs-lookup"><span data-stu-id="02809-1019">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="02809-1020">Исправлена проблема, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="02809-1020">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="02809-1021">Исправлена проблема, из-за которой в некоторых случаях маркеры списка отображались неверно в сообщении.</span><span class="sxs-lookup"><span data-stu-id="02809-1021">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="02809-1022">Исправлена проблема с макросом, из-за которой AutoOpen запускался до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="02809-1022">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-1023">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1023">Office Suite</span></span>

- <span data-ttu-id="02809-1024">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="02809-1024">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="02809-1025">Исправлена проблема в диалоговом окне "Сжатие рисунка", из-за которой некоторые выбранные пользователем параметры разрешения не сохранялись.</span><span class="sxs-lookup"><span data-stu-id="02809-1025">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="02809-1026">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="02809-1026">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-04"></a><span data-ttu-id="02809-1028">Версия 2008: 4 сентября</span><span class="sxs-lookup"><span data-stu-id="02809-1028">Version 2008: September 04</span></span>
<span data-ttu-id="02809-1029">*Версия 2008 (сборка 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="02809-1029">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1031">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1031">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="02809-1032">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1032">Office Suite</span></span>

- <span data-ttu-id="02809-1033">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="02809-1033">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-02"></a><span data-ttu-id="02809-1035">Версия 2008: 2 сентября</span><span class="sxs-lookup"><span data-stu-id="02809-1035">Version 2008: September 02</span></span>
<span data-ttu-id="02809-1036">*Версия 2008 (сборка 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="02809-1036">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1038">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1038">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1039">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1039">Excel</span></span>

- <span data-ttu-id="02809-1040">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="02809-1040">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="02809-1041">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1041">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="02809-1042">**Быстрые правки с помощью пера в Excel.** Перо для рукописного ввода и быстрого изменения данных</span><span class="sxs-lookup"><span data-stu-id="02809-1042">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1045">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1045">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1046">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1046">Excel</span></span>

- <span data-ttu-id="02809-1047">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="02809-1047">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="02809-1048">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1048">Word</span></span>

- <span data-ttu-id="02809-1049">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="02809-1049">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-27"></a><span data-ttu-id="02809-1051">Версия 2008: 27 августа</span><span class="sxs-lookup"><span data-stu-id="02809-1051">Version 2008: August 27</span></span>
<span data-ttu-id="02809-1052">*Версия 2008 (сборка 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="02809-1052">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1056">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1056">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1057">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1057">Outlook</span></span>

- <span data-ttu-id="02809-1058">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="02809-1058">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="02809-1059">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="02809-1059">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="02809-1060">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="02809-1060">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="02809-1061">Исправлена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="02809-1061">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="02809-1062">Исправлена проблема, из-за которой возникали аномалии при использовании пользователями компактного представления.</span><span class="sxs-lookup"><span data-stu-id="02809-1062">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1063">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1063">Word</span></span>

- <span data-ttu-id="02809-1064">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="02809-1064">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="02809-1065">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec</span><span class="sxs-lookup"><span data-stu-id="02809-1065">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-25"></a><span data-ttu-id="02809-1067">Версия 2008: 25 августа</span><span class="sxs-lookup"><span data-stu-id="02809-1067">Version 2008: August 25</span></span>
<span data-ttu-id="02809-1068">*Версия 2008 (сборка 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="02809-1068">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1070">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1070">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1071">Outlook</span></span>

- <span data-ttu-id="02809-1072">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите условия поиска Outlook, вы получаете в предложениях наиболее подходящую электронную почту.</span><span class="sxs-lookup"><span data-stu-id="02809-1072">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1075">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1075">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1076">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1076">Outlook</span></span>

- <span data-ttu-id="02809-1077">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="02809-1077">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="02809-1078">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="02809-1078">Do you want to download them anyway?</span></span> <span data-ttu-id="02809-1079">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="02809-1079">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="02809-1080">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1080">Project</span></span>

- <span data-ttu-id="02809-1081">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="02809-1081">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="02809-1082">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1082">Word</span></span>

- <span data-ttu-id="02809-1083">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="02809-1083">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-17"></a><span data-ttu-id="02809-1085">Версия 2008: 17 августа</span><span class="sxs-lookup"><span data-stu-id="02809-1085">Version 2008: August 17</span></span>
<span data-ttu-id="02809-1086">*Версия 2008 (сборка 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="02809-1086">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1088">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1088">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1089">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1089">Outlook</span></span>

- <span data-ttu-id="02809-1090">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="02809-1090">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="02809-1091">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="02809-1091">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="02809-1092">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="02809-1092">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="02809-1093">Устранена проблема, из-за которой контекстное меню, вызываемое щелчком правой кнопки мыши, не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="02809-1093">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-11"></a><span data-ttu-id="02809-1095">Версия 2008: 11 августа</span><span class="sxs-lookup"><span data-stu-id="02809-1095">Version 2008: August 11</span></span>
<span data-ttu-id="02809-1096">*Версия 2008 (сборка 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="02809-1096">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="02809-1097">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="02809-1097">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1099">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1099">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-1100">Доступ</span><span class="sxs-lookup"><span data-stu-id="02809-1100">Access</span></span>

- <span data-ttu-id="02809-1101">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="02809-1101">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="02809-1102">Если у вас установлен Office 365, вам больше не требуется устанавливать наш распространяемый модуль ACE, чтобы предоставлять доступ к ACE за пределами экосистемы Office.</span><span class="sxs-lookup"><span data-stu-id="02809-1102">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="02809-1103">Поэтому пользователям Office 365 больше не нужен распространяемый модуль ACE и у них не должна возникать эта проблема.</span><span class="sxs-lookup"><span data-stu-id="02809-1103">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="02809-1104">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="02809-1104">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="02809-1105">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1105">Excel</span></span>

- <span data-ttu-id="02809-1106">Мы исправили проблему, когда при изменении порядка рядов диаграммы соответствующие флажки не были упорядочены по рядам.</span><span class="sxs-lookup"><span data-stu-id="02809-1106">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="02809-1107">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="02809-1107">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="02809-1108">Исправлена проблема, из-за которой диаграммы не всегда обновлялись ожидаемым образом, если для книги был включен параметр ForceFullCalculation с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="02809-1108">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="02809-1109">Исправлена проблема, из-за которой копия изображения с заливкой радиальным градиентом не соответствовала оригиналу.</span><span class="sxs-lookup"><span data-stu-id="02809-1109">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="02809-1110">OneNote</span><span class="sxs-lookup"><span data-stu-id="02809-1110">OneNote</span></span>

- <span data-ttu-id="02809-1111">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="02809-1111">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1112">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1112">Outlook</span></span>

- <span data-ttu-id="02809-1113">Исправлена проблема с созданием нескольких профилей в Outlook из одного домена электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-1113">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="02809-1114">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="02809-1114">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="02809-1115">Устранена проблема, приводившая к отсутствию значка блокировки в заголовке зашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="02809-1115">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="02809-1116">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="02809-1116">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="02809-1117">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="02809-1117">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="02809-1118">Исправлена проблема, из-за которой кнопка печати отображалась в отключенном состоянии даже при наличии у пользователя соответствующих разрешений на печать.</span><span class="sxs-lookup"><span data-stu-id="02809-1118">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="02809-1119">Устранена проблема, приводившая к удалению вложений из сообщений S/MIME при отправке в незашифрованном виде.</span><span class="sxs-lookup"><span data-stu-id="02809-1119">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="02809-1120">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="02809-1120">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="02809-1121">Устранена проблема, из-за которой вложения повреждались при отправке незашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="02809-1121">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="02809-1122">Устранена проблема, из-за которой получатели не могли сохранять сообщения с защищенными правами, даже если отправитель предоставил разрешение на сохранение.</span><span class="sxs-lookup"><span data-stu-id="02809-1122">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="02809-1123">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="02809-1123">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="02809-1124">Исправлена проблема, из-за которой в Outlook некорректно отображались разрывы строк в содержимом файла Markdown.</span><span class="sxs-lookup"><span data-stu-id="02809-1124">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="02809-1125">Устранена проблема, приводившая к усечению некоторых подписей параметров расширенного поиска на некоторых языках.</span><span class="sxs-lookup"><span data-stu-id="02809-1125">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1126">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1126">PowerPoint</span></span>

- <span data-ttu-id="02809-1127">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="02809-1127">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="02809-1128">Исправлена проблема с кнопкой Forms в PowerPoint, которая не позволяла создавать формы, если был запрещен доступ к Магазину Office.</span><span class="sxs-lookup"><span data-stu-id="02809-1128">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1129">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1129">Project</span></span>

- <span data-ttu-id="02809-1130">Исправлена проблема, из-за которой задачи, перечисленные в представлении доски задач, не синхронизировались с диалоговым окном "Назначение ресурсов".</span><span class="sxs-lookup"><span data-stu-id="02809-1130">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="02809-1131">Исправлена проблема, из-за которой при попытке сохранить файл PDF или XPS из Project в библиотеке документов SharePoint ничего не происходило.</span><span class="sxs-lookup"><span data-stu-id="02809-1131">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="02809-1132">Исправлена проблема, из-за которой при копировании и вставке задачи с несколькими зависимостями не все зависимости копировались правильно.</span><span class="sxs-lookup"><span data-stu-id="02809-1132">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="02809-1133">Исправлена проблема, из-за которой для списка задач SharePoint могли быть отключены кнопки ленты на второй вкладке.</span><span class="sxs-lookup"><span data-stu-id="02809-1133">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="02809-1134">Skype</span><span class="sxs-lookup"><span data-stu-id="02809-1134">Skype</span></span>

- <span data-ttu-id="02809-1135">Оттенок кожи танцующего смайлика изменен на нейтральный цвет</span><span class="sxs-lookup"><span data-stu-id="02809-1135">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="02809-1136">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-1136">Visio</span></span>

- <span data-ttu-id="02809-1137">После этого исправления, если пользователь приостанавливает выполнение команды удаления каким-либо способом (в данном случае с помощью надстройки), не возникает утечка памяти и компьютер не затрагивается.</span><span class="sxs-lookup"><span data-stu-id="02809-1137">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1138">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1138">Word</span></span>

- <span data-ttu-id="02809-1139">Исправлена проблема, из-за которой Word переставал отвечать на запросы после вставки текста и изображения в поле примечаний.</span><span class="sxs-lookup"><span data-stu-id="02809-1139">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="02809-1140">Исправлена проблема, из-за которой копия изображения с заливкой радиальным градиентом не соответствовала оригиналу.</span><span class="sxs-lookup"><span data-stu-id="02809-1140">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="02809-1141">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="02809-1141">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="02809-1142">Исправлена проблема, из-за которой при добавлении примечаний для отслеживания изменений неожиданно открывалась область исправлений.</span><span class="sxs-lookup"><span data-stu-id="02809-1142">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="02809-1143">Исправлена проблема, из-за которой команда "Корректор" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="02809-1143">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="02809-1144">Исправлена проблема, из-за которой команда "Показать разметку" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="02809-1144">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="02809-1145">Исправлена проблема, из-за которой кнопка "Создать примечание" отключалась после удаления последнего примечания.</span><span class="sxs-lookup"><span data-stu-id="02809-1145">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="02809-1146">Исправлена проблема, из-за которой параметр "Определенные пользователи" для отслеживания изменений был отключен.</span><span class="sxs-lookup"><span data-stu-id="02809-1146">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="02809-1147">Исправлена проблема, из-за которой ссылки на документы не вставлялись в поле примечаний с помощью раскрывающегося списка "Ссылка" вкладки "Вставка".</span><span class="sxs-lookup"><span data-stu-id="02809-1147">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="02809-1148">Исправлены случайные зависания при открытии HTML-файлов.</span><span class="sxs-lookup"><span data-stu-id="02809-1148">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="02809-1149">Исправлена проблема в пользовательском XML, из-за которой состояние примечаний могло исчезать при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="02809-1149">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="02809-1150">Мы исправили проблему, когда после добавления изображения, содержащего гиперссылку, количество гиперссылок в коллекции гиперссылок VBA было наверно подсчитано.</span><span class="sxs-lookup"><span data-stu-id="02809-1150">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="02809-1151">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта.</span><span class="sxs-lookup"><span data-stu-id="02809-1151">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="02809-1152">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="02809-1152">This is now fixed.</span></span>

- <span data-ttu-id="02809-1153">Исправлена проблема, из-за которой после открытия пользователем нового окна приложения из панели задач и создания пустого документа создавались дополнительные файлы.</span><span class="sxs-lookup"><span data-stu-id="02809-1153">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="02809-1154">Исправлена проблема, из-за которой в случае редактирования документа и утраты разрешений пользователь не уведомлялся о необходимости повторной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="02809-1154">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-august-05"></a><span data-ttu-id="02809-1156">Версия 2007: 5 августа</span><span class="sxs-lookup"><span data-stu-id="02809-1156">Version 2007: August 05</span></span>
<span data-ttu-id="02809-1157">*Версия 2007 (сборка 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="02809-1157">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1161">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1161">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1162">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1162">Outlook</span></span>

- <span data-ttu-id="02809-1163">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="02809-1163">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="02809-1164">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="02809-1164">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="02809-1165">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1165">Project</span></span>

- <span data-ttu-id="02809-1166">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="02809-1166">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-29"></a><span data-ttu-id="02809-1168">Версия 2007: 29 июля</span><span class="sxs-lookup"><span data-stu-id="02809-1168">Version 2007: July 29</span></span>
<span data-ttu-id="02809-1169">*Версия 2007 (сборка 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="02809-1169">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1171">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1171">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1172">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1172">Excel</span></span>

- <span data-ttu-id="02809-1173">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 E5/A5 или Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="02809-1173">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="02809-1174">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="02809-1174">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="02809-1175">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="02809-1175">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="02809-1176">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1176">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="02809-1177">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="02809-1177">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1178">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1178">Outlook</span></span>

- <span data-ttu-id="02809-1179">**Выбор места для поиска.** Новый раскрывающийся список области поиска позволит вам легко изменять параметры поиска и переключаться между текущей папкой и текущим почтовым ящиком.</span><span class="sxs-lookup"><span data-stu-id="02809-1179">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="02809-1180">Благодарим всех из Coming Soon, кто прислал отзывы о новом интерфейсе Search at Top.</span><span class="sxs-lookup"><span data-stu-id="02809-1180">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="02809-1181">Этот дизайн и обновление — результат этих отзывов!</span><span class="sxs-lookup"><span data-stu-id="02809-1181">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="02809-1182">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1182">Word</span></span>

- <span data-ttu-id="02809-1183">**Усовершенствована функция совместной работы с помощью современных комментариев.** Добавление примечаний к объектам, @упоминание коллег и завершение цепочек комментариев для повышения удобства совместной работы.</span><span class="sxs-lookup"><span data-stu-id="02809-1183">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="02809-1184">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1184">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1187">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1187">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1188">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1188">Outlook</span></span>

- <span data-ttu-id="02809-1189">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="02809-1189">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="02809-1190">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="02809-1190">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="02809-1191">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="02809-1191">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-27"></a><span data-ttu-id="02809-1193">Версия 2007: 27 июля</span><span class="sxs-lookup"><span data-stu-id="02809-1193">Version 2007: July 27</span></span>
<span data-ttu-id="02809-1194">*Версия 2007 (сборка 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="02809-1194">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="02809-1195">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1195">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="02809-1196">Версия 2007: 20 июля</span><span class="sxs-lookup"><span data-stu-id="02809-1196">Version 2007: July 20</span></span>
<span data-ttu-id="02809-1197">*Версия 2007 (сборка 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="02809-1197">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="02809-1198">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1198">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="02809-1199">Версия 2007: 15 июля</span><span class="sxs-lookup"><span data-stu-id="02809-1199">Version 2007: July 15</span></span>
<span data-ttu-id="02809-1200">*Версия 2007 (сборка 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="02809-1200">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1202">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1202">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1203">Excel</span></span>

- <span data-ttu-id="02809-1204">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="02809-1204">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="02809-1205">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1205">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1208">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1208">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-1209">Доступ</span><span class="sxs-lookup"><span data-stu-id="02809-1209">Access</span></span>

- <span data-ttu-id="02809-1210">Исправлена проблема, из-за которой диспетчер связанных таблиц запрашивал первичный ключ при обновлении связанной таблицы SQL.</span><span class="sxs-lookup"><span data-stu-id="02809-1210">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="02809-1211">Исправлена проблема, из-за которой запросы в редакторе запросов не отображались при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="02809-1211">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="02809-1212">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="02809-1212">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="02809-1213">Устранена проблема, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="02809-1213">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="02809-1214">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1214">Excel</span></span>

- <span data-ttu-id="02809-1215">Исправлена проблема, из-за которой URL-адреса, отличные от HTTP или HTTPS, не отображались в списке недавно использовавшихся.</span><span class="sxs-lookup"><span data-stu-id="02809-1215">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="02809-1216">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы возникает ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="02809-1216">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="02809-1217">Устранена проблема, связанная с тем, что таблицы моделей данных, созданные в некоторых версиях Excel, не отображались в представлении "Предварительный просмотр таблицы" даже при отсутствии изменений запроса, связанного с таблицей.</span><span class="sxs-lookup"><span data-stu-id="02809-1217">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="02809-1218">Устранена проблема, из-за которой переставали работать формулы при отключении параметра "Игнорировать тип ссылки" в диалоговом окне "Задать имя \ Применение имен".</span><span class="sxs-lookup"><span data-stu-id="02809-1218">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="02809-1219">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении книги в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="02809-1219">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="02809-1220">Исправлена проблема, из-за которой книги были доступны только для чтения, если файл рекомендовался только для чтения.</span><span class="sxs-lookup"><span data-stu-id="02809-1220">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="02809-1221">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы возникает ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="02809-1221">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="02809-1222">Устранена проблема, из-за которой нельзя было правильно отформатировать основные линии сетки лепестковых диаграмм.</span><span class="sxs-lookup"><span data-stu-id="02809-1222">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="02809-1223">Исправлена проблема, из-за которой очистка расширенного фильтра данных могла привести к потере форматирования таблицы.</span><span class="sxs-lookup"><span data-stu-id="02809-1223">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="02809-1224">Исправлена проблема, из-за которой в подписи к документу вместо имени внедренного PDF-документа отображался весь путь к нему.</span><span class="sxs-lookup"><span data-stu-id="02809-1224">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="02809-1225">Исправлена проблема, из-за которой мог произойти сбой после отключения облачного соединителя Wolfram с последующим сохранением и повторным открытием книги Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-1225">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="02809-1226">Исправлена проблема, вызывавшая сбой в результате загрузки Excel при включенной надстройке "Поиск решения".</span><span class="sxs-lookup"><span data-stu-id="02809-1226">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-1227">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1227">Outlook</span></span>

- <span data-ttu-id="02809-1228">Исправлена проблема, вызывавшая зависание приложения Outlook, когда в строке "Кому" было указано более 130 получателей. Кроме того, мы повысили производительность отрисовки текста.</span><span class="sxs-lookup"><span data-stu-id="02809-1228">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="02809-1229">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="02809-1229">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="02809-1230">Исправлена проблема, из-за которой в области To Do для событий длительностью более двух дней указывалось одинаковое время окончания для всех последующих дней.</span><span class="sxs-lookup"><span data-stu-id="02809-1230">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="02809-1231">Исправлена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="02809-1231">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="02809-1232">Исправлена проблема, из-за которой пользователи не могли "отправить как" или "отправить от имени" группы рассылки.</span><span class="sxs-lookup"><span data-stu-id="02809-1232">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="02809-1233">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="02809-1233">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="02809-1234">Исправлена проблема, приводившая к отображению следующей ошибки при закрытии ранее сохраненной встречи: "Не удалось сохранить элемент, так как он был изменен другим пользователем или в другом окне.</span><span class="sxs-lookup"><span data-stu-id="02809-1234">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="02809-1235">Создать копию в папке для элемента по умолчанию?"</span><span class="sxs-lookup"><span data-stu-id="02809-1235">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="02809-1236">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="02809-1236">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="02809-1237">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="02809-1237">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="02809-1238">Исправлена проблема, из-за которой у пользователей Outlook после использования общих календарей на несколько минут переставал обновляться список сообщений.</span><span class="sxs-lookup"><span data-stu-id="02809-1238">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="02809-1239">Исправлена проблема, препятствовавшая отображению точного времени в напоминаниях календаря для собраний, до наступления которых осталось меньше недели.</span><span class="sxs-lookup"><span data-stu-id="02809-1239">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="02809-1240">Исправлена проблема, из-за которой вставка изображения в текст сообщения с последующим сохранением сообщения в виде черновика приводила к изменению размера изображения.</span><span class="sxs-lookup"><span data-stu-id="02809-1240">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="02809-1241">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="02809-1241">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="02809-1242">Исправлена проблема, из-за которой даты в мини-календаре не выделялись полужирным шрифтом для пользователей в Японии.</span><span class="sxs-lookup"><span data-stu-id="02809-1242">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-1243">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1243">PowerPoint</span></span>

- <span data-ttu-id="02809-1244">Исправлена проблема, из-за которой в галерее совместного редактирования не обновлялся цветовой индикатор присутствия пользователя во время совместного редактирования в реальном времени.</span><span class="sxs-lookup"><span data-stu-id="02809-1244">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="02809-1245">Исправлена проблема, из-за которой при вставке HTML в область текста на слайде производилась вставка в текстовое поле, созданное в верхней части слайда.</span><span class="sxs-lookup"><span data-stu-id="02809-1245">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="02809-1246">Исправлена проблема, из-за которой возникало необработанное исключение при выделении всех слайдов в режиме докладчика и выходе из режима докладчика с помощью клавиш ALT+TAB, возврате в слайд-шоу и щелчке по команде "Завершить слайд-шоу".</span><span class="sxs-lookup"><span data-stu-id="02809-1246">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="02809-1247">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1247">Project</span></span>

- <span data-ttu-id="02809-1248">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1248">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="02809-1249">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="02809-1249">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="02809-1250">Исправлена проблема, из-за которой мог возникнуть сбой при открытии определенных XML-файлов.</span><span class="sxs-lookup"><span data-stu-id="02809-1250">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="02809-1251">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="02809-1251">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="02809-1252">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости будут скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="02809-1252">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="02809-1253">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="02809-1253">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="02809-1254">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-1254">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="02809-1255">Исправлена проблема, из-за которой процент выполнения задачи был менее 100 %, если задачи с фиксированной длительностью выполнены на 100 %, но не указано фактическое окончание.</span><span class="sxs-lookup"><span data-stu-id="02809-1255">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="02809-1256">Устранена проблема, из-за которой при сбросе или обновлении базового плана могли изменяться показатели расходов или рабочих ресурсов тех или иных этапов бюджета, и базовый план мог содержать неправильные значения статей бюджета.</span><span class="sxs-lookup"><span data-stu-id="02809-1256">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="02809-1257">Исправлена проблема, из-за которой ссылки планировщика Project в средах GCC были отключены.</span><span class="sxs-lookup"><span data-stu-id="02809-1257">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="02809-1258">Исправлена проблема, из-за которой не удавалось открыть файл Project из библиотеки документов SharePoint, если библиотека находилась в современном режиме.</span><span class="sxs-lookup"><span data-stu-id="02809-1258">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="02809-1259">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1259">Word</span></span>

- <span data-ttu-id="02809-1260">Исправлена проблема, из-за которой не работала функция очистки форматирования в области примечаний с помощью кнопки "Очистить форматирование" на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="02809-1260">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="02809-1261">Исправлена проблема, из-за которой текст, вставленный в изображение в формате SVG, был неудобочитаемым после добавления в файл Word, Excel или PowerPoint, сохранения и закрытия файла, а затем его повторного открытия.</span><span class="sxs-lookup"><span data-stu-id="02809-1261">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="02809-1262">Исправлена проблема, из-за которой изменение размера таблицы при скрытой линейке приводило к миганию других приложений, работающих на заднем фоне.</span><span class="sxs-lookup"><span data-stu-id="02809-1262">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="02809-1263">Исправлена проблема, из-за которой в режиме совместного редактирования ответы на примечания иногда не отображались в области примечаний, но отображались в области изменений.</span><span class="sxs-lookup"><span data-stu-id="02809-1263">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="02809-1264">Исправлена проблема в режиме совместного редактирования: теперь при возникновении конфликта объединения изменений при том, что пользователь уже выбрал отмену изменений, вариант сохранения или отмены изменений больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="02809-1264">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="02809-1265">Исправлена проблема, из-за которой цвет гиперссылки HTML отображался неправильно.</span><span class="sxs-lookup"><span data-stu-id="02809-1265">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="02809-1266">Исправлена проблема, из-за которой в тех случаях, когда в Word имелся список более чем 50 часто открываемых документов, после сохранения и открытия документа отображался журнал изменений, хотя никаких изменений в документ не вносилось.</span><span class="sxs-lookup"><span data-stu-id="02809-1266">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="02809-1267">Исправлена проблема с автосохранением при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="02809-1267">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="02809-1268">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="02809-1268">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-1269">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1269">Office Suite</span></span>

- <span data-ttu-id="02809-1270">При закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="02809-1270">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="02809-1271">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="02809-1271">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="02809-1272">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="02809-1272">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-july-09"></a><span data-ttu-id="02809-1274">Версия 2006: 09 июля</span><span class="sxs-lookup"><span data-stu-id="02809-1274">Version 2006: July 09</span></span>
<span data-ttu-id="02809-1275">*Версия 2006 (сборка 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="02809-1275">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1277">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1277">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1278">Excel</span></span>

- <span data-ttu-id="02809-1279">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="02809-1279">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="02809-1280">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1280">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="02809-1281">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="02809-1281">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="02809-1282">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="02809-1282">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="02809-1283">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1283">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="02809-1284">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="02809-1284">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="02809-1285">**Сочетания клавиш в Excel.** Обновлены сочетания клавиш в Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1285">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1286">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1286">Outlook</span></span>

- <span data-ttu-id="02809-1287">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="02809-1287">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="02809-1288">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-1288">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1291">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1291">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-1292">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1292">Access</span></span>

- <span data-ttu-id="02809-1293">Эта проблема устранена, и скоро вы сможете без проблем добавлять связанные таблицы SQL, содержащие поле удостоверения (например, счетчика), в Access.</span><span class="sxs-lookup"><span data-stu-id="02809-1293">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="02809-1294">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1294">Excel</span></span>

- <span data-ttu-id="02809-1295">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="02809-1295">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1296">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1296">Outlook</span></span>

- <span data-ttu-id="02809-1297">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="02809-1297">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="02809-1298">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1298">Office Suite</span></span>

- <span data-ttu-id="02809-1299">Мы отправили часть AppV51 на доработку, чтобы исправить в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="02809-1299">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="02809-1300">В работе узла Office в Windows происходил сбой при активации надстройки и при значении типа TabProcGrowth в реестре равному "REG_SZ", а также при значении "0".</span><span class="sxs-lookup"><span data-stu-id="02809-1300">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="02809-1301">Значение TabProcGrowth в реестре может находиться в одном из указанных путей: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main. Это изменение исправит проблему.</span><span class="sxs-lookup"><span data-stu-id="02809-1301">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-25"></a><span data-ttu-id="02809-1303">Версия 2006: 25 июня</span><span class="sxs-lookup"><span data-stu-id="02809-1303">Version 2006: June 25</span></span>
<span data-ttu-id="02809-1304">*Версия 2006 (сборка 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="02809-1304">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1306">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1306">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="02809-1307">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-1307">Visio</span></span>

- <span data-ttu-id="02809-1308">**Создание профессиональных диаграмм Visio в Excel.** Создавайте блок-схемы или организационные диаграммы, основанные на данных на листе.</span><span class="sxs-lookup"><span data-stu-id="02809-1308">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1311">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1311">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-1312">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1312">Access</span></span>

- <span data-ttu-id="02809-1313">Эта проблема уже устранена.</span><span class="sxs-lookup"><span data-stu-id="02809-1313">This problem is now resolved.</span></span> <span data-ttu-id="02809-1314">Сообщите нам, если вы столкнетесь с другими проблемами, связанными с этим процессом.</span><span class="sxs-lookup"><span data-stu-id="02809-1314">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-1315">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1315">Outlook</span></span>

- <span data-ttu-id="02809-1316"><span style="display:inline !important;">Исправлена проблема, из-за которой <span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">дату создания&nbsp; вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как &nbsp;1 января 4501 г.</span></span><span class="sxs-lookup"><span data-stu-id="02809-1316"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="02809-1317"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Исправлена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span></span><span class="sxs-lookup"><span data-stu-id="02809-1317"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="02809-1318"><span style="display:inline !important;">Исправлена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span></span><span class="sxs-lookup"><span data-stu-id="02809-1318"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="02809-1319"><span style="display:inline !important;">Исправлена проблема, из-за которой поиск возможности предложения функции не возвращал результатов и не позволял пользователям поделиться идеями.</span></span><span class="sxs-lookup"><span data-stu-id="02809-1319"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-18"></a><span data-ttu-id="02809-1321">Версия 2006: 18 июня</span><span class="sxs-lookup"><span data-stu-id="02809-1321">Version 2006: June 18</span></span>
<span data-ttu-id="02809-1322">*Версия 2006 (сборка 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="02809-1322">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1324">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1325">Excel</span></span>



- <span data-ttu-id="02809-1326">**Сохранение в закрепленные папки.** Закрепление папок сделает сохранение файлов Office проще. Мы получили отзывы о том, что пользователям нужно больше удобства и контроля при сохранении новых файлов в папки.</span><span class="sxs-lookup"><span data-stu-id="02809-1326">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="02809-1327">Мы рады предоставить вам новую возможность: закрепление папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="02809-1327">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="02809-1328">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1328">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="02809-1329">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="02809-1329">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1330">PowerPoint</span></span>

- <span data-ttu-id="02809-1331">**Сохранение в закрепленные папки.** Закрепление папок сделает сохранение файлов Office проще. Мы получили отзывы о том, что пользователям нужно больше удобства и контроля при сохранении новых файлов в папки.</span><span class="sxs-lookup"><span data-stu-id="02809-1331">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="02809-1332">Мы рады предоставить вам новую возможность: закрепление папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="02809-1332">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="02809-1333">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1333">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="02809-1334">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="02809-1334">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="02809-1335">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1335">Word</span></span>

- <span data-ttu-id="02809-1336">**Сохранение в закрепленные папки.** Закрепление папок сделает сохранение файлов Office проще. Мы получили отзывы о том, что пользователям нужно больше удобства и контроля при сохранении новых файлов в папки.</span><span class="sxs-lookup"><span data-stu-id="02809-1336">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="02809-1337">Мы рады предоставить вам новую возможность: закрепление папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="02809-1337">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="02809-1338">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1338">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="02809-1339">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="02809-1339">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1342">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1342">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1343">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1343">Excel</span></span>

- <span data-ttu-id="02809-1344">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="02809-1344">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1345">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1345">Outlook</span></span>

- <span data-ttu-id="02809-1346">Исправлена проблема, из-за которой не выполнялось действие при нажатии CTRL и щелчка мыши при включенных параметрах облака.</span><span class="sxs-lookup"><span data-stu-id="02809-1346">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1347">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1347">Project</span></span>

- <span data-ttu-id="02809-1348">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="02809-1348">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-11"></a><span data-ttu-id="02809-1350">Версия 2006: 11 июня</span><span class="sxs-lookup"><span data-stu-id="02809-1350">Version 2006: June 11</span></span>
<span data-ttu-id="02809-1351">*Версия 2006 (сборка 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="02809-1351">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1353">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1353">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-1354">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1354">PowerPoint</span></span>

- <span data-ttu-id="02809-1355">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="02809-1355">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="02809-1356">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="02809-1356">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1357">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1357">Word</span></span>

- <span data-ttu-id="02809-1358">**Сохранение текста в векторах.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Excel, Word и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1358">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1361">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1361">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1362">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1362">Excel</span></span>

- <span data-ttu-id="02809-1363">Исправлена проблема, из-за которой Excel иногда завершал работу при взаимодействии с OneDrive.</span><span class="sxs-lookup"><span data-stu-id="02809-1363">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="02809-1364">Исправлена проблема с неправильным применением пользовательских значений в осях на схемах.</span><span class="sxs-lookup"><span data-stu-id="02809-1364">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="02809-1365">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="02809-1365">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="02809-1366">Исправлена проблема, из-за которой в списке доступных принтеров имена принтеров повторялись.</span><span class="sxs-lookup"><span data-stu-id="02809-1366">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="02809-1367">Исправлена проблема, из-за которой увеличивалось время производительности для пользователей при удалении ими объединенных столбцов. </span><span class="sxs-lookup"><span data-stu-id="02809-1367">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="02809-1368">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, так что закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="02809-1368">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="02809-1369">Исправлена проблема, из-за которой повреждалась память при управлении шрифтами между Excel и некоторыми сторонними приложениями специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="02809-1369">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="02809-1370">Исправлена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="02809-1370">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="02809-1371">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="02809-1371">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="02809-1372">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="02809-1372">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="02809-1373">Исправлена проблема, из-за которой в Excel возникал сбой, когда надстройки запрашивали элементы хоста на листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="02809-1373">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="02809-1374">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="02809-1374">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1375">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1375">Outlook</span></span>

- <span data-ttu-id="02809-1376">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="02809-1376">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="02809-1377">Исправлена проблема, из-за которой возникал сбой при просмотре шаблона во время создания нового сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-1377">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="02809-1378">Исправлена проблема, из-за которой пользователи не могли использовать общедоступные папки Exchange 2010 после Outlook версии 1911.</span><span class="sxs-lookup"><span data-stu-id="02809-1378">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="02809-1379">Исправлена проблема с отключенной кнопкой "Выбрать категорию" в календаре группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="02809-1379">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="02809-1380">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="02809-1380">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="02809-1381">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-1381">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="02809-1382">Исправлена проблема, из-за которой пользователи не могли поделиться календарем с гостевым пользователем.</span><span class="sxs-lookup"><span data-stu-id="02809-1382">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="02809-1383">Исправлена проблема, из-за которой элементы календаря, переходящие за полночь, отображались как события на весь день.</span><span class="sxs-lookup"><span data-stu-id="02809-1383">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="02809-1384">Исправлена проблема с отсутствием раскрывающегося списка Online Archive в свойствах папки у пользователей с мониторами высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="02809-1384">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="02809-1385">Исправлена проблема, из-за которой событие Folder.BeforeItemMove срабатывало неправильно, когда пользователь перемещал элементы между папками.</span><span class="sxs-lookup"><span data-stu-id="02809-1385">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="02809-1386">Исправлена проблема, из-за которой в Outlook возникал сбой, когда две надстройки добавляли кнопку в одну группу на ленте.</span><span class="sxs-lookup"><span data-stu-id="02809-1386">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="02809-1387">Исправлена проблема, из-за которой в работе Outlook возникал сбой при использовании гиперссылок в электронных сообщениях в формате обычного текста.</span><span class="sxs-lookup"><span data-stu-id="02809-1387">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="02809-1388">Исправлена проблема, приводившая к неспособности Outlook анализировать длинные имена файлов, закодированные с помощью RFC2231.</span><span class="sxs-lookup"><span data-stu-id="02809-1388">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="02809-1389">Исправлена проблема периодических зависаний в Outlook при использовании средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="02809-1389">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="02809-1390">Исправлена проблема со сбоями в работе Outlook при наличии конфликтов в контактах.</span><span class="sxs-lookup"><span data-stu-id="02809-1390">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1391">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1391">PowerPoint</span></span>

- <span data-ttu-id="02809-1392">Исправлена проблема с открытием файлов с сервера, на котором настроена проверка подлинности на основе форм.</span><span class="sxs-lookup"><span data-stu-id="02809-1392">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="02809-1393">Исправлена проблема, приводившая к ошибкам при сохранении файлов PowerPoint с внедренными диаграммами и книгами.</span><span class="sxs-lookup"><span data-stu-id="02809-1393">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="02809-1394">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1394">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="02809-1395">Исправлена проблема, из-за которой слайды не располагались по центру после изменения масштаба с помощью колесика мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1395">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="02809-1396">Исправлена проблема, из-за которой сочетания клавиш и средства проверки орфографии не работают должным образом при использовании клавиатуры на английском языке для Швейцарии (QWERTZ).</span><span class="sxs-lookup"><span data-stu-id="02809-1396">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="02809-1397">Исправлена проблема, при которой закрытая пользователем область примечаний автоматически открывалась снова.</span><span class="sxs-lookup"><span data-stu-id="02809-1397">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="02809-1398">Исправлена проблема, из-за которой редактор слайдов одного слайда перекрывал следующий слайд.</span><span class="sxs-lookup"><span data-stu-id="02809-1398">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1399">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1399">Project</span></span>

- <span data-ttu-id="02809-1400">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-1400">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="02809-1401">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="02809-1401">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="02809-1402">Исправлена проблема, из-за которой Project аварийно завершал работу после нажатия кнопки "Параметры".</span><span class="sxs-lookup"><span data-stu-id="02809-1402">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="02809-1403">Исправлена проблема, препятствовавшая удалению или переназначению задач, утративших связи после удаления родительского плана.</span><span class="sxs-lookup"><span data-stu-id="02809-1403">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="02809-1404">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-1404">Visio</span></span>

- <span data-ttu-id="02809-1405">Исправлена регрессия в зависимом коде.</span><span class="sxs-lookup"><span data-stu-id="02809-1405">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="02809-1406">Теперь отрисовка изображений происходит службах Visio, работающих в SharePoint локально.</span><span class="sxs-lookup"><span data-stu-id="02809-1406">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1407">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1407">Word</span></span>

- <span data-ttu-id="02809-1408">Исправлена проблема несоответствия метки времени в панелях примечаний установленному в системе местному времени.</span><span class="sxs-lookup"><span data-stu-id="02809-1408">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="02809-1409">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="02809-1409">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="02809-1410">Исправлена проблема, из-за которой не отображался текст, скопированный и вставленный в область примечаний.</span><span class="sxs-lookup"><span data-stu-id="02809-1410">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="02809-1411">Исправлена проблема, из-за которой гиперссылки в примечаниях не работали.</span><span class="sxs-lookup"><span data-stu-id="02809-1411">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="02809-1412">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1412">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="02809-1413">Исправлена проблема с отсутствием синхронизации примечаний между веб-приложением и классическим приложением.</span><span class="sxs-lookup"><span data-stu-id="02809-1413">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="02809-1414">Исправлена проблема, из-за которой выноска маркера примечания казалась размытой при масштабе 100 %.</span><span class="sxs-lookup"><span data-stu-id="02809-1414">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="02809-1415">Исправлена проблема, из-за которой при добавлении нового примечания в пустой документ ничего не происходит.</span><span class="sxs-lookup"><span data-stu-id="02809-1415">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="02809-1416">Исправлена проблема, из-за которой не работала вставка HTML в WordMail для календаря.</span><span class="sxs-lookup"><span data-stu-id="02809-1416">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="02809-1417">Исправлена проблема, из-за которой ответ на примечание в сеансе совместного редактирования иногда приводил к зависанию Word.</span><span class="sxs-lookup"><span data-stu-id="02809-1417">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="02809-1418">Исправлена проблема, из-за которой вставка или обновление индекса в документе, содержащем более сотни элементов, приводит к сбою работы приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-1418">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="02809-1419">Исправлена проблема, из-за которой включение политики "Двоичные документы и шаблоны Word 2007 и более поздних версий" вызывало сбой в некоторых случаях совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="02809-1419">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="02809-1420">Исправлена проблема, из-за которой файлы, в которых есть настраиваемые значения, открывались очень медленно.</span><span class="sxs-lookup"><span data-stu-id="02809-1420">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="02809-1421">Исправлена проблема, из-за которой файлы с длинными именами путей (больше 32 КБ) не открывались, а соответствующее сообщение об ошибке не отображалось.</span><span class="sxs-lookup"><span data-stu-id="02809-1421">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="02809-1422">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1422">Office Suite</span></span>

- <span data-ttu-id="02809-1423">Мы изучили и устранили проблему, из-за которой развертывание Office 365 профессиональный плюс с помощью InTune было приостановлено после завершения работы ОС.</span><span class="sxs-lookup"><span data-stu-id="02809-1423">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="02809-1424">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="02809-1424">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="02809-1425">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="02809-1425">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-08"></a><span data-ttu-id="02809-1427">Версия 2005: 08 июня</span><span class="sxs-lookup"><span data-stu-id="02809-1427">Version 2005: June 08</span></span>
<span data-ttu-id="02809-1428">*Версия 2005 (сборка 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="02809-1428">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1430">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1430">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-1431">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1431">PowerPoint</span></span>

- <span data-ttu-id="02809-1432">Исправлена проблема с диалоговым окном замены шрифтов, в котором в раскрывающемся списке вместо шрифтов, установленных в системе, отображались шрифты, использованные в презентации.</span><span class="sxs-lookup"><span data-stu-id="02809-1432">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-04"></a><span data-ttu-id="02809-1434">Версия 2005: 04 июня</span><span class="sxs-lookup"><span data-stu-id="02809-1434">Version 2005: June 04</span></span>
<span data-ttu-id="02809-1435">*Версия 2005 (сборка 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="02809-1435">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1437">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1437">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="02809-1438">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1438">Access</span></span>

- <span data-ttu-id="02809-1439">**Более высокая точность расширенных типов данных времени и дат.** Представляем новые и улучшенные типы данных.</span><span class="sxs-lookup"><span data-stu-id="02809-1439">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="02809-1440">Чтобы повысить совместимость синтаксиса с SQL, а также точность и уровень детализации записей, включающих даты и время, мы реализуем новый тип данных DateTime2 в Access.</span><span class="sxs-lookup"><span data-stu-id="02809-1440">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="02809-1441">Этот тип данных будет включать больший диапазон дат (с 01.01.0001 по 31.12.9999) и более точное время (в наносекундах, а не секундах), с которыми вы сможете выполнять необходимые вычисления.</span><span class="sxs-lookup"><span data-stu-id="02809-1441">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="02809-1442">Чтобы включить новый тип, установите флажок "Новое поле" > "Расширенный формат даты и времени".</span><span class="sxs-lookup"><span data-stu-id="02809-1442">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="02809-1443">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1443">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="02809-1444">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1444">Excel</span></span>

- <span data-ttu-id="02809-1445">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="02809-1445">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="02809-1446">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="02809-1446">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="02809-1447">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="02809-1447">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1448">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1448">Outlook</span></span>

- <span data-ttu-id="02809-1449">**Быстрое повторное открытие элементов из предыдущего сеанса Outlook.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-1449">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1452">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1452">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="02809-1453">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1453">PowerPoint</span></span>

- <span data-ttu-id="02809-1454">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="02809-1454">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-1455">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1455">Office Suite</span></span>

- <span data-ttu-id="02809-1456">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="02809-1456">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-29"></a><span data-ttu-id="02809-1458">Версия 2005: 29 мая</span><span class="sxs-lookup"><span data-stu-id="02809-1458">Version 2005: May 29</span></span>
<span data-ttu-id="02809-1459">*Версия 2005 (сборка 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="02809-1459">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1461">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1461">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="02809-1462">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1462">Excel</span></span>

- <span data-ttu-id="02809-1463">**Представление листа.** Добавлена возможность сортировки и фильтрации при совместной работе с другими пользователями в классической версии Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-1463">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1464">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1464">Outlook</span></span>

- <span data-ttu-id="02809-1465">**Добавлены кнопки во всплывающие уведомления Outlook.** При использовании Outlook в Windows 10 кнопки быстрых действий теперь отображаются во всплывающих уведомлениях Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-1465">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1468">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1468">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="02809-1469">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1469">Outlook</span></span>

- <span data-ttu-id="02809-1470">Исправлена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="02809-1470">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="02809-1471">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="02809-1471">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="02809-1472">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1472">Office Suite</span></span>

- <span data-ttu-id="02809-1473">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="02809-1473">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="02809-1474">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="02809-1474">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-21"></a><span data-ttu-id="02809-1476">Версия 2005: 21 мая</span><span class="sxs-lookup"><span data-stu-id="02809-1476">Version 2005: May 21</span></span>
<span data-ttu-id="02809-1477">*Версия 2005 (сборка 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="02809-1477">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1481">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1481">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1482">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1482">Excel</span></span>

- <span data-ttu-id="02809-1483">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="02809-1483">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="02809-1484">В некоторых случаях при щелчке гиперссылки внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="02809-1484">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="02809-1485">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1485">Outlook</span></span>

- <span data-ttu-id="02809-1486">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="02809-1486">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="02809-1487">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="02809-1487">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-14"></a><span data-ttu-id="02809-1489">Версия 2005: 14 мая</span><span class="sxs-lookup"><span data-stu-id="02809-1489">Version 2005: May 14</span></span>
<span data-ttu-id="02809-1490">*Версия 2005 (сборка 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="02809-1490">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1492">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1492">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1493">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1493">Excel</span></span>

- <span data-ttu-id="02809-1494">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="02809-1494">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1495">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1495">PowerPoint</span></span>

- <span data-ttu-id="02809-1496">**Переключатель не нужен: наушники вам в помощь.** Используйте наушники Surface для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1496">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="02809-1497">Важно! Чтобы использовать жесты для управления презентациями, необходимо связать наушники Surface с приложением Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="02809-1497">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="02809-1498">Инструкции о начале работы с приложением Surface Audio на Windows 10 находятся здесь.</span><span class="sxs-lookup"><span data-stu-id="02809-1498">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="02809-1499">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1499">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="02809-1500">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="02809-1500">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1501">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1501">Word</span></span>

- <span data-ttu-id="02809-1502">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="02809-1502">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1505">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1505">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="02809-1506">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1506">Excel</span></span>

- <span data-ttu-id="02809-1507">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="02809-1507">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="02809-1508">Исправлена проблема, из-за которой в таблице данных диаграммы неправильно отображались значения оси дат.</span><span class="sxs-lookup"><span data-stu-id="02809-1508">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="02809-1509">Исправлена проблема, из-за которой разрывы страниц не удавалось отключить после перехода в режим макета страницы или страничный режим.</span><span class="sxs-lookup"><span data-stu-id="02809-1509">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="02809-1510">Исправлена проблема, из-за которой стили линий диаграммы могли пропадать после скрытия и повторного отображения столбцов с рядами данных.</span><span class="sxs-lookup"><span data-stu-id="02809-1510">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="02809-1511">Исправлена проблема, из-за которой вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="02809-1511">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="02809-1512">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="02809-1512">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="02809-1513">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="02809-1513">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="02809-1514">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-1514">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="02809-1515">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="02809-1515">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="02809-1516">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-1516">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="02809-1517">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="02809-1517">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="02809-1518">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="02809-1518">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="02809-1519">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="02809-1519">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="02809-1520">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="02809-1520">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="02809-1521">Исправлена проблема, из-за которой пользовательское форматирование в сводных диаграммах не сохранялось при включенном параметре "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="02809-1521">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="02809-1522">Исправлена проблема, из-за которой пользовательское форматирование одной точки данных в сводной диаграмме не сохранялось, если был выбран параметр "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="02809-1522">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="02809-1523">Это исправление устраняет проблему, из-за которой символ "@", отправленный в CSV-файл, приводил к преобразованию строки после символа "@" в формулу.</span><span class="sxs-lookup"><span data-stu-id="02809-1523">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="02809-1524">Исправлена проблема, из-за которой десятичные значения в функции ПОСЛЕДОВ округлялись неправильно.</span><span class="sxs-lookup"><span data-stu-id="02809-1524">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="02809-1525">OneNote</span><span class="sxs-lookup"><span data-stu-id="02809-1525">OneNote</span></span>

- <span data-ttu-id="02809-1526">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="02809-1526">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1527">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1527">Outlook</span></span>

- <span data-ttu-id="02809-1528">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="02809-1528">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="02809-1529">Устранена проблема, из-за которой была отключена кнопка "Классифицировать" для календарей группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="02809-1529">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="02809-1530">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-1530">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="02809-1531">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="02809-1531">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="02809-1532">Исправлена проблема, приводившая к сбою загрузки очень длинных безопасных ссылок (из-за усечения), при переходе по ним в классическом клиенте Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-1532">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="02809-1533">Исправлена проблема, из-за которой папки Outlook с именами, содержащими двухбайтовые знаки (DBCS), периодически исчезали при синхронизации с сервером.</span><span class="sxs-lookup"><span data-stu-id="02809-1533">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="02809-1534">Чтобы это происходило, Outlook должен быть настроен с использованием учетной записи IMAP и работать в системе, языком которой выбран японский.</span><span class="sxs-lookup"><span data-stu-id="02809-1534">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="02809-1535">Решена проблема, из-за которой правила удаления, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, стали недействительными.</span><span class="sxs-lookup"><span data-stu-id="02809-1535">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="02809-1536">Исправлена проблема, которая приводила к удалению вложений при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="02809-1536">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="02809-1537">Исправлена проблему, из-за которой в собраниях, с моменты которых прошло более двух месяцев, не отображалась тема собрания в Помощнике по планированию.</span><span class="sxs-lookup"><span data-stu-id="02809-1537">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="02809-1538">Устранена проблема, из-за которой пользователи видели текст сообщения неполностью при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="02809-1538">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="02809-1539">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="02809-1539">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1540">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1540">PowerPoint</span></span>

- <span data-ttu-id="02809-1541">Исправлена следующая проблема: если пользователь создавал комментарий, не публикуя его, и закрывал область комментариев, затем открывал новое окно, просматривал несколько слайдов, закрывал окно и повторно открывал область комментариев в исходной презентации, черновик комментария был недоступен.</span><span class="sxs-lookup"><span data-stu-id="02809-1541">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="02809-1542">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="02809-1542">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1543">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1543">Project</span></span>

- <span data-ttu-id="02809-1544">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="02809-1544">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="02809-1545">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1545">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="02809-1546">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="02809-1546">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="02809-1547">Исправлена проблема, из-за которой при подключении Project к Project Web App и использовании запятой в качестве десятичного разделителя метод добавления объектов TaskDependencies завершался сбоем, если добавлен параметр Lag.</span><span class="sxs-lookup"><span data-stu-id="02809-1547">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="02809-1548">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1548">Word</span></span>

- <span data-ttu-id="02809-1549">Исправлена проблема, из-за которой иногда не удавалось вставить комментарии в документ в режиме совместной работы.</span><span class="sxs-lookup"><span data-stu-id="02809-1549">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="02809-1550">Это изменение исправляет ошибку, из-за которой карточка "Люди" мерцала при щелчке по @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="02809-1550">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="02809-1551">При включении параметра "Показывать закладки" закладки не отображались.</span><span class="sxs-lookup"><span data-stu-id="02809-1551">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="02809-1552">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="02809-1552">This has been fixed.</span></span>

- <span data-ttu-id="02809-1553">Исправлена следующая проблема: пользователю, закрывавшему документ с черновиком комментариев, предлагалось подтвердить закрытие без сохранения черновика комментариев,</span><span class="sxs-lookup"><span data-stu-id="02809-1553">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="02809-1554">и при отмене запроса документ закрывался, а не оставался открытым.</span><span class="sxs-lookup"><span data-stu-id="02809-1554">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="02809-1555">Исправлена проблема, возникающая при копировании и вставке заголовков.</span><span class="sxs-lookup"><span data-stu-id="02809-1555">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="02809-1556">Исправлена проблема, из-за которой при переводе опубликованного комментария возникала ошибка "Сбой вставки переведенного текста".</span><span class="sxs-lookup"><span data-stu-id="02809-1556">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="02809-1557">Это изменение устраняет проблему, из-за которой при включении параметра "Показывать коды полей вместо их значений" текст с гиперссылками может не отображаться.</span><span class="sxs-lookup"><span data-stu-id="02809-1557">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="02809-1558">В веб-представлении или иммерсивном средстве чтения щелчок по подсказке приводил к прокручиванию в верхнюю часть представления, хотя она уже была просмотрена.</span><span class="sxs-lookup"><span data-stu-id="02809-1558">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="02809-1559">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="02809-1559">This has been fixed.</span></span>

- <span data-ttu-id="02809-1560">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="02809-1560">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="02809-1561">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1561">Office Suite</span></span>

- <span data-ttu-id="02809-1562">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="02809-1562">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="02809-1563">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="02809-1563">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="02809-1564">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="02809-1564">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="02809-1565">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="02809-1565">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="02809-1566">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="02809-1566">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-11"></a><span data-ttu-id="02809-1568">Версия 2004: 11 мая</span><span class="sxs-lookup"><span data-stu-id="02809-1568">Version 2004: May 11</span></span>
<span data-ttu-id="02809-1569">*Версия 2004 (сборка 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="02809-1569">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1571">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1571">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1572">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1572">Excel</span></span>

- <span data-ttu-id="02809-1573">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="02809-1573">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1574">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1574">Outlook</span></span>

- <span data-ttu-id="02809-1575">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="02809-1575">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="02809-1576">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="02809-1576">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="02809-1577">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1577">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="02809-1578">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="02809-1578">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="02809-1579">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="02809-1579">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1580">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1580">PowerPoint</span></span>

- <span data-ttu-id="02809-1581">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="02809-1581">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="02809-1582">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1582">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="02809-1583">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1583">Word</span></span>

- <span data-ttu-id="02809-1584">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="02809-1584">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1587">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1587">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1588">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1588">Outlook</span></span>

- <span data-ttu-id="02809-1589">Устранена проблема, из-за которой у пользователей возникали сбои при отображении всплывающих уведомлений.</span><span class="sxs-lookup"><span data-stu-id="02809-1589">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-04"></a><span data-ttu-id="02809-1591">Версия 2004: 04 мая</span><span class="sxs-lookup"><span data-stu-id="02809-1591">Version 2004: May 04</span></span>
<span data-ttu-id="02809-1592">*Версия 2004 (сборка 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="02809-1592">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1594">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1594">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1595">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1595">Outlook</span></span>

- <span data-ttu-id="02809-1596">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="02809-1596">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="02809-1597">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1597">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="02809-1598">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-1598">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="02809-1599">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1599">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1602">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1602">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="02809-1603">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1603">Office Suite</span></span>

- <span data-ttu-id="02809-1604">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="02809-1604">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-29"></a><span data-ttu-id="02809-1606">Версия 2004: 29 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1606">Version 2004: April 29</span></span>
<span data-ttu-id="02809-1607">*Версия 2004 (сборка 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="02809-1607">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1609">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1609">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1610">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1610">Outlook</span></span>

- <span data-ttu-id="02809-1611">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="02809-1611">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1614">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1614">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1615">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1615">Outlook</span></span>

- <span data-ttu-id="02809-1616">Исправлена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-1616">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-25"></a><span data-ttu-id="02809-1618">Версия 2004: 25 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1618">Version 2004: April 25</span></span>
<span data-ttu-id="02809-1619">*Версия 2004 (сборка 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="02809-1619">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1621">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1621">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1622">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1622">Outlook</span></span>

- <span data-ttu-id="02809-1623">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="02809-1623">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1624">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1624">Project</span></span>

- <span data-ttu-id="02809-1625">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="02809-1625">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-1626">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1626">Office Suite</span></span>

- <span data-ttu-id="02809-1627">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="02809-1627">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-21"></a><span data-ttu-id="02809-1629">Версия 2004: 21 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1629">Version 2004: April 21</span></span>
<span data-ttu-id="02809-1630">*Версия 2004 (сборка 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="02809-1630">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1632">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1632">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1633">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1633">Outlook</span></span>

- <span data-ttu-id="02809-1634">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="02809-1634">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="02809-1635">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-1635">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-15"></a><span data-ttu-id="02809-1637">Версия 2004: 15 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1637">Version 2004: April 15</span></span>
<span data-ttu-id="02809-1638">*Версия 2004 (сборка 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="02809-1638">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1640">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1640">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1641">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1641">Excel</span></span>

- <span data-ttu-id="02809-1642">**Поддержка коннектора Facebook заканчивается:** Начиная с апреля 2020 года Excel больше не будет поддерживать подключения к внешним данным, которые используют коннектор Facebook.</span><span class="sxs-lookup"><span data-stu-id="02809-1642">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1643">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1643">Outlook</span></span>

- <span data-ttu-id="02809-1644">**Новая опция, позволяющая отключить предложения @ упоминания при составлении писем в Outlook:** Считаете ли вы средство @ упоминания более раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="02809-1644">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="02809-1645">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="02809-1645">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1646">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1646">PowerPoint</span></span>

- <span data-ttu-id="02809-1647">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="02809-1647">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1648">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1648">Word</span></span>

- <span data-ttu-id="02809-1649">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="02809-1649">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="02809-1650">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="02809-1650">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1653">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1653">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-1654">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1654">Access</span></span>

- <span data-ttu-id="02809-1655">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="02809-1655">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="02809-1656">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="02809-1656">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="02809-1657">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1657">Excel</span></span>

- <span data-ttu-id="02809-1658">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="02809-1658">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="02809-1659">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-1659">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="02809-1660">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="02809-1660">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="02809-1661">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="02809-1661">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="02809-1662">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="02809-1662">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="02809-1663">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="02809-1663">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="02809-1664">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="02809-1664">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="02809-1665">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="02809-1665">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="02809-1666">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="02809-1666">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="02809-1667">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="02809-1667">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="02809-1668">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="02809-1668">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1669">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1669">Outlook</span></span>

- <span data-ttu-id="02809-1670">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="02809-1670">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="02809-1671">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-1671">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="02809-1672">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="02809-1672">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="02809-1673">Устранена проблема, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="02809-1673">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="02809-1674">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="02809-1674">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="02809-1675">Устранена проблема, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="02809-1675">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="02809-1676">Устранена проблема, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="02809-1676">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="02809-1677">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="02809-1677">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="02809-1678">Устранена проблема, из-за которой кнопка «Сохранить в облаке» отсутствовала в инструментах вложений.</span><span class="sxs-lookup"><span data-stu-id="02809-1678">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="02809-1679">Устранена проблема, из-за которой пользователи не могли добавлять подпись при ответе на сообщение с цифровыми правами из окна инспектора, когда у пользователя нет разрешения Владельца на сообщение, на которое он отвечает.</span><span class="sxs-lookup"><span data-stu-id="02809-1679">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="02809-1680">Устранена проблема, из-за которой пользователи не могли добавлять дополнительные вложения из веб-сайта в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="02809-1680">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="02809-1681">Устранена проблема, из-за которой дата «последнего изменения» в файле обновлялась при добавлении вложения в сообщение или при сохранении вложения из сообщения путем его перетаскивания (в отличие от меню).</span><span class="sxs-lookup"><span data-stu-id="02809-1681">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="02809-1682">Устранена проблема, из-за которой при вводе в расширенной области поиска не удавалось запустить поиск, вместо этого требовалось, чтобы пользователи нажимали кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="02809-1682">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="02809-1683">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="02809-1683">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="02809-1684">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="02809-1684">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-1685">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1685">PowerPoint</span></span>

- <span data-ttu-id="02809-1686">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="02809-1686">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="02809-1687">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="02809-1687">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="02809-1688">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="02809-1688">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="02809-1689">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="02809-1689">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1690">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1690">Project</span></span>

- <span data-ttu-id="02809-1691">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-1691">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="02809-1692">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="02809-1692">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="02809-1693">Исправлена ошибка, из-за которой событие Visual Basic Applications (VBA) ProjectBeforeTaskChange не срабатывало, когда пользователь нажимал кнопку «Деактивировать», найденную на ленте задач в группе планирования.</span><span class="sxs-lookup"><span data-stu-id="02809-1693">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="02809-1694">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="02809-1694">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="02809-1695">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="02809-1695">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="02809-1696">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="02809-1696">This behavior has been fixed.</span></span>

- <span data-ttu-id="02809-1697">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="02809-1697">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="02809-1698">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="02809-1698">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="02809-1699">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="02809-1699">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="02809-1700">Исправлена ошибка, из-за которой при печати временной шкалы с использованием календаря хиджры месяц пропускался или дублировался в представлении печати.</span><span class="sxs-lookup"><span data-stu-id="02809-1700">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="02809-1701">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="02809-1701">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="02809-1702">Исправлена ошибка, из-за которой, если выполняется CustomFieldValueListGetItem 'и таблица поиска для настраиваемого поля не существует, создается пустая таблица поиска, хотя это не должно быть.</span><span class="sxs-lookup"><span data-stu-id="02809-1702">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="02809-1703">Когда данные редактора или преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange</span><span class="sxs-lookup"><span data-stu-id="02809-1703">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="02809-1704">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="02809-1704">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1705">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1705">Word</span></span>

- <span data-ttu-id="02809-1706">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="02809-1706">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="02809-1707">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="02809-1707">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="02809-1708">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="02809-1708">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="02809-1709">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="02809-1709">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="02809-1710">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="02809-1710">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="02809-1711">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="02809-1711">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="02809-1712">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="02809-1712">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="02809-1713">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="02809-1713">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="02809-1714">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="02809-1714">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="02809-1715">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="02809-1715">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="02809-1716">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="02809-1716">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="02809-1717">Мы исправили проблему, из-за которой выравнивание слова в документе зашифровывается при попытке изменить его после печати с использованием Quick Print.</span><span class="sxs-lookup"><span data-stu-id="02809-1717">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="02809-1718">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="02809-1718">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="02809-1719">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="02809-1719">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="02809-1720">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="02809-1720">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-14"></a><span data-ttu-id="02809-1722">Версия 2003: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1722">Version 2003: April 14</span></span>
<span data-ttu-id="02809-1723">*Версия 2003 (сборка 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="02809-1723">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="02809-1724">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="02809-1724">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

- <span data-ttu-id="02809-1726">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1726">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-09"></a><span data-ttu-id="02809-1728">Версия 2003: 9 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1728">Version 2003: April 09</span></span>
<span data-ttu-id="02809-1729">*Версия 2003 (сборка 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="02809-1729">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1731">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1731">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1732">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1732">Excel</span></span>

- <span data-ttu-id="02809-1733">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="02809-1733">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="02809-1734">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="02809-1734">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1735">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1735">Outlook</span></span>

- <span data-ttu-id="02809-1736">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="02809-1736">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="02809-1737">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="02809-1737">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1738">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1738">PowerPoint</span></span>

- <span data-ttu-id="02809-1739">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="02809-1739">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="02809-1740">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="02809-1740">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="02809-1741">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1741">Word</span></span>

- <span data-ttu-id="02809-1742">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="02809-1742">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="02809-1743">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="02809-1743">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-03"></a><span data-ttu-id="02809-1747">Версия 2003: 3 апреля</span><span class="sxs-lookup"><span data-stu-id="02809-1747">Version 2003: April 03</span></span>
<span data-ttu-id="02809-1748">*Версия 2003 (сборка 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="02809-1748">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1750">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1750">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1751">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1751">Excel</span></span>

- <span data-ttu-id="02809-1752">В некоторых случаях при использовании приложения VBA не работала оценка определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="02809-1752">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1753">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1753">Outlook</span></span>

- <span data-ttu-id="02809-1754">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1754">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="02809-1755">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1755">Project</span></span>

- <span data-ttu-id="02809-1756">При изменении данных предшественника или последователя в представлении формы возникало дополнительное событие ProjectBeforeTaskChangeevent.</span><span class="sxs-lookup"><span data-stu-id="02809-1756">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1757">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1757">Word</span></span>

- <span data-ttu-id="02809-1758">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1758">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-31"></a><span data-ttu-id="02809-1760">Версия 2003: 31 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1760">Version 2003: March 31</span></span>
<span data-ttu-id="02809-1761">*Версия 2003 (сборка 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="02809-1761">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1763">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1763">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="02809-1764">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1764">Access</span></span>

- <span data-ttu-id="02809-1765">**Область задач "Добавление таблиц":** новая область задач Access "Добавление таблиц" наконец доступна!</span><span class="sxs-lookup"><span data-stu-id="02809-1765">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="02809-1766">Эта функция позволяет легко выбирать несколько таблиц, которые нужно добавить или удалить в окне запроса, не переходя к диалоговому окну "Отображение таблиц" для запросов и представления связей.</span><span class="sxs-lookup"><span data-stu-id="02809-1766">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="02809-1767">Она также включает новую вкладку "Ссылки" для отображения связанных таблиц, поле поиска для фильтрации текущего списка, действие перетаскивания и многое другое!</span><span class="sxs-lookup"><span data-stu-id="02809-1767">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1770">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1770">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="02809-1771">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1771">Project</span></span>

- <span data-ttu-id="02809-1772"><span style="display:inline !important;">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span></span><span class="sxs-lookup"><span data-stu-id="02809-1772"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-25"></a><span data-ttu-id="02809-1774">Версия 2003: 25 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1774">Version 2003: March 25</span></span>
<span data-ttu-id="02809-1775">*Версия 2003 (сборка 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="02809-1775">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="02809-1776">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1776">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="02809-1777">Версия 2003: 23 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1777">Version 2003: March 23</span></span>
<span data-ttu-id="02809-1778">*Версия 2003 (сборка 12624,20296)*</span><span class="sxs-lookup"><span data-stu-id="02809-1778">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="02809-1779">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1779">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="02809-1780">Версия 2003: 21 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1780">Version 2003: March 21</span></span>
<span data-ttu-id="02809-1781">*Версия 2003 (сборка 12624,20276)*</span><span class="sxs-lookup"><span data-stu-id="02809-1781">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1783">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1783">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1784">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1784">Outlook</span></span>

- <span data-ttu-id="02809-1785">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="02809-1785">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="02809-1786">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1786">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="02809-1787">**Визуальное обновление календаря:** в прошлом году мы представили вам обновленную почту, а в этом году настала очередь календаря!</span><span class="sxs-lookup"><span data-stu-id="02809-1787">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="02809-1788">Обновления свежие, но знакомые, поэтому, как опытный пользователь Outlook, вы можете сразу же подключиться и стать более продуктивным.</span><span class="sxs-lookup"><span data-stu-id="02809-1788">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1789">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1789">PowerPoint</span></span>

- <span data-ttu-id="02809-1790">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="02809-1790">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-16"></a><span data-ttu-id="02809-1792">Версия 2003: 16 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1792">Version 2003: March 16</span></span>
<span data-ttu-id="02809-1793">*Версия 2003 (сборка 12624,20224)*</span><span class="sxs-lookup"><span data-stu-id="02809-1793">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1795">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1795">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1796">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1796">Excel</span></span>

- <span data-ttu-id="02809-1797">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="02809-1797">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1798">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1798">Outlook</span></span>

- <span data-ttu-id="02809-1799">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="02809-1799">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1800">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1800">PowerPoint</span></span>

- <span data-ttu-id="02809-1801">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="02809-1801">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1802">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1802">Word</span></span>

- <span data-ttu-id="02809-1803">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="02809-1803">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="02809-1804">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1804">Office Suite</span></span>

- <span data-ttu-id="02809-1805">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="02809-1805">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="02809-1806">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="02809-1806">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1809">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1809">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1810">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1810">Excel</span></span>

- <span data-ttu-id="02809-1811">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="02809-1811">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1812">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1812">Outlook</span></span>

- <span data-ttu-id="02809-1813">Устранена проблема, из-за которой пользователи могли видеть процесс Outlook, задерживающийся в диспетчере задач после выхода.</span><span class="sxs-lookup"><span data-stu-id="02809-1813">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-10"></a><span data-ttu-id="02809-1815">Версия 2003: 10 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1815">Version 2003: March 10</span></span>
<span data-ttu-id="02809-1816">*Версия 2003 (сборка 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="02809-1816">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="02809-1817">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="02809-1817">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)
### <a name="feature-updates"></a><span data-ttu-id="02809-1819">Обновления компонентов</span><span class="sxs-lookup"><span data-stu-id="02809-1819">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1820">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1820">Excel</span></span>
- <span data-ttu-id="02809-1821">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="02809-1821">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="02809-1822">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1822">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="02809-1823">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1823">PowerPoint</span></span>
- <span data-ttu-id="02809-1824">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="02809-1824">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="02809-1825">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1825">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="02809-1826">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1826">Word</span></span>
- <span data-ttu-id="02809-1827">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="02809-1827">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="02809-1828">Подробнее</span><span class="sxs-lookup"><span data-stu-id="02809-1828">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="02809-1829">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1829">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1830">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1830">Excel</span></span>

- <span data-ttu-id="02809-1831">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="02809-1831">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="02809-1832">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="02809-1832">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="02809-1833">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="02809-1833">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="02809-1834">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="02809-1834">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="02809-1835">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="02809-1835">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="02809-1836">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="02809-1836">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="02809-1837">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="02809-1837">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="02809-1838">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="02809-1838">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="02809-1839">Это изменение исправляет ошибку во время выполнения в объектной модели и потенциальный сбой приложения (Excel, Word), если надстройки запрашивают элементы узла в документах или листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="02809-1839">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="02809-1840">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="02809-1840">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="02809-1841">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1841">Outlook</span></span>

- <span data-ttu-id="02809-1842">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не сохранялось на сервере Exchange Server и возникал конфликт.</span><span class="sxs-lookup"><span data-stu-id="02809-1842">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="02809-1843">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="02809-1843">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="02809-1844">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="02809-1844">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="02809-1845">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="02809-1845">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="02809-1846">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="02809-1846">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="02809-1847">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="02809-1847">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="02809-1848">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря &quot;Параметры доступности&quot;.</span><span class="sxs-lookup"><span data-stu-id="02809-1848">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="02809-1849">Исправлена проблема, которая могла привести к появлению оповещения &quot;К сожалению, не удалось открыть элемент&quot; при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="02809-1849">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="02809-1850">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="02809-1850">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="02809-1851">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="02809-1851">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="02809-1852">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="02809-1852">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="02809-1853">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="02809-1853">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="02809-1854">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1854">PowerPoint</span></span>

- <span data-ttu-id="02809-1855">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1855">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="02809-1856">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1856">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="02809-1857">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="02809-1857">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="02809-1858">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="02809-1858">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="02809-1859">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1859">Project</span></span>

- <span data-ttu-id="02809-1860">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="02809-1860">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="02809-1861">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="02809-1861">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="02809-1862">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-1862">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="02809-1863">Visio</span><span class="sxs-lookup"><span data-stu-id="02809-1863">Visio</span></span>

- <span data-ttu-id="02809-1864">В области сведений о фигуре отображались несогласованные данные в разделе "Данные фигуры" в зависимости от файла при открытии в классической версии Visio.</span><span class="sxs-lookup"><span data-stu-id="02809-1864">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="02809-1865">Это исправлено.</span><span class="sxs-lookup"><span data-stu-id="02809-1865">It has now been fixed.</span></span>

- <span data-ttu-id="02809-1866">Точечные рисунки, импортированные в версиях до 2016, не отображались из-за некоторых проверок безопасности.</span><span class="sxs-lookup"><span data-stu-id="02809-1866">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="02809-1867">Эта проблема исправлена в подписке на Visio.</span><span class="sxs-lookup"><span data-stu-id="02809-1867">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1868">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1868">Word</span></span>

- <span data-ttu-id="02809-1869">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="02809-1869">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="02809-1870">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="02809-1870">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="02809-1871">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="02809-1871">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="02809-1872">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега.</span><span class="sxs-lookup"><span data-stu-id="02809-1872">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="02809-1873">Эта проблема исправлена.</span><span class="sxs-lookup"><span data-stu-id="02809-1873">This issue has been fixed.</span></span>

- <span data-ttu-id="02809-1874">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="02809-1874">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="02809-1875">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="02809-1875">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="02809-1876">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="02809-1876">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="02809-1877">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1877">Office Suite</span></span>

- <span data-ttu-id="02809-1878">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="02809-1878">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="02809-1879">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="02809-1879">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="02809-1880">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="02809-1880">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="02809-1881">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1881">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="02809-1882">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="02809-1882">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-05"></a><span data-ttu-id="02809-1884">Версия 2002: 5 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1884">Version 2002: March 05</span></span>
<span data-ttu-id="02809-1885">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="02809-1885">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="02809-1886">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1886">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="02809-1887">Версия 2002: 4 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1887">Version 2002: March 04</span></span>
<span data-ttu-id="02809-1888">*Версия 2002 (сборка 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="02809-1888">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1890">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1890">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="02809-1891">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1891">Project</span></span>
- <span data-ttu-id="02809-1892">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="02809-1892">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-1893">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1893">Office Suite</span></span>
- <span data-ttu-id="02809-1894">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="02809-1894">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-01"></a><span data-ttu-id="02809-1896">Версия 2002: 1 марта</span><span class="sxs-lookup"><span data-stu-id="02809-1896">Version 2002: March 01</span></span>
<span data-ttu-id="02809-1897">*Версия 2002 (сборка 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="02809-1897">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="02809-1898">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1898">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1899">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1899">Outlook</span></span>

- <span data-ttu-id="02809-1900">Исправлена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="02809-1900">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-24"></a><span data-ttu-id="02809-1902">Версия 2002: 24 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-1902">Version 2002: February 24</span></span>
<span data-ttu-id="02809-1903">*Версия 2002 (сборка 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="02809-1903">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="02809-1904">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1904">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="02809-1905">Версия 2002: 22 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-1905">Version 2002: February 22</span></span>
<span data-ttu-id="02809-1906">*Версия 2002 (сборка 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="02809-1906">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="02809-1907">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="02809-1907">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="02809-1908">Версия 2002: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-1908">Version 2002: February 21</span></span>
<span data-ttu-id="02809-1909">*Версия 2002 (сборка 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="02809-1909">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1911">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1911">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="02809-1912">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1912">Access</span></span>

- <span data-ttu-id="02809-1913">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="02809-1913">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="02809-1914">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="02809-1914">Search and replace text in SQL View.</span></span> <span data-ttu-id="02809-1915">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="02809-1915">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1916">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1916">Outlook</span></span>

- <span data-ttu-id="02809-1917">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="02809-1917">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="02809-1918">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="02809-1918">Outlook now detects this and helps you get connected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1921">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1921">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="02809-1922">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1922">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="02809-1923">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="02809-1923">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="02809-1924">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1924">Outlook</span></span>

- <span data-ttu-id="02809-1925">Исправлена проблема, из-за которой запятые в поле месторасположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="02809-1925">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="02809-1926">Исправлена проблема, которая могла приводить к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="02809-1926">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="02809-1927">Исправлена проблема, из-за которой приложение Outlook неожиданно синхронизировало всю почту, даже если ползунок синхронизация настроен на меньшее значение.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="02809-1927">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="02809-1928">Исправлена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке &quot;От&quot; отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="02809-1928">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="02809-1929"><span style="display:inline !important;">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span></span><span class="sxs-lookup"><span data-stu-id="02809-1929"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-18"></a><span data-ttu-id="02809-1931">Версия 2002: 18 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-1931">Version 2002: February 18</span></span>
<span data-ttu-id="02809-1932">*Версия 2002 (сборка 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="02809-1932">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="02809-1933">Версия 2002:11 февраля</span><span class="sxs-lookup"><span data-stu-id="02809-1933">Version 2002: February 11</span></span>
<span data-ttu-id="02809-1934">*Версия 2002 (сборка 12527,20092)*</span><span class="sxs-lookup"><span data-stu-id="02809-1934">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="02809-1935">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="02809-1935">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="02809-1937">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="02809-1937">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="02809-1938">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1938">Outlook</span></span>

- <span data-ttu-id="02809-1939">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="02809-1939">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="02809-1940">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="02809-1940">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="02809-1941">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1941">Word</span></span>

- <span data-ttu-id="02809-1942">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="02809-1942">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="02809-1943">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1943">Office Suite</span></span>

- <span data-ttu-id="02809-1944">**Более понятные значки строки состояния:** значки строки состояния стали понятнее.</span><span class="sxs-lookup"><span data-stu-id="02809-1944">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="02809-1947">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="02809-1947">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="02809-1948">Access</span><span class="sxs-lookup"><span data-stu-id="02809-1948">Access</span></span>

- <span data-ttu-id="02809-1949">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="02809-1949">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="02809-1950">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="02809-1950">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="02809-1951">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="02809-1951">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="02809-1952">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="02809-1952">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="02809-1953">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="02809-1953">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="02809-1954">Excel</span><span class="sxs-lookup"><span data-stu-id="02809-1954">Excel</span></span>

- <span data-ttu-id="02809-1955">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="02809-1955">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="02809-1956">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="02809-1956">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="02809-1957">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="02809-1957">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="02809-1958">Outlook</span><span class="sxs-lookup"><span data-stu-id="02809-1958">Outlook</span></span>

- <span data-ttu-id="02809-1959">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="02809-1959">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="02809-1960">Папки, сохраненные в разделе "Избранное" в области навигации слева, могут периодически исчезать.</span><span class="sxs-lookup"><span data-stu-id="02809-1960">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="02809-1961">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="02809-1961">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="02809-1962">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="02809-1962">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="02809-1963">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="02809-1963">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="02809-1964">Исправлена проблема, из-за которой срок действия почты в соответствии с политикой хранения будет иметь две метки.</span><span class="sxs-lookup"><span data-stu-id="02809-1964">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="02809-1965">Один показывает, что срок действия письма истекает через один день, а другой - что срок его действия истекает через два дня.</span><span class="sxs-lookup"><span data-stu-id="02809-1965">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="02809-1966">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="02809-1966">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="02809-1967">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="02809-1967">PowerPoint</span></span>

- <span data-ttu-id="02809-1968">Исправлена проблема, из-за которой рукописные фрагменты могли не отображаться полностью или пропускаться при использовании анимации рукописного ввода в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1968">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="02809-1969">Исправлена ошибка, из-за которой после закрытия файла PowerPoint не сразу удалял его из коллекции презентаций, если были запущены какие-либо обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="02809-1969">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="02809-1970">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02809-1970">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="02809-1971">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="02809-1971">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="02809-1972">Project</span><span class="sxs-lookup"><span data-stu-id="02809-1972">Project</span></span>

- <span data-ttu-id="02809-1973">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="02809-1973">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="02809-1974">Word</span><span class="sxs-lookup"><span data-stu-id="02809-1974">Word</span></span>

- <span data-ttu-id="02809-1975">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="02809-1975">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="02809-1976">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="02809-1976">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="02809-1977">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="02809-1977">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="02809-1978">Исправлена ошибка, из-за которой форматирование курсива терялось после редактирования комментария, выделения курсивом текста и последующей публикации.</span><span class="sxs-lookup"><span data-stu-id="02809-1978">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="02809-1979">Исправлена проблема, из-за которой подсказки примечаний не были видны в режиме чтения с помощью инвертированного цвета страницы.</span><span class="sxs-lookup"><span data-stu-id="02809-1979">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="02809-1980">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="02809-1980">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="02809-1981">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="02809-1981">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="02809-1982">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="02809-1982">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="02809-1983">Исправлена ошибка, из-за которой команды комментария (Редактировать комментарий, Ответить на комментарий, Удалить комментарий, Разрешить комментарий) в контекстном меню комментариев не отображались.</span><span class="sxs-lookup"><span data-stu-id="02809-1983">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="02809-1984">Набор Office</span><span class="sxs-lookup"><span data-stu-id="02809-1984">Office Suite</span></span>

- <span data-ttu-id="02809-1985">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="02809-1985">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="02809-1986">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="02809-1986">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)