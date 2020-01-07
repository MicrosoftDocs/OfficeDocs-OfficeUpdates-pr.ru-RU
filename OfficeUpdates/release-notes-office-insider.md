---
title: Заметки о выпуске для участников программы предварительной оценки Office
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с ранним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: b136c43128f6f995057f35c7b47c9e517c457097
ms.sourcegitcommit: 78fb0c27e6b75aefcfcbd1b0ac7d17c1b53f86e0
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/07/2020
ms.locfileid: "40951097"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="7467d-103">Заметки о выпуске для участников программы предварительной оценки Office</span><span class="sxs-lookup"><span data-stu-id="7467d-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="7467d-104">Эта статья содержит заметки о выпуске для сборок приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows, предоставляемых в рамках программы предварительной оценки.</span><span class="sxs-lookup"><span data-stu-id="7467d-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="7467d-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="7467d-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="7467d-106">Обратите внимание на то, что развертывание возможностей (а иногда даже исправлений) для участников программы предварительной оценки зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="7467d-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="7467d-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="7467d-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="7467d-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="7467d-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="7467d-109">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок.</span><span class="sxs-lookup"><span data-stu-id="7467d-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="7467d-110">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="7467d-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="7467d-111">Microsoft Teams для существующих установок Office 365 профессиональный плюс — с конца июня Microsoft Teams будет добавляться в существующие установки Office 365 профессиональный плюс (и Office 365 бизнес) при обновлении этих установок.</span><span class="sxs-lookup"><span data-stu-id="7467d-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="7467d-112">Дата добавления приложения Teams зависит от используемого канала обновления.</span><span class="sxs-lookup"><span data-stu-id="7467d-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="7467d-113">Дополнительные сведения см. в статье [Развертывание Microsoft Teams с Office 365 профессиональный плюс](https://docs.microsoft.com/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="7467d-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

## <a name="version-2001-january-03"></a><span data-ttu-id="7467d-115">Версия 2001: 3 января</span><span class="sxs-lookup"><span data-stu-id="7467d-115">Version 2001: January 03</span></span>
<span data-ttu-id="7467d-116">*Версия 2001 (сборка 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-116">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-118">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-118">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-119">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-119">Excel</span></span>
- <span data-ttu-id="7467d-120">Некоторые линии границ могут печататься неправильно на бумаге размера A4.</span><span class="sxs-lookup"><span data-stu-id="7467d-120">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="7467d-121">Добавление изображения в колонтитул объекта диаграммы на листе с помощью VBA может приводить к ошибке.</span><span class="sxs-lookup"><span data-stu-id="7467d-121">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="7467d-122">При форматировании оси диаграммы интервал между надписями ограничивался значением 255.</span><span class="sxs-lookup"><span data-stu-id="7467d-122">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="7467d-123">Исправлена проблема, из-за которой возникала ошибка при попытке обновить XML-запрос, в котором URL-адрес источника данных был усечен.</span><span class="sxs-lookup"><span data-stu-id="7467d-123">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="7467d-124">В статистике книги указывалось число макросов из всех открытых книг, включая личную книгу макросов.</span><span class="sxs-lookup"><span data-stu-id="7467d-124">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-125">Outlook</span></span>
- <span data-ttu-id="7467d-126">Переключение между папками могло приводить к кратковременному белому "мерцанию" в списке почты или при предварительном просмотре почты.</span><span class="sxs-lookup"><span data-stu-id="7467d-126">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="7467d-127">Это поведение было более заметным в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="7467d-127">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-128">PowerPoint</span></span>
- <span data-ttu-id="7467d-129">Исправлена проблема с объектной моделью, из-за которой вызов метода Shape.Paste приводил к перемещению фокуса на вставленную фигуру.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="7467d-129">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="7467d-130">Улучшен сценарий копирования со вставкой.&nbsp;Цикл программного копирования фигуры из слайда PowerPoint и ее вставка на другой слайд мог завершаться сбоем с ошибкой исключения.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="7467d-130">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="7467d-131">Анимация в заголовках разделов слайдов отображалась неправильно после свертывания и развертывания заголовков разделов.</span><span class="sxs-lookup"><span data-stu-id="7467d-131">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="7467d-132">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-132">Project</span></span>
- <span data-ttu-id="7467d-133">Исправлена проблема с неработающим обтеканием текстом в представлениях задач и использования ресурсов.</span><span class="sxs-lookup"><span data-stu-id="7467d-133">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="7467d-134">Исправлена проблема, из-за которой при наличии у ресурса нескольких норм затрат значение затрат в назначениях могло быть неверным.</span><span class="sxs-lookup"><span data-stu-id="7467d-134">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-135">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-135">Word</span></span>
- <span data-ttu-id="7467d-136">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводила к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="7467d-136">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="7467d-137">При совместном редактировании примечание, добавленное с помощью Word Online, могло не отображаться в классической версии Word.</span><span class="sxs-lookup"><span data-stu-id="7467d-137">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-138">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-138">Office Suite</span></span>
- <span data-ttu-id="7467d-139">Удалено отображение неверной даты окончания действующей лицензии при попытке сменить единственную лицензию.</span><span class="sxs-lookup"><span data-stu-id="7467d-139">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-december-13"></a><span data-ttu-id="7467d-141">Версия 2001: 13 декабря</span><span class="sxs-lookup"><span data-stu-id="7467d-141">Version 2001: December 13</span></span>
<span data-ttu-id="7467d-142">*Версия 2001 (сборка 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-142">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-144">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-144">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7467d-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-145">Outlook</span></span>

- <span data-ttu-id="7467d-146">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="7467d-146">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="7467d-147">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="7467d-147">Messages you drag will be shared with all group members.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-150">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-150">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7467d-151">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-151">Access</span></span>
- <span data-ttu-id="7467d-152">Выполнение запроса на объединение, который ссылается на связанные таблицы ODBC и содержит предложение Order By, приводит к сбою 64-разрядной версии Access.</span><span class="sxs-lookup"><span data-stu-id="7467d-152">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="7467d-153">Суммирование данных из запросов на объединение в Access (O365) может приводить к усечению десятичных данных.</span><span class="sxs-lookup"><span data-stu-id="7467d-153">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="7467d-154">Интерфейсы COM для ACE не предоставляются для использования вне приложений Office.</span><span class="sxs-lookup"><span data-stu-id="7467d-154">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-155">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-155">Excel</span></span>
- <span data-ttu-id="7467d-156">Вставка трехмерной модели (анимированной или статической) и попытка сохранить файл как рисунок не работает.</span><span class="sxs-lookup"><span data-stu-id="7467d-156">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="7467d-157">Сочетание клавиш (ALT+CTRL+7/8) для отправки отзыва из представления Backstage вступает в конфликт с клавиатурами AZERTY (ALT-GR+7/8).</span><span class="sxs-lookup"><span data-stu-id="7467d-157">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="7467d-158">Воздействие: пользователи не могут использовать некоторые символы, например '\'.</span><span class="sxs-lookup"><span data-stu-id="7467d-158">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-159">Outlook</span></span>
- <span data-ttu-id="7467d-160">Исправлена проблема, приводившая к отправке сообщения электронной почты на неправильный адрес получателя.</span><span class="sxs-lookup"><span data-stu-id="7467d-160">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="7467d-161">Исправлена проблема, из-за которой приложение Outlook неверно позволяло пользователям с доступом к почтовому ящику для &quot;чтения&quot; изменить прочтенное или непрочтенное состояние сообщения.</span><span class="sxs-lookup"><span data-stu-id="7467d-161">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="7467d-162">Отзыв сертификата безопасности на веб-сайте не воспроизводится службой поддержки продукта.</span><span class="sxs-lookup"><span data-stu-id="7467d-162">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="7467d-163">Чтобы устранить основную причину этой проблемы, требуется добавить ведение журнала.</span><span class="sxs-lookup"><span data-stu-id="7467d-163">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="7467d-164">Исправлена проблема, из-за которой для пользователей отображались сбои синхронизации.</span><span class="sxs-lookup"><span data-stu-id="7467d-164">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-165">PowerPoint</span></span>
- <span data-ttu-id="7467d-166">Вставка трехмерной модели (анимированной или статической) и попытка сохранить файл как рисунок не работает.</span><span class="sxs-lookup"><span data-stu-id="7467d-166">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="7467d-167">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-167">Project</span></span>
- <span data-ttu-id="7467d-168">Работа задачи не вычисляется в сводке для дочерних задач, запланированных вручную.</span><span class="sxs-lookup"><span data-stu-id="7467d-168">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="7467d-169">Код VBA Project, вызванный кнопкой ленты может не работать при попытке сохранить серверные проекты.</span><span class="sxs-lookup"><span data-stu-id="7467d-169">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="7467d-170">Если приложение Project не запущено, при открытии файлов Project из библиотеки документов SharePoint появляется сообщение об ошибке и файл не открывается.</span><span class="sxs-lookup"><span data-stu-id="7467d-170">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-171">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-171">Word</span></span>
- <span data-ttu-id="7467d-172">Сохранение существующих файлов может не работать.</span><span class="sxs-lookup"><span data-stu-id="7467d-172">Saving existing files may not work.</span></span>
- <span data-ttu-id="7467d-173">Использование клавиш со стрелками в окне редактора правописания может приводить к периодическому мерцанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-173">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="7467d-174">При разрешении элементов к исполнению связанные примечания могут не преобразовываться в примечания пунктов.</span><span class="sxs-lookup"><span data-stu-id="7467d-174">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="7467d-175">Вставка трехмерной модели (анимированной или статической) и попытка сохранить файл как рисунок не работает.</span><span class="sxs-lookup"><span data-stu-id="7467d-175">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-176">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-176">Office Suite</span></span>
- <span data-ttu-id="7467d-177">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="7467d-177">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="7467d-178">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="7467d-178">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-december-06"></a><span data-ttu-id="7467d-180">Версия 1912: 6 декабря</span><span class="sxs-lookup"><span data-stu-id="7467d-180">Version 1912: December 06</span></span>
<span data-ttu-id="7467d-181">*Версия 1912 (сборка 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="7467d-181">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-183">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-183">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7467d-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-184">Outlook</span></span>

- <span data-ttu-id="7467d-185">**Дополнительные параметры электронной почты группы.** Эта функция позволяет группам пользователей настраивать сообщения или события, получаемые и отслеживаемые в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="7467d-185">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="7467d-186">**Политика именования групп.** Политика именования групп позволяет ИТ-администратору стандартизировать имена групп, созданных пользователями в организации, а также управлять ими.</span><span class="sxs-lookup"><span data-stu-id="7467d-186">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="7467d-187">Администратор может требовать добавления специального префикса и суффикса к имени группы при ее создании и может запретить использование определенных слов.</span><span class="sxs-lookup"><span data-stu-id="7467d-187">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="7467d-188">Это позволяет уменьшить использование недопустимых слов в названиях групп, а также управлять отображением групп в каталоге.</span><span class="sxs-lookup"><span data-stu-id="7467d-188">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="7467d-189">Политика именования также помогает организациям развертывать сайты групп для их классификации по отделам.</span><span class="sxs-lookup"><span data-stu-id="7467d-189">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-190">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-190">Office Suite</span></span>

- <span data-ttu-id="7467d-191">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="7467d-191">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="7467d-192">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="7467d-192">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-195">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-195">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-196">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-196">Excel</span></span>
- <span data-ttu-id="7467d-197">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="7467d-197">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="7467d-198">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="7467d-198">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="7467d-199">Отключение аппаратного ускорения графики при использовании разрешения 4K может приводить к задержке отображения ячеек при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="7467d-199">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="7467d-200">При удалении длинной формулы, пересекающей границу ячейки, она по-прежнему может отображаться за границей ячейки.</span><span class="sxs-lookup"><span data-stu-id="7467d-200">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="7467d-201">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="7467d-201">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="7467d-202">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="7467d-202">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="7467d-203">OneNote</span><span class="sxs-lookup"><span data-stu-id="7467d-203">OneNote</span></span>
- <span data-ttu-id="7467d-204">Приложение OneNote может не открываться при использовании надстройки "Заметки к собранию" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="7467d-204">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-205">Outlook</span></span>
- <span data-ttu-id="7467d-206">Метки политики хранения могут отображать срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="7467d-206">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="7467d-207">В карточках контактов может появляться пустое место при использовании японского языкового пакета.</span><span class="sxs-lookup"><span data-stu-id="7467d-207">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="7467d-208">Иногда изменяются размеры изображений, вставленных в сообщения электронной почты Outlook.</span><span class="sxs-lookup"><span data-stu-id="7467d-208">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-209">PowerPoint</span></span>
- <span data-ttu-id="7467d-210">Если на слайде пользователя в облачном файле имеется два (или более) видеоролика, видеоизображения отображаются правильно, но когда пользователь щелкает каждое из них для воспроизведения, видеоконтент оказывается одинаковым.</span><span class="sxs-lookup"><span data-stu-id="7467d-210">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="7467d-211">В некоторых случаях прокрутка на сенсорных устройствах не работает.</span><span class="sxs-lookup"><span data-stu-id="7467d-211">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="7467d-212">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="7467d-212">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="7467d-213">Безопасные ссылки, ведущие из одного приложения Office в другое, могут не запускать связанное приложение.</span><span class="sxs-lookup"><span data-stu-id="7467d-213">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="7467d-214">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-214">Project</span></span>
- <span data-ttu-id="7467d-215">Приложение Project может аварийно завершать работу при использовании функции сравнения проектов.</span><span class="sxs-lookup"><span data-stu-id="7467d-215">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="7467d-216">Если используется темный режим при переходе в панель инспектора в задаче, содержащей ресурс с превышением доступности, вы не сможете прочесть таблицу.</span><span class="sxs-lookup"><span data-stu-id="7467d-216">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="7467d-217">Настройка трудозатрат для задач без заданий округляется до одного дня.</span><span class="sxs-lookup"><span data-stu-id="7467d-217">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-218">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-218">Word</span></span>
- <span data-ttu-id="7467d-219">Может не работать сохранение файла после слияния при определенных условиях.</span><span class="sxs-lookup"><span data-stu-id="7467d-219">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="7467d-220">Диспетчер стандартных блоков может отображать неправильное оповещение: &quot;Были изменены стили, стандартные блоки&quot;.</span><span class="sxs-lookup"><span data-stu-id="7467d-220">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="7467d-221">Область примечаний иногда перезагружается при использовании команд копирования и вставки.</span><span class="sxs-lookup"><span data-stu-id="7467d-221">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="7467d-222">Примечания иногда вставляются в неправильном порядке.</span><span class="sxs-lookup"><span data-stu-id="7467d-222">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="7467d-223">При применении к существующим документам шаблона, состоящего из многоуровневого списка с пользовательскими стилями, стили могут не сохраняться при определенных условиях.</span><span class="sxs-lookup"><span data-stu-id="7467d-223">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="7467d-224">Изменение границы разделенного экрана может приводить к дополнительному разделению экрана.</span><span class="sxs-lookup"><span data-stu-id="7467d-224">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="7467d-225">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="7467d-225">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="7467d-226">При упоминании пользователя в карточке примечания может отображаться формат JSON.</span><span class="sxs-lookup"><span data-stu-id="7467d-226">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="7467d-227">Безопасные ссылки, ведущие из одного приложения Office в другое, могут не запускать связанное приложение.</span><span class="sxs-lookup"><span data-stu-id="7467d-227">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-228">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-228">Office Suite</span></span>
- <span data-ttu-id="7467d-229">В продуктах на японском языке имя и фамилия пользователя учетной записи могут отображаться в неправильном порядке.</span><span class="sxs-lookup"><span data-stu-id="7467d-229">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="7467d-230">При наведении указателя мыши на примечание может появляться рамка вокруг примечания.</span><span class="sxs-lookup"><span data-stu-id="7467d-230">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-november-15"></a><span data-ttu-id="7467d-232">Версия 1912, 15 ноября</span><span class="sxs-lookup"><span data-stu-id="7467d-232">Version 1912: November 15</span></span>
<span data-ttu-id="7467d-233">*Версия 1912 (сборка 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-233">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-235">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-235">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="7467d-236">Службы аналитики</span><span class="sxs-lookup"><span data-stu-id="7467d-236">Insights Services</span></span>
- <span data-ttu-id="7467d-237">**Запросы на естественном языке в инструменте "Идеи" в Excel.** Новая возможность "Идеи", чтобы задавать вопрос о ваших данных на естественном языке в Excel.</span><span class="sxs-lookup"><span data-stu-id="7467d-237">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-240">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-241">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-241">Excel</span></span>
- <span data-ttu-id="7467d-242">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="7467d-242">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="7467d-243">Редактирование формул динамического массива в ячейке может привести к выравниванию текста за границами ячейки.</span><span class="sxs-lookup"><span data-stu-id="7467d-243">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-244">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-244">Outlook</span></span>
- <span data-ttu-id="7467d-245">Добавлена возможность применять конфигурацию S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="7467d-245">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="7467d-246">Встроенные изображения могут отображаться в размере меньше предполагаемого.</span><span class="sxs-lookup"><span data-stu-id="7467d-246">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-247">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-247">PowerPoint</span></span>
- <span data-ttu-id="7467d-248">Курсор может исчезнуть после перемещения фокуса с текста.</span><span class="sxs-lookup"><span data-stu-id="7467d-248">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="7467d-249">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-249">Project</span></span>
- <span data-ttu-id="7467d-250">У пользователей может возникать ошибка лицензирования.</span><span class="sxs-lookup"><span data-stu-id="7467d-250">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="7467d-251">Возможна установка неверной даты кнопкой "Сегодня" в средстве выбора даты.</span><span class="sxs-lookup"><span data-stu-id="7467d-251">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-252">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-252">Word</span></span>
- <span data-ttu-id="7467d-253">Иногда щелчок правой кнопкой мыши не выделяет все слово.</span><span class="sxs-lookup"><span data-stu-id="7467d-253">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="7467d-254">Курсор может оставаться активным в объекте после преобразования в предлагаемый формат.</span><span class="sxs-lookup"><span data-stu-id="7467d-254">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="7467d-255">В некоторых ситуациях изображения в сообщениях могут быть неправильно масштабированы.</span><span class="sxs-lookup"><span data-stu-id="7467d-255">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="7467d-256">В некоторых темах иногда сложно определить выбранное примечание.</span><span class="sxs-lookup"><span data-stu-id="7467d-256">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="7467d-257">При выборе маркера примечаний теперь должна отображаться современная область примечаний, если она скрыта в переключателе области.</span><span class="sxs-lookup"><span data-stu-id="7467d-257">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-258">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-258">Office Suite</span></span>
- <span data-ttu-id="7467d-259">При ответе на примечание возможно вертикальное расширение текстового поля за край области.</span><span class="sxs-lookup"><span data-stu-id="7467d-259">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-november-08"></a><span data-ttu-id="7467d-261">Версия 1912: 8 ноября</span><span class="sxs-lookup"><span data-stu-id="7467d-261">Version 1912: November 08</span></span>
<span data-ttu-id="7467d-262">*Версия 1912 (сборка 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-262">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-264">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-264">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="7467d-265">Жизненный цикл пользователя</span><span class="sxs-lookup"><span data-stu-id="7467d-265">User Lifecycle</span></span>
- <span data-ttu-id="7467d-266">**Улучшение взаимодействия для активации AFO.** Обновления экранов, демонстрируемых пользователям при активации Office, входящего в состав нового компьютера.</span><span class="sxs-lookup"><span data-stu-id="7467d-266">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-267">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-267">Word</span></span>
- <span data-ttu-id="7467d-268">**Новые и улучшенные возможности для видео из Интернета в Word.** Новые и более безопасные функции для видео из Интернета, предназначенные для вставки новых и воспроизведения существующих видео в Word.</span><span class="sxs-lookup"><span data-stu-id="7467d-268">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-271">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-271">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7467d-272">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-272">Outlook</span></span>
- <span data-ttu-id="7467d-273">Периодические сбои при работе с содержимым разных папок.</span><span class="sxs-lookup"><span data-stu-id="7467d-273">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-274">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-274">Office Suite</span></span>
- <span data-ttu-id="7467d-275">Вставка диаграммы из Excel в PowerPoint может уменьшать размер диаграммы.</span><span class="sxs-lookup"><span data-stu-id="7467d-275">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-november-01"></a><span data-ttu-id="7467d-277">Версия 1911: 1 ноября</span><span class="sxs-lookup"><span data-stu-id="7467d-277">Version 1911: November 01</span></span>
<span data-ttu-id="7467d-278">*Версия 1911 (сборка 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="7467d-278">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-280">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-280">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-281">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-281">Excel</span></span>
- <span data-ttu-id="7467d-282">**Использование контекста вместе с объектами SVG.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Office.</span><span class="sxs-lookup"><span data-stu-id="7467d-282">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="7467d-283">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="7467d-283">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-284">PowerPoint</span></span>
- <span data-ttu-id="7467d-285">**Использование контекста вместе с объектами SVG.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Office.</span><span class="sxs-lookup"><span data-stu-id="7467d-285">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="7467d-286">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="7467d-286">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="7467d-287">Visio</span><span class="sxs-lookup"><span data-stu-id="7467d-287">Visio</span></span>
- <span data-ttu-id="7467d-288">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="7467d-288">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="7467d-289">[Подробнее](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="7467d-289">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="7467d-290">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-290">Word</span></span>
- <span data-ttu-id="7467d-291">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="7467d-291">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="7467d-292">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="7467d-292">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="7467d-293">**Другие пользователи быстро просматривают внесенные вами изменения.** С улучшенными функциями совместного редактирования участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо прежде.</span><span class="sxs-lookup"><span data-stu-id="7467d-293">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-296">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-296">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-297">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-297">Excel</span></span>
- <span data-ttu-id="7467d-298">Исправлена проблема, из-за которой мог происходить сбой программы Excel при изменении защищенного файла из ненадежного сетевого ресурса.</span><span class="sxs-lookup"><span data-stu-id="7467d-298">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="7467d-299">Исправлена проблема, из-за которой удаление листов, содержащих спарклайны со ссылками на данные других листов, могло привести к обозначению файла как поврежденного при повторном открытии.</span><span class="sxs-lookup"><span data-stu-id="7467d-299">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="7467d-300">Устранена проблема, из-за которой можно было получить неверный результат при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="7467d-300">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="7467d-301">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-301">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="7467d-302">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-302">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-303">Outlook</span></span>
- <span data-ttu-id="7467d-304">Перенаправленная электронная почта может лишиться внедренных изображений.</span><span class="sxs-lookup"><span data-stu-id="7467d-304">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="7467d-305">Средство поиска помещений может отображать значение &quot;Нет&quot; для доступных помещений.</span><span class="sxs-lookup"><span data-stu-id="7467d-305">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="7467d-306">Пользователи не могут создавать профили Outlook со строгим ограничением клиента.</span><span class="sxs-lookup"><span data-stu-id="7467d-306">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-307">PowerPoint</span></span>
- <span data-ttu-id="7467d-308">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-308">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="7467d-309">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-309">Project</span></span>
- <span data-ttu-id="7467d-310">Пользователь не может отметить задачу как завершенную, и ее выполнение остается на уровне 99 %.</span><span class="sxs-lookup"><span data-stu-id="7467d-310">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="7467d-311">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="7467d-311">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-312">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-312">Word</span></span>
- <span data-ttu-id="7467d-313">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-313">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="7467d-314">Открытие устаревших документов с последующим переходом на вкладку "Сведения" может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-314">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="7467d-315">Предложения проверки не отображаются в контекстных меню.</span><span class="sxs-lookup"><span data-stu-id="7467d-315">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="7467d-316">Политики содержимого применяются к комментариям некорректно.</span><span class="sxs-lookup"><span data-stu-id="7467d-316">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="7467d-317">Старые комментарии, написанные темным текстом, не видны в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="7467d-317">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="7467d-318">При использовании автозамены в языковой паре корейский-английский могут отображаться некорректные символы.</span><span class="sxs-lookup"><span data-stu-id="7467d-318">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="7467d-319">Могут применяться метки менее строгих политик, когда приоритет должна иметь метка более строгой политики.</span><span class="sxs-lookup"><span data-stu-id="7467d-319">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="7467d-320">Ссылки cid: теперь связь с изображениями из сообщений Outlook&nbsp;может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="7467d-320">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="7467d-321">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-321">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="7467d-322">Поиск из области навигации может завершаться неудачей.</span><span class="sxs-lookup"><span data-stu-id="7467d-322">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-323">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-323">Office Suite</span></span>
- <span data-ttu-id="7467d-324">Некоторые рисунки могут не отображаться в предварительном просмотре или в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="7467d-324">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="7467d-325">Символы катаканы могут неправильно отображаться в вертикальной надписи.</span><span class="sxs-lookup"><span data-stu-id="7467d-325">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="7467d-326">Попытка сохранить файл в сетевой папке, с которой потеряна связь, может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="7467d-326">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-october-25"></a><span data-ttu-id="7467d-328">Версия 1911: 25 октября</span><span class="sxs-lookup"><span data-stu-id="7467d-328">Version 1911: October 25</span></span>
<span data-ttu-id="7467d-329">*Версия 1911 (сборка 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="7467d-329">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-331">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-331">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="7467d-332">Visio</span><span class="sxs-lookup"><span data-stu-id="7467d-332">Visio</span></span>

- <span data-ttu-id="7467d-333">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="7467d-333">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="7467d-334">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-334">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="7467d-335">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-335">Word</span></span>

- <span data-ttu-id="7467d-336">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="7467d-336">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="7467d-337">**Другие пользователи быстро просматривают внесенные вами изменения.** С улучшенными функциями совместного редактирования участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо прежде.</span><span class="sxs-lookup"><span data-stu-id="7467d-337">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="7467d-340">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="7467d-340">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7467d-341">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-341">Access</span></span>

- <div><span data-ttu-id="7467d-342"><span>Число записей может быть неверным</span></span><span class="sxs-lookup"><span data-stu-id="7467d-342"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="7467d-343">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-343">Excel</span></span>

- <div><span data-ttu-id="7467d-344"><span>Значительно повышена производительность при удалении столбцов с объединенными ячейками</span></span><span class="sxs-lookup"><span data-stu-id="7467d-344"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="7467d-345"><span>Пользователям не удается сохранять записи в формате книги Excel в Office 365</span></span><span class="sxs-lookup"><span data-stu-id="7467d-345"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="7467d-346"><span>Флажки могут отображаться неправильно</span></span><span class="sxs-lookup"><span data-stu-id="7467d-346"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="7467d-347"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="7467d-347"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="7467d-348"><span>Некоторые функции VBA возвращают ошибку в новых типах диаграмм</span></span><span class="sxs-lookup"><span data-stu-id="7467d-348"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="7467d-349"><span>В диалоговых окнах "Выбор источника данных" не учитывается регистр для некоторых полей</span></span><span class="sxs-lookup"><span data-stu-id="7467d-349"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-350">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-351"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="7467d-351"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="7467d-352">Publisher</span><span class="sxs-lookup"><span data-stu-id="7467d-352">Publisher</span></span>

- <div><span data-ttu-id="7467d-353"><span>Фигуры могут отображаться за пределами границы рисунка</span></span><span class="sxs-lookup"><span data-stu-id="7467d-353"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-354">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-354">Word</span></span>

- <div><span data-ttu-id="7467d-355"><span>Фигуры могут отображаться за пределами границы рисунка</span></span><span class="sxs-lookup"><span data-stu-id="7467d-355"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="7467d-356"><span>Обтекание текста может оказаться трудной задачей</span></span><span class="sxs-lookup"><span data-stu-id="7467d-356"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="7467d-357"><span>Пользователю не удается перейти к отдельному элементу в редакторе</span></span><span class="sxs-lookup"><span data-stu-id="7467d-357"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="7467d-358"><span>Грамматические и орфографические ошибки могут не выделяться</span></span><span class="sxs-lookup"><span data-stu-id="7467d-358"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="7467d-359"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="7467d-359"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="7467d-360"><span>Не удается открыть карточку контакта после применения форматирования к @упоминанию</span></span><span class="sxs-lookup"><span data-stu-id="7467d-360"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="7467d-361"><span>Решена проблема, из-за которой пользователям не удается сохранить документы Word, Excel и PowerPoint.&nbsp; Эта проблема возникает у пользователей, создающих файл и использующих параметр &quot;Сохранить как модельное диалоговое окно&quot; после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-361"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="7467d-362">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-362">Office Suite</span></span>

- <div><span data-ttu-id="7467d-363"><span>Проблема с производительностью при использовании фигур в Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="7467d-363"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-october-18"></a><span data-ttu-id="7467d-365">Версия 1911: 18 октября</span><span class="sxs-lookup"><span data-stu-id="7467d-365">Version 1911: October 18</span></span>
<span data-ttu-id="7467d-366">*Версия 1911 (сборка 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="7467d-366">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-368">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-368">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7467d-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-369">Outlook</span></span>

- <span data-ttu-id="7467d-370">**Отправка писем со специальными возможностями пользователям, которым они нужны.** Outlook отображает подсказку, помогающую обеспечить доступность контента при отправке пользователю, который предпочитает контент с поддержкой специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="7467d-370">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-371">PowerPoint</span></span>

- <span data-ttu-id="7467d-372">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="7467d-372">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7467d-373">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-373">Office Suite</span></span>

- <span data-ttu-id="7467d-374">**Центр отправки заменяется интерфейсом "Файлы, требующие внимания".** Центр отправки заменяется интерфейсом "Файлы, требующие внимания", доступным в приложениях Office в разделе "Файл" > "Открыть".</span><span class="sxs-lookup"><span data-stu-id="7467d-374">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="7467d-375">Этот новый интерфейс более современный, интегрированный и менее навязчивый по сравнению с Центром отправки.</span><span class="sxs-lookup"><span data-stu-id="7467d-375">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-378">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-378">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-379">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-379">Excel</span></span>

- <div><span data-ttu-id="7467d-380"><span>Исправлена проблема, из-за которой флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки</span></span><span class="sxs-lookup"><span data-stu-id="7467d-380"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="7467d-381"><span>Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки</span></span><span class="sxs-lookup"><span data-stu-id="7467d-381"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-382">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-382">Outlook</span></span>

- <div><span data-ttu-id="7467d-383"><span>Обнаружена проблема, которая может вызывать нарушение цифровых подписей при подписании сообщения, содержащего вложение с цифровой подписью</span></span><span class="sxs-lookup"><span data-stu-id="7467d-383"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="7467d-384"><span>Обнаружена проблема, из-за которой длинные имена файлов усекались после перетаскивания в текст сообщения</span></span><span class="sxs-lookup"><span data-stu-id="7467d-384"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="7467d-385">Обнаружена проблема, из-за которой поле поиска может исчезать, если лента настроена на автоматическое скрытие</span><span class="sxs-lookup"><span data-stu-id="7467d-385">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-386">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-387"><span>Обнаружена проблема, из-за которой пропорции при предварительном просмотре слайда блокировались или разблокировались неправильно.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-387"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="7467d-388">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-388">Project</span></span>

- <div><span data-ttu-id="7467d-389">Обнаружена проблема, из-за которой примечания могут не сохраняться, если вводятся при выполнении задач обновления</span><span class="sxs-lookup"><span data-stu-id="7467d-389">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="7467d-390">Обнаружена проблема, из-за которой файл может блокироваться пользователем, но в сообщении об ошибке не отображается имя пользователя</span><span class="sxs-lookup"><span data-stu-id="7467d-390">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="7467d-391"><span>Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения</span></span><span class="sxs-lookup"><span data-stu-id="7467d-391"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-392">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-392">Word</span></span>

- <div><span data-ttu-id="7467d-393"><span>Выявлена проблема с просмотром примечаний при использовании средства чтения с экрана</span></span><span class="sxs-lookup"><span data-stu-id="7467d-393"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="7467d-394"><span>Обнаружена проблема, из-за которой некоторые замечания неправильно определялись как орфографические или грамматические замечания</span></span><span class="sxs-lookup"><span data-stu-id="7467d-394"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="7467d-395"><span>Обнаружена проблема, из-за которой фокус иногда не перемещается в диалоговое окно создания примечания</span></span><span class="sxs-lookup"><span data-stu-id="7467d-395"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="7467d-396">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-396">Office Suite</span></span>

- <div><span data-ttu-id="7467d-397"><span>Исправлена проблема, из-за которой обновление могло блокироваться неверным сообщением об ошибке &quot;Уже запущен другой процесс установки&quot;</span></span><span class="sxs-lookup"><span data-stu-id="7467d-397"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="7467d-398"><span>Обнаружена проблема, которая может влиять на синхронизацию локального ресурса с облачным</span></span><span class="sxs-lookup"><span data-stu-id="7467d-398"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="7467d-399"><span>Обнаружена проблема, из-за которой приветственное сообщение содержит неправильную ссылку</span></span><span class="sxs-lookup"><span data-stu-id="7467d-399"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-october-11"></a><span data-ttu-id="7467d-401">Версия 1910: 11 октября</span><span class="sxs-lookup"><span data-stu-id="7467d-401">Version 1910: October 11</span></span>
<span data-ttu-id="7467d-402">*Версия 1910 (сборка 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="7467d-402">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-406">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-406">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-407">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-407">Excel</span></span>

- <div><span data-ttu-id="7467d-408">Решена проблема со вставкой файлов в качестве объектов из OneDrive</span><span class="sxs-lookup"><span data-stu-id="7467d-408">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="7467d-409">Решена проблема, из-за которой не удавалось правильно применять формат гиперссылки к некоторому содержимому</span><span class="sxs-lookup"><span data-stu-id="7467d-409">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="7467d-410">Решена проблема, из-за которой формулы со структурированными абсолютными ссылками могли изменяться неправильно</span><span class="sxs-lookup"><span data-stu-id="7467d-410">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="7467d-411">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office</span><span class="sxs-lookup"><span data-stu-id="7467d-411">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="7467d-412">Решена проблема, из-за которой содержимое, скопированное из Excel, могло отображаться неправильно при вставке в другие приложения Office</span><span class="sxs-lookup"><span data-stu-id="7467d-412">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="7467d-413">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм</span><span class="sxs-lookup"><span data-stu-id="7467d-413">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-414">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-414">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-415">Обнаружена проблема, из-за которой устройства ARC могли терять подключение при работе в AirSpace WinComp</span><span class="sxs-lookup"><span data-stu-id="7467d-415">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-416">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-416">Word</span></span>

- <div><span data-ttu-id="7467d-417">Решена проблема со вставкой файлов в качестве объектов из OneDrive</span><span class="sxs-lookup"><span data-stu-id="7467d-417">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="7467d-418">Улучшены этапы восстановления для и<span>справления проблемы, приводившей к удалению графического содержимого из цепочек электронной почты.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="7467d-418">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-october-04"></a><span data-ttu-id="7467d-420">Версия 1910: 4 октября</span><span class="sxs-lookup"><span data-stu-id="7467d-420">Version 1910: October 04</span></span>
<span data-ttu-id="7467d-421">*Версия 1910 (сборка 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-421">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-423">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-423">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-424">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-424">Excel</span></span>

- <span data-ttu-id="7467d-425">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="7467d-425">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="7467d-426">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-426">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-429">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-429">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-430">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-430">Excel</span></span>

- <div><span data-ttu-id="7467d-431"><span>Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати</span></span><span class="sxs-lookup"><span data-stu-id="7467d-431"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="7467d-432"><span>Исправлена проблема, которая могла блокировать обновление сводных таблиц во время совместного редактирования</span></span><span class="sxs-lookup"><span data-stu-id="7467d-432"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="7467d-433">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-433">Access</span></span>

- <div><span data-ttu-id="7467d-434">Исправлена проблема, из-за которой пользователи могли сталкиваться с ошибкой &quot;несогласованного состояния&quot; при использовании общей базы данных.</span><span class="sxs-lookup"><span data-stu-id="7467d-434">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-435">Outlook</span></span>

- <div><span data-ttu-id="7467d-436"><span>Исправлена проблема, которая могла приводить к дублированию почтовых папок</span></span><span class="sxs-lookup"><span data-stu-id="7467d-436"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="7467d-437"><span>Исправлена проблема, из-за которой могло неправильно возникать сообщение об ошибке при попытке отправить письмо, зашифрованное с помощью S/MIME</span></span><span class="sxs-lookup"><span data-stu-id="7467d-437"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="7467d-438"><span>Исправлена проблема, из-за которой иногда мог возникать сбой при получении пользователем сообщения "Пропущенная беседа" из Skype</span></span><span class="sxs-lookup"><span data-stu-id="7467d-438"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="7467d-439"><span>Исправлена проблема, которая могла приводить к утечке памяти</span></span><span class="sxs-lookup"><span data-stu-id="7467d-439"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="7467d-440"><span>Исправлена проблема, которая могла приводить к изменению имени отправителя при сохранении в виде черновика</span></span><span class="sxs-lookup"><span data-stu-id="7467d-440"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-441">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="7467d-442">Исправлена проблема, из-за которой могли повреждаться объекты TextRange после вставки текста в колонтитулы или заполнители номеров страниц слайдов в образце слайдов и макете слайдов.</span><span class="sxs-lookup"><span data-stu-id="7467d-442">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="7467d-443">Исправлена проблема, не позволявшая создавать гиперссылку при вставке текста с гиперссылкой.</span><span class="sxs-lookup"><span data-stu-id="7467d-443">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="7467d-444">Исправлена проблема, которая могла мешать правильной работе статистических данных.</span><span class="sxs-lookup"><span data-stu-id="7467d-444">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-445">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-445">Word</span></span>

- <div><span data-ttu-id="7467d-446"><span>Исправлена проблема, из-за которой не фиксировался цвет шрифта</span></span><span class="sxs-lookup"><span data-stu-id="7467d-446"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="7467d-447">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7467d-447">Office Suite</span></span>

- <div><span data-ttu-id="7467d-448">Исправлена проблема, из-за которой мог предлагаться журнал версий, когда эта функция отключена.</span><span class="sxs-lookup"><span data-stu-id="7467d-448">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-27"></a><span data-ttu-id="7467d-450">Версия 1910: 27 сентября</span><span class="sxs-lookup"><span data-stu-id="7467d-450">Version 1910: September 27</span></span>
<span data-ttu-id="7467d-451">*Версия 1910 (сборка 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-451">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-455">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-455">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-456">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-456">Excel</span></span>

- <div><span data-ttu-id="7467d-457"><span>Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов</span></span><span class="sxs-lookup"><span data-stu-id="7467d-457"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-458">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-458">Outlook</span></span>

- <div><span data-ttu-id="7467d-459"><span>Исправлена проблема, которая могла приводить к ошибкам с разрешениями при взаимодействии с общими папками календаря</span></span><span class="sxs-lookup"><span data-stu-id="7467d-459"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="7467d-460"><span>Исправлена проблема, которая могла мешать пользователям добавлять вложения в календари</span></span><span class="sxs-lookup"><span data-stu-id="7467d-460"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="7467d-461"><span>Исправлена проблема, приводившая к появлению сообщений об ошибках при ответе на сообщение с цифровой подписью</span></span><span class="sxs-lookup"><span data-stu-id="7467d-461"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-462">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-462">Word</span></span>

- <div><span data-ttu-id="7467d-463"><span>Исправлена проблема, которая могла приводить к ошибкам с масштабированием при печати на принтерах Deskjet</span></span><span class="sxs-lookup"><span data-stu-id="7467d-463"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="7467d-464">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-464">Office Suite</span></span>

- <div><span data-ttu-id="7467d-465"><span>Исправлена проблема, из-за которой к полужирному тексту среднего размера могли применяться неправильные стили</span></span><span class="sxs-lookup"><span data-stu-id="7467d-465"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="7467d-466"><span>Исправлена проблема, из-за которой для пользователя могло отображаться неверное сообщение об ошибке при закрытии файла, ожидающего отправки</span></span><span class="sxs-lookup"><span data-stu-id="7467d-466"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-20"></a><span data-ttu-id="7467d-468">Версия 1910: 20 сентября</span><span class="sxs-lookup"><span data-stu-id="7467d-468">Version 1910: September 20</span></span>
<span data-ttu-id="7467d-469">*Версия 1910 (сборка 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-469">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-473">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-473">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-474">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-474">Excel</span></span>

- <div><span data-ttu-id="7467d-475"><span>Исправлена проблема, из-за которой Excel иногда зависал при запуске</span></span><span class="sxs-lookup"><span data-stu-id="7467d-475"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="7467d-476">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-476">Outlook</span></span>

- <div><span data-ttu-id="7467d-477"><span>Мы значительно улучшили производительность при выборе помещения, если доступно много помещений</span></span><span class="sxs-lookup"><span data-stu-id="7467d-477"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="7467d-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Исправлена проблема, которая могла мешать синхронизации почтовых ящиков клиентов с почтовыми ящиками в Outlook при переходе на современную проверку подлинности в Office 365.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="7467d-479"><span>Исправлена проблема, из-за которой некоторые символы в метках подписей не отображались в выпадающем меню</span></span><span class="sxs-lookup"><span data-stu-id="7467d-479"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="7467d-480">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-480">Project</span></span>

- <div><span data-ttu-id="7467d-481"><span>Исправлена проблема, которая могла приводить к сбою при замене корпоративного ресурса локальным ресурсом</span></span><span class="sxs-lookup"><span data-stu-id="7467d-481"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-482">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-482">Word</span></span>

- <div><span data-ttu-id="7467d-483"><span>Исправлена проблема, которая могла мешать правильной работе синхронной прокрутки в режиме черновика</span></span><span class="sxs-lookup"><span data-stu-id="7467d-483"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="7467d-484">Исправлена проблема, из-за которой всплывающие подсказки могли неправильно отображаться после сохранения документа в первый раз</span><span class="sxs-lookup"><span data-stu-id="7467d-484">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-13"></a><span data-ttu-id="7467d-486">Версия 1910: 13 сентября</span><span class="sxs-lookup"><span data-stu-id="7467d-486">Version 1910: September 13</span></span>
<span data-ttu-id="7467d-487">*Версия 1910 (сборка 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-487">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-489">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-489">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-490">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-490">Excel</span></span>

- <div><span data-ttu-id="7467d-491"><span>Исправлена проблема, которая могла мешать пользователям вставлять гиперссылки в некоторых защищенных листах</span></span><span class="sxs-lookup"><span data-stu-id="7467d-491"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-492">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-492">Outlook</span></span>

- <div><span data-ttu-id="7467d-493"><span>Исправлена проблема, из-за которой пользовательский интерфейс мог зависать в компактном представлении</span></span><span class="sxs-lookup"><span data-stu-id="7467d-493"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-494">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-495"><span>Исправлена проблема, из-за которой у пользователя могла возникать ошибка при печати в PDF</span></span><span class="sxs-lookup"><span data-stu-id="7467d-495"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="7467d-496">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-496">Project</span></span>

- <div><span data-ttu-id="7467d-497"><span>Исправлена проблема, из-за которой <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">изменение значения трудозатрат в суммарной задаче могло приводить к сбою при включенной функции защищенных значений трудозатрат</span></span></span><span class="sxs-lookup"><span data-stu-id="7467d-497"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="7467d-498"><font size=2 style="background-color:rgb(255, 255, 255);">Исправлена проблема, которая могла блокировать возможность синхронизации событий с корпоративными календарями</font></span><span class="sxs-lookup"><span data-stu-id="7467d-498"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="7467d-499">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7467d-499">Office Suite</span></span>

- <div><span data-ttu-id="7467d-500"><span>Исправлена проблема, которая могла приводить к повторному предупреждению об удалении локальных версий файла</span></span><span class="sxs-lookup"><span data-stu-id="7467d-500"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-06"></a><span data-ttu-id="7467d-502">Версия 1910: 06 сентября</span><span class="sxs-lookup"><span data-stu-id="7467d-502">Version 1910: September 06</span></span>
<span data-ttu-id="7467d-503">*Версия 1910 (сборка 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="7467d-503">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-505">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-505">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-506">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-506">Excel</span></span>

- <span data-ttu-id="7467d-507">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="7467d-507">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="7467d-508">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-508">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="7467d-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-509">PowerPoint</span></span>

- <span data-ttu-id="7467d-510">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="7467d-510">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="7467d-511">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-511">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="7467d-512">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-512">Word</span></span>

- <span data-ttu-id="7467d-513">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="7467d-513">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="7467d-514">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-514">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-517">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-517">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-518">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-518">Excel</span></span>

- <div><span data-ttu-id="7467d-519"><span>Исправлена проблема, из-за которой имя шрифта на ленте могло отличаться от используемого шрифта</span></span><span class="sxs-lookup"><span data-stu-id="7467d-519"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-520">Outlook</span></span>

- <div><span data-ttu-id="7467d-521"><span>Исправлена проблема, которая приводила к неправильному потреблению ресурсов в Outlook при отключении защищенного режима для ограниченных сайтов в Internet Explorer</span></span><span class="sxs-lookup"><span data-stu-id="7467d-521"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="7467d-522"><span>Исправлена проблема, из-за которой при вставке текста из источника ANSI иногда появлялись символы Юникода</span></span><span class="sxs-lookup"><span data-stu-id="7467d-522"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="7467d-523"><span>Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span></span><span class="sxs-lookup"><span data-stu-id="7467d-523"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-524">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-524">Word</span></span>

- <div><span data-ttu-id="7467d-525"><span>Исправлена проблема с сохранением форматирования таблиц</span></span><span class="sxs-lookup"><span data-stu-id="7467d-525"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="7467d-526"><span>Исправлена проблема, которая могла приводить к сбою сочетания клавиш CTRL + V</span></span><span class="sxs-lookup"><span data-stu-id="7467d-526"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1909-august-30"></a><span data-ttu-id="7467d-528">Версия 1909: 30 августа</span><span class="sxs-lookup"><span data-stu-id="7467d-528">Version 1909: August 30</span></span>
<span data-ttu-id="7467d-529">*Версия 1909 (сборка 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="7467d-529">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="7467d-531">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-531">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="7467d-532">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-532">Access</span></span>

- <span data-ttu-id="7467d-533">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="7467d-533">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-534">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-534">PowerPoint</span></span>

- <span data-ttu-id="7467d-535">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="7467d-535">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="7467d-536">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-536">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="7467d-539">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-539">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7467d-540">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-540">Excel</span></span>

- <div><span data-ttu-id="7467d-541"><span>Исправлена проблема, из-за которой возникал конфликт между подсказкой клавиш для функции&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">конфиденциальности </span>и&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">другой подсказкой клавиш.</span></span></span><span class="sxs-lookup"><span data-stu-id="7467d-541"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="7467d-542"><span>Исправлена проблема, возникавшая при работе с общей книгой при попытке ее сохранения.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-542"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="7467d-543"><span>Исправлена проблема, из-за которой в Excel указывались только первые 16 надстроек из значений реестра "\Excel\Add-in Manager".<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="7467d-543"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="7467d-544"><span>Исправлена проблема, из-за которой функция ЧАСТОТА() возвращает неправильные результаты.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-544"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="7467d-545"><span>Значительно повышена производительность фильтрации по цвету.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-545"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="7467d-546"><span>Исправлена проблема для пользователей Surface, из-за которой перемещение мыши могло интерпретироваться как событие щелчка мыши.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-546"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="7467d-547"><span>Исправлена проблема, не позволявшая использовать навигацию с помощью клавиатуры в диалоговом окне "Найти и заменить".</span></span><span class="sxs-lookup"><span data-stu-id="7467d-547"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="7467d-548"><span>Исправлена проблема, из-за которой неправильно отображались названия некоторых шрифтов.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-548"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="7467d-549"><span>Исправлена проблема, препятствовавшая отображению формата CSV в качестве поддерживаемого типа файла</span></span><span class="sxs-lookup"><span data-stu-id="7467d-549"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="7467d-550">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-550">Access</span></span>

- <div><span data-ttu-id="7467d-551">Исправлена проблема, из-за которой пользователи могли сталкиваться с ошибкой &quot;несогласованного состояния&quot; при использовании общей базы данных.</span><span class="sxs-lookup"><span data-stu-id="7467d-551">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="7467d-552"><span>Исправлена проблема, которая могла приводить к появлению элемента управления "Выбор даты", когда этого не требовалось.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-552"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-553">Outlook</span></span>

- <div><span data-ttu-id="7467d-554"><span>Исправлена проблема, из-за которой HTML-содержимое не отображалось для некоторых пользователей POP3.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-554"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="7467d-555"><span>Исправлена проблема для удаления неработающей ссылки "Планировщик" из меню переполнения в карточке контакта при работе в средах, в которых этот компонент недоступен.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-555"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="7467d-556">OneNote</span><span class="sxs-lookup"><span data-stu-id="7467d-556">OneNote</span></span>

- <div><span data-ttu-id="7467d-557"><span>Исправлена проблема, связанная с тем, что &nbsp;фоновая синхронизация OneNote иногда перехватывала фокус.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-557"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-558">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-559"><span>Исправлена проблема, которая могла влиять на ориентацию вращения трехмерной вертушки.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-559"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="7467d-560"><span>Исправлена проблема, из-за которой некоторые гиперссылки не работали, если они содержали специальные знаки.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-560"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="7467d-561"><span>Исправлена проблема, из-за которой одновременно открывалось несколько областей примечаний.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-561"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="7467d-562">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-562">Project</span></span>

- <div><span data-ttu-id="7467d-563"><span>Исправлена проблема, которая могла приводить к сбою после печати представления визуального оптимизатора ресурсов.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-563"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="7467d-564">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-564">Word</span></span>

- <div><span data-ttu-id="7467d-565"><span>Исправлена проблема, из-за которой многобайтовые знаки в вертикальной надписи отображаются с наложением в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="7467d-565">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="7467d-566"><span>Исправлена&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">проблема, из-за которой ресурсы надстроек, связанные с открытками на японском языке, не удается найти, когда пользователь выполняет действия в мастере надстроек.</span></span></span><span class="sxs-lookup"><span data-stu-id="7467d-566"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="7467d-567"><span>Исправлена проблема, из-за которой могли возникать неполадки с пользовательским интерфейсом строки заголовка окна в режиме защищенного просмотра.</span></span><span class="sxs-lookup"><span data-stu-id="7467d-567"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="7467d-568">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7467d-568">Office Suite</span></span>

- <div><span data-ttu-id="7467d-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Исправлена проблема повреждения файлов при применении действия "Изменить фигуру" к выбранному фрагменту, содержащему обычную фигуру и соединительную линию.</span></span></span><span class="sxs-lookup"><span data-stu-id="7467d-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="7467d-570"><span>Исправлена проблема, <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">приводившая к неполадкам в работе приложений при подключении к нескольким внешним дисплеям или при отключении от них. </span></span></span><span class="sxs-lookup"><span data-stu-id="7467d-570"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="august-23-2019br"></a><span data-ttu-id="7467d-572">**23 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="7467d-572">**August 23, 2019**</span></span><br/>
<span data-ttu-id="7467d-573">Версия 1909 (сборка 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="7467d-573">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="7467d-574">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-574">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-575">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-575">Excel</span></span>

- <div><span data-ttu-id="7467d-576"><span>Значительно повышена производительность при удалении столбцов с объединенными ячейками</span></span><span class="sxs-lookup"><span data-stu-id="7467d-576"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="7467d-577">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7467d-577">Office Suite</span></span>

- <div><span data-ttu-id="7467d-578"><span>Исправлена проблема, которая могла препятствовать отображению некоторых символов Юникода при просмотре в браузере</span></span><span class="sxs-lookup"><span data-stu-id="7467d-578"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="7467d-579">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-579">Outlook</span></span>

- <div><span data-ttu-id="7467d-580"><span>Исправлена проблема, которая могла препятствовать сохранению файлов в папке WebDAV</span></span><span class="sxs-lookup"><span data-stu-id="7467d-580"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-581">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-582"><span>Исправлена проблема, из-за которой при щелчке пользователя по одному примечанию выделялось другое примечание</span></span><span class="sxs-lookup"><span data-stu-id="7467d-582"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="7467d-583">**16 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="7467d-583">**August 16, 2019**</span></span><br/>
<span data-ttu-id="7467d-584">Версия 1909 (сборка 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-584">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7467d-585">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-585">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="7467d-586">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="7467d-586">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="7467d-587">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="7467d-587">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="7467d-588">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-588">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-589">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-589">Excel</span></span>

- <div><span data-ttu-id="7467d-590"><span>Исправлена проблема, которая приводила к включению функции автосохранения</span></span><span class="sxs-lookup"><span data-stu-id="7467d-590"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="7467d-591">Исправлена проблема, которая приводила к неточному измерению высоты ячеек</span><span class="sxs-lookup"><span data-stu-id="7467d-591">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="7467d-592">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7467d-592">Office Suite</span></span>

- <div><span data-ttu-id="7467d-593"><span>Исправлена проблема, благодаря чему значительно улучшилась производительность функции примечаний</span></span><span class="sxs-lookup"><span data-stu-id="7467d-593"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="7467d-594"><span>Исправлена проблема, которая могла приводить к сбою при использовании клавиш со стрелками во время поиска</span></span><span class="sxs-lookup"><span data-stu-id="7467d-594"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="7467d-595"><span>Исправлена проблема, из-за которой @упоминание было недоступным, если символ @ стоял после определенных символов</span></span><span class="sxs-lookup"><span data-stu-id="7467d-595"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="7467d-596"><span>Исправлена проблема, которая могла приводить к сбою при удалении @упоминаний</span></span><span class="sxs-lookup"><span data-stu-id="7467d-596"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="7467d-597"><span>Исправлена проблема, из-за которой эмодзи могли неправильно отображаться в карточках примечаний</span></span><span class="sxs-lookup"><span data-stu-id="7467d-597"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="7467d-598"><span>Исправлена проблема с активным буфером обмена, которая могла приводить к сбою</span></span><span class="sxs-lookup"><span data-stu-id="7467d-598"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="7467d-599"><span>Исправлена проблема, которая могла приводить к прекращению работы кнопок на панели быстрого доступа</span></span><span class="sxs-lookup"><span data-stu-id="7467d-599"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="7467d-600"><span>Исправлена проблема, из-за которой предварительный просмотр форматирования документа мог не переключаться на задний план</span></span><span class="sxs-lookup"><span data-stu-id="7467d-600"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="7467d-601">OneNote</span><span class="sxs-lookup"><span data-stu-id="7467d-601">OneNote</span></span>

- <span data-ttu-id="7467d-602">Исправлена проблема, из-за которой имена разделов не отображаются в раскрывающемся списке разделов, если для темы Office задано значение "черная".</span><span class="sxs-lookup"><span data-stu-id="7467d-602">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-603">Outlook</span></span>

- <div><span data-ttu-id="7467d-604"><span>Исправлена проблема с отправкой событий, из-за которой приложение Outlook могло периодически терять фокус</span></span><span class="sxs-lookup"><span data-stu-id="7467d-604"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="7467d-605"><span>Исправлена проблема, из-за которой не работало сочетание клавиш для помещения ответа в папку</span></span><span class="sxs-lookup"><span data-stu-id="7467d-605"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="7467d-606">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-606">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-607"><span>Исправлена проблема с режимом защищенного просмотра, из-за которой иногда возникали проблемы при совместной работе</span></span><span class="sxs-lookup"><span data-stu-id="7467d-607"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="7467d-608"><span>Исправлена проблема, которая приводила к неправильному отображению задач в области примечаний</span></span><span class="sxs-lookup"><span data-stu-id="7467d-608"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="7467d-609"><span>Исправлена проблема, которая могла приводить к сбою при вставке новых слайдов</span></span><span class="sxs-lookup"><span data-stu-id="7467d-609"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="7467d-610">Жизненный цикл пользователя</span><span class="sxs-lookup"><span data-stu-id="7467d-610">User Lifecycle</span></span>

- <div><span data-ttu-id="7467d-611"><span>Исправлена проблема, из-за которой могла быть недоступна возможность подписки</span></span><span class="sxs-lookup"><span data-stu-id="7467d-611"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="7467d-612">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-612">Word</span></span>

- <div><span data-ttu-id="7467d-613"><span>Исправлена проблема, из-за которой гиперссылки не работали, если содержали определенные символы</span></span><span class="sxs-lookup"><span data-stu-id="7467d-613"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="7467d-614"><span>Исправлена проблема, из-за которой размеры изображения могли изменяться при просмотре примечаний к нему</span></span><span class="sxs-lookup"><span data-stu-id="7467d-614"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="7467d-615"><span>Исправлена проблема с раскрывающимся меню маркированного списка, которая могло приводить к сбою</span></span><span class="sxs-lookup"><span data-stu-id="7467d-615"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="7467d-616">**9 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="7467d-616">**August 09, 2019**</span></span><br/>
<span data-ttu-id="7467d-617">Версия 1909 (сборка 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-617">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="7467d-618">Обновления функций Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-618">Excel Feature updates:</span></span>

- <span data-ttu-id="7467d-619">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="7467d-619">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="7467d-620">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="7467d-620">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7467d-621">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="7467d-621">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="7467d-622">Набор Office. Обновления функций</span><span class="sxs-lookup"><span data-stu-id="7467d-622">Office Suite Feature updates:</span></span>

- <span data-ttu-id="7467d-623">**Новые значки приложений Office.** Обновленные значки приложений отражают простоту, функциональность и интеллектуальные возможности Office</span><span class="sxs-lookup"><span data-stu-id="7467d-623">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="7467d-624">Обновления функций Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-624">Outlook Feature updates:</span></span>

- <span data-ttu-id="7467d-625">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="7467d-625">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="7467d-626">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="7467d-626">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7467d-627">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="7467d-627">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7467d-628">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-628">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="7467d-629">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="7467d-629">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7467d-630">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="7467d-630">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="7467d-631">Обновления функций Word</span><span class="sxs-lookup"><span data-stu-id="7467d-631">Word Feature updates:</span></span>

- <span data-ttu-id="7467d-632">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="7467d-632">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="7467d-633">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="7467d-633">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7467d-634">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="7467d-634">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="7467d-635">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-635">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-636">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-636">Outlook</span></span>

- <div><span data-ttu-id="7467d-637"><span>Исправлена проблема, из-за которой получатели приглашения на собрание получали два уведомления после отмены собрания</span></span><span class="sxs-lookup"><span data-stu-id="7467d-637"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="7467d-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-638">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-639"><span>Исправлена проблема, которая приводила к сбою, когда пользователь выбирал пункт "Без контура" или "Без заливки" в меню "Фигуры и значки"</span></span><span class="sxs-lookup"><span data-stu-id="7467d-639"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="7467d-640">**2 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="7467d-640">**August 02, 2019**</span></span><br/>
<span data-ttu-id="7467d-641">Версия 1908 (сборка 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="7467d-641">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="7467d-642">Обновления функций Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-642">Excel Feature updates:</span></span>

- <span data-ttu-id="7467d-643">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="7467d-643">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="7467d-644">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="7467d-644">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="7467d-645">Обновления функций Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-645">Outlook Feature updates:</span></span>

- <span data-ttu-id="7467d-646">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="7467d-646">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7467d-647">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-647">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="7467d-648">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="7467d-648">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="7467d-649">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="7467d-649">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="7467d-650">Обновления функций Word</span><span class="sxs-lookup"><span data-stu-id="7467d-650">Word Feature updates:</span></span>

- <span data-ttu-id="7467d-651">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="7467d-651">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="7467d-652">**Выразите мысль другими словами.** Если вы хотите выразить мысль по-другому, можно воспользоваться функцией переписывания.</span><span class="sxs-lookup"><span data-stu-id="7467d-652">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="7467d-653">Она предлагает другие варианты, подходящие для ваших фраз.</span><span class="sxs-lookup"><span data-stu-id="7467d-653">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="7467d-654">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="7467d-654">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="7467d-655">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="7467d-655">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="7467d-656">Доступ</span><span class="sxs-lookup"><span data-stu-id="7467d-656">Access</span></span>
- <span data-ttu-id="7467d-657">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-657">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-658">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-658">Excel</span></span>

- <div><span data-ttu-id="7467d-659"><span>Устранена проблема, из-за которой при печати PDF-файлов применялась команда &quot;Повторять все подписи&quot;</span></span><span class="sxs-lookup"><span data-stu-id="7467d-659"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="7467d-660">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7467d-660">Office Suite</span></span>

- <div><span data-ttu-id="7467d-661"><span>Устранена проблема, из-за которой документ иногда не открывался с рабочего стола</span></span><span class="sxs-lookup"><span data-stu-id="7467d-661"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="7467d-662"><span>Устранена проблема с обновлением при получении неправильного сообщения об ошибке &quot;Выполняется другая установка&quot;</span></span><span class="sxs-lookup"><span data-stu-id="7467d-662"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="7467d-663"><span>Устранена проблема, из-за которой появлялись сообщения об ошибке при установке обновлений для системы безопасности</span></span><span class="sxs-lookup"><span data-stu-id="7467d-663"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="7467d-664"><span>Устранена проблема, из-за которой иногда исчезал курсор</span></span><span class="sxs-lookup"><span data-stu-id="7467d-664"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="7467d-665"><span>Устранена проблема, из-за которой по умолчанию открывалась вкладка "Рисование" вместо вкладки "Главная"</span></span><span class="sxs-lookup"><span data-stu-id="7467d-665"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="7467d-666"><span>Устранена проблема, из-за которой представление в виде большого дерева могло привести к сбою</span></span><span class="sxs-lookup"><span data-stu-id="7467d-666"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="7467d-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-667">Outlook</span></span>

- <div></div><span data-ttu-id="7467d-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Устранена проблема, при которой многократно отображался запрос пароля</span></span><span class="sxs-lookup"><span data-stu-id="7467d-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="7467d-669"><span>Устранена проблема, из-за которой создавался неправильный запрос адреса электронной почты</span></span><span class="sxs-lookup"><span data-stu-id="7467d-669"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="7467d-670"><span>Устранена проблема, из-за которой не открывались элементы календаря, созданные в устаревших версиях Outlook</span></span><span class="sxs-lookup"><span data-stu-id="7467d-670"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="7467d-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-671">PowerPoint</span></span>

- <div><span data-ttu-id="7467d-672"><span>Устранена проблема, из-за которой не запускались некоторые анимации</span></span><span class="sxs-lookup"><span data-stu-id="7467d-672"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="7467d-673">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-673">Project</span></span>
- <span data-ttu-id="7467d-674">Устранение проблем с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="7467d-674">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="7467d-675">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-675">Word</span></span>

- <div><span data-ttu-id="7467d-676"><span>Устранена проблема, из-за которой ответы на комментарии отображались не по порядку</span></span><span class="sxs-lookup"><span data-stu-id="7467d-676"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="7467d-677"><span>Устранена проблема, из-за которой в некоторых ситуациях вместо комментариев отображались подсказки</span></span><span class="sxs-lookup"><span data-stu-id="7467d-677"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="7467d-678"><span>Устранена проблема, из-за которой при попытке добавить комментарий отображалась область исправлений</span></span><span class="sxs-lookup"><span data-stu-id="7467d-678"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="7467d-679"><span>Устранена проблема, из-за которой не отображался раскрывающийся список отмены</span></span><span class="sxs-lookup"><span data-stu-id="7467d-679"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="7467d-680"><span>Устранена проблема, из-за которой не удавалось добавить комментарии</span></span><span class="sxs-lookup"><span data-stu-id="7467d-680"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="7467d-681">26 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-681">July 26, 2019</span></span>
<span data-ttu-id="7467d-682">Версия 1908 (сборка 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-682">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-683">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-683">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="7467d-684">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-684">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="7467d-685">Создание более удобных для чтения PDF-документов</span><span class="sxs-lookup"><span data-stu-id="7467d-685">Create more accessible PDFs</span></span>

<span data-ttu-id="7467d-686">Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="7467d-686">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-687">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-687">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-688">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-688">All</span></span>

- <span data-ttu-id="7467d-689">Исправлена проблема, из-за которой при обновлении Office иногда могли возникать ошибки с сопоставлением типов файлов и значками для Office</span><span class="sxs-lookup"><span data-stu-id="7467d-689">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="7467d-690">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-690">Word</span></span> 
- <span data-ttu-id="7467d-691">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-691">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-692">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-692">Excel</span></span>
- <span data-ttu-id="7467d-693">Исправлена проблема, из-за которой перемещение диаграммы иногда могло приводить к сбою</span><span class="sxs-lookup"><span data-stu-id="7467d-693">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="7467d-694">Исправлена проблема, из-за которой получение объекта Workbook из объекта Chart после изменения типов диаграмм иногда могло приводить к ошибке</span><span class="sxs-lookup"><span data-stu-id="7467d-694">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-695">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-695">PowerPoint</span></span>
- <span data-ttu-id="7467d-696">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-696">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-697">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-697">Outlook</span></span>
- <span data-ttu-id="7467d-698">Исправлена проблема, из-за которой на упрощенной ленте отключенный элемент управления иногда не затенялся</span><span class="sxs-lookup"><span data-stu-id="7467d-698">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="7467d-699">Доступ</span><span class="sxs-lookup"><span data-stu-id="7467d-699">Access</span></span>
- <span data-ttu-id="7467d-700">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-700">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-701">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-701">Project</span></span>
- <span data-ttu-id="7467d-702">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-702">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="7467d-703">19 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-703">July 19, 2019</span></span>
<span data-ttu-id="7467d-704">Версия 1908 (сборка 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-704">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-705">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-705">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-706">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-706">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="7467d-707">Изучение значения сокращений при чтении в Word Online</span><span class="sxs-lookup"><span data-stu-id="7467d-707">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="7467d-708">Когда вам попадется сокращение, мы попробуем расшифровать его с помощью данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="7467d-708">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="7467d-709">Важные исправления</span><span class="sxs-lookup"><span data-stu-id="7467d-709">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-710">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-710">Word</span></span> 
- <span data-ttu-id="7467d-711">Исправлена проблема с отсутствием тега BookMarkEnd.</span><span class="sxs-lookup"><span data-stu-id="7467d-711">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="7467d-712">Исправлена проблема с изменением выбранного шрифта при вводе пользователем специальных символов.</span><span class="sxs-lookup"><span data-stu-id="7467d-712">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="7467d-713">Исправлена проблема, из-за которой в новой карточке с комментариями иногда могли появляться пустые ответы.</span><span class="sxs-lookup"><span data-stu-id="7467d-713">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="7467d-714">Исправлена проблема с потерей форматирования при общем доступе к электронной почте.</span><span class="sxs-lookup"><span data-stu-id="7467d-714">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-715">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-715">Excel</span></span>
- <span data-ttu-id="7467d-716">Исправлена проблема, из-за которой массив с большим диапазоном иногда мог вызывать сбой.</span><span class="sxs-lookup"><span data-stu-id="7467d-716">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="7467d-717">Значительно улучшена производительность при копировании данных из отфильтрованных диапазонов.</span><span class="sxs-lookup"><span data-stu-id="7467d-717">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="7467d-718">Исправлена проблема, из-за которой некоторые файлы с именами, содержавшими специальные символы, не открывались.</span><span class="sxs-lookup"><span data-stu-id="7467d-718">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-719">PowerPoint</span></span>
- <span data-ttu-id="7467d-720">Исправлена проблема, из-за которой не присваивалось название раздела вновь созданному разделу в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="7467d-720">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="7467d-721">Исправлена проблема, из-за которой использование пользовательского интерфейса затруднялось при использовании монитора 4:3.</span><span class="sxs-lookup"><span data-stu-id="7467d-721">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-722">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-722">Outlook</span></span>
- <span data-ttu-id="7467d-723">Исправлена проблема, из-за которой доступные помещения могли не отображаться в списке.</span><span class="sxs-lookup"><span data-stu-id="7467d-723">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="7467d-724">Исправлена проблема, из-за которой форматирование HTML для некоторых пользователей POP3 было недоступным.</span><span class="sxs-lookup"><span data-stu-id="7467d-724">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="7467d-725">Доступ</span><span class="sxs-lookup"><span data-stu-id="7467d-725">Access</span></span>
- <span data-ttu-id="7467d-726">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-726">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-727">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-727">Project</span></span>
- <span data-ttu-id="7467d-728">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-728">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="7467d-729">12 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-729">July 12, 2019</span></span>
<span data-ttu-id="7467d-730">Версия 1907 (сборка 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="7467d-730">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-731">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-731">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-732">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-732">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="7467d-733">Воспроизведение рукописного ввода в презентациях</span><span class="sxs-lookup"><span data-stu-id="7467d-733">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="7467d-734">Используйте анимацию воспроизведения для рукописного ввода в PowerPoint для большей наглядности презентаций.</span><span class="sxs-lookup"><span data-stu-id="7467d-734">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="7467d-735">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-735">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-736">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-736">Word</span></span> 
- <span data-ttu-id="7467d-737">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-737">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-738">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-738">Excel</span></span>
- <span data-ttu-id="7467d-739">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-739">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-740">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-740">PowerPoint</span></span>
- <span data-ttu-id="7467d-741">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-741">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-742">Outlook</span></span>
- <span data-ttu-id="7467d-743">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-743">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="7467d-744">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-744">Access</span></span>
- <span data-ttu-id="7467d-745">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-745">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-746">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-746">Project</span></span>
- <span data-ttu-id="7467d-747">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-747">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="7467d-748">5 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-748">July 5, 2019</span></span>
<span data-ttu-id="7467d-749">Версия 1907 (сборка 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="7467d-749">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-750">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-750">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="7467d-751">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-751">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="7467d-752">Фигуры в виде эскиза!</span><span class="sxs-lookup"><span data-stu-id="7467d-752">Sketchy Shapes!</span></span>

<span data-ttu-id="7467d-753">Находитесь в процессе создания презентации?</span><span class="sxs-lookup"><span data-stu-id="7467d-753">In the middle of drafting a presentation?</span></span> <span data-ttu-id="7467d-754">Примените эскизный стиль, чтобы продемонстрировать незавершенность работы.</span><span class="sxs-lookup"><span data-stu-id="7467d-754">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="7467d-755">Это придает индивидуальность вашим объектам, не превращая их в фигуры произвольной формы, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="7467d-755">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-756">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-756">Excel</span></span>

- <span data-ttu-id="7467d-757">**Быстрое предоставление общего доступа к файлам**. Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="7467d-757">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7467d-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-758">PowerPoint</span></span>

- <span data-ttu-id="7467d-759">**Параметр "Печать номеров слайдов на раздаточных материалах" перемещен в меню печати для облегчения доступа.** Он находится в раскрывающемся меню "Печать > Макет печати", когда выбран макет раздаточных материалов.</span><span class="sxs-lookup"><span data-stu-id="7467d-759">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="7467d-760">Это также позволяет легко включать и отключать этот параметр для отдельных презентаций.</span><span class="sxs-lookup"><span data-stu-id="7467d-760">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="7467d-761">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7467d-761">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="7467d-762">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="7467d-762">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-763">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-763">Word</span></span>

- <span data-ttu-id="7467d-764">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="7467d-764">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-765">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-765">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-766">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-766">All</span></span>
- <span data-ttu-id="7467d-767">Значительно улучшена производительность подсказок ленты</span><span class="sxs-lookup"><span data-stu-id="7467d-767">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="7467d-768">Исправлена проблема, мешавшая правильному отображению диалогового окна "Посмотрите, что нового появится в ближайшее время"</span><span class="sxs-lookup"><span data-stu-id="7467d-768">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="7467d-769">Исправлена проблема, которая могла приводить к неправильному выравниванию фотографий во всплывающей коллекции совместной работы</span><span class="sxs-lookup"><span data-stu-id="7467d-769">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="7467d-770">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-770">Word</span></span> 
- <span data-ttu-id="7467d-771">Исправлена проблема, которая иногда могла препятствовать добавлению новых примечаний</span><span class="sxs-lookup"><span data-stu-id="7467d-771">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="7467d-772">Исправлена проблема, из-за которой таблицы иногда могли вызывать сбой</span><span class="sxs-lookup"><span data-stu-id="7467d-772">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="7467d-773">Исправлена проблема, из-за которой иногда могли добавляться недопустимые данные в конец слияния почты</span><span class="sxs-lookup"><span data-stu-id="7467d-773">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="7467d-774">Исправлена проблема, которая могла приводить к неправильному отображению некоторых уравнений LaTeX</span><span class="sxs-lookup"><span data-stu-id="7467d-774">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-775">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-775">Excel</span></span>
- <span data-ttu-id="7467d-776">Исправлена проблема, из-за которой изменение типов диаграмм могло иногда приводить к возникновению исключения во время выполнения</span><span class="sxs-lookup"><span data-stu-id="7467d-776">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="7467d-777">Исправлена проблема с отображением неправильной ленты при открытии нескольких окон</span><span class="sxs-lookup"><span data-stu-id="7467d-777">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="7467d-778">Исправлена проблема, которая могла вызывать ошибку при открытии макросом второго экземпляра книги</span><span class="sxs-lookup"><span data-stu-id="7467d-778">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="7467d-779">Исправлена проблема, которая могла приводить к сбою при открытии книги, создании книги или переключении между книгами</span><span class="sxs-lookup"><span data-stu-id="7467d-779">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="7467d-780">Исправлена проблема, не позволявшая пользователям открыть PDF-файл, созданный из Word в Teams</span><span class="sxs-lookup"><span data-stu-id="7467d-780">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-781">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-781">PowerPoint</span></span>
- <span data-ttu-id="7467d-782">Исправлена проблема, из-за которой могло ухудшаться качество диаграммы при экспорте в PDF-файл</span><span class="sxs-lookup"><span data-stu-id="7467d-782">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="7467d-783">Исправлена проблема, препятствовавшая отображению подсказки с указанием расстояния до центра</span><span class="sxs-lookup"><span data-stu-id="7467d-783">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-784">Outlook</span></span>
- <span data-ttu-id="7467d-785">Исправлена проблема, которая иногда могла мешать отображению ошибки с сообщением о переполнении диска</span><span class="sxs-lookup"><span data-stu-id="7467d-785">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="7467d-786">Исправлена проблема, которая могла приводить к дублированию вложений при обновлении приглашения на собрание</span><span class="sxs-lookup"><span data-stu-id="7467d-786">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="7467d-787">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-787">Access</span></span>
- <span data-ttu-id="7467d-788">Исправлена проблема, препятствовавшая возврату длинных целых значений при некоторых запросах</span><span class="sxs-lookup"><span data-stu-id="7467d-788">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="7467d-789">Исправлена проблема, из-за которой поле SQL могло стать нередактируемым</span><span class="sxs-lookup"><span data-stu-id="7467d-789">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="7467d-790">Исправлена проблема, из-за которой подсказки могло быть плохо видно на экранах с высоким разрешением</span><span class="sxs-lookup"><span data-stu-id="7467d-790">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="7467d-791">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-791">Project</span></span>
- <span data-ttu-id="7467d-792">Исправлена проблема, из-за которой значения флагов могли стать нередактируемыми в новых задачах</span><span class="sxs-lookup"><span data-stu-id="7467d-792">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="7467d-793">Исправлена проблема, которая могла приводить к неправильной установке фактической даты начала в назначениях и задачах при обновлении состояния</span><span class="sxs-lookup"><span data-stu-id="7467d-793">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="7467d-794">Исправлена проблема, которая могла приводить к неправильному отображению превышения доступности для некоторых ресурсов</span><span class="sxs-lookup"><span data-stu-id="7467d-794">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="7467d-795">Исправлена проблема, из-за которой метод добавления объектов TaskDependencies мог завершаться сбоем, если добавлен параметр Lag, десятичным разделителем является запятая и выполнено подключение к серверу</span><span class="sxs-lookup"><span data-stu-id="7467d-795">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="7467d-796">Исправлена проблема, из-за которой обновление значений таблицы подстановки локальных настраиваемых полей через CSOM могло приводить к сбою компьютеров</span><span class="sxs-lookup"><span data-stu-id="7467d-796">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="7467d-797">Исправлена проблема, из-за которой значения общего объема работ могли отображаться неправильно, если они содержали десятичное число</span><span class="sxs-lookup"><span data-stu-id="7467d-797">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="7467d-798">28 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-798">June 28, 2019</span></span>
<span data-ttu-id="7467d-799">Версия 1907 (сборка 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="7467d-799">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-800">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-800">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-801">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-801">Excel</span></span>

- <span data-ttu-id="7467d-802">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="7467d-802">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="7467d-803">Также легко находить функции, столбцы и параметры</span><span class="sxs-lookup"><span data-stu-id="7467d-803">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="7467d-804">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="7467d-804">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-805">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-805">Word</span></span>

- <span data-ttu-id="7467d-806">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="7467d-806">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="7467d-807">Word, Excel, PowerPoint и Visio</span><span class="sxs-lookup"><span data-stu-id="7467d-807">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="7467d-808">Рекомендуемые документы</span><span class="sxs-lookup"><span data-stu-id="7467d-808">Recommended Documents</span></span>

<span data-ttu-id="7467d-809">Находите рекомендуемые вам документы с важными действиями.</span><span class="sxs-lookup"><span data-stu-id="7467d-809">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-810">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-810">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-811">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-811">Word</span></span> 
- <span data-ttu-id="7467d-812">Исправлена проблема, из-за которой не удавалось открыть некоторые DOC-файлы</span><span class="sxs-lookup"><span data-stu-id="7467d-812">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="7467d-813">Исправлена проблема, которая могла мешать правильной загрузке примечаний</span><span class="sxs-lookup"><span data-stu-id="7467d-813">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-814">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-814">Excel</span></span>
- <span data-ttu-id="7467d-815">Улучшена производительность запросов Power Query</span><span class="sxs-lookup"><span data-stu-id="7467d-815">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-816">PowerPoint</span></span>
- <span data-ttu-id="7467d-817">Исправлена проблема, связанная с использованием пера на устройстве Surface, которая могла приводить к мерцанию экрана</span><span class="sxs-lookup"><span data-stu-id="7467d-817">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-818">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-818">Outlook</span></span>
- <span data-ttu-id="7467d-819">Исправлена проблема, из-за которой могло изменяться состояние доступности встречи при преобразовании в собрание</span><span class="sxs-lookup"><span data-stu-id="7467d-819">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="7467d-820">Исправлена проблема с отображением неправильного шаблона и описания, если сообщение защищено с помощью специального шаблона</span><span class="sxs-lookup"><span data-stu-id="7467d-820">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="7467d-821">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-821">Access</span></span>
- <span data-ttu-id="7467d-822">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-822">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-823">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-823">Project</span></span>
- <span data-ttu-id="7467d-824">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-824">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="7467d-825">21 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-825">June 21, 2019</span></span>
<span data-ttu-id="7467d-826">Версия 1907 (сборка 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="7467d-826">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-827">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-827">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-828">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-828">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="7467d-829">Темный режим для черной темы в классическом приложении Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-829">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="7467d-830">Когда используется темный режим, для пользователей, выбравших черную тему, области чтения и создания сообщений теперь также отображаются на темном фоне при чтении и создании сообщений электронной почты соответственно.</span><span class="sxs-lookup"><span data-stu-id="7467d-830">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="7467d-831">В области чтения и на ленте есть переключатель с изображением солнца или луны, позволяющий пользователям предварительно просмотреть сообщение на светлом фоне.</span><span class="sxs-lookup"><span data-stu-id="7467d-831">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-832">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-832">Getting Started:</span></span>

1. <span data-ttu-id="7467d-833">Включите черную тему, и темный режим запустится по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-833">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="7467d-834">Используйте переключатель с изображением луны или солнца (в области чтения и на ленте), чтобы просмотреть оформление сообщения для пользователей, не применяющих темный режим</span><span class="sxs-lookup"><span data-stu-id="7467d-834">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-835">Возможные действия</span><span class="sxs-lookup"><span data-stu-id="7467d-835">Scenarios to Try</span></span>

1. <span data-ttu-id="7467d-836">Читайте сообщения в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="7467d-836">Read emails in dark mode.</span></span> <span data-ttu-id="7467d-837">Если вам не удается что-то прочитать, используйте переключатель с изображением солнца в области чтения, чтобы переключиться на светлый фон.</span><span class="sxs-lookup"><span data-stu-id="7467d-837">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="7467d-838">Создавайте сообщения в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="7467d-838">Compose emails in dark mode.</span></span> <span data-ttu-id="7467d-839">Просматривайте сообщение на светлом фоне с помощью переключателя с изображением солнца на ленте.</span><span class="sxs-lookup"><span data-stu-id="7467d-839">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="7467d-840">Если вы столкнулись с неправильным отображением сообщений, отправьте их (в виде вложения) на адрес электронной почты OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="7467d-840">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="7467d-841">Получение предложений по расположению</span><span class="sxs-lookup"><span data-stu-id="7467d-841">Get location suggestions</span></span>

<span data-ttu-id="7467d-842">Начните ввод текста и Outlook подберет подходящие расположения.</span><span class="sxs-lookup"><span data-stu-id="7467d-842">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="7467d-843">Это применяется к полю "Расположение" при создании встреч и собраний.</span><span class="sxs-lookup"><span data-stu-id="7467d-843">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-844">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-844">Getting Started:</span></span>

- <span data-ttu-id="7467d-845">Создайте встречу или собрание в календаре Outlook в Office 365 или Outlook.com.</span><span class="sxs-lookup"><span data-stu-id="7467d-845">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="7467d-846">Щелкните поле "Расположение" и начните вводить текст...</span><span class="sxs-lookup"><span data-stu-id="7467d-846">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-847">Возможные действия</span><span class="sxs-lookup"><span data-stu-id="7467d-847">Scenarios to Try</span></span>

<span data-ttu-id="7467d-848">При добавлении конференц-зала к собранию щелкните поле "Расположение", а не надстройку "Поиск помещений" или адресную книгу.</span><span class="sxs-lookup"><span data-stu-id="7467d-848">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="7467d-849">Для встреч в общественных местах, например в ресторане, кафе или даже кабинете стоматолога, постарайтесь найти точное расположение с помощью нового средства выбора.</span><span class="sxs-lookup"><span data-stu-id="7467d-849">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="7467d-850">Так вы сможете получать уведомления в Outlook Mobile, когда придет время отправляться в путь.</span><span class="sxs-lookup"><span data-stu-id="7467d-850">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-851">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-851">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-852">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-852">All</span></span>
- <span data-ttu-id="7467d-853">Исправлена проблема, из-за которой поле поиска могло оставаться активным в автономном режиме</span><span class="sxs-lookup"><span data-stu-id="7467d-853">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="7467d-854">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-854">Word</span></span> 
- <span data-ttu-id="7467d-855">Исправлена проблема, из-за которой иногда трудно было увидеть фокус клавиатуры</span><span class="sxs-lookup"><span data-stu-id="7467d-855">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="7467d-856">Исправлена проблема, из-за которой текст, вставлявшийся в новый документ, иногда мог выравниваться неправильно</span><span class="sxs-lookup"><span data-stu-id="7467d-856">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="7467d-857">Исправлена проблема, из-за которой некоторым пользователям не удавалось сохранять изменения после приостановки работы компьютера</span><span class="sxs-lookup"><span data-stu-id="7467d-857">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="7467d-858">Исправлена проблема, из-за которой в некоторых случаях печатался весь документ вместо выбранного диапазона</span><span class="sxs-lookup"><span data-stu-id="7467d-858">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="7467d-859">Исправлена проблема, которая могла затруднять чтение примечаний на небольших экранах</span><span class="sxs-lookup"><span data-stu-id="7467d-859">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="7467d-860">Исправлена проблема, которая могла приводить к сбою при записи на устройство</span><span class="sxs-lookup"><span data-stu-id="7467d-860">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-861">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-861">Excel</span></span>
- <span data-ttu-id="7467d-862">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-862">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-863">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-863">PowerPoint</span></span>
- <span data-ttu-id="7467d-864">Исправлена проблема, из-за которой иногда трудно было увидеть фокус клавиатуры</span><span class="sxs-lookup"><span data-stu-id="7467d-864">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-865">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-865">Outlook</span></span>
- <span data-ttu-id="7467d-866">Исправлена проблема, из-за которой надстройка могла неправильно отображаться как включенная, хотя она выключена.</span><span class="sxs-lookup"><span data-stu-id="7467d-866">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="7467d-867">Исправлена проблема, не позволявшая пользователю просматривать все политики хранения, если их много</span><span class="sxs-lookup"><span data-stu-id="7467d-867">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="7467d-868">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-868">Access</span></span>
- <span data-ttu-id="7467d-869">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-869">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-870">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-870">Project</span></span>
- <span data-ttu-id="7467d-871">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-871">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="7467d-872">14 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-872">June 14, 2019</span></span>
<span data-ttu-id="7467d-873">Версия 1907 (сборка 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-873">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-874">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-874">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-875">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-875">Word</span></span> 
- <span data-ttu-id="7467d-876">Исправлена проблема, которая могла препятствовать входу пользователя при сохранении в OneDrive</span><span class="sxs-lookup"><span data-stu-id="7467d-876">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="7467d-877">Исправлена проблема, из-за которой пользователю могло быть запрещено изменять свойства SharePoint в режиме ограниченного доступа</span><span class="sxs-lookup"><span data-stu-id="7467d-877">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="7467d-878">Исправлена проблема, из-за которой содержимое колонтитулов могло меняться при изменении полей</span><span class="sxs-lookup"><span data-stu-id="7467d-878">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="7467d-879">Исправлена проблема, из-за которой форматирование могло разрываться при переходе в веб-представление</span><span class="sxs-lookup"><span data-stu-id="7467d-879">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="7467d-880">Исправлена проблема, которая могла помешать пользователю использовать настраиваемые поля при открытии из SharePoint</span><span class="sxs-lookup"><span data-stu-id="7467d-880">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-881">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-881">Excel</span></span>
- <span data-ttu-id="7467d-882">Исправлена проблема с производительностью при удалении строк отфильтрованного набора</span><span class="sxs-lookup"><span data-stu-id="7467d-882">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="7467d-883">Исправлена проблема, которая могла иногда вызывать мерцание указателя мыши в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="7467d-883">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="7467d-884">Устранена проблема, которая могла приводить к сбою при удалении ряда</span><span class="sxs-lookup"><span data-stu-id="7467d-884">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="7467d-885">Исправлена проблема, из-за которой некоторым пользователям предоставлялась возможность добавить журнал версий, когда он недоступен</span><span class="sxs-lookup"><span data-stu-id="7467d-885">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="7467d-886">Исправлена проблема, которая могла приводить к возникновению исключения при использовании средства сравнения электронных таблиц</span><span class="sxs-lookup"><span data-stu-id="7467d-886">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-887">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-887">PowerPoint</span></span>
- <span data-ttu-id="7467d-888">Устранена проблема, из-за которой мог происходить сбой при переходе по ссылке к SharePoint</span><span class="sxs-lookup"><span data-stu-id="7467d-888">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="7467d-889">Исправлена проблема, из-за которой пользователь мог переключаться на следующую страницу при вводе с помощью ручки Surface</span><span class="sxs-lookup"><span data-stu-id="7467d-889">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-890">Outlook</span></span>
- <span data-ttu-id="7467d-891">Исправлена проблема, из-за которой в некоторых случаях поле "Кому" отображалось увеличенным</span><span class="sxs-lookup"><span data-stu-id="7467d-891">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="7467d-892">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-892">Access</span></span>
- <span data-ttu-id="7467d-893">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-893">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-894">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-894">Project</span></span>
- <span data-ttu-id="7467d-895">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-895">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="7467d-896">7 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-896">June 7, 2019</span></span>
<span data-ttu-id="7467d-897">Версия 1907 (сборка 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="7467d-897">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-898">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-898">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-899">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-899">Word</span></span> 
- <span data-ttu-id="7467d-900">Исправлена проблема, из-за которой возникал сбой в работе Word при автозамене первой буквы предложения на прописную</span><span class="sxs-lookup"><span data-stu-id="7467d-900">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="7467d-901">Улучшена производительность при редактировании документа в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="7467d-901">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="7467d-902">Исправлена проблема, из-за которой неправильно отображались векторные изображения, созданные в Adobe Illustrator</span><span class="sxs-lookup"><span data-stu-id="7467d-902">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-903">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-903">Excel</span></span>
- <span data-ttu-id="7467d-904">Исправлена проблема, из-за которой поля сортировки могли быть неправильно установлены при записи макроса</span><span class="sxs-lookup"><span data-stu-id="7467d-904">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="7467d-905">Исправлена проблема, приводящая к зависанию или сбою при пересчете формулы массива</span><span class="sxs-lookup"><span data-stu-id="7467d-905">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-906">PowerPoint</span></span>
- <span data-ttu-id="7467d-907">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-907">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-908">Outlook</span></span>
- <span data-ttu-id="7467d-909">Исправлена проблема, из-за которой встроенные вложения иногда имели неправильный масштаб</span><span class="sxs-lookup"><span data-stu-id="7467d-909">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="7467d-910">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-910">Access</span></span>
- <span data-ttu-id="7467d-911">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-911">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-912">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-912">Project</span></span>
- <span data-ttu-id="7467d-913">Исправлена проблема, из-за которой в расписании заданий с фиксированной длительностью может изменяться дата окончания</span><span class="sxs-lookup"><span data-stu-id="7467d-913">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="7467d-914">Исправлена проблема, из-за которой могло неправильно отображаться значение процента выполнения при открытии проекта из более ранней версии</span><span class="sxs-lookup"><span data-stu-id="7467d-914">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="7467d-915">31 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-915">May 31, 2019</span></span>
<span data-ttu-id="7467d-916">Версия 1906 (сборка 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="7467d-916">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-917">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-918">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="7467d-919">Диалоговое окно обращения в службу поддержки теперь закрепляется и отображается справа</span><span class="sxs-lookup"><span data-stu-id="7467d-919">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="7467d-920">Диалоговое окно, используемое для обращения в службу поддержки, отображается в области справа и выводится как закрепленное окно.</span><span class="sxs-lookup"><span data-stu-id="7467d-920">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="7467d-921">Рукописный ввод в вашем электронном письме!</span><span class="sxs-lookup"><span data-stu-id="7467d-921">Ink in Your Email!</span></span>

<span data-ttu-id="7467d-922">В сообщениях электронной почты Outlook теперь можно рисовать и создавать примечания к изображениям.</span><span class="sxs-lookup"><span data-stu-id="7467d-922">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-923">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-923">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="7467d-924">Открытие ссылок на документы в Word</span><span class="sxs-lookup"><span data-stu-id="7467d-924">Open document links in Word</span></span>

<span data-ttu-id="7467d-925">При переходе по ссылке на документ в Office вы можете изменить параметр, чтобы открывать его в приложении Word по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-925">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="7467d-926">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="7467d-926">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="7467d-927">Подробнее: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="7467d-927">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-928">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-928">Getting Started:</span></span>

<span data-ttu-id="7467d-929">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-929">Feature will default to off.</span></span> <span data-ttu-id="7467d-930">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="7467d-930">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="7467d-931">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-931">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="7467d-932">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="7467d-932">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="7467d-933">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="7467d-933">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="7467d-934">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="7467d-934">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-935">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-935">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-936">Чтобы запустить интерфейс согласия на открытие ссылки на документ Word, хранящийся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="7467d-936">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="7467d-937">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="7467d-937">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-938">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-938">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="7467d-939">Открытие ссылок на презентации в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-939">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="7467d-940">При переходе по ссылке на презентацию в Office вы можете изменить параметр, чтобы открывать ее в приложении PowerPoint по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-940">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="7467d-941">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="7467d-941">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="7467d-942">Подробнее: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="7467d-942">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-943">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-943">Getting Started:</span></span>

<span data-ttu-id="7467d-944">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-944">Feature will default to off.</span></span> <span data-ttu-id="7467d-945">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="7467d-945">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="7467d-946">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-946">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="7467d-947">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="7467d-947">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="7467d-948">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="7467d-948">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="7467d-949">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="7467d-949">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-950">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-950">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-951">Чтобы запустить интерфейс согласия на открытие ссылки на презентацию PowerPoint, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="7467d-951">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="7467d-952">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="7467d-952">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-953">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-953">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="7467d-954">Открытие ссылок на книги в Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-954">Open workbook links in Excel</span></span>

<span data-ttu-id="7467d-955">При переходе по ссылке на книгу в Office вы можете изменить параметр, чтобы открывать ее в приложении Excel по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-955">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="7467d-956">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="7467d-956">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="7467d-957">Подробнее: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="7467d-957">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-958">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-958">Getting Started:</span></span>

<span data-ttu-id="7467d-959">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-959">Feature will default to off.</span></span> <span data-ttu-id="7467d-960">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="7467d-960">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="7467d-961">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="7467d-961">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="7467d-962">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="7467d-962">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="7467d-963">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="7467d-963">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="7467d-964">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="7467d-964">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-965">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-965">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-966">Чтобы запустить интерфейс согласия на открытие ссылки на книгу Excel, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="7467d-966">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="7467d-967">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="7467d-967">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-968">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-968">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-969">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-969">All</span></span>
- <span data-ttu-id="7467d-970">Исправлена проблема, из-за которой файлы иногда автоматически сохранялись даже при отключенной функции автоматического сохранения.</span><span class="sxs-lookup"><span data-stu-id="7467d-970">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="7467d-971">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-971">Word</span></span> 
- <span data-ttu-id="7467d-972">Исправлена ошибка, которая могла не позволять некоторым пользователям сохранять файлы в SharePoint</span><span class="sxs-lookup"><span data-stu-id="7467d-972">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-973">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-973">Excel</span></span>
- <span data-ttu-id="7467d-974">Исправлена проблема с возможным отображением неправильного значка для неактивных фильтров</span><span class="sxs-lookup"><span data-stu-id="7467d-974">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-975">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-975">PowerPoint</span></span>
- <span data-ttu-id="7467d-976">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-976">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-977">Outlook</span></span>
- <span data-ttu-id="7467d-978">Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span><span class="sxs-lookup"><span data-stu-id="7467d-978">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="7467d-979">Исправлена проблема, не позволявшая функции безопасных ссылок анализировать URL-адрес с конечным пробелом</span><span class="sxs-lookup"><span data-stu-id="7467d-979">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="7467d-980">Устранена проблема, из-за которой помещения отображались доступными за пределами нерабочего времени</span><span class="sxs-lookup"><span data-stu-id="7467d-980">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="7467d-981">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-981">Access</span></span>
- <span data-ttu-id="7467d-982">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-982">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-983">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-983">Project</span></span>
- <span data-ttu-id="7467d-984">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-984">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="7467d-985">24 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-985">May 24, 2019</span></span>
<span data-ttu-id="7467d-986">Версия 1906 (сборка 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="7467d-986">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-987">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-987">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="7467d-988">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="7467d-988">User Experience Updates</span></span>

<span data-ttu-id="7467d-989">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="7467d-989">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-990">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-990">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-991">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-991">All</span></span>

- <span data-ttu-id="7467d-992">Исправлена проблема, из-за которой не отображалась область чата</span><span class="sxs-lookup"><span data-stu-id="7467d-992">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="7467d-993">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-993">Word</span></span> 
- <span data-ttu-id="7467d-994">Исправлена проблема, из-за которой в некоторых случаях приложение Word могло неправильно выделять текст на наличие грамматических ошибок</span><span class="sxs-lookup"><span data-stu-id="7467d-994">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-995">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-995">Excel</span></span>
- <span data-ttu-id="7467d-996">Исправлена проблема, из-за которой применялся неправильный значок для элементов диаграммы</span><span class="sxs-lookup"><span data-stu-id="7467d-996">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="7467d-997">Исправлена проблема, приводившая к активации неверной книги в скрипте VBA, если эта книга уже открыта</span><span class="sxs-lookup"><span data-stu-id="7467d-997">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-998">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-998">PowerPoint</span></span>
- <span data-ttu-id="7467d-999">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-999">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1000">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1000">Outlook</span></span>
- <span data-ttu-id="7467d-1001">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1001">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1002">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1002">Access</span></span>
- <span data-ttu-id="7467d-1003">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1003">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1004">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1004">Project</span></span>
- <span data-ttu-id="7467d-1005">Устранена ошибка, при которой приложение Project аварийно завершало работу после перехода на панель задач</span><span class="sxs-lookup"><span data-stu-id="7467d-1005">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="7467d-1006">17 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1006">May 17, 2019</span></span>
<span data-ttu-id="7467d-1007">Версия 1906 (сборка 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="7467d-1007">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1008">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1008">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1009">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="7467d-1010">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="7467d-1010">User Experience Updates</span></span>

<span data-ttu-id="7467d-1011">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="7467d-1011">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1012">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1012">Getting Started:</span></span>

<span data-ttu-id="7467d-1013">Эти изменения относятся к новому стандартному пользовательскому интерфейсу; он был доступен с помощью переключателя "Ожидается в ближайшее время" с середины декабря для 100 % рабочих сред</span><span class="sxs-lookup"><span data-stu-id="7467d-1013">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="7467d-1014">Настраиваемая упрощенная лента</span><span class="sxs-lookup"><span data-stu-id="7467d-1014">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="7467d-1015">Возможность простой настройки для переключения между классическим и упрощенным представлением, а также для закрепления и открепления команд.</span><span class="sxs-lookup"><span data-stu-id="7467d-1015">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1016">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1016">Getting Started:</span></span>

<span data-ttu-id="7467d-1017">Пользователи могут перейти к упрощенной ленте, включив переключатель "Ожидается в ближайшее время" (изначально) и щелкнув шеврон на ленте, чтобы переключаться между классической многострочной и новой упрощенной однострочной лентой.</span><span class="sxs-lookup"><span data-stu-id="7467d-1017">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1018">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1018">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1019">Переключение с классической на упрощенную ленту</span><span class="sxs-lookup"><span data-stu-id="7467d-1019">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="7467d-1020">Выбор избранного действия</span><span class="sxs-lookup"><span data-stu-id="7467d-1020">Pick your favorite action</span></span>

<span data-ttu-id="7467d-1021">Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="7467d-1021">Don't use Flag and Delete?</span></span> <span data-ttu-id="7467d-1022">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="7467d-1022">How about Archive or Mark as Read?</span></span> <span data-ttu-id="7467d-1023">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="7467d-1023">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1024">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1024">Getting Started:</span></span>

<span data-ttu-id="7467d-1025">Чтобы выбрать быстрые действия, щелкните правой кнопкой мыши сообщение в списке для отображения контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="7467d-1025">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="7467d-1026">Затем выберите пункт "Задать быстрые действия"</span><span class="sxs-lookup"><span data-stu-id="7467d-1026">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1027">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1027">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1028">Изменение используемых по умолчанию действий "Пометить" и "Удалить" на "Архивировать", "Переместить", "Пометить как прочитанные" или "Отсутствует" для уменьшения элементов в списке сообщений</span><span class="sxs-lookup"><span data-stu-id="7467d-1028">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="7467d-1029">Выбор свободного или компактного макета</span><span class="sxs-lookup"><span data-stu-id="7467d-1029">Relaxed or tighter layout?</span></span> <span data-ttu-id="7467d-1030">по своему усмотрению</span><span class="sxs-lookup"><span data-stu-id="7467d-1030">You choose</span></span>

<span data-ttu-id="7467d-1031">С помощью компактных интервалов можно выбрать дополнительное пространство между элементами или более сжатый макет, чтобы увидеть больше элементов.</span><span class="sxs-lookup"><span data-stu-id="7467d-1031">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1032">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1032">Getting Started:</span></span>

<span data-ttu-id="7467d-1033">Вкладка "Вид", флажок "Уменьшить интервал" в группе "Сообщения" для классической ленты и параметры текущего представления для упрощенной ленты</span><span class="sxs-lookup"><span data-stu-id="7467d-1033">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1034">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1034">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1035">Использование Outlook для просмотра и создания сообщений с включенным и отключенным параметром.</span><span class="sxs-lookup"><span data-stu-id="7467d-1035">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="7467d-1036">При включенном параметре "Уменьшить интервал" на странице располагается больше сообщений, а элементы управления в формах создания упрощаются.</span><span class="sxs-lookup"><span data-stu-id="7467d-1036">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="7467d-1037">Дедупликация недавно использовавшихся записей при применении клиента синхронизации OneDrive</span><span class="sxs-lookup"><span data-stu-id="7467d-1037">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="7467d-1038">Улучшите интеграцию с клиентом синхронизации OneDrive с помощью облачных вложений, выполнив дедупликацмию недавно использовавшихся записей, обеспечивающую ускорение вложения в виде копии для синхронизированных данных</span><span class="sxs-lookup"><span data-stu-id="7467d-1038">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1039">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1039">Getting Started:</span></span>

<span data-ttu-id="7467d-1040">При использовании клиента синхронизации OneDrive дубликаты больше не отображаются в меню последних выбиравшихся для вложений файлов.</span><span class="sxs-lookup"><span data-stu-id="7467d-1040">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1041">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1041">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1042">Включение клиента синхронизации OneDrive и использование меню "Вложить файл" в классической версии Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1042">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="7467d-1043">Улучшенная синхронизация общих папок для почтовых ящиков с большим числом папок</span><span class="sxs-lookup"><span data-stu-id="7467d-1043">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="7467d-1044">В течение нескольких лет при синхронизации общих почтовых ящиков в приложении Outlook существовало ограничение не более 500 папок.</span><span class="sxs-lookup"><span data-stu-id="7467d-1044">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="7467d-1045">В результате этого изменения при синхронизации в Outlook больше не будет применяться это ограничение в 500 папок.</span><span class="sxs-lookup"><span data-stu-id="7467d-1045">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1046">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1046">Getting Started:</span></span>

<span data-ttu-id="7467d-1047">Создайте в почтовом ящике 1000 папок, предоставьте другому пользователю доступ к почтовому ящику, создайте профиль Outlook для "другого пользователя" и убедитесь в выполнении синхронизации.</span><span class="sxs-lookup"><span data-stu-id="7467d-1047">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1048">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1048">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="7467d-1049">Стереть лишь небольшую часть</span><span class="sxs-lookup"><span data-stu-id="7467d-1049">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1050">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1050">Getting Started:</span></span>

<span data-ttu-id="7467d-1051">Откройте вкладку "Рисование". Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="7467d-1051">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="7467d-1052">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="7467d-1052">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1053">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1053">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1054">Откройте вкладку "Рисование". Выберите перо.</span><span class="sxs-lookup"><span data-stu-id="7467d-1054">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="7467d-1055">Нанесите росчерк пером.</span><span class="sxs-lookup"><span data-stu-id="7467d-1055">Draw an ink stroke.</span></span> <span data-ttu-id="7467d-1056">Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="7467d-1056">Select the Eraser dropdown.</span></span> <span data-ttu-id="7467d-1057">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="7467d-1057">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="7467d-1058">Сотрите лишь небольшую часть росчерка пера.</span><span class="sxs-lookup"><span data-stu-id="7467d-1058">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1059">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-1060">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-1060">All</span></span> 
- <span data-ttu-id="7467d-1061">Исправлена проблема, из-за которой некоторым пользователям могло не удаваться сохранять файлы в формате PDF</span><span class="sxs-lookup"><span data-stu-id="7467d-1061">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="7467d-1062">Исправлена проблема, которая могла влиять на сохранение пользователями больших файлов в 32-разрядной системе</span><span class="sxs-lookup"><span data-stu-id="7467d-1062">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1063">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1063">Word</span></span> 
- <span data-ttu-id="7467d-1064">Значительно повышена скорость реагирования функции диктовки</span><span class="sxs-lookup"><span data-stu-id="7467d-1064">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1065">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1065">Excel</span></span>
- <span data-ttu-id="7467d-1066">Исправлена проблема, из-за которой события двойного щелчка могли не срабатывать на устройствах с сенсорным экраном</span><span class="sxs-lookup"><span data-stu-id="7467d-1066">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="7467d-1067">Исправлена проблема, которая могла блокировать для некоторых пользователей редактирование макросов VBA</span><span class="sxs-lookup"><span data-stu-id="7467d-1067">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="7467d-1068">Исправлена проблема, которая могла влиять на производительность при использовании срезов</span><span class="sxs-lookup"><span data-stu-id="7467d-1068">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1069">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1069">PowerPoint</span></span>
- <span data-ttu-id="7467d-1070">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1070">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1071">Outlook</span></span>
- <span data-ttu-id="7467d-1072">Исправлена проблема, из-за которой неверный шаблон мог отображаться среди выбранных</span><span class="sxs-lookup"><span data-stu-id="7467d-1072">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1073">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1073">Access</span></span>
- <span data-ttu-id="7467d-1074">Исправлена проблема, из-за которой могло быть затруднено чтение текста при использовании построителя масштаба для отображения длинного форматированного текста</span><span class="sxs-lookup"><span data-stu-id="7467d-1074">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1075">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1075">Project</span></span>
- <span data-ttu-id="7467d-1076">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1076">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="7467d-1077">10 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1077">May 10, 2019</span></span>
<span data-ttu-id="7467d-1078">Версия 1906 (сборка 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-1078">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1079">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1079">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1080">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1080">Outlook</span></span>

<span data-ttu-id="7467d-1081">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="7467d-1081">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1082">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1082">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-1083">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-1083">All</span></span>
- <span data-ttu-id="7467d-1084">Исправлена проблема, из-за которой диалоговое окно "Сохранить как" могло отображать неправильный путь</span><span class="sxs-lookup"><span data-stu-id="7467d-1084">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1085">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1085">Word</span></span> 
- <span data-ttu-id="7467d-1086">Исправлена проблема, из-за которой не вставлялись некоторые выбранные элементы из области "Что вы хотите сделать?"</span><span class="sxs-lookup"><span data-stu-id="7467d-1086">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1087">Excel</span></span>
- <span data-ttu-id="7467d-1088">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1088">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1089">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1089">PowerPoint</span></span>
- <span data-ttu-id="7467d-1090">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1090">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1091">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1091">Outlook</span></span>
- <span data-ttu-id="7467d-1092">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1092">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1093">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1093">Access</span></span>
- <span data-ttu-id="7467d-1094">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1094">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1095">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1095">Project</span></span>
- <span data-ttu-id="7467d-1096">Исправлена проблема, из-за которой могло требоваться выделение для просмотра идентификатора задачи</span><span class="sxs-lookup"><span data-stu-id="7467d-1096">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="7467d-1097">3 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1097">May 3, 2019</span></span>
<span data-ttu-id="7467d-1098">Версия 1906 (сборка 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="7467d-1098">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1099">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1099">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1100">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1100">Outlook</span></span>

<span data-ttu-id="7467d-1101">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="7467d-1101">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1102">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1102">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="7467d-1103">Все</span><span class="sxs-lookup"><span data-stu-id="7467d-1103">All</span></span>
- <span data-ttu-id="7467d-1104">Исправлена ошибка, из-за которой у некоторых пользователей возникали проблемы с синхронизацией OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="7467d-1104">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1105">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1105">Word</span></span> 
- <span data-ttu-id="7467d-1106">Исправлена ошибка, из-за которой в некоторых случаях запуск Word занимал много времени</span><span class="sxs-lookup"><span data-stu-id="7467d-1106">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1107">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1107">Excel</span></span>
- <span data-ttu-id="7467d-1108">Исправлена проблема, из-за которой внешние ссылки иногда удалялись из книг после обновления до более новой версии Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1108">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="7467d-1109">Исправлена проблема, из-за которой у некоторых пользователей могли возникать сложности с выделением ячеек в новой книге</span><span class="sxs-lookup"><span data-stu-id="7467d-1109">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1110">PowerPoint</span></span>
- <span data-ttu-id="7467d-1111">Исправлена проблема, из-за которой при преобразовании рисунков в текст неправильно согласовывались размеры шрифтов</span><span class="sxs-lookup"><span data-stu-id="7467d-1111">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1112">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1112">Outlook</span></span>
- <span data-ttu-id="7467d-1113">Исправлена проблема, из-за которой сохранение контакта из VCF-файла могло привести к получению пустых полей</span><span class="sxs-lookup"><span data-stu-id="7467d-1113">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="7467d-1114">Исправлена проблема, из-за которой сообщение могло оставаться в папке "Исходящие", хотя оно было отправлено</span><span class="sxs-lookup"><span data-stu-id="7467d-1114">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="7467d-1115">Исправлена проблема с аварийным завершением работы Outlook при просмотре сообщения DRM</span><span class="sxs-lookup"><span data-stu-id="7467d-1115">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1116">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1116">Access</span></span>
- <span data-ttu-id="7467d-1117">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1118">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1118">Project</span></span>
- <span data-ttu-id="7467d-1119">Устранена ошибка, при которой редактор менялся с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="7467d-1119">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="7467d-1120">Устранена проблема, из-за которой неопубликованные задачи могли отображаться в опубликованной копии главного проекта</span><span class="sxs-lookup"><span data-stu-id="7467d-1120">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="7467d-1121">26 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1121">April 26, 2019</span></span>
<span data-ttu-id="7467d-1122">Версия 1905 (сборка 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="7467d-1122">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="7467d-1123">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="7467d-1123">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1124">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1124">Outlook</span></span>

<span data-ttu-id="7467d-1125">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="7467d-1125">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="7467d-1126">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="7467d-1126">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1127">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="7467d-1128">Улучшенные возможности совместного редактирования</span><span class="sxs-lookup"><span data-stu-id="7467d-1128">Coauthoring improvements</span></span>

<span data-ttu-id="7467d-1129">Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="7467d-1129">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="7467d-1130">Visio</span><span class="sxs-lookup"><span data-stu-id="7467d-1130">Visio</span></span>

- <span data-ttu-id="7467d-1131">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="7467d-1131">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1132">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1132">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1133">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1133">Word</span></span> 
- <span data-ttu-id="7467d-1134">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1134">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1135">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1135">Excel</span></span>
- <span data-ttu-id="7467d-1136">Устранена проблема, которая приводила к невозможности запуска макросов надстройки "Поиск решения"</span><span class="sxs-lookup"><span data-stu-id="7467d-1136">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="7467d-1137">Устранена проблема, которая могла препятствовать импорту файлов Excel в SharePoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1137">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1138">PowerPoint</span></span>
- <span data-ttu-id="7467d-1139">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1139">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1140">Outlook</span></span>
- <span data-ttu-id="7467d-1141">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1141">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1142">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1142">Access</span></span>
- <span data-ttu-id="7467d-1143">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1143">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1144">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1144">Project</span></span>
- <span data-ttu-id="7467d-1145">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1145">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="7467d-1146">19 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1146">April 19, 2019</span></span>
<span data-ttu-id="7467d-1147">Версия 1905 (сборка 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="7467d-1147">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1148">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1148">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1149">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1149">Outlook</span></span>

<span data-ttu-id="7467d-1150">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="7467d-1150">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1151">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1151">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="7467d-1152">Улучшенный интерфейс картограмм с использованием типов данных</span><span class="sxs-lookup"><span data-stu-id="7467d-1152">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="7467d-1153">Эта возможность является улучшением для пользователей, создающих картограммы с использованием географических типов данных Excel.</span><span class="sxs-lookup"><span data-stu-id="7467d-1153">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="7467d-1154">Преимущество для пользователей заключается в более глубокой интеграции функций и повышенной точности в области, которую пользователь хочет отобразить на карте.</span><span class="sxs-lookup"><span data-stu-id="7467d-1154">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="7467d-1155">Дополнительные преимущества включают возможность нанесения на карту многоугольников городов.</span><span class="sxs-lookup"><span data-stu-id="7467d-1155">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="7467d-1156">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1156">Getting Started:</span></span>

- <span data-ttu-id="7467d-1157">Эта возможность является улучшением существующих функций в Excel.</span><span class="sxs-lookup"><span data-stu-id="7467d-1157">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="7467d-1158">Чтобы использовать улучшение, преобразуйте расположения в объекты Rich и выполните построение с помощью картограмм.</span><span class="sxs-lookup"><span data-stu-id="7467d-1158">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1159">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1159">Scenarios to Try:</span></span>

- <span data-ttu-id="7467d-1160">Пользователи могут попробовать указать на картах города, регионы, районы, страны и почтовые индексы.</span><span class="sxs-lookup"><span data-stu-id="7467d-1160">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="7467d-1161">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1161">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="7467d-1162">Все приложения</span><span class="sxs-lookup"><span data-stu-id="7467d-1162">All Applications</span></span>
- <span data-ttu-id="7467d-1163">Исправлена ошибка, из-за которой диалоговое окно первого запуска отображалось при каждом запуске приложения</span><span class="sxs-lookup"><span data-stu-id="7467d-1163">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="7467d-1164">Исправлена ошибка с возможным отсутствием ссылки SharePoint в диалоговом окне "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="7467d-1164">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="7467d-1165">Исправлена ошибка, из-за которой для пользователей неправильно отображалось диалоговое окно "Восстановить"</span><span class="sxs-lookup"><span data-stu-id="7467d-1165">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1166">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1166">Word</span></span> 
- <span data-ttu-id="7467d-1167">Исправлена ошибка, из-за которой у некоторых пользователей могла возникать ошибка с сообщением о недостатке памяти или места на диске при запросе шрифта</span><span class="sxs-lookup"><span data-stu-id="7467d-1167">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="7467d-1168">Исправлена ошибка, из-за которой мог теряться фокус окна при переходе из области примечаний</span><span class="sxs-lookup"><span data-stu-id="7467d-1168">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1169">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1169">Excel</span></span>
- <span data-ttu-id="7467d-1170">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1170">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1171">PowerPoint</span></span>
- <span data-ttu-id="7467d-1172">Исправлена ошибка, не позволявшая изменять размер фигур с фирменной символикой</span><span class="sxs-lookup"><span data-stu-id="7467d-1172">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="7467d-1173">Исправлена ошибка, из-за которой приложение PowerPoint могло аварийно завершать работу при открытии файла в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="7467d-1173">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1174">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1174">Outlook</span></span>
- <span data-ttu-id="7467d-1175">Исправлена ошибка, не позволявшая некоторым пользователям выделять китайские слова</span><span class="sxs-lookup"><span data-stu-id="7467d-1175">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="7467d-1176">Исправлена ошибка с неправильным вычислением сроков действия</span><span class="sxs-lookup"><span data-stu-id="7467d-1176">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1177">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1177">Access</span></span>
- <span data-ttu-id="7467d-1178">Исправлена ошибка, не позволявшая некоторым пользователям применять построитель макросов</span><span class="sxs-lookup"><span data-stu-id="7467d-1178">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="7467d-1179">Исправлена ошибка, из-за которой при печати отчета печаталась только первая страница</span><span class="sxs-lookup"><span data-stu-id="7467d-1179">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="7467d-1180">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при наведении указателя на гиперссылку</span><span class="sxs-lookup"><span data-stu-id="7467d-1180">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="7467d-1181">Исправлена проблема, приводившая к отображению некоторых элементов вне экрана при использовании представления "Схема данных"</span><span class="sxs-lookup"><span data-stu-id="7467d-1181">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1182">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1182">Project</span></span>
- <span data-ttu-id="7467d-1183">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1183">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="7467d-1184">12 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1184">April 12, 2019</span></span>
<span data-ttu-id="7467d-1185">Версия 1905 (сборка 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="7467d-1185">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1186">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1186">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1187">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1187">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="7467d-1188">Получение интеллектуальных данных с помощью Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="7467d-1188">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="7467d-1189">Импортируйте интеллектуальные данные или ссылайтесь на них и взгляните по-новому на свою классическую базу данных с помощью интеллектуальных технологий.</span><span class="sxs-lookup"><span data-stu-id="7467d-1189">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1190">Важные исправления</span><span class="sxs-lookup"><span data-stu-id="7467d-1190">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="7467d-1191">Все приложения</span><span class="sxs-lookup"><span data-stu-id="7467d-1191">All Applications</span></span>
 - <span data-ttu-id="7467d-1192">Исправлена ошибка, не позволявшая некоторым пользователям сохранять файлы в облачных расположениях</span><span class="sxs-lookup"><span data-stu-id="7467d-1192">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="7467d-1193">Исправлена ошибка, из-за которой могла открываться неправильная область из ленты</span><span class="sxs-lookup"><span data-stu-id="7467d-1193">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1194">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1194">Word</span></span> 
- <span data-ttu-id="7467d-1195">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1195">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1196">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1196">Excel</span></span>
- <span data-ttu-id="7467d-1197">Исправлена ошибка, из-за которой для пользователей отображалось сообщение об ошибке, относящееся к связанным типам данных, если книга не содержала связанные типы данных</span><span class="sxs-lookup"><span data-stu-id="7467d-1197">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="7467d-1198">Исправлена ошибка, из-за которой URL-ссылки в документе Word могли изменяться в зависимости от способа просмотра (локально или в Интернете)</span><span class="sxs-lookup"><span data-stu-id="7467d-1198">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1199">PowerPoint</span></span>
- <span data-ttu-id="7467d-1200">Исправлена ошибка, из-за которой мог происходить сбой приложения после отмены всех изменений на вкладке "Анимация"</span><span class="sxs-lookup"><span data-stu-id="7467d-1200">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1201">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1201">Outlook</span></span>
- <span data-ttu-id="7467d-1202">Исправлена ошибка, не позволявшая некоторым пользователям изменять поле "Заметки" для контактов в общедоступной папке</span><span class="sxs-lookup"><span data-stu-id="7467d-1202">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="7467d-1203">Исправлена ошибка, из-за которой мог возникать конфликт между датами окончания срока действия и датами удаления</span><span class="sxs-lookup"><span data-stu-id="7467d-1203">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1204">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1204">Access</span></span>
- <span data-ttu-id="7467d-1205">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1205">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1206">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1206">Project</span></span>
- <span data-ttu-id="7467d-1207">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1207">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="7467d-1208">5 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1208">April 5, 2019</span></span>
<span data-ttu-id="7467d-1209">Версия 1904 (сборка 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="7467d-1209">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1210">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1210">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1211">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1211">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="7467d-1212">Outlook для Windows: настройка параметров сортировки почты и предоставление к ним общего доступа</span><span class="sxs-lookup"><span data-stu-id="7467d-1212">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="7467d-1213">Ваши параметры сортировки почты хранятся в облаке, поэтому можно наслаждаться единообразным интерфейсом при использовании Outlook для Windows и Outlook в Интернете с любого устройства.</span><span class="sxs-lookup"><span data-stu-id="7467d-1213">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1214">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1214">Getting Started:</span></span>

<span data-ttu-id="7467d-1215">На вкладке "Общие" в разделе "Файл" > "Параметры" есть новый параметр "Хранить мои параметры Outlook в облаке".</span><span class="sxs-lookup"><span data-stu-id="7467d-1215">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="7467d-1216">Пользователям нужно установить флажок, чтобы разрешить перенос параметра сортировки почты в другие экземпляры классической версии Outlook и Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="7467d-1216">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1217">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1217">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1218">Измените сортировку почты на компьютере с включенными облачными параметрами.</span><span class="sxs-lookup"><span data-stu-id="7467d-1218">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="7467d-1219">Перейдите в Outlook Web App и убедитесь, что этот параметр также применен.</span><span class="sxs-lookup"><span data-stu-id="7467d-1219">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="7467d-1220">Измените настройки сортировки почты в Outlook Web App и запустите классическую версию Outlook, чтобы увидеть применение этих настроек.</span><span class="sxs-lookup"><span data-stu-id="7467d-1220">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1221">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1221">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="7467d-1222">В режиме "Средства обучения" реализована поддержка дополнительных цветов страниц</span><span class="sxs-lookup"><span data-stu-id="7467d-1222">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="7467d-1223">Средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="7467d-1223">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="7467d-1224">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="7467d-1224">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1225">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1225">Getting Started:</span></span>

<span data-ttu-id="7467d-1226">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="7467d-1226">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1227">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1227">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1228">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="7467d-1228">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1229">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1229">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="7467d-1230">Расширение возможностей для творчества с помощью анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="7467d-1230">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="7467d-1231">Теперь Office поддерживает анимированные модели, воспроизводимые в редакторе, чтобы вы могли оживить свои листы!</span><span class="sxs-lookup"><span data-stu-id="7467d-1231">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1232">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1232">Getting Started:</span></span>

1. <span data-ttu-id="7467d-1233">Откройте Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1233">Open Excel</span></span>
2. <span data-ttu-id="7467d-1234">Вставьте анимированную трехмерную модель (вскоре будут доступны в сообществе Remix, а пока их можно найти здесь: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="7467d-1234">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="7467d-1235">Анимированная модель будет воспроизводиться в редакторе!</span><span class="sxs-lookup"><span data-stu-id="7467d-1235">The animated model will play in the editor!</span></span> <span data-ttu-id="7467d-1236">Проверьте режим слайд-шоу, она будет воспроизводиться и там!</span><span class="sxs-lookup"><span data-stu-id="7467d-1236">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="7467d-1237">На ленте форматирования трехмерных моделей можно ознакомиться с дополнительными анимационными сценами в модели</span><span class="sxs-lookup"><span data-stu-id="7467d-1237">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1238">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1238">Scenarios to Try:</span></span>

1. <span data-ttu-id="7467d-1239">Вставьте анимированную модель и посмотрите, как она будет воспроизводиться в редакторе</span><span class="sxs-lookup"><span data-stu-id="7467d-1239">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="7467d-1240">Узнайте, какие анимационные сцены доступны для анимированной модели в коллекции "Сцены" на ленте форматирования трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="7467d-1240">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="7467d-1241">Можно воспроизводить или приостанавливать анимацию с помощью ленты, мини-панели или клавиши ПРОБЕЛ.</span><span class="sxs-lookup"><span data-stu-id="7467d-1241">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1242">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1242">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="7467d-1243">Все приложения</span><span class="sxs-lookup"><span data-stu-id="7467d-1243">All Applications</span></span>
- <span data-ttu-id="7467d-1244">Мы исправили ошибку, когда значок приложения для Excel может отображаться неправильно в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="7467d-1244">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="7467d-1245">Мы исправили ошибку, когда после установки обновления может исчезать кнопка меню "Файл".</span><span class="sxs-lookup"><span data-stu-id="7467d-1245">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="7467d-1246">Исправлена проблема, в результате которой может измениться пользовательская лицензия.</span><span class="sxs-lookup"><span data-stu-id="7467d-1246">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1247">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1247">Word</span></span> 
- <span data-ttu-id="7467d-1248">Исправлена проблема с неправильным отображением текста при определенных уровнях масштабирования.</span><span class="sxs-lookup"><span data-stu-id="7467d-1248">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1249">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1249">Excel</span></span>
- <span data-ttu-id="7467d-1250">Мы исправили ошибку, в результате которой пользователи могли не видеть запрос на сохранение книги после внесения изменений.</span><span class="sxs-lookup"><span data-stu-id="7467d-1250">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="7467d-1251">Мы исправили ошибку, когда событие BeforeSave не запускалось, если пользователь предоставил общий доступ к книге.</span><span class="sxs-lookup"><span data-stu-id="7467d-1251">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="7467d-1252">Исправлена проблема, когда изменение размера столбца на менее чем 6 пикселей вызывает появление сообщения об ошибке.</span><span class="sxs-lookup"><span data-stu-id="7467d-1252">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="7467d-1253">Исправлена ошибка, когда Excel игнорирует метку Application.Visible.</span><span class="sxs-lookup"><span data-stu-id="7467d-1253">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="7467d-1254">Исправлена ошибка, когда стрелки трассировки остаются на неактивных закрепленных областях.</span><span class="sxs-lookup"><span data-stu-id="7467d-1254">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="7467d-1255">Исправлена ошибка, когда форматирование ячеек дат и валют может изменяться при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="7467d-1255">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="7467d-1256">Мы исправили ошибку, когда подсказки могли неожиданно перемещаться</span><span class="sxs-lookup"><span data-stu-id="7467d-1256">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="7467d-1257">Мы исправили ошибки локализации редактора Power Query</span><span class="sxs-lookup"><span data-stu-id="7467d-1257">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="7467d-1258">Мы устранили проблему, когда рабочая книга могла удаляться из вложений при отправке по электронной почте.</span><span class="sxs-lookup"><span data-stu-id="7467d-1258">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1259">PowerPoint</span></span>
- <span data-ttu-id="7467d-1260">Мы устранили проблему с длительным временем, которое может требоваться на копирование форм.</span><span class="sxs-lookup"><span data-stu-id="7467d-1260">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1261">Outlook</span></span>
- <span data-ttu-id="7467d-1262">Мы устранили проблему с аварийным завершением работы Outlook при использовании инструмента рисования</span><span class="sxs-lookup"><span data-stu-id="7467d-1262">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="7467d-1263">Устранена проблема локализации при составлении HTML-сообщений электронной почты</span><span class="sxs-lookup"><span data-stu-id="7467d-1263">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="7467d-1264">Мы устранили проблему, когда пользователи сталкивались с трудностями при выборе нижней панели</span><span class="sxs-lookup"><span data-stu-id="7467d-1264">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1265">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1265">Access</span></span>
- <span data-ttu-id="7467d-1266">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1266">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1267">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1267">Project</span></span>
- <span data-ttu-id="7467d-1268">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1268">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="7467d-1269">22 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1269">March 22, 2019</span></span>
<span data-ttu-id="7467d-1270">Версия 1904 (сборка 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="7467d-1270">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="7467d-1271">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="7467d-1271">New Features</span></span>

- <span data-ttu-id="7467d-1272">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="7467d-1272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="7467d-1273">Дополнительные сведения <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="7467d-1273">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="7467d-1274">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="7467d-1274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1275">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1275">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1276">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1276">Word</span></span> 
- <span data-ttu-id="7467d-1277">Устранена ошибка, при которой в интерфейсе пользователя постоянно отображается "Проверка изменений".</span><span class="sxs-lookup"><span data-stu-id="7467d-1277">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1278">Excel</span></span>
- <span data-ttu-id="7467d-1279">Устранена ошибка, при которой приложение аварийно завершало работу после перемещения листа</span><span class="sxs-lookup"><span data-stu-id="7467d-1279">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="7467d-1280">Устранена ошибка, при которой приложение аварийно завершало работу после сохранения в формате PDF</span><span class="sxs-lookup"><span data-stu-id="7467d-1280">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="7467d-1281">Устранена ошибка, при которой диалоговое окно сохранения не воспринимало некоторые корейские символы</span><span class="sxs-lookup"><span data-stu-id="7467d-1281">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1282">PowerPoint</span></span>
- <span data-ttu-id="7467d-1283">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1283">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1284">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1284">Outlook</span></span>
- <span data-ttu-id="7467d-1285">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1285">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1286">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1286">Access</span></span>
- <span data-ttu-id="7467d-1287">Исправлено сообщение об ошибке в Access, при которой создавался дополнительный ярлык для Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1287">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="7467d-1288">Устранена ошибка, при которой данные со связанного сайта SharePoint отображались неправильно</span><span class="sxs-lookup"><span data-stu-id="7467d-1288">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1289">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1289">Project</span></span>
- <span data-ttu-id="7467d-1290">Устранена ошибка, при которой языковые параметры менялись с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="7467d-1290">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="7467d-1291">Устранена ошибка, при которой приложение аварийно завершало работу при синхронизации с SharePoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1291">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="7467d-1292">15 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1292">March 15, 2019</span></span>
<span data-ttu-id="7467d-1293">Версия 1904 (сборка 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-1293">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1294">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1294">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1295">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1295">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="7467d-1296">Режим фокусировки</span><span class="sxs-lookup"><span data-stu-id="7467d-1296">Focus Mode</span></span>

<span data-ttu-id="7467d-1297">Хотите, чтобы вас ничего не отвлекало от работы? Переключитесь в режим фокусировки в меню "Вид".</span><span class="sxs-lookup"><span data-stu-id="7467d-1297">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="7467d-1298">Только для обладателей подписки на Office 365.</span><span class="sxs-lookup"><span data-stu-id="7467d-1298">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1299">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1299">Getting Started:</span></span>

<span data-ttu-id="7467d-1300">Кнопка "Фокус" вкладки "Вид" в строке состояния ленты с кнопкой "Фокус"</span><span class="sxs-lookup"><span data-stu-id="7467d-1300">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1301">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1301">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1302">Переход в режим фокусировки и работа в интерфейсе фокусировки</span><span class="sxs-lookup"><span data-stu-id="7467d-1302">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1303">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1303">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1304">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1304">Word</span></span> 
- <span data-ttu-id="7467d-1305">Исправлена проблема, из-за которой изображения в документе, сохраненном в формате PDF, имели неправильное значение точек на дюйм</span><span class="sxs-lookup"><span data-stu-id="7467d-1305">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1306">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1306">Excel</span></span>
- <span data-ttu-id="7467d-1307">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1307">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1308">PowerPoint</span></span>
- <span data-ttu-id="7467d-1309">Исправлена проблема, из-за которой область примечаний открывалась и закрывалась неправильно</span><span class="sxs-lookup"><span data-stu-id="7467d-1309">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="7467d-1310">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при удалении видео</span><span class="sxs-lookup"><span data-stu-id="7467d-1310">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="7467d-1311">Исправлена проблема, когда некоторые экземпляры приложения не запускались.</span><span class="sxs-lookup"><span data-stu-id="7467d-1311">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1312">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1312">Outlook</span></span>
- <span data-ttu-id="7467d-1313">Исправлена проблема с неправильными уведомлениями о прочтении при просмотре на японском языке.</span><span class="sxs-lookup"><span data-stu-id="7467d-1313">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1314">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1314">Access</span></span>
- <span data-ttu-id="7467d-1315">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1315">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1316">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1316">Project</span></span>
- <span data-ttu-id="7467d-1317">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1317">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="7467d-1318">8 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1318">March 8, 2019</span></span> 
<span data-ttu-id="7467d-1319">Версия 1903 (сборка 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="7467d-1319">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1320">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1320">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1321">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1321">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="7467d-1322">Находите нужные элементы с помощью Поиска (Майкрософт)</span><span class="sxs-lookup"><span data-stu-id="7467d-1322">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="7467d-1323">С помощью поиска Майкрософт можно найти все файлы, команды и пользователей, которые необходимы для выполнения работы.</span><span class="sxs-lookup"><span data-stu-id="7467d-1323">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1324">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1324">Getting Started:</span></span>

- <span data-ttu-id="7467d-1325">Эта функция выделяется вверху пользовательского интерфейса в заголовке.</span><span class="sxs-lookup"><span data-stu-id="7467d-1325">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1326">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1326">Scenarios to Try:</span></span>

- <span data-ttu-id="7467d-1327">Поиск учебного заведения, недавнего документа или часто используемых команд ленты</span><span class="sxs-lookup"><span data-stu-id="7467d-1327">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="7467d-1328">Поиск статьи или темы и получение дополнительных сведений о ней</span><span class="sxs-lookup"><span data-stu-id="7467d-1328">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="7467d-1329">Совместное редактирование</span><span class="sxs-lookup"><span data-stu-id="7467d-1329">CoAuthoring</span></span>

<span data-ttu-id="7467d-1330">Вам надоело получать блокировку на документы с макросами?</span><span class="sxs-lookup"><span data-stu-id="7467d-1330">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="7467d-1331">Теперь DOCM-файлы в OneDrive для бизнеса поддерживают одновременное редактирование несколькими авторами.</span><span class="sxs-lookup"><span data-stu-id="7467d-1331">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1332">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1332">Getting Started:</span></span>

<span data-ttu-id="7467d-1333">Пользователю не нужно нажимать какие-либо кнопки в пользовательском интерфейсе, чтобы применить эту возможность.</span><span class="sxs-lookup"><span data-stu-id="7467d-1333">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="7467d-1334">Она включена по умолчанию для DOCM-файлов в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="7467d-1334">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="7467d-1335">Чтобы применить ее, пользователю нужно сохранить DOCM-файл в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="7467d-1335">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1336">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1336">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1337">Создайте DOCM-файл в OneDrive для бизнеса, поделитесь им с коллегами и работайте совместно!</span><span class="sxs-lookup"><span data-stu-id="7467d-1337">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1338">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1338">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1339">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1339">Word</span></span> 
- <span data-ttu-id="7467d-1340">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="7467d-1340">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="7467d-1341">Решена проблема со сбоем, происходившим при ответе на примечания</span><span class="sxs-lookup"><span data-stu-id="7467d-1341">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="7467d-1342">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="7467d-1342">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1343">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1343">Excel</span></span>
- <span data-ttu-id="7467d-1344">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="7467d-1344">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1345">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1345">PowerPoint</span></span>
- <span data-ttu-id="7467d-1346">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1346">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1347">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1347">Outlook</span></span>
- <span data-ttu-id="7467d-1348">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="7467d-1348">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="7467d-1349">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="7467d-1349">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="7467d-1350">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="7467d-1350">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1351">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1351">Access</span></span>
- <span data-ttu-id="7467d-1352">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="7467d-1352">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="7467d-1353">Исправлена проблема, из-за которой пользователи не могли присвоить свойству DisplayControl для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="7467d-1353">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1354">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1354">Project</span></span>
- <span data-ttu-id="7467d-1355">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1355">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="7467d-1356">1 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1356">March 1, 2019</span></span> 
<span data-ttu-id="7467d-1357">Версия 1903 (сборка 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="7467d-1357">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1358">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="7467d-1358">What's New</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1359">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1359">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="7467d-1360">Синхронизированные цвета для отслеживания изменений, примечаний и совместной работы в режиме реального времени</span><span class="sxs-lookup"><span data-stu-id="7467d-1360">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="7467d-1361">Исправления в наших продуктах теперь обеспечивают отображение одинаковым цветом примечаний, изменений и указателя мыши при совместной работе.</span><span class="sxs-lookup"><span data-stu-id="7467d-1361">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1362">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1362">Getting Started:</span></span>

<span data-ttu-id="7467d-1363">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="7467d-1363">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="7467d-1364">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="7467d-1364">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1365">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1365">Scenarios to Try:</span></span>

<span data-ttu-id="7467d-1366">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="7467d-1366">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="7467d-1367">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="7467d-1367">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1368">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1368">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1369">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1369">Word</span></span> 
- <span data-ttu-id="7467d-1370">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="7467d-1370">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="7467d-1371">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="7467d-1371">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1372">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1372">Excel</span></span>
- <span data-ttu-id="7467d-1373">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="7467d-1373">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1374">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1374">PowerPoint</span></span>
- <span data-ttu-id="7467d-1375">Исправлена проблема с размером изображения слайда при использовании @упоминаний в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1375">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1376">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1376">Outlook</span></span>
- <span data-ttu-id="7467d-1377">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="7467d-1377">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="7467d-1378">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="7467d-1378">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="7467d-1379">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="7467d-1379">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1380">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1380">Access</span></span>
- <span data-ttu-id="7467d-1381">Обновлен текст запроса, отображаемый для подтверждения обновления связей таблицы с источником данных</span><span class="sxs-lookup"><span data-stu-id="7467d-1381">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="7467d-1382">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="7467d-1382">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="7467d-1383">Исправлена проблема, из-за которой пользователи не могли присвоить свойству "Тип элемента управления" для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="7467d-1383">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1384">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1384">Project</span></span>
- <span data-ttu-id="7467d-1385">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1385">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="7467d-1386">15 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1386">February 15, 2019</span></span> 
<span data-ttu-id="7467d-1387">Версия 1903 (сборка 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="7467d-1387">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="7467d-1388">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="7467d-1388">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1389">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1389">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="7467d-1390">Улучшения перехода "Трансформация" — трансформация по имени</span><span class="sxs-lookup"><span data-stu-id="7467d-1390">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="7467d-1391">Укажите фигуры, которые нужно трансформировать</span><span class="sxs-lookup"><span data-stu-id="7467d-1391">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1392">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1392">Getting Started:</span></span>

- <span data-ttu-id="7467d-1393">Чтобы при переходе "Трансформация" два объекта обрабатывались как одинаковые, пользователь может переименовать фигуры с помощью области выделения.</span><span class="sxs-lookup"><span data-stu-id="7467d-1393">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="7467d-1394">Имя должно начинаться с двух восклицательных знаков</span><span class="sxs-lookup"><span data-stu-id="7467d-1394">The name must be prefaced with “!!”</span></span> <span data-ttu-id="7467d-1395">("!!"), чтобы использовать его при трансформации для переопределения стандартного сопоставления, например "!!Имя".</span><span class="sxs-lookup"><span data-stu-id="7467d-1395">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="7467d-1396">Пользователи могут продолжать переименовывать фигуры, используя любые имена, которые не начинаются с "!!",</span><span class="sxs-lookup"><span data-stu-id="7467d-1396">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="7467d-1397">не беспокоясь о том, что это изменит работу перехода "Трансформация".</span><span class="sxs-lookup"><span data-stu-id="7467d-1397">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1398">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1398">Scenarios to Try:</span></span>

- <span data-ttu-id="7467d-1399">Вставьте фигуру на слайд, например прямоугольник</span><span class="sxs-lookup"><span data-stu-id="7467d-1399">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="7467d-1400">Создайте новый слайд</span><span class="sxs-lookup"><span data-stu-id="7467d-1400">Create a new slide</span></span>
- <span data-ttu-id="7467d-1401">Вставьте другую фигуру на втором слайде, например треугольник</span><span class="sxs-lookup"><span data-stu-id="7467d-1401">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="7467d-1402">Откройте область выделения и присвойте имя "!!фигура" прямоугольнику на слайде 1 и треугольнику на слайде 2.</span><span class="sxs-lookup"><span data-stu-id="7467d-1402">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="7467d-1403">Примените переход "Трансформация" ко второму слайду</span><span class="sxs-lookup"><span data-stu-id="7467d-1403">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="7467d-1404">Улучшения перехода "Трансформация" — графические элементы SmartArt</span><span class="sxs-lookup"><span data-stu-id="7467d-1404">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="7467d-1405">Трансформация графических элементов SmartArt с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="7467d-1405">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1406">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1406">Getting Started:</span></span>

<span data-ttu-id="7467d-1407">Аналогичное использование перехода "Трансформация" при применении графических элементов SmartArt</span><span class="sxs-lookup"><span data-stu-id="7467d-1407">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1408">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1408">Scenarios to Try:</span></span>

- <span data-ttu-id="7467d-1409">Вставьте графический элемент SmartArt на слайд</span><span class="sxs-lookup"><span data-stu-id="7467d-1409">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="7467d-1410">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="7467d-1410">Duplicate the Slide</span></span>
- <span data-ttu-id="7467d-1411">Поменяйте размер, измените или переместите графический элемент SmartArt на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="7467d-1411">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="7467d-1412">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="7467d-1412">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="7467d-1413">Улучшения перехода "Трансформация" — таблицы</span><span class="sxs-lookup"><span data-stu-id="7467d-1413">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="7467d-1414">Трансформация таблиц с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="7467d-1414">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="7467d-1415">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="7467d-1415">Getting Started:</span></span>
<span data-ttu-id="7467d-1416">Аналогичное использование перехода "Трансформация" при применении таблиц</span><span class="sxs-lookup"><span data-stu-id="7467d-1416">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1417">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1417">Scenarios to Try:</span></span>

- <span data-ttu-id="7467d-1418">Вставьте таблицу на слайд</span><span class="sxs-lookup"><span data-stu-id="7467d-1418">Insert a Table in a slide</span></span>
- <span data-ttu-id="7467d-1419">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="7467d-1419">Duplicate the slide</span></span>
- <span data-ttu-id="7467d-1420">Поменяйте размер, измените или переместите таблицу на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="7467d-1420">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="7467d-1421">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="7467d-1421">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="7467d-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher и Visio</span><span class="sxs-lookup"><span data-stu-id="7467d-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="7467d-1423">Легкое переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="7467d-1423">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="7467d-1424">Новый диспетчер учетных записей отображает все рабочие и личные учетные записи в одном месте и позволяет управлять переключением между ними.</span><span class="sxs-lookup"><span data-stu-id="7467d-1424">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="7467d-1425">Этот обновленный интерфейс уточняет способ выполненного входа и обеспечивает возможность переключения между рабочими и личными учетными записями без выхода из системы или появления сложных диалоговых окон.</span><span class="sxs-lookup"><span data-stu-id="7467d-1425">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="7467d-1427">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="7467d-1427">Scenarios to Try:</span></span>
- <span data-ttu-id="7467d-1428">Переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="7467d-1428">Switch between accounts</span></span>
- <span data-ttu-id="7467d-1429">Добавление новой учетной записи [Примечание. Рекомендуется сначала открыть "Файл" | "Учетная запись" | "Подключенные службы" и удалить все личные службы, подключенные к рабочей учетной записи и наоборот]</span><span class="sxs-lookup"><span data-stu-id="7467d-1429">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="7467d-1430">Выход из учетной записи</span><span class="sxs-lookup"><span data-stu-id="7467d-1430">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="7467d-1431">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1431">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1432">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1432">Word</span></span> 
- <span data-ttu-id="7467d-1433">Исправлена проблема с предварительным просмотром контекста для таблиц и изображений</span><span class="sxs-lookup"><span data-stu-id="7467d-1433">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1434">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1434">Excel</span></span>
- <span data-ttu-id="7467d-1435">Исправлена ошибка, из-за которой при использовании темы "Черная" текст в поле поиска автофильтра был белого цвета</span><span class="sxs-lookup"><span data-stu-id="7467d-1435">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="7467d-1436">Исправлена проблема с согласованным пользовательским интерфейсом для новой надстройки Office</span><span class="sxs-lookup"><span data-stu-id="7467d-1436">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1437">PowerPoint</span></span>
- <span data-ttu-id="7467d-1438">Исправлена проблема с автоматическим расширением области отображения во время презентации на ноутбуках и планшетах.</span><span class="sxs-lookup"><span data-stu-id="7467d-1438">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1439">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1439">Outlook</span></span>
- <span data-ttu-id="7467d-1440">Исправлена проблема с отображением кнопки "Отправить в OneNote"</span><span class="sxs-lookup"><span data-stu-id="7467d-1440">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1441">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1441">Access</span></span>
- <span data-ttu-id="7467d-1442">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1442">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1443">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1443">Project</span></span>
- <span data-ttu-id="7467d-1444">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1444">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="7467d-1445">11 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1445">February 11, 2019</span></span>
<span data-ttu-id="7467d-1446">Версия 1903 (сборка 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="7467d-1446">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="7467d-1447">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1447">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1448">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1448">Word</span></span> 
- <span data-ttu-id="7467d-1449">Исправлена ошибка, из-за которой некоторые настроенные стили нельзя было применить в Word Online</span><span class="sxs-lookup"><span data-stu-id="7467d-1449">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="7467d-1450">Исправлены проблемы предварительного просмотра контекста, связанные с форматированными объектами в Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1450">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="7467d-1451">Исправлена ошибка, из-за которой при вставке списков происходил сбой Word.</span><span class="sxs-lookup"><span data-stu-id="7467d-1451">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1452">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1452">Excel</span></span>
- <span data-ttu-id="7467d-1453">Исправлена ошибка, из-за которой добавляемые пробелы после числовых форматов не отображались при отсутствии обозначения денежной единицы</span><span class="sxs-lookup"><span data-stu-id="7467d-1453">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="7467d-1454">Исправлена проблема с автоматическим определением акций</span><span class="sxs-lookup"><span data-stu-id="7467d-1454">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1455">PowerPoint</span></span>
- <span data-ttu-id="7467d-1456">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1456">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1457">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1457">Outlook</span></span>
- <span data-ttu-id="7467d-1458">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1458">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1459">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1459">Access</span></span>
- <span data-ttu-id="7467d-1460">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1460">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1461">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1461">Project</span></span>
- <span data-ttu-id="7467d-1462">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1462">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="7467d-1463">1 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7467d-1463">February 1, 2019</span></span> 
<span data-ttu-id="7467d-1464">Версия 1902 (сборка 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="7467d-1464">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="7467d-1465">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="7467d-1465">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="7467d-1466">Word</span><span class="sxs-lookup"><span data-stu-id="7467d-1466">Word</span></span> 
- <span data-ttu-id="7467d-1467">Устранена проблема с изменением размера ячеек во внедренной таблице Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1467">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="7467d-1468">Устранена проблема с копированием и вставкой фигур на полотне</span><span class="sxs-lookup"><span data-stu-id="7467d-1468">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="7467d-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="7467d-1469">Excel</span></span>
- <span data-ttu-id="7467d-1470">Исправлена ошибка с открытием файлов из Excel Web App</span><span class="sxs-lookup"><span data-stu-id="7467d-1470">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="7467d-1471">Исправлена ошибка, вызывавшая сбой при сохранении CSV-файла в формате XLSX из-за длины имени файла</span><span class="sxs-lookup"><span data-stu-id="7467d-1471">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="7467d-1472">Исправлено контекстное меню для отображения параметров контекстного меню</span><span class="sxs-lookup"><span data-stu-id="7467d-1472">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7467d-1473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7467d-1473">PowerPoint</span></span>
- <span data-ttu-id="7467d-1474">Устранена проблема, из-за которой пользователи не могли использовать сочетания клавиш CTRL+ALT+7 и CTRL+ALT+8 для ввода квадратных скобок</span><span class="sxs-lookup"><span data-stu-id="7467d-1474">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="7467d-1475">Исправлена ошибка, из-за которой при вставке локального видео в файл PPT уменьшалось место на диске "C"</span><span class="sxs-lookup"><span data-stu-id="7467d-1475">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="7467d-1476">Исправлена кнопка "Публикация в Microsoft Stream", не отображавшаяся у некоторых пользователей</span><span class="sxs-lookup"><span data-stu-id="7467d-1476">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="7467d-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="7467d-1477">Outlook</span></span>
- <span data-ttu-id="7467d-1478">Исправлена ошибка, из-за которой в представлении задач в календаре неправильно отображалась тема задачи.</span><span class="sxs-lookup"><span data-stu-id="7467d-1478">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="7467d-1479">Access</span><span class="sxs-lookup"><span data-stu-id="7467d-1479">Access</span></span>
- <span data-ttu-id="7467d-1480">Исправлена проблема с масштабированием диаграмм</span><span class="sxs-lookup"><span data-stu-id="7467d-1480">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="7467d-1481">Project</span><span class="sxs-lookup"><span data-stu-id="7467d-1481">Project</span></span>
- <span data-ttu-id="7467d-1482">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="7467d-1482">Various performance and stability fixes</span></span>
