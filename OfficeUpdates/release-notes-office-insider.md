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
ms.openlocfilehash: 38f26f551be55a7817a993108f598c6a6a9ecdb5
ms.sourcegitcommit: fdc89a96b2ab35af2f08654ef28117dec7657443
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/24/2020
ms.locfileid: "43804906"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="9c87c-103">Заметки о выпуске для участников программы предварительной оценки Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="9c87c-104">Эта статья содержит заметки о выпуске для сборок приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows, предоставляемых в рамках программы предварительной оценки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="9c87c-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="9c87c-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="9c87c-106">Обратите внимание на то, что развертывание возможностей (а иногда даже исправлений) для участников программы предварительной оценки зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="9c87c-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="9c87c-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="9c87c-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="9c87c-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="9c87c-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="9c87c-109">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок.</span><span class="sxs-lookup"><span data-stu-id="9c87c-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="9c87c-110">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-110">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-april-24"></a><span data-ttu-id="9c87c-113">Версия 2005: 24 апреля</span><span class="sxs-lookup"><span data-stu-id="9c87c-113">Version 2005: April 24</span></span>
<span data-ttu-id="9c87c-114">*Версия 2005 (сборка 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-114">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-118">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-119">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-119">Excel</span></span>
- <span data-ttu-id="9c87c-120">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="9c87c-120">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="9c87c-121">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="9c87c-121">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-122">Outlook</span></span>
- <span data-ttu-id="9c87c-123">Устранена проблема, из-за которой была отключена кнопка "Классифицировать" для календарей группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="9c87c-123">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="9c87c-124">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="9c87c-124">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-125">PowerPoint</span></span>
- <span data-ttu-id="9c87c-126">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="9c87c-126">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-127">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-127">Word</span></span>
- <span data-ttu-id="9c87c-128">При включении параметра "Показывать закладки" закладки не отображались.</span><span class="sxs-lookup"><span data-stu-id="9c87c-128">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="9c87c-129">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="9c87c-129">This has been fixed.</span></span>
- <span data-ttu-id="9c87c-130">Это изменение устраняет проблему, из-за которой при включении параметра "Показывать коды полей вместо их значений" текст с гиперссылками может не отображаться.</span><span class="sxs-lookup"><span data-stu-id="9c87c-130">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-april-17"></a><span data-ttu-id="9c87c-132">Версия 2005: 17 апреля</span><span class="sxs-lookup"><span data-stu-id="9c87c-132">Version 2005: April 17</span></span>
<span data-ttu-id="9c87c-133">*Версия 2005 (сборка 12810,20002)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-133">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-135">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-136">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-136">Excel</span></span>
- <span data-ttu-id="9c87c-137">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="9c87c-137">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="9c87c-138">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-138">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="9c87c-139">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="9c87c-139">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="9c87c-140">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="9c87c-140">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="9c87c-141">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="9c87c-141">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="9c87c-142">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c87c-142">OneNote</span></span>
- <span data-ttu-id="9c87c-143">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="9c87c-143">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-144">Outlook</span></span>
- <span data-ttu-id="9c87c-145">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="9c87c-145">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="9c87c-146">Решает проблему, из-за которой собрания, для которых прошло более 2 месяцев, не отображали тему собрания в Помощнике по планированию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-146">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="9c87c-147">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="9c87c-147">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="9c87c-148">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="9c87c-148">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="9c87c-149">Решена проблема, из-за которой правила удаления, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, стали недействительными.</span><span class="sxs-lookup"><span data-stu-id="9c87c-149">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="9c87c-150">Решает проблему, которая приводила к удалению вложений при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-150">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-151">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-151">Project</span></span>
- <span data-ttu-id="9c87c-152">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="9c87c-152">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="9c87c-153">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-153">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="9c87c-154">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="9c87c-154">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-10"></a><span data-ttu-id="9c87c-156">Версия 2004: 10 апреля</span><span class="sxs-lookup"><span data-stu-id="9c87c-156">Version 2004: April 10</span></span>
<span data-ttu-id="9c87c-157">*Версия 2004 (сборка 12730,20024)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-157">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-159">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-159">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9c87c-160">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-160">Access</span></span>

- <span data-ttu-id="9c87c-161">**Пропустите диалоговое окно «Показать таблицу», перейдите непосредственно к панели задач и упростите добавление таблиц к отношениям и запросам.:** Добавьте таблицы и запросы, щелкнув четыре вкладки, выбрав несколько имен, выполнив поиск по тексту и перетащив из области задач, которая остается открой пока ты работаешь.</span><span class="sxs-lookup"><span data-stu-id="9c87c-161">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-162">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-162">Excel</span></span>

- <span data-ttu-id="9c87c-163">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="9c87c-163">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c87c-164">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c87c-164">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-165">Outlook</span></span>

- <span data-ttu-id="9c87c-166">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="9c87c-166">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c87c-167">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c87c-167">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="9c87c-168">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-168">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-169">PowerPoint</span></span>

- <span data-ttu-id="9c87c-170">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="9c87c-170">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c87c-171">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c87c-171">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="9c87c-172">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-172">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-173">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-173">Word</span></span>

- <span data-ttu-id="9c87c-174">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="9c87c-174">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="9c87c-175">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="9c87c-175">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="9c87c-176">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="9c87c-176">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="9c87c-177">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-177">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-180">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-180">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c87c-181">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-181">Access</span></span>

- <span data-ttu-id="9c87c-182">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="9c87c-182">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-183">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-183">Excel</span></span>

- <span data-ttu-id="9c87c-184">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-184">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="9c87c-185">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="9c87c-185">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="9c87c-186">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-186">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="9c87c-187">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="9c87c-187">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="9c87c-188">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="9c87c-188">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-189">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-189">Outlook</span></span>

- <span data-ttu-id="9c87c-190">Решает проблему, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-190">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="9c87c-191">Решает проблему, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="9c87c-191">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="9c87c-192">Устраняет проблему, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-192">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="9c87c-193">Решает проблему, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="9c87c-193">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-194">PowerPoint</span></span>

- <span data-ttu-id="9c87c-195">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-195">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="9c87c-196">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="9c87c-196">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="9c87c-197">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="9c87c-197">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-198">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-198">Project</span></span>

- <span data-ttu-id="9c87c-199">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="9c87c-199">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-200">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-200">Word</span></span>

- <span data-ttu-id="9c87c-201">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="9c87c-201">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="9c87c-202">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="9c87c-202">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="9c87c-203">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-203">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="9c87c-204">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="9c87c-204">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="9c87c-205">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="9c87c-205">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-27"></a><span data-ttu-id="9c87c-207">Версия 2004: 27 марта</span><span class="sxs-lookup"><span data-stu-id="9c87c-207">Version 2004: March 27</span></span>
<span data-ttu-id="9c87c-208">*Версия 2004 (сборка 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-208">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-210">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-210">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-211">Outlook</span></span>

- <span data-ttu-id="9c87c-212">**Новый параметр, позволяющий отключить предложения для @упоминаний при создании сообщений.** Считаете ли вы средство выбора @упоминаний скорее раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="9c87c-212">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="9c87c-213">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="9c87c-213">Now you can turn it off if you prefer.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-216">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-216">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-217">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-217">Outlook</span></span>
- <span data-ttu-id="9c87c-218">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="9c87c-218">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="9c87c-219">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="9c87c-219">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="9c87c-220">Исправлена проблема, из-за которой пользователи не могли добавить дополнительные вложения из расположения в Интернете в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="9c87c-220">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-221">PowerPoint</span></span>
- <span data-ttu-id="9c87c-222">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="9c87c-222">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-223">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-223">Project</span></span>
- <span data-ttu-id="9c87c-224">Исправлена проблема, из-за которой при выполнении "CustomFieldValueListGetItem" и отсутствии таблицы подстановки для настраиваемого поля создается пустая таблица подстановки, хотя этого быть не должно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-224">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-225">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-225">Word</span></span>
- <span data-ttu-id="9c87c-226">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="9c87c-226">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-20"></a><span data-ttu-id="9c87c-228">Версия 2004: 20 марта</span><span class="sxs-lookup"><span data-stu-id="9c87c-228">Version 2004: March 20</span></span>
<span data-ttu-id="9c87c-229">*Версия 2004 (сборка 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-229">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-231">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-231">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-232">Outlook</span></span>

- <span data-ttu-id="9c87c-233">**Обновление внешнего вида календаря.** В прошлом году мы обновили интерфейс почты, а сейчас пришло время улучшить внешний вид календаря!</span><span class="sxs-lookup"><span data-stu-id="9c87c-233">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="9c87c-234">Обновления придали интерфейсу свежести, но он остался вполне узнаваемым, поэтому вам, как опытному пользователю Outlook, будет легко освоить его на ходу и сразу повысить свою продуктивность.</span><span class="sxs-lookup"><span data-stu-id="9c87c-234">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="9c87c-235">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-235">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-236">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-236">PowerPoint</span></span>

- <span data-ttu-id="9c87c-237">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-237">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-240">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-241">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-241">Excel</span></span>

- <span data-ttu-id="9c87c-242">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="9c87c-242">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-243">Outlook</span></span>

- <span data-ttu-id="9c87c-244">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="9c87c-244">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="9c87c-245">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-245">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="9c87c-246">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="9c87c-246">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="9c87c-247">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="9c87c-247">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="9c87c-248">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="9c87c-248">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-249">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-249">Project</span></span>

- <span data-ttu-id="9c87c-250">Исправлена проблема, из-за которой событие 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) при нажатии пользователем кнопки "Деактивировать" на ленте задач группировки "Планирование" не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="9c87c-250">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="9c87c-251">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="9c87c-251">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="9c87c-252">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="9c87c-252">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="9c87c-253">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="9c87c-253">This behavior has been fixed.</span></span>

- <span data-ttu-id="9c87c-254">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="9c87c-254">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="9c87c-255">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="9c87c-255">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="9c87c-256">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-256">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="9c87c-257">Исправлена проблема, из-за которой при печати временной шкалы с использованием календаря Hijri в представлении для печати пропускался или дублировался месяц.</span><span class="sxs-lookup"><span data-stu-id="9c87c-257">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="9c87c-258">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="9c87c-258">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-259">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-259">Word</span></span>

- <span data-ttu-id="9c87c-260">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="9c87c-260">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="9c87c-261">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="9c87c-261">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="9c87c-262">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-262">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="9c87c-263">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="9c87c-263">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="9c87c-264">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-264">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-13"></a><span data-ttu-id="9c87c-266">Версия 2004: 13 марта</span><span class="sxs-lookup"><span data-stu-id="9c87c-266">Version 2004: March 13</span></span>
<span data-ttu-id="9c87c-267">*Версия 2004 (сборка 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-267">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-269">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-269">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-270">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-270">Excel</span></span>
- <span data-ttu-id="9c87c-271">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-271">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="9c87c-272">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-272">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="9c87c-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-273">PowerPoint</span></span>
- <span data-ttu-id="9c87c-274">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-274">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="9c87c-275">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-275">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="9c87c-276">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-276">Word</span></span>
- <span data-ttu-id="9c87c-277">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-277">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="9c87c-278">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-278">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-281">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-281">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-282">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-282">Access</span></span>
- <span data-ttu-id="9c87c-283">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-283">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-284">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-284">Excel</span></span>
- <span data-ttu-id="9c87c-285">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="9c87c-285">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="9c87c-286">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-286">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-287">Outlook</span></span>
- <span data-ttu-id="9c87c-288">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="9c87c-288">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="9c87c-289">Исправлена проблема, из-за которой не начинался поиск при нажатии клавиши ВВОД в развернутой области поиска, и требовалось вместо этого щелкать кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="9c87c-289">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="9c87c-290">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="9c87c-290">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-291">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-291">Project</span></span>
- <span data-ttu-id="9c87c-292">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="9c87c-292">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="9c87c-293">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="9c87c-293">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-294">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-294">Word</span></span>
- <span data-ttu-id="9c87c-295">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="9c87c-295">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="9c87c-296">Исправлена проблема, из-за которой выравнивание слов в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="9c87c-296">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="9c87c-297">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="9c87c-297">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="9c87c-298">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="9c87c-298">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-06"></a><span data-ttu-id="9c87c-300">Версия 2003: 6 марта</span><span class="sxs-lookup"><span data-stu-id="9c87c-300">Version 2003: March 06</span></span>
<span data-ttu-id="9c87c-301">*Версия 2003 (сборка 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-301">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-303">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-303">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-304">Outlook</span></span>

- <span data-ttu-id="9c87c-305">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не было сохранено на сервере Exchange Server и возник конфликт.</span><span class="sxs-lookup"><span data-stu-id="9c87c-305">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="9c87c-306">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="9c87c-306">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="9c87c-307">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="9c87c-307">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-308">PowerPoint</span></span>

- <span data-ttu-id="9c87c-309">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="9c87c-309">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="9c87c-310">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-310">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-311">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-311">Word</span></span>

- <span data-ttu-id="9c87c-312">Исправлена проблема с функцией сравнения для документов, защищенных для редактирования.</span><span class="sxs-lookup"><span data-stu-id="9c87c-312">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-313">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-313">Office Suite</span></span>

- <span data-ttu-id="9c87c-314">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-314">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="9c87c-315">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="9c87c-315">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2003-february-28"></a><span data-ttu-id="9c87c-318">Версия 2003: 28 февраля</span><span class="sxs-lookup"><span data-stu-id="9c87c-318">Version 2003: February 28</span></span>
<span data-ttu-id="9c87c-319">*Версия 2003 (сборка 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-319">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-321">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-321">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-322">Outlook</span></span>

- <span data-ttu-id="9c87c-323">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="9c87c-323">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-324">PowerPoint</span></span>

- <span data-ttu-id="9c87c-325">**Улучшенный рукописный ввод для работы со схемами.** Создавайте отличные схемы и преобразуйте их в объекты Office, которыми можно управлять. [Подробнее](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="9c87c-325">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-328">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-329">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-329">Excel</span></span>

- <span data-ttu-id="9c87c-330">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="9c87c-330">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-331">Outlook</span></span>

- <span data-ttu-id="9c87c-332">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="9c87c-332">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-333">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-333">Word</span></span>

- <span data-ttu-id="9c87c-334">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="9c87c-334">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="9c87c-335">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="9c87c-335">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="9c87c-336">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="9c87c-336">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-337">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-337">Office Suite</span></span>

- <span data-ttu-id="9c87c-338">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="9c87c-338">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-21"></a><span data-ttu-id="9c87c-340">Версия 2003: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="9c87c-340">Version 2003: February 21</span></span>
<span data-ttu-id="9c87c-341">*Версия 2003 (сборка 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-341">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-343">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-343">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="9c87c-344">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-344">Office Suite</span></span>

- <span data-ttu-id="9c87c-345">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="9c87c-345">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-348">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-348">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-349">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-349">Excel</span></span>
- <span data-ttu-id="9c87c-350">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-350">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="9c87c-351">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="9c87c-351">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="9c87c-352">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="9c87c-352">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="9c87c-353">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="9c87c-353">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="9c87c-354">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="9c87c-354">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-355">Outlook</span></span>
- <span data-ttu-id="9c87c-356">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="9c87c-356">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="9c87c-357">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="9c87c-357">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="9c87c-358">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="9c87c-358">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-359">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-359">Word</span></span>
- <span data-ttu-id="9c87c-360">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="9c87c-360">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="9c87c-361">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега.</span><span class="sxs-lookup"><span data-stu-id="9c87c-361">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="9c87c-362">Эта проблема исправлена.</span><span class="sxs-lookup"><span data-stu-id="9c87c-362">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-363">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-363">Office Suite</span></span>
- <span data-ttu-id="9c87c-364">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="9c87c-364">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="9c87c-365">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="9c87c-365">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="9c87c-366">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="9c87c-366">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-14"></a><span data-ttu-id="9c87c-368">Версия 2003: 14 февраля</span><span class="sxs-lookup"><span data-stu-id="9c87c-368">Version 2003: February 14</span></span>
<span data-ttu-id="9c87c-369">*Версия 2003 (сборка 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-369">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-371">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-371">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-372">Outlook</span></span>

- <span data-ttu-id="9c87c-373">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="9c87c-373">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="9c87c-374">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="9c87c-374">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-375">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-375">Word</span></span>

- <span data-ttu-id="9c87c-376">**Правки от руки в инструментах рисования.** Нажмите "Рисование" и выберите перо Правки от руки, чтобы редактировать документ с помощью пальца или цифрового пера.</span><span class="sxs-lookup"><span data-stu-id="9c87c-376">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="9c87c-377">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-377">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="9c87c-378">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-378">Office Suite</span></span>

- <span data-ttu-id="9c87c-379">**Более понятные значки строки состояния.** Значки строки состояния стали понятнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-379">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-382">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-382">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-383">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-383">Outlook</span></span>

- <span data-ttu-id="9c87c-384">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря "Параметры доступности".</span><span class="sxs-lookup"><span data-stu-id="9c87c-384">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="9c87c-385">Исправлена проблема, которая могла привести к появлению оповещения "К сожалению, не удалось открыть элемент" при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-385">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="9c87c-386">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-386">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="9c87c-387">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-387">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-388">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-388">PowerPoint</span></span>

- <span data-ttu-id="9c87c-389">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-389">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-390">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-390">Word</span></span>

- <span data-ttu-id="9c87c-391">Исправлена проблема, из-за которой изображения в документах теряли прозрачность при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="9c87c-391">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-07"></a><span data-ttu-id="9c87c-393">Версия 2002: 7 февраля</span><span class="sxs-lookup"><span data-stu-id="9c87c-393">Version 2002: February 07</span></span>
<span data-ttu-id="9c87c-394">*Версия 2002 (сборка 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-394">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-396">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-396">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9c87c-397">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-397">Access</span></span>

- <span data-ttu-id="9c87c-398">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="9c87c-398">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="9c87c-399">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="9c87c-399">Search and replace text in SQL View.</span></span> <span data-ttu-id="9c87c-400">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="9c87c-400">Select multiple tables in the Relationships window.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-403">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-403">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c87c-404">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-404">Access</span></span>

- <span data-ttu-id="9c87c-405">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="9c87c-405">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="9c87c-406">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-406">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="9c87c-407">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="9c87c-407">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-408">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-408">Excel</span></span>

- <span data-ttu-id="9c87c-409">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="9c87c-409">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-410">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-410">Outlook</span></span>

- <span data-ttu-id="9c87c-411">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="9c87c-411">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="9c87c-412">Решена проблема, приводившая к сбоям при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="9c87c-412">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-413">PowerPoint</span></span>

- <span data-ttu-id="9c87c-414">Исправлена проблема, из-за которой после закрытия файла приложение PowerPoint не удаляет его сразу из коллекции презентаций, если запущены обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="9c87c-414">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="9c87c-415">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-415">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="9c87c-416">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="9c87c-416">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-417">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-417">Word</span></span>

- <span data-ttu-id="9c87c-418">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="9c87c-418">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="9c87c-419">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="9c87c-419">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="9c87c-420">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="9c87c-420">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="9c87c-421">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="9c87c-421">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="9c87c-422">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="9c87c-422">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="9c87c-423">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="9c87c-423">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-424">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-424">Office Suite</span></span>

- <span data-ttu-id="9c87c-425">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="9c87c-425">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-january-31"></a><span data-ttu-id="9c87c-427">Версия 2002:31 января</span><span class="sxs-lookup"><span data-stu-id="9c87c-427">Version 2002: January 31</span></span>
<span data-ttu-id="9c87c-428">*Версия 2002 (сборка 12513,20010)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-428">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-430">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-430">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-431">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-431">Excel</span></span>

- <span data-ttu-id="9c87c-432">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-432">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="9c87c-433">**Профилирование данных в редакторе запросов.** Получайте быстрый анализ данных в столбцах, выявляйте ошибки и пустые значения, просматривайте гистограммы распределения и т. д.</span><span class="sxs-lookup"><span data-stu-id="9c87c-433">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-436">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-436">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-437">Outlook</span></span>

- <span data-ttu-id="9c87c-438">Исправлена проблема, из-за которой срок действия почты в соответствии с политикой хранения будет иметь две метки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-438">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="9c87c-439">Один показывает, что срок действия письма истекает через один день, а другой - что срок его действия истекает через два дня.</span><span class="sxs-lookup"><span data-stu-id="9c87c-439">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-440">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-440">Word</span></span>

- <span data-ttu-id="9c87c-441">Исправлена ошибка, из-за которой подсказка для комментария не отображалась в режиме чтения с цветом страницы &quot;Инверсия&quot;.</span><span class="sxs-lookup"><span data-stu-id="9c87c-441">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="9c87c-442">Исправлена ошибка, из-за которой форматирование курсива терялось после редактирования комментария, выделения курсивом текста и последующей публикации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-442">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="9c87c-443">Исправлена ошибка, из-за которой команды комментария (Редактировать комментарий, Ответить на комментарий, Удалить комментарий, Разрешить комментарий) в контекстном меню комментариев не отображались.</span><span class="sxs-lookup"><span data-stu-id="9c87c-443">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-january-17"></a><span data-ttu-id="9c87c-445">Версия 2002: 17 января</span><span class="sxs-lookup"><span data-stu-id="9c87c-445">Version 2002: January 17</span></span>
<span data-ttu-id="9c87c-446">*Версия 2002 (сборка 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-446">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-448">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-448">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="9c87c-449">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-449">Word</span></span>

- <span data-ttu-id="9c87c-450">**Сообщения электронной почты с уведомлениями об @упоминаниях и примечаниях теперь содержат область предварительного просмотра.** Уведомления по электронной почте об упоминаниях и примечаниях теперь будут содержать область предварительного просмотра с текстом примечания и контекстом, к которому оно относится.</span><span class="sxs-lookup"><span data-stu-id="9c87c-450">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-453">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-453">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-454">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-454">Excel</span></span>

- <span data-ttu-id="9c87c-455">В некоторых случаях средство проверки читаемости не отображало рекомендации для фигур.</span><span class="sxs-lookup"><span data-stu-id="9c87c-455">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-456">Outlook</span></span>

- <span data-ttu-id="9c87c-457">Папки, сохраненные в разделе "Избранное" в области навигации слева, могут периодически исчезать.</span><span class="sxs-lookup"><span data-stu-id="9c87c-457">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-458">PowerPoint</span></span>

- <span data-ttu-id="9c87c-459">Исправлена проблема, из-за которой рукописные фрагменты могли не отображаться полностью или пропускаться при использовании анимации рукописного ввода в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-459">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-january-10"></a><span data-ttu-id="9c87c-461">Версия 2001: 10 января</span><span class="sxs-lookup"><span data-stu-id="9c87c-461">Version 2001: January 10</span></span>
<span data-ttu-id="9c87c-462">*Версия 2001 (сборка 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-462">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-464">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-464">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-465">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-465">Excel</span></span>
- <span data-ttu-id="9c87c-466">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-466">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="9c87c-467">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-467">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="9c87c-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-468">Outlook</span></span>
- <span data-ttu-id="9c87c-469">**Пользователь теперь может сохранять объекты в Word, Excel и Outlook в виде рисунков для Windows.** С помощью этой возможности, ранее представленной в PowerPoint, пользователи теперь могут сохранять объекты в Word, Excel и Outlook в виде рисунков.</span><span class="sxs-lookup"><span data-stu-id="9c87c-469">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="9c87c-470">К объектам относятся фигуры, значки, изображения и многое другое!</span><span class="sxs-lookup"><span data-stu-id="9c87c-470">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="9c87c-471">Это возможность доступна с помощью контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="9c87c-471">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-472">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-472">Word</span></span>
- <span data-ttu-id="9c87c-473">**Легко выделяйте рукописный фрагмент в Word, нарисовав вокруг него фигуру.** С помощью инструмента "Произвольное выделение" на вкладке "Рисование" можно выделять объекты, созданные от руки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-473">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="9c87c-474">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="9c87c-474">Select individual strokes, or whole words.</span></span> <span data-ttu-id="9c87c-475">Это удобно, если у вас много рукописных фрагментов, но вы хотите работать только с некоторыми из них.</span><span class="sxs-lookup"><span data-stu-id="9c87c-475">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="9c87c-476">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-476">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="9c87c-477">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-477">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="9c87c-478">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-478">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-481">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-481">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="9c87c-482">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c87c-482">OneNote</span></span>
- <span data-ttu-id="9c87c-483">При 100% разрешении вкладки страниц могут отображаться слишком маленькими и располагаться близко друг к другу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-483">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-484">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-484">Word</span></span>
- <span data-ttu-id="9c87c-485">При наличии крупного набора примечаний удаление примечания в конце списка может приводить к прокручиванию к верхней части области.</span><span class="sxs-lookup"><span data-stu-id="9c87c-485">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-january-03"></a><span data-ttu-id="9c87c-487">Версия 2001: 3 января</span><span class="sxs-lookup"><span data-stu-id="9c87c-487">Version 2001: January 03</span></span>
<span data-ttu-id="9c87c-488">*Версия 2001 (сборка 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-488">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-490">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-490">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-491">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-491">Excel</span></span>
- <span data-ttu-id="9c87c-492">Некоторые линии границ могут печататься неправильно на бумаге размера A4.</span><span class="sxs-lookup"><span data-stu-id="9c87c-492">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="9c87c-493">Добавление изображения в колонтитул объекта диаграммы на листе с помощью VBA может приводить к ошибке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-493">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="9c87c-494">При форматировании оси диаграммы интервал между надписями ограничивался значением 255.</span><span class="sxs-lookup"><span data-stu-id="9c87c-494">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="9c87c-495">Исправлена проблема, из-за которой возникала ошибка при попытке обновить XML-запрос, в котором URL-адрес источника данных был усечен.</span><span class="sxs-lookup"><span data-stu-id="9c87c-495">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="9c87c-496">В статистике книги указывалось число макросов из всех открытых книг, включая личную книгу макросов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-496">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-497">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-497">Outlook</span></span>
- <span data-ttu-id="9c87c-498">Переключение между папками могло приводить к кратковременному белому "мерцанию" в списке почты или при предварительном просмотре почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-498">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="9c87c-499">Это поведение было более заметным в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="9c87c-499">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-500">PowerPoint</span></span>
- <span data-ttu-id="9c87c-501">Исправлена проблема с объектной моделью, из-за которой вызов метода Shape.Paste приводил к перемещению фокуса на вставленную фигуру.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="9c87c-501">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="9c87c-502">Улучшен сценарий копирования со вставкой.&nbsp;Цикл программного копирования фигуры из слайда PowerPoint и ее вставка на другой слайд мог завершаться сбоем с ошибкой исключения.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="9c87c-502">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="9c87c-503">Анимация в заголовках разделов слайдов отображалась неправильно после свертывания и развертывания заголовков разделов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-503">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-504">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-504">Project</span></span>
- <span data-ttu-id="9c87c-505">Исправлена проблема с неработающим обтеканием текстом в представлениях задач и использования ресурсов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-505">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="9c87c-506">Исправлена проблема, из-за которой при наличии у ресурса нескольких норм затрат значение затрат в назначениях могло быть неверным.</span><span class="sxs-lookup"><span data-stu-id="9c87c-506">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-507">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-507">Word</span></span>
- <span data-ttu-id="9c87c-508">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводила к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="9c87c-508">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="9c87c-509">При совместном редактировании примечание, добавленное с помощью Word Online, могло не отображаться в классической версии Word.</span><span class="sxs-lookup"><span data-stu-id="9c87c-509">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-510">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-510">Office Suite</span></span>
- <span data-ttu-id="9c87c-511">Удалено отображение неверной даты окончания действующей лицензии при попытке сменить единственную лицензию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-511">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-december-13"></a><span data-ttu-id="9c87c-513">Версия 2001: 13 декабря</span><span class="sxs-lookup"><span data-stu-id="9c87c-513">Version 2001: December 13</span></span>
<span data-ttu-id="9c87c-514">*Версия 2001 (сборка 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-514">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-516">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-516">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-517">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-517">Outlook</span></span>

- <span data-ttu-id="9c87c-518">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="9c87c-518">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="9c87c-519">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-519">Messages you drag will be shared with all group members.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-522">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-522">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c87c-523">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-523">Access</span></span>
- <span data-ttu-id="9c87c-524">Выполнение запроса на объединение, который ссылается на связанные таблицы ODBC и содержит предложение Order By, приводит к сбою 64-разрядной версии Access.</span><span class="sxs-lookup"><span data-stu-id="9c87c-524">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="9c87c-525">Суммирование данных из запросов на объединение в Access (O365) может приводить к усечению десятичных данных.</span><span class="sxs-lookup"><span data-stu-id="9c87c-525">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="9c87c-526">Интерфейсы COM для ACE не предоставляются для использования вне приложений Office.</span><span class="sxs-lookup"><span data-stu-id="9c87c-526">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-527">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-527">Excel</span></span>
- <span data-ttu-id="9c87c-528">Вставка трехмерной модели (анимированной или статической) и попытка сохранить файл как рисунок не работает.</span><span class="sxs-lookup"><span data-stu-id="9c87c-528">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="9c87c-529">Сочетание клавиш (ALT+CTRL+7/8) для отправки отзыва из представления Backstage вступает в конфликт с клавиатурами AZERTY (ALT-GR+7/8).</span><span class="sxs-lookup"><span data-stu-id="9c87c-529">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="9c87c-530">Воздействие: пользователи не могут использовать некоторые символы, например '\'.</span><span class="sxs-lookup"><span data-stu-id="9c87c-530">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-531">Outlook</span></span>
- <span data-ttu-id="9c87c-532">Исправлена проблема, приводившая к отправке сообщения электронной почты на неправильный адрес получателя.</span><span class="sxs-lookup"><span data-stu-id="9c87c-532">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="9c87c-533">Исправлена проблема, из-за которой приложение Outlook неверно позволяло пользователям с доступом к почтовому ящику для &quot;чтения&quot; изменить прочтенное или непрочтенное состояние сообщения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-533">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="9c87c-534">Отзыв сертификата безопасности на веб-сайте не воспроизводится службой поддержки продукта.</span><span class="sxs-lookup"><span data-stu-id="9c87c-534">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="9c87c-535">Чтобы устранить основную причину этой проблемы, требуется добавить ведение журнала.</span><span class="sxs-lookup"><span data-stu-id="9c87c-535">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="9c87c-536">Исправлена проблема, из-за которой для пользователей отображались сбои синхронизации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-536">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-537">PowerPoint</span></span>
- <span data-ttu-id="9c87c-538">Вставка трехмерной модели (анимированной или статической) и попытка сохранить файл как рисунок не работает.</span><span class="sxs-lookup"><span data-stu-id="9c87c-538">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-539">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-539">Project</span></span>
- <span data-ttu-id="9c87c-540">Работа задачи не вычисляется в сводке для дочерних задач, запланированных вручную.</span><span class="sxs-lookup"><span data-stu-id="9c87c-540">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="9c87c-541">Код VBA Project, вызванный кнопкой ленты может не работать при попытке сохранить серверные проекты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-541">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="9c87c-542">Если приложение Project не запущено, при открытии файлов Project из библиотеки документов SharePoint появляется сообщение об ошибке и файл не открывается.</span><span class="sxs-lookup"><span data-stu-id="9c87c-542">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-543">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-543">Word</span></span>
- <span data-ttu-id="9c87c-544">Сохранение существующих файлов может не работать.</span><span class="sxs-lookup"><span data-stu-id="9c87c-544">Saving existing files may not work.</span></span>
- <span data-ttu-id="9c87c-545">Использование клавиш со стрелками в окне редактора правописания может приводить к периодическому мерцанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-545">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="9c87c-546">При разрешении элементов к исполнению связанные примечания могут не преобразовываться в примечания пунктов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-546">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="9c87c-547">Вставка трехмерной модели (анимированной или статической) и попытка сохранить файл как рисунок не работает.</span><span class="sxs-lookup"><span data-stu-id="9c87c-547">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-548">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-548">Office Suite</span></span>
- <span data-ttu-id="9c87c-549">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="9c87c-549">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="9c87c-550">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="9c87c-550">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-december-06"></a><span data-ttu-id="9c87c-552">Версия 1912: 6 декабря</span><span class="sxs-lookup"><span data-stu-id="9c87c-552">Version 1912: December 06</span></span>
<span data-ttu-id="9c87c-553">*Версия 1912 (сборка 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-553">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-555">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-556">Outlook</span></span>

- <span data-ttu-id="9c87c-557">**Дополнительные параметры электронной почты группы.** Эта функция позволяет группам пользователей настраивать сообщения или события, получаемые и отслеживаемые в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="9c87c-557">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="9c87c-558">**Политика именования групп.** Политика именования групп позволяет ИТ-администратору стандартизировать имена групп, созданных пользователями в организации, а также управлять ими.</span><span class="sxs-lookup"><span data-stu-id="9c87c-558">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="9c87c-559">Администратор может требовать добавления специального префикса и суффикса к имени группы при ее создании и может запретить использование определенных слов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-559">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="9c87c-560">Это позволяет уменьшить использование недопустимых слов в названиях групп, а также управлять отображением групп в каталоге.</span><span class="sxs-lookup"><span data-stu-id="9c87c-560">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="9c87c-561">Политика именования также помогает организациям развертывать сайты групп для их классификации по отделам.</span><span class="sxs-lookup"><span data-stu-id="9c87c-561">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-562">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-562">Office Suite</span></span>

- <span data-ttu-id="9c87c-563">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-563">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="9c87c-564">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="9c87c-564">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-567">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-567">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-568">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-568">Excel</span></span>
- <span data-ttu-id="9c87c-569">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="9c87c-569">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="9c87c-570">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="9c87c-570">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="9c87c-571">Отключение аппаратного ускорения графики при использовании разрешения 4K может приводить к задержке отображения ячеек при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-571">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="9c87c-572">При удалении длинной формулы, пересекающей границу ячейки, она по-прежнему может отображаться за границей ячейки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-572">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="9c87c-573">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="9c87c-573">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="9c87c-574">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-574">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="9c87c-575">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c87c-575">OneNote</span></span>
- <span data-ttu-id="9c87c-576">Приложение OneNote может не открываться при использовании надстройки "Заметки к собранию" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="9c87c-576">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-577">Outlook</span></span>
- <span data-ttu-id="9c87c-578">Метки политики хранения могут отображать срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="9c87c-578">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="9c87c-579">В карточках контактов может появляться пустое место при использовании японского языкового пакета.</span><span class="sxs-lookup"><span data-stu-id="9c87c-579">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="9c87c-580">Иногда изменяются размеры изображений, вставленных в сообщения электронной почты Outlook.</span><span class="sxs-lookup"><span data-stu-id="9c87c-580">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-581">PowerPoint</span></span>
- <span data-ttu-id="9c87c-582">Если на слайде пользователя в облачном файле имеется два (или более) видеоролика, видеоизображения отображаются правильно, но когда пользователь щелкает каждое из них для воспроизведения, видеоконтент оказывается одинаковым.</span><span class="sxs-lookup"><span data-stu-id="9c87c-582">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="9c87c-583">В некоторых случаях прокрутка на сенсорных устройствах не работает.</span><span class="sxs-lookup"><span data-stu-id="9c87c-583">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="9c87c-584">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-584">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="9c87c-585">Безопасные ссылки, ведущие из одного приложения Office в другое, могут не запускать связанное приложение.</span><span class="sxs-lookup"><span data-stu-id="9c87c-585">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-586">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-586">Project</span></span>
- <span data-ttu-id="9c87c-587">Приложение Project может аварийно завершать работу при использовании функции сравнения проектов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-587">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="9c87c-588">Если используется темный режим при переходе в панель инспектора в задаче, содержащей ресурс с превышением доступности, вы не сможете прочесть таблицу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-588">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="9c87c-589">Настройка трудозатрат для задач без заданий округляется до одного дня.</span><span class="sxs-lookup"><span data-stu-id="9c87c-589">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-590">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-590">Word</span></span>
- <span data-ttu-id="9c87c-591">Может не работать сохранение файла после слияния при определенных условиях.</span><span class="sxs-lookup"><span data-stu-id="9c87c-591">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="9c87c-592">Диспетчер стандартных блоков может отображать неправильное оповещение: &quot;Были изменены стили, стандартные блоки&quot;.</span><span class="sxs-lookup"><span data-stu-id="9c87c-592">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="9c87c-593">Область примечаний иногда перезагружается при использовании команд копирования и вставки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-593">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="9c87c-594">Примечания иногда вставляются в неправильном порядке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-594">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="9c87c-595">При применении к существующим документам шаблона, состоящего из многоуровневого списка с пользовательскими стилями, стили могут не сохраняться при определенных условиях.</span><span class="sxs-lookup"><span data-stu-id="9c87c-595">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="9c87c-596">Изменение границы разделенного экрана может приводить к дополнительному разделению экрана.</span><span class="sxs-lookup"><span data-stu-id="9c87c-596">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="9c87c-597">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-597">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="9c87c-598">При упоминании пользователя в карточке примечания может отображаться формат JSON.</span><span class="sxs-lookup"><span data-stu-id="9c87c-598">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="9c87c-599">Безопасные ссылки, ведущие из одного приложения Office в другое, могут не запускать связанное приложение.</span><span class="sxs-lookup"><span data-stu-id="9c87c-599">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-600">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-600">Office Suite</span></span>
- <span data-ttu-id="9c87c-601">В продуктах на японском языке имя и фамилия пользователя учетной записи могут отображаться в неправильном порядке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-601">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="9c87c-602">При наведении указателя мыши на примечание может появляться рамка вокруг примечания.</span><span class="sxs-lookup"><span data-stu-id="9c87c-602">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-november-15"></a><span data-ttu-id="9c87c-604">Версия 1912, 15 ноября</span><span class="sxs-lookup"><span data-stu-id="9c87c-604">Version 1912: November 15</span></span>
<span data-ttu-id="9c87c-605">*Версия 1912 (сборка 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-605">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-607">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-607">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="9c87c-608">Службы аналитики</span><span class="sxs-lookup"><span data-stu-id="9c87c-608">Insights Services</span></span>
- <span data-ttu-id="9c87c-609">**Запросы на естественном языке в инструменте "Идеи" в Excel.** Новая возможность "Идеи", чтобы задавать вопрос о ваших данных на естественном языке в Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-609">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-612">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-613">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-613">Excel</span></span>
- <span data-ttu-id="9c87c-614">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-614">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="9c87c-615">Редактирование формул динамического массива в ячейке может привести к выравниванию текста за границами ячейки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-615">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-616">Outlook</span></span>
- <span data-ttu-id="9c87c-617">Добавлена возможность применять конфигурацию S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="9c87c-617">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="9c87c-618">Встроенные изображения могут отображаться в размере меньше предполагаемого.</span><span class="sxs-lookup"><span data-stu-id="9c87c-618">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-619">PowerPoint</span></span>
- <span data-ttu-id="9c87c-620">Курсор может исчезнуть после перемещения фокуса с текста.</span><span class="sxs-lookup"><span data-stu-id="9c87c-620">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-621">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-621">Project</span></span>
- <span data-ttu-id="9c87c-622">У пользователей может возникать ошибка лицензирования.</span><span class="sxs-lookup"><span data-stu-id="9c87c-622">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="9c87c-623">Возможна установка неверной даты кнопкой "Сегодня" в средстве выбора даты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-623">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-624">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-624">Word</span></span>
- <span data-ttu-id="9c87c-625">Иногда щелчок правой кнопкой мыши не выделяет все слово.</span><span class="sxs-lookup"><span data-stu-id="9c87c-625">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="9c87c-626">Курсор может оставаться активным в объекте после преобразования в предлагаемый формат.</span><span class="sxs-lookup"><span data-stu-id="9c87c-626">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="9c87c-627">В некоторых ситуациях изображения в сообщениях могут быть неправильно масштабированы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-627">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="9c87c-628">В некоторых темах иногда сложно определить выбранное примечание.</span><span class="sxs-lookup"><span data-stu-id="9c87c-628">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="9c87c-629">При выборе маркера примечаний теперь должна отображаться современная область примечаний, если она скрыта в переключателе области.</span><span class="sxs-lookup"><span data-stu-id="9c87c-629">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-630">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-630">Office Suite</span></span>
- <span data-ttu-id="9c87c-631">При ответе на примечание возможно вертикальное расширение текстового поля за край области.</span><span class="sxs-lookup"><span data-stu-id="9c87c-631">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-november-08"></a><span data-ttu-id="9c87c-633">Версия 1912: 8 ноября</span><span class="sxs-lookup"><span data-stu-id="9c87c-633">Version 1912: November 08</span></span>
<span data-ttu-id="9c87c-634">*Версия 1912 (сборка 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-634">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-636">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-636">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="9c87c-637">Жизненный цикл пользователя</span><span class="sxs-lookup"><span data-stu-id="9c87c-637">User Lifecycle</span></span>
- <span data-ttu-id="9c87c-638">**Улучшение взаимодействия для активации AFO.** Обновления экранов, демонстрируемых пользователям при активации Office, входящего в состав нового компьютера.</span><span class="sxs-lookup"><span data-stu-id="9c87c-638">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-639">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-639">Word</span></span>
- <span data-ttu-id="9c87c-640">**Новые и улучшенные возможности для видео из Интернета в Word.** Новые и более безопасные функции для видео из Интернета, предназначенные для вставки новых и воспроизведения существующих видео в Word.</span><span class="sxs-lookup"><span data-stu-id="9c87c-640">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-643">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-644">Outlook</span></span>
- <span data-ttu-id="9c87c-645">Периодические сбои при работе с содержимым разных папок.</span><span class="sxs-lookup"><span data-stu-id="9c87c-645">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-646">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-646">Office Suite</span></span>
- <span data-ttu-id="9c87c-647">Вставка диаграммы из Excel в PowerPoint может уменьшать размер диаграммы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-647">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-november-01"></a><span data-ttu-id="9c87c-649">Версия 1911: 1 ноября</span><span class="sxs-lookup"><span data-stu-id="9c87c-649">Version 1911: November 01</span></span>
<span data-ttu-id="9c87c-650">*Версия 1911 (сборка 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-650">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-652">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-652">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-653">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-653">Excel</span></span>
- <span data-ttu-id="9c87c-654">**Использование контекста вместе с объектами SVG.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Office.</span><span class="sxs-lookup"><span data-stu-id="9c87c-654">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="9c87c-655">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-655">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-656">PowerPoint</span></span>
- <span data-ttu-id="9c87c-657">**Использование контекста вместе с объектами SVG.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Office.</span><span class="sxs-lookup"><span data-stu-id="9c87c-657">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="9c87c-658">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-658">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="9c87c-659">Visio</span><span class="sxs-lookup"><span data-stu-id="9c87c-659">Visio</span></span>
- <span data-ttu-id="9c87c-660">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-660">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="9c87c-661">[Подробнее](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="9c87c-661">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-662">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-662">Word</span></span>
- <span data-ttu-id="9c87c-663">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-663">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="9c87c-664">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="9c87c-664">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="9c87c-665">**Другие пользователи быстро просматривают внесенные вами изменения.** С улучшенными функциями совместного редактирования участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо прежде.</span><span class="sxs-lookup"><span data-stu-id="9c87c-665">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-668">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-669">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-669">Excel</span></span>
- <span data-ttu-id="9c87c-670">Исправлена проблема, из-за которой мог происходить сбой программы Excel при изменении защищенного файла из ненадежного сетевого ресурса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-670">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="9c87c-671">Исправлена проблема, из-за которой удаление листов, содержащих спарклайны со ссылками на данные других листов, могло привести к обозначению файла как поврежденного при повторном открытии.</span><span class="sxs-lookup"><span data-stu-id="9c87c-671">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="9c87c-672">Устранена проблема, из-за которой можно было получить неверный результат при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="9c87c-672">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="9c87c-673">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-673">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="9c87c-674">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-674">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-675">Outlook</span></span>
- <span data-ttu-id="9c87c-676">Перенаправленная электронная почта может лишиться внедренных изображений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-676">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="9c87c-677">Средство поиска помещений может отображать значение &quot;Нет&quot; для доступных помещений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-677">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="9c87c-678">Пользователи не могут создавать профили Outlook со строгим ограничением клиента.</span><span class="sxs-lookup"><span data-stu-id="9c87c-678">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-679">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-679">PowerPoint</span></span>
- <span data-ttu-id="9c87c-680">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-680">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-681">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-681">Project</span></span>
- <span data-ttu-id="9c87c-682">Пользователь не может отметить задачу как завершенную, и ее выполнение остается на уровне 99 %.</span><span class="sxs-lookup"><span data-stu-id="9c87c-682">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="9c87c-683">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="9c87c-683">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-684">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-684">Word</span></span>
- <span data-ttu-id="9c87c-685">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-685">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="9c87c-686">Открытие устаревших документов с последующим переходом на вкладку "Сведения" может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-686">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="9c87c-687">Предложения проверки не отображаются в контекстных меню.</span><span class="sxs-lookup"><span data-stu-id="9c87c-687">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="9c87c-688">Политики содержимого применяются к комментариям некорректно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-688">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="9c87c-689">Старые комментарии, написанные темным текстом, не видны в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="9c87c-689">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="9c87c-690">При использовании автозамены в языковой паре корейский-английский могут отображаться некорректные символы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-690">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="9c87c-691">Могут применяться метки менее строгих политик, когда приоритет должна иметь метка более строгой политики.</span><span class="sxs-lookup"><span data-stu-id="9c87c-691">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="9c87c-692">Ссылки cid: теперь связь с изображениями из сообщений Outlook&nbsp;может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-692">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="9c87c-693">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-693">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="9c87c-694">Поиск из области навигации может завершаться неудачей.</span><span class="sxs-lookup"><span data-stu-id="9c87c-694">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-695">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-695">Office Suite</span></span>
- <span data-ttu-id="9c87c-696">Некоторые рисунки могут не отображаться в предварительном просмотре или в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-696">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="9c87c-697">Символы катаканы могут неправильно отображаться в вертикальной надписи.</span><span class="sxs-lookup"><span data-stu-id="9c87c-697">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="9c87c-698">Попытка сохранить файл в сетевой папке, с которой потеряна связь, может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="9c87c-698">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-october-25"></a><span data-ttu-id="9c87c-700">Версия 1911: 25 октября</span><span class="sxs-lookup"><span data-stu-id="9c87c-700">Version 1911: October 25</span></span>
<span data-ttu-id="9c87c-701">*Версия 1911 (сборка 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-701">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-703">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-703">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="9c87c-704">Visio</span><span class="sxs-lookup"><span data-stu-id="9c87c-704">Visio</span></span>

- <span data-ttu-id="9c87c-705">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-705">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="9c87c-706">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-706">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="9c87c-707">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-707">Word</span></span>

- <span data-ttu-id="9c87c-708">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="9c87c-708">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="9c87c-709">**Другие пользователи быстро просматривают внесенные вами изменения.** С улучшенными функциями совместного редактирования участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо прежде.</span><span class="sxs-lookup"><span data-stu-id="9c87c-709">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="9c87c-712">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="9c87c-712">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9c87c-713">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-713">Access</span></span>

- <div><span data-ttu-id="9c87c-714"><span>Число записей может быть неверным</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-714"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="9c87c-715">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-715">Excel</span></span>

- <div><span data-ttu-id="9c87c-716"><span>Значительно повышена производительность при удалении столбцов с объединенными ячейками</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-716"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="9c87c-717"><span>Пользователям не удается сохранять записи в формате книги Excel в Office 365</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-717"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="9c87c-718"><span>Флажки могут отображаться неправильно</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-718"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="9c87c-719"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-719"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="9c87c-720"><span>Некоторые функции VBA возвращают ошибку в новых типах диаграмм</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-720"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="9c87c-721"><span>В диалоговых окнах "Выбор источника данных" не учитывается регистр для некоторых полей</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-721"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-722">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-723"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-723"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="9c87c-724">Publisher</span><span class="sxs-lookup"><span data-stu-id="9c87c-724">Publisher</span></span>

- <div><span data-ttu-id="9c87c-725"><span>Фигуры могут отображаться за пределами границы рисунка</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-725"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-726">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-726">Word</span></span>

- <div><span data-ttu-id="9c87c-727"><span>Фигуры могут отображаться за пределами границы рисунка</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-727"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="9c87c-728"><span>Обтекание текста может оказаться трудной задачей</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-728"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="9c87c-729"><span>Пользователю не удается перейти к отдельному элементу в редакторе</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-729"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="9c87c-730"><span>Грамматические и орфографические ошибки могут не выделяться</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-730"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="9c87c-731"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-731"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="9c87c-732"><span>Не удается открыть карточку контакта после применения форматирования к @упоминанию</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-732"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="9c87c-733"><span>Решена проблема, из-за которой пользователям не удается сохранить документы Word, Excel и PowerPoint.&nbsp; Эта проблема возникает у пользователей, создающих файл и использующих параметр &quot;Сохранить как модельное диалоговое окно&quot; после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-733"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c87c-734">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-734">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-735"><span>Проблема с производительностью при использовании фигур в Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-735"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-october-18"></a><span data-ttu-id="9c87c-737">Версия 1911: 18 октября</span><span class="sxs-lookup"><span data-stu-id="9c87c-737">Version 1911: October 18</span></span>
<span data-ttu-id="9c87c-738">*Версия 1911 (сборка 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-738">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-740">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-740">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="9c87c-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-741">Outlook</span></span>

- <span data-ttu-id="9c87c-742">**Отправка писем со специальными возможностями пользователям, которым они нужны.** Outlook отображает подсказку, помогающую обеспечить доступность контента при отправке пользователю, который предпочитает контент с поддержкой специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="9c87c-742">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-743">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-743">PowerPoint</span></span>

- <span data-ttu-id="9c87c-744">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="9c87c-744">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9c87c-745">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-745">Office Suite</span></span>

- <span data-ttu-id="9c87c-746">**Центр отправки заменяется интерфейсом "Файлы, требующие внимания".** Центр отправки заменяется интерфейсом "Файлы, требующие внимания", доступным в приложениях Office в разделе "Файл" > "Открыть".</span><span class="sxs-lookup"><span data-stu-id="9c87c-746">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="9c87c-747">Этот новый интерфейс более современный, интегрированный и менее навязчивый по сравнению с Центром отправки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-747">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-750">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-750">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-751">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-751">Excel</span></span>

- <div><span data-ttu-id="9c87c-752"><span>Исправлена проблема, из-за которой флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-752"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="9c87c-753"><span>Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-753"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-754">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-754">Outlook</span></span>

- <div><span data-ttu-id="9c87c-755"><span>Обнаружена проблема, которая может вызывать нарушение цифровых подписей при подписании сообщения, содержащего вложение с цифровой подписью</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-755"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="9c87c-756"><span>Обнаружена проблема, из-за которой длинные имена файлов усекались после перетаскивания в текст сообщения</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-756"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="9c87c-757">Обнаружена проблема, из-за которой поле поиска может исчезать, если лента настроена на автоматическое скрытие</span><span class="sxs-lookup"><span data-stu-id="9c87c-757">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-758">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-759"><span>Обнаружена проблема, из-за которой пропорции при предварительном просмотре слайда блокировались или разблокировались неправильно.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-759"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="9c87c-760">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-760">Project</span></span>

- <div><span data-ttu-id="9c87c-761">Обнаружена проблема, из-за которой примечания могут не сохраняться, если вводятся при выполнении задач обновления</span><span class="sxs-lookup"><span data-stu-id="9c87c-761">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="9c87c-762">Обнаружена проблема, из-за которой файл может блокироваться пользователем, но в сообщении об ошибке не отображается имя пользователя</span><span class="sxs-lookup"><span data-stu-id="9c87c-762">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="9c87c-763"><span>Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-763"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-764">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-764">Word</span></span>

- <div><span data-ttu-id="9c87c-765"><span>Выявлена проблема с просмотром примечаний при использовании средства чтения с экрана</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-765"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="9c87c-766"><span>Обнаружена проблема, из-за которой некоторые замечания неправильно определялись как орфографические или грамматические замечания</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-766"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="9c87c-767"><span>Обнаружена проблема, из-за которой фокус иногда не перемещается в диалоговое окно создания примечания</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-767"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c87c-768">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-768">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-769"><span>Исправлена проблема, из-за которой обновление могло блокироваться неверным сообщением об ошибке &quot;Уже запущен другой процесс установки&quot;</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-769"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="9c87c-770"><span>Обнаружена проблема, которая может влиять на синхронизацию локального ресурса с облачным</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-770"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="9c87c-771"><span>Обнаружена проблема, из-за которой приветственное сообщение содержит неправильную ссылку</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-771"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-october-11"></a><span data-ttu-id="9c87c-773">Версия 1910: 11 октября</span><span class="sxs-lookup"><span data-stu-id="9c87c-773">Version 1910: October 11</span></span>
<span data-ttu-id="9c87c-774">*Версия 1910 (сборка 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-774">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-778">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-778">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-779">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-779">Excel</span></span>

- <div><span data-ttu-id="9c87c-780">Решена проблема со вставкой файлов в качестве объектов из OneDrive</span><span class="sxs-lookup"><span data-stu-id="9c87c-780">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="9c87c-781">Решена проблема, из-за которой не удавалось правильно применять формат гиперссылки к некоторому содержимому</span><span class="sxs-lookup"><span data-stu-id="9c87c-781">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="9c87c-782">Решена проблема, из-за которой формулы со структурированными абсолютными ссылками могли изменяться неправильно</span><span class="sxs-lookup"><span data-stu-id="9c87c-782">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="9c87c-783">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-783">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="9c87c-784">Решена проблема, из-за которой содержимое, скопированное из Excel, могло отображаться неправильно при вставке в другие приложения Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-784">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="9c87c-785">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм</span><span class="sxs-lookup"><span data-stu-id="9c87c-785">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-786">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-786">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-787">Обнаружена проблема, из-за которой устройства ARC могли терять подключение при работе в AirSpace WinComp</span><span class="sxs-lookup"><span data-stu-id="9c87c-787">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-788">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-788">Word</span></span>

- <div><span data-ttu-id="9c87c-789">Решена проблема со вставкой файлов в качестве объектов из OneDrive</span><span class="sxs-lookup"><span data-stu-id="9c87c-789">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="9c87c-790">Улучшены этапы восстановления для и<span>справления проблемы, приводившей к удалению графического содержимого из цепочек электронной почты.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-790">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-october-04"></a><span data-ttu-id="9c87c-792">Версия 1910: 4 октября</span><span class="sxs-lookup"><span data-stu-id="9c87c-792">Version 1910: October 04</span></span>
<span data-ttu-id="9c87c-793">*Версия 1910 (сборка 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-793">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-795">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-795">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-796">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-796">Excel</span></span>

- <span data-ttu-id="9c87c-797">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-797">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="9c87c-798">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-798">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-801">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-801">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-802">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-802">Excel</span></span>

- <div><span data-ttu-id="9c87c-803"><span>Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-803"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="9c87c-804"><span>Исправлена проблема, которая могла блокировать обновление сводных таблиц во время совместного редактирования</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-804"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="9c87c-805">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-805">Access</span></span>

- <div><span data-ttu-id="9c87c-806">Исправлена проблема, из-за которой пользователи могли сталкиваться с ошибкой &quot;несогласованного состояния&quot; при использовании общей базы данных.</span><span class="sxs-lookup"><span data-stu-id="9c87c-806">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-807">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-807">Outlook</span></span>

- <div><span data-ttu-id="9c87c-808"><span>Исправлена проблема, которая могла приводить к дублированию почтовых папок</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-808"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="9c87c-809"><span>Исправлена проблема, из-за которой могло неправильно возникать сообщение об ошибке при попытке отправить письмо, зашифрованное с помощью S/MIME</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-809"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="9c87c-810"><span>Исправлена проблема, из-за которой иногда мог возникать сбой при получении пользователем сообщения "Пропущенная беседа" из Skype</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-810"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="9c87c-811"><span>Исправлена проблема, которая могла приводить к утечке памяти</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-811"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="9c87c-812"><span>Исправлена проблема, которая могла приводить к изменению имени отправителя при сохранении в виде черновика</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-812"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-813">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="9c87c-814">Исправлена проблема, из-за которой могли повреждаться объекты TextRange после вставки текста в колонтитулы или заполнители номеров страниц слайдов в образце слайдов и макете слайдов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-814">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="9c87c-815">Исправлена проблема, не позволявшая создавать гиперссылку при вставке текста с гиперссылкой.</span><span class="sxs-lookup"><span data-stu-id="9c87c-815">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="9c87c-816">Исправлена проблема, которая могла мешать правильной работе статистических данных.</span><span class="sxs-lookup"><span data-stu-id="9c87c-816">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-817">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-817">Word</span></span>

- <div><span data-ttu-id="9c87c-818"><span>Исправлена проблема, из-за которой не фиксировался цвет шрифта</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-818"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c87c-819">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-819">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-820">Исправлена проблема, из-за которой мог предлагаться журнал версий, когда эта функция отключена.</span><span class="sxs-lookup"><span data-stu-id="9c87c-820">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-27"></a><span data-ttu-id="9c87c-822">Версия 1910: 27 сентября</span><span class="sxs-lookup"><span data-stu-id="9c87c-822">Version 1910: September 27</span></span>
<span data-ttu-id="9c87c-823">*Версия 1910 (сборка 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-823">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-827">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-827">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-828">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-828">Excel</span></span>

- <div><span data-ttu-id="9c87c-829"><span>Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-829"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-830">Outlook</span></span>

- <div><span data-ttu-id="9c87c-831"><span>Исправлена проблема, которая могла приводить к ошибкам с разрешениями при взаимодействии с общими папками календаря</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-831"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="9c87c-832"><span>Исправлена проблема, которая могла мешать пользователям добавлять вложения в календари</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-832"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="9c87c-833"><span>Исправлена проблема, приводившая к появлению сообщений об ошибках при ответе на сообщение с цифровой подписью</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-833"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-834">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-834">Word</span></span>

- <div><span data-ttu-id="9c87c-835"><span>Исправлена проблема, которая могла приводить к ошибкам с масштабированием при печати на принтерах Deskjet</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-835"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c87c-836">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-836">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-837"><span>Исправлена проблема, из-за которой к полужирному тексту среднего размера могли применяться неправильные стили</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-837"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="9c87c-838"><span>Исправлена проблема, из-за которой для пользователя могло отображаться неверное сообщение об ошибке при закрытии файла, ожидающего отправки</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-838"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-20"></a><span data-ttu-id="9c87c-840">Версия 1910: 20 сентября</span><span class="sxs-lookup"><span data-stu-id="9c87c-840">Version 1910: September 20</span></span>
<span data-ttu-id="9c87c-841">*Версия 1910 (сборка 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-841">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-845">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-845">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-846">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-846">Excel</span></span>

- <div><span data-ttu-id="9c87c-847"><span>Исправлена проблема, из-за которой Excel иногда зависал при запуске</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-847"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="9c87c-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-848">Outlook</span></span>

- <div><span data-ttu-id="9c87c-849"><span>Мы значительно улучшили производительность при выборе помещения, если доступно много помещений</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-849"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="9c87c-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Исправлена проблема, которая могла мешать синхронизации почтовых ящиков клиентов с почтовыми ящиками в Outlook при переходе на современную проверку подлинности в Office 365.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="9c87c-851"><span>Исправлена проблема, из-за которой некоторые символы в метках подписей не отображались в выпадающем меню</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-851"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="9c87c-852">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-852">Project</span></span>

- <div><span data-ttu-id="9c87c-853"><span>Исправлена проблема, которая могла приводить к сбою при замене корпоративного ресурса локальным ресурсом</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-853"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-854">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-854">Word</span></span>

- <div><span data-ttu-id="9c87c-855"><span>Исправлена проблема, которая могла мешать правильной работе синхронной прокрутки в режиме черновика</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-855"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="9c87c-856">Исправлена проблема, из-за которой всплывающие подсказки могли неправильно отображаться после сохранения документа в первый раз</span><span class="sxs-lookup"><span data-stu-id="9c87c-856">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-13"></a><span data-ttu-id="9c87c-858">Версия 1910: 13 сентября</span><span class="sxs-lookup"><span data-stu-id="9c87c-858">Version 1910: September 13</span></span>
<span data-ttu-id="9c87c-859">*Версия 1910 (сборка 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-859">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-861">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-861">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-862">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-862">Excel</span></span>

- <div><span data-ttu-id="9c87c-863"><span>Исправлена проблема, которая могла мешать пользователям вставлять гиперссылки в некоторых защищенных листах</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-863"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-864">Outlook</span></span>

- <div><span data-ttu-id="9c87c-865"><span>Исправлена проблема, из-за которой пользовательский интерфейс мог зависать в компактном представлении</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-865"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-866">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-866">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-867"><span>Исправлена проблема, из-за которой у пользователя могла возникать ошибка при печати в PDF</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-867"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="9c87c-868">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-868">Project</span></span>

- <div><span data-ttu-id="9c87c-869"><span>Исправлена проблема, из-за которой <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">изменение значения трудозатрат в суммарной задаче могло приводить к сбою при включенной функции защищенных значений трудозатрат</span></span></span><span class="sxs-lookup"><span data-stu-id="9c87c-869"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="9c87c-870"><font size=2 style="background-color:rgb(255, 255, 255);">Исправлена проблема, которая могла блокировать возможность синхронизации событий с корпоративными календарями</font></span><span class="sxs-lookup"><span data-stu-id="9c87c-870"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="9c87c-871">Набор Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-871">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-872"><span>Исправлена проблема, которая могла приводить к повторному предупреждению об удалении локальных версий файла</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-872"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-06"></a><span data-ttu-id="9c87c-874">Версия 1910: 06 сентября</span><span class="sxs-lookup"><span data-stu-id="9c87c-874">Version 1910: September 06</span></span>
<span data-ttu-id="9c87c-875">*Версия 1910 (сборка 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-875">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-877">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-877">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-878">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-878">Excel</span></span>

- <span data-ttu-id="9c87c-879">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-879">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="9c87c-880">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="9c87c-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-881">PowerPoint</span></span>

- <span data-ttu-id="9c87c-882">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-882">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="9c87c-883">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-883">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="9c87c-884">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-884">Word</span></span>

- <span data-ttu-id="9c87c-885">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-885">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="9c87c-886">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-886">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-889">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-889">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-890">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-890">Excel</span></span>

- <div><span data-ttu-id="9c87c-891"><span>Исправлена проблема, из-за которой имя шрифта на ленте могло отличаться от используемого шрифта</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-891"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-892">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-892">Outlook</span></span>

- <div><span data-ttu-id="9c87c-893"><span>Исправлена проблема, которая приводила к неправильному потреблению ресурсов в Outlook при отключении защищенного режима для ограниченных сайтов в Internet Explorer</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-893"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="9c87c-894"><span>Исправлена проблема, из-за которой при вставке текста из источника ANSI иногда появлялись символы Юникода</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-894"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="9c87c-895"><span>Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-895"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-896">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-896">Word</span></span>

- <div><span data-ttu-id="9c87c-897"><span>Исправлена проблема с сохранением форматирования таблиц</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-897"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="9c87c-898"><span>Исправлена проблема, которая могла приводить к сбою сочетания клавиш CTRL + V</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-898"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1909-august-30"></a><span data-ttu-id="9c87c-900">Версия 1909: 30 августа</span><span class="sxs-lookup"><span data-stu-id="9c87c-900">Version 1909: August 30</span></span>
<span data-ttu-id="9c87c-901">*Версия 1909 (сборка 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="9c87c-901">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="9c87c-903">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-903">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-904">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-904">Access</span></span>

- <span data-ttu-id="9c87c-905">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="9c87c-905">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-906">PowerPoint</span></span>

- <span data-ttu-id="9c87c-907">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="9c87c-907">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="9c87c-908">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-908">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="9c87c-911">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-911">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="9c87c-912">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-912">Excel</span></span>

- <div><span data-ttu-id="9c87c-913"><span>Исправлена проблема, из-за которой возникал конфликт между подсказкой клавиш для функции&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">конфиденциальности </span>и&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">другой подсказкой клавиш.</span></span></span><span class="sxs-lookup"><span data-stu-id="9c87c-913"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="9c87c-914"><span>Исправлена проблема, возникавшая при работе с общей книгой при попытке ее сохранения.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-914"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="9c87c-915"><span>Исправлена проблема, из-за которой в Excel указывались только первые 16 надстроек из значений реестра "\Excel\Add-in Manager".<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="9c87c-915"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="9c87c-916"><span>Исправлена проблема, из-за которой функция ЧАСТОТА() возвращает неправильные результаты.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-916"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="9c87c-917"><span>Значительно повышена производительность фильтрации по цвету.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-917"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="9c87c-918"><span>Исправлена проблема для пользователей Surface, из-за которой перемещение мыши могло интерпретироваться как событие щелчка мыши.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-918"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="9c87c-919"><span>Исправлена проблема, не позволявшая использовать навигацию с помощью клавиатуры в диалоговом окне "Найти и заменить".</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-919"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="9c87c-920"><span>Исправлена проблема, из-за которой неправильно отображались названия некоторых шрифтов.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-920"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="9c87c-921"><span>Исправлена проблема, препятствовавшая отображению формата CSV в качестве поддерживаемого типа файла</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-921"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="9c87c-922">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-922">Access</span></span>

- <div><span data-ttu-id="9c87c-923">Исправлена проблема, из-за которой пользователи могли сталкиваться с ошибкой &quot;несогласованного состояния&quot; при использовании общей базы данных.</span><span class="sxs-lookup"><span data-stu-id="9c87c-923">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="9c87c-924"><span>Исправлена проблема, которая могла приводить к появлению элемента управления "Выбор даты", когда этого не требовалось.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-924"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-925">Outlook</span></span>

- <div><span data-ttu-id="9c87c-926"><span>Исправлена проблема, из-за которой HTML-содержимое не отображалось для некоторых пользователей POP3.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-926"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="9c87c-927"><span>Исправлена проблема для удаления неработающей ссылки "Планировщик" из меню переполнения в карточке контакта при работе в средах, в которых этот компонент недоступен.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-927"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="9c87c-928">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c87c-928">OneNote</span></span>

- <div><span data-ttu-id="9c87c-929"><span>Исправлена проблема, связанная с тем, что &nbsp;фоновая синхронизация OneNote иногда перехватывала фокус.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-929"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-930">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-931"><span>Исправлена проблема, которая могла влиять на ориентацию вращения трехмерной вертушки.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-931"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="9c87c-932"><span>Исправлена проблема, из-за которой некоторые гиперссылки не работали, если они содержали специальные знаки.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-932"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="9c87c-933"><span>Исправлена проблема, из-за которой одновременно открывалось несколько областей примечаний.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-933"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="9c87c-934">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-934">Project</span></span>

- <div><span data-ttu-id="9c87c-935"><span>Исправлена проблема, которая могла приводить к сбою после печати представления визуального оптимизатора ресурсов.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-935"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="9c87c-936">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-936">Word</span></span>

- <div><span data-ttu-id="9c87c-937"><span>Исправлена проблема, из-за которой многобайтовые знаки в вертикальной надписи отображаются с наложением в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-937">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="9c87c-938"><span>Исправлена&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">проблема, из-за которой ресурсы надстроек, связанные с открытками на японском языке, не удается найти, когда пользователь выполняет действия в мастере надстроек.</span></span></span><span class="sxs-lookup"><span data-stu-id="9c87c-938"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="9c87c-939"><span>Исправлена проблема, из-за которой могли возникать неполадки с пользовательским интерфейсом строки заголовка окна в режиме защищенного просмотра.</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-939"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="9c87c-940">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-940">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Исправлена проблема повреждения файлов при применении действия "Изменить фигуру" к выбранному фрагменту, содержащему обычную фигуру и соединительную линию.</span></span></span><span class="sxs-lookup"><span data-stu-id="9c87c-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="9c87c-942"><span>Исправлена проблема, <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">приводившая к неполадкам в работе приложений при подключении к нескольким внешним дисплеям или при отключении от них. </span></span></span><span class="sxs-lookup"><span data-stu-id="9c87c-942"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="august-23-2019br"></a><span data-ttu-id="9c87c-944">**23 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="9c87c-944">**August 23, 2019**</span></span><br/>
<span data-ttu-id="9c87c-945">Версия 1909 (сборка 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="9c87c-945">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="9c87c-946">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-946">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-947">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-947">Excel</span></span>

- <div><span data-ttu-id="9c87c-948"><span>Значительно повышена производительность при удалении столбцов с объединенными ячейками</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-948"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c87c-949">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-949">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-950"><span>Исправлена проблема, которая могла препятствовать отображению некоторых символов Юникода при просмотре в браузере</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-950"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="9c87c-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-951">Outlook</span></span>

- <div><span data-ttu-id="9c87c-952"><span>Исправлена проблема, которая могла препятствовать сохранению файлов в папке WebDAV</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-952"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-953">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-953">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-954"><span>Исправлена проблема, из-за которой при щелчке пользователя по одному примечанию выделялось другое примечание</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-954"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="9c87c-955">**16 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="9c87c-955">**August 16, 2019**</span></span><br/>
<span data-ttu-id="9c87c-956">Версия 1909 (сборка 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-956">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="9c87c-957">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-957">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="9c87c-958">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-958">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="9c87c-959">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="9c87c-959">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="9c87c-960">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-960">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-961">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-961">Excel</span></span>

- <div><span data-ttu-id="9c87c-962"><span>Исправлена проблема, которая приводила к включению функции автосохранения</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-962"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="9c87c-963">Исправлена проблема, которая приводила к неточному измерению высоты ячеек</span><span class="sxs-lookup"><span data-stu-id="9c87c-963">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="9c87c-964">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-964">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-965"><span>Исправлена проблема, благодаря чему значительно улучшилась производительность функции примечаний</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-965"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="9c87c-966"><span>Исправлена проблема, которая могла приводить к сбою при использовании клавиш со стрелками во время поиска</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-966"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="9c87c-967"><span>Исправлена проблема, из-за которой @упоминание было недоступным, если символ @ стоял после определенных символов</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-967"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="9c87c-968"><span>Исправлена проблема, которая могла приводить к сбою при удалении @упоминаний</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-968"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="9c87c-969"><span>Исправлена проблема, из-за которой эмодзи могли неправильно отображаться в карточках примечаний</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-969"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="9c87c-970"><span>Исправлена проблема с активным буфером обмена, которая могла приводить к сбою</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-970"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="9c87c-971"><span>Исправлена проблема, которая могла приводить к прекращению работы кнопок на панели быстрого доступа</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-971"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="9c87c-972"><span>Исправлена проблема, из-за которой предварительный просмотр форматирования документа мог не переключаться на задний план</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-972"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="9c87c-973">OneNote</span><span class="sxs-lookup"><span data-stu-id="9c87c-973">OneNote</span></span>

- <span data-ttu-id="9c87c-974">Исправлена проблема, из-за которой имена разделов не отображаются в раскрывающемся списке разделов, если для темы Office задано значение "черная".</span><span class="sxs-lookup"><span data-stu-id="9c87c-974">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-975">Outlook</span></span>

- <div><span data-ttu-id="9c87c-976"><span>Исправлена проблема с отправкой событий, из-за которой приложение Outlook могло периодически терять фокус</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-976"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="9c87c-977"><span>Исправлена проблема, из-за которой не работало сочетание клавиш для помещения ответа в папку</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-977"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-978">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-979"><span>Исправлена проблема с режимом защищенного просмотра, из-за которой иногда возникали проблемы при совместной работе</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-979"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="9c87c-980"><span>Исправлена проблема, которая приводила к неправильному отображению задач в области примечаний</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-980"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="9c87c-981"><span>Исправлена проблема, которая могла приводить к сбою при вставке новых слайдов</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-981"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="9c87c-982">Жизненный цикл пользователя</span><span class="sxs-lookup"><span data-stu-id="9c87c-982">User Lifecycle</span></span>

- <div><span data-ttu-id="9c87c-983"><span>Исправлена проблема, из-за которой могла быть недоступна возможность подписки</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-983"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="9c87c-984">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-984">Word</span></span>

- <div><span data-ttu-id="9c87c-985"><span>Исправлена проблема, из-за которой гиперссылки не работали, если содержали определенные символы</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-985"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="9c87c-986"><span>Исправлена проблема, из-за которой размеры изображения могли изменяться при просмотре примечаний к нему</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-986"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="9c87c-987"><span>Исправлена проблема с раскрывающимся меню маркированного списка, которая могло приводить к сбою</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-987"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="9c87c-988">**9 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="9c87c-988">**August 09, 2019**</span></span><br/>
<span data-ttu-id="9c87c-989">Версия 1909 (сборка 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-989">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="9c87c-990">Обновления функций Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-990">Excel Feature updates:</span></span>

- <span data-ttu-id="9c87c-991">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-991">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="9c87c-992">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="9c87c-992">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c87c-993">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="9c87c-993">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="9c87c-994">Набор Office. Обновления функций</span><span class="sxs-lookup"><span data-stu-id="9c87c-994">Office Suite Feature updates:</span></span>

- <span data-ttu-id="9c87c-995">**Новые значки приложений Office.** Обновленные значки приложений отражают простоту, функциональность и интеллектуальные возможности Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-995">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="9c87c-996">Обновления функций Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-996">Outlook Feature updates:</span></span>

- <span data-ttu-id="9c87c-997">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="9c87c-997">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="9c87c-998">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="9c87c-998">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c87c-999">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="9c87c-999">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="9c87c-1000">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1000">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="9c87c-1001">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1001">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c87c-1002">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1002">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="9c87c-1003">Обновления функций Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1003">Word Feature updates:</span></span>

- <span data-ttu-id="9c87c-1004">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1004">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="9c87c-1005">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1005">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="9c87c-1006">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1006">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="9c87c-1007">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-1007">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1008">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1008">Outlook</span></span>

- <div><span data-ttu-id="9c87c-1009"><span>Исправлена проблема, из-за которой получатели приглашения на собрание получали два уведомления после отмены собрания</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1009"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="9c87c-1010">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1010">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-1011"><span>Исправлена проблема, которая приводила к сбою, когда пользователь выбирал пункт "Без контура" или "Без заливки" в меню "Фигуры и значки"</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1011"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="9c87c-1012">**2 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="9c87c-1012">**August 02, 2019**</span></span><br/>
<span data-ttu-id="9c87c-1013">Версия 1908 (сборка 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1013">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="9c87c-1014">Обновления функций Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1014">Excel Feature updates:</span></span>

- <span data-ttu-id="9c87c-1015">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1015">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="9c87c-1016">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1016">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="9c87c-1017">Обновления функций Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1017">Outlook Feature updates:</span></span>

- <span data-ttu-id="9c87c-1018">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1018">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="9c87c-1019">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1019">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="9c87c-1020">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1020">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="9c87c-1021">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1021">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="9c87c-1022">Обновления функций Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1022">Word Feature updates:</span></span>

- <span data-ttu-id="9c87c-1023">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1023">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="9c87c-1024">**Выразите мысль другими словами.** Если вы хотите выразить мысль по-другому, можно воспользоваться функцией переписывания.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1024">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="9c87c-1025">Она предлагает другие варианты, подходящие для ваших фраз.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1025">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="9c87c-1026">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1026">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="9c87c-1027">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-1027">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1028">Доступ</span><span class="sxs-lookup"><span data-stu-id="9c87c-1028">Access</span></span>
- <span data-ttu-id="9c87c-1029">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1029">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1030">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1030">Excel</span></span>

- <div><span data-ttu-id="9c87c-1031"><span>Устранена проблема, из-за которой при печати PDF-файлов применялась команда &quot;Повторять все подписи&quot;</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1031"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="9c87c-1032">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-1032">Office Suite</span></span>

- <div><span data-ttu-id="9c87c-1033"><span>Устранена проблема, из-за которой документ иногда не открывался с рабочего стола</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1033"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="9c87c-1034"><span>Устранена проблема с обновлением при получении неправильного сообщения об ошибке &quot;Выполняется другая установка&quot;</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1034"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="9c87c-1035"><span>Устранена проблема, из-за которой появлялись сообщения об ошибке при установке обновлений для системы безопасности</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1035"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="9c87c-1036"><span>Устранена проблема, из-за которой иногда исчезал курсор</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1036"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="9c87c-1037"><span>Устранена проблема, из-за которой по умолчанию открывалась вкладка "Рисование" вместо вкладки "Главная"</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1037"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="9c87c-1038"><span>Устранена проблема, из-за которой представление в виде большого дерева могло привести к сбою</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1038"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="9c87c-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1039">Outlook</span></span>

- <div></div><span data-ttu-id="9c87c-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Устранена проблема, при которой многократно отображался запрос пароля</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="9c87c-1041"><span>Устранена проблема, из-за которой создавался неправильный запрос адреса электронной почты</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1041"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="9c87c-1042"><span>Устранена проблема, из-за которой не открывались элементы календаря, созданные в устаревших версиях Outlook</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1042"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1043">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1043">PowerPoint</span></span>

- <div><span data-ttu-id="9c87c-1044"><span>Устранена проблема, из-за которой не запускались некоторые анимации</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1044"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="9c87c-1045">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1045">Project</span></span>
- <span data-ttu-id="9c87c-1046">Устранение проблем с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="9c87c-1046">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1047">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1047">Word</span></span>

- <div><span data-ttu-id="9c87c-1048"><span>Устранена проблема, из-за которой ответы на комментарии отображались не по порядку</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1048"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="9c87c-1049"><span>Устранена проблема, из-за которой в некоторых ситуациях вместо комментариев отображались подсказки</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1049"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="9c87c-1050"><span>Устранена проблема, из-за которой при попытке добавить комментарий отображалась область исправлений</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1050"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="9c87c-1051"><span>Устранена проблема, из-за которой не отображался раскрывающийся список отмены</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1051"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="9c87c-1052"><span>Устранена проблема, из-за которой не удавалось добавить комментарии</span></span><span class="sxs-lookup"><span data-stu-id="9c87c-1052"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="9c87c-1053">26 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1053">July 26, 2019</span></span>
<span data-ttu-id="9c87c-1054">Версия 1908 (сборка 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1054">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1055">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1055">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="9c87c-1056">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1056">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="9c87c-1057">Создание более удобных для чтения PDF-документов</span><span class="sxs-lookup"><span data-stu-id="9c87c-1057">Create more accessible PDFs</span></span>

<span data-ttu-id="9c87c-1058">Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1058">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1059">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1060">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1060">All</span></span>

- <span data-ttu-id="9c87c-1061">Исправлена проблема, из-за которой при обновлении Office иногда могли возникать ошибки с сопоставлением типов файлов и значками для Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-1061">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1062">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1062">Word</span></span> 
- <span data-ttu-id="9c87c-1063">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1063">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1064">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1064">Excel</span></span>
- <span data-ttu-id="9c87c-1065">Исправлена проблема, из-за которой перемещение диаграммы иногда могло приводить к сбою</span><span class="sxs-lookup"><span data-stu-id="9c87c-1065">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="9c87c-1066">Исправлена проблема, из-за которой получение объекта Workbook из объекта Chart после изменения типов диаграмм иногда могло приводить к ошибке</span><span class="sxs-lookup"><span data-stu-id="9c87c-1066">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1067">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1067">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1068">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1068">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1069">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1069">Outlook</span></span>
- <span data-ttu-id="9c87c-1070">Исправлена проблема, из-за которой на упрощенной ленте отключенный элемент управления иногда не затенялся</span><span class="sxs-lookup"><span data-stu-id="9c87c-1070">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1071">Доступ</span><span class="sxs-lookup"><span data-stu-id="9c87c-1071">Access</span></span>
- <span data-ttu-id="9c87c-1072">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1072">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1073">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1073">Project</span></span>
- <span data-ttu-id="9c87c-1074">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1074">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="9c87c-1075">19 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1075">July 19, 2019</span></span>
<span data-ttu-id="9c87c-1076">Версия 1908 (сборка 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1076">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1077">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1077">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1078">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1078">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="9c87c-1079">Изучение значения сокращений при чтении в Word Online</span><span class="sxs-lookup"><span data-stu-id="9c87c-1079">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="9c87c-1080">Когда вам попадется сокращение, мы попробуем расшифровать его с помощью данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1080">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1081">Важные исправления</span><span class="sxs-lookup"><span data-stu-id="9c87c-1081">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1082">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1082">Word</span></span> 
- <span data-ttu-id="9c87c-1083">Исправлена проблема с отсутствием тега BookMarkEnd.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1083">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="9c87c-1084">Исправлена проблема с изменением выбранного шрифта при вводе пользователем специальных символов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1084">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="9c87c-1085">Исправлена проблема, из-за которой в новой карточке с комментариями иногда могли появляться пустые ответы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1085">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="9c87c-1086">Исправлена проблема с потерей форматирования при общем доступе к электронной почте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1086">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1087">Excel</span></span>
- <span data-ttu-id="9c87c-1088">Исправлена проблема, из-за которой массив с большим диапазоном иногда мог вызывать сбой.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1088">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="9c87c-1089">Значительно улучшена производительность при копировании данных из отфильтрованных диапазонов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1089">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="9c87c-1090">Исправлена проблема, из-за которой некоторые файлы с именами, содержавшими специальные символы, не открывались.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1090">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1091">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1092">Исправлена проблема, из-за которой не присваивалось название раздела вновь созданному разделу в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1092">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="9c87c-1093">Исправлена проблема, из-за которой использование пользовательского интерфейса затруднялось при использовании монитора 4:3.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1093">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1094">Outlook</span></span>
- <span data-ttu-id="9c87c-1095">Исправлена проблема, из-за которой доступные помещения могли не отображаться в списке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1095">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="9c87c-1096">Исправлена проблема, из-за которой форматирование HTML для некоторых пользователей POP3 было недоступным.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1096">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1097">Доступ</span><span class="sxs-lookup"><span data-stu-id="9c87c-1097">Access</span></span>
- <span data-ttu-id="9c87c-1098">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1099">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1099">Project</span></span>
- <span data-ttu-id="9c87c-1100">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1100">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="9c87c-1101">12 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1101">July 12, 2019</span></span>
<span data-ttu-id="9c87c-1102">Версия 1907 (сборка 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1102">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1103">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1103">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1104">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1104">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="9c87c-1105">Воспроизведение рукописного ввода в презентациях</span><span class="sxs-lookup"><span data-stu-id="9c87c-1105">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="9c87c-1106">Используйте анимацию воспроизведения для рукописного ввода в PowerPoint для большей наглядности презентаций.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1106">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1107">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1107">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1108">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1108">Word</span></span> 
- <span data-ttu-id="9c87c-1109">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1109">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1110">Excel</span></span>
- <span data-ttu-id="9c87c-1111">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1111">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1112">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1112">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1113">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1113">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1114">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1114">Outlook</span></span>
- <span data-ttu-id="9c87c-1115">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1115">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1116">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1116">Access</span></span>
- <span data-ttu-id="9c87c-1117">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1118">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1118">Project</span></span>
- <span data-ttu-id="9c87c-1119">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1119">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="9c87c-1120">5 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1120">July 5, 2019</span></span>
<span data-ttu-id="9c87c-1121">Версия 1907 (сборка 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1121">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1122">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1122">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="9c87c-1123">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1123">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="9c87c-1124">Фигуры в виде эскиза!</span><span class="sxs-lookup"><span data-stu-id="9c87c-1124">Sketchy Shapes!</span></span>

<span data-ttu-id="9c87c-1125">Находитесь в процессе создания презентации?</span><span class="sxs-lookup"><span data-stu-id="9c87c-1125">In the middle of drafting a presentation?</span></span> <span data-ttu-id="9c87c-1126">Примените эскизный стиль, чтобы продемонстрировать незавершенность работы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1126">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="9c87c-1127">Это придает индивидуальность вашим объектам, не превращая их в фигуры произвольной формы, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1127">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1128">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1128">Excel</span></span>

- <span data-ttu-id="9c87c-1129">**Быстрое предоставление общего доступа к файлам**. Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1129">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="9c87c-1130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1130">PowerPoint</span></span>

- <span data-ttu-id="9c87c-1131">**Параметр "Печать номеров слайдов на раздаточных материалах" перемещен в меню печати для облегчения доступа.** Он находится в раскрывающемся меню "Печать > Макет печати", когда выбран макет раздаточных материалов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1131">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="9c87c-1132">Это также позволяет легко включать и отключать этот параметр для отдельных презентаций.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1132">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="9c87c-1133">Подробнее</span><span class="sxs-lookup"><span data-stu-id="9c87c-1133">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="9c87c-1134">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1134">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1135">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1135">Word</span></span>

- <span data-ttu-id="9c87c-1136">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1136">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1137">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1137">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1138">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1138">All</span></span>
- <span data-ttu-id="9c87c-1139">Значительно улучшена производительность подсказок ленты</span><span class="sxs-lookup"><span data-stu-id="9c87c-1139">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="9c87c-1140">Исправлена проблема, мешавшая правильному отображению диалогового окна "Посмотрите, что нового появится в ближайшее время"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1140">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="9c87c-1141">Исправлена проблема, которая могла приводить к неправильному выравниванию фотографий во всплывающей коллекции совместной работы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1141">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1142">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1142">Word</span></span> 
- <span data-ttu-id="9c87c-1143">Исправлена проблема, которая иногда могла препятствовать добавлению новых примечаний</span><span class="sxs-lookup"><span data-stu-id="9c87c-1143">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="9c87c-1144">Исправлена проблема, из-за которой таблицы иногда могли вызывать сбой</span><span class="sxs-lookup"><span data-stu-id="9c87c-1144">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="9c87c-1145">Исправлена проблема, из-за которой иногда могли добавляться недопустимые данные в конец слияния почты</span><span class="sxs-lookup"><span data-stu-id="9c87c-1145">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="9c87c-1146">Исправлена проблема, которая могла приводить к неправильному отображению некоторых уравнений LaTeX</span><span class="sxs-lookup"><span data-stu-id="9c87c-1146">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1147">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1147">Excel</span></span>
- <span data-ttu-id="9c87c-1148">Исправлена проблема, из-за которой изменение типов диаграмм могло иногда приводить к возникновению исключения во время выполнения</span><span class="sxs-lookup"><span data-stu-id="9c87c-1148">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="9c87c-1149">Исправлена проблема с отображением неправильной ленты при открытии нескольких окон</span><span class="sxs-lookup"><span data-stu-id="9c87c-1149">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="9c87c-1150">Исправлена проблема, которая могла вызывать ошибку при открытии макросом второго экземпляра книги</span><span class="sxs-lookup"><span data-stu-id="9c87c-1150">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="9c87c-1151">Исправлена проблема, которая могла приводить к сбою при открытии книги, создании книги или переключении между книгами</span><span class="sxs-lookup"><span data-stu-id="9c87c-1151">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="9c87c-1152">Исправлена проблема, не позволявшая пользователям открыть PDF-файл, созданный из Word в Teams</span><span class="sxs-lookup"><span data-stu-id="9c87c-1152">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1153">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1154">Исправлена проблема, из-за которой могло ухудшаться качество диаграммы при экспорте в PDF-файл</span><span class="sxs-lookup"><span data-stu-id="9c87c-1154">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="9c87c-1155">Исправлена проблема, препятствовавшая отображению подсказки с указанием расстояния до центра</span><span class="sxs-lookup"><span data-stu-id="9c87c-1155">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1156">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1156">Outlook</span></span>
- <span data-ttu-id="9c87c-1157">Исправлена проблема, которая иногда могла мешать отображению ошибки с сообщением о переполнении диска</span><span class="sxs-lookup"><span data-stu-id="9c87c-1157">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="9c87c-1158">Исправлена проблема, которая могла приводить к дублированию вложений при обновлении приглашения на собрание</span><span class="sxs-lookup"><span data-stu-id="9c87c-1158">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1159">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1159">Access</span></span>
- <span data-ttu-id="9c87c-1160">Исправлена проблема, препятствовавшая возврату длинных целых значений при некоторых запросах</span><span class="sxs-lookup"><span data-stu-id="9c87c-1160">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="9c87c-1161">Исправлена проблема, из-за которой поле SQL могло стать нередактируемым</span><span class="sxs-lookup"><span data-stu-id="9c87c-1161">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="9c87c-1162">Исправлена проблема, из-за которой подсказки могло быть плохо видно на экранах с высоким разрешением</span><span class="sxs-lookup"><span data-stu-id="9c87c-1162">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1163">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1163">Project</span></span>
- <span data-ttu-id="9c87c-1164">Исправлена проблема, из-за которой значения флагов могли стать нередактируемыми в новых задачах</span><span class="sxs-lookup"><span data-stu-id="9c87c-1164">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="9c87c-1165">Исправлена проблема, которая могла приводить к неправильной установке фактической даты начала в назначениях и задачах при обновлении состояния</span><span class="sxs-lookup"><span data-stu-id="9c87c-1165">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="9c87c-1166">Исправлена проблема, которая могла приводить к неправильному отображению превышения доступности для некоторых ресурсов</span><span class="sxs-lookup"><span data-stu-id="9c87c-1166">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="9c87c-1167">Исправлена проблема, из-за которой метод добавления объектов TaskDependencies мог завершаться сбоем, если добавлен параметр Lag, десятичным разделителем является запятая и выполнено подключение к серверу</span><span class="sxs-lookup"><span data-stu-id="9c87c-1167">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="9c87c-1168">Исправлена проблема, из-за которой обновление значений таблицы подстановки локальных настраиваемых полей через CSOM могло приводить к сбою компьютеров</span><span class="sxs-lookup"><span data-stu-id="9c87c-1168">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="9c87c-1169">Исправлена проблема, из-за которой значения общего объема работ могли отображаться неправильно, если они содержали десятичное число</span><span class="sxs-lookup"><span data-stu-id="9c87c-1169">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="9c87c-1170">28 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1170">June 28, 2019</span></span>
<span data-ttu-id="9c87c-1171">Версия 1907 (сборка 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1171">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1172">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1172">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1173">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1173">Excel</span></span>

- <span data-ttu-id="9c87c-1174">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1174">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="9c87c-1175">Также легко находить функции, столбцы и параметры</span><span class="sxs-lookup"><span data-stu-id="9c87c-1175">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="9c87c-1176">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1176">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1177">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1177">Word</span></span>

- <span data-ttu-id="9c87c-1178">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1178">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="9c87c-1179">Word, Excel, PowerPoint и Visio</span><span class="sxs-lookup"><span data-stu-id="9c87c-1179">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="9c87c-1180">Рекомендуемые документы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1180">Recommended Documents</span></span>

<span data-ttu-id="9c87c-1181">Находите рекомендуемые вам документы с важными действиями.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1181">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1182">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1182">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1183">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1183">Word</span></span> 
- <span data-ttu-id="9c87c-1184">Исправлена проблема, из-за которой не удавалось открыть некоторые DOC-файлы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1184">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="9c87c-1185">Исправлена проблема, которая могла мешать правильной загрузке примечаний</span><span class="sxs-lookup"><span data-stu-id="9c87c-1185">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1186">Excel</span></span>
- <span data-ttu-id="9c87c-1187">Улучшена производительность запросов Power Query</span><span class="sxs-lookup"><span data-stu-id="9c87c-1187">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1188">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1189">Исправлена проблема, связанная с использованием пера на устройстве Surface, которая могла приводить к мерцанию экрана</span><span class="sxs-lookup"><span data-stu-id="9c87c-1189">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1190">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1190">Outlook</span></span>
- <span data-ttu-id="9c87c-1191">Исправлена проблема, из-за которой могло изменяться состояние доступности встречи при преобразовании в собрание</span><span class="sxs-lookup"><span data-stu-id="9c87c-1191">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="9c87c-1192">Исправлена проблема с отображением неправильного шаблона и описания, если сообщение защищено с помощью специального шаблона</span><span class="sxs-lookup"><span data-stu-id="9c87c-1192">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1193">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1193">Access</span></span>
- <span data-ttu-id="9c87c-1194">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1194">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1195">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1195">Project</span></span>
- <span data-ttu-id="9c87c-1196">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1196">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="9c87c-1197">21 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1197">June 21, 2019</span></span>
<span data-ttu-id="9c87c-1198">Версия 1907 (сборка 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1198">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1199">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1199">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1200">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1200">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="9c87c-1201">Темный режим для черной темы в классическом приложении Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1201">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="9c87c-1202">Когда используется темный режим, для пользователей, выбравших черную тему, области чтения и создания сообщений теперь также отображаются на темном фоне при чтении и создании сообщений электронной почты соответственно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1202">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="9c87c-1203">В области чтения и на ленте есть переключатель с изображением солнца или луны, позволяющий пользователям предварительно просмотреть сообщение на светлом фоне.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1203">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1204">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1204">Getting Started:</span></span>

1. <span data-ttu-id="9c87c-1205">Включите черную тему, и темный режим запустится по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1205">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="9c87c-1206">Используйте переключатель с изображением луны или солнца (в области чтения и на ленте), чтобы просмотреть оформление сообщения для пользователей, не применяющих темный режим</span><span class="sxs-lookup"><span data-stu-id="9c87c-1206">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1207">Возможные действия</span><span class="sxs-lookup"><span data-stu-id="9c87c-1207">Scenarios to Try</span></span>

1. <span data-ttu-id="9c87c-1208">Читайте сообщения в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1208">Read emails in dark mode.</span></span> <span data-ttu-id="9c87c-1209">Если вам не удается что-то прочитать, используйте переключатель с изображением солнца в области чтения, чтобы переключиться на светлый фон.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1209">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="9c87c-1210">Создавайте сообщения в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1210">Compose emails in dark mode.</span></span> <span data-ttu-id="9c87c-1211">Просматривайте сообщение на светлом фоне с помощью переключателя с изображением солнца на ленте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1211">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="9c87c-1212">Если вы столкнулись с неправильным отображением сообщений, отправьте их (в виде вложения) на адрес электронной почты OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="9c87c-1212">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="9c87c-1213">Получение предложений по расположению</span><span class="sxs-lookup"><span data-stu-id="9c87c-1213">Get location suggestions</span></span>

<span data-ttu-id="9c87c-1214">Начните ввод текста и Outlook подберет подходящие расположения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1214">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="9c87c-1215">Это применяется к полю "Расположение" при создании встреч и собраний.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1215">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1216">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1216">Getting Started:</span></span>

- <span data-ttu-id="9c87c-1217">Создайте встречу или собрание в календаре Outlook в Office 365 или Outlook.com.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1217">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="9c87c-1218">Щелкните поле "Расположение" и начните вводить текст...</span><span class="sxs-lookup"><span data-stu-id="9c87c-1218">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1219">Возможные действия</span><span class="sxs-lookup"><span data-stu-id="9c87c-1219">Scenarios to Try</span></span>

<span data-ttu-id="9c87c-1220">При добавлении конференц-зала к собранию щелкните поле "Расположение", а не надстройку "Поиск помещений" или адресную книгу.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1220">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="9c87c-1221">Для встреч в общественных местах, например в ресторане, кафе или даже кабинете стоматолога, постарайтесь найти точное расположение с помощью нового средства выбора.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1221">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="9c87c-1222">Так вы сможете получать уведомления в Outlook Mobile, когда придет время отправляться в путь.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1222">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1223">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1223">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1224">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1224">All</span></span>
- <span data-ttu-id="9c87c-1225">Исправлена проблема, из-за которой поле поиска могло оставаться активным в автономном режиме</span><span class="sxs-lookup"><span data-stu-id="9c87c-1225">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1226">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1226">Word</span></span> 
- <span data-ttu-id="9c87c-1227">Исправлена проблема, из-за которой иногда трудно было увидеть фокус клавиатуры</span><span class="sxs-lookup"><span data-stu-id="9c87c-1227">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="9c87c-1228">Исправлена проблема, из-за которой текст, вставлявшийся в новый документ, иногда мог выравниваться неправильно</span><span class="sxs-lookup"><span data-stu-id="9c87c-1228">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="9c87c-1229">Исправлена проблема, из-за которой некоторым пользователям не удавалось сохранять изменения после приостановки работы компьютера</span><span class="sxs-lookup"><span data-stu-id="9c87c-1229">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="9c87c-1230">Исправлена проблема, из-за которой в некоторых случаях печатался весь документ вместо выбранного диапазона</span><span class="sxs-lookup"><span data-stu-id="9c87c-1230">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="9c87c-1231">Исправлена проблема, которая могла затруднять чтение примечаний на небольших экранах</span><span class="sxs-lookup"><span data-stu-id="9c87c-1231">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="9c87c-1232">Исправлена проблема, которая могла приводить к сбою при записи на устройство</span><span class="sxs-lookup"><span data-stu-id="9c87c-1232">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1233">Excel</span></span>
- <span data-ttu-id="9c87c-1234">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1234">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1235">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1236">Исправлена проблема, из-за которой иногда трудно было увидеть фокус клавиатуры</span><span class="sxs-lookup"><span data-stu-id="9c87c-1236">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1237">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1237">Outlook</span></span>
- <span data-ttu-id="9c87c-1238">Исправлена проблема, из-за которой надстройка могла неправильно отображаться как включенная, хотя она выключена.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1238">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="9c87c-1239">Исправлена проблема, не позволявшая пользователю просматривать все политики хранения, если их много</span><span class="sxs-lookup"><span data-stu-id="9c87c-1239">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1240">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1240">Access</span></span>
- <span data-ttu-id="9c87c-1241">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1241">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1242">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1242">Project</span></span>
- <span data-ttu-id="9c87c-1243">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1243">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="9c87c-1244">14 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1244">June 14, 2019</span></span>
<span data-ttu-id="9c87c-1245">Версия 1907 (сборка 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1245">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1246">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1246">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1247">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1247">Word</span></span> 
- <span data-ttu-id="9c87c-1248">Исправлена проблема, которая могла препятствовать входу пользователя при сохранении в OneDrive</span><span class="sxs-lookup"><span data-stu-id="9c87c-1248">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="9c87c-1249">Исправлена проблема, из-за которой пользователю могло быть запрещено изменять свойства SharePoint в режиме ограниченного доступа</span><span class="sxs-lookup"><span data-stu-id="9c87c-1249">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="9c87c-1250">Исправлена проблема, из-за которой содержимое колонтитулов могло меняться при изменении полей</span><span class="sxs-lookup"><span data-stu-id="9c87c-1250">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="9c87c-1251">Исправлена проблема, из-за которой форматирование могло разрываться при переходе в веб-представление</span><span class="sxs-lookup"><span data-stu-id="9c87c-1251">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="9c87c-1252">Исправлена проблема, которая могла помешать пользователю использовать настраиваемые поля при открытии из SharePoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1252">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1253">Excel</span></span>
- <span data-ttu-id="9c87c-1254">Исправлена проблема с производительностью при удалении строк отфильтрованного набора</span><span class="sxs-lookup"><span data-stu-id="9c87c-1254">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="9c87c-1255">Исправлена проблема, которая могла иногда вызывать мерцание указателя мыши в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="9c87c-1255">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="9c87c-1256">Устранена проблема, которая могла приводить к сбою при удалении ряда</span><span class="sxs-lookup"><span data-stu-id="9c87c-1256">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="9c87c-1257">Исправлена проблема, из-за которой некоторым пользователям предоставлялась возможность добавить журнал версий, когда он недоступен</span><span class="sxs-lookup"><span data-stu-id="9c87c-1257">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="9c87c-1258">Исправлена проблема, которая могла приводить к возникновению исключения при использовании средства сравнения электронных таблиц</span><span class="sxs-lookup"><span data-stu-id="9c87c-1258">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1259">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1260">Устранена проблема, из-за которой мог происходить сбой при переходе по ссылке к SharePoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1260">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="9c87c-1261">Исправлена проблема, из-за которой пользователь мог переключаться на следующую страницу при вводе с помощью ручки Surface</span><span class="sxs-lookup"><span data-stu-id="9c87c-1261">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1262">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1262">Outlook</span></span>
- <span data-ttu-id="9c87c-1263">Исправлена проблема, из-за которой в некоторых случаях поле "Кому" отображалось увеличенным</span><span class="sxs-lookup"><span data-stu-id="9c87c-1263">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1264">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1264">Access</span></span>
- <span data-ttu-id="9c87c-1265">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1265">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1266">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1266">Project</span></span>
- <span data-ttu-id="9c87c-1267">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1267">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="9c87c-1268">7 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1268">June 7, 2019</span></span>
<span data-ttu-id="9c87c-1269">Версия 1907 (сборка 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1269">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1270">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1271">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1271">Word</span></span> 
- <span data-ttu-id="9c87c-1272">Исправлена проблема, из-за которой возникал сбой в работе Word при автозамене первой буквы предложения на прописную</span><span class="sxs-lookup"><span data-stu-id="9c87c-1272">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="9c87c-1273">Улучшена производительность при редактировании документа в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1273">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="9c87c-1274">Исправлена проблема, из-за которой неправильно отображались векторные изображения, созданные в Adobe Illustrator</span><span class="sxs-lookup"><span data-stu-id="9c87c-1274">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1275">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1275">Excel</span></span>
- <span data-ttu-id="9c87c-1276">Исправлена проблема, из-за которой поля сортировки могли быть неправильно установлены при записи макроса</span><span class="sxs-lookup"><span data-stu-id="9c87c-1276">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="9c87c-1277">Исправлена проблема, приводящая к зависанию или сбою при пересчете формулы массива</span><span class="sxs-lookup"><span data-stu-id="9c87c-1277">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1278">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1278">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1279">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1279">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1280">Outlook</span></span>
- <span data-ttu-id="9c87c-1281">Исправлена проблема, из-за которой встроенные вложения иногда имели неправильный масштаб</span><span class="sxs-lookup"><span data-stu-id="9c87c-1281">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1282">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1282">Access</span></span>
- <span data-ttu-id="9c87c-1283">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1283">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1284">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1284">Project</span></span>
- <span data-ttu-id="9c87c-1285">Исправлена проблема, из-за которой в расписании заданий с фиксированной длительностью может изменяться дата окончания</span><span class="sxs-lookup"><span data-stu-id="9c87c-1285">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="9c87c-1286">Исправлена проблема, из-за которой могло неправильно отображаться значение процента выполнения при открытии проекта из более ранней версии</span><span class="sxs-lookup"><span data-stu-id="9c87c-1286">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="9c87c-1287">31 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1287">May 31, 2019</span></span>
<span data-ttu-id="9c87c-1288">Версия 1906 (сборка 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1288">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1289">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1289">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1290">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1290">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="9c87c-1291">Диалоговое окно обращения в службу поддержки теперь закрепляется и отображается справа</span><span class="sxs-lookup"><span data-stu-id="9c87c-1291">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="9c87c-1292">Диалоговое окно, используемое для обращения в службу поддержки, отображается в области справа и выводится как закрепленное окно.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1292">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="9c87c-1293">Рукописный ввод в вашем электронном письме!</span><span class="sxs-lookup"><span data-stu-id="9c87c-1293">Ink in Your Email!</span></span>

<span data-ttu-id="9c87c-1294">В сообщениях электронной почты Outlook теперь можно рисовать и создавать примечания к изображениям.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1294">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1295">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1295">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="9c87c-1296">Открытие ссылок на документы в Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1296">Open document links in Word</span></span>

<span data-ttu-id="9c87c-1297">При переходе по ссылке на документ в Office вы можете изменить параметр, чтобы открывать его в приложении Word по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1297">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="9c87c-1298">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1298">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9c87c-1299">Подробнее: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9c87c-1299">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1300">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1300">Getting Started:</span></span>

<span data-ttu-id="9c87c-1301">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1301">Feature will default to off.</span></span> <span data-ttu-id="9c87c-1302">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1302">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9c87c-1303">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1303">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9c87c-1304">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1304">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9c87c-1305">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1305">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9c87c-1306">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1306">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1307">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1307">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1308">Чтобы запустить интерфейс согласия на открытие ссылки на документ Word, хранящийся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1308">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9c87c-1309">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1309">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1310">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="9c87c-1311">Открытие ссылок на презентации в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1311">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="9c87c-1312">При переходе по ссылке на презентацию в Office вы можете изменить параметр, чтобы открывать ее в приложении PowerPoint по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1312">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="9c87c-1313">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1313">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9c87c-1314">Подробнее: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9c87c-1314">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1315">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1315">Getting Started:</span></span>

<span data-ttu-id="9c87c-1316">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1316">Feature will default to off.</span></span> <span data-ttu-id="9c87c-1317">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1317">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9c87c-1318">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1318">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9c87c-1319">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1319">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9c87c-1320">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1320">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9c87c-1321">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1321">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1322">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1322">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1323">Чтобы запустить интерфейс согласия на открытие ссылки на презентацию PowerPoint, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1323">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9c87c-1324">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1324">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1325">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="9c87c-1326">Открытие ссылок на книги в Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1326">Open workbook links in Excel</span></span>

<span data-ttu-id="9c87c-1327">При переходе по ссылке на книгу в Office вы можете изменить параметр, чтобы открывать ее в приложении Excel по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1327">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="9c87c-1328">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1328">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9c87c-1329">Подробнее: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9c87c-1329">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1330">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1330">Getting Started:</span></span>

<span data-ttu-id="9c87c-1331">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1331">Feature will default to off.</span></span> <span data-ttu-id="9c87c-1332">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1332">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9c87c-1333">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1333">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9c87c-1334">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1334">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9c87c-1335">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1335">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9c87c-1336">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1336">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1337">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1337">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1338">Чтобы запустить интерфейс согласия на открытие ссылки на книгу Excel, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1338">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9c87c-1339">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1339">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1340">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1340">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1341">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1341">All</span></span>
- <span data-ttu-id="9c87c-1342">Исправлена проблема, из-за которой файлы иногда автоматически сохранялись даже при отключенной функции автоматического сохранения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1342">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1343">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1343">Word</span></span> 
- <span data-ttu-id="9c87c-1344">Исправлена ошибка, которая могла не позволять некоторым пользователям сохранять файлы в SharePoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1344">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1345">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1345">Excel</span></span>
- <span data-ttu-id="9c87c-1346">Исправлена проблема с возможным отображением неправильного значка для неактивных фильтров</span><span class="sxs-lookup"><span data-stu-id="9c87c-1346">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1347">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1348">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1348">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1349">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1349">Outlook</span></span>
- <span data-ttu-id="9c87c-1350">Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1350">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="9c87c-1351">Исправлена проблема, не позволявшая функции безопасных ссылок анализировать URL-адрес с конечным пробелом</span><span class="sxs-lookup"><span data-stu-id="9c87c-1351">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="9c87c-1352">Устранена проблема, из-за которой помещения отображались доступными за пределами нерабочего времени</span><span class="sxs-lookup"><span data-stu-id="9c87c-1352">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1353">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1353">Access</span></span>
- <span data-ttu-id="9c87c-1354">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1354">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1355">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1355">Project</span></span>
- <span data-ttu-id="9c87c-1356">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1356">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="9c87c-1357">24 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1357">May 24, 2019</span></span>
<span data-ttu-id="9c87c-1358">Версия 1906 (сборка 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1358">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1359">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1359">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="9c87c-1360">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="9c87c-1360">User Experience Updates</span></span>

<span data-ttu-id="9c87c-1361">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1361">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1362">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1362">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1363">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1363">All</span></span>

- <span data-ttu-id="9c87c-1364">Исправлена проблема, из-за которой не отображалась область чата</span><span class="sxs-lookup"><span data-stu-id="9c87c-1364">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1365">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1365">Word</span></span> 
- <span data-ttu-id="9c87c-1366">Исправлена проблема, из-за которой в некоторых случаях приложение Word могло неправильно выделять текст на наличие грамматических ошибок</span><span class="sxs-lookup"><span data-stu-id="9c87c-1366">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1367">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1367">Excel</span></span>
- <span data-ttu-id="9c87c-1368">Исправлена проблема, из-за которой применялся неправильный значок для элементов диаграммы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1368">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="9c87c-1369">Исправлена проблема, приводившая к активации неверной книги в скрипте VBA, если эта книга уже открыта</span><span class="sxs-lookup"><span data-stu-id="9c87c-1369">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1370">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1371">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1371">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1372">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1372">Outlook</span></span>
- <span data-ttu-id="9c87c-1373">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1373">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1374">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1374">Access</span></span>
- <span data-ttu-id="9c87c-1375">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1375">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1376">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1376">Project</span></span>
- <span data-ttu-id="9c87c-1377">Устранена ошибка, при которой приложение Project аварийно завершало работу после перехода на панель задач</span><span class="sxs-lookup"><span data-stu-id="9c87c-1377">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="9c87c-1378">17 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1378">May 17, 2019</span></span>
<span data-ttu-id="9c87c-1379">Версия 1906 (сборка 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1379">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1380">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1380">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1381">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="9c87c-1382">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="9c87c-1382">User Experience Updates</span></span>

<span data-ttu-id="9c87c-1383">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1383">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1384">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1384">Getting Started:</span></span>

<span data-ttu-id="9c87c-1385">Эти изменения относятся к новому стандартному пользовательскому интерфейсу; он был доступен с помощью переключателя "Ожидается в ближайшее время" с середины декабря для 100 % рабочих сред</span><span class="sxs-lookup"><span data-stu-id="9c87c-1385">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="9c87c-1386">Настраиваемая упрощенная лента</span><span class="sxs-lookup"><span data-stu-id="9c87c-1386">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="9c87c-1387">Возможность простой настройки для переключения между классическим и упрощенным представлением, а также для закрепления и открепления команд.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1387">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1388">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1388">Getting Started:</span></span>

<span data-ttu-id="9c87c-1389">Пользователи могут перейти к упрощенной ленте, включив переключатель "Ожидается в ближайшее время" (изначально) и щелкнув шеврон на ленте, чтобы переключаться между классической многострочной и новой упрощенной однострочной лентой.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1389">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1390">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1390">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1391">Переключение с классической на упрощенную ленту</span><span class="sxs-lookup"><span data-stu-id="9c87c-1391">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="9c87c-1392">Выбор избранного действия</span><span class="sxs-lookup"><span data-stu-id="9c87c-1392">Pick your favorite action</span></span>

<span data-ttu-id="9c87c-1393">Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="9c87c-1393">Don't use Flag and Delete?</span></span> <span data-ttu-id="9c87c-1394">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="9c87c-1394">How about Archive or Mark as Read?</span></span> <span data-ttu-id="9c87c-1395">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1395">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1396">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1396">Getting Started:</span></span>

<span data-ttu-id="9c87c-1397">Чтобы выбрать быстрые действия, щелкните правой кнопкой мыши сообщение в списке для отображения контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1397">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="9c87c-1398">Затем выберите пункт "Задать быстрые действия"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1398">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1399">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1399">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1400">Изменение используемых по умолчанию действий "Пометить" и "Удалить" на "Архивировать", "Переместить", "Пометить как прочитанные" или "Отсутствует" для уменьшения элементов в списке сообщений</span><span class="sxs-lookup"><span data-stu-id="9c87c-1400">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="9c87c-1401">Выбор свободного или компактного макета</span><span class="sxs-lookup"><span data-stu-id="9c87c-1401">Relaxed or tighter layout?</span></span> <span data-ttu-id="9c87c-1402">по своему усмотрению</span><span class="sxs-lookup"><span data-stu-id="9c87c-1402">You choose</span></span>

<span data-ttu-id="9c87c-1403">С помощью компактных интервалов можно выбрать дополнительное пространство между элементами или более сжатый макет, чтобы увидеть больше элементов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1403">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1404">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1404">Getting Started:</span></span>

<span data-ttu-id="9c87c-1405">Вкладка "Вид", флажок "Уменьшить интервал" в группе "Сообщения" для классической ленты и параметры текущего представления для упрощенной ленты</span><span class="sxs-lookup"><span data-stu-id="9c87c-1405">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1406">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1406">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1407">Использование Outlook для просмотра и создания сообщений с включенным и отключенным параметром.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1407">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="9c87c-1408">При включенном параметре "Уменьшить интервал" на странице располагается больше сообщений, а элементы управления в формах создания упрощаются.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1408">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="9c87c-1409">Дедупликация недавно использовавшихся записей при применении клиента синхронизации OneDrive</span><span class="sxs-lookup"><span data-stu-id="9c87c-1409">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="9c87c-1410">Улучшите интеграцию с клиентом синхронизации OneDrive с помощью облачных вложений, выполнив дедупликацмию недавно использовавшихся записей, обеспечивающую ускорение вложения в виде копии для синхронизированных данных</span><span class="sxs-lookup"><span data-stu-id="9c87c-1410">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1411">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1411">Getting Started:</span></span>

<span data-ttu-id="9c87c-1412">При использовании клиента синхронизации OneDrive дубликаты больше не отображаются в меню последних выбиравшихся для вложений файлов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1412">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1413">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1413">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1414">Включение клиента синхронизации OneDrive и использование меню "Вложить файл" в классической версии Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1414">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="9c87c-1415">Улучшенная синхронизация общих папок для почтовых ящиков с большим числом папок</span><span class="sxs-lookup"><span data-stu-id="9c87c-1415">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="9c87c-1416">В течение нескольких лет при синхронизации общих почтовых ящиков в приложении Outlook существовало ограничение не более 500 папок.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1416">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="9c87c-1417">В результате этого изменения при синхронизации в Outlook больше не будет применяться это ограничение в 500 папок.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1417">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1418">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1418">Getting Started:</span></span>

<span data-ttu-id="9c87c-1419">Создайте в почтовом ящике 1000 папок, предоставьте другому пользователю доступ к почтовому ящику, создайте профиль Outlook для "другого пользователя" и убедитесь в выполнении синхронизации.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1419">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1420">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1420">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="9c87c-1421">Стереть лишь небольшую часть</span><span class="sxs-lookup"><span data-stu-id="9c87c-1421">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1422">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1422">Getting Started:</span></span>

<span data-ttu-id="9c87c-1423">Откройте вкладку "Рисование". Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1423">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="9c87c-1424">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1424">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1425">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1425">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1426">Откройте вкладку "Рисование". Выберите перо.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1426">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="9c87c-1427">Нанесите росчерк пером.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1427">Draw an ink stroke.</span></span> <span data-ttu-id="9c87c-1428">Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1428">Select the Eraser dropdown.</span></span> <span data-ttu-id="9c87c-1429">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1429">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="9c87c-1430">Сотрите лишь небольшую часть росчерка пера.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1430">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1431">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1431">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1432">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1432">All</span></span> 
- <span data-ttu-id="9c87c-1433">Исправлена проблема, из-за которой некоторым пользователям могло не удаваться сохранять файлы в формате PDF</span><span class="sxs-lookup"><span data-stu-id="9c87c-1433">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="9c87c-1434">Исправлена проблема, которая могла влиять на сохранение пользователями больших файлов в 32-разрядной системе</span><span class="sxs-lookup"><span data-stu-id="9c87c-1434">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1435">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1435">Word</span></span> 
- <span data-ttu-id="9c87c-1436">Значительно повышена скорость реагирования функции диктовки</span><span class="sxs-lookup"><span data-stu-id="9c87c-1436">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1437">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1437">Excel</span></span>
- <span data-ttu-id="9c87c-1438">Исправлена проблема, из-за которой события двойного щелчка могли не срабатывать на устройствах с сенсорным экраном</span><span class="sxs-lookup"><span data-stu-id="9c87c-1438">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="9c87c-1439">Исправлена проблема, которая могла блокировать для некоторых пользователей редактирование макросов VBA</span><span class="sxs-lookup"><span data-stu-id="9c87c-1439">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="9c87c-1440">Исправлена проблема, которая могла влиять на производительность при использовании срезов</span><span class="sxs-lookup"><span data-stu-id="9c87c-1440">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1441">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1442">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1442">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1443">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1443">Outlook</span></span>
- <span data-ttu-id="9c87c-1444">Исправлена проблема, из-за которой неверный шаблон мог отображаться среди выбранных</span><span class="sxs-lookup"><span data-stu-id="9c87c-1444">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1445">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1445">Access</span></span>
- <span data-ttu-id="9c87c-1446">Исправлена проблема, из-за которой могло быть затруднено чтение текста при использовании построителя масштаба для отображения длинного форматированного текста</span><span class="sxs-lookup"><span data-stu-id="9c87c-1446">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1447">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1447">Project</span></span>
- <span data-ttu-id="9c87c-1448">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1448">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="9c87c-1449">10 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1449">May 10, 2019</span></span>
<span data-ttu-id="9c87c-1450">Версия 1906 (сборка 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1450">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1451">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1451">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1452">Outlook</span></span>

<span data-ttu-id="9c87c-1453">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1453">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1454">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1454">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1455">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1455">All</span></span>
- <span data-ttu-id="9c87c-1456">Исправлена проблема, из-за которой диалоговое окно "Сохранить как" могло отображать неправильный путь</span><span class="sxs-lookup"><span data-stu-id="9c87c-1456">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1457">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1457">Word</span></span> 
- <span data-ttu-id="9c87c-1458">Исправлена проблема, из-за которой не вставлялись некоторые выбранные элементы из области "Что вы хотите сделать?"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1458">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1459">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1459">Excel</span></span>
- <span data-ttu-id="9c87c-1460">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1460">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1461">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1462">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1462">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1463">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1463">Outlook</span></span>
- <span data-ttu-id="9c87c-1464">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1464">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1465">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1465">Access</span></span>
- <span data-ttu-id="9c87c-1466">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1466">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1467">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1467">Project</span></span>
- <span data-ttu-id="9c87c-1468">Исправлена проблема, из-за которой могло требоваться выделение для просмотра идентификатора задачи</span><span class="sxs-lookup"><span data-stu-id="9c87c-1468">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="9c87c-1469">3 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1469">May 3, 2019</span></span>
<span data-ttu-id="9c87c-1470">Версия 1906 (сборка 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1470">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1471">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1471">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1472">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1472">Outlook</span></span>

<span data-ttu-id="9c87c-1473">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1473">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1474">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1474">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9c87c-1475">Все</span><span class="sxs-lookup"><span data-stu-id="9c87c-1475">All</span></span>
- <span data-ttu-id="9c87c-1476">Исправлена ошибка, из-за которой у некоторых пользователей возникали проблемы с синхронизацией OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="9c87c-1476">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1477">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1477">Word</span></span> 
- <span data-ttu-id="9c87c-1478">Исправлена ошибка, из-за которой в некоторых случаях запуск Word занимал много времени</span><span class="sxs-lookup"><span data-stu-id="9c87c-1478">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1479">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1479">Excel</span></span>
- <span data-ttu-id="9c87c-1480">Исправлена проблема, из-за которой внешние ссылки иногда удалялись из книг после обновления до более новой версии Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1480">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="9c87c-1481">Исправлена проблема, из-за которой у некоторых пользователей могли возникать сложности с выделением ячеек в новой книге</span><span class="sxs-lookup"><span data-stu-id="9c87c-1481">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1482">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1482">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1483">Исправлена проблема, из-за которой при преобразовании рисунков в текст неправильно согласовывались размеры шрифтов</span><span class="sxs-lookup"><span data-stu-id="9c87c-1483">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1484">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1484">Outlook</span></span>
- <span data-ttu-id="9c87c-1485">Исправлена проблема, из-за которой сохранение контакта из VCF-файла могло привести к получению пустых полей</span><span class="sxs-lookup"><span data-stu-id="9c87c-1485">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="9c87c-1486">Исправлена проблема, из-за которой сообщение могло оставаться в папке "Исходящие", хотя оно было отправлено</span><span class="sxs-lookup"><span data-stu-id="9c87c-1486">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="9c87c-1487">Исправлена проблема с аварийным завершением работы Outlook при просмотре сообщения DRM</span><span class="sxs-lookup"><span data-stu-id="9c87c-1487">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1488">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1488">Access</span></span>
- <span data-ttu-id="9c87c-1489">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1489">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1490">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1490">Project</span></span>
- <span data-ttu-id="9c87c-1491">Устранена ошибка, при которой редактор менялся с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="9c87c-1491">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="9c87c-1492">Устранена проблема, из-за которой неопубликованные задачи могли отображаться в опубликованной копии главного проекта</span><span class="sxs-lookup"><span data-stu-id="9c87c-1492">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="9c87c-1493">26 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1493">April 26, 2019</span></span>
<span data-ttu-id="9c87c-1494">Версия 1905 (сборка 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1494">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="9c87c-1495">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1495">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1496">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1496">Outlook</span></span>

<span data-ttu-id="9c87c-1497">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1497">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="9c87c-1498">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1498">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1499">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1499">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="9c87c-1500">Улучшенные возможности совместного редактирования</span><span class="sxs-lookup"><span data-stu-id="9c87c-1500">Coauthoring improvements</span></span>

<span data-ttu-id="9c87c-1501">Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1501">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="9c87c-1502">Visio</span><span class="sxs-lookup"><span data-stu-id="9c87c-1502">Visio</span></span>

- <span data-ttu-id="9c87c-1503">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1503">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1504">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1505">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1505">Word</span></span> 
- <span data-ttu-id="9c87c-1506">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1506">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1507">Excel</span></span>
- <span data-ttu-id="9c87c-1508">Устранена проблема, которая приводила к невозможности запуска макросов надстройки "Поиск решения"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1508">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="9c87c-1509">Устранена проблема, которая могла препятствовать импорту файлов Excel в SharePoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1509">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1510">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1510">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1511">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1511">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1512">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1512">Outlook</span></span>
- <span data-ttu-id="9c87c-1513">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1513">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1514">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1514">Access</span></span>
- <span data-ttu-id="9c87c-1515">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1515">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1516">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1516">Project</span></span>
- <span data-ttu-id="9c87c-1517">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1517">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="9c87c-1518">19 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1518">April 19, 2019</span></span>
<span data-ttu-id="9c87c-1519">Версия 1905 (сборка 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1519">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1520">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1520">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1521">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1521">Outlook</span></span>

<span data-ttu-id="9c87c-1522">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1522">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1523">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1523">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="9c87c-1524">Улучшенный интерфейс картограмм с использованием типов данных</span><span class="sxs-lookup"><span data-stu-id="9c87c-1524">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="9c87c-1525">Эта возможность является улучшением для пользователей, создающих картограммы с использованием географических типов данных Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1525">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="9c87c-1526">Преимущество для пользователей заключается в более глубокой интеграции функций и повышенной точности в области, которую пользователь хочет отобразить на карте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1526">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="9c87c-1527">Дополнительные преимущества включают возможность нанесения на карту многоугольников городов.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1527">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9c87c-1528">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1528">Getting Started:</span></span>

- <span data-ttu-id="9c87c-1529">Эта возможность является улучшением существующих функций в Excel.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1529">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="9c87c-1530">Чтобы использовать улучшение, преобразуйте расположения в объекты Rich и выполните построение с помощью картограмм.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1530">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1531">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1531">Scenarios to Try:</span></span>

- <span data-ttu-id="9c87c-1532">Пользователи могут попробовать указать на картах города, регионы, районы, страны и почтовые индексы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1532">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1533">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1533">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9c87c-1534">Все приложения</span><span class="sxs-lookup"><span data-stu-id="9c87c-1534">All Applications</span></span>
- <span data-ttu-id="9c87c-1535">Исправлена ошибка, из-за которой диалоговое окно первого запуска отображалось при каждом запуске приложения</span><span class="sxs-lookup"><span data-stu-id="9c87c-1535">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="9c87c-1536">Исправлена ошибка с возможным отсутствием ссылки SharePoint в диалоговом окне "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1536">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="9c87c-1537">Исправлена ошибка, из-за которой для пользователей неправильно отображалось диалоговое окно "Восстановить"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1537">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1538">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1538">Word</span></span> 
- <span data-ttu-id="9c87c-1539">Исправлена ошибка, из-за которой у некоторых пользователей могла возникать ошибка с сообщением о недостатке памяти или места на диске при запросе шрифта</span><span class="sxs-lookup"><span data-stu-id="9c87c-1539">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="9c87c-1540">Исправлена ошибка, из-за которой мог теряться фокус окна при переходе из области примечаний</span><span class="sxs-lookup"><span data-stu-id="9c87c-1540">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1541">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1541">Excel</span></span>
- <span data-ttu-id="9c87c-1542">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1542">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1543">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1544">Исправлена ошибка, не позволявшая изменять размер фигур с фирменной символикой</span><span class="sxs-lookup"><span data-stu-id="9c87c-1544">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="9c87c-1545">Исправлена ошибка, из-за которой приложение PowerPoint могло аварийно завершать работу при открытии файла в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="9c87c-1545">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1546">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1546">Outlook</span></span>
- <span data-ttu-id="9c87c-1547">Исправлена ошибка, не позволявшая некоторым пользователям выделять китайские слова</span><span class="sxs-lookup"><span data-stu-id="9c87c-1547">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="9c87c-1548">Исправлена ошибка с неправильным вычислением сроков действия</span><span class="sxs-lookup"><span data-stu-id="9c87c-1548">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1549">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1549">Access</span></span>
- <span data-ttu-id="9c87c-1550">Исправлена ошибка, не позволявшая некоторым пользователям применять построитель макросов</span><span class="sxs-lookup"><span data-stu-id="9c87c-1550">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="9c87c-1551">Исправлена ошибка, из-за которой при печати отчета печаталась только первая страница</span><span class="sxs-lookup"><span data-stu-id="9c87c-1551">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="9c87c-1552">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при наведении указателя на гиперссылку</span><span class="sxs-lookup"><span data-stu-id="9c87c-1552">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="9c87c-1553">Исправлена проблема, приводившая к отображению некоторых элементов вне экрана при использовании представления "Схема данных"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1553">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1554">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1554">Project</span></span>
- <span data-ttu-id="9c87c-1555">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1555">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="9c87c-1556">12 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1556">April 12, 2019</span></span>
<span data-ttu-id="9c87c-1557">Версия 1905 (сборка 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1557">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1558">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1558">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1559">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1559">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="9c87c-1560">Получение интеллектуальных данных с помощью Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="9c87c-1560">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="9c87c-1561">Импортируйте интеллектуальные данные или ссылайтесь на них и взгляните по-новому на свою классическую базу данных с помощью интеллектуальных технологий.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1561">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1562">Важные исправления</span><span class="sxs-lookup"><span data-stu-id="9c87c-1562">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9c87c-1563">Все приложения</span><span class="sxs-lookup"><span data-stu-id="9c87c-1563">All Applications</span></span>
 - <span data-ttu-id="9c87c-1564">Исправлена ошибка, не позволявшая некоторым пользователям сохранять файлы в облачных расположениях</span><span class="sxs-lookup"><span data-stu-id="9c87c-1564">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="9c87c-1565">Исправлена ошибка, из-за которой могла открываться неправильная область из ленты</span><span class="sxs-lookup"><span data-stu-id="9c87c-1565">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1566">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1566">Word</span></span> 
- <span data-ttu-id="9c87c-1567">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1567">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1568">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1568">Excel</span></span>
- <span data-ttu-id="9c87c-1569">Исправлена ошибка, из-за которой для пользователей отображалось сообщение об ошибке, относящееся к связанным типам данных, если книга не содержала связанные типы данных</span><span class="sxs-lookup"><span data-stu-id="9c87c-1569">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="9c87c-1570">Исправлена ошибка, из-за которой URL-ссылки в документе Word могли изменяться в зависимости от способа просмотра (локально или в Интернете)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1570">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1571">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1572">Исправлена ошибка, из-за которой мог происходить сбой приложения после отмены всех изменений на вкладке "Анимация"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1572">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1573">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1573">Outlook</span></span>
- <span data-ttu-id="9c87c-1574">Исправлена ошибка, не позволявшая некоторым пользователям изменять поле "Заметки" для контактов в общедоступной папке</span><span class="sxs-lookup"><span data-stu-id="9c87c-1574">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="9c87c-1575">Исправлена ошибка, из-за которой мог возникать конфликт между датами окончания срока действия и датами удаления</span><span class="sxs-lookup"><span data-stu-id="9c87c-1575">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1576">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1576">Access</span></span>
- <span data-ttu-id="9c87c-1577">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1577">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1578">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1578">Project</span></span>
- <span data-ttu-id="9c87c-1579">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1579">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="9c87c-1580">5 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1580">April 5, 2019</span></span>
<span data-ttu-id="9c87c-1581">Версия 1904 (сборка 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1581">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1582">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1582">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1583">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1583">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="9c87c-1584">Outlook для Windows: настройка параметров сортировки почты и предоставление к ним общего доступа</span><span class="sxs-lookup"><span data-stu-id="9c87c-1584">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="9c87c-1585">Ваши параметры сортировки почты хранятся в облаке, поэтому можно наслаждаться единообразным интерфейсом при использовании Outlook для Windows и Outlook в Интернете с любого устройства.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1585">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1586">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1586">Getting Started:</span></span>

<span data-ttu-id="9c87c-1587">На вкладке "Общие" в разделе "Файл" > "Параметры" есть новый параметр "Хранить мои параметры Outlook в облаке".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1587">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="9c87c-1588">Пользователям нужно установить флажок, чтобы разрешить перенос параметра сортировки почты в другие экземпляры классической версии Outlook и Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1588">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1589">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1589">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1590">Измените сортировку почты на компьютере с включенными облачными параметрами.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1590">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="9c87c-1591">Перейдите в Outlook Web App и убедитесь, что этот параметр также применен.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1591">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="9c87c-1592">Измените настройки сортировки почты в Outlook Web App и запустите классическую версию Outlook, чтобы увидеть применение этих настроек.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1592">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1593">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1593">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="9c87c-1594">В режиме "Средства обучения" реализована поддержка дополнительных цветов страниц</span><span class="sxs-lookup"><span data-stu-id="9c87c-1594">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="9c87c-1595">Средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1595">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="9c87c-1596">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1596">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1597">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1597">Getting Started:</span></span>

<span data-ttu-id="9c87c-1598">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1598">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1599">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1599">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1600">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1600">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1601">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1601">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="9c87c-1602">Расширение возможностей для творчества с помощью анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="9c87c-1602">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="9c87c-1603">Теперь Office поддерживает анимированные модели, воспроизводимые в редакторе, чтобы вы могли оживить свои листы!</span><span class="sxs-lookup"><span data-stu-id="9c87c-1603">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1604">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1604">Getting Started:</span></span>

1. <span data-ttu-id="9c87c-1605">Откройте Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1605">Open Excel</span></span>
2. <span data-ttu-id="9c87c-1606">Вставьте анимированную трехмерную модель (вскоре будут доступны в сообществе Remix, а пока их можно найти здесь: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1606">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="9c87c-1607">Анимированная модель будет воспроизводиться в редакторе!</span><span class="sxs-lookup"><span data-stu-id="9c87c-1607">The animated model will play in the editor!</span></span> <span data-ttu-id="9c87c-1608">Проверьте режим слайд-шоу, она будет воспроизводиться и там!</span><span class="sxs-lookup"><span data-stu-id="9c87c-1608">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="9c87c-1609">На ленте форматирования трехмерных моделей можно ознакомиться с дополнительными анимационными сценами в модели</span><span class="sxs-lookup"><span data-stu-id="9c87c-1609">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1610">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1610">Scenarios to Try:</span></span>

1. <span data-ttu-id="9c87c-1611">Вставьте анимированную модель и посмотрите, как она будет воспроизводиться в редакторе</span><span class="sxs-lookup"><span data-stu-id="9c87c-1611">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="9c87c-1612">Узнайте, какие анимационные сцены доступны для анимированной модели в коллекции "Сцены" на ленте форматирования трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="9c87c-1612">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="9c87c-1613">Можно воспроизводить или приостанавливать анимацию с помощью ленты, мини-панели или клавиши ПРОБЕЛ.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1613">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1614">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1614">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9c87c-1615">Все приложения</span><span class="sxs-lookup"><span data-stu-id="9c87c-1615">All Applications</span></span>
- <span data-ttu-id="9c87c-1616">Мы исправили ошибку, когда значок приложения для Excel может отображаться неправильно в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1616">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="9c87c-1617">Мы исправили ошибку, когда после установки обновления может исчезать кнопка меню "Файл".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1617">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="9c87c-1618">Исправлена проблема, в результате которой может измениться пользовательская лицензия.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1618">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1619">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1619">Word</span></span> 
- <span data-ttu-id="9c87c-1620">Исправлена проблема с неправильным отображением текста при определенных уровнях масштабирования.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1620">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1621">Excel</span></span>
- <span data-ttu-id="9c87c-1622">Мы исправили ошибку, в результате которой пользователи могли не видеть запрос на сохранение книги после внесения изменений.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1622">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="9c87c-1623">Мы исправили ошибку, когда событие BeforeSave не запускалось, если пользователь предоставил общий доступ к книге.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1623">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="9c87c-1624">Исправлена проблема, когда изменение размера столбца на менее чем 6 пикселей вызывает появление сообщения об ошибке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1624">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="9c87c-1625">Исправлена ошибка, когда Excel игнорирует метку Application.Visible.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1625">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="9c87c-1626">Исправлена ошибка, когда стрелки трассировки остаются на неактивных закрепленных областях.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1626">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="9c87c-1627">Исправлена ошибка, когда форматирование ячеек дат и валют может изменяться при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1627">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="9c87c-1628">Мы исправили ошибку, когда подсказки могли неожиданно перемещаться</span><span class="sxs-lookup"><span data-stu-id="9c87c-1628">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="9c87c-1629">Мы исправили ошибки локализации редактора Power Query</span><span class="sxs-lookup"><span data-stu-id="9c87c-1629">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="9c87c-1630">Мы устранили проблему, когда рабочая книга могла удаляться из вложений при отправке по электронной почте.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1630">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1631">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1632">Мы устранили проблему с длительным временем, которое может требоваться на копирование форм.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1632">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1633">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1633">Outlook</span></span>
- <span data-ttu-id="9c87c-1634">Мы устранили проблему с аварийным завершением работы Outlook при использовании инструмента рисования</span><span class="sxs-lookup"><span data-stu-id="9c87c-1634">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="9c87c-1635">Устранена проблема локализации при составлении HTML-сообщений электронной почты</span><span class="sxs-lookup"><span data-stu-id="9c87c-1635">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="9c87c-1636">Мы устранили проблему, когда пользователи сталкивались с трудностями при выборе нижней панели</span><span class="sxs-lookup"><span data-stu-id="9c87c-1636">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1637">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1637">Access</span></span>
- <span data-ttu-id="9c87c-1638">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1638">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1639">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1639">Project</span></span>
- <span data-ttu-id="9c87c-1640">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1640">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="9c87c-1641">22 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1641">March 22, 2019</span></span>
<span data-ttu-id="9c87c-1642">Версия 1904 (сборка 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1642">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="9c87c-1643">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1643">New Features</span></span>

- <span data-ttu-id="9c87c-1644">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1644">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="9c87c-1645">Дополнительные сведения <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="9c87c-1645">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="9c87c-1646">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1646">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1647">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1647">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1648">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1648">Word</span></span> 
- <span data-ttu-id="9c87c-1649">Устранена ошибка, при которой в интерфейсе пользователя постоянно отображается "Проверка изменений".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1649">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1650">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1650">Excel</span></span>
- <span data-ttu-id="9c87c-1651">Устранена ошибка, при которой приложение аварийно завершало работу после перемещения листа</span><span class="sxs-lookup"><span data-stu-id="9c87c-1651">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="9c87c-1652">Устранена ошибка, при которой приложение аварийно завершало работу после сохранения в формате PDF</span><span class="sxs-lookup"><span data-stu-id="9c87c-1652">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="9c87c-1653">Устранена ошибка, при которой диалоговое окно сохранения не воспринимало некоторые корейские символы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1653">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1654">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1655">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1655">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1656">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1656">Outlook</span></span>
- <span data-ttu-id="9c87c-1657">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1657">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1658">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1658">Access</span></span>
- <span data-ttu-id="9c87c-1659">Исправлено сообщение об ошибке в Access, при которой создавался дополнительный ярлык для Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1659">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="9c87c-1660">Устранена ошибка, при которой данные со связанного сайта SharePoint отображались неправильно</span><span class="sxs-lookup"><span data-stu-id="9c87c-1660">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1661">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1661">Project</span></span>
- <span data-ttu-id="9c87c-1662">Устранена ошибка, при которой языковые параметры менялись с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="9c87c-1662">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="9c87c-1663">Устранена ошибка, при которой приложение аварийно завершало работу при синхронизации с SharePoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1663">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="9c87c-1664">15 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1664">March 15, 2019</span></span>
<span data-ttu-id="9c87c-1665">Версия 1904 (сборка 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1665">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1666">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1666">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1667">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1667">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="9c87c-1668">Режим фокусировки</span><span class="sxs-lookup"><span data-stu-id="9c87c-1668">Focus Mode</span></span>

<span data-ttu-id="9c87c-1669">Хотите, чтобы вас ничего не отвлекало от работы? Переключитесь в режим фокусировки в меню "Вид".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1669">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="9c87c-1670">Только для обладателей подписки на Office 365.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1670">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1671">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1671">Getting Started:</span></span>

<span data-ttu-id="9c87c-1672">Кнопка "Фокус" вкладки "Вид" в строке состояния ленты с кнопкой "Фокус"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1672">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1673">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1673">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1674">Переход в режим фокусировки и работа в интерфейсе фокусировки</span><span class="sxs-lookup"><span data-stu-id="9c87c-1674">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1675">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1675">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1676">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1676">Word</span></span> 
- <span data-ttu-id="9c87c-1677">Исправлена проблема, из-за которой изображения в документе, сохраненном в формате PDF, имели неправильное значение точек на дюйм</span><span class="sxs-lookup"><span data-stu-id="9c87c-1677">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1678">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1678">Excel</span></span>
- <span data-ttu-id="9c87c-1679">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1679">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1680">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1681">Исправлена проблема, из-за которой область примечаний открывалась и закрывалась неправильно</span><span class="sxs-lookup"><span data-stu-id="9c87c-1681">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="9c87c-1682">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при удалении видео</span><span class="sxs-lookup"><span data-stu-id="9c87c-1682">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="9c87c-1683">Исправлена проблема, когда некоторые экземпляры приложения не запускались.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1683">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1684">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1684">Outlook</span></span>
- <span data-ttu-id="9c87c-1685">Исправлена проблема с неправильными уведомлениями о прочтении при просмотре на японском языке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1685">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1686">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1686">Access</span></span>
- <span data-ttu-id="9c87c-1687">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1687">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1688">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1688">Project</span></span>
- <span data-ttu-id="9c87c-1689">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1689">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="9c87c-1690">8 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1690">March 8, 2019</span></span> 
<span data-ttu-id="9c87c-1691">Версия 1903 (сборка 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1691">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1692">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1692">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1693">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1693">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="9c87c-1694">Находите нужные элементы с помощью Поиска (Майкрософт)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1694">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="9c87c-1695">С помощью поиска Майкрософт можно найти все файлы, команды и пользователей, которые необходимы для выполнения работы.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1695">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1696">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1696">Getting Started:</span></span>

- <span data-ttu-id="9c87c-1697">Эта функция выделяется вверху пользовательского интерфейса в заголовке.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1697">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1698">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1698">Scenarios to Try:</span></span>

- <span data-ttu-id="9c87c-1699">Поиск учебного заведения, недавнего документа или часто используемых команд ленты</span><span class="sxs-lookup"><span data-stu-id="9c87c-1699">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="9c87c-1700">Поиск статьи или темы и получение дополнительных сведений о ней</span><span class="sxs-lookup"><span data-stu-id="9c87c-1700">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="9c87c-1701">Совместное редактирование</span><span class="sxs-lookup"><span data-stu-id="9c87c-1701">CoAuthoring</span></span>

<span data-ttu-id="9c87c-1702">Вам надоело получать блокировку на документы с макросами?</span><span class="sxs-lookup"><span data-stu-id="9c87c-1702">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="9c87c-1703">Теперь DOCM-файлы в OneDrive для бизнеса поддерживают одновременное редактирование несколькими авторами.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1703">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1704">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1704">Getting Started:</span></span>

<span data-ttu-id="9c87c-1705">Пользователю не нужно нажимать какие-либо кнопки в пользовательском интерфейсе, чтобы применить эту возможность.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1705">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="9c87c-1706">Она включена по умолчанию для DOCM-файлов в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1706">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="9c87c-1707">Чтобы применить ее, пользователю нужно сохранить DOCM-файл в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1707">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1708">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1708">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1709">Создайте DOCM-файл в OneDrive для бизнеса, поделитесь им с коллегами и работайте совместно!</span><span class="sxs-lookup"><span data-stu-id="9c87c-1709">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1710">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1710">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1711">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1711">Word</span></span> 
- <span data-ttu-id="9c87c-1712">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="9c87c-1712">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="9c87c-1713">Решена проблема со сбоем, происходившим при ответе на примечания</span><span class="sxs-lookup"><span data-stu-id="9c87c-1713">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="9c87c-1714">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="9c87c-1714">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1715">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1715">Excel</span></span>
- <span data-ttu-id="9c87c-1716">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="9c87c-1716">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1717">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1717">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1718">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1718">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1719">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1719">Outlook</span></span>
- <span data-ttu-id="9c87c-1720">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="9c87c-1720">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="9c87c-1721">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1721">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="9c87c-1722">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1722">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1723">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1723">Access</span></span>
- <span data-ttu-id="9c87c-1724">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="9c87c-1724">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="9c87c-1725">Исправлена проблема, из-за которой пользователи не могли присвоить свойству DisplayControl для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="9c87c-1725">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1726">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1726">Project</span></span>
- <span data-ttu-id="9c87c-1727">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1727">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="9c87c-1728">1 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1728">March 1, 2019</span></span> 
<span data-ttu-id="9c87c-1729">Версия 1903 (сборка 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1729">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1730">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1730">What's New</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1731">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1731">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="9c87c-1732">Синхронизированные цвета для отслеживания изменений, примечаний и совместной работы в режиме реального времени</span><span class="sxs-lookup"><span data-stu-id="9c87c-1732">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="9c87c-1733">Исправления в наших продуктах теперь обеспечивают отображение одинаковым цветом примечаний, изменений и указателя мыши при совместной работе.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1733">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1734">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1734">Getting Started:</span></span>

<span data-ttu-id="9c87c-1735">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1735">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="9c87c-1736">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1736">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1737">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1737">Scenarios to Try:</span></span>

<span data-ttu-id="9c87c-1738">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1738">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="9c87c-1739">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1739">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1740">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1740">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1741">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1741">Word</span></span> 
- <span data-ttu-id="9c87c-1742">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="9c87c-1742">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="9c87c-1743">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="9c87c-1743">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1744">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1744">Excel</span></span>
- <span data-ttu-id="9c87c-1745">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="9c87c-1745">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1746">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1746">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1747">Исправлена проблема с размером изображения слайда при использовании @упоминаний в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1747">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1748">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1748">Outlook</span></span>
- <span data-ttu-id="9c87c-1749">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="9c87c-1749">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="9c87c-1750">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1750">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="9c87c-1751">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1751">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1752">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1752">Access</span></span>
- <span data-ttu-id="9c87c-1753">Обновлен текст запроса, отображаемый для подтверждения обновления связей таблицы с источником данных</span><span class="sxs-lookup"><span data-stu-id="9c87c-1753">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="9c87c-1754">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="9c87c-1754">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="9c87c-1755">Исправлена проблема, из-за которой пользователи не могли присвоить свойству "Тип элемента управления" для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="9c87c-1755">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1756">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1756">Project</span></span>
- <span data-ttu-id="9c87c-1757">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1757">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="9c87c-1758">15 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1758">February 15, 2019</span></span> 
<span data-ttu-id="9c87c-1759">Версия 1903 (сборка 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1759">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9c87c-1760">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1760">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1761">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1761">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="9c87c-1762">Улучшения перехода "Трансформация" — трансформация по имени</span><span class="sxs-lookup"><span data-stu-id="9c87c-1762">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="9c87c-1763">Укажите фигуры, которые нужно трансформировать</span><span class="sxs-lookup"><span data-stu-id="9c87c-1763">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1764">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1764">Getting Started:</span></span>

- <span data-ttu-id="9c87c-1765">Чтобы при переходе "Трансформация" два объекта обрабатывались как одинаковые, пользователь может переименовать фигуры с помощью области выделения.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1765">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="9c87c-1766">Имя должно начинаться с двух восклицательных знаков</span><span class="sxs-lookup"><span data-stu-id="9c87c-1766">The name must be prefaced with "!!"</span></span> <span data-ttu-id="9c87c-1767">("!!"), чтобы использовать его при трансформации для переопределения стандартного сопоставления, например "!!Имя"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1767">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="9c87c-1768">Пользователи могут продолжать переименовывать фигуры, используя любые имена, которые не начинаются с "!!",</span><span class="sxs-lookup"><span data-stu-id="9c87c-1768">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="9c87c-1769">не беспокоясь о том, что это изменит работу перехода "Трансформация".</span><span class="sxs-lookup"><span data-stu-id="9c87c-1769">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1770">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1770">Scenarios to Try:</span></span>

- <span data-ttu-id="9c87c-1771">Вставьте фигуру на слайд, например прямоугольник</span><span class="sxs-lookup"><span data-stu-id="9c87c-1771">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="9c87c-1772">Создайте новый слайд</span><span class="sxs-lookup"><span data-stu-id="9c87c-1772">Create a new slide</span></span>
- <span data-ttu-id="9c87c-1773">Вставьте другую фигуру на втором слайде, например треугольник</span><span class="sxs-lookup"><span data-stu-id="9c87c-1773">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="9c87c-1774">Откройте область выделения и присвойте имя "!!фигура" прямоугольнику на слайде 1 и треугольнику на слайде 2.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1774">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="9c87c-1775">Примените переход "Трансформация" ко второму слайду</span><span class="sxs-lookup"><span data-stu-id="9c87c-1775">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="9c87c-1776">Улучшения перехода "Трансформация" — графические элементы SmartArt</span><span class="sxs-lookup"><span data-stu-id="9c87c-1776">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="9c87c-1777">Трансформация графических элементов SmartArt с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="9c87c-1777">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1778">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1778">Getting Started:</span></span>

<span data-ttu-id="9c87c-1779">Аналогичное использование перехода "Трансформация" при применении графических элементов SmartArt</span><span class="sxs-lookup"><span data-stu-id="9c87c-1779">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1780">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1780">Scenarios to Try:</span></span>

- <span data-ttu-id="9c87c-1781">Вставьте графический элемент SmartArt на слайд</span><span class="sxs-lookup"><span data-stu-id="9c87c-1781">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="9c87c-1782">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="9c87c-1782">Duplicate the Slide</span></span>
- <span data-ttu-id="9c87c-1783">Поменяйте размер, измените или переместите графический элемент SmartArt на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="9c87c-1783">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="9c87c-1784">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="9c87c-1784">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="9c87c-1785">Улучшения перехода "Трансформация" — таблицы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1785">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="9c87c-1786">Трансформация таблиц с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="9c87c-1786">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9c87c-1787">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1787">Getting Started:</span></span>
<span data-ttu-id="9c87c-1788">Аналогичное использование перехода "Трансформация" при применении таблиц</span><span class="sxs-lookup"><span data-stu-id="9c87c-1788">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1789">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1789">Scenarios to Try:</span></span>

- <span data-ttu-id="9c87c-1790">Вставьте таблицу на слайд</span><span class="sxs-lookup"><span data-stu-id="9c87c-1790">Insert a Table in a slide</span></span>
- <span data-ttu-id="9c87c-1791">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="9c87c-1791">Duplicate the slide</span></span>
- <span data-ttu-id="9c87c-1792">Поменяйте размер, измените или переместите таблицу на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="9c87c-1792">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="9c87c-1793">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="9c87c-1793">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="9c87c-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher и Visio</span><span class="sxs-lookup"><span data-stu-id="9c87c-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="9c87c-1795">Легкое переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="9c87c-1795">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="9c87c-1796">Новый диспетчер учетных записей отображает все рабочие и личные учетные записи в одном месте и позволяет управлять переключением между ними.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1796">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="9c87c-1797">Этот обновленный интерфейс уточняет способ выполненного входа и обеспечивает возможность переключения между рабочими и личными учетными записями без выхода из системы или появления сложных диалоговых окон.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1797">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="9c87c-1799">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1799">Scenarios to Try:</span></span>
- <span data-ttu-id="9c87c-1800">Переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="9c87c-1800">Switch between accounts</span></span>
- <span data-ttu-id="9c87c-1801">Добавление новой учетной записи [Примечание. Рекомендуется сначала открыть "Файл" | "Учетная запись" | "Подключенные службы" и удалить все личные службы, подключенные к рабочей учетной записи и наоборот]</span><span class="sxs-lookup"><span data-stu-id="9c87c-1801">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="9c87c-1802">Выход из учетной записи</span><span class="sxs-lookup"><span data-stu-id="9c87c-1802">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1803">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1803">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1804">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1804">Word</span></span> 
- <span data-ttu-id="9c87c-1805">Исправлена проблема с предварительным просмотром контекста для таблиц и изображений</span><span class="sxs-lookup"><span data-stu-id="9c87c-1805">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1806">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1806">Excel</span></span>
- <span data-ttu-id="9c87c-1807">Исправлена ошибка, из-за которой при использовании темы "Черная" текст в поле поиска автофильтра был белого цвета</span><span class="sxs-lookup"><span data-stu-id="9c87c-1807">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="9c87c-1808">Исправлена проблема с согласованным пользовательским интерфейсом для новой надстройки Office</span><span class="sxs-lookup"><span data-stu-id="9c87c-1808">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1809">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1810">Исправлена проблема с автоматическим расширением области отображения во время презентации на ноутбуках и планшетах.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1810">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1811">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1811">Outlook</span></span>
- <span data-ttu-id="9c87c-1812">Исправлена проблема с отображением кнопки "Отправить в OneNote"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1812">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1813">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1813">Access</span></span>
- <span data-ttu-id="9c87c-1814">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1814">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1815">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1815">Project</span></span>
- <span data-ttu-id="9c87c-1816">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1816">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="9c87c-1817">11 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1817">February 11, 2019</span></span>
<span data-ttu-id="9c87c-1818">Версия 1903 (сборка 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1818">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1819">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1819">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1820">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1820">Word</span></span> 
- <span data-ttu-id="9c87c-1821">Исправлена ошибка, из-за которой некоторые настроенные стили нельзя было применить в Word Online</span><span class="sxs-lookup"><span data-stu-id="9c87c-1821">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="9c87c-1822">Исправлены проблемы предварительного просмотра контекста, связанные с форматированными объектами в Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1822">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="9c87c-1823">Исправлена ошибка, из-за которой при вставке списков происходил сбой Word.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1823">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1824">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1824">Excel</span></span>
- <span data-ttu-id="9c87c-1825">Исправлена ошибка, из-за которой добавляемые пробелы после числовых форматов не отображались при отсутствии обозначения денежной единицы</span><span class="sxs-lookup"><span data-stu-id="9c87c-1825">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="9c87c-1826">Исправлена проблема с автоматическим определением акций</span><span class="sxs-lookup"><span data-stu-id="9c87c-1826">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1827">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1827">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1828">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1828">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1829">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1829">Outlook</span></span>
- <span data-ttu-id="9c87c-1830">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1830">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1831">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1831">Access</span></span>
- <span data-ttu-id="9c87c-1832">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1832">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1833">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1833">Project</span></span>
- <span data-ttu-id="9c87c-1834">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1834">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="9c87c-1835">1 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1835">February 1, 2019</span></span> 
<span data-ttu-id="9c87c-1836">Версия 1902 (сборка 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="9c87c-1836">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9c87c-1837">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="9c87c-1837">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="9c87c-1838">Word</span><span class="sxs-lookup"><span data-stu-id="9c87c-1838">Word</span></span> 
- <span data-ttu-id="9c87c-1839">Устранена проблема с изменением размера ячеек во внедренной таблице Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1839">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="9c87c-1840">Устранена проблема с копированием и вставкой фигур на полотне</span><span class="sxs-lookup"><span data-stu-id="9c87c-1840">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="9c87c-1841">Excel</span><span class="sxs-lookup"><span data-stu-id="9c87c-1841">Excel</span></span>
- <span data-ttu-id="9c87c-1842">Исправлена ошибка с открытием файлов из Excel Web App</span><span class="sxs-lookup"><span data-stu-id="9c87c-1842">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="9c87c-1843">Исправлена ошибка, вызывавшая сбой при сохранении CSV-файла в формате XLSX из-за длины имени файла</span><span class="sxs-lookup"><span data-stu-id="9c87c-1843">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="9c87c-1844">Исправлено контекстное меню для отображения параметров контекстного меню</span><span class="sxs-lookup"><span data-stu-id="9c87c-1844">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9c87c-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9c87c-1845">PowerPoint</span></span>
- <span data-ttu-id="9c87c-1846">Устранена проблема, из-за которой пользователи не могли использовать сочетания клавиш CTRL+ALT+7 и CTRL+ALT+8 для ввода квадратных скобок</span><span class="sxs-lookup"><span data-stu-id="9c87c-1846">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="9c87c-1847">Исправлена ошибка, из-за которой при вставке локального видео в файл PPT уменьшалось место на диске "C"</span><span class="sxs-lookup"><span data-stu-id="9c87c-1847">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="9c87c-1848">Исправлена кнопка "Публикация в Microsoft Stream", не отображавшаяся у некоторых пользователей</span><span class="sxs-lookup"><span data-stu-id="9c87c-1848">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="9c87c-1849">Outlook</span><span class="sxs-lookup"><span data-stu-id="9c87c-1849">Outlook</span></span>
- <span data-ttu-id="9c87c-1850">Исправлена ошибка, из-за которой в представлении задач в календаре неправильно отображалась тема задачи.</span><span class="sxs-lookup"><span data-stu-id="9c87c-1850">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="9c87c-1851">Access</span><span class="sxs-lookup"><span data-stu-id="9c87c-1851">Access</span></span>
- <span data-ttu-id="9c87c-1852">Исправлена проблема с масштабированием диаграмм</span><span class="sxs-lookup"><span data-stu-id="9c87c-1852">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="9c87c-1853">Project</span><span class="sxs-lookup"><span data-stu-id="9c87c-1853">Project</span></span>
- <span data-ttu-id="9c87c-1854">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="9c87c-1854">Various performance and stability fixes</span></span>
