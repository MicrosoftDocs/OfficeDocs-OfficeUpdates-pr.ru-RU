---
title: Заметки о выпуске для бета-канала
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с ранним доступом последний список новых функций, исправлений или известных проблем
ms.openlocfilehash: 36166e5e6ab4c814e56d5a5458747ba1c67964e7
ms.sourcegitcommit: 9775ae224ef323ec5f92db13c85a8d0abf256f9c
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/13/2020
ms.locfileid: "49071538"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="084fc-103">Заметки о выпуске для бета-канала</span><span class="sxs-lookup"><span data-stu-id="084fc-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="084fc-p101">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don't see something described below, don't worry you'll get it eventually.</span><span class="sxs-lookup"><span data-stu-id="084fc-p101">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="084fc-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="084fc-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="084fc-111">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок.</span><span class="sxs-lookup"><span data-stu-id="084fc-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="084fc-112">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="084fc-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2012-november-13"></a><span data-ttu-id="084fc-115">Версия 2012: 13 ноября</span><span class="sxs-lookup"><span data-stu-id="084fc-115">Version 2012: November 13</span></span>
<span data-ttu-id="084fc-116">*Версия 2012 (сборка 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="084fc-116">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-118">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-119">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-119">Excel</span></span>

- <span data-ttu-id="084fc-120">Исправлена проблема, из-за которой команда "Вставить объект" не отображала соответствующий значок при вставке файла из локальной папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="084fc-120">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="084fc-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-121">Outlook</span></span>

- <span data-ttu-id="084fc-122">Исправлена проблема, из-за которой поле "Кому:" было пустым в отчетах о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="084fc-122">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="084fc-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-123">PowerPoint</span></span>

- <span data-ttu-id="084fc-124">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="084fc-124">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="084fc-125">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-125">Project</span></span>

- <span data-ttu-id="084fc-126">Исправлена проблема, из-за которой не удавалось удалить зависимости в конечных результатах, если сайт SharePoint, с которым были связаны конечные результаты, больше не существовал.</span><span class="sxs-lookup"><span data-stu-id="084fc-126">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="084fc-127">Исправлена проблема, из-за которой отсутствовали изменения при открытии пользователями проектов, сохраненных с измененными сведениями.</span><span class="sxs-lookup"><span data-stu-id="084fc-127">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="084fc-128">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-128">Word</span></span>

- <span data-ttu-id="084fc-129">Исправлена проблема, из-за которой изображения становились размытыми при изменении масштаба.</span><span class="sxs-lookup"><span data-stu-id="084fc-129">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="084fc-130">Исправлена проблема, из-за которой длинные гиперссылки усекались.</span><span class="sxs-lookup"><span data-stu-id="084fc-130">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-november-06"></a><span data-ttu-id="084fc-132">Версия 2012: 6 ноября</span><span class="sxs-lookup"><span data-stu-id="084fc-132">Version 2012: November 06</span></span>
<span data-ttu-id="084fc-133">*Версия 2012 (сборка 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-133">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-135">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-135">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-136">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-136">Excel</span></span>

- <span data-ttu-id="084fc-137">**Отображение нескольких листов одновременно.** Больше не нужно отображать листы по одному. Отображайте несколько скрытых листов одновременно.</span><span class="sxs-lookup"><span data-stu-id="084fc-137">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="084fc-138">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-138">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="084fc-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-139">Outlook</span></span>

- <span data-ttu-id="084fc-140">**Одна подпись на всех устройствах.** Ваша подпись хранится в облаке.</span><span class="sxs-lookup"><span data-stu-id="084fc-140">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="084fc-141">Создайте ее один раз и используйте везде, где применяете Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-141">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-144">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-144">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-145">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-145">Excel</span></span>

- <span data-ttu-id="084fc-146">Исправлена проблема, из-за которой некоторые элементы не был локализованы на китайском языке (упрощенное письмо).</span><span class="sxs-lookup"><span data-stu-id="084fc-146">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="084fc-147">Исправлена проблема, из-за которой приложение Excel неожиданно прекращало работу при обновлении.</span><span class="sxs-lookup"><span data-stu-id="084fc-147">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="084fc-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-148">Outlook</span></span>

- <span data-ttu-id="084fc-149">Исправлена проблема, из-за которой не удавалось добавить вложение в сообщение, открытое из ZIP-файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-149">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-30"></a><span data-ttu-id="084fc-151">Версия 2011: 30 октября</span><span class="sxs-lookup"><span data-stu-id="084fc-151">Version 2011: October 30</span></span>
<span data-ttu-id="084fc-152">*Версия 2011 (сборка 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="084fc-152">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-154">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-154">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-155">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-155">Excel</span></span>

- <span data-ttu-id="084fc-156">**Улучшенные диалоговые окна условного форматирования.** Теперь размеры диалоговых окон условного форматирования можно изменять, и вы можете дублировать правило одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="084fc-156">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="084fc-157">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-157">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-160">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-160">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-161">Доступ</span><span class="sxs-lookup"><span data-stu-id="084fc-161">Access</span></span>

- <span data-ttu-id="084fc-162">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="084fc-162">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="084fc-163">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-163">Excel</span></span>

- <span data-ttu-id="084fc-164">Исправлена проблема с Power Pivot при использовании подключения к базе данных Oracle.</span><span class="sxs-lookup"><span data-stu-id="084fc-164">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="084fc-165">Исправлена проблема с неожиданным прекращением работы Excel, когда запускалось вычисление MTR и обновление объекта групповой политики (например, с помощью удаленного обновления групповой политики).</span><span class="sxs-lookup"><span data-stu-id="084fc-165">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="084fc-166">Это изменение исправляет ошибку, приводившую к сбою в Excel при попытке загрузки файла ATOMSVC.</span><span class="sxs-lookup"><span data-stu-id="084fc-166">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="084fc-167">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="084fc-167">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="084fc-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-168">Outlook</span></span>

- <span data-ttu-id="084fc-169">Исправлена проблема, из-за которой владелец почтового ящика не мог управлять разрешением общего доступа для своего календаря, так как этот параметр был затенен.</span><span class="sxs-lookup"><span data-stu-id="084fc-169">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="084fc-170">Исправлена проблема, из-за которой сохранение шаблонов электронной почты в виде OFT-файлов приводило к изменению китайских иероглифов на вопросительные знаки.</span><span class="sxs-lookup"><span data-stu-id="084fc-170">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="084fc-171">Исправлена проблема, из-за которой приложение Outlook не могло создать сообщение с ограниченным разрешением.</span><span class="sxs-lookup"><span data-stu-id="084fc-171">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="084fc-172">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="084fc-172">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="084fc-173">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-173">PowerPoint</span></span>

- <span data-ttu-id="084fc-174">Исправлена проблема, из-за которой линии сетки смещались со слайдов при закрытии области конструктора.</span><span class="sxs-lookup"><span data-stu-id="084fc-174">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="084fc-175">Исправлена проблема, из-за которой полоса прокрутки на слайде начинала двигаться самостоятельно после прекращения записи экрана с открытой областью выбора.</span><span class="sxs-lookup"><span data-stu-id="084fc-175">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="084fc-176">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-176">Project</span></span>

- <span data-ttu-id="084fc-177">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="084fc-177">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="084fc-178">Исправлена проблема, из-за которой задействование ресурсов выполняло поиск ресурса по имени, а не по GUID, что приводило к проблемам при наличии нескольких ресурсов с одинаковым именем.</span><span class="sxs-lookup"><span data-stu-id="084fc-178">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="084fc-179">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-179">Word</span></span>

- <span data-ttu-id="084fc-180">Исправлена проблема, из-за которой щелчок по маркеру примечания не приводил к уменьшению масштаба для отображения карточки примечания в представлении.</span><span class="sxs-lookup"><span data-stu-id="084fc-180">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="084fc-181">Исправлена проблема макета, из-за которой могла смещаться линия между столбцами.</span><span class="sxs-lookup"><span data-stu-id="084fc-181">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="084fc-182">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="084fc-182">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="084fc-183">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-183">Office Suite</span></span>

- <span data-ttu-id="084fc-184">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="084fc-184">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-23"></a><span data-ttu-id="084fc-186">Версия 2011: 23 октября</span><span class="sxs-lookup"><span data-stu-id="084fc-186">Version 2011: October 23</span></span>
<span data-ttu-id="084fc-187">*Версия 2011 (сборка 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-187">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-189">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-189">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="084fc-190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-190">PowerPoint</span></span>

- <span data-ttu-id="084fc-191">**Отрепетируйте презентацию с помощью тренера выступлений.** Получите отзывы, которые помогут удержать аудиторию, в том числе о темпе речи, тоне, словах-заполнителях, деликатных фразах и т. д.</span><span class="sxs-lookup"><span data-stu-id="084fc-191">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="084fc-192">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-192">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-195">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-195">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-196">Доступ</span><span class="sxs-lookup"><span data-stu-id="084fc-196">Access</span></span>

- <span data-ttu-id="084fc-197">Исправлена проблема, из-за которой для некоторых пользователей отображалась ошибка "Недостаточно системных ресурсов", когда они пытались экспортировать запрос из своей синхронизированной папки OneDrive.</span><span class="sxs-lookup"><span data-stu-id="084fc-197">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="084fc-198">Исправлена проблема, из-за которой автоматическое переключение между окнами форм приводило к переключению на другую форму.</span><span class="sxs-lookup"><span data-stu-id="084fc-198">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-199">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-199">Outlook</span></span>

- <span data-ttu-id="084fc-200">Исправлена проблема, из-за которой при вставке URL-адреса, скопированного из расположения собрания, в другое место (например, в браузер) URL-адрес содержал в конце точку с запятой.</span><span class="sxs-lookup"><span data-stu-id="084fc-200">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-201">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-201">PowerPoint</span></span>

- <span data-ttu-id="084fc-202">Исправлена проблема, из-за которой при дублировании слайд-шоу на второй монитор оно могло быть скрыто за другим окном.</span><span class="sxs-lookup"><span data-stu-id="084fc-202">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-203">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-203">Project</span></span>

- <span data-ttu-id="084fc-204">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="084fc-204">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-205">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-205">Word</span></span>

- <span data-ttu-id="084fc-206">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="084fc-206">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="084fc-207">Исправлена проблема печати, из-за которой применялась метка конфиденциальности с подложками.</span><span class="sxs-lookup"><span data-stu-id="084fc-207">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-16"></a><span data-ttu-id="084fc-209">Версия 2011: 16 октября</span><span class="sxs-lookup"><span data-stu-id="084fc-209">Version 2011: October 16</span></span>
<span data-ttu-id="084fc-210">*Версия 2011 (сборка 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-210">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-212">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-212">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-213">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-213">Excel</span></span>

- <span data-ttu-id="084fc-214">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="084fc-214">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="084fc-215">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-215">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="084fc-216">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-216">Outlook</span></span>

- <span data-ttu-id="084fc-217">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="084fc-217">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="084fc-218">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-218">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="084fc-219">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-219">PowerPoint</span></span>

- <span data-ttu-id="084fc-220">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="084fc-220">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="084fc-221">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-221">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="084fc-222">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-222">Word</span></span>

- <span data-ttu-id="084fc-223">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="084fc-223">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="084fc-224">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-224">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-227">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-227">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-228">Outlook</span></span>

- <span data-ttu-id="084fc-229">Мы исправили проблему, из-за которой пользователи не могли удалять встречи в календаре Групп Microsoft 365 в рамках обычной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="084fc-229">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="084fc-230">Исправлена проблема с невозможностью запуска Outlook при загрузке кэша псевдонимов.</span><span class="sxs-lookup"><span data-stu-id="084fc-230">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="084fc-231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-231">PowerPoint</span></span>

- <span data-ttu-id="084fc-232">Исправлена проблема, из-за которой в значке заполнителя содержимого рядом с "Изображениями" не было всплывающих подсказок.</span><span class="sxs-lookup"><span data-stu-id="084fc-232">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="084fc-233">Исправлена проблема, из-за которой при защищенном просмотре слайд-шоу, демонстрируемого в файле pptsx, можно было сделать снимок экрана документа, защищенного IRM.</span><span class="sxs-lookup"><span data-stu-id="084fc-233">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-09"></a><span data-ttu-id="084fc-235">Версия 2011: 9 октября</span><span class="sxs-lookup"><span data-stu-id="084fc-235">Version 2011: October 09</span></span>
<span data-ttu-id="084fc-236">*Версия 2011 (сборка 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-236">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-238">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-238">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-239">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-239">Excel</span></span>

- <span data-ttu-id="084fc-240">**Создание потоков данных Power Platform в запросах:** теперь можно экспортировать запросы в шаблоны Power Query, которые могут использоваться для создания новых потоков данных Power Platform.</span><span class="sxs-lookup"><span data-stu-id="084fc-240">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-241">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-241">PowerPoint</span></span>

- <span data-ttu-id="084fc-242">**Экспорт GIF с анимацией в диапазоне:** можно выбрать диапазон слайдов при экспорте в GIF с анимацией</span><span class="sxs-lookup"><span data-stu-id="084fc-242">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="084fc-243">**Создание GIF-файлов с прозрачным фоном:** при экспорте в GIF с анимацией новый параметр позволит сделать фон прозрачным.</span><span class="sxs-lookup"><span data-stu-id="084fc-243">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-246">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-246">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-247">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-247">Excel</span></span>

- <span data-ttu-id="084fc-248">Устранена проблема, при которой имя файла не изменялось после включения операции SaveAs для надстроек COM.</span><span class="sxs-lookup"><span data-stu-id="084fc-248">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="084fc-249">Устранена проблема, вызывавшая сбой при автоматическом сохранении с неверным или ошибочным сообщением об ошибке, если в модели данных Excel было неверное определение меры.</span><span class="sxs-lookup"><span data-stu-id="084fc-249">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="084fc-250">Устранена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-250">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="084fc-251">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-251">Outlook</span></span>

- <span data-ttu-id="084fc-252">Устранена проблема, из-за которой быстрая печать вложенных изображений вызывала ошибку: "Не удалось найти изображение.</span><span class="sxs-lookup"><span data-stu-id="084fc-252">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="084fc-253">Проверьте путь и повторите попытку."</span><span class="sxs-lookup"><span data-stu-id="084fc-253">Check the location, and then try again".</span></span>


- <span data-ttu-id="084fc-254">Устранена проблема, из-за которой у некоторых пользователей происходил запуск Outlook в автономном состоянии, пока они вручную не выбирали сетевой режим работы.</span><span class="sxs-lookup"><span data-stu-id="084fc-254">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="084fc-255">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-255">PowerPoint</span></span>

- <span data-ttu-id="084fc-256">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-256">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="084fc-257">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-257">Project</span></span>

- <span data-ttu-id="084fc-258">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChagne не имело правильного значения в случае изменения задержки в представлении типа "Форма задач".</span><span class="sxs-lookup"><span data-stu-id="084fc-258">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="084fc-259">Устранена проблема, из-за которой после группирования списка задач на сайте проекта нельзя было быстро изменить список задач.</span><span class="sxs-lookup"><span data-stu-id="084fc-259">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="084fc-260">Исправлена проблема, при которой после обновления корпоративного ресурса с помощью CSOM максимальные единицы для ресурса могли быть потеряны.</span><span class="sxs-lookup"><span data-stu-id="084fc-260">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="084fc-261">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-261">Word</span></span>

- <span data-ttu-id="084fc-262">Устранена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-262">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="084fc-263">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="084fc-263">Office Suite</span></span>

- <span data-ttu-id="084fc-264">Устранена проблема, из-за которой при интерактивном входе в SSO API возвращался код ошибки.</span><span class="sxs-lookup"><span data-stu-id="084fc-264">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-02"></a><span data-ttu-id="084fc-266">Версия 2010: 2 октября</span><span class="sxs-lookup"><span data-stu-id="084fc-266">Version 2010: October 02</span></span>
<span data-ttu-id="084fc-267">*Версия 2010 (сборка 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-267">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-269">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-269">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-270">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-270">Excel</span></span>

- <span data-ttu-id="084fc-271">**Создание типов данных с помощью диалогового окна дополнительных параметров.** В диалоговом окне дополнительных параметров можно вручную выбрать столбцы, объединяющие типы данных, которые вы создаете.</span><span class="sxs-lookup"><span data-stu-id="084fc-271">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-274">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-274">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="084fc-275">OneNote</span><span class="sxs-lookup"><span data-stu-id="084fc-275">OneNote</span></span>

- <span data-ttu-id="084fc-276">Исправлена проблема, из-за которой пользователь не мог выбрать и скопировать URL-адрес записной книжки из текстового поля в разделе "Файл OutSpace > Сведения".</span><span class="sxs-lookup"><span data-stu-id="084fc-276">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="084fc-277">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-277">Outlook</span></span>

- <span data-ttu-id="084fc-278">Исправлена проблема, из-за которой автоматически созданные сообщения отправлялись пустые, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="084fc-278">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="084fc-279">Исправлена проблема с кэшированием неправильного GUID для папок.</span><span class="sxs-lookup"><span data-stu-id="084fc-279">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="084fc-280">При копировании и вставке адреса электронной почты в поле "получатель" с отображаемым именем адрес электронной почты не всегда распознается правильно и появляется сообщение о недействительном адресе.</span><span class="sxs-lookup"><span data-stu-id="084fc-280">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="084fc-281">Эта проблема устранена, то есть имя и адрес электронной почты распознаются правильно, а предупреждение больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="084fc-281">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="084fc-282">Исправлена проблема, из-за которой общие сетевые папки не возвращали имя родительской папки.</span><span class="sxs-lookup"><span data-stu-id="084fc-282">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="084fc-283">Вместо сбоя они возвращали пустой путь, который ошибочно отправлялся в основную учетную запись.</span><span class="sxs-lookup"><span data-stu-id="084fc-283">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="084fc-284">Исправлена проблема, из-за которой после повторного открытия черновика в области просмотра "Только для чтения" включалось отслеживание изменений.</span><span class="sxs-lookup"><span data-stu-id="084fc-284">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="084fc-285">Исправлена проблема, из-за которой параметр "Сохранить как" был недоступен для классических вложений.</span><span class="sxs-lookup"><span data-stu-id="084fc-285">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="084fc-286">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="084fc-286">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="084fc-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-287">PowerPoint</span></span>

- <span data-ttu-id="084fc-288">Исправлена проблема, из-за которой PowerPoint не экспортировал маркеры списка в виде прямоугольников при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="084fc-288">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="084fc-289">Исправлена проблема, из-за которой диалоговое окно завершения сеанса отображалось на странице сводки, если вы переходили с последнего слайда к следующему после нажатия кнопки "Завершить сеанс" и до появления сводки.</span><span class="sxs-lookup"><span data-stu-id="084fc-289">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="084fc-290">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-290">Project</span></span>

- <span data-ttu-id="084fc-291">Исправлена проблема, из-за которой Project мог аварийно завершить работу, если вы применяли группу с помощью представления "Использование ресурсов" или "Лист ресурсов", а затем вставляли столбец.</span><span class="sxs-lookup"><span data-stu-id="084fc-291">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="084fc-292">Исправлена проблема, из-за которой могли возникать задержки при переключении представлений и открытии сведений о задаче или проекте при наличии настраиваемых полей с формулами и использовании освоенного объема.</span><span class="sxs-lookup"><span data-stu-id="084fc-292">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="084fc-293">Исправлена проблема, из-за которой метод VBA ConsolidateProjects мог выполнять регистрацию, если вы пытались добавить один проект несколько раз и присвоили параметру AttachToSources значение false.</span><span class="sxs-lookup"><span data-stu-id="084fc-293">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="084fc-294">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="084fc-294">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-25"></a><span data-ttu-id="084fc-296">Версия 2010: 25 сентября</span><span class="sxs-lookup"><span data-stu-id="084fc-296">Version 2010: September 25</span></span>
<span data-ttu-id="084fc-297">*Версия 2010 (сборка 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-297">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-299">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-299">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-300">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-300">Excel</span></span>

- <span data-ttu-id="084fc-301">**Создание типов данных с помощью Power Query:** создание насыщенных типов данных с помощью Power Query из любого источника данных</span><span class="sxs-lookup"><span data-stu-id="084fc-301">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-302">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-302">Outlook</span></span>

- <span data-ttu-id="084fc-303">**Обновления для задач пользовательского интерфейса:** визуальное обновление элементов задач</span><span class="sxs-lookup"><span data-stu-id="084fc-303">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="084fc-304">**Экономия времени при создании сообщений:** в Outlook отображаются предложения по литературной правке, помогающие быстро создавать сообщения.</span><span class="sxs-lookup"><span data-stu-id="084fc-304">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="084fc-305">Чтобы принять предложение, используйте клавишу TAB.</span><span class="sxs-lookup"><span data-stu-id="084fc-305">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-306">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-306">Word</span></span>

- <span data-ttu-id="084fc-307">**Обновление области "Корректор" (Майкрософт) в классическом приложении Word:** мы обновили текущий интерфейс области "Корректор" в классическом приложении Word.</span><span class="sxs-lookup"><span data-stu-id="084fc-307">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-310">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-310">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-311">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-311">Access</span></span>

- <span data-ttu-id="084fc-312">Исправлена проблема, из-за которой не удавалось правильно задать положение полосы прокрутки при загрузке окна запроса или схемы данных, сохраненных во время прокрутки.</span><span class="sxs-lookup"><span data-stu-id="084fc-312">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="084fc-313">Исправлена проблема, из-за которой в области задач "Добавить таблицу" неправильно отображались имена, содержащие '&'.</span><span class="sxs-lookup"><span data-stu-id="084fc-313">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="084fc-314">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-314">Excel</span></span>

- <span data-ttu-id="084fc-315">Исправлена проблема, из-за которой в диаграммах не работал многоуровневый ручной интервал категорий.</span><span class="sxs-lookup"><span data-stu-id="084fc-315">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="084fc-316">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="084fc-316">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="084fc-317">Исправлена проблема, из-за которой при добавлении в таблицу, используемую для проверки данных, не обновлялись параметры для всех листов в книге.</span><span class="sxs-lookup"><span data-stu-id="084fc-317">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="084fc-318">OneNote</span><span class="sxs-lookup"><span data-stu-id="084fc-318">OneNote</span></span>

- <span data-ttu-id="084fc-319">Исправлена проблема, из-за которой OneNote не поддерживал высокую контрастность цветов в полотне для пользовательских тем.</span><span class="sxs-lookup"><span data-stu-id="084fc-319">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="084fc-320">Исправлена проблема, из-за которой при наведении указателя мыши на зеленый цвет в селекторе цветов записной книжки появлялось всплывающее окно "красный мел".</span><span class="sxs-lookup"><span data-stu-id="084fc-320">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="084fc-321">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-321">PowerPoint</span></span>

- <span data-ttu-id="084fc-322">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="084fc-322">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="084fc-323">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-323">Word</span></span>

- <span data-ttu-id="084fc-324">Исправлена проблема, из-за которой ссылки на файлы, поддерживающие рабочий процесс, не открывались должным образом.</span><span class="sxs-lookup"><span data-stu-id="084fc-324">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-18"></a><span data-ttu-id="084fc-326">Версия 2010: 18 сентября</span><span class="sxs-lookup"><span data-stu-id="084fc-326">Version 2010: September 18</span></span>
<span data-ttu-id="084fc-327">*Версия 2010 (сборка 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="084fc-327">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-329">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-329">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-330">Outlook</span></span>

- <span data-ttu-id="084fc-331">**Проверка правописания в сообщениях в Редакторе:** теперь можно использовать рекомендации по грамматике и стилю в письмах для пользователей 64-разрядных версий Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-331">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="084fc-332">Найдите подчеркнутые слова, чтобы увидеть рекомендации Редактора по улучшению текста.</span><span class="sxs-lookup"><span data-stu-id="084fc-332">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="084fc-333">**Преодолейте языковый барьер с помощью встроенного переводчика.** Надстройки для перевода больше не нужны!</span><span class="sxs-lookup"><span data-stu-id="084fc-333">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="084fc-334">В сообщении щелкните правой кнопкой мыши, чтобы перевести определенные слова, фразы или весь текст.</span><span class="sxs-lookup"><span data-stu-id="084fc-334">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-337">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-337">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-338">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-338">Excel</span></span>

- <span data-ttu-id="084fc-339">Исправлена проблема с 2D-диаграммами с картами, когда нельзя было задать цвета для максимального, среднего и минимального значений ряда данных с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="084fc-339">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="084fc-340">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="084fc-340">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="084fc-341">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="084fc-341">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="084fc-342">Исправлена проблема, которая в некоторых случаях приводила к сбою на листе диаграммы при вводе формулы в строке формул.</span><span class="sxs-lookup"><span data-stu-id="084fc-342">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="084fc-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-343">Outlook</span></span>

- <span data-ttu-id="084fc-344">При копировании и вставке адреса электронной почты в поле "получатель" с отображаемым именем адрес электронной почты не всегда распознается правильно и появляется сообщение о недействительном адресе.</span><span class="sxs-lookup"><span data-stu-id="084fc-344">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="084fc-345">Эта проблема устранена, то есть имя и адрес электронной почты распознаются правильно, а предупреждение больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="084fc-345">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="084fc-346">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-346">Word</span></span>

- <span data-ttu-id="084fc-347">Исправлена проблема, из-за после прикосновения к исправлению (вставке или удалению) появлялось всплывающее примечание.</span><span class="sxs-lookup"><span data-stu-id="084fc-347">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="084fc-348">Исправлена проблема с удалением выносок примечаний в Word.</span><span class="sxs-lookup"><span data-stu-id="084fc-348">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="084fc-349">Исправлена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-349">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="084fc-350">Исправлена проблема с сохранением документа Word, содержащего ссылку и формулу.</span><span class="sxs-lookup"><span data-stu-id="084fc-350">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-11"></a><span data-ttu-id="084fc-352">Версия 2010: 11 сентября</span><span class="sxs-lookup"><span data-stu-id="084fc-352">Version 2010: September 11</span></span>
<span data-ttu-id="084fc-353">*Версия 2010 (сборка 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-353">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-355">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-355">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="084fc-356">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-356">Access</span></span>

- <span data-ttu-id="084fc-357">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-357">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-358">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-358">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-359">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-359">Excel</span></span>

- <span data-ttu-id="084fc-360">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-360">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-361">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-361">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="084fc-362">OneNote</span><span class="sxs-lookup"><span data-stu-id="084fc-362">OneNote</span></span>

- <span data-ttu-id="084fc-363">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-363">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-364">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-364">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-365">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-365">Outlook</span></span>

- <span data-ttu-id="084fc-366">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-366">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-367">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-367">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-368">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-368">PowerPoint</span></span>

- <span data-ttu-id="084fc-369">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-369">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-370">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-370">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-371">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-371">Project</span></span>

- <span data-ttu-id="084fc-372">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-372">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-373">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-373">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="084fc-374">Publisher</span><span class="sxs-lookup"><span data-stu-id="084fc-374">Publisher</span></span>

- <span data-ttu-id="084fc-375">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-375">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-376">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-376">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="084fc-377">Visio</span><span class="sxs-lookup"><span data-stu-id="084fc-377">Visio</span></span>

- <span data-ttu-id="084fc-378">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-378">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-379">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-379">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-380">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-380">Word</span></span>

- <span data-ttu-id="084fc-381">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="084fc-381">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="084fc-382">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-382">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-385">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-386">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-386">Excel</span></span>

- <span data-ttu-id="084fc-387">Исправлена проблема, из-за которой при переключении между листами с большим объемом данных могла возникать заметная задержка, если был включен страничный режим.</span><span class="sxs-lookup"><span data-stu-id="084fc-387">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-388">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-388">Outlook</span></span>

- <span data-ttu-id="084fc-389">Исправлена проблема, из-за которой сообщения электронной почты скрывались после отключения сортировки почты и выполнения сортировки.</span><span class="sxs-lookup"><span data-stu-id="084fc-389">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-390">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-390">PowerPoint</span></span>

- <span data-ttu-id="084fc-391">Исправлена проблема, из-за которой изображение GIF анимировалось только один раз в текстовом редакторе и слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="084fc-391">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-04"></a><span data-ttu-id="084fc-393">Версия 2010: 4 сентября</span><span class="sxs-lookup"><span data-stu-id="084fc-393">Version 2010: September 04</span></span>
<span data-ttu-id="084fc-394">*Версия 2010 (сборка 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="084fc-394">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-396">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-396">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-397">Outlook</span></span>

- <span data-ttu-id="084fc-398">**Закрепление сообщения электронной почты:** эта функция попомгает пользователям следить за письмами, которым нужно уделить внимание или которые следует оставить наверху списка сообщений.</span><span class="sxs-lookup"><span data-stu-id="084fc-398">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="084fc-399">**Получение предложений электронной почты при поиске пользователя:** когда вы вводите условия поиска Outlook, вы получаете в предложениях наиболее подходящую электронную почту.</span><span class="sxs-lookup"><span data-stu-id="084fc-399">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="084fc-400">**Получение предложений электронной почты при поиске пользователя:** когда вы вводите условия поиска Outlook, вы получаете в предложениях наиболее подходящую электронную почту.</span><span class="sxs-lookup"><span data-stu-id="084fc-400">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="084fc-401">**Редактор Microsoft получает обновление для настольных клиентов Word и Outlook:** мы запускаем новую модель "Щелчок для просмотра" для получения предложений по правописанию, грамматике и тонкостям стиля.</span><span class="sxs-lookup"><span data-stu-id="084fc-401">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="084fc-402">Помимо этого, добавляется отдельная карточка для просмотра предложений.</span><span class="sxs-lookup"><span data-stu-id="084fc-402">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-403">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-403">Word</span></span>

- <span data-ttu-id="084fc-404">**Редактор Microsoft получает обновление для настольных клиентов Word и Outlook:** мы запускаем новую модель "Щелчок для просмотра" для получения предложений по правописанию, грамматике и тонкостям стиля.</span><span class="sxs-lookup"><span data-stu-id="084fc-404">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="084fc-405">Помимо этого, добавляется отдельная карточка для просмотра предложений.</span><span class="sxs-lookup"><span data-stu-id="084fc-405">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-408">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-408">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-409">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-409">Excel</span></span>

- <span data-ttu-id="084fc-410">Мы устранили проблему, из-за которой при открытии файла с функцией ПУСТЬ появлялось сообщение: "Обнаружена проблема в содержимом файла "ваш_файл.xlsx".</span><span class="sxs-lookup"><span data-stu-id="084fc-410">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="084fc-411">Хотите восстановить все, что возможно?</span><span class="sxs-lookup"><span data-stu-id="084fc-411">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="084fc-412">Если вы доверяете источнику этой книги, выберите Да".</span><span class="sxs-lookup"><span data-stu-id="084fc-412">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="084fc-413">Исправлена ошибка сбоя, связанного со ссылками на надстройки XLAM и именованными диапазонами.</span><span class="sxs-lookup"><span data-stu-id="084fc-413">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="084fc-414">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="084fc-414">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="084fc-415">Исправлена проблема, при которой при назначении пользователем настраиваемого стиля динамическому массиву появлялась ошибка: "Изменение части массива недопустимо".</span><span class="sxs-lookup"><span data-stu-id="084fc-415">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="084fc-416">Это устаревшее ограничение, которое следовало убрать.</span><span class="sxs-lookup"><span data-stu-id="084fc-416">This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="084fc-417">Исправлена проблема с панелью формул Excel, которая не отображалась полностью после отключения от устройства, например с подключении или отклчючении от уадаленного сеанса или при смене монитора.</span><span class="sxs-lookup"><span data-stu-id="084fc-417">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-418">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-418">Outlook</span></span>

- <span data-ttu-id="084fc-419">Исправлена проблема, которая обеспечивала включение/отключение параметров входа по умолчанию через групповые политики.</span><span class="sxs-lookup"><span data-stu-id="084fc-419">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="084fc-420">Исправлена проблема, при которой устаревшее имя домена для отправителя сообщения электронной почты с правами помощника или менеджера сохранялось и показывалось при перемещении черновика письма между папками.</span><span class="sxs-lookup"><span data-stu-id="084fc-420">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="084fc-421">Исправлена проблем, при которой у некоторых пользователей Outlook запускался в автономном состоянии, пока они не выбирали сетевой режим работы вручную.</span><span class="sxs-lookup"><span data-stu-id="084fc-421">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="084fc-422">Исправлена проблема, когда при запуске кода VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") после включения однострочной ленты (SLR) выдавалась ошибка среды выполнения.</span><span class="sxs-lookup"><span data-stu-id="084fc-422">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="084fc-423">Исправлена проблема, при которой кнопки "OK" и "Отмена" в диалогах с автоматическими ответами были не видны в системах с высоким разрешением (например, 1750 x 1920), если выбран большой размер текста (например, 175%).</span><span class="sxs-lookup"><span data-stu-id="084fc-423">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="084fc-424">Исправлена проблема, при которой в результате отправки приглашения на собрание из пустой группы контактов в другую группу контактов появлялась ошибка.</span><span class="sxs-lookup"><span data-stu-id="084fc-424">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="084fc-425">Исправлена проблема, которая вызывала сбой при открытии определенных очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="084fc-425">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="084fc-426">Исправлена ошибка, при которой в случае, когда требуется, чтобы в групповой политике всегда была активна надстройка, надстройка мониторинга становится недоступной, чтобы не дать пользователям отключить надстройку.</span><span class="sxs-lookup"><span data-stu-id="084fc-426">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-427">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-427">PowerPoint</span></span>

- <span data-ttu-id="084fc-428">Исправлена ошибка, при которой во время слайд-шоу видео не воспроизводились автоматически.</span><span class="sxs-lookup"><span data-stu-id="084fc-428">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="084fc-429">Исправлена ошибка, при которой после загрузки PowerPoint, вставки слайда, открытия и закрытия панели комментариев, слайды в области эскизов отображались с наложением.</span><span class="sxs-lookup"><span data-stu-id="084fc-429">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-430">Проект</span><span class="sxs-lookup"><span data-stu-id="084fc-430">Project</span></span>

- <span data-ttu-id="084fc-431">Исправлена проблема, при которой оставшиеся затраты не подсчитываются правильно, если у ресурса есть несколько таблиц норм затрат.</span><span class="sxs-lookup"><span data-stu-id="084fc-431">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="084fc-432">Исправлена проблема, из-за которой дата окончания проекта не обновляется для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-432">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-433">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-433">Word</span></span>

- <span data-ttu-id="084fc-434">Исправлена проблема, из-за которой при нажатии пользователя на комментарий вокруг комментария отображалась граница.</span><span class="sxs-lookup"><span data-stu-id="084fc-434">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="084fc-435">Исправлена проблема, при которой фокус не переходил на панели комментариев, если масштаб документа был 160% или более, а панель комментариев была не видна.</span><span class="sxs-lookup"><span data-stu-id="084fc-435">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="084fc-436">Исправлена проблема, при которой комментарии для одного документа показывались в других открытых документах после переключения между открытыми документами.</span><span class="sxs-lookup"><span data-stu-id="084fc-436">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="084fc-437">Исправлена проблема, из-за которой при создании черновика комментария и привязки его к линии, на которой уже есть комментарии, то черновик имел неверный порядок по отношению к выделенному комментарию в SideTrack.</span><span class="sxs-lookup"><span data-stu-id="084fc-437">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="084fc-438">Исправлена проблема, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="084fc-438">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="084fc-439">Исправлена проблема с макросом, из-за которой AutoOpen запускался до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="084fc-439">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-28"></a><span data-ttu-id="084fc-441">Версия 2009: 28 августа</span><span class="sxs-lookup"><span data-stu-id="084fc-441">Version 2009: August 28</span></span>
<span data-ttu-id="084fc-442">*Версия 2009 (сборка 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="084fc-442">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-444">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-444">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-445">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-445">Outlook</span></span>

- <span data-ttu-id="084fc-446">Исправлена проблема, из-за которой пользователи могли отправлять содержимое письма, к которому применена политика "Не пересылать", в OneNote, если выбрано несколько сообщений.</span><span class="sxs-lookup"><span data-stu-id="084fc-446">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-447">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-447">PowerPoint</span></span>

- <span data-ttu-id="084fc-448">Исправлена проблема с отключенной функцией вставки видео.</span><span class="sxs-lookup"><span data-stu-id="084fc-448">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-449">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-449">Word</span></span>

- <span data-ttu-id="084fc-450">Исправлена проблема, из-за которой пользователь не мог выйти из колонтитулов при выборе примечания.</span><span class="sxs-lookup"><span data-stu-id="084fc-450">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="084fc-451">Исправлена проблема, не позволявшая пользователям просматривать цепочки примечаний, выходивших за границы ответвления, так как прокрутка в ответвлении не работала.</span><span class="sxs-lookup"><span data-stu-id="084fc-451">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="084fc-452">Исправлена проблема, из-за которой поиск разрешенных примечаний в панели ответвления не работал.</span><span class="sxs-lookup"><span data-stu-id="084fc-452">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-453">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-453">Office Suite</span></span>

- <span data-ttu-id="084fc-454">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="084fc-454">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="084fc-455">Исправлена проблема в диалоговом окне "Сжатие рисунка", из-за которой некоторые выбранные пользователем параметры разрешения не сохранялись.</span><span class="sxs-lookup"><span data-stu-id="084fc-455">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-21"></a><span data-ttu-id="084fc-457">Версия 2009: 21 августа</span><span class="sxs-lookup"><span data-stu-id="084fc-457">Version 2009: August 21</span></span>
<span data-ttu-id="084fc-458">*Версия 2009 (сборка 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-458">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-460">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-460">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-461">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-461">Excel</span></span>

- <span data-ttu-id="084fc-462">**Перо действий в Excel.** Перо для рукописного ввода и быстрого изменения данных</span><span class="sxs-lookup"><span data-stu-id="084fc-462">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-463">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-463">Outlook</span></span>

- <span data-ttu-id="084fc-464">**Удаление беседы владельцем сообщения.** Эта функция позволяет удалять беседы владельцу сообщения.</span><span class="sxs-lookup"><span data-stu-id="084fc-464">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-467">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-467">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-468">Доступ</span><span class="sxs-lookup"><span data-stu-id="084fc-468">Access</span></span>

- <span data-ttu-id="084fc-469">Исправлена проблема, из-за которой подключения к базе данных ODBC не работали со сторонними приложениями.</span><span class="sxs-lookup"><span data-stu-id="084fc-469">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-470">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-470">Excel</span></span>

- <span data-ttu-id="084fc-471">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="084fc-471">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="084fc-472">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="084fc-472">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-473">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-473">Outlook</span></span>

- <span data-ttu-id="084fc-474">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-474">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-475">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-475">Word</span></span>

- <span data-ttu-id="084fc-476">Исправлена проблема, из-за которой Word мог аварийно завершить работу после удаления примечаний.</span><span class="sxs-lookup"><span data-stu-id="084fc-476">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="084fc-477">Исправлена проблема, из-за которой иногда маркеры списка отображались в письме неверно.</span><span class="sxs-lookup"><span data-stu-id="084fc-477">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-14"></a><span data-ttu-id="084fc-479">Версия 2009: 14 августа</span><span class="sxs-lookup"><span data-stu-id="084fc-479">Version 2009: August 14</span></span>
<span data-ttu-id="084fc-480">*Версия 2009 (сборка 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-480">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-482">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-482">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-483">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-483">Excel</span></span>

- <span data-ttu-id="084fc-484">Исправлена проблема, из-за которой при вводе имени формулы со скобками и вызове справки с помощью клавиши F1 не отображался раздел справки, относящийся к этой формуле.</span><span class="sxs-lookup"><span data-stu-id="084fc-484">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="084fc-485">Исправлена проблема, из-за которой макросы, назначенные кнопкам, не работали после восстановления более ранней версии файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-485">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-486">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-486">Outlook</span></span>

- <span data-ttu-id="084fc-487">Это изменение исправляет проблему, из-за которой страница "Собрание" продолжала отображаться после того, как пользователь переключал вкладки со страницы "Собрание" на страницу "Помощник по планированию".</span><span class="sxs-lookup"><span data-stu-id="084fc-487">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-488">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-488">Word</span></span>

- <span data-ttu-id="084fc-489">Исправлена проблема, из-за которой неправильно отображался значок маркера.</span><span class="sxs-lookup"><span data-stu-id="084fc-489">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-07"></a><span data-ttu-id="084fc-491">Версия 2009: 7 августа</span><span class="sxs-lookup"><span data-stu-id="084fc-491">Version 2009: August 07</span></span>
<span data-ttu-id="084fc-492">*Версия 2009 (сборка 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-492">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-494">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-494">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-495">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-495">Outlook</span></span>

- <span data-ttu-id="084fc-496">Исправлена проблема, из-за которой атрибуты учетной записи пользователя в Active Directory для "otherTelephone" и "otherHomePhone" не сопоставлялись с соответствующими атрибутами LDAP Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-496">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-497">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-497">PowerPoint</span></span>

- <span data-ttu-id="084fc-498">Исправлена проблема, из-за которой при определенных условиях пользователи не видели ленту/заголовок окна.</span><span class="sxs-lookup"><span data-stu-id="084fc-498">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-31"></a><span data-ttu-id="084fc-500">Версия 2008: 31 июля</span><span class="sxs-lookup"><span data-stu-id="084fc-500">Version 2008: July 31</span></span>
<span data-ttu-id="084fc-501">*Версия 2008 (сборка 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-501">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-503">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-504">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-504">Excel</span></span>

- <span data-ttu-id="084fc-505">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-505">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="084fc-506">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="084fc-506">No conversion required.</span></span><br /><span data-ttu-id="084fc-507">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="084fc-507">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-508">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-508">Outlook</span></span>

- <span data-ttu-id="084fc-509">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-509">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="084fc-510">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="084fc-510">No conversion required.</span></span><br /><span data-ttu-id="084fc-511">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="084fc-511">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-512">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-512">PowerPoint</span></span>

- <span data-ttu-id="084fc-513">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-513">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="084fc-514">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="084fc-514">No conversion required.</span></span><br /><span data-ttu-id="084fc-515">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="084fc-515">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="084fc-516">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-516">Word</span></span>

- <span data-ttu-id="084fc-517">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-517">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="084fc-518">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="084fc-518">No conversion required.</span></span><br /><span data-ttu-id="084fc-519">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="084fc-519">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-522">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-522">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-523">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-523">Access</span></span>

- <span data-ttu-id="084fc-524">Была исправлена проблема, когда при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке «Слишком сложный запрос.»</span><span class="sxs-lookup"><span data-stu-id="084fc-524">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-525">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-525">Excel</span></span>

- <span data-ttu-id="084fc-526">Мы исправили проблему, когда при изменении порядка рядов диаграммы соответствующие флажки не были упорядочены по рядам.</span><span class="sxs-lookup"><span data-stu-id="084fc-526">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="084fc-527">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="084fc-527">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-528">Outlook</span></span>

- <span data-ttu-id="084fc-529">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="084fc-529">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="084fc-530">Исправлена проблема, из-за которой в Outlook некорректно отображались разрывы строк в содержимом файла Markdown.</span><span class="sxs-lookup"><span data-stu-id="084fc-530">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-531">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-531">PowerPoint</span></span>

- <span data-ttu-id="084fc-532">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="084fc-532">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="084fc-533">Мы исправили проблемы с кнопкой "формы" в PowerPoint, которая не позволяла создавать формы, когда доступ к магазину Office не был разрешен.</span><span class="sxs-lookup"><span data-stu-id="084fc-533">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-534">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-534">Project</span></span>

- <span data-ttu-id="084fc-535">Мы исправили проблемы, когда для списка задач SharePoint кнопки ленты на второй вкладке могли быть отключены.</span><span class="sxs-lookup"><span data-stu-id="084fc-535">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-536">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-536">Word</span></span>

- <span data-ttu-id="084fc-537">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="084fc-537">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="084fc-538">Мы исправили проблему, когда при добавлении примечаний для отслеживания изменений, неожиданно открывалась область исправлений.</span><span class="sxs-lookup"><span data-stu-id="084fc-538">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="084fc-539">Мы исправили проблему, когда ссылки на документы не вставлялись в поле «Примечания» через «Вставка» -> Раскрывающийся список.</span><span class="sxs-lookup"><span data-stu-id="084fc-539">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="084fc-540">Мы исправили проблему, когда после добавления изображения, содержащего гиперссылку, количество гиперссылок в коллекции гиперссылок VBA было наверно подсчитано.</span><span class="sxs-lookup"><span data-stu-id="084fc-540">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-24"></a><span data-ttu-id="084fc-542">Версия 2008: 24 июля</span><span class="sxs-lookup"><span data-stu-id="084fc-542">Version 2008: July 24</span></span>
<span data-ttu-id="084fc-543">*Версия 2008 (сборка 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-543">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-545">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-545">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-546">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-546">Excel</span></span>

- <span data-ttu-id="084fc-547">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="084fc-547">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="084fc-548">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-548">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-551">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-551">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="084fc-552">OneNote</span><span class="sxs-lookup"><span data-stu-id="084fc-552">OneNote</span></span>

- <span data-ttu-id="084fc-553">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="084fc-553">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-554">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-554">Word</span></span>

- <span data-ttu-id="084fc-555">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="084fc-555">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="084fc-556">Исправлена проблема, из-за которой команда "Определенные пользователи" для отслеживания изменений была отключена.</span><span class="sxs-lookup"><span data-stu-id="084fc-556">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="084fc-557">Исправлены случайные зависания при открытии HTML-файлов.</span><span class="sxs-lookup"><span data-stu-id="084fc-557">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-17"></a><span data-ttu-id="084fc-559">Версия 2008: 17 июля</span><span class="sxs-lookup"><span data-stu-id="084fc-559">Version 2008: July 17</span></span>
<span data-ttu-id="084fc-560">*Версия 2008 (сборка 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-560">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-562">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-562">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-563">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-563">Excel</span></span>

- <span data-ttu-id="084fc-564">Исправлена проблема, из-за которой каждый раз, когда сводная диаграмма со скрытыми линиями выноски сохранялась и повторно открывалась, линии выноски становились видимыми.</span><span class="sxs-lookup"><span data-stu-id="084fc-564">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="084fc-565">Исправлена проблема, из-за которой диаграммы не всегда обновлялись ожидаемым образом, если для книги был включен параметр ForceFullCalculation с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="084fc-565">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-566">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-566">Outlook</span></span>

- <span data-ttu-id="084fc-567">Исправлена проблема с созданием нескольких профилей в Outlook из одного домена электронной почты.</span><span class="sxs-lookup"><span data-stu-id="084fc-567">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="084fc-568">Устранена проблема, приводившая к отсутствию значка блокировки в заголовке зашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="084fc-568">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="084fc-569">Устранена проблема, приводившая к удалению вложений из сообщений S/MIME при отправке в незашифрованном виде.</span><span class="sxs-lookup"><span data-stu-id="084fc-569">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="084fc-570">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="084fc-570">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="084fc-571">Устранена проблема, из-за которой вложения повреждались при отправке незашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="084fc-571">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="084fc-572">Устранена проблема, из-за которой пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="084fc-572">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="084fc-573">Устранена проблема, из-за которой получатели не могли сохранять сообщения с защищенными правами, даже если отправитель предоставил разрешение на сохранение.</span><span class="sxs-lookup"><span data-stu-id="084fc-573">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="084fc-574">Устранена проблема, приводившая к усечению некоторых подписей параметров расширенного поиска на некоторых языках.</span><span class="sxs-lookup"><span data-stu-id="084fc-574">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-575">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-575">Project</span></span>

- <span data-ttu-id="084fc-576">Исправлена проблема, из-за которой задачи, перечисленные в представлении доски задач, не синхронизировались с диалоговым окном "Назначение ресурсов".</span><span class="sxs-lookup"><span data-stu-id="084fc-576">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="084fc-577">Исправлена проблема, из-за которой при копировании и вставке задачи с несколькими зависимостями не все зависимости копировались правильно.</span><span class="sxs-lookup"><span data-stu-id="084fc-577">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-578">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-578">Word</span></span>

- <span data-ttu-id="084fc-579">Исправлена проблема, из-за которой команда "Корректор" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="084fc-579">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="084fc-580">Исправлена проблема, из-за которой команда "Показать разметку" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="084fc-580">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="084fc-581">Исправлена проблема в пользовательском XML, из-за которой состояние примечаний могло исчезать при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="084fc-581">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-582">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-582">Office Suite</span></span>

- <span data-ttu-id="084fc-583">Исправлена проблема, из-за которой после открытия пользователем нового окна приложения из панели задач и создания пустого документа создавались дополнительные файлы.</span><span class="sxs-lookup"><span data-stu-id="084fc-583">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="084fc-584">Исправлена проблема, из-за которой в случае редактирования документа и утраты разрешений пользователь не уведомлялся о необходимости повторной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="084fc-584">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-10"></a><span data-ttu-id="084fc-586">Версия 2008: 10 июля</span><span class="sxs-lookup"><span data-stu-id="084fc-586">Version 2008: July 10</span></span>
<span data-ttu-id="084fc-587">*Версия 2008 (сборка 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-587">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-589">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-589">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-590">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-590">Outlook</span></span>

- <span data-ttu-id="084fc-591">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если не установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="084fc-591">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="084fc-592">Исправлена проблема, из-за которой кнопка печати отображалась в отключенном состоянии даже при наличии у пользователя соответствующих разрешений на печать.</span><span class="sxs-lookup"><span data-stu-id="084fc-592">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-593">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-593">Project</span></span>

- <span data-ttu-id="084fc-594">Исправлена проблема, из-за которой при попытке сохранить файл PDF или XPS из Project в библиотеке документов SharePoint ничего не происходило.</span><span class="sxs-lookup"><span data-stu-id="084fc-594">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-595">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-595">Word</span></span>

- <span data-ttu-id="084fc-596">Исправлена проблема, из-за которой Word переставал отвечать на запросы после вставки текста и изображения в поле примечаний.</span><span class="sxs-lookup"><span data-stu-id="084fc-596">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="084fc-597">Исправлена проблема, из-за которой кнопка "Создать примечание" отключалась после удаления последнего примечания.</span><span class="sxs-lookup"><span data-stu-id="084fc-597">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-03"></a><span data-ttu-id="084fc-599">Версия 2007: 3 июля</span><span class="sxs-lookup"><span data-stu-id="084fc-599">Version 2007: July 03</span></span>
<span data-ttu-id="084fc-600">*Версия 2007 (сборка 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="084fc-600">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-602">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-602">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-603">Outlook</span></span>

- <span data-ttu-id="084fc-604">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="084fc-604">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="084fc-605">**Новая функция "Поиск помещений".** Поиск конференц-залов с учетом различных возможностей. </span><span class="sxs-lookup"><span data-stu-id="084fc-605">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-608">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-608">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-609">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-609">Excel</span></span>

- <span data-ttu-id="084fc-610">Устранена проблема, связанная с тем, что таблицы моделей данных, созданные в некоторых версиях Excel, не отображались в представлении "Предварительный просмотр таблицы" даже при отсутствии изменений запроса, связанного с таблицей.</span><span class="sxs-lookup"><span data-stu-id="084fc-610">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="084fc-611">Устранена проблема, из-за которой переставали работать формулы при отключении параметра "Игнорировать тип ссылки" в диалоговом окне "Задать имя \ Применение имен".</span><span class="sxs-lookup"><span data-stu-id="084fc-611">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="084fc-612">Исправлена проблема, из-за которой очистка расширенного фильтра данных могла привести к потере форматирования таблицы.</span><span class="sxs-lookup"><span data-stu-id="084fc-612">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="084fc-613">Исправлена проблема, из-за которой в подписи к документу вместо имени внедренного PDF-документа отображался весь путь к нему.</span><span class="sxs-lookup"><span data-stu-id="084fc-613">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="084fc-614">Исправлена проблема, из-за которой мог произойти сбой после отключения облачного соединителя Wolfram с последующим сохранением и повторным открытием книги Excel.</span><span class="sxs-lookup"><span data-stu-id="084fc-614">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="084fc-615">Исправлена проблема, вызывавшая сбой в результате загрузки Excel при включенной надстройке "Поиск решения".</span><span class="sxs-lookup"><span data-stu-id="084fc-615">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-616">Outlook</span></span>

- <span data-ttu-id="084fc-617">Исправлена проблема, вызывавшая зависание приложения Outlook, когда в строке "Кому" было указано более 130 получателей. Кроме того, мы повысили производительность отрисовки текста.</span><span class="sxs-lookup"><span data-stu-id="084fc-617">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="084fc-618">Исправлена проблема, из-за которой в области To Do для событий длительностью более двух дней указывалось одинаковое время окончания для всех последующих дней.</span><span class="sxs-lookup"><span data-stu-id="084fc-618">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="084fc-619">Исправлена проблема, из-за которой у пользователей Outlook после использования общих календарей на несколько минут переставал обновляться список сообщений.</span><span class="sxs-lookup"><span data-stu-id="084fc-619">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-620">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-620">PowerPoint</span></span>

- <span data-ttu-id="084fc-621">Исправлена проблема, из-за которой при вставке HTML в область текста на слайде производилась вставка в текстовое поле, созданное в верхней части слайда.</span><span class="sxs-lookup"><span data-stu-id="084fc-621">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="084fc-622">Исправлена проблема, из-за которой возникало необработанное исключение при выделении всех слайдов в режиме докладчика и выходе из режима докладчика с помощью клавиш ALT+TAB, возврате в слайд-шоу и щелчке по команде "Завершить слайд-шоу".</span><span class="sxs-lookup"><span data-stu-id="084fc-622">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-623">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-623">Project</span></span>

- <span data-ttu-id="084fc-624">Исправлена проблема, из-за которой мог возникнуть сбой при открытии определенных XML-файлов.</span><span class="sxs-lookup"><span data-stu-id="084fc-624">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="084fc-625">Исправлена проблема, из-за которой не удавалось открыть файл Project из библиотеки документов SharePoint, если библиотека находилась в современном режиме.</span><span class="sxs-lookup"><span data-stu-id="084fc-625">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="084fc-626">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="084fc-626">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-627">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-627">Word</span></span>

- <span data-ttu-id="084fc-628">Исправлена проблема в режиме совместного редактирования: теперь при возникновении конфликта объединения изменений при том, что пользователь уже выбрал отмену изменений, вариант сохранения или отмены изменений больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="084fc-628">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="084fc-629">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="084fc-629">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-26"></a><span data-ttu-id="084fc-631">Версия 2007: 26 июня</span><span class="sxs-lookup"><span data-stu-id="084fc-631">Version 2007: June 26</span></span>
<span data-ttu-id="084fc-632">*Версия 2007 (сборка 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="084fc-632">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-634">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-634">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-635">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-635">Access</span></span>

- <span data-ttu-id="084fc-636">Исправлена проблема, из-за которой диспетчер связанных таблиц запрашивал первичный ключ при обновлении связанной таблицы SQL.</span><span class="sxs-lookup"><span data-stu-id="084fc-636">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="084fc-637">Исправлена проблема, из-за которой запросы в редакторе запросов не отображались при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="084fc-637">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="084fc-638">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="084fc-638">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-639">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-639">Outlook</span></span>

- <span data-ttu-id="084fc-640">Исправлена проблема, из-за которой пользователи не могли "отправить как" или "отправить от имени" группы рассылки.</span><span class="sxs-lookup"><span data-stu-id="084fc-640">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="084fc-641">Исправлена проблема, из-за которой вставка изображения в текст сообщения с последующим сохранением сообщения в виде черновика приводила к изменению размера изображения.</span><span class="sxs-lookup"><span data-stu-id="084fc-641">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="084fc-642">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="084fc-642">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-643">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-643">Project</span></span>

- <span data-ttu-id="084fc-644">Исправлена проблема, из-за которой ссылки планировщика Project в средах GCC были отключены.</span><span class="sxs-lookup"><span data-stu-id="084fc-644">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-645">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-645">Office Suite</span></span>

- <span data-ttu-id="084fc-646">Исправлена проблема, из-за которой текст, вставленный в изображение в формате SVG, был неудобочитаемым после добавления в файл Word, Excel или PowerPoint, сохранения и закрытия файла, а затем его повторного открытия.</span><span class="sxs-lookup"><span data-stu-id="084fc-646">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-19"></a><span data-ttu-id="084fc-648">Версия 2007: 19 июня</span><span class="sxs-lookup"><span data-stu-id="084fc-648">Version 2007: June 19</span></span>
<span data-ttu-id="084fc-649">*Версия 2007 (сборка 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-649">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-651">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-651">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-652">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-652">Excel</span></span>

- <span data-ttu-id="084fc-653">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении книги в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="084fc-653">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="084fc-654">Исправлена проблема, из-за которой книги были доступны только для чтения, если файл рекомендовался только для чтения.</span><span class="sxs-lookup"><span data-stu-id="084fc-654">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-655">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-655">Outlook</span></span>

- <span data-ttu-id="084fc-656">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="084fc-656">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="084fc-657">Исправлена проблема, приводившая к отображению следующей ошибки при закрытии ранее сохраненной встречи: "Не удалось сохранить элемент, так как он был изменен другим пользователем или в другом окне.</span><span class="sxs-lookup"><span data-stu-id="084fc-657">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="084fc-658">Создать копию в папке для элемента по умолчанию?"</span><span class="sxs-lookup"><span data-stu-id="084fc-658">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="084fc-659">Исправлена проблема, из-за которой даты в мини-календаре не выделялись полужирным шрифтом для пользователей в Японии.</span><span class="sxs-lookup"><span data-stu-id="084fc-659">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="084fc-660">Исправлена проблема, препятствовавшая отображению точного времени в напоминаниях календаря для собраний, до наступления которых осталось меньше недели.</span><span class="sxs-lookup"><span data-stu-id="084fc-660">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-661">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-661">PowerPoint</span></span>

- <span data-ttu-id="084fc-662">Исправлена проблема, из-за которой в галерее совместного редактирования не обновлялся цветовой индикатор присутствия пользователя во время совместного редактирования в реальном времени.</span><span class="sxs-lookup"><span data-stu-id="084fc-662">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-663">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-663">Project</span></span>

- <span data-ttu-id="084fc-664">Исправлена проблема, из-за которой процент выполнения задачи был менее 100 %, если задачи с фиксированной длительностью выполнены на 100 %, но не указано фактическое окончание.</span><span class="sxs-lookup"><span data-stu-id="084fc-664">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-665">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-665">Word</span></span>

- <span data-ttu-id="084fc-666">Исправлена проблема, из-за которой цвет гиперссылки HTML отображался неправильно.</span><span class="sxs-lookup"><span data-stu-id="084fc-666">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-667">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-667">Office Suite</span></span>

- <span data-ttu-id="084fc-668">Исправлена проблема, из-за которой URL-адреса, отличные от HTTP или HTTPS, не отображались в списке недавно использовавшихся.</span><span class="sxs-lookup"><span data-stu-id="084fc-668">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-12"></a><span data-ttu-id="084fc-670">Версия 2007: 12 июня</span><span class="sxs-lookup"><span data-stu-id="084fc-670">Version 2007: June 12</span></span>
<span data-ttu-id="084fc-671">*Версия 2007 (сборка 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-671">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-673">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-673">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-674">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-674">Excel</span></span>

- <span data-ttu-id="084fc-675">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 E5/A5 или Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="084fc-675">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="084fc-676">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="084fc-676">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="084fc-677">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="084fc-677">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="084fc-678">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-678">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="084fc-679">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="084fc-679">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-682">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-682">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-683">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-683">Access</span></span>

- <span data-ttu-id="084fc-684">Устранена проблема, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="084fc-684">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-685">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-685">Excel</span></span>

- <span data-ttu-id="084fc-686">Устранена проблема, из-за которой нельзя было правильно отформатировать основные линии сетки лепестковых диаграмм.</span><span class="sxs-lookup"><span data-stu-id="084fc-686">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-687">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-687">Project</span></span>

- <span data-ttu-id="084fc-688">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="084fc-688">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="084fc-689">Устранена проблема, из-за которой при сбросе или обновлении базового плана могли изменяться показатели расходов или рабочих ресурсов тех или иных этапов бюджета, и базовый план мог содержать неправильные значения статей бюджета.</span><span class="sxs-lookup"><span data-stu-id="084fc-689">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-690">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-690">Word</span></span>

- <span data-ttu-id="084fc-691">Исправлена проблема, из-за которой не работала функция очистки форматирования в области примечаний с помощью кнопки "Очистить форматирование" на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-691">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="084fc-692">Исправлена проблема, из-за которой изменение размера таблицы при скрытой линейке приводило к миганию других приложений, работающих на заднем фоне.</span><span class="sxs-lookup"><span data-stu-id="084fc-692">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="084fc-693">Исправлена проблема, из-за которой в режиме совместного редактирования ответы на примечания иногда не отображались в области примечаний, но отображались в области изменений.</span><span class="sxs-lookup"><span data-stu-id="084fc-693">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="084fc-694">Исправлена проблема, из-за которой в тех случаях, когда в Word имелся список более чем 50 часто открываемых документов, после сохранения и открытия документа отображался журнал изменений, хотя никаких изменений в документ не вносилось.</span><span class="sxs-lookup"><span data-stu-id="084fc-694">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-05"></a><span data-ttu-id="084fc-696">Версия 2006: 5 июня</span><span class="sxs-lookup"><span data-stu-id="084fc-696">Version 2006: June 05</span></span>
<span data-ttu-id="084fc-697">*Версия 2006 (сборка 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-697">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-699">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-699">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-700">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-700">Excel</span></span>

- <span data-ttu-id="084fc-701">**Сортировка и фильтрация при совместной работе в Excel.** Теперь вы можете выполнять сортировку и фильтрацию в файле Excel при совместной работе с другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="084fc-701">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="084fc-702">Благодаря этой новой функции вам не будет мешать выполняемая другими пользователями сортировка и фильтрация при совместной работе с документом.</span><span class="sxs-lookup"><span data-stu-id="084fc-702">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="084fc-703">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="084fc-703">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="084fc-704">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="084fc-704">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="084fc-705">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="084fc-705">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="084fc-706">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-706">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="084fc-707">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-707">Outlook</span></span>

- <span data-ttu-id="084fc-708">**Быстрое повторное открытие элементов из предыдущего сеанса.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-708">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="084fc-709">После нормального или аварийного завершения работы Outlook при повторном открытии приложения можно быстро перезапустить его элементы.</span><span class="sxs-lookup"><span data-stu-id="084fc-709">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="084fc-710">По умолчанию эта функция включена.</span><span class="sxs-lookup"><span data-stu-id="084fc-710">This feature is on by default.</span></span> <span data-ttu-id="084fc-711">Чтобы ее отключить, выберите "Параметры > Общие > Параметры запуска".</span><span class="sxs-lookup"><span data-stu-id="084fc-711">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-714">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-714">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-715">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-715">Excel</span></span>

- <span data-ttu-id="084fc-716">Исправлена проблема с неправильным применением пользовательских значений в осях на схемах.</span><span class="sxs-lookup"><span data-stu-id="084fc-716">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="084fc-717">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="084fc-717">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-718">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-718">Outlook</span></span>

- <span data-ttu-id="084fc-719">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="084fc-719">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="084fc-720">Исправлена проблема, из-за которой возникал сбой при просмотре шаблона во время создания нового сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="084fc-720">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="084fc-721">Исправлена проблема, из-за которой пользователи не могли использовать общедоступные папки Exchange 2010 после Outlook версии 1911.</span><span class="sxs-lookup"><span data-stu-id="084fc-721">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="084fc-722">Исправлена проблема с отключенной кнопкой "Выбрать категорию" в календаре группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-722">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="084fc-723">Исправлена проблема со сбоями в работе Outlook при наличии конфликтов в контактах.</span><span class="sxs-lookup"><span data-stu-id="084fc-723">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="084fc-724">Исправлена проблема с отсутствием раскрывающегося списка Online Archive в свойствах папки у пользователей с мониторами высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="084fc-724">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="084fc-725">Исправлена проблема, из-за которой в работе Outlook возникал сбой при использовании гиперссылок в электронных сообщениях в формате обычного текста.</span><span class="sxs-lookup"><span data-stu-id="084fc-725">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="084fc-726">Исправлена проблема, приводившая к неспособности Outlook анализировать длинные имена файлов, закодированные с помощью RFC2231.</span><span class="sxs-lookup"><span data-stu-id="084fc-726">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="084fc-727">Исправлена проблема периодических зависаний в Outlook при использовании средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="084fc-727">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-728">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-728">PowerPoint</span></span>

- <span data-ttu-id="084fc-729">Исправлена проблема с открытием файлов с сервера, на котором настроена проверка подлинности на основе форм.</span><span class="sxs-lookup"><span data-stu-id="084fc-729">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="084fc-730">Исправлена проблема, приводившая к ошибкам при сохранении файлов PowerPoint с внедренными диаграммами и книгами.</span><span class="sxs-lookup"><span data-stu-id="084fc-730">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="084fc-731">Исправлена проблема, при которой закрытая пользователем область примечаний автоматически открывалась снова.</span><span class="sxs-lookup"><span data-stu-id="084fc-731">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="084fc-732">Исправлена проблема, из-за которой редактор слайдов одного слайда перекрывал следующий слайд.</span><span class="sxs-lookup"><span data-stu-id="084fc-732">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-733">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-733">Project</span></span>

- <span data-ttu-id="084fc-734">Исправлена проблема, препятствовавшая удалению или переназначению задач, утративших связи после удаления родительского плана.</span><span class="sxs-lookup"><span data-stu-id="084fc-734">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-735">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-735">Word</span></span>

- <span data-ttu-id="084fc-736">Исправлена проблема несоответствия метки времени в панелях примечаний установленному в системе местному времени.</span><span class="sxs-lookup"><span data-stu-id="084fc-736">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="084fc-737">Исправлена проблема с отсутствием синхронизации примечаний между веб-приложением и классическим приложением.</span><span class="sxs-lookup"><span data-stu-id="084fc-737">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2006-may-29"></a><span data-ttu-id="084fc-739">Версия 2006: 29 мая</span><span class="sxs-lookup"><span data-stu-id="084fc-739">Version 2006: May 29</span></span>
<span data-ttu-id="084fc-740">*Версия 2006 (сборка 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-740">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="084fc-741">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-741">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-742">Outlook</span></span>

- <span data-ttu-id="084fc-743">**Добавлены кнопки во всплывающие уведомления Outlook.** При использовании Outlook в Windows 10 кнопки быстрых действий теперь отображаются во всплывающих уведомлениях Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-743">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-744">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-744">PowerPoint</span></span>

- <span data-ttu-id="084fc-745">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="084fc-745">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="084fc-746">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="084fc-746">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-749">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-749">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-750">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-750">Excel</span></span>

- <span data-ttu-id="084fc-751">Исправлена проблема, из-за которой Excel иногда завершал работу при взаимодействии с OneDrive.</span><span class="sxs-lookup"><span data-stu-id="084fc-751">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="084fc-752">Исправлена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="084fc-752">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="084fc-753">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="084fc-753">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="084fc-754">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="084fc-754">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-755">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-755">PowerPoint</span></span>

- <span data-ttu-id="084fc-756">Исправлена проблема, из-за которой слайды не располагались по центру после изменения масштаба с помощью колесика мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-756">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-757">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-757">Word</span></span>

- <span data-ttu-id="084fc-758">Исправлена проблема, из-за которой не отображался текст, скопированный и вставленный в область примечаний.</span><span class="sxs-lookup"><span data-stu-id="084fc-758">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="084fc-759">Исправлена проблема, из-за которой выноска маркера примечания казалась размытой при масштабе 100 %.</span><span class="sxs-lookup"><span data-stu-id="084fc-759">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="084fc-760">Исправлена проблема, из-за которой включение политики "Двоичные документы и шаблоны Word 2007 и более поздних версий" вызывало сбой в некоторых случаях совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="084fc-760">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="084fc-761">Исправлена проблема, из-за которой файлы с длинными именами путей (больше 32 КБ) не открывались, а соответствующее сообщение об ошибке не отображалось.</span><span class="sxs-lookup"><span data-stu-id="084fc-761">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2006-may-22"></a><span data-ttu-id="084fc-763">Версия 2006: 22 мая</span><span class="sxs-lookup"><span data-stu-id="084fc-763">Version 2006: May 22</span></span>
<span data-ttu-id="084fc-764">*Версия 2006 (сборка 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-764">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-766">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-766">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-767">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-767">Excel</span></span>

- <span data-ttu-id="084fc-768">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-768">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="084fc-769">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-769">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="084fc-770">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="084fc-770">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="084fc-771">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-771">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="084fc-772">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="084fc-772">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-773">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-773">PowerPoint</span></span>

- <span data-ttu-id="084fc-774">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-774">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="084fc-775">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-775">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="084fc-776">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="084fc-776">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="084fc-777">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-777">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="084fc-778">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="084fc-778">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="084fc-779">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-779">Word</span></span>

- <span data-ttu-id="084fc-780">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-780">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="084fc-781">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-781">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="084fc-782">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="084fc-782">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="084fc-783">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-783">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="084fc-784">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="084fc-784">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-787">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-787">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-788">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-788">Excel</span></span>

- <span data-ttu-id="084fc-789">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, так что закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="084fc-789">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="084fc-790">Исправлена проблема, из-за которой повреждалась память при управлении шрифтами между Excel и некоторыми сторонними приложениями специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="084fc-790">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="084fc-791">Исправлена проблема, из-за которой в Excel возникал сбой, когда надстройки запрашивали элементы хоста на листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="084fc-791">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-792">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-792">Outlook</span></span>

- <span data-ttu-id="084fc-793">Исправлена проблема, из-за которой событие Folder.BeforeItemMove срабатывало неправильно, когда пользователь перемещал элементы между папками.</span><span class="sxs-lookup"><span data-stu-id="084fc-793">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="084fc-794">Исправлена проблема, из-за которой элементы календаря, переходящие за полночь, отображались как события на весь день.</span><span class="sxs-lookup"><span data-stu-id="084fc-794">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="084fc-795">Исправлена проблема, из-за которой в Outlook возникал сбой, когда две надстройки добавляли кнопку в одну группу на ленте.</span><span class="sxs-lookup"><span data-stu-id="084fc-795">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="084fc-796">Исправлена проблема, из-за которой пользователи не могли поделиться календарем с гостевым пользователем.</span><span class="sxs-lookup"><span data-stu-id="084fc-796">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-797">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-797">PowerPoint</span></span>

- <span data-ttu-id="084fc-798">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-798">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-799">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-799">Project</span></span>

- <span data-ttu-id="084fc-800">Исправлена проблема, из-за которой Project аварийно завершал работу после нажатия кнопки "Параметры".</span><span class="sxs-lookup"><span data-stu-id="084fc-800">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-801">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-801">Word</span></span>

- <span data-ttu-id="084fc-802">Исправлена проблема, из-за которой гиперссылки в примечаниях не работали.</span><span class="sxs-lookup"><span data-stu-id="084fc-802">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="084fc-803">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-803">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="084fc-804">Исправлена проблема, из-за которой не работала вставка HTML в WordMail для календаря.</span><span class="sxs-lookup"><span data-stu-id="084fc-804">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="084fc-805">Исправлена проблема, из-за которой ответ на примечание в сеансе совместного редактирования иногда приводил к зависанию Word.</span><span class="sxs-lookup"><span data-stu-id="084fc-805">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-may-15"></a><span data-ttu-id="084fc-807">Версия 2006: 15 мая</span><span class="sxs-lookup"><span data-stu-id="084fc-807">Version 2006: May 15</span></span>
<span data-ttu-id="084fc-808">*Версия 2006 (сборка 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-808">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-810">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-810">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-811">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-811">Excel</span></span>

- <span data-ttu-id="084fc-812">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="084fc-812">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="084fc-813">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-813">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="084fc-814">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-814">Outlook</span></span>

- <span data-ttu-id="084fc-815">**Поиск именно того, что нужно.** Сужайте область поиска с помощью таких параметров, как "папка", "отправитель", "дата", "сведения о вложении" и т.д.</span><span class="sxs-lookup"><span data-stu-id="084fc-815">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-816">PowerPoint</span></span>

- <span data-ttu-id="084fc-817">**Переключатель не нужен: наушники вам в помощь.** Используйте наушники Surface для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-817">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="084fc-818">Важно! Чтобы использовать жесты для управления презентациями, необходимо связать наушники Surface с приложением Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="084fc-818">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="084fc-819">Инструкции о начале работы с приложением Surface Audio на Windows 10 находятся здесь.</span><span class="sxs-lookup"><span data-stu-id="084fc-819">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="084fc-820">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-820">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="084fc-821">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-821">Word</span></span>

- <span data-ttu-id="084fc-822">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="084fc-822">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-825">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-825">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-826">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-826">Excel</span></span>
- <span data-ttu-id="084fc-827">Исправлена проблема, из-за которой увеличивалось время производительности для пользователей при удалении ими объединенных столбцов. </span><span class="sxs-lookup"><span data-stu-id="084fc-827">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="084fc-828">Исправлена проблема, из-за которой в списке доступных принтеров имена принтеров повторялись.</span><span class="sxs-lookup"><span data-stu-id="084fc-828">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="084fc-829">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-829">PowerPoint</span></span>
- <span data-ttu-id="084fc-830">Исправлена проблема, из-за которой сочетания клавиш и средства проверки орфографии не работают должным образом при использовании клавиатуры на английском языке для Швейцарии (QWERTZ).</span><span class="sxs-lookup"><span data-stu-id="084fc-830">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-831">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-831">Word</span></span>
- <span data-ttu-id="084fc-832">Исправлена проблема, из-за которой при добавлении нового примечания в пустой документ ничего не происходит.</span><span class="sxs-lookup"><span data-stu-id="084fc-832">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="084fc-833">Исправлена проблема, из-за которой вставка или обновление индекса в документе, содержащем более сотни элементов, приводит к сбою работы приложения.</span><span class="sxs-lookup"><span data-stu-id="084fc-833">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="084fc-834">Исправлена проблема, из-за которой файлы, в которых есть настраиваемые значения, открывались очень медленно.</span><span class="sxs-lookup"><span data-stu-id="084fc-834">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-835">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-835">Office Suite</span></span>
- <span data-ttu-id="084fc-836">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="084fc-836">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-may-08"></a><span data-ttu-id="084fc-839">Версия 2006: 8 мая</span><span class="sxs-lookup"><span data-stu-id="084fc-839">Version 2006: May 08</span></span>
<span data-ttu-id="084fc-840">*Версия 2006 (сборка 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-840">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-842">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-842">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-843">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-843">Excel</span></span>

- <span data-ttu-id="084fc-844">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="084fc-844">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-845">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-845">Outlook</span></span>

- <span data-ttu-id="084fc-846">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="084fc-846">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="084fc-847">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-847">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="084fc-848">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="084fc-848">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-849">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-849">PowerPoint</span></span>

- <span data-ttu-id="084fc-850">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="084fc-850">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="084fc-851">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-851">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="084fc-852">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-852">Word</span></span>

- <span data-ttu-id="084fc-853">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="084fc-853">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-856">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-856">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="084fc-857">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-857">Office Suite</span></span>

- <span data-ttu-id="084fc-858">Мы изучили и устранили проблему, из-за которой развертывание Office 365 профессиональный плюс с помощью InTune было приостановлено после завершения работы ОС.</span><span class="sxs-lookup"><span data-stu-id="084fc-858">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-01"></a><span data-ttu-id="084fc-860">Версия 2005: 1 мая</span><span class="sxs-lookup"><span data-stu-id="084fc-860">Version 2005: May 01</span></span>
<span data-ttu-id="084fc-861">*Версия 2005 (сборка 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="084fc-861">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-863">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-863">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-864">Outlook</span></span>

- <span data-ttu-id="084fc-865">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-865">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="084fc-866">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="084fc-866">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="084fc-867">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-867">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-870">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-870">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-871">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-871">Excel</span></span>

- <span data-ttu-id="084fc-872">Исправлена проблема, из-за которой в таблице данных диаграммы неправильно отображались значения оси дат.</span><span class="sxs-lookup"><span data-stu-id="084fc-872">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="084fc-873">Исправлена проблема, из-за которой разрывы страниц не удавалось отключить после перехода в режим макета страницы или страничный режим.</span><span class="sxs-lookup"><span data-stu-id="084fc-873">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="084fc-874">Исправлена проблема, из-за которой стили линий диаграммы могли пропадать после скрытия и повторного отображения столбцов с рядами данных.</span><span class="sxs-lookup"><span data-stu-id="084fc-874">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="084fc-875">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="084fc-875">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="084fc-876">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="084fc-876">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="084fc-877">Исправлена проблема, из-за которой пользовательское форматирование в сводных диаграммах не сохранялось при включенном параметре "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="084fc-877">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="084fc-878">Исправлена проблема, из-за которой пользовательское форматирование одной точки данных в сводной диаграмме не сохранялось, если был выбран параметр "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="084fc-878">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="084fc-879">Это исправление устраняет проблему, из-за которой символ "@", отправленный в CSV-файл, приводил к преобразованию строки после символа "@" в формулу.</span><span class="sxs-lookup"><span data-stu-id="084fc-879">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="084fc-880">Исправлена проблема, из-за которой десятичные значения в функции ПОСЛЕДОВ округлялись неправильно.</span><span class="sxs-lookup"><span data-stu-id="084fc-880">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-881">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-881">Outlook</span></span>

- <span data-ttu-id="084fc-882">Исправлена проблема, приводившая к сбою загрузки очень длинных безопасных ссылок (из-за усечения), при переходе по ним в классическом клиенте Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-882">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="084fc-883">Исправлена проблема, из-за которой папки Outlook с именами, содержащими двухбайтовые знаки (DBCS), периодически исчезали при синхронизации с сервером.</span><span class="sxs-lookup"><span data-stu-id="084fc-883">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="084fc-884">Чтобы это происходило, Outlook должен быть настроен с использованием учетной записи IMAP и работать в системе, языком которой выбран японский.</span><span class="sxs-lookup"><span data-stu-id="084fc-884">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-885">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-885">PowerPoint</span></span>

- <span data-ttu-id="084fc-886">Исправлена следующая проблема: если пользователь создавал комментарий, не публикуя его, и закрывал область комментариев, затем открывал новое окно, просматривал несколько слайдов, закрывал окно и повторно открывал область комментариев в исходной презентации, черновик комментария был недоступен.</span><span class="sxs-lookup"><span data-stu-id="084fc-886">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-887">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-887">Project</span></span>

- <span data-ttu-id="084fc-888">Исправлена проблема, из-за которой при подключении Project к Project Web App и использовании запятой в качестве десятичного разделителя метод добавления объектов TaskDependencies завершался сбоем, если добавлен параметр Lag.</span><span class="sxs-lookup"><span data-stu-id="084fc-888">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-889">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-889">Word</span></span>

- <span data-ttu-id="084fc-890">Исправлена проблема, из-за которой иногда не удавалось вставить комментарии в документ в режиме совместной работы.</span><span class="sxs-lookup"><span data-stu-id="084fc-890">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="084fc-891">Это изменение исправляет ошибку, из-за которой карточка "Люди" мерцала при щелчке по @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="084fc-891">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="084fc-892">Исправлена следующая проблема: пользователю, закрывавшему документ с черновиком комментариев, предлагалось подтвердить закрытие без сохранения черновика комментариев,</span><span class="sxs-lookup"><span data-stu-id="084fc-892">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="084fc-893">и при отмене запроса документ закрывался, а не оставался открытым.</span><span class="sxs-lookup"><span data-stu-id="084fc-893">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="084fc-894">Исправлена проблема, из-за которой при переводе опубликованного комментария возникала ошибка "Сбой вставки переведенного текста".</span><span class="sxs-lookup"><span data-stu-id="084fc-894">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="084fc-895">В веб-представлении или иммерсивном средстве чтения щелчок по подсказке приводил к прокручиванию в верхнюю часть представления, хотя она уже была просмотрена.</span><span class="sxs-lookup"><span data-stu-id="084fc-895">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="084fc-896">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="084fc-896">This has been fixed.</span></span>
- <span data-ttu-id="084fc-897">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="084fc-897">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2005-april-24"></a><span data-ttu-id="084fc-899">Версия 2005: 24 апреля</span><span class="sxs-lookup"><span data-stu-id="084fc-899">Version 2005: April 24</span></span>
<span data-ttu-id="084fc-900">*Версия 2005 (сборка 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="084fc-900">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-902">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-902">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-903">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-903">Excel</span></span>
- <span data-ttu-id="084fc-904">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="084fc-904">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="084fc-905">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="084fc-905">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-906">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-906">Outlook</span></span>
- <span data-ttu-id="084fc-907">Устранена проблема, из-за которой была отключена кнопка "Классифицировать" для календарей группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="084fc-907">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="084fc-908">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="084fc-908">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-909">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-909">PowerPoint</span></span>
- <span data-ttu-id="084fc-910">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="084fc-910">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-911">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-911">Word</span></span>
- <span data-ttu-id="084fc-912">При включении параметра "Показывать закладки" закладки не отображались.</span><span class="sxs-lookup"><span data-stu-id="084fc-912">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="084fc-913">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="084fc-913">This has been fixed.</span></span>
- <span data-ttu-id="084fc-914">Это изменение устраняет проблему, из-за которой при включении параметра "Показывать коды полей вместо их значений" текст с гиперссылками может не отображаться.</span><span class="sxs-lookup"><span data-stu-id="084fc-914">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2005-april-17"></a><span data-ttu-id="084fc-916">Версия 2005: 17 апреля</span><span class="sxs-lookup"><span data-stu-id="084fc-916">Version 2005: April 17</span></span>
<span data-ttu-id="084fc-917">*Версия 2005 (сборка 12810,20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-917">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-919">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-919">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-920">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-920">Excel</span></span>
- <span data-ttu-id="084fc-921">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="084fc-921">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="084fc-922">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="084fc-922">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="084fc-923">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="084fc-923">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="084fc-924">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="084fc-924">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="084fc-925">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="084fc-925">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="084fc-926">OneNote</span><span class="sxs-lookup"><span data-stu-id="084fc-926">OneNote</span></span>
- <span data-ttu-id="084fc-927">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="084fc-927">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-928">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-928">Outlook</span></span>
- <span data-ttu-id="084fc-929">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="084fc-929">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="084fc-930">Решает проблему, из-за которой собрания, для которых прошло более 2 месяцев, не отображали тему собрания в Помощнике по планированию.</span><span class="sxs-lookup"><span data-stu-id="084fc-930">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="084fc-931">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="084fc-931">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="084fc-932">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="084fc-932">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="084fc-933">Решена проблема, из-за которой правила удаления, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, стали недействительными.</span><span class="sxs-lookup"><span data-stu-id="084fc-933">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="084fc-934">Решает проблему, которая приводила к удалению вложений при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="084fc-934">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-935">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-935">Project</span></span>
- <span data-ttu-id="084fc-936">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="084fc-936">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="084fc-937">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-937">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="084fc-938">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="084fc-938">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2004-april-10"></a><span data-ttu-id="084fc-940">Версия 2004: 10 апреля</span><span class="sxs-lookup"><span data-stu-id="084fc-940">Version 2004: April 10</span></span>
<span data-ttu-id="084fc-941">*Версия 2004 (сборка 12730,20024)*</span><span class="sxs-lookup"><span data-stu-id="084fc-941">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-943">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-943">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="084fc-944">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-944">Access</span></span>

- <span data-ttu-id="084fc-945">**Пропустите диалоговое окно «Показать таблицу», перейдите непосредственно к панели задач и упростите добавление таблиц к отношениям и запросам.:** Добавьте таблицы и запросы, щелкнув четыре вкладки, выбрав несколько имен, выполнив поиск по тексту и перетащив из области задач, которая остается открой пока ты работаешь.</span><span class="sxs-lookup"><span data-stu-id="084fc-945">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-946">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-946">Excel</span></span>

- <span data-ttu-id="084fc-947">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="084fc-947">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="084fc-948">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="084fc-948">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-949">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-949">Outlook</span></span>

- <span data-ttu-id="084fc-950">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="084fc-950">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="084fc-951">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="084fc-951">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="084fc-952">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="084fc-952">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-953">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-953">PowerPoint</span></span>

- <span data-ttu-id="084fc-954">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="084fc-954">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="084fc-955">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="084fc-955">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="084fc-956">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="084fc-956">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-957">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-957">Word</span></span>

- <span data-ttu-id="084fc-958">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="084fc-958">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="084fc-959">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="084fc-959">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="084fc-960">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="084fc-960">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="084fc-961">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="084fc-961">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-964">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-964">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-965">Доступ</span><span class="sxs-lookup"><span data-stu-id="084fc-965">Access</span></span>

- <span data-ttu-id="084fc-966">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="084fc-966">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-967">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-967">Excel</span></span>

- <span data-ttu-id="084fc-968">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="084fc-968">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="084fc-969">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="084fc-969">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="084fc-970">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="084fc-970">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="084fc-971">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="084fc-971">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="084fc-972">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="084fc-972">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-973">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-973">Outlook</span></span>

- <span data-ttu-id="084fc-974">Решает проблему, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="084fc-974">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="084fc-975">Решает проблему, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="084fc-975">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="084fc-976">Устраняет проблему, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="084fc-976">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="084fc-977">Решает проблему, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="084fc-977">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-978">PowerPoint</span></span>

- <span data-ttu-id="084fc-979">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="084fc-979">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="084fc-980">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="084fc-980">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="084fc-981">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="084fc-981">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-982">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-982">Project</span></span>

- <span data-ttu-id="084fc-983">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="084fc-983">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-984">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-984">Word</span></span>

- <span data-ttu-id="084fc-985">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="084fc-985">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="084fc-986">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="084fc-986">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="084fc-987">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="084fc-987">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="084fc-988">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="084fc-988">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="084fc-989">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="084fc-989">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-27"></a><span data-ttu-id="084fc-991">Версия 2004: 27 марта</span><span class="sxs-lookup"><span data-stu-id="084fc-991">Version 2004: March 27</span></span>
<span data-ttu-id="084fc-992">*Версия 2004 (сборка 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="084fc-992">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-994">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-994">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-995">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-995">Outlook</span></span>

- <span data-ttu-id="084fc-996">**Новый параметр, позволяющий отключить предложения для @упоминаний при создании сообщений.** Считаете ли вы средство выбора @упоминаний скорее раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="084fc-996">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="084fc-997">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="084fc-997">Now you can turn it off if you prefer.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1000">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1000">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-1001">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1001">Outlook</span></span>
- <span data-ttu-id="084fc-1002">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="084fc-1002">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="084fc-1003">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="084fc-1003">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="084fc-1004">Исправлена проблема, из-за которой пользователи не могли добавить дополнительные вложения из расположения в Интернете в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="084fc-1004">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-1005">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1005">PowerPoint</span></span>
- <span data-ttu-id="084fc-1006">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="084fc-1006">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-1007">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-1007">Project</span></span>
- <span data-ttu-id="084fc-1008">Исправлена проблема, из-за которой при выполнении "CustomFieldValueListGetItem" и отсутствии таблицы подстановки для настраиваемого поля создается пустая таблица подстановки, хотя этого быть не должно.</span><span class="sxs-lookup"><span data-stu-id="084fc-1008">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1009">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1009">Word</span></span>
- <span data-ttu-id="084fc-1010">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="084fc-1010">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-20"></a><span data-ttu-id="084fc-1012">Версия 2004: 20 марта</span><span class="sxs-lookup"><span data-stu-id="084fc-1012">Version 2004: March 20</span></span>
<span data-ttu-id="084fc-1013">*Версия 2004 (сборка 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1013">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-1015">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-1015">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-1016">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1016">Outlook</span></span>

- <span data-ttu-id="084fc-1017">**Обновление внешнего вида календаря.** В прошлом году мы обновили интерфейс почты, а сейчас пришло время улучшить внешний вид календаря!</span><span class="sxs-lookup"><span data-stu-id="084fc-1017">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="084fc-1018">Обновления придали интерфейсу свежести, но он остался вполне узнаваемым, поэтому вам, как опытному пользователю Outlook, будет легко освоить его на ходу и сразу повысить свою продуктивность.</span><span class="sxs-lookup"><span data-stu-id="084fc-1018">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="084fc-1019">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="084fc-1019">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-1020">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1020">PowerPoint</span></span>

- <span data-ttu-id="084fc-1021">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="084fc-1021">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1024">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1024">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-1025">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-1025">Excel</span></span>

- <span data-ttu-id="084fc-1026">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="084fc-1026">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-1027">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1027">Outlook</span></span>

- <span data-ttu-id="084fc-1028">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="084fc-1028">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="084fc-1029">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="084fc-1029">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="084fc-1030">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="084fc-1030">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="084fc-1031">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="084fc-1031">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="084fc-1032">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="084fc-1032">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-1033">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-1033">Project</span></span>

- <span data-ttu-id="084fc-1034">Исправлена проблема, из-за которой событие 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) при нажатии пользователем кнопки "Деактивировать" на ленте задач группировки "Планирование" не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="084fc-1034">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="084fc-1035">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="084fc-1035">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="084fc-1036">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="084fc-1036">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="084fc-1037">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="084fc-1037">This behavior has been fixed.</span></span>

- <span data-ttu-id="084fc-1038">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="084fc-1038">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="084fc-1039">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="084fc-1039">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="084fc-1040">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="084fc-1040">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="084fc-1041">Исправлена проблема, из-за которой при печати временной шкалы с использованием календаря Hijri в представлении для печати пропускался или дублировался месяц.</span><span class="sxs-lookup"><span data-stu-id="084fc-1041">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="084fc-1042">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="084fc-1042">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1043">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1043">Word</span></span>

- <span data-ttu-id="084fc-1044">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="084fc-1044">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="084fc-1045">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="084fc-1045">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="084fc-1046">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="084fc-1046">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="084fc-1047">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="084fc-1047">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="084fc-1048">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="084fc-1048">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-13"></a><span data-ttu-id="084fc-1050">Версия 2004: 13 марта</span><span class="sxs-lookup"><span data-stu-id="084fc-1050">Version 2004: March 13</span></span>
<span data-ttu-id="084fc-1051">*Версия 2004 (сборка 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1051">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-1053">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-1053">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-1054">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-1054">Excel</span></span>
- <span data-ttu-id="084fc-1055">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="084fc-1055">**Sensitivity labels** : You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="084fc-1056">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-1056">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="084fc-1057">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1057">PowerPoint</span></span>
- <span data-ttu-id="084fc-1058">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="084fc-1058">**Sensitivity labels** : You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="084fc-1059">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-1059">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="084fc-1060">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1060">Word</span></span>
- <span data-ttu-id="084fc-1061">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="084fc-1061">**Sensitivity labels** : You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="084fc-1062">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-1062">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1065">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1065">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="084fc-1066">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-1066">Access</span></span>
- <span data-ttu-id="084fc-1067">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="084fc-1067">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-1068">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-1068">Excel</span></span>
- <span data-ttu-id="084fc-1069">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="084fc-1069">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="084fc-1070">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="084fc-1070">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1071">Outlook</span></span>
- <span data-ttu-id="084fc-1072">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="084fc-1072">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="084fc-1073">Исправлена проблема, из-за которой не начинался поиск при нажатии клавиши ВВОД в развернутой области поиска, и требовалось вместо этого щелкать кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="084fc-1073">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="084fc-1074">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="084fc-1074">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="084fc-1075">Project</span><span class="sxs-lookup"><span data-stu-id="084fc-1075">Project</span></span>
- <span data-ttu-id="084fc-1076">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="084fc-1076">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="084fc-1077">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="084fc-1077">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1078">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1078">Word</span></span>
- <span data-ttu-id="084fc-1079">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="084fc-1079">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="084fc-1080">Исправлена проблема, из-за которой выравнивание слов в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="084fc-1080">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="084fc-1081">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="084fc-1081">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="084fc-1082">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="084fc-1082">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-06"></a><span data-ttu-id="084fc-1084">Версия 2003: 6 марта</span><span class="sxs-lookup"><span data-stu-id="084fc-1084">Version 2003: March 06</span></span>
<span data-ttu-id="084fc-1085">*Версия 2003 (сборка 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1085">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1087">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1087">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-1088">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1088">Outlook</span></span>

- <span data-ttu-id="084fc-1089">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не было сохранено на сервере Exchange Server и возник конфликт.</span><span class="sxs-lookup"><span data-stu-id="084fc-1089">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="084fc-1090">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="084fc-1090">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="084fc-1091">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="084fc-1091">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-1092">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1092">PowerPoint</span></span>

- <span data-ttu-id="084fc-1093">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-1093">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="084fc-1094">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-1094">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1095">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1095">Word</span></span>

- <span data-ttu-id="084fc-1096">Исправлена проблема с функцией сравнения для документов, защищенных для редактирования.</span><span class="sxs-lookup"><span data-stu-id="084fc-1096">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-1097">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-1097">Office Suite</span></span>

- <span data-ttu-id="084fc-1098">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-1098">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="084fc-1099">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="084fc-1099">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2003-february-28"></a><span data-ttu-id="084fc-1102">Версия 2003: 28 февраля</span><span class="sxs-lookup"><span data-stu-id="084fc-1102">Version 2003: February 28</span></span>
<span data-ttu-id="084fc-1103">*Версия 2003 (сборка 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1103">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-1105">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-1105">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-1106">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1106">Outlook</span></span>

- <span data-ttu-id="084fc-1107">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="084fc-1107">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="084fc-1108">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-1108">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="084fc-1109">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1109">PowerPoint</span></span>

- <span data-ttu-id="084fc-1110">**Улучшенный рукописный ввод для работы со схемами.** Создавайте отличные схемы и преобразуйте их в объекты Office, которыми можно управлять. [Подробнее](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="084fc-1110">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1113">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="084fc-1114">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-1114">Excel</span></span>

- <span data-ttu-id="084fc-1115">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="084fc-1115">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-1116">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1116">Outlook</span></span>

- <span data-ttu-id="084fc-1117">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="084fc-1117">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1118">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1118">Word</span></span>

- <span data-ttu-id="084fc-1119">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="084fc-1119">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="084fc-1120">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="084fc-1120">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="084fc-1121">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="084fc-1121">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-1122">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-1122">Office Suite</span></span>

- <span data-ttu-id="084fc-1123">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="084fc-1123">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-21"></a><span data-ttu-id="084fc-1125">Версия 2003: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="084fc-1125">Version 2003: February 21</span></span>
<span data-ttu-id="084fc-1126">*Версия 2003 (сборка 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1126">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-1128">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-1128">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="084fc-1129">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-1129">Office Suite</span></span>

- <span data-ttu-id="084fc-1130">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="084fc-1130">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1133">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1133">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-1134">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-1134">Excel</span></span>
- <span data-ttu-id="084fc-1135">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="084fc-1135">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="084fc-1136">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="084fc-1136">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="084fc-1137">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="084fc-1137">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="084fc-1138">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="084fc-1138">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="084fc-1139">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="084fc-1139">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1140">Outlook</span></span>
- <span data-ttu-id="084fc-1141">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="084fc-1141">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="084fc-1142">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="084fc-1142">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="084fc-1143">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="084fc-1143">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1144">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1144">Word</span></span>
- <span data-ttu-id="084fc-1145">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="084fc-1145">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="084fc-1146">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега.</span><span class="sxs-lookup"><span data-stu-id="084fc-1146">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="084fc-1147">Эта проблема исправлена.</span><span class="sxs-lookup"><span data-stu-id="084fc-1147">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-1148">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-1148">Office Suite</span></span>
- <span data-ttu-id="084fc-1149">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="084fc-1149">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="084fc-1150">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="084fc-1150">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="084fc-1151">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="084fc-1151">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-14"></a><span data-ttu-id="084fc-1153">Версия 2003: 14 февраля</span><span class="sxs-lookup"><span data-stu-id="084fc-1153">Version 2003: February 14</span></span>
<span data-ttu-id="084fc-1154">*Версия 2003 (сборка 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1154">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-1156">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-1156">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-1157">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1157">Outlook</span></span>

- <span data-ttu-id="084fc-1158">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="084fc-1158">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="084fc-1159">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="084fc-1159">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1160">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1160">Word</span></span>

- <span data-ttu-id="084fc-1161">**Правки от руки в инструментах рисования.** Нажмите "Рисование" и выберите перо Правки от руки, чтобы редактировать документ с помощью пальца или цифрового пера.</span><span class="sxs-lookup"><span data-stu-id="084fc-1161">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="084fc-1162">Подробнее</span><span class="sxs-lookup"><span data-stu-id="084fc-1162">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="084fc-1163">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-1163">Office Suite</span></span>

- <span data-ttu-id="084fc-1164">**Более понятные значки строки состояния.** Значки строки состояния стали понятнее</span><span class="sxs-lookup"><span data-stu-id="084fc-1164">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1167">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1167">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="084fc-1168">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1168">Outlook</span></span>

- <span data-ttu-id="084fc-1169">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря "Параметры доступности".</span><span class="sxs-lookup"><span data-stu-id="084fc-1169">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="084fc-1170">Исправлена проблема, которая могла привести к появлению оповещения "К сожалению, не удалось открыть элемент" при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="084fc-1170">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="084fc-1171">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="084fc-1171">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="084fc-1172">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="084fc-1172">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-1173">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1173">PowerPoint</span></span>

- <span data-ttu-id="084fc-1174">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="084fc-1174">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1175">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1175">Word</span></span>

- <span data-ttu-id="084fc-1176">Исправлена проблема, из-за которой изображения в документах теряли прозрачность при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="084fc-1176">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-07"></a><span data-ttu-id="084fc-1178">Версия 2002: 7 февраля</span><span class="sxs-lookup"><span data-stu-id="084fc-1178">Version 2002: February 07</span></span>
<span data-ttu-id="084fc-1179">*Версия 2002 (сборка 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="084fc-1179">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="084fc-1181">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="084fc-1181">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="084fc-1182">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-1182">Access</span></span>

- <span data-ttu-id="084fc-1183">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="084fc-1183">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="084fc-1184">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="084fc-1184">Search and replace text in SQL View.</span></span> <span data-ttu-id="084fc-1185">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="084fc-1185">Select multiple tables in the Relationships window.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="084fc-1188">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="084fc-1188">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="084fc-1189">Access</span><span class="sxs-lookup"><span data-stu-id="084fc-1189">Access</span></span>

- <span data-ttu-id="084fc-1190">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="084fc-1190">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="084fc-1191">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="084fc-1191">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="084fc-1192">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="084fc-1192">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="084fc-1193">Excel</span><span class="sxs-lookup"><span data-stu-id="084fc-1193">Excel</span></span>

- <span data-ttu-id="084fc-1194">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="084fc-1194">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="084fc-1195">Outlook</span><span class="sxs-lookup"><span data-stu-id="084fc-1195">Outlook</span></span>

- <span data-ttu-id="084fc-1196">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="084fc-1196">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="084fc-1197">Решена проблема, приводившая к сбоям при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="084fc-1197">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="084fc-1198">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="084fc-1198">PowerPoint</span></span>

- <span data-ttu-id="084fc-1199">Исправлена проблема, из-за которой после закрытия файла приложение PowerPoint не удаляет его сразу из коллекции презентаций, если запущены обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="084fc-1199">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="084fc-1200">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="084fc-1200">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="084fc-1201">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="084fc-1201">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="084fc-1202">Word</span><span class="sxs-lookup"><span data-stu-id="084fc-1202">Word</span></span>

- <span data-ttu-id="084fc-1203">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="084fc-1203">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="084fc-1204">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="084fc-1204">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="084fc-1205">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="084fc-1205">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="084fc-1206">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="084fc-1206">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="084fc-1207">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="084fc-1207">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="084fc-1208">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="084fc-1208">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="084fc-1209">Набор Office</span><span class="sxs-lookup"><span data-stu-id="084fc-1209">Office Suite</span></span>

- <span data-ttu-id="084fc-1210">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="084fc-1210">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|DevMain|Insiders| |16.0.13510.20004|version-2012-november-13|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13430.20000|version-2012-november-06|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13426.20004|version-2011-october-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13415.20002|version-2011-october-23|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13408.20000|version-2011-october-16|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13406.20000|version-2011-october-09|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13328.20000|version-2010-october-02|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13318.20000|version-2010-september-25|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13312.20006|version-2010-september-18|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13304.20000|version-2010-september-11|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
