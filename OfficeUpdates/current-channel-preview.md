---
title: Заметки о выпуске Актуального канала (предварительная версия)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставление участникам программы предварительной оценки с поздним доступом последнего списка новых функций, исправлений или известных проблем
ms.openlocfilehash: 712501114acb6e1a14ae8f0c55727ac3e504afe1
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851849"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="2bf7d-103">Заметки о выпуске Актуального канала Office (предварительная версия)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="2bf7d-104">Эта статья содержит заметки о выпуске для сборок Актуального канала (предварительная версия) приложений Word, Excel, PowerPoint, Outlook, Access, Project и Teams для Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="2bf7d-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="2bf7d-106">Обратите внимание, что развертывание возможностей (а иногда даже исправлений) в Актуальном канале (предварительная версия) зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="2bf7d-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="2bf7d-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  


> [!NOTE]
> - <span data-ttu-id="2bf7d-109">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="2bf7d-110">Функции Microsoft Teams могут отличаться от последних версий Актуального канала (предварительная версия), поскольку они выпускаются чаще.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-110">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2106-june-07"></a><span data-ttu-id="2bf7d-113">Версия 2106: 7 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-113">Version 2106: June 07</span></span>
<span data-ttu-id="2bf7d-114">*Версия 2106 (сборка 14131.20012)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-114">*Version 2106 (Build 14131.20012)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-116">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-116">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-117">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-117">Excel</span></span>

- <span data-ttu-id="2bf7d-118">Исправлена проблема, из-за которой диспетчеру имен не удавалось открывать книги с большим количеством скрытых имен.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-118">We fixed an issue that prevented the Name Manager from opening books with a large number of hidden names.</span></span>


- <span data-ttu-id="2bf7d-119">Исправлена проблема, влиявшая на производительность функций ВПР и ИНДЕКС/ПОИСКПОЗ при заполнении большого объема данных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-119">We fixed an issue that impacted the performance of VLOOKUP and INDEX/MATCH when filling a large amount of data.</span></span>


- <span data-ttu-id="2bf7d-120">Исправлена проблема, из-за которой динамические массивы не обновляли значения ячеек, когда на них ссылались функции RealTimeData.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-120">We fixed an issue that caused Dynamic Arrays to not update cell values when referenced by RealTimeData functions.</span></span>


- <span data-ttu-id="2bf7d-121">Исправлена проблема, из-за которой режим замены IME не вводил символы, а ставил их в конце строки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-121">Fixed an issue where IME's OverType mode was not typing over characters, it left them at the end of the string.</span></span>


- <span data-ttu-id="2bf7d-122">Исправлена проблема, связанная с прокруткой двумя пальцами при использовании областей закрепления.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-122">We fixed an issue related to two-finger scrolling when using freeze panes.</span></span>


- <span data-ttu-id="2bf7d-123">Исправлена проблема, связанная с ошибками "Недостаточно памяти" при печати на крупноформатных принтерах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-123">We fixed an issue related to out of memory issues when printing on large-format printers.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-124">Outlook</span></span>

- <span data-ttu-id="2bf7d-125">Исправлена проблема, из-за которой сообщения с действиями либо постоянно обновлялись, либо возвращались к заголовкам после скачивания при запуске в режиме "Загружать только заголовки".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-125">We fixed an issue that caused users to see actionable messages either constantly refreshing or reverting back to headers after download when running in Download Headers Only mode.</span></span>


- <span data-ttu-id="2bf7d-126">Исправлена проблема, из-за которой пользователи не могли перемещать элементы между папками в версиях Outlook с лицензией "не бизнес".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-126">We fixed an issue where users were unable to move items across folders in "non-business" licensed Outlook versions.</span></span>


- <span data-ttu-id="2bf7d-127">Исправлена проблема, из-за которой пользователи сталкивались с непредвиденным закрытием при удалении папок из архивного хранилища.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-127">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="2bf7d-128">Исправлена проблема, из-за которой у некоторых пользователей приложение неожиданно закрывались при загрузке карточек пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-128">We fixed an issue that caused some users to experience a unexpected close when loading person cards.</span></span>


- <span data-ttu-id="2bf7d-129">Исправлена проблема, из-за которой средство выбора людей в Outlook разворачивалось вверх, а не вниз для пользователей с бессрочной лицензией.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-129">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


- <span data-ttu-id="2bf7d-130">Исправлена проблема, из-за которой параметр обратной связи не отображался для пользователей предварительной версии Office Perpetual 2021.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-130">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="2bf7d-131">Исправлена проблема, из-за которой пользователи видели копии всех отправленных элементов в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-131">We fixed an issue that caused users to see copies of all of their sent items appearing in their Outbox folder.</span></span>


- <span data-ttu-id="2bf7d-132">Исправлена проблема, из-за которой пользователи личных доменов видели предупреждающее сообщение о разрешениях при вставке ссылки в сообщение электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-132">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>


- <span data-ttu-id="2bf7d-133">Мы добавили раздел реестра, отключающий новые возможности поиска помещений (такой же, как в Outlook в Интернете) и включающий устаревшую версию поиска помещений с предлагаемыми интервалами времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-133">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

    <span data-ttu-id="2bf7d-134">Раздел реестра:</span><span class="sxs-lookup"><span data-stu-id="2bf7d-134">Registry Key:</span></span>

    ><span data-ttu-id="2bf7d-135">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="2bf7d-135">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    > <span data-ttu-id="2bf7d-136">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="2bf7d-136">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="2bf7d-137">0 (по умолчанию) — Outlook использует новый интерфейс поиска помещений на платформе OWA, когда пользователь нажимает кнопку "Поиск помещений" для поиска доступных помещений</span><span class="sxs-lookup"><span data-stu-id="2bf7d-137">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="2bf7d-138">1 — Outlook использует устаревший пользовательский интерфейс поиска помещений для поиска доступных помещений</span><span class="sxs-lookup"><span data-stu-id="2bf7d-138">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="2bf7d-139">Исправлена проблема, которая приводила к неожиданному закрытию при использовании чтения вслух с другими версиями Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-139">We fixed an issue that caused an expected close when using read aloud with other versions of Windows.</span></span>


- <span data-ttu-id="2bf7d-140">Исправлена проблема, из-за которой пользователи сталкивались с зависанием при удалении папок из архивного хранилища.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-140">We fixed an issue that caused users to experience a hang when removing folders from an archive store.</span></span>


- <span data-ttu-id="2bf7d-141">Исправлена проблема, из-за которой у некоторых пользователей был сбой при загрузке карточек пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-141">We fixed an issue that caused some users to experience a crash when loading person cards.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-142">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-142">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-143">Исправлена проблема, из-за которой было невозможно копировать данные из области заметок докладчика в режиме "Только чтение".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-143">We fixed an issue that prevented copying from the speaker notes pane while in Read Only mode.</span></span>


- <span data-ttu-id="2bf7d-144">Исправлена проблема, из-за которой файл, сохраненный с помощью кнопки "Повторить сохранение" на панели, не добавлялся в список последних файлов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-144">We fixed an issue to ensure that a file saved using the Retry Save button on the bus bar is added to the Recent List.</span></span>


- <span data-ttu-id="2bf7d-145">Исправлена проблема, из-за которой функция “Повторное использование слайдов” была недоступна некоторым пользователям.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-145">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-146">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-146">Project</span></span>

- <span data-ttu-id="2bf7d-147">Исправлена проблема, из-за которой назначения для задач, запланированных вручную, могли перемещаться на неверную дату.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-147">We fixed an issue where assignments on manually scheduled tasks could be moved to an incorrect date.</span></span>


- <span data-ttu-id="2bf7d-148">Исправлена проблема, из-за которой пул ресурсов зависал и его не удавалось открыть.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-148">We fixed an issue where the resource pool was unresponsive and couldn't be opened.</span></span>


- <span data-ttu-id="2bf7d-149">Исправлена ошибка, из-за которой возникала ошибка при создании формулы настраиваемого поля с использованием функции ProjectDate */ProjectDur* с определенными параметрами даты и времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-149">We fixed an issue where an error was generated if you created a custom field formula that used the ProjectDate */ProjectDur* functions with specific date or time parameters.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-150">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-150">Word</span></span>

- <span data-ttu-id="2bf7d-151">Исправлена проблема, из-за которой комментарий временно не отображался после публикации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-151">Fixes an issue where a  comment is temporarily blank after posting.</span></span>


- <span data-ttu-id="2bf7d-152">Исправлена проблема, из-за которой отображалось сообщение об ошибке "Сохранить как" даже после того, как пользователь выбирал "Отменить изменения".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-152">We fixed an issue where a Save As error message was displayed even after a user chose to discard changes.</span></span>


- <span data-ttu-id="2bf7d-153">Исправлена проблема, из-за которой было невозможно публиковать изображения в современных комментариях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-153">We fixed an issue that prevented images from being posted in modern comments.</span></span>


- <span data-ttu-id="2bf7d-154">Исправлена проблема, из-за которой нажатие сочетаний клавиш, например CTRL+SHIFT+@, не приводило к появлению символа с диакритическим знаком (в данном случае — "å").</span><span class="sxs-lookup"><span data-stu-id="2bf7d-154">We fixed an issue where pressing key combinations such as ctrl + shift + @ would not produce the expected accented character( in this case, 'å').</span></span>


- <span data-ttu-id="2bf7d-155">Исправлена проблема, связанная со сжатием изображений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-155">We fixed an issue related to image compression.</span></span>


- <span data-ttu-id="2bf7d-156">Исправлена проблема, из-за которой область "Рецензирование" могла прокручиваться (или имитировать прокрутку), но не совпадала с выбранным комментарием.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-156">We fixed an issue where the Reviewing pane could scroll or appear to scroll but didn't align with selected comment.</span></span>


- <span data-ttu-id="2bf7d-157">Исправлена проблема, из-за которой часть комментариев не сохранялась при экспорте документа в PDF.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-157">We fixed an issue where some comments were not saved when exporting a document to PDF.</span></span>


- <span data-ttu-id="2bf7d-158">Исправлена проблема, которая препятствовала редактированию нового комментария в незащищенной области документа при применении ограниченного редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-158">We fixed an issue that prevented the editing of a new comment in an unprotected area of a document when Restricted Editing is applied.</span></span>


- <span data-ttu-id="2bf7d-159">Исправлена проблема, связанная с ненужной анимацией прокрутки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-159">We fixed an issue related to unneeded scrolling animation.</span></span>


- <span data-ttu-id="2bf7d-160">Исправлена проблема, из-за которой неожиданно закрывалась область комментариев.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-160">Fixed an issue where the comments pane closed unexpectedly.</span></span>


- <span data-ttu-id="2bf7d-161">Исправлена проблема, из-за которой комментарии не выделяются при выборе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-161">We fixed an issue where comments aren't highlighted when selected.</span></span>


- <span data-ttu-id="2bf7d-162">Исправлена проблема, из-за которой выделенный фрагмент в документе не очищался при щелчке вне только что созданного комментария.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-162">We fixed an issue that caused the selection in the document to not be cleared when clicking outside a newly created comment.</span></span>


- <span data-ttu-id="2bf7d-163">Исправлена проблема, из-за которой не удавалось скопировать почтовое вложение в приложение, отличное от Word, если имя файла включало символы DBCS.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-163">We fixed an issue where copying a mail attachment to an application other than Word would fail if the filename included DBCS characters.</span></span>


- <span data-ttu-id="2bf7d-164">Исправлена проблема, которая приводила к неожиданному закрытию при использовании чтения вслух с другими версиями Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-164">We fixed an issue that caused an expected close when using read aloud with other versions of Windows.</span></span>


- <span data-ttu-id="2bf7d-165">Устранена проблема, из-за которой контекстные карточки холста для орфографии и грамматики отображали кнопки значков, но эти кнопки не имели всплывающих подсказок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-165">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


- <span data-ttu-id="2bf7d-166">Исправлена проблема, которая вызывала несоответствие между темой области "Редактор" и системной темой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-166">We fixed an issue that was causing a mismatch between the Editor pane theme and the system theme.</span></span>


- <span data-ttu-id="2bf7d-167">Исправлена проблема, из-за которой не открывается область редактора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-167">Fixed an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="2bf7d-168">Исправлена проблема, из-за которой подчеркивания сходства не исчезало при переключении в категорию проверки орфографии в редакторе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-168">Fixed an issue where similarity squiggles do not dissapear when switching to Spelling category in the Editor.</span></span>


- <span data-ttu-id="2bf7d-169">Исправлена проблема, из-за которой Word иногда отображал границу вокруг текста, которая не нужна.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-169">We fixed an issue where Word sometimes displayed a border around text that should not have been there.</span></span>


- <span data-ttu-id="2bf7d-170">Исправлена проблема, из-за которой для определенных шрифтов при повороте на 90 градусов увеличивался межзнаковый интервал.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-170">We fixed an issue where character spacing increases for specific fonts when rotating them 90 degrees.</span></span>


- <span data-ttu-id="2bf7d-171">Исправлена проблема, из-за которой при выполнении макроса обновлялось неверное поле, если были применены ограничения редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-171">We fixed an issue where the wrong field is getting updated when running a macro if editing restrictions are applied.</span></span>


- <span data-ttu-id="2bf7d-172">Исправлена проблема, из-за которой ответы на комментарии иногда терялись при совместном редактировании с несколькими пользователями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-172">We fixed an issue where comment replies were sometimes lost when coauthoring with multiple users.</span></span>


- <span data-ttu-id="2bf7d-173">Исправлена проблема с производительностью при работе с большими документами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-173">We fixed a performance issue related to working with large documents.</span></span>


- <span data-ttu-id="2bf7d-174">Исправлена проблема, из-за которой некоторые файлы Word не открываются из-за поврежденных закладок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-174">We fixed an issue where some Word files don't open because of corrupt bookmarks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-175">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-175">Office Suite</span></span>

- <span data-ttu-id="2bf7d-176">Исправлена проблема, из-за которой функция CLP ранее вызывала непроизвольные сохранения в файле SyncBacked (файл, синхронизированный службой OneDrive).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-176">We fixed an issue where the CLP feature previously caused unprompted saves to the SyncBacked file (File synced by OneDrive).</span></span>


- <span data-ttu-id="2bf7d-177">Исправлена проблема, из-за которой пользователю не удавалось редактировать файлы, сохраненные на локальных серверах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-177">We fixed an issue where the user was unable to edit files stored in OnPrem servers.</span></span>


- <span data-ttu-id="2bf7d-178">Исправлена регрессия производительности при открытии файлов SyncBacked.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-178">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="2bf7d-179">Исправлена проблема, из-за которой в OneDrive отображалось сообщение об ошибке слияния, когда конфликт слияния отсутствовал.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-179">We fixed an issue where OneDrive would display a merge error message when there was indeed no merge conflict.</span></span>


- <span data-ttu-id="2bf7d-180">Исправлена проблема, из-за которой вход с другой учетной записью приводил к отключению.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-180">We fixed an issue where signing in with a different account could result in a shutdown.</span></span>


- <span data-ttu-id="2bf7d-181">Исправлена проблема, связанная с z-порядком объектов SVG при преобразовании в фигуры.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-181">We fixed an issue related to z-order of SVG objects when converted to shapes.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-june-04"></a><span data-ttu-id="2bf7d-183">Версия 2105: 4 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-183">Version 2105: June 04</span></span>
<span data-ttu-id="2bf7d-184">*Версия 2105 (сборка 14026.20264)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-184">*Version 2105 (Build 14026.20264)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-186">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-186">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-187">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-187">Excel</span></span>

- <span data-ttu-id="2bf7d-188">**Параметры обнаружения типов данных.** Настройте поведение обнаружения типов данных при импорте данных из неструктурированных источников с помощью Power Query в Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-188">**Data type detection settings:** Configure the data type detection behavior when importing data from unstructured sources with Power Query in Excel</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-189">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-189">Word</span></span>

- <span data-ttu-id="2bf7d-190">**Стилистика.** Функции стилистики предоставляют замечания на основе выбранного пользователем уровня формальности</span><span class="sxs-lookup"><span data-stu-id="2bf7d-190">**Writing Styles:** Writing Styles curates critiques based on users' selected formality level</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-193">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-193">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-194">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-194">Excel</span></span>

- <span data-ttu-id="2bf7d-195">Исправлена проблема, из-за которой в списке надстроек Excel для некоторых пользователей отображались дополнительные записи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-195">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-june-01"></a><span data-ttu-id="2bf7d-197">Версия 2105: 1 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-197">Version 2105: June 01</span></span>
<span data-ttu-id="2bf7d-198">*Версия 2105 (сборка 14026.20254)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-198">*Version 2105 (Build 14026.20254)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-200">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-200">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-201">Outlook</span></span>

- <span data-ttu-id="2bf7d-202">**Последний вход или подозрительный вход:** теперь приложение Outlook предоставляет информацию о времени и месте последнего входа в вашу учетную запись, а также оповещает вас при обнаружении подозрительных действий входа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-202">**Last Sign In / Suspicious Sign In:** Outlook now tells you when and where you last signed into your account, and alerts you if any suspicious sign-in activity is detected</span></span>

- <span data-ttu-id="2bf7d-203">**Включение улучшений общего календаря.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-203">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="2bf7d-204">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-204">Turn on the preview for faster and more reliable updates to shared calendars.</span></span><br /><span data-ttu-id="2bf7d-205">Дополнительные сведения см. в [записи блога](https://insider.office.com/ru-RU/blog/shared-calendars-improvements-in-outlook-for-windows)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-205">See details in [blog post](https://insider.office.com/ru-RU/blog/shared-calendars-improvements-in-outlook-for-windows)</span></span>

- <span data-ttu-id="2bf7d-206">**Средство проверки доступности посылает напоминание при отправке сообщений в большие списки рассылки или внешним пользователям:** Мы добавили функцию автоматического напоминания с помощью подсказки о возможных нарушениях доступности при отправке сообщения широкой аудитории, внешним пользователям и т. д. Эти параметры доступны в разделе специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-206">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span><br /><span data-ttu-id="2bf7d-207">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/sending-accessible-emails-in-outlook-for-windows)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-207">See details in [blog post](https://insider.office.com/ru-RU/blog/sending-accessible-emails-in-outlook-for-windows)</span></span>

### <a name="visio"></a><span data-ttu-id="2bf7d-208">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-208">Visio</span></span>

- <span data-ttu-id="2bf7d-209">**Трафареты и фигуры AWS:** мы добавили трафареты с новейшими фигурами AWS, которые помогут вам создавать схемы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-209">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="2bf7d-210">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-210">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-213">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-213">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-214">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-214">Outlook</span></span>

- <span data-ttu-id="2bf7d-215">Исправлена проблема, которая может вызывать неожиданное закрытие при взаимодействии с почтой Outlook или представлениями календаря.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-215">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-may-23"></a><span data-ttu-id="2bf7d-217">Версия 2105: 23 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-217">Version 2105: May 23</span></span>
<span data-ttu-id="2bf7d-218">*Версия 2105 (сборка 14026.20246)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-218">*Version 2105 (Build 14026.20246)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-220">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-220">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-221">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-221">Teams</span></span>

- <span data-ttu-id="2bf7d-222">**Объявление о представлениях панели мониторинга данных об участии.** Вам больше не нужно вручную загружать отчеты. Теперь Teams позволяет просматривать все агрегированные данные в представлении панели мониторинга, вызываемой одним щелчком</span><span class="sxs-lookup"><span data-stu-id="2bf7d-222">**Announcing attendance data dashboard views:** No longer do you need to manually download reports, Teams now allows you to view all aggregated data in a one click dashboard view</span></span>

- <span data-ttu-id="2bf7d-223">**Функции безопасности, соответствия требованиям и защиты данных для приложений.** Для приложений Microsoft 365, сертифицированных для Teams, администраторы могут просматривать функции безопасности, соответствия требованиям и защиты данных на новой вкладке страницы сведений о приложении в Центре администрирования Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-223">**Security, compliance, and data protection capabilities for apps:** For Microsoft 365 Certified Teams apps, admins can view security, compliance, and data protection capabilities in a new tab on the app's detail page in the Teams Admin Center.</span></span> <span data-ttu-id="2bf7d-224">Эта прозрачность позволяет клиентам Майкрософт доверять приложениям, на которых основана работа их организаций.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-224">This transparency gives Microsoft customers trust in the applications that run their organizations.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-227">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-227">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-228">Outlook</span></span>

- <span data-ttu-id="2bf7d-229">Исправлена проблема, из-за которой некоторые инструкции для функции "Сократить длительность собраний" были недоступны при использовании технологий чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-229">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be unavailable through screen reader technologies.</span></span>


- <span data-ttu-id="2bf7d-230">Исправлена проблема, из-за которой у некоторых пользователей приложение неожиданно закрывались при загрузке карточек пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-230">We fixed an issue that caused some users to experience unexpectedly closed when loading person cards.</span></span>


- <span data-ttu-id="2bf7d-231">Мы добавили раздел реестра, отключающий новые возможности поиска помещений (такой же, как в Outlook в Интернете) и включающий устаревшую версию поиска помещений с предлагаемыми интервалами времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-231">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    - <span data-ttu-id="2bf7d-232">Раздел реестра:</span><span class="sxs-lookup"><span data-stu-id="2bf7d-232">Registry Key:</span></span>

        > <span data-ttu-id="2bf7d-233">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="2bf7d-233">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
        > <span data-ttu-id="2bf7d-234">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="2bf7d-234">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
        > <span data-ttu-id="2bf7d-235">0 (по умолчанию) — Outlook использует новый интерфейс поиска помещений на платформе OWA, когда пользователь нажимает кнопку "Поиск помещений" для поиска доступных помещений</span><span class="sxs-lookup"><span data-stu-id="2bf7d-235">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
        > <span data-ttu-id="2bf7d-236">1 — Outlook использует устаревший пользовательский интерфейс поиска помещений для поиска доступных помещений</span><span class="sxs-lookup"><span data-stu-id="2bf7d-236">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


### <a name="project"></a><span data-ttu-id="2bf7d-237">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-237">Project</span></span>

- <span data-ttu-id="2bf7d-238">Исправлена проблема, из-за которой назначения для задач, запланированных вручную, могли перемещаться в неверную дату.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-238">Fixed an issue where assignments on manually scheduled tasks may be moved to an incorrect date.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-may-19"></a><span data-ttu-id="2bf7d-240">Версия 2105: 19 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-240">Version 2105: May 19</span></span>
<span data-ttu-id="2bf7d-241">*Версия 2105 (сборка 14026.20202)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-241">*Version 2105 (Build 14026.20202)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-243">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-243">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-244">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-244">Teams</span></span>

- <span data-ttu-id="2bf7d-245">**Вебинары Teams интегрируются с Dynamics 365 Marketing, чтобы обеспечить привлечение потенциальных клиентов.** С помощью этой функции организаторы вебинаров могут поддерживать взаимодействие с зарегистрировавшимися участниками после мероприятия, используя D365 Marketing.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-245">**Teams Webinars integrate with Dynamics 365 Marketing to enable lead nurturing:** With this feature, webinar organizers can drive post event engagement with registrants by leveraging D365 Marketing.</span></span> <span data-ttu-id="2bf7d-246">Данные о задействовании участников синхронизируются с организацией D365 Marketing и поддерживают автоматические пользовательские процессы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-246">The attendee engagement data syncs with D365 Marketing org and enabled automated user journeys</span></span>

- <span data-ttu-id="2bf7d-247">**Интеллектуальные динамики.** Интеллектуальные динамики — это интеллектуальные периферийные устройства для Комнат Microsoft Teams в Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-247">**Intelligent speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="2bf7d-248">Эти устройства отображают для участников, находящихся в комнате собрания, транскрипцию собрания с указанием выступающих, поэтому участники смогут тратить меньше времени на запись заметок и смогут легче отслеживать, кто что сказал.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-248">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="2bf7d-249">**Позволяйте пользователям Teams приобретать приложения Teams в клиенте Teams.** Пользователи Teams теперь могут приобретать подписки на приложения Teams в Магазине Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-249">**Enable Teams users to purchase Teams apps through Teams client:** Teams users have now the ability to purchase Teams app subscriptions from the Teams store.</span></span>

- <span data-ttu-id="2bf7d-250">**Создавайте команды с помощью шаблонов команд.** Благодаря шаблонам в Teams пользователи могут выбирать из разнообразных настраиваемых вариантов при создании новой команды, что помогает быстрее начать работу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-250">**Create Teams with Team Templates:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="2bf7d-251">ИТ-администраторы также могут создавать настраиваемые шаблоны для своей организации, что позволяет им стандартизировать структуры команд, предварительно устанавливать важные приложения и масштабировать рекомендации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-251">IT Admins can also create custom templates for their organization, allowing them to standardize team structures, preinstall relevant apps, and scale best practices.</span></span> <span data-ttu-id="2bf7d-252">ИТ-администраторы могут выбрать в Центре администрирования Teams шаблоны команд, которые будут демонстрироваться конечным пользователям, а также предварительно настроить вкладки веб-сайтов, добавив URL-адреса на вкладку веб-сайта в шаблоне команды.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-252">IT Admins can choose which team templates to show to end users in Teams Admin Center, and also preconfigure website tabs by adding URLs to a website tab in a team template.</span></span>

- <span data-ttu-id="2bf7d-253">**Используйте лазерную указку и заметки от руки в PowerPoint Live в Teams.** Мы представляем виртуальную лазерную указку и заметки, чтобы выступающие могли эффективно демонстрировать содержимое и привлекать внимание аудитории к определенным разделам презентации PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-253">**Use laser pointer and ink annotations in PowerPoint Live in Teams:** We are introducing virtual laser pointer and annotations so presenters can effectively share content and engage their audience by drawing attention to certain sections of the PowerPoint deck.</span></span> <span data-ttu-id="2bf7d-254">По аналогии с физической лазерной указкой в комнате, PowerPoint Live позволяет эффективно указывать на разные места, чтобы зрители могли легко следить за тем, что происходит на слайде.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-254">Just as you would use a physical laser point in a room, PowerPoint Live allows you to effectively point at different places so the audience can easily follow along what’s on the slide.</span></span>

- <span data-ttu-id="2bf7d-255">**Рекомендации потоков Power Automate с использованием шаблонов команды 1P.** Ознакомьтесь с шаблонами потоков Power Automate для команд, созданных на основе шаблонов команды 1P</span><span class="sxs-lookup"><span data-stu-id="2bf7d-255">**Power Automate flow recommendations with 1P Team Templates:** Surface Power Automate flow templates for teams created from 1P team templates</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-258">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-258">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-259">Outlook</span></span>

- <span data-ttu-id="2bf7d-260">Исправлена проблема, из-за которой параметр обратной связи не отображался для пользователей предварительной версии Office Perpetual 2021.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-260">We fixed an issue that caused the feedback option unable to appear for users of the Office Perpetual 2021 preview.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-may-12"></a><span data-ttu-id="2bf7d-262">Версия 2105: от 12 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-262">Version 2105: May 12</span></span>
<span data-ttu-id="2bf7d-263">*Версия 2105 (сборка 14026.20164)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-263">*Version 2105 (Build 14026.20164)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-265">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-265">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-266">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-266">Teams</span></span>

- <span data-ttu-id="2bf7d-267">**Параметр пользователя для открытия файлов по умолчанию на рабочем столе (или) в браузере (или) в Teams:** пользователи могут установить свои предпочтения по умолчанию на значение "Браузер", "Рабочий стол" или "Teams" при открытии файлов Office (Word, Excel и Power Point), к которым предоставлен общий доступ в Teams. Параметр "Рабочий стол" можно выбрать, если установлены и активированы последние версии клиентов Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-267">**User preference setting to open files by default in Desktop (or) Browser (or) Teams:** Users can set their default preference as Browser, Desktop or Teams when opening Office (Word, Excel, and Power Point) files that are shared in Teams.Desktop setting can be selected if latest Office clients are installed and activated</span></span>

- <span data-ttu-id="2bf7d-268">**Телерепортер и режим "Рядом" в собраниях Teams:** теперь вы можете отображаться рядом с вашим содержимым для более привлекательного представления и использования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-268">**Reporter and Side-by-Side Mode in Teams meetings:** You can now appear next to your content for a more engaging presentation and consumption experience</span></span>

- <span data-ttu-id="2bf7d-269">**Общедоступность возможностей вебинаров Teams:** планируйте и проводите вебинары на 1000 человек с помощью того же приложения Teams, которое вы используете для собраний!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-269">**Teams webinar capabilities general availability:** Schedule and deliver 1,000 person webinars with the same Teams app you use for meetings!</span></span> <span data-ttu-id="2bf7d-270">Возможности вебинара поддерживают создание страницы регистрации, подтверждение по электронной почте для регистрантов, управление хостом для видео- и аудиоучастников, отчеты об участниках, а также интерактивные возможности, такие как опросы, чат и реакции.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-270">Webinar capabilities support registration page creation, email confirmation for registrants, host management for attendee video and audio, attendee reporting, plus interactive features like polls, chat and reactions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-273">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-273">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="2bf7d-274">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-274">Word</span></span>

- <span data-ttu-id="2bf7d-275">Устранена проблема, из-за которой контекстные карточки холста для орфографии и грамматики отображали кнопки значков, но эти кнопки не имели всплывающих подсказок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-275">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-may-07"></a><span data-ttu-id="2bf7d-277">Версия 2105: 7 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-277">Version 2105: May 07</span></span>
<span data-ttu-id="2bf7d-278">*Версия 2105 (сборка 14026.20138)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-278">*Version 2105 (Build 14026.20138)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-280">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-280">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-281">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-281">Teams</span></span>

- <span data-ttu-id="2bf7d-282">**Представляем макеты для собраний Teams.** Теперь вы можете отображаться поверх содержимого для более захватывающего представления и использования</span><span class="sxs-lookup"><span data-stu-id="2bf7d-282">**Introducing layouts to Teams meetings:** Now you can appear overlaid ontop of content for a more immersive presentation and consumption experience</span></span>

- <span data-ttu-id="2bf7d-283">**Отключение камеры для определенных участников.** Организаторы и участники собрания могут отключать камеры определенных участников на собрании Teams, чтобы убедиться, что они не деляться видео на собрании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-283">**Disable Camera for Specific Attendees:** Meeting Organizers and Presenters can disable the cameras of specific Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="2bf7d-284">**Отключение камеры для всех участников.** Организаторы и участники собрания могут отключать камеры всех участников на собрании Teams, чтобы убедиться, что они не деляться видео на собрании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-284">**Disable Camera for All Attendees:** Meeting Organizers and Presenters can disable the cameras of all Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="2bf7d-285">**Анонимные пользователи могут участвовать в трансляциях.** Во время трансляций Teams была добавлена возможность для анонимных пользователей присоединиться к трансляции, чтобы они также могли присутствовать во время события.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-285">**Anonymous users can present:** When hosting a Teams live event, we added the ability for an anonymous users to join a Live Event and so that they can also present during the event.</span></span>

- <span data-ttu-id="2bf7d-286">**Управление тегами в Teams программным путем. API тегов Microsoft Teams теперь находятся в общедоступной предварительной версии.** Этот набор API можно использовать для программного назначения тегов пользователей в команде, что ускоряет и упрощает создание и обслуживание тегов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-286">**Manage tags in Teams programmatically - Microsoft Teams Tags APIs are now in public preview:** This set of APIs can be used to programmatically assign users tags in a team, making tag creation and maintenance faster and easier.</span></span>  <span data-ttu-id="2bf7d-287">Теги в Teams позволяют пользователям быстро связаться с группой людей без необходимости @упоминания или ввода всех.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-287">Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.</span></span> <span data-ttu-id="2bf7d-288">Дополнительные сведения о тегах в Teams см. в разделе "Использование тегов в Teams".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-288">For more information on tag in teams, see Using tags in Teams.</span></span> <span data-ttu-id="2bf7d-289">С помощью этих новых API разработчики теперь могут соединять теги в команде и назначать usersGet список тегов в тегах обновления группы TagsDelete</span><span class="sxs-lookup"><span data-stu-id="2bf7d-289">Using these new APIs, developers can nowCreate tags in a team and assign usersGet a list of tags in a team Update tagsDelete tags</span></span>

- <span data-ttu-id="2bf7d-290">**Проведение презентаций из PowerPoint в Teams:** демонстрируйте слайды непосредственно из приложения PowerPoint на собрание Teams с помощью PowerPoint Live.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-290">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-293">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-293">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="2bf7d-294">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-294">Word</span></span>

- <span data-ttu-id="2bf7d-295">Исправлена проблема, из-за которой не открывается область редактора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-295">Fixes an issue where the Editor Pane doesn't open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-296">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-296">Office Suite</span></span>

- <span data-ttu-id="2bf7d-297">RelNotesNotNeeded</span><span class="sxs-lookup"><span data-stu-id="2bf7d-297">RelNotesNotNeeded</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-may-03"></a><span data-ttu-id="2bf7d-299">Версия 2105: 3 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-299">Version 2105: May 03</span></span>
<span data-ttu-id="2bf7d-300">*Версия 2105 (сборка 14026.20052)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-300">*Version 2105 (Build 14026.20052)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-302">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-302">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-303">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-303">Teams</span></span>

- <span data-ttu-id="2bf7d-304">**Одновременно несколько важных участников на собрании:** организаторы и выступающие могут отметить сразу нескольких участников в качестве важных во время собраний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-304">**Spotlight multiple users at the same time in a meeting:** Organizers and presenters can now spotlight multiple participants simultaneously during meetings.</span></span> <span data-ttu-id="2bf7d-305">Эти важные участники со своими видео или аватарами будут отображаться на сцене собрания для всех пользователей собрания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-305">The meeting stage will show these spotlighted participants, with their videos or avatars, to everyone in the meeting.</span></span>

- <span data-ttu-id="2bf7d-306">**Проведение презентаций из PowerPoint в Teams:** демонстрируйте слайды непосредственно из приложения PowerPoint на собрание Teams с помощью PowerPoint Live.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-306">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>

- <span data-ttu-id="2bf7d-307">**Новые возможности управления тегами и другие усовершенствования:** с помощью тегов в Teams пользователи могут быстро обращаться к группе пользователей без необходимости @упоминать каждого из них. Возможности по управлению теперь объединены на вкладке. Кроме того, теги теперь снабжены полем описания, поэтому в каждый тег можно добавить больше информации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-307">**New manage tag experience and other enhancements:** Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.The manage tags experience is now a Tab. Tags also now have a description field so that you can add more details to a tag.</span></span> <span data-ttu-id="2bf7d-308">Новая вкладка "Теги" станет целевой страницей для уведомлений и поиска тегов: эти функции будут реализованы в ближайшее время.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-308">The new Tags Tab will be the landing page for tag notifications and search for tags, which is also coming soon.</span></span>

- <span data-ttu-id="2bf7d-309">**Интеллектуальные динамики:** — интеллектуальные динамики — это интеллектуальные периферийные устройства для Комнат Microsoft Teams в Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-309">**Intelligent Speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="2bf7d-310">Эти устройства отображают для участников, находящихся в комнате собрания, транскрипцию собрания с указанием выступающих, поэтому участники смогут тратить меньше времени на запись заметок и смогут легче отслеживать, кто что сказал.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-310">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="2bf7d-311">**Использование режима "Собственные уведомления" по умолчанию вместо Teams Purple для новых пользователей:** режим "Собственные уведомления" обладает множеством преимуществ, включая поддержку центра уведомлений, поддержку режима фокусировки внимания и т. п. В настоящее время по умолчанию для новых пользователей Microsoft Teams используется стиль уведомлений Teams Purple.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-311">**Changing default to native notification from teams purple for new users:** Native Notifications provide a host of benefits like support for action center, accessibility, support for focus assist mode e.t.c.Currently the default notification style for a new user in Microsoft teams is Teams Purple.</span></span> <span data-ttu-id="2bf7d-312">После этого изменения для новых пользователей будет по умолчанию использоваться режим "Собственные уведомления".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-312">With this change the default for new user will change to Native Notification.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-315">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-315">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-316">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-316">Excel</span></span>

- <span data-ttu-id="2bf7d-317">Исправлена проблема, вызывавшая неожиданное закрытие Excel при использовании 32-разрядной версии Office в 64-разрядной версии Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-317">We fixed an issue that caused Excel to close unexpectedly when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="2bf7d-318">Исправлена проблема, вызывавшая неожиданное закрытие Excel при перемещении по комментариям в области "Комментарии".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-318">We fixed an issue that caused Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="2bf7d-319">Исправлена проблема, из-за которой не загружались некоторые надстройки автоматизации Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-319">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="2bf7d-320">Исправлена проблема, из-за которой экранный диктор неправильно читал свойства двух кнопок на вкладке "Колонтитулы" диалогового окна "Параметры страницы".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-320">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


- <span data-ttu-id="2bf7d-321">Исправлена проблема, из-за которую некоторые книги, связанные с другими приложениями Office, закрывались без сохранения изменений при запуске обновления ссылок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-321">We fixed an issue that caused some workbooks linked in other Office applications to close without saving changes when running Update Link.</span></span>


- <span data-ttu-id="2bf7d-322">Исправлена проблема, из-за которой надстройка "Пакет анализа" не работала у некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-322">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="2bf7d-323">Исправлена проблема, из-за которой некоторые файлы иногда не открывались в защищенном просмотре</span><span class="sxs-lookup"><span data-stu-id="2bf7d-323">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


- <span data-ttu-id="2bf7d-324">Исправлена проблема, из-за которой форматирование даты отображалось неправильно на некоторых языках при использовании надстроек.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-324">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="2bf7d-325">Исправлена проблема, из-за которой в строке состояния не указывалось состояние готовности для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-325">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


- <span data-ttu-id="2bf7d-326">Мы внесли изменения, чтобы диспетчер имен открывался в книгах с большим количеством скрытых имен.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-326">We made a change to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="2bf7d-p115">Исправлена проблема, приводившая к тому, что файлы, сохраненные в более поздней версии Excel, неправильно загружались в более ранних версиях Excel из-за таких функций как ЕСЛИОШИБКА и ПРОСМОТРX, добавленных в Excel начиная с версии Office 2007.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p115">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel failed to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="2bf7d-329">Исправлена проблема, которая в определенных ситуациях могла привести к неожиданному закрытию Excel при использовании специальной вставки с форматами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-329">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-330">Outlook</span></span>

- <span data-ttu-id="2bf7d-331">Исправлена проблема, из-за которой Outlook переопределял настройки сортировки почты, заданные в OWA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-331">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="2bf7d-332">Исправлена проблема, из-за которой пользователи перемещаемых профилей испытывали задержки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-332">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


- <span data-ttu-id="2bf7d-333">Исправлена проблема, вызывавшая отключение разрешения имен при отправке от имени другого пользователя и разрешении в адресной книге, не входящей в общую адресную книгу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-333">We fixed an issue that caused name resolution disabled when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="2bf7d-334">Исправлена проблема, из-за которой у некоторых пользователей улучшенной функции общего доступа к календарю возникали проблемы при взаимодействии со своим календарем в области навигации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-334">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="2bf7d-335">Исправлена проблема, из-за которой при использовании режима высокой контрастности в течение продолжительного периода времени приложение Outlook неожиданно закрывалось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-335">We fixed an issue where using High Contrast mode for extended periods of time would caused Outlook to close unexpectedly.</span></span>


- <span data-ttu-id="2bf7d-336">Исправлена проблема, из-за которой гиперссылки, включая цифры, прерывались при составлении сообщения в Outlook на языке с написанием справа налево.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-336">We fixed an issue where hyperlinks including digits would be disable when composing a message in Outlook in a right-to-left language.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-337">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-337">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-338">Исправлена проблема со связанным рисунками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-338">Fixes an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-339">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-339">Project</span></span>

- <span data-ttu-id="2bf7d-340">Исправлена проблема, из-за которой изменения, внесенные с помощью мастеров планирования, не всегда регистрировались событиями изменений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-340">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="2bf7d-341">Исправлена проблема, из-за которой пользователи не могли удалять проекты из пула ресурсов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-341">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-342">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-342">Visio</span></span>

- <span data-ttu-id="2bf7d-343">Исправлена проблема, приводившая к неожиданному закрытию Visio последней сборки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-343">We fixed an issue which caused Visio closed unexpectedly with recent build.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-344">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-344">Word</span></span>

- <span data-ttu-id="2bf7d-345">Исправлена проблема, из-за которой форматирование текста остается прежним после удаления гиперссылки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-345">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="2bf7d-346">Исправлена проблема, из-за которой замещающий текст обрезался в примечаниях при использовании языков с написанием справа налево.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-346">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


- <span data-ttu-id="2bf7d-347">Исправлена проблема, из-за которой комментарии не отображались после фильтрации по людям.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-347">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="2bf7d-348">Исправлена проблема, из-за которой Word не удавалось выполнить слияние почты с базой данных Access.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-348">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="2bf7d-349">Исправлена проблема, которая позволяла свернуть поля в документе, содержащем несколько столбцов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-349">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="2bf7d-350">Исправлена проблема, вызывавшая неправильное изображение некоторых символов в ячейках таблицы при наличии в документе комментариев.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-350">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="2bf7d-351">Исправлена проблема, из-за которой формат файла менялся при сохранении документов с включенной надстройкой AIP.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-351">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="2bf7d-352">Исправлена проблема, из-за которой Word зависал при попытке редактировать поля.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-352">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="2bf7d-353">Исправлена проблема, из-за которой метка конфиденциальности исчезала из файла в Word после отправки файла в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-353">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


- <span data-ttu-id="2bf7d-354">Исправлена проблема, из-за которой пользователям не предлагалось сохранять документы с помощью команды (а не сочетания клавиш CTRL+S).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-354">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="2bf7d-355">Исправлена проблема, из-за которой приложение Word могло неожиданно закрываться при завершении работы в связи с выходом пользователя из системы или перезапуском компьютера.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-355">Fixes an issue that may caused Word unexpectedly closed when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="2bf7d-356">Исправлена проблема, из-за которой форматирование текста остается прежним после удаления гиперссылок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-356">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-357">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-357">Office Suite</span></span>

- <span data-ttu-id="2bf7d-358">Исправлена проблема, из-за которой кнопка диктовки приобретала неправильное выравнивание при добавлении комментариев в документ.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-358">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="2bf7d-359">Исправлена проблема при обработке строки эмодзи, приводившая к неожиданному закрытию приложения при чтении вне границ массива.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-359">Fixed an issue when parsing a string for emoji processing that casued application closed unexpectedly when reading outside of the bounds of an array</span></span>


- <span data-ttu-id="2bf7d-360">Исправлена проблема, из-за которой элементы SVG отображались неправильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-360">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-april-28"></a><span data-ttu-id="2bf7d-362">Версия 2104: 28 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-362">Version 2104: April 28</span></span>
<span data-ttu-id="2bf7d-363">*Версия 2104 (сборка 13929.20296)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-363">*Version 2104 (Build 13929.20296)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-365">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-365">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-366">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-366">Teams</span></span>

- <span data-ttu-id="2bf7d-367">**Средство расширенного выбора эмодзи.** Обновление для расширения выбора эмодзи позволяет более интересно проводить время и выражать свои чувства в Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-367">**Expanded Emoji Picker:** The expanded emoji update offers people more fun and expressiveness in Teams.</span></span> <span data-ttu-id="2bf7d-368">Кроме того, это средство выбора предоставляет более широкую диверсификацию и мультикультурность.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-368">It also introduces a wider range of diversity and representation.</span></span> <span data-ttu-id="2bf7d-369">Набор, ранее содержавший 85 эмодзи, теперь содержит более 800 эмодзи со средствами выбора категорий, цвета кожи и короткого кода.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-369">The emoji set has expanded from 85 to over 800 emojis, with a category selector, skin tone selector and shortcode picker.</span></span>

- <span data-ttu-id="2bf7d-370">**Microsoft Teams: изменен интерфейс предоставления общего доступа во время собрания**. Пользовательский интерфейс функции "Поделиться" в Microsoft Teams был изменен, чтобы упростить и ускорить поиск нужного содержимого для ведущего презентацию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-370">**Microsoft Teams: Revised in-meeting Share experience:** The user interface for the in-meeting Share feature in Microsoft Teams has been redesigned to help presenters find their desired content more quickly and easily.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-373">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-373">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-374">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-374">Excel</span></span>

- <span data-ttu-id="2bf7d-375">Исправлена проблема, из-за которой не загружались некоторые надстройки автоматизации Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-375">Fixed a problem where some automation add-ins for Excel failed to load.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-376">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-376">Outlook</span></span>

- <span data-ttu-id="2bf7d-377">Исправлена проблема, из-за которой пользователи перемещаемых профилей испытывали задержку ответа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-377">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-378">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-378">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-379">Исправлена проблема со связанным рисунками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-379">We fixed an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-380">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-380">Project</span></span>

- <span data-ttu-id="2bf7d-381">Исправлена проблема, из-за которой пользователи не могли удалить проекты из пула ресурсов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-381">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-382">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-382">Word</span></span>

- <span data-ttu-id="2bf7d-383">Внесены изменения в редактирование объекта OLE.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-383">We made a change on editing OLE object.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-april-26"></a><span data-ttu-id="2bf7d-385">Версия 2104: 26 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-385">Version 2104: April 26</span></span>
<span data-ttu-id="2bf7d-386">*Версия 2104 (сборка 13929.20254)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-386">*Version 2104 (Build 13929.20254)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-388">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-388">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-389">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-389">Outlook</span></span>

- <span data-ttu-id="2bf7d-390">**Включение улучшений общего календаря.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-390">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="2bf7d-391">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-391">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-394">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-394">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-395">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-395">Excel</span></span>

- <span data-ttu-id="2bf7d-396">Исправлена проблема, из-за которой некоторые файлы иногда не открывались в защищенном просмотре</span><span class="sxs-lookup"><span data-stu-id="2bf7d-396">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-397">Outlook</span></span>

- <span data-ttu-id="2bf7d-398">Исправлена проблема, из-за которой Outlook переопределял настройки сортировки почты, заданные в OWA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-398">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-april-19"></a><span data-ttu-id="2bf7d-400">Версия 2104: 19 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-400">Version 2104: April 19</span></span>
<span data-ttu-id="2bf7d-401">*Версия 2104 (сборка 13929.20216)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-401">*Version 2104 (Build 13929.20216)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-403">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-403">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-404">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-404">Excel</span></span>

- <span data-ttu-id="2bf7d-405">**Импорт данных из динамических массивов.** Теперь вы можете импортировать, формировать и обновлять данные из динамических массивов в текущей книге.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-405">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="2bf7d-406">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-406">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a><span data-ttu-id="2bf7d-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-407">Outlook</span></span>

- <span data-ttu-id="2bf7d-408">**Улучшенный поиск в календаре.** Поиск в календаре улучшен. Главное новшество — более удобный переход на следующее вхождение ряда в результатах поиска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-408">**Improved Calendar Search:** Improvements have been made to Calendar search, largest of which is the ability to more easily find the next occurence of a series in search results.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-411">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-411">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-412">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-412">Access</span></span>

- <span data-ttu-id="2bf7d-413">Это изменение исправляет проблему, из-за которой в некоторых случаях при выполнении запроса к серверу SQL Server могло возникать сообщение об ошибке, указывающее на "недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-413">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


- <span data-ttu-id="2bf7d-414">Исправлена проблема, из-за которой невозможно было завершить работу до разблокировки указателя, когда внешнее приложение запрашивало интерфейс со специальными возможностями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-414">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-415">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-415">Excel</span></span>

- <span data-ttu-id="2bf7d-416">Исправлена проблема, не позволявшая вставлять формулы на защищенном листе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-416">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="2bf7d-417">Исправлена проблема, из-за которой гиперссылки, созданные с помощью функции ГИПЕРССЫЛКА, не работали, если файл был сохранен в формате PDF.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-417">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


- <span data-ttu-id="2bf7d-418">Исправлена проблема, из-за которой символ неявного оператора (@) добавлялся в формулу со ссылкой на пустой диапазон и мог давать неверный результат.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-418">We fixed an issue where an implicit operator (@) symbol would be added to the formula with a reference to an empty range and potentially give the incorrect result.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-419">Outlook</span></span>

- <span data-ttu-id="2bf7d-420">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при синхронизации изменений в иерархии папок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-420">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="2bf7d-421">Исправлена проблема, из-за которой пользователи ошибочно видели сообщение "Это может занять некоторое время" при добавлении календаря.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-421">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="2bf7d-422">Исправлена проблема, из-за которую делегаты отображались в качестве организаторов собраний, созданных во вновь добавленных календарях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-422">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="2bf7d-423">Собрания в этом состоянии не отображаются в календаре субъекта.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-423">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="2bf7d-424">Исправлена проблема, вызывавшая сбой при поиске.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-424">We fixed an issue that caused users to experience a crash when searching.</span></span>


- <span data-ttu-id="2bf7d-425">Исправлен сбой, связанный с поиском.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-425">We fixed a search related crash.</span></span>


- <span data-ttu-id="2bf7d-426">Исправлена проблема, из-за которой пользователи видели неожиданное исчезновение подписей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-426">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="2bf7d-427">Исправлена проблема, из-за которой в ходе составления сообщения пользователем оно могло терять фокус пользовательского интерфейса.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-427">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="2bf7d-428">Исправлена проблема, из-за которую Outlook переопределял настройку "Сортировка почты", заданную в OWA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-428">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="2bf7d-429">Исправлена проблема, из-за которой пользовательские параметры функции "Параметры облака" менялись на значения по умолчанию после настройки Outlook на новом устройстве.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-429">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="2bf7d-430">Исправлена проблема, из-за которой некоторые пользователи не могли получить доступ к подписям, связанным с дополнительными учетными записями почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-430">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="2bf7d-431">Исправлена проблема, вызывавшая сбой разрешения имен при отправке от имени другого пользователя и разрешении в адресной книге, не являющейся глобальным списком адресов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-431">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="2bf7d-432">Исправлена проблема, вызывавшая сбой разрешения имен при отправке от имени другого пользователя и разрешении в адресной книге, не являющейся глобальным списком адресов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-432">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-433">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-433">Project</span></span>

- <span data-ttu-id="2bf7d-434">Исправлена проблема, из-за которой при использовании формата даты W4/4 в средстве выбора даты мог отображаться неправильный день и год.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-434">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-435">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-435">Visio</span></span>

- <span data-ttu-id="2bf7d-436">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-436">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="2bf7d-437">Исправлена функция "Поиск фигуры" — теперь она показывает все результаты</span><span class="sxs-lookup"><span data-stu-id="2bf7d-437">Fixed "Search Shape" feature to display all the results</span></span>



### <a name="word"></a><span data-ttu-id="2bf7d-438">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-438">Word</span></span>

- <span data-ttu-id="2bf7d-p120">Из-за этой ошибки определенные политики не учитывались в Office (группа шаблонов отображалась на домашней странице, когда они должны были быть отключены).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p120">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="2bf7d-441">При совместной работе над документом активный черновик не очищается при смене порядка комментариев.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-441">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="2bf7d-442">Исправлена ошибка в современном комментировании, из-за которой знаки препинания и цифры для некоторых международных языков выводились не на той стороне.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-442">Fixed bug in Modern Commenting where punctuation and numbers would show up on the wrong side for some international languages.</span></span>


- <span data-ttu-id="2bf7d-443">Исправлена проблема, из-за которой сочетание "B" и ")" автоматически превращалось в эмодзи в черных очках; теперь это сочетание сохраняется как два отдельных символа</span><span class="sxs-lookup"><span data-stu-id="2bf7d-443">Fixed an issue where the combination of 'B' and ')' would automatically turn into the sunglass wearing emoji and now remain as the individual characters</span></span>


- <span data-ttu-id="2bf7d-444">Обновляет текст в выноске автосохранения для файлов, сохраненных локально.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-444">Updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="2bf7d-445">Исправлена проблема с комментариями во время совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-445">We fixed an issue with comments during coauthoring.</span></span>


- <span data-ttu-id="2bf7d-446">Исправлена проблема, связанная со значком комментария.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-446">We fixed an issue relating to comment icon.</span></span>


- <span data-ttu-id="2bf7d-447">Исправлена проблема, из-за которой при копировании и вставке стиль вставленного текста мог отличаться.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-447">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="2bf7d-448">Оптимизирует условия для предлагаемого прогнозируемого текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-448">Optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="2bf7d-449">Исправлена проблема, связанная с гиперссылками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-449">We fixed an issue relating to hyperlink.</span></span>


- <span data-ttu-id="2bf7d-450">Выделенный текст может быть не виден при использовании темной темы в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-450">Some select text not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="2bf7d-451">Исправлена проблема с автосохранением.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-451">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="2bf7d-452">Исправлена ошибка в методе Application.OnTime, из-за которой он мог запускаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-452">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-453">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-453">Office Suite</span></span>

- <span data-ttu-id="2bf7d-454">Исправлена проблема с производительностью, связанная с итерацией текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-454">Fixed a performance issue related to iteration of text.</span></span>


- <span data-ttu-id="2bf7d-455">Исправлена проблема с поддержкой GDI+ LineJoinMiterClipped в Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-455">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>


- <span data-ttu-id="2bf7d-456">В этом выпуске улучшена обработка конфиденциального содержимого, занимающего несколько строк, когда ключевое слово находится в первой строке документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-456">This release improves handling of line-spanning sensitive content when the keyword is on the first line of a document.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-april-13"></a><span data-ttu-id="2bf7d-458">Версия 2103: 13 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-458">Version 2103: April 13</span></span>
<span data-ttu-id="2bf7d-459">*Версия 2103 (сборка 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-459">*Version 2103 (Build 13901.20400)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-460">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-460">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-461">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-461">Teams</span></span>

- <span data-ttu-id="2bf7d-462">**Динамическое представление**. Динамическое представление автоматически оптимизирует общее содержимое и видео участников в собраниях Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-462">**Dynamic view** Dynamic view automatically optimizes shared content and video participants in Teams meetings.</span></span> <span data-ttu-id="2bf7d-463">Новые элементы управления позволяют персонализировать представление в соответствии со своими потребностями. Например, можно рядом отображать общее содержимое и определенных участников.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-463">New controls let you personalize the view to suit your preferences and needs, such as the ability to show shared content and specific participants side-by-side.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-april-10"></a><span data-ttu-id="2bf7d-465">Версия 2103: 10 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-465">Version 2103: April 10</span></span>
<span data-ttu-id="2bf7d-466">*Версия 2103 (сборка 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-466">*Version 2103 (Build 13901.20400)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-468">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-469">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-469">Excel</span></span>

- <span data-ttu-id="2bf7d-470">Исправлена потенциальная проблема нехватки ресурсов в Word при рисовании изображения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-470">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-471">Outlook</span></span>

- <span data-ttu-id="2bf7d-472">Исправлена проблема, из-за которой пользователи ошибочно видели сообщение "Это может занять некоторое время" при добавлении календаря.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-472">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>

- <span data-ttu-id="2bf7d-473">Исправлена проблема, из-за которую делегаты отображались в качестве организаторов собраний, созданных во вновь добавленных календарях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-473">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="2bf7d-474">Собрания в этом состоянии не отображаются в календаре субъекта.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-474">Meetings in this state did not appear on the principal's calendar.</span></span>

- <span data-ttu-id="2bf7d-475">Исправлена потенциальная проблема нехватки ресурсов в Word при рисовании изображения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-475">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-476">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-476">Powerpoint</span></span>

- <span data-ttu-id="2bf7d-477">Исправлена потенциальная проблема нехватки ресурсов в Word при рисовании изображения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-477">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-478">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-478">Word</span></span>

- <span data-ttu-id="2bf7d-479">Исправлена потенциальная проблема нехватки ресурсов в Word при рисовании изображения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-479">Fixed a potential resource contention issue in word when drawing an image.</span></span>

- <span data-ttu-id="2bf7d-480">Исправлена проблема с отсутствием ответа при предварительном просмотре.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-480">Fixed a non-responsive issue while in Print preview.</span></span>

- <span data-ttu-id="2bf7d-481">Обновляет текст в выноске автосохранения для файлов, сохраненных локально.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-481">Updates text on autosave callout for files saved locally.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-482">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-482">Office Suite</span></span>

- <span data-ttu-id="2bf7d-483">Исправлена ошибка переименования при открытии файла SyncBacked в автономном режиме, а затем переименовании файла в приложении перед сохранением файла.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-483">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-april-02"></a><span data-ttu-id="2bf7d-485">Версия 2103: 2 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-485">Version 2103: April 02</span></span>
<span data-ttu-id="2bf7d-486">*Версия 2103 (сборка 13901.20336)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-486">*Version 2103 (Build 13901.20336)*</span></span>
* <span data-ttu-id="2bf7d-487">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-487">Various bugs and performance fixes.</span></span>

## <a name="version-2103-april-1"></a><span data-ttu-id="2bf7d-488">Версия 2103: 1 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-488">Version 2103: April 1</span></span>
<span data-ttu-id="2bf7d-489">*Версия 2103 (сборка 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-489">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-490">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-490">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-491">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-491">Teams</span></span>

- <span data-ttu-id="2bf7d-492">**Формат даты и времени**. После этого обновления форматы даты и времени в Teams будут соответствовать региональным настройкам операционной системы Mac и Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-492">**Date/Time format** With this update, the date/time formats in Teams will match the Mac and Windows operating system regional settings.</span></span> <span data-ttu-id="2bf7d-493">Ранее в Teams формат даты и времени соответствовал региональной настройке приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-493">Previously, Teams would only show date/time in the format corresponding to the application's language.</span></span> <span data-ttu-id="2bf7d-494">Важно отметить, что поддерживается только григорианский календарь, независимо от настройки календаря операционной системы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-494">It's important to note that only the Gregorian calendar is supported regardless of the operating system's calendar setting.</span></span> 

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-30"></a><span data-ttu-id="2bf7d-496">Версия 2103: 30 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-496">Version 2103: March 30</span></span>
<span data-ttu-id="2bf7d-497">*Версия 2103 (сборка 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-497">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="2bf7d-498">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-498">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="2bf7d-499">Версия 2103: 28 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-499">Version 2103: March 28</span></span>
<span data-ttu-id="2bf7d-500">*Версия 2103 (сборка 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-500">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-502">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-502">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-503">Outlook</span></span>

- <span data-ttu-id="2bf7d-504">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при синхронизации изменений в иерархии папок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-504">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="2bf7d-505">Исправлена проблема, из-за которой у некоторых пользователей основной и дополнительный календари менялись местами в области навигации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-505">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-22"></a><span data-ttu-id="2bf7d-507">Версия 2103: 22 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-507">Version 2103: March 22</span></span>
<span data-ttu-id="2bf7d-508">*Версия 2103 (сборка 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-508">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-510">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-510">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-511">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-511">Outlook</span></span>

- <span data-ttu-id="2bf7d-512">Исправлена проблема, из-за которой пользователи видели больше подписей, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-512">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-15"></a><span data-ttu-id="2bf7d-514">Версия 2103: 15 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-514">Version 2103: March 15</span></span>
<span data-ttu-id="2bf7d-515">*Версия 2103 (сборка 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-515">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-517">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-517">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2bf7d-518">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-518">Project</span></span>

- <span data-ttu-id="2bf7d-519">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-519">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-520">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-520">Visio</span></span>

- <span data-ttu-id="2bf7d-521">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-521">Fixed an issue where Visio could stop working during close.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
## <a name="version-2103-march-11"></a><span data-ttu-id="2bf7d-524">Версия 2103: 11 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-524">Version 2103: March 11</span></span>
<span data-ttu-id="2bf7d-525">*Версия 2103 (сборка 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-525">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-526">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-526">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-527">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-527">Excel</span></span>

- <span data-ttu-id="2bf7d-528">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-528">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="2bf7d-529">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-529">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="2bf7d-530">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-530">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-531">Outlook</span></span>

- <span data-ttu-id="2bf7d-532">**Новые возможности резервирования конференц-залов и рабочей области:** обновлен процесс резервирования конференц-залов и добавлены возможности для планирования отдельных рабочих областей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-532">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-533">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-534">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-534">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="2bf7d-535">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-535">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="2bf7d-536">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-536">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="teams"></a><span data-ttu-id="2bf7d-537">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-537">Teams</span></span>

- <span data-ttu-id="2bf7d-538">**Статус “Нет на месте”** Оставьте уведомление, чтобы при отправке сообщений в чате другие знали, что вы недоступны или в отпуске и не сможете ответить.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-538">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="2bf7d-539">Ваш статус “Нет на месте” также синхронизируется с автоматическими ответами в календаре Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-539">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

### <a name="visio"></a><span data-ttu-id="2bf7d-540">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-540">Visio</span></span>

- <span data-ttu-id="2bf7d-541">**Новый дизайн значков Office:** дизайн значков продукта изменен, чтобы показать простой, функциональный и удобный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-541">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="2bf7d-542">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-542">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="2bf7d-543">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-543">Word</span></span>

- <span data-ttu-id="2bf7d-544">**Темный режим для документов Word:** темный режим помогает снизить нагрузку на глаза и учитывает светочувствительность при работе с документами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-544">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="2bf7d-545">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-545">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="2bf7d-546">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-546">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="2bf7d-547">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-547">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-550">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-550">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-551">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-551">Access</span></span>

- <span data-ttu-id="2bf7d-552">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-552">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2bf7d-553">Исправлена проблема, из-за которой невозможно было завершить работу до разблокировки указателя, когда внешнее приложение запрашивало интерфейс со специальными возможностями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-553">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-554">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-554">Excel</span></span>

- <span data-ttu-id="2bf7d-555">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-555">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2bf7d-556">Устранена проблема, из-за которой Excel иногда неожиданно закрывался при попытке показать карточку типов данных, поскольку не мог получить изображение.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-556">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="2bf7d-557">Исправлена проблема, из-за которой шрифт неожиданно менялся при использовании знака умножения или деления с японским шрифтом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-557">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="2bf7d-558">Теперь продолжится использование того же шрифта, если он поддерживает символ.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-558">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="2bf7d-559">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-559">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="2bf7d-560">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании функции "Вставить связанный рисунок".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-560">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="2bf7d-561">Исправлена проблема потери некоторого форматирования при копировании листа во время совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-561">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="2bf7d-562">Исправлена проблема, из-за которой неожиданно отображались некоторые заметки при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-562">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="2bf7d-563">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-563">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-564">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-564">Outlook</span></span>

- <span data-ttu-id="2bf7d-565">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-565">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2bf7d-566">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-566">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="2bf7d-567">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-567">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="2bf7d-568">Исправлена проблема, из-за которой новые календари не появлялись в области навигации, пока пользователь не перезапустит Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-568">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="2bf7d-569">Исправлена проблема, из-за которой символы, отличные от ASCII, некорректно экспортировались в CSV-файл.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-569">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="2bf7d-570">Исправлена проблема, из-за которой некоторые пользователи не могли получить доступ к подписям, связанным с дополнительными учетными записями почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-570">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="2bf7d-571">Исправлена проблема, из-за которой пользовательские параметры функции "Параметры облака" менялись на значения по умолчанию после настройки Outlook на новом устройстве.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-571">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="2bf7d-572">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-572">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="2bf7d-573">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-573">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="2bf7d-574">Исправлена проблема, из-за которой дублировались вложения при удалении защиты DRM.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-574">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="2bf7d-575">Исправлена проблема, из-за которой пользователи не могли найти группу контактов с помощью проверки имен при создании сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-575">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-576">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-576">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-577">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-577">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2bf7d-578">Исправлена проблема, из-за которой стрелки на графиках отображались неправильно в режиме слайд-шоу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-578">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="2bf7d-579">Устранена проблема с повторением анимаций и звуковыми закладками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-579">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-580">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-580">Project</span></span>

- <span data-ttu-id="2bf7d-581">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-581">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="2bf7d-582">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-582">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2bf7d-583">Устранена проблема, из-за которой задача, выполненная на 100%, могла вернуться к выполнению на 99%.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-583">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="2bf7d-584">Устранена проблема, из-за которой Project иногда неожиданно закрывался при запуске JAWS и переходе в диалоговое окно сведений о задаче.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-584">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="2bf7d-585">Исправлена проблема, из-за которой при вырезании суммарной задачи не появлялось предупреждение об удалении подзадач, если столбец индикатора отсутствовал в первом столбце.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-585">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="2bf7d-586">Исправлена проблема, из-за которой в создаваемом назначении могли применяться неправильные единицы доступности ресурса, если пользователь выбирал функцию "Добавление себя в задачу" в своем расписании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-586">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="2bf7d-587">Исправлена проблема, из-за которой при сохранении проекта из веб-приложения Project в локальный файл могли неправильно создаваться разбиения задач.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-587">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="2bf7d-588">Это могло происходить при использовании календаря задач с нестандартным рабочим временем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-588">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="2bf7d-589">Publisher</span><span class="sxs-lookup"><span data-stu-id="2bf7d-589">Publisher</span></span>

- <span data-ttu-id="2bf7d-590">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-590">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-591">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-591">Visio</span></span>

- <span data-ttu-id="2bf7d-592">Исправлена проблема, из-за которой приложение Visio могло прекратить работу во время закрытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-592">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="2bf7d-593">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-593">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-594">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-594">Word</span></span>

- <span data-ttu-id="2bf7d-595">Исправлена проблема, из-за которой открытие файла, защищенного с помощью метки Microsoft Information Protection (MIP), могло зависать на неопределенное время, если пользователь не вошел в систему с удостоверением, имеющим доступ к защищенной метке MIP.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-595">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="2bf7d-596">Открытие будет принудительно отменено, чтобы отобразить запрос на вход. Только после этого получится открыть файл.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-596">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="2bf7d-597">Устранение этой проблемы возможно путем отображения запроса на вход во время открытия или загрузки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-597">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="2bf7d-598">Исправлена проблема, приводившая к неожиданному закрытию приложения при отключении внешнего жесткого диска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-598">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2bf7d-599">Исправлена проблема при использовании диктофона в новой версии комментирования Word. Теперь кнопка диктофона правильно включается и отключается в карточке комментария.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-599">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="2bf7d-600">При совместной работе над документом активный черновик не очищается при смене порядка комментариев.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-600">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="2bf7d-601">Исправлена проблема, из-за которой при диктовке в документе между словами не вставлялись пробелы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-601">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="2bf7d-602">Исправлена проблема в конвейере отрисовки, связанная со слоями прокрутки, содержащими анимации прокрутки или масштабирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-602">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="2bf7d-603">Исправлена проблема с применением цветовой гаммы к значкам и изображениям SVG с трехмерными эффектами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-603">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="2bf7d-604">Исправлена проблема с автосохранением.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-604">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="2bf7d-605">Исправлена проблема со сносками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-605">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="2bf7d-606">Исправлена проблема при публикации многострочных комментариев, введенных справа налево, из-за которой вторая и последующие строки выравнивались по левому краю, а не по правому.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-606">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="2bf7d-607">Исправлена проблема с выравниванием нескольких комментариев.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-607">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="2bf7d-608">Исправлена проблема с сочетаниями клавиш области задач "Прочесть вслух".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-608">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="2bf7d-609">Исправлена проблема, из-за которой экранный диктор иногда пропускает абзац.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-609">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="2bf7d-610">Исправлена проблема, из-за которой проверка орфографии переключалась между двумя разными контекстными меню проверки орфографии.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-610">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="2bf7d-611">Исправлена проблема с элементами управления форматированным текстом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-611">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="2bf7d-612">Исправлена проблема, из-за которой набор текста в конце скрытого абзаца мог привести к зависанию приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-612">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="2bf7d-613">Исправлена проблема, из-за которой в столбцах мог быть перекрывающийся текст.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-613">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="2bf7d-614">Исправлена проблема, связанная с закладкой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-614">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="2bf7d-615">Исправлена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-615">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-616">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-616">Office Suite</span></span>

- <span data-ttu-id="2bf7d-617">Места в OneDrive теперь фильтруются в соответствии с настройками групповой политики.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-617">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="2bf7d-618">Исправлена проблема, которая возникала при использовании экранного диктора в тексте с математическими уравнениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-618">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="2bf7d-619">Исправлена проблема надежности, связанная с поддержкой приложений Office, работающих в сеансе 0.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-619">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="2bf7d-620">Исправлена проблема надежности, связанная с поддержкой приложений Office, работающих в сеансе 0.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-620">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="2bf7d-621">Исправлена проблема, связанная с отсутствием отклика при загрузке изображений EMF.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-621">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-03"></a><span data-ttu-id="2bf7d-623">Версия 2102: 3 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-623">Version 2102: March 03</span></span>
<span data-ttu-id="2bf7d-624">*Версия 2102 (сборка 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-624">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-626">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-626">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="2bf7d-627">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-627">Word</span></span>

- <span data-ttu-id="2bf7d-628">Исправлена проблема с информацией о теме, примененной к значкам и изображениям SVG.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-628">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-march-01"></a><span data-ttu-id="2bf7d-630">Версия 2102: 1 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-630">Version 2102: March 01</span></span>
<span data-ttu-id="2bf7d-631">*Версия 2102 (сборка 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-631">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-633">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-633">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-634">Outlook</span></span>

- <span data-ttu-id="2bf7d-635">**Поделиться в Teams.** Поделитесь сообщениями из Outlook с пользователем или каналом в Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-635">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-638">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-638">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-639">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-639">Outlook</span></span>

- <span data-ttu-id="2bf7d-640">Исправлена и устранена проблема, из-за которой пользователи видели повторяющиеся группы календаря, отображающиеся после создания новой группы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-640">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="2bf7d-641">Исправлена проблема, из-за которой пользователи улучшений общего календаря не могли установить для него желтый или коричневый цвет.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-641">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="2bf7d-642">Исправлена проблема, из-за которой у некоторых пользователей закрывалось приложение при закрытии окон сообщений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-642">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="2bf7d-643">Исправлена проблема, из-за которой пользователи видели, что подписи с содержимым Юникода, были повреждены.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-643">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="2bf7d-644">Исправлена проблема, из-за которой пользователи машинного перевода не могли отправить отзыв.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-644">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-february-21"></a><span data-ttu-id="2bf7d-646">Версия 2102: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-646">Version 2102: February 21</span></span>
<span data-ttu-id="2bf7d-647">*Версия 2102 (сборка 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-647">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-649">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-649">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-650">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-650">Outlook</span></span>

- <span data-ttu-id="2bf7d-651">**Создать сообщения с помощью голоса.** Используйте новую панель инструментов для диктовки, голосовые команды, автоматическую пунктуацию и многое другое для создания сообщений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-651">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-652">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-652">Word</span></span>

- <span data-ttu-id="2bf7d-653">**Создать документ с помощью голоса.** Используйте новую панель инструментов для диктовки, голосовые команды и автоматическую пунктуацию для создания документов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-653">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-656">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-656">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-657">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-657">Excel</span></span>

- <span data-ttu-id="2bf7d-658">Исправлена проблема, из-за которой изображение было меньше, чем ожидалось, при использовании параметра "Вставка связанного рисунка".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-658">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-february-16"></a><span data-ttu-id="2bf7d-660">Версия 2102: 16 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-660">Version 2102: February 16</span></span>
<span data-ttu-id="2bf7d-661">*Версия 2102 (сборка 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-661">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="2bf7d-662">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-662">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="2bf7d-663">Версия 2102: 15 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-663">Version 2102: February 15</span></span>
<span data-ttu-id="2bf7d-664">*Версия 2102 (сборка 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-664">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-666">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-666">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-667">Outlook</span></span>

- <span data-ttu-id="2bf7d-668">**Диктовка доступна на большем количестве языков.** Теперь диктовка поддерживает семь новых языков: хинди, русский, польский, португальский (Португалия), корейский, тайский и китайский (Тайвань).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-668">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-669">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-669">Word</span></span>

- <span data-ttu-id="2bf7d-670">**Диктовка доступна на большем количестве языков.** Теперь диктовка поддерживает семь новых языков: хинди, русский, польский, португальский (Португалия), корейский, тайский и китайский (Тайвань).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-670">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-673">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-673">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-674">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-674">Excel</span></span>

- <span data-ttu-id="2bf7d-675">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-675">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-676">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-676">Word</span></span>

- <span data-ttu-id="2bf7d-677">Устранена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-677">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2102-february-11"></a><span data-ttu-id="2bf7d-679">Версия 2102: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-679">Version 2102: February 11</span></span>
<span data-ttu-id="2bf7d-680">*Версия 2102 (сборка 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-680">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-682">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-682">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-683">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-683">Teams</span></span>

- <span data-ttu-id="2bf7d-684">**Видео 2x2 в браузерах Microsoft Edge и Chrome для Windows и Mac** Пользователи могут видеть до 4 участников на видео-собраниях Teams в браузерах Microsoft Edge и Chrome для Windows и Mac.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-684">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="2bf7d-685">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-685">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="2bf7d-687">Версия 2102: 8 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-687">Version 2102: February 08</span></span>
<span data-ttu-id="2bf7d-688">*Версия 2102 (сборка 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-688">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-690">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-690">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-691">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-691">Outlook</span></span>

- <span data-ttu-id="2bf7d-692">**Создание предложений (Кому\Копия\СК) на основе Поиска (Майкрософт):** добавление пользователей в строку "Кому"\"Копия" теперь выполняется на платформе Поиска (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-692">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-695">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-695">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-696">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-696">Access</span></span>

- <span data-ttu-id="2bf7d-697">Теперь выбранные вкладки будут отображаться четче в Access.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-697">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-698">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-698">Excel</span></span>

- <span data-ttu-id="2bf7d-699">Исправляет проблемы, при которых определенные диаграммы, в которых используются несмежные диапазоны ячеек, не будут загружаться при повторном открытии файлов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-699">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="2bf7d-700">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-700">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="2bf7d-701">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-701">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="2bf7d-702">Исправлена проблема, из-за которой приложение Excel неожиданно завершало работу при добавлении имени в диалоговом окне "Присвоение имени".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-702">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="2bf7d-703">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-703">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-704">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-704">Outlook</span></span>

- <span data-ttu-id="2bf7d-705">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-705">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="2bf7d-706">Исправлена проблема, из-за которой значок шифрования не отображался для сообщений, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-706">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-707">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-708">Исправлена проблема, связанная с отображением эмодзи в цвете.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-708">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="2bf7d-709">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-709">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-710">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-710">Visio</span></span>

- <span data-ttu-id="2bf7d-711">Эта проблема с отрисовкой фигур из наборов элементов САПР исправлена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-711">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="2bf7d-712">Проблема устранена для пользователей в последней сборке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-712">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-713">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-713">Word</span></span>

- <span data-ttu-id="2bf7d-714">Это исправление проблемы, из-за которой был невозможен ввод в режиме реального времени и восстановление присутствия после потери подключения к Интернету в течение определенного периода времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-714">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="2bf7d-715">Когда пользователь выбирает текст в примечании, Word теперь отменяет выделение текста в других примечаниях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-715">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="2bf7d-716">Теперь Word позволяет копировать текст примечаний в Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-716">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="2bf7d-717">Исправлена проблема, из-за которой возникал сбой при запуске макроса VBA ExportAsFixedFormat2 с ошибкой "Недопустимое значение презентации (неизвестный участник)".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-717">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="2bf7d-718">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-718">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="2bf7d-719">Устранена проблема, из-за которой примечание может быть обрезано с ссылками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-719">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="2bf7d-720">Устранена проблема с сохранением в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-720">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="2bf7d-721">Устранена проблема с экспортом документов Word в PDF.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-721">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="2bf7d-722">Исправлена проблема с автовосстановлением.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-722">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="2bf7d-723">Исправлена проблема с совместным редактированием файлов, защищенных с помощью DRM</span><span class="sxs-lookup"><span data-stu-id="2bf7d-723">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-724">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-724">Office Suite</span></span>

- <span data-ttu-id="2bf7d-725">Исправлена ошибка в PowerPoint, из-за которой вставка маркеров в виде изображений приводила к исчезновению маркеров.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-725">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="2bf7d-726">Это исправление повышает надежность их отрисовки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-726">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="2bf7d-727">Устранена проблема, из-за которой в некоторых случаях в Office отображались метки конфиденциальности для одной учетной записи, в которую был выполнен вход, тогда как нужно было для другой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-727">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-february-03"></a><span data-ttu-id="2bf7d-729">Версия 2101: 3 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-729">Version 2101: February 03</span></span>
<span data-ttu-id="2bf7d-730">*Версия 2101 (сборка 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-730">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-732">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-732">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-733">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-733">Outlook</span></span>

- <span data-ttu-id="2bf7d-734">Исправлена проблема, из-за которой возникали проблемы с отображением правильной подписи по умолчанию в OWA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-734">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="2bf7d-735">Исправлена проблема, из-за которой значок шифрования не отображался в сообщениях, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-735">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-february-02"></a><span data-ttu-id="2bf7d-737">Версия 2101: 2 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-737">Version 2101: February 02</span></span>
<span data-ttu-id="2bf7d-738">*Версия 2101 (сборка 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-738">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-740">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-741">Outlook</span></span>

- <span data-ttu-id="2bf7d-742">Исправлена проблема, приводившая к зависанию у пользователей облачных параметров при обновлении настроек.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-742">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-25"></a><span data-ttu-id="2bf7d-744">Версия 2101: 25 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-744">Version 2101: January 25</span></span>
<span data-ttu-id="2bf7d-745">*Версия 2101 (сборка 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-745">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-747">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-747">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-748">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-748">Excel</span></span>

- <span data-ttu-id="2bf7d-749">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-749">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="2bf7d-750">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-750">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="2bf7d-751">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-751">Outlook</span></span>

- <span data-ttu-id="2bf7d-752">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-752">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="2bf7d-753">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-753">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-754">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-754">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-755">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-755">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="2bf7d-756">[Подробнее](/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-756">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-757">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-757">Word</span></span>

- <span data-ttu-id="2bf7d-758">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-758">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="2bf7d-759">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-759">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-760">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-760">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-761">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-761">Outlook</span></span>

- <span data-ttu-id="2bf7d-762">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-762">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



## <a name="version-2101-january-18"></a><span data-ttu-id="2bf7d-764">Версия 2101: 18 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-764">Version 2101: January 18</span></span>
<span data-ttu-id="2bf7d-765">*Версия 2101 (сборка 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-765">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-769">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-769">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2bf7d-770">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-770">Project</span></span>

- <span data-ttu-id="2bf7d-771">Исправлена проблема, из-за которой границы не отображались для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-771">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="2bf7d-772">Исправлена проблема, из-за которой не работало перетаскивание для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-772">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-13"></a><span data-ttu-id="2bf7d-774">Версия 2101: 13 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-774">Version 2101: January 13</span></span>
<span data-ttu-id="2bf7d-775">*Версия 2101 (сборка 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-775">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
### <a name="feature-updates"></a><span data-ttu-id="2bf7d-777">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-777">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2bf7d-778">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-778">Teams</span></span>
- <span data-ttu-id="2bf7d-779">**Дополнительные темы**. Новые темы теперь доступны для классических и веб-клиентов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-779">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="2bf7d-780">**Общий доступ в PPT**. Режим докладчика в Teams. После выбора файла PowerPoint на панели общего доступа Teams автоматически открывается режим докладчика.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-780">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="2bf7d-781">Вы увидите текущий слайд, заметки к слайду и ряд эскизов всех слайдов в колоде для удобной навигации по слайдам.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-781">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="2bf7d-782">Этот режим работает в фоновом режиме, является личным под управлением выступающего.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-782">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="2bf7d-783">Аудитория может только просматривать текущий слайд (выделенный в красном квадратике) или слайд, к которому они будут переходить (если навигация аудитории не заблокирована).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-783">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="2bf7d-784">**Включить звук компьютера при демонстрации рабочего стола или окна на компьютере Mac** Когда вы демонстрируете рабочий стол или окно в Teams для Mac, теперь можно включить звук компьютера, чтобы люди, присоединившись к собранию, могли слышать звук из вашего компьютера.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-784">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="2bf7d-786">Версия 2101: 9 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-786">Version 2101: January 09</span></span>
<span data-ttu-id="2bf7d-787">*Версия 2101 (сборка 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-787">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-789">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-789">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-790">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-790">Outlook</span></span>

- <span data-ttu-id="2bf7d-791">**Быстрые рекомендации по стилю.** Применяйте рекомендации литературной правки одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-791">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="2bf7d-792">Корректор исправляет правописание и предлагает идеи по уточнению текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-792">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="2bf7d-793">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-793">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="2bf7d-794">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/microsoft-editor-gets-an-upgrade)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-794">See details in [blog post](https://insider.office.com/ru-RU/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-797">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-797">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-798">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-798">Outlook</span></span>

- <span data-ttu-id="2bf7d-799">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось в определенных сценариях поиска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-799">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-07"></a><span data-ttu-id="2bf7d-801">Версия 2101: 7 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-801">Version 2101: January 07</span></span>
<span data-ttu-id="2bf7d-802">*Версия 2101 (сборка 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-802">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-804">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-804">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-805">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-805">Excel</span></span>

- <span data-ttu-id="2bf7d-806">**Отображение нескольких листов одновременно.** Больше не нужно отображать листы по одному. Отображайте несколько скрытых листов одновременно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-806">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="2bf7d-807">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-807">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="2bf7d-808">**Улучшенные диалоговые окна условного форматирования.** Теперь размеры диалоговых окон условного форматирования можно изменять, и вы можете дублировать правило одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-808">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="2bf7d-809">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-809">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-812">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-812">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-813">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-813">Excel</span></span>

- <span data-ttu-id="2bf7d-814">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-814">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="2bf7d-815">Исправлена проблема с переключением разделителей после вызова Selection.Parent.Copy.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-815">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="2bf7d-816">Улучшена производительность при применении стилей форматирования для сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-816">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="2bf7d-817">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-817">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="2bf7d-818">Обновление, чтобы обеспечить перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-818">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="2bf7d-819">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-819">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="2bf7d-820">Исправлена проблема, которая приводит к появлению предупреждения о нехватке ресурсов при использовании функции "ИСТОРИЯАКЦИЙ".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-820">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="2bf7d-821">Добавлена библиотека DLL FuzzyClustering в список библиотек DLL PQ.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-821">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="2bf7d-822">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-822">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="2bf7d-823">Исправлена проблема, из-за которой предварительный просмотр внедренного диапазона Excel в PowerPoint показывает неверный размер.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-823">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="2bf7d-824">OneNote</span><span class="sxs-lookup"><span data-stu-id="2bf7d-824">OneNote</span></span>

- <span data-ttu-id="2bf7d-825">Это исправление устраняет проблему отрисовки, влияющую на OneNote.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-825">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-826">Outlook</span></span>

- <span data-ttu-id="2bf7d-827">Исправлена проблема, из-за которой пользователи не могли указать, на какой срок нужно разрешить доступ при начале слияния из Word, что приводило к получению избыточных запросов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-827">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="2bf7d-828">Это изменение позволяет Outlook использовать параметр Exchange Server, предотвращающий отображение архивного почтового ящика Exchange Online для конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-828">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="2bf7d-829">Исправлена проблема, из-за которой Outlook неожиданно закрывался у пользователей надстроек на основе Redemption. </span><span class="sxs-lookup"><span data-stu-id="2bf7d-829">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="2bf7d-830">Устранена проблема, из-за которой пользователи не могли выбрать больше одной категории для поиска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-830">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="2bf7d-831">Устранена проблема, из-за которой время начала для некоторых элементов календаря неожиданно изменялось при копировании события из другой встречи. </span><span class="sxs-lookup"><span data-stu-id="2bf7d-831">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="2bf7d-832">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-832">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-833">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-833">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-834">Это изменение исправляет проблему с объединением фигур при работе с текстом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-834">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="2bf7d-835">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-835">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="2bf7d-836">Это изменение исправляет проблему с циклическим воспроизведением фоновых видео в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-836">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="2bf7d-837">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-837">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-838">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-838">Project</span></span>

- <span data-ttu-id="2bf7d-839">Исправлена ​​проблема, из-за которой максимальное количество единиц ресурса не всегда отражало последнее обновление.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-839">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-840">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-840">Visio</span></span>

- <span data-ttu-id="2bf7d-841">Эта проблема возникла из-за недавней регрессии.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-841">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="2bf7d-842">Мы устранили эту проблему.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-842">We have resolved the issue.</span></span> <span data-ttu-id="2bf7d-843">В диалоговом окне "Сохранить как веб-страницу" поля будут правильно заполнены в соответствии с вводом пользователя, и пользователи могут легко сохранять свои файлы как веб-страницы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-843">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="2bf7d-p144">Проблема исправлена. Теперь можно внедрять файлы Visio как объекты в другие приложения Office, такие как PowerPoint и Word, а также осуществлять беспроблемный доступ к ним из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p144">This issue has been fixed. You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-846">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-846">Word</span></span>

- <span data-ttu-id="2bf7d-847">Исправлена проблема, из-за которой на компьютерах с настраиваемыми параметрами хеша наблюдались проблемы во время сеанса совместной работы с параметрами хеша, отличным от sha512.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-847">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="2bf7d-848">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-848">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="2bf7d-849">Исправлена проблема при редактировании записи примечания с @упоминанием.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-849">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="2bf7d-850">Исправлена проблема для повышения функциональности современных примечаний. </span><span class="sxs-lookup"><span data-stu-id="2bf7d-850">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="2bf7d-851">Исправлена проблема с удалением современных примечаний в элементе управления содержимым, который помечен как нередактирумый.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-851">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="2bf7d-852">Исправлена проблема с анимацией при вводе текста в нижней части карточки комментария.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-852">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="2bf7d-853">Исправлена проблема, из-за которой поле ответа в карточке примечания располагалось вне экрана.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-853">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="2bf7d-854">Исправлена проблема с картой примечаний, отображаемой в верхней части страницы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-854">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="2bf7d-855">Исправлена ошибка в примечаниях, из-за которой текст пропадал при прокручивании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-855">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="2bf7d-856">Исправлена проблема со встроенными полосами прокрутки в области примечаний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-856">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="2bf7d-857">Черновики примечаний исчезают при создании нового экземпляра Word.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-857">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="2bf7d-858">Устранена проблема, из-за которой Word зависал при сохранении документа в формате PDF со скрытым текстом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-858">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-january-04"></a><span data-ttu-id="2bf7d-860">Версия 2012: 4 января</span><span class="sxs-lookup"><span data-stu-id="2bf7d-860">Version 2012: January 04</span></span>
<span data-ttu-id="2bf7d-861">*Версия 2012 (сборка 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-861">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="2bf7d-862">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-862">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-864">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-864">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-865">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-865">Excel</span></span>

- <span data-ttu-id="2bf7d-866">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-866">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-867">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-867">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-868">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-868">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-869">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-869">Word</span></span>

- <span data-ttu-id="2bf7d-870">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-870">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-28"></a><span data-ttu-id="2bf7d-872">Версия 2012: 28 декабря</span><span class="sxs-lookup"><span data-stu-id="2bf7d-872">Version 2012: December 28</span></span>
<span data-ttu-id="2bf7d-873">*Версия 2012 (сборка 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-873">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-875">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-875">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-876">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-876">Outlook</span></span>

- <span data-ttu-id="2bf7d-877">Исправлена проблема, приводившая к зависаниям у некоторых пользователей при загрузке их календарей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-877">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-21"></a><span data-ttu-id="2bf7d-879">Версия 2012: 21 декабря</span><span class="sxs-lookup"><span data-stu-id="2bf7d-879">Version 2012: December 21</span></span>
<span data-ttu-id="2bf7d-880">*Версия 2012 (сборка 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-880">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-882">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-882">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-883">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-883">Excel</span></span>

- <span data-ttu-id="2bf7d-884">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-884">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2bf7d-885">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-885">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-886">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-886">Outlook</span></span>

- <span data-ttu-id="2bf7d-887">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время начала собрания на 5–10 минут позже по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-887">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="2bf7d-888">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-888">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="2bf7d-889">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-889">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2bf7d-890">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-890">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-891">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-891">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-892">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-892">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2bf7d-893">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-893">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-894">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-894">Word</span></span>

- <span data-ttu-id="2bf7d-895">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-895">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2bf7d-896">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-896">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-899">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-899">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-900">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-900">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-901">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-901">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-14"></a><span data-ttu-id="2bf7d-903">Версия 2012: 14 декабря</span><span class="sxs-lookup"><span data-stu-id="2bf7d-903">Version 2012: December 14</span></span>
<span data-ttu-id="2bf7d-904">*Версия 2012 (сборка 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-904">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-906">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-906">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-907">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-907">Outlook</span></span>

- <span data-ttu-id="2bf7d-908">**Ваши параметры Outlook в облаке.** Выберите свои параметры Outlook для Windows, например автоматические ответы, сортировку почты и конфиденциальность, и получайте их на любом компьютере.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-908">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-911">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-911">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2bf7d-912">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-912">Office Suite</span></span>

- <span data-ttu-id="2bf7d-913">Оптимизированный размер двоичного файла.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-913">Optimized binary size.</span></span>


- <span data-ttu-id="2bf7d-914">Anaheim WebView пока не поддерживает службу Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-914">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="2bf7d-915">С этим исправлением платформа надстроек Office откатывается на веб-представление уровнем ниже в среде с поддержкой WIP.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-915">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="2bf7d-916">Это может быть Edge Spartan WebView или Trident WebView в зависимости от среды на компьютере пользователя.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-916">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="2bf7d-917">Оба веб-представления уровнем ниже поддерживают WIP.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-917">Both down level WebViews support WIP.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-07"></a><span data-ttu-id="2bf7d-919">Версия 2012: 7 декабря</span><span class="sxs-lookup"><span data-stu-id="2bf7d-919">Version 2012: December 07</span></span>
<span data-ttu-id="2bf7d-920">*Версия 2012 (сборка 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-920">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-922">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-922">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="2bf7d-923">Teams</span><span class="sxs-lookup"><span data-stu-id="2bf7d-923">Teams</span></span>

- <span data-ttu-id="2bf7d-924">**В Teams теперь поддерживаются встроенные уведомления Windows:** Теперь пользователи могут выбирать предпочитаемый способ доставки уведомлений, используя команды, встроенные в баннеры Teams или встроенные баннеры Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-924">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="2bf7d-925">**Представление галереи 2x2 для собраний Teams в VDI Citrix и VMware:** Функция представления галереи 2x2 в VDI в Teams позволяет просматривать до четырех участников в представлении галереи 2x2 на клиентах VDI от Citrix, VMWare при использовании клиента Teams в оптимизированном режиме для VDI.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-925">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="2bf7d-926">**Реакции на собраниях:**  Реакции на собраниях — новый способ взаимодействия на собраниях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-926">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="2bf7d-927">Участники могут отправлять реакции, которые будут показаны в виде потока на контенте, к которому предоставляется доступ, а также на пользователе, отправившем реакцию, если они отображаются на сцене собрания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-927">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="2bf7d-928">**Режим "Вместе" и Большая галерея для веб-собраний** С помощью Большой галереи можно просматривать видео до 49 других пользователей одновременно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-928">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="2bf7d-929">Этот параметр доступен, если камеры включены не менее чем у десяти участников.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-929">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="2bf7d-930">Режим "Вместе" создает ощущение, что вы и все участники собрания находитесь в одном и том же месте.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-930">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="2bf7d-931">Режим "Вместе" доступен, если на собрании присутствует не менее пяти участников.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-931">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="2bf7d-932">**Объединение звонков** Функция объединения звонков позволяет пользователям объединять новый звонок или новый входящий вызов с их личным или групповым звонком.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-932">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="2bf7d-933">Она используется для вызовов VOIP и звонков по ТСОП в Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-933">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="2bf7d-934">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-934">Visio</span></span>

- <span data-ttu-id="2bf7d-935">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-935">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="2bf7d-936">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-936">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-939">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-939">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-940">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-940">Excel</span></span>

- <span data-ttu-id="2bf7d-941">Исправлена проблема, из-за которой некоторые элементы не был локализованы на китайском языке (упрощенное письмо).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-941">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="2bf7d-942">Исправлена проблема, из-за которой приложение Excel неожиданно прекращало работу при обновлении.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-942">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="2bf7d-943">Исправлена проблема, из-за которой команда "Вставить объект" не отображала соответствующий значок при вставке файла из локальной папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-943">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="2bf7d-944">Исправлена проблема, из-за которой правка на языках, требующих использования IME, не работала должным образом, если правка выполнялась в режиме перезаписи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-944">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="2bf7d-945">Исправлена проблема, из-за которой для некоторых пользователей неверно отображалась панель сообщений, уведомляющая о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-945">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="2bf7d-946">Устранена проблема, вызывавшая неожиданное закрытие Excel при копировании и вставке данных в представлении формулы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-946">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="2bf7d-947">Восстановлена нарушенная ссылка на справочную статью в оповещении, возникающем при отключении автосохранения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-947">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="2bf7d-948">Исправлена проблема, из-за которой приложение Excel переставало работать, если выполнялся ввод данных при запуске Excel в определенных языках.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-948">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="2bf7d-949">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-949">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="2bf7d-950">Исправлена проблема, из-за которой Power Pivot не мог правильно импортировать текстовый файл с разделителями (табуляциями).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-950">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-951">Outlook</span></span>

- <span data-ttu-id="2bf7d-952">Исправлена проблема, из-за которой поле "Кому:" было пустым в отчетах о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-952">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="2bf7d-953">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-953">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="2bf7d-954">Исправлена проблема, из-за которой у пользователей возникали ошибки при отправке почты Outlook из приложений, отличных от Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-954">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="2bf7d-955">Исправлена проблема, из-за которой терялось форматирование смарт-ссылок при сохранении в черновике.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-955">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="2bf7d-956">Исправлена проблема, из-за которой не удавалось добавить вложение в сообщение, открытое из ZIP-файла.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-956">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-957">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-958">Исправлена ошибка при копировании и вставке уравнения из Word в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-958">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="2bf7d-959">Это изменение устраняет проблему, связанную с таймаутами при анализе рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-959">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="2bf7d-960">Это изменение устраняет грамматическую ошибку в пользовательском интерфейсе создания GIF с анимацией.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-960">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="2bf7d-961">Это изменение устраняет проблему с заливками путей при объединений фигур определенных геометрий.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-961">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="2bf7d-962">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-962">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="2bf7d-963">Это изменение устраняет проблему с обработкой ошибок, которые могут возникнуть во время загрузки видео.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-963">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="2bf7d-964">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-964">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="2bf7d-965">Исправлена проблема, из-за которой индикатор присутствия неизвестного соавтора не обновлялся полностью при получении дополнительных сведений о соавторе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-965">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="2bf7d-966">Исправлено удаление ссылки на пустой указатель при изменении размера представления слайда с включенной линейкой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-966">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="2bf7d-967">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-967">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-968">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-968">Project</span></span>

- <span data-ttu-id="2bf7d-969">Исправлена проблема, из-за которой отсутствовали изменения при открытии пользователями проектов, сохраненных с измененными сведениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-969">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="2bf7d-970">Исправлена проблема, из-за которой не удавалось удалить зависимости в конечных результатах, если сайт SharePoint, с которым были связаны конечные результаты, больше не существовал.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-970">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="2bf7d-971">Исправлена проблема, из-за которой открытие проекта с большим количеством ресурсов занимало много времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-971">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="2bf7d-972">Исправлена проблема, из-за которой могли отображаться многочисленные неназначенные задания, связанные с задачей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-972">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="2bf7d-973">Исправлена проблема, из-за которой в крупных проектах имя задачи могло вводиться очень медленно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-973">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="2bf7d-974">Исправлена проблема, из-за которой могли открываться определенные проекты, если имелась проблема с файлом проекта в определенной части загрузки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-974">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-975">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-975">Word</span></span>

- <span data-ttu-id="2bf7d-976">Вставка в виде обычного текста часто бывает предпочтительнее вставки форматированного текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-976">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="2bf7d-977">Это исправленное контекстное меню позволяет пользователю выполнять вставку в виде обычного текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-977">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="2bf7d-978">В противном случае пользователю потребовалось бы копировать в редактор обычного текста, например Блокнот, а затем копировать из Блокнота в нужное приложение</span><span class="sxs-lookup"><span data-stu-id="2bf7d-978">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="2bf7d-979">Исправлена ошибка при копировании и вставке уравнения из Word в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-979">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="2bf7d-980">Это изменение исправляет проблему, связанную с курсором при редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-980">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="2bf7d-981">Исправлена проблема, из-за которой изображения становились размытыми при изменении масштаба.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-981">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="2bf7d-982">Исправлена проблема, из-за которой длинные гиперссылки усекались.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-982">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-983">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-983">Office Suite</span></span>

- <span data-ttu-id="2bf7d-984">В наборе Office исправлена проблема, из-за которой установка более новой версии Office поверх некоторых старых версий могла приводить к ухудшению функциональности (например, невозможности использовать Power Query) из-за отсутствия записей в реестре.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-984">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-december-01"></a><span data-ttu-id="2bf7d-986">Версия 2011: 1 декабря</span><span class="sxs-lookup"><span data-stu-id="2bf7d-986">Version 2011: December 01</span></span>
<span data-ttu-id="2bf7d-987">*Версия 2011 (сборка 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-987">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-989">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-989">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-990">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-990">Outlook</span></span>

- <span data-ttu-id="2bf7d-991">**Все собрания по сети.** Упростите планирование собраний по сети с помощью нового параметра, который переводит все собрания в онлайн по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-991">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-994">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-994">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-995">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-995">Outlook</span></span>

- <span data-ttu-id="2bf7d-996">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-996">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="2bf7d-997">Исправлена проблема, из-за которой некоторые пользователи не видели подписей в раскрывающемся списке подписей, хотя у них настроена одна или несколько подписей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-997">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-998">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-998">Project</span></span>

- <span data-ttu-id="2bf7d-999">Исправлена проблема, из-за которой могли открываться определенные проекты, если имелась проблема с файлом проекта в определенной части загрузки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-999">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-24"></a><span data-ttu-id="2bf7d-1001">Версия 2011: 24 ноября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1001">Version 2011: November 24</span></span>
<span data-ttu-id="2bf7d-1002">*Версия 2011 (сборка 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1002">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1004">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1004">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2bf7d-1005">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1005">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1006">Исправлена ошибка при копировании и вставке уравнения из Word в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1006">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-21"></a><span data-ttu-id="2bf7d-1008">Версия 2011: 21 ноября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1008">Version 2011: November 21</span></span>
<span data-ttu-id="2bf7d-1009">*Версия 2011 (сборка 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1009">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1011">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1011">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1012">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1012">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1013">**Библиотека видео.** Улучшайте свои документы с помощью библиотеки специально отобранных бесплатных видеоматериалов, доступных в приложении</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1013">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1016">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1016">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1017">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1017">Outlook</span></span>

- <span data-ttu-id="2bf7d-1018">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1018">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="2bf7d-1019">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1019">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="2bf7d-1020">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1020">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="2bf7d-1021">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1021">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="2bf7d-1022">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1022">0 = filetimes are excluded.</span></span> <span data-ttu-id="2bf7d-1023">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1023">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="2bf7d-1024">Исправлена проблема, приводившая к исчезновению встроенных изображений при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1024">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-18"></a><span data-ttu-id="2bf7d-1026">Версия 2011: 18 ноября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1026">Version 2011: November 18</span></span>
<span data-ttu-id="2bf7d-1027">*Версия 2011 (сборка 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1027">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="2bf7d-1028">Исправления различных ошибок и проблем производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1028">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="2bf7d-1029">Версия 2011: 16 октября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1029">Version 2011: November 16</span></span>
<span data-ttu-id="2bf7d-1030">*Версия 2011 (сборка 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1030">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1032">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1032">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1033">Outlook</span></span>

- <span data-ttu-id="2bf7d-1034">**Одна подпись на всех устройствах.** Ваша подпись хранится в облаке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1034">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="2bf7d-1035">Создайте ее один раз и используйте везде, где применяете Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1035">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1038">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1038">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1039">Outlook</span></span>

- <span data-ttu-id="2bf7d-1040">Исправлена проблема, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1040">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1041">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1041">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1042">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1042">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-november-09"></a><span data-ttu-id="2bf7d-1044">Версия 2011: 9 ноября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1044">Version 2011: November 09</span></span>
<span data-ttu-id="2bf7d-1045">*Версия 2011 (сборка 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1045">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1047">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1047">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1048">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1048">Excel</span></span>

- <span data-ttu-id="2bf7d-1049">**Создание потоков данных Power Platform из запросов:** теперь можно экспортировать запросы в шаблоны Power Query, которые можно использовать для создания новых потоков данных Power Platform.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1049">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1052">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1052">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1053">Доступ</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1053">Access</span></span>

- <span data-ttu-id="2bf7d-1054">Исправлена проблема, из-за которой для некоторых пользователей отображалась ошибка "Недостаточно системных ресурсов", когда они пытались экспортировать запрос из своей синхронизированной папки OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1054">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="2bf7d-1055">Исправлена проблема, из-за которой автоматическое переключение между окнами форм приводило к переключению на другую форму.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1055">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="2bf7d-1056">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1056">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-1057">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1057">Excel</span></span>

- <span data-ttu-id="2bf7d-1058">Устранена проблема, из-за которой имя файла не изменялось после операции SaveAs с включенными надстройками COM.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1058">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="2bf7d-1059">Исправлена проблема с Power Pivot при использовании подключения к базе данных Oracle.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1059">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="2bf7d-1060">Устранена проблема, вызывавшая сбой при автоматическом сохранении с неверным или ошибочным сообщением об ошибке, если в модели данных Excel было неверное определение меры.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1060">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="2bf7d-1061">Исправлена проблема, вызывавшая неожиданное прекращение работы Excel при запуске вычисления MTR и обновления объекта групповой политики (например, с помощью удаленного обновления групповой политики).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1061">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="2bf7d-1062">Исправлена проблема, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1062">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="2bf7d-1063">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1063">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="2bf7d-1064">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1064">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-1065">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1065">Outlook</span></span>

- <span data-ttu-id="2bf7d-1066">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1066">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="2bf7d-p158">Устранена проблема, из-за которой быстрая печать вложенных изображений вызывала ошибку: "Windows не удалось найти изображение. Проверьте его местонахождение и попробуйте еще раз".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p158">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="2bf7d-1069">Исправлена проблема, из-за которой у некоторых пользователей Outlook запускался в автономном состоянии, пока они не выбирали сетевой режим работы вручную.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1069">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="2bf7d-1070">Исправлена проблема, из-за которой при вставке URL-адреса, скопированного из расположения собрания, в другое место (например, в браузер) URL-адрес содержал в конце точку с запятой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1070">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="2bf7d-1071">Исправлена проблема, из-за которой пользователи не могли удалять встречи в календаре групп Microsoft 365 при обычной проверке подлинности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1071">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="2bf7d-1072">Исправлена проблема, вызывавшая сбой запуска Outlook при загрузке кэша псевдонимов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1072">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="2bf7d-1073">Исправлена проблема, из-за которой владелец почтового ящика не мог управлять разрешением общего доступа для своего календаря, так как этот параметр был затенен.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1073">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="2bf7d-1074">Исправлена проблема, из-за которой приложение Outlook не могло создать сообщение с ограниченным разрешением.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1074">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="2bf7d-1075">Исправлена проблема, из-за которой сохранение шаблонов электронной почты в виде OFT-файлов приводило к изменению китайских иероглифов на вопросительные знаки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1075">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1076">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1076">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1077">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1077">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="2bf7d-1078">Исправлена проблема, из-за которой в значке заполнителя содержимого рядом с "Изображениями" не было всплывающих подсказок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1078">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="2bf7d-1079">Исправлена проблема, из-за которой при защищенном просмотре слайд-шоу, демонстрируемом в файле pptsx, можно было сделать снимок экрана документа, защищенного IRM.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1079">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="2bf7d-1080">Исправлена проблема, из-за которой линии сетки смещались со слайдов при закрытии области конструктора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1080">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="2bf7d-1081">Исправлена проблема, из-за которой при дублировании слайд-шоу на второй монитор оно могло быть скрыто за другим окном.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1081">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="2bf7d-1082">Исправлена проблема, из-за которой полоса прокрутки на слайде начинала двигаться самостоятельно после прекращения записи экрана с открытой областью выбора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1082">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1083">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1083">Project</span></span>

- <span data-ttu-id="2bf7d-1084">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChagne имело неправильное значение в случае изменения задержки в представлении типа "Форма задач".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1084">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="2bf7d-1085">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1085">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="2bf7d-1086">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1086">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2bf7d-1087">Исправлена проблема, из-за которой задействование ресурсов выполняло поиск ресурса по имени, а не по GUID, что приводило к проблемам при наличии нескольких ресурсов с одинаковым именем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1087">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="2bf7d-1088">Устранена проблема, из-за которой после группирования списка задач на сайте проекта нельзя было быстро изменить список задач.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1088">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="2bf7d-1089">Исправлена проблема, при которой после обновления корпоративного ресурса с помощью CSOM максимальные единицы для ресурса могли быть потеряны.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1089">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1090">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1090">Word</span></span>

- <span data-ttu-id="2bf7d-1091">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1091">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="2bf7d-1092">Исправлена проблема, из-за которой щелчок по маркеру примечания не приводил к уменьшению масштаба для отображения карточки примечания в представлении.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1092">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="2bf7d-1093">Исправлена проблема макета, из-за которой могла смещаться линия между столбцами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1093">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="2bf7d-1094">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1094">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="2bf7d-1095">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1095">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="2bf7d-1096">Исправлена проблема печати, из-за которой применялась метка конфиденциальности с подложками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1096">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1097">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1097">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1098">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1098">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="2bf7d-1099">Устранена проблема, из-за которой при интерактивном входе в SSO API возвращался код ошибки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1099">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-november-06"></a><span data-ttu-id="2bf7d-1101">Версия 2010: 6 ноября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1101">Version 2010: November 06</span></span>
<span data-ttu-id="2bf7d-1102">*Версия 2010 (сборка 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1102">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="2bf7d-1103">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1103">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-november-04"></a><span data-ttu-id="2bf7d-1106">Версия 2010: 4 ноября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1106">Version 2010: November 04</span></span>
<span data-ttu-id="2bf7d-1107">*Версия 2010 (сборка 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1107">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1109">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1109">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1110">Excel</span></span>

- <span data-ttu-id="2bf7d-1111">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1111">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2bf7d-1112">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1112">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="2bf7d-1113">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1113">Outlook</span></span>

- <span data-ttu-id="2bf7d-1114">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1114">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2bf7d-1115">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1115">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1116">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1116">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1117">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1117">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2bf7d-1118">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1118">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="2bf7d-1119">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1119">See details in [blog post](https://insider.office.com/ru-RU/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="2bf7d-1120">**Создание GIF с прозрачным фоном:** при экспорте в GIF с анимацией новый параметр позволит сделать фон прозрачным.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1120">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="2bf7d-1121">Дополнительные сведения см. в этой [записи блога](https://insider.office.com/ru-RU/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1121">See details in [blog post](https://insider.office.com/ru-RU/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="2bf7d-1122">**Экспорт GIF с анимацией в диапазоне:** выберите диапазон слайдов при экспорте в GIF с анимацией</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1122">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1123">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1123">Word</span></span>

- <span data-ttu-id="2bf7d-1124">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1124">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2bf7d-1125">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1125">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1128">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1128">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1129">Outlook</span></span>

- <span data-ttu-id="2bf7d-1130">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1130">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1131">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1131">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1132">Исправлена проблема, вызывавшая сбой при попытке сохранить файлы, перешедшие из состояния "синхронизировано" в состояние "только для сервера".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1132">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-27"></a><span data-ttu-id="2bf7d-1134">Версия 2010: 27 октября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1134">Version 2010: October 27</span></span>
<span data-ttu-id="2bf7d-1135">*Версия 2010 (сборка 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1135">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1139">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1140">Outlook</span></span>

- <span data-ttu-id="2bf7d-1141">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1141">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="2bf7d-1142">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1142">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-24"></a><span data-ttu-id="2bf7d-1144">Версия 2010: 24 октября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1144">Version 2010: October 24</span></span>
<span data-ttu-id="2bf7d-1145">*Версия 2010 (сборка 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1145">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1149">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1149">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1150">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1150">Outlook</span></span>

- <span data-ttu-id="2bf7d-1151">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1151">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="2bf7d-1152">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1152">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1153">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1153">Project</span></span>

- <span data-ttu-id="2bf7d-1154">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1154">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2bf7d-1155">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1155">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-19"></a><span data-ttu-id="2bf7d-1157">Версия 2010: 19 октября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1157">Version 2010: October 19</span></span>
<span data-ttu-id="2bf7d-1158">*Версия 2010 (сборка 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1158">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1160">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1160">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1161">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1161">Outlook</span></span>

- <span data-ttu-id="2bf7d-1162">**Экономия времени при создании сообщений:** в Outlook отображаются предложения по литературной правке, помогающие быстро создавать сообщения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1162">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="2bf7d-1163">Чтобы принять предложение, используйте клавишу TAB.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1163">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="2bf7d-1164">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/text-predictions-in-word-outlook)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1164">See details in [blog post](https://insider.office.com/ru-RU/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="2bf7d-1165">**Преодолейте языковый барьер с помощью встроенного переводчика.** Надстройки для перевода больше не нужны!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1165">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="2bf7d-1166">В сообщении щелкните правой кнопкой мыши, чтобы перевести определенные слова, фразы или весь текст.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1166">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="2bf7d-1167">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1167">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="2bf7d-1168">**Обновления для задач пользовательского интерфейса:** визуальное обновление элементов задач</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1168">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1169">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1170">**Отрепетируйте презентацию с помощью тренера выступлений.** Получите подсказки, которые помогут удержать аудиторию, в том числе об использовании темпа речи, чрезмерного употребления слов, языка тела и т. д.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1170">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="2bf7d-1171">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1171">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="2bf7d-1172">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1172">Word</span></span>

- <span data-ttu-id="2bf7d-1173">**Обновление области "Корректор" (Майкрософт) в классическом приложении Word:** мы обновили текущий интерфейс области "Корректор" в классическом приложении Word.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1173">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="2bf7d-1174">**Мгновенные предложения по написанию.** Применяйте рукописный ввод одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1174">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="2bf7d-1175">Обновленная панель редактора позволяет легко переходить между предложениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1175">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1178">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1178">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1179">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1179">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1180">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1180">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-11"></a><span data-ttu-id="2bf7d-1182">Версия 2010: 11 октября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1182">Version 2010: October 11</span></span>
<span data-ttu-id="2bf7d-1183">*Версия 2010 (сборка 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1183">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1185">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1185">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1186">Excel</span></span>

- <span data-ttu-id="2bf7d-1187">**Защита данных от вредоносных файлов.** Application Guard помогает защитить вас от вредоносных программ, позволяя читать, печатать и сохранять файлы Office в изолированном контейнере.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1187">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="2bf7d-1188">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1188">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1189">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1190">**Защита данных от вредоносных файлов.** Application Guard помогает защитить вас от вредоносных программ, позволяя читать, печатать и сохранять файлы Office в изолированном контейнере.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1190">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="2bf7d-1191">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1191">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="2bf7d-1192">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1192">Word</span></span>

- <span data-ttu-id="2bf7d-1193">**Защита данных от вредоносных файлов.** Application Guard помогает защитить вас от вредоносных программ, позволяя читать, печатать и сохранять файлы Office в изолированном контейнере.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1193">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="2bf7d-1194">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1194">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1197">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1197">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1198">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1198">Access</span></span>

- <span data-ttu-id="2bf7d-1199">Исправлена проблема, из-за которой не удавалось правильно задать положение полосы прокрутки при загрузке окна запроса или схемы данных, сохраненных во время прокрутки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1199">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="2bf7d-1200">Исправлена проблема, из-за которой в области задач "Добавить таблицу" неправильно отображались имена, содержащие '&'.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1200">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-1201">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1201">Excel</span></span>

- <span data-ttu-id="2bf7d-1202">Исправлена проблема, из-за которой в диаграммах не работал многоуровневый ручной интервал категорий.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1202">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="2bf7d-1203">Исправлена проблема с 2D-диаграммами с картами, когда нельзя было задать цвета для максимального, среднего и минимального значений ряда данных с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1203">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="2bf7d-1204">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1204">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="2bf7d-1205">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1205">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="2bf7d-1206">Исправлена проблема, из-за которой при переключении между листами с большим объемом данных могла возникать заметная задержка, если был включен страничный режим.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1206">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="2bf7d-1207">Исправлена проблема, из-за которой при добавлении в таблицу, используемую для проверки данных, не обновлялись параметры для всех листов в книге.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1207">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="2bf7d-1208">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1208">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="2bf7d-1209">Исправлена проблема, которая в некоторых случаях приводила к сбою на листе диаграммы при вводе формулы в строке формул.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1209">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="2bf7d-1210">Исправлена проблема с панелью формул Excel, которая не отображалась полностью после отключения от устройства, например с подключении или отклчючении от уадаленного сеанса или при смене монитора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1210">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="2bf7d-1211">OneNote</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1211">OneNote</span></span>

- <span data-ttu-id="2bf7d-1212">Исправлена проблема, из-за которой пользователь не мог выбрать и скопировать URL-адрес записной книжки из текстового поля в разделе "Файл OutSpace > Сведения".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1212">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="2bf7d-1213">Исправлена проблема, из-за которой при наведении указателя мыши на зеленый цвет в селекторе цветов записной книжки появлялось всплывающее окно "красный мел".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1213">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="2bf7d-1214">Исправлена проблема, из-за которой OneNote не поддерживал высокую контрастность цветов в полотне для пользовательских тем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1214">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-1215">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1215">Outlook</span></span>

- <span data-ttu-id="2bf7d-1216">Исправлена проблема, из-за которой автоматически созданные сообщения отправлялись пустые, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1216">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="2bf7d-1217">Исправлена проблема с кэшированием неправильного GUID для папок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1217">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="2bf7d-1218">При копировании и вставке адреса электронной почты в поле "получатель" с отображаемым именем адрес электронной почты не всегда распознается правильно и появляется сообщение о недействительном адресе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1218">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="2bf7d-1219">Эта проблема устранена, то есть имя и адрес электронной почты распознаются правильно, а предупреждение больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1219">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="2bf7d-1220">Исправлена проблема, из-за которой общие сетевые папки не возвращали имя родительской папки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1220">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="2bf7d-1221">Вместо сбоя они возвращали пустой путь, который ошибочно отправлялся в основную учетную запись.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1221">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="2bf7d-1222">Исправлена проблема, из-за которой параметр "Сохранить как" был недоступен для классических вложений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1222">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="2bf7d-1223">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1223">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="2bf7d-1224">Исправлена проблема, из-за которой после повторного открытия черновика в области просмотра "Только для чтения" включалось отслеживание изменений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1224">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="2bf7d-1225">Исправлена проблема, из-за которой сообщения электронной почты скрывались после отключения сортировки почты и выполнения сортировки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1225">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="2bf7d-1226">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1226">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1227">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1228">Исправлена проблема, из-за которой PowerPoint не экспортировал маркеры списка в виде прямоугольников при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1228">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="2bf7d-1229">Исправлена проблема, из-за которой изображение GIF анимировалось только один раз в редакторе и слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1229">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="2bf7d-1230">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1230">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="2bf7d-1231">Исправлена проблема, из-за которой диалоговое окно завершения сеанса отображалось на странице сводки, если вы переходили с последнего слайда к следующему после нажатия кнопки "Завершить сеанс" и до появления сводки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1231">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1232">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1232">Project</span></span>

- <span data-ttu-id="2bf7d-1233">Исправлена проблема, из-за которой метод VBA ConsolidateProjects мог выполнять регистрацию, если вы пытались добавить один проект несколько раз и присвоили параметру AttachToSources значение false.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1233">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="2bf7d-1234">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1234">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="2bf7d-1235">Исправлена проблема, из-за которой метод VBA ConsolidateProjects мог выполнять регистрацию, если вы пытались добавить один проект несколько раз и присвоили параметру AttachToSources значение false.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1235">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="2bf7d-1236">Исправлена проблема, из-за которой могли возникать задержки при переключении представлений и открытии сведений о задаче или проекте при наличии настраиваемых полей с формулами и использовании освоенного объема.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1236">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="2bf7d-1237">Исправлена проблема, из-за которой Project мог аварийно завершить работу, если вы применяли группу с помощью представления "Использование ресурсов" или "Лист ресурсов", а затем вставляли столбец.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1237">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1238">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1238">Word</span></span>

- <span data-ttu-id="2bf7d-1239">Исправлена проблема, из-за которой ссылки на файлы, поддерживающие рабочий процесс, не открывались должным образом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1239">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="2bf7d-1240">Исправлена проблема, из-за после прикосновения к исправлению (вставке или удалению) появлялось всплывающее примечание.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1240">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="2bf7d-1241">Исправлена проблема с удалением выносок примечаний в Word.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1241">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="2bf7d-1242">Исправлена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1242">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="2bf7d-1243">Исправлена проблема с сохранением документа Word, содержащего ссылку и формулу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1243">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="2bf7d-1244">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1244">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1245">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1245">Office Suite</span></span>

- <span data-ttu-id="2bf7d-p172">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах тонера нет в принципе. Сообщение было изменено и теперь гласит: "Мало чернил или тонера" и "Нет чернил или тонера".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p172">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-october-07"></a><span data-ttu-id="2bf7d-1249">Версия 2009: 7 октября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1249">Version 2009: October 07</span></span>
<span data-ttu-id="2bf7d-1250">*Версия 2009 (сборка 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1250">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1252">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1252">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1253">Excel</span></span>

- <span data-ttu-id="2bf7d-1254">**Создание типов данных с помощью Power Query:** создание насыщенных типов данных с помощью Power Query из любого источника данных</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1254">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1255">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1255">Outlook</span></span>

- <span data-ttu-id="2bf7d-1256">**Вам помогает проверка грамматики:** Outlook помечает грамматические ошибки по мере ввода текста, так что вы можете применять исправления одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1256">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="2bf7d-1257">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1257">See details in [blog post](https://insider.office.com/ru-RU/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1260">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1260">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1261">Outlook</span></span>

- <span data-ttu-id="2bf7d-1262">Решает проблему, в результате которой при поиске в некэшированных общих календарях не возвращалось результатов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1262">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="2bf7d-1263">Решает проблему, при которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1263">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="2bf7d-1264">Решает проблему, которая приводила к появлению периодических отказов при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1264">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1265">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1266">Установка исправления безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1266">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1267">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1267">Office Suite</span></span>

- <span data-ttu-id="2bf7d-p173">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах тонера нет в принципе. Сообщение было изменено и теперь гласит: "Мало чернил или тонера" и "Нет чернил или тонера".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p173">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-26"></a><span data-ttu-id="2bf7d-1271">Версия 2009: 26 сентября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1271">Version 2009: September 26</span></span>
<span data-ttu-id="2bf7d-1272">*Версия 2009 (сборка 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1272">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1274">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1274">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1275">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1275">Outlook</span></span>

- <span data-ttu-id="2bf7d-1276">Решает проблему, из-за которой некоторые автоматически созданные сообщения электронной почты отправляются без текста сообщения если в строке темы письма она не указана.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1276">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1277">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1277">Project</span></span>

- <span data-ttu-id="2bf7d-1278">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1278">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-21"></a><span data-ttu-id="2bf7d-1280">Версия 2009: 21 сентября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1280">Version 2009: September 21</span></span>
<span data-ttu-id="2bf7d-1281">*Версия 2009 (сборка 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1281">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1283">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1283">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1284">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1284">Access</span></span>

- <span data-ttu-id="2bf7d-1285">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1285">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1286">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1286">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1287">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1287">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="2bf7d-1288">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1288">Excel</span></span>

- <span data-ttu-id="2bf7d-1289">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1289">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2bf7d-1290">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1290">No conversion required.</span></span><br /><span data-ttu-id="2bf7d-1291">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1291">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2bf7d-1292">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1292">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1293">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1293">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1294">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1294">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="2bf7d-1295">OneNote</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1295">OneNote</span></span>

- <span data-ttu-id="2bf7d-1296">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1296">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1297">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1297">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1298">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1298">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="2bf7d-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1299">Outlook</span></span>

- <span data-ttu-id="2bf7d-1300">**Удаление беседы владельцем сообщения.** Эта функция позволяет удалять беседы владельцу сообщения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1300">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="2bf7d-1301">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1301">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2bf7d-1302">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1302">No conversion required.</span></span><br /><span data-ttu-id="2bf7d-1303">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1303">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2bf7d-1304">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1304">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1305">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1305">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1306">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1306">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1307">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1308">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1308">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2bf7d-1309">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1309">No conversion required.</span></span><br /><span data-ttu-id="2bf7d-1310">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1310">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2bf7d-1311">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1311">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1312">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1312">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1313">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1313">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="2bf7d-1314">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1314">Project</span></span>

- <span data-ttu-id="2bf7d-1315">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1315">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1316">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1316">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1317">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1317">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="2bf7d-1318">Publisher</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1318">Publisher</span></span>

- <span data-ttu-id="2bf7d-1319">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1319">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1320">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1320">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1321">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1321">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="2bf7d-1322">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1322">Visio</span></span>

- <span data-ttu-id="2bf7d-1323">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1323">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1324">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1324">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1325">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1325">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="2bf7d-1326">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1326">Word</span></span>

- <span data-ttu-id="2bf7d-1327">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1327">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2bf7d-1328">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1328">No conversion required.</span></span><br /><span data-ttu-id="2bf7d-1329">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1329">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2bf7d-1330">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1330">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2bf7d-1331">Перейдите в раздел Файл > Параметры и выберите пункт "Использовать параметр системы" рядом с темой Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1331">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2bf7d-1332">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1332">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1335">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1335">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1336">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1336">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1337">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1337">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-14"></a><span data-ttu-id="2bf7d-1339">Версия 2009: 14 сентября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1339">Version 2009: September 14</span></span>
<span data-ttu-id="2bf7d-1340">*Версия 2009 (сборка 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1340">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="2bf7d-1341">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1341">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-10"></a><span data-ttu-id="2bf7d-1344">Версия 2009: 10 сентября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1344">Version 2009: September 10</span></span>
<span data-ttu-id="2bf7d-1345">*Версия 2009 (сборка 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1345">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1347">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1347">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1348">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1348">Access</span></span>

- <span data-ttu-id="2bf7d-1349">Эта проблема уже устранена и больше не должна вызывать сбой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1349">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="2bf7d-1350">Исправлена проблема, из-за которой подключения к базе данных ODBC не работали со сторонними приложениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1350">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-1351">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1351">Excel</span></span>

- <span data-ttu-id="2bf7d-1352">Мы устранили проблему, из-за которой при открытии файла с функцией ПУСТЬ появлялось сообщение: "Обнаружена проблема в содержимом файла "ваш_файл.xlsx".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1352">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="2bf7d-1353">Хотите восстановить все, что возможно?</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1353">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="2bf7d-1354">Если вы доверяете источнику этой книги, выберите Да".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1354">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="2bf7d-1355">Исправлена проблема, из-за которой при вводе имени формулы со скобками и вызове справки с помощью клавиши F1 не отображался раздел справки, относящийся к этой формуле.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1355">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="2bf7d-1356">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1356">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="2bf7d-1357">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1357">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="2bf7d-1358">Исправлен сбой, связанный со ссылками на надстройки XLAM и именованными диапазонами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1358">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="2bf7d-p188">Исправлена проблема, при которой при назначении пользователем настраиваемого стиля динамическому массиву появлялась ошибка: "Изменение части массива недопустимо". Это ограничение унаследовано из предыдущей версии и теперь удалено.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p188">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="2bf7d-1361">Исправлена проблема, из-за которой макросы, назначенные кнопкам, не работали после восстановления более ранней версии файла.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1361">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="2bf7d-1362">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1362">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-1363">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1363">Outlook</span></span>

- <span data-ttu-id="2bf7d-1364">Исправлена проблема, которая обеспечивала включение/отключение параметров входа по умолчанию через групповые политики.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1364">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="2bf7d-1365">Исправлена проблема, при которой устаревшее имя домена для отправителя сообщения электронной почты с правами помощника или менеджера сохранялось и показывалось при перемещении черновика письма между папками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1365">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="2bf7d-1366">Исправлена проблем, из-за которой у некоторых пользователей Outlook запускался в автономном состоянии, пока они не выбирали сетевой режим работы вручную.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1366">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="2bf7d-1367">Исправлена проблема, когда при запуске кода VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") после включения однострочной ленты (SLR) выдавалась ошибка среды выполнения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1367">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="2bf7d-1368">Исправлена проблема, при которой кнопки "OK" и "Отмена" в диалогах с автоматическими ответами были не видны в системах с высоким разрешением (например, 1750 x 1920), если выбран большой размер текста (например, 175%).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1368">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="2bf7d-1369">Исправлена проблема, при которой в результате отправки приглашения на собрание из пустой группы контактов в другую группу контактов появлялась ошибка.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1369">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="2bf7d-1370">Исправлена проблема, которая вызывала сбой при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1370">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="2bf7d-1371">Исправлена ошибка, при которой в случае, когда требуется, чтобы в групповой политике всегда была активна надстройка, надстройка мониторинга становится недоступной, чтобы не дать пользователям отключить надстройку.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1371">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="2bf7d-1372">Исправлена проблема, из-за которой пользователи могли отправлять содержимое письма, к которому применена политика "Не пересылать", в OneNote, если выбрано несколько сообщений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1372">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="2bf7d-1373">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1373">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="2bf7d-1374">Исправлена проблема, из-за которой атрибуты учетной записи пользователя в Active Directory для "otherTelephone" и "otherHomePhone" не сопоставлялись с соответствующими атрибутами LDAP Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1374">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="2bf7d-1375">Это изменение исправляет проблему, из-за которой страница "Собрание" продолжала отображаться после того, как пользователь переключал вкладки со страницы "Собрание" на страницу "Помощник по планированию".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1375">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1376">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1376">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1377">Исправлена проблема, из-за которой при определенных условиях пользователи не видели ленту/заголовок окна.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1377">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="2bf7d-1378">Исправлена ошибка, при которой после загрузки PowerPoint, вставки слайда, открытия и закрытия панели комментариев, слайды в области эскизов отображались с наложением.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1378">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="2bf7d-1379">Исправлена проблема с отключенной функцией вставки видео.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1379">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="2bf7d-1380">Исправлена проблема, из-за которой видео не воспроизводились автоматически в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1380">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1381">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1381">Project</span></span>

- <span data-ttu-id="2bf7d-1382">Исправлена проблема, при которой оставшиеся затраты не подсчитываются правильно, если у ресурса есть несколько таблиц норм затрат.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1382">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="2bf7d-1383">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1383">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="2bf7d-1384">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1384">Visio</span></span>

- <span data-ttu-id="2bf7d-1385">Пользователи сообщают о сбоях динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1385">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="2bf7d-1386">Самый распространенный сбой в вилке за июль.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1386">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1387">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1387">Word</span></span>

- <span data-ttu-id="2bf7d-1388">Исправлена проблема, из-за которой при нажатии пользователя на комментарий вокруг комментария отображалась граница.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1388">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="2bf7d-1389">Исправлена проблема, из-за которой неправильно отображался значок маркера.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1389">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="2bf7d-1390">Исправлена проблема, из-за которой пользователь не мог выйти из колонтитулов при выборе примечания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1390">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="2bf7d-1391">Исправлена проблема, из-за которой Word мог аварийно завершить работу после удаления примечаний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1391">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="2bf7d-1392">Исправлена проблема, из-за которой при создании черновика комментария и привязки его к линии, на которой уже есть комментарии, то черновик имел неверный порядок по отношению к выделенному комментарию в SideTrack.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1392">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="2bf7d-1393">Исправлена проблема, при которой фокус не переходил на панели комментариев, если масштаб документа был 160% или более, а панель комментариев была не видна.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1393">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="2bf7d-1394">Исправлена проблема, не позволявшая пользователям просматривать цепочки примечаний, выходивших за границы ответвления, так как прокрутка в ответвлении не работала.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1394">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="2bf7d-1395">Исправлена проблема, из-за которой поиск разрешенных примечаний в панели ответвления не работал.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1395">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="2bf7d-1396">Исправлена проблема, при которой комментарии для одного документа показывались в других открытых документах после переключения между открытыми документами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1396">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="2bf7d-1397">Исправлена проблема, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1397">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="2bf7d-1398">Исправлена проблема, из-за которой в некоторых случаях маркеры списка отображались неверно в сообщении.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1398">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="2bf7d-1399">Исправлена проблема с макросом, из-за которой AutoOpen запускался до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1399">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1400">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1400">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1401">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1401">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="2bf7d-1402">Исправлена проблема в диалоговом окне "Сжатие рисунка", из-за которой некоторые выбранные пользователем параметры разрешения не сохранялись.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1402">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="2bf7d-1403">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1403">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-04"></a><span data-ttu-id="2bf7d-1405">Версия 2008: 4 сентября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1405">Version 2008: September 04</span></span>
<span data-ttu-id="2bf7d-1406">*Версия 2008 (сборка 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1406">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1408">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1408">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2bf7d-1409">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1409">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1410">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1410">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-02"></a><span data-ttu-id="2bf7d-1412">Версия 2008: 2 сентября</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1412">Version 2008: September 02</span></span>
<span data-ttu-id="2bf7d-1413">*Версия 2008 (сборка 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1413">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1415">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1416">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1416">Excel</span></span>

- <span data-ttu-id="2bf7d-1417">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1417">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2bf7d-1418">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1418">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2bf7d-1419">**Быстрые правки с помощью пера в Excel.** Перо для рукописного ввода и быстрого изменения данных</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1419">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1422">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1422">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1423">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1423">Excel</span></span>

- <span data-ttu-id="2bf7d-1424">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1424">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1425">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1425">Word</span></span>

- <span data-ttu-id="2bf7d-1426">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1426">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-27"></a><span data-ttu-id="2bf7d-1428">Версия 2008: 27 августа</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1428">Version 2008: August 27</span></span>
<span data-ttu-id="2bf7d-1429">*Версия 2008 (сборка 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1429">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1433">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1433">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1434">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1434">Outlook</span></span>

- <span data-ttu-id="2bf7d-1435">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1435">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="2bf7d-1436">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1436">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="2bf7d-1437">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1437">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="2bf7d-1438">Исправлена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1438">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="2bf7d-1439">Исправлена проблема, из-за которой возникали аномалии при использовании пользователями компактного представления.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1439">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1440">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1440">Word</span></span>

- <span data-ttu-id="2bf7d-1441">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1441">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="2bf7d-1442">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1442">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-25"></a><span data-ttu-id="2bf7d-1444">Версия 2008: 25 августа</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1444">Version 2008: August 25</span></span>
<span data-ttu-id="2bf7d-1445">*Версия 2008 (сборка 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1445">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1447">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1447">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1448">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1448">Outlook</span></span>

- <span data-ttu-id="2bf7d-1449">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите условия поиска Outlook, вы получаете в предложениях наиболее подходящую электронную почту.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1449">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1452">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1452">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1453">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1453">Outlook</span></span>

- <span data-ttu-id="2bf7d-1454">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1454">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="2bf7d-1455">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1455">Do you want to download them anyway?</span></span> <span data-ttu-id="2bf7d-1456">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1456">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1457">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1457">Project</span></span>

- <span data-ttu-id="2bf7d-1458">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1458">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1459">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1459">Word</span></span>

- <span data-ttu-id="2bf7d-1460">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1460">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-17"></a><span data-ttu-id="2bf7d-1462">Версия 2008: 17 августа</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1462">Version 2008: August 17</span></span>
<span data-ttu-id="2bf7d-1463">*Версия 2008 (сборка 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1463">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1465">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1465">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1466">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1466">Outlook</span></span>

- <span data-ttu-id="2bf7d-1467">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1467">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="2bf7d-1468">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1468">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="2bf7d-1469">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1469">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="2bf7d-1470">Устранена проблема, из-за которой контекстное меню, вызываемое щелчком правой кнопки мыши, не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1470">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-11"></a><span data-ttu-id="2bf7d-1472">Версия 2008: 11 августа</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1472">Version 2008: August 11</span></span>
<span data-ttu-id="2bf7d-1473">*Версия 2008 (сборка 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1473">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="2bf7d-1474">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1474">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1476">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1476">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1477">Доступ</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1477">Access</span></span>

- <span data-ttu-id="2bf7d-1478">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1478">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="2bf7d-1479">Если у вас установлен Office 365, вам больше не требуется устанавливать наш распространяемый модуль ACE, чтобы предоставлять доступ к ACE за пределами экосистемы Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1479">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="2bf7d-1480">Поэтому пользователям Office 365 больше не нужен распространяемый модуль ACE и у них не должна возникать эта проблема.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1480">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="2bf7d-1481">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1481">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="2bf7d-1482">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1482">Excel</span></span>

- <span data-ttu-id="2bf7d-1483">Мы исправили проблему, когда при изменении порядка рядов диаграммы соответствующие флажки не были упорядочены по рядам.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1483">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="2bf7d-1484">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1484">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="2bf7d-1485">Исправлена проблема, из-за которой диаграммы не всегда обновлялись ожидаемым образом, если для книги был включен параметр ForceFullCalculation с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1485">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="2bf7d-1486">Исправлена проблема, из-за которой копия изображения с заливкой радиальным градиентом не соответствовала оригиналу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1486">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="2bf7d-1487">OneNote</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1487">OneNote</span></span>

- <span data-ttu-id="2bf7d-1488">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1488">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1489">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1489">Outlook</span></span>

- <span data-ttu-id="2bf7d-1490">Исправлена проблема с созданием нескольких профилей в Outlook из одного домена электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1490">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="2bf7d-1491">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1491">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="2bf7d-1492">Устранена проблема, приводившая к отсутствию значка блокировки в заголовке зашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1492">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="2bf7d-1493">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1493">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="2bf7d-1494">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1494">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2bf7d-1495">Исправлена проблема, из-за которой кнопка печати отображалась в отключенном состоянии даже при наличии у пользователя соответствующих разрешений на печать.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1495">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="2bf7d-1496">Устранена проблема, приводившая к удалению вложений из сообщений S/MIME при отправке в незашифрованном виде.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1496">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="2bf7d-1497">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1497">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="2bf7d-1498">Устранена проблема, из-за которой вложения повреждались при отправке незашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1498">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="2bf7d-1499">Устранена проблема, из-за которой получатели не могли сохранять сообщения с защищенными правами, даже если отправитель предоставил разрешение на сохранение.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1499">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="2bf7d-1500">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1500">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="2bf7d-1501">Исправлена проблема, из-за которой в Outlook некорректно отображались разрывы строк в содержимом файла Markdown.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1501">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="2bf7d-1502">Устранена проблема, приводившая к усечению некоторых подписей параметров расширенного поиска на некоторых языках.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1502">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1503">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1504">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1504">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="2bf7d-1505">Исправлена проблема с кнопкой Forms в PowerPoint, которая не позволяла создавать формы, если был запрещен доступ к Магазину Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1505">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-1506">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1506">Project</span></span>

- <span data-ttu-id="2bf7d-1507">Исправлена проблема, из-за которой задачи, перечисленные в представлении доски задач, не синхронизировались с диалоговым окном "Назначение ресурсов".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1507">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="2bf7d-1508">Исправлена проблема, из-за которой при попытке сохранить файл PDF или XPS из Project в библиотеке документов SharePoint ничего не происходило.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1508">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="2bf7d-1509">Исправлена проблема, из-за которой при копировании и вставке задачи с несколькими зависимостями не все зависимости копировались правильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1509">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="2bf7d-1510">Исправлена проблема, из-за которой для списка задач SharePoint могли быть отключены кнопки ленты на второй вкладке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1510">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="2bf7d-1511">Skype</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1511">Skype</span></span>

- <span data-ttu-id="2bf7d-1512">Оттенок кожи танцующего смайлика изменен на нейтральный цвет</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1512">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="2bf7d-1513">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1513">Visio</span></span>

- <span data-ttu-id="2bf7d-1514">После этого исправления, если пользователь приостанавливает выполнение команды удаления каким-либо способом (в данном случае с помощью надстройки), не возникает утечка памяти и компьютер не затрагивается.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1514">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1515">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1515">Word</span></span>

- <span data-ttu-id="2bf7d-1516">Исправлена проблема, из-за которой Word переставал отвечать на запросы после вставки текста и изображения в поле примечаний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1516">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="2bf7d-1517">Исправлена проблема, из-за которой копия изображения с заливкой радиальным градиентом не соответствовала оригиналу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1517">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="2bf7d-1518">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1518">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="2bf7d-1519">Исправлена проблема, из-за которой при добавлении примечаний для отслеживания изменений неожиданно открывалась область исправлений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1519">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="2bf7d-1520">Исправлена проблема, из-за которой команда "Корректор" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1520">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="2bf7d-1521">Исправлена проблема, из-за которой команда "Показать разметку" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1521">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="2bf7d-1522">Исправлена проблема, из-за которой кнопка "Создать примечание" отключалась после удаления последнего примечания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1522">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="2bf7d-1523">Исправлена проблема, из-за которой параметр "Определенные пользователи" для отслеживания изменений был отключен.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1523">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="2bf7d-1524">Исправлена проблема, из-за которой ссылки на документы не вставлялись в поле примечаний с помощью раскрывающегося списка "Ссылка" вкладки "Вставка".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1524">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="2bf7d-1525">Исправлены случайные зависания при открытии HTML-файлов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1525">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="2bf7d-1526">Исправлена проблема в пользовательском XML, из-за которой состояние примечаний могло исчезать при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1526">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="2bf7d-1527">Мы исправили проблему, когда после добавления изображения, содержащего гиперссылку, количество гиперссылок в коллекции гиперссылок VBA было наверно подсчитано.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1527">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="2bf7d-p193">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта. Эта проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p193">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>

- <span data-ttu-id="2bf7d-1530">Исправлена проблема, из-за которой после открытия пользователем нового окна приложения из панели задач и создания пустого документа создавались дополнительные файлы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1530">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="2bf7d-1531">Исправлена проблема, из-за которой в случае редактирования документа и утраты разрешений пользователь не уведомлялся о необходимости повторной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1531">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-august-05"></a><span data-ttu-id="2bf7d-1533">Версия 2007: 5 августа</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1533">Version 2007: August 05</span></span>
<span data-ttu-id="2bf7d-1534">*Версия 2007 (сборка 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1534">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1538">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1538">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1539">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1539">Outlook</span></span>

- <span data-ttu-id="2bf7d-1540">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1540">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="2bf7d-1541">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1541">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1542">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1542">Project</span></span>

- <span data-ttu-id="2bf7d-1543">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1543">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-29"></a><span data-ttu-id="2bf7d-1545">Версия 2007: 29 июля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1545">Version 2007: July 29</span></span>
<span data-ttu-id="2bf7d-1546">*Версия 2007 (сборка 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1546">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1548">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1548">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1549">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1549">Excel</span></span>

- <span data-ttu-id="2bf7d-1550">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 E5/A5 или Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1550">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="2bf7d-1551">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1551">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="2bf7d-1552">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1552">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="2bf7d-1553">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1553">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="2bf7d-1554">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1554">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1555">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1555">Outlook</span></span>

- <span data-ttu-id="2bf7d-1556">**Выбор места для поиска.** Новый раскрывающийся список области поиска позволит вам легко изменять параметры поиска и переключаться между текущей папкой и текущим почтовым ящиком.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1556">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="2bf7d-1557">Благодарим всех из Coming Soon, кто прислал отзывы о новом интерфейсе Search at Top.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1557">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="2bf7d-1558">Этот дизайн и обновление — результат этих отзывов!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1558">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1559">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1559">Word</span></span>

- <span data-ttu-id="2bf7d-1560">**Усовершенствована функция совместной работы с помощью современных комментариев.** Добавление примечаний к объектам, @упоминание коллег и завершение цепочек комментариев для повышения удобства совместной работы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1560">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="2bf7d-1561">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1561">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1564">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1564">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1565">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1565">Outlook</span></span>

- <span data-ttu-id="2bf7d-1566">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1566">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="2bf7d-1567">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1567">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="2bf7d-1568">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1568">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-27"></a><span data-ttu-id="2bf7d-1570">Версия 2007: 27 июля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1570">Version 2007: July 27</span></span>
<span data-ttu-id="2bf7d-1571">*Версия 2007 (сборка 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1571">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="2bf7d-1572">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1572">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="2bf7d-1573">Версия 2007: 20 июля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1573">Version 2007: July 20</span></span>
<span data-ttu-id="2bf7d-1574">*Версия 2007 (сборка 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1574">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="2bf7d-1575">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1575">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="2bf7d-1576">Версия 2007: 15 июля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1576">Version 2007: July 15</span></span>
<span data-ttu-id="2bf7d-1577">*Версия 2007 (сборка 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1577">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1579">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1579">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1580">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1580">Excel</span></span>

- <span data-ttu-id="2bf7d-1581">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1581">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2bf7d-1582">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1582">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1585">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1585">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1586">Доступ</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1586">Access</span></span>

- <span data-ttu-id="2bf7d-1587">Исправлена проблема, из-за которой диспетчер связанных таблиц запрашивал первичный ключ при обновлении связанной таблицы SQL.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1587">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="2bf7d-1588">Исправлена проблема, из-за которой запросы в редакторе запросов не отображались при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1588">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="2bf7d-1589">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1589">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="2bf7d-1590">Устранена проблема, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1590">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="2bf7d-1591">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1591">Excel</span></span>

- <span data-ttu-id="2bf7d-1592">Исправлена проблема, из-за которой URL-адреса, отличные от HTTP или HTTPS, не отображались в списке недавно использовавшихся.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1592">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="2bf7d-1593">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы возникает ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1593">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="2bf7d-1594">Устранена проблема, связанная с тем, что таблицы моделей данных, созданные в некоторых версиях Excel, не отображались в представлении "Предварительный просмотр таблицы" даже при отсутствии изменений запроса, связанного с таблицей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1594">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="2bf7d-1595">Устранена проблема, из-за которой переставали работать формулы при отключении параметра "Игнорировать тип ссылки" в диалоговом окне "Задать имя \ Применение имен".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1595">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="2bf7d-1596">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении книги в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1596">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="2bf7d-1597">Исправлена проблема, из-за которой книги были доступны только для чтения, если файл рекомендовался только для чтения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1597">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="2bf7d-1598">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы возникает ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1598">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="2bf7d-1599">Устранена проблема, из-за которой нельзя было правильно отформатировать основные линии сетки лепестковых диаграмм.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1599">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="2bf7d-1600">Исправлена проблема, из-за которой очистка расширенного фильтра данных могла привести к потере форматирования таблицы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1600">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="2bf7d-1601">Исправлена проблема, из-за которой в подписи к документу вместо имени внедренного PDF-документа отображался весь путь к нему.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1601">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="2bf7d-1602">Исправлена проблема, из-за которой мог произойти сбой после отключения облачного соединителя Wolfram с последующим сохранением и повторным открытием книги Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1602">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="2bf7d-1603">Исправлена проблема, вызывавшая сбой в результате загрузки Excel при включенной надстройке "Поиск решения".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1603">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-1604">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1604">Outlook</span></span>

- <span data-ttu-id="2bf7d-1605">Исправлена проблема, вызывавшая зависание приложения Outlook, когда в строке "Кому" было указано более 130 получателей. Кроме того, мы повысили производительность отрисовки текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1605">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="2bf7d-1606">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1606">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="2bf7d-1607">Исправлена проблема, из-за которой в области To Do для событий длительностью более двух дней указывалось одинаковое время окончания для всех последующих дней.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1607">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="2bf7d-1608">Исправлена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1608">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="2bf7d-1609">Исправлена проблема, из-за которой пользователи не могли "отправить как" или "отправить от имени" группы рассылки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1609">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="2bf7d-1610">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1610">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="2bf7d-p198">Исправлена проблема, из-за которой при закрытии ранее сохраненной встречи выводилось следующее сообщение об ошибке: "Не удалось сохранить элемент, так как он был изменен другим пользователем или в другом окне. Хотите сохранить копию элемента в папке по умолчанию?"</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p198">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="2bf7d-1613">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1613">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="2bf7d-1614">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1614">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="2bf7d-1615">Исправлена проблема, из-за которой у пользователей Outlook после использования общих календарей на несколько минут переставал обновляться список сообщений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1615">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="2bf7d-1616">Исправлена проблема, препятствовавшая отображению точного времени в напоминаниях календаря для собраний, до наступления которых осталось меньше недели.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1616">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="2bf7d-1617">Исправлена проблема, из-за которой вставка изображения в текст сообщения с последующим сохранением сообщения в виде черновика приводила к изменению размера изображения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1617">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="2bf7d-1618">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1618">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="2bf7d-1619">Исправлена проблема, из-за которой даты в мини-календаре не выделялись полужирным шрифтом для пользователей в Японии.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1619">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1620">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1620">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1621">Исправлена проблема, из-за которой в галерее совместного редактирования не обновлялся цветовой индикатор присутствия пользователя во время совместного редактирования в реальном времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1621">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="2bf7d-1622">Исправлена проблема, из-за которой при вставке HTML в область текста на слайде производилась вставка в текстовое поле, созданное в верхней части слайда.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1622">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="2bf7d-1623">Исправлена проблема, из-за которой возникало необработанное исключение при выделении всех слайдов в режиме докладчика и выходе из режима докладчика с помощью клавиш ALT+TAB, возврате в слайд-шоу и щелчке по команде "Завершить слайд-шоу".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1623">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-1624">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1624">Project</span></span>

- <span data-ttu-id="2bf7d-1625">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1625">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="2bf7d-1626">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1626">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="2bf7d-1627">Исправлена проблема, из-за которой мог возникнуть сбой при открытии определенных XML-файлов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1627">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="2bf7d-1628">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1628">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="2bf7d-1629">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости будут скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1629">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="2bf7d-1630">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1630">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="2bf7d-1631">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1631">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="2bf7d-1632">Исправлена проблема, из-за которой процент выполнения задачи был менее 100 %, если задачи с фиксированной длительностью выполнены на 100 %, но не указано фактическое окончание.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1632">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="2bf7d-1633">Устранена проблема, из-за которой при сбросе или обновлении базового плана могли изменяться показатели расходов или рабочих ресурсов тех или иных этапов бюджета, и базовый план мог содержать неправильные значения статей бюджета.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1633">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="2bf7d-1634">Исправлена проблема, из-за которой ссылки планировщика Project в средах GCC были отключены.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1634">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="2bf7d-1635">Исправлена проблема, из-за которой не удавалось открыть файл Project из библиотеки документов SharePoint, если библиотека находилась в современном режиме.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1635">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1636">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1636">Word</span></span>

- <span data-ttu-id="2bf7d-1637">Исправлена проблема, из-за которой не работала функция очистки форматирования в области примечаний с помощью кнопки "Очистить форматирование" на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1637">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="2bf7d-1638">Исправлена проблема, из-за которой текст, вставленный в изображение в формате SVG, был неудобочитаемым после добавления в файл Word, Excel или PowerPoint, сохранения и закрытия файла, а затем его повторного открытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1638">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="2bf7d-1639">Исправлена проблема, из-за которой изменение размера таблицы при скрытой линейке приводило к миганию других приложений, работающих на заднем фоне.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1639">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="2bf7d-1640">Исправлена проблема, из-за которой в режиме совместного редактирования ответы на примечания иногда не отображались в области примечаний, но отображались в области изменений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1640">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="2bf7d-1641">Исправлена проблема в режиме совместного редактирования: теперь при возникновении конфликта объединения изменений при том, что пользователь уже выбрал отмену изменений, вариант сохранения или отмены изменений больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1641">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="2bf7d-1642">Исправлена проблема, из-за которой цвет гиперссылки HTML отображался неправильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1642">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="2bf7d-1643">Исправлена проблема, из-за которой в тех случаях, когда в Word имелся список более чем 50 часто открываемых документов, после сохранения и открытия документа отображался журнал изменений, хотя никаких изменений в документ не вносилось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1643">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="2bf7d-1644">Исправлена проблема с автосохранением при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1644">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="2bf7d-1645">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1645">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1646">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1646">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1647">При закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1647">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="2bf7d-1648">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1648">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="2bf7d-1649">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1649">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-july-09"></a><span data-ttu-id="2bf7d-1651">Версия 2006: 09 июля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1651">Version 2006: July 09</span></span>
<span data-ttu-id="2bf7d-1652">*Версия 2006 (сборка 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1652">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1654">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1654">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1655">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1655">Excel</span></span>

- <span data-ttu-id="2bf7d-1656">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1656">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="2bf7d-1657">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1657">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="2bf7d-1658">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1658">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="2bf7d-1659">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1659">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="2bf7d-1660">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1660">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="2bf7d-1661">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1661">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="2bf7d-1662">**Сочетания клавиш в Excel.** Обновлены сочетания клавиш в Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1662">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1663">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1663">Outlook</span></span>

- <span data-ttu-id="2bf7d-1664">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1664">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="2bf7d-1665">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1665">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1668">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1668">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1669">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1669">Access</span></span>

- <span data-ttu-id="2bf7d-1670">Эта проблема устранена, и скоро вы сможете без проблем добавлять связанные таблицы SQL, содержащие поле удостоверения (например, счетчика), в Access.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1670">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="2bf7d-1671">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1671">Excel</span></span>

- <span data-ttu-id="2bf7d-1672">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1672">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1673">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1673">Outlook</span></span>

- <span data-ttu-id="2bf7d-1674">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1674">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-1675">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1675">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1676">Мы отправили часть AppV51 на доработку, чтобы исправить в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1676">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2bf7d-1677">В работе узла Office в Windows происходил сбой при активации надстройки и при значении типа TabProcGrowth в реестре равному "REG_SZ", а также при значении "0".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1677">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="2bf7d-1678">Значение TabProcGrowth в реестре может находиться в одном из указанных путей: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main. Это изменение исправит проблему.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1678">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-25"></a><span data-ttu-id="2bf7d-1680">Версия 2006: 25 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1680">Version 2006: June 25</span></span>
<span data-ttu-id="2bf7d-1681">*Версия 2006 (сборка 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1681">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1683">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1683">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="2bf7d-1684">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1684">Visio</span></span>

- <span data-ttu-id="2bf7d-1685">**Создание профессиональных диаграмм Visio в Excel.** Создавайте блок-схемы или организационные диаграммы, основанные на данных на листе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1685">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1688">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1688">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1689">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1689">Access</span></span>

- <span data-ttu-id="2bf7d-p203">Проблема устранена. Сообщите нам, если вы столкнетесь с другими проблемами, связанными с этим процессом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p203">This problem is now resolved. Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-1692">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1692">Outlook</span></span>

- <span data-ttu-id="2bf7d-1693"><span style="display:inline !important;">Исправлена проблема, из-за которой <span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">дату создания&nbsp; вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как &nbsp;1 января 4501 г.</span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-1693"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="2bf7d-1694"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Исправлена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-1694"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="2bf7d-1695"><span style="display:inline !important;">Исправлена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-1695"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="2bf7d-1696"><span style="display:inline !important;">Исправлена проблема, из-за которой поиск возможности предложения функции не возвращал результатов и не позволял пользователям поделиться идеями.</span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-1696"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-18"></a><span data-ttu-id="2bf7d-1698">Версия 2006: 18 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1698">Version 2006: June 18</span></span>
<span data-ttu-id="2bf7d-1699">*Версия 2006 (сборка 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1699">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1701">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1701">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1702">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1702">Excel</span></span>



- <span data-ttu-id="2bf7d-1703">**Сохранение в закрепленные папки.** Закрепление папок сделает сохранение файлов Office проще. Мы получили отзывы о том, что пользователям нужно больше удобства и контроля при сохранении новых файлов в папки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1703">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2bf7d-1704">Мы рады предоставить вам новую возможность: закрепление папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1704">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2bf7d-1705">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1705">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="2bf7d-1706">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1706">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1707">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1708">**Сохранение в закрепленные папки.** Закрепление папок сделает сохранение файлов Office проще. Мы получили отзывы о том, что пользователям нужно больше удобства и контроля при сохранении новых файлов в папки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1708">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2bf7d-1709">Мы рады предоставить вам новую возможность: закрепление папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1709">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2bf7d-1710">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1710">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="2bf7d-1711">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1711">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1712">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1712">Word</span></span>

- <span data-ttu-id="2bf7d-1713">**Сохранение в закрепленные папки.** Закрепление папок сделает сохранение файлов Office проще. Мы получили отзывы о том, что пользователям нужно больше удобства и контроля при сохранении новых файлов в папки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1713">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2bf7d-1714">Мы рады предоставить вам новую возможность: закрепление папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1714">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2bf7d-1715">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1715">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="2bf7d-1716">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1716">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1719">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1719">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1720">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1720">Excel</span></span>

- <span data-ttu-id="2bf7d-1721">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1721">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1722">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1722">Outlook</span></span>

- <span data-ttu-id="2bf7d-1723">Исправлена проблема, из-за которой не выполнялось действие при нажатии CTRL и щелчка мыши при включенных параметрах облака.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1723">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-1724">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1724">Project</span></span>

- <span data-ttu-id="2bf7d-1725">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1725">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-11"></a><span data-ttu-id="2bf7d-1727">Версия 2006: 11 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1727">Version 2006: June 11</span></span>
<span data-ttu-id="2bf7d-1728">*Версия 2006 (сборка 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1728">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1730">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1730">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1731">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1731">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1732">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1732">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="2bf7d-1733">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1733">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1734">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1734">Word</span></span>

- <span data-ttu-id="2bf7d-1735">**Сохранение текста в векторах.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Excel, Word и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1735">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1738">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1739">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1739">Excel</span></span>

- <span data-ttu-id="2bf7d-1740">Исправлена проблема, из-за которой Excel иногда завершал работу при взаимодействии с OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1740">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="2bf7d-1741">Исправлена проблема с неправильным применением пользовательских значений в осях на схемах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1741">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="2bf7d-1742">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1742">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="2bf7d-1743">Исправлена проблема, из-за которой в списке доступных принтеров имена принтеров повторялись.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1743">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="2bf7d-1744">Исправлена проблема, из-за которой увеличивалось время производительности для пользователей при удалении ими объединенных столбцов. </span><span class="sxs-lookup"><span data-stu-id="2bf7d-1744">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="2bf7d-1745">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, так что закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1745">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="2bf7d-1746">Исправлена проблема, из-за которой повреждалась память при управлении шрифтами между Excel и некоторыми сторонними приложениями специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1746">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="2bf7d-1747">Исправлена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1747">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2bf7d-1748">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1748">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="2bf7d-1749">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1749">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="2bf7d-1750">Исправлена проблема, из-за которой в Excel возникал сбой, когда надстройки запрашивали элементы хоста на листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1750">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="2bf7d-1751">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1751">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1752">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1752">Outlook</span></span>

- <span data-ttu-id="2bf7d-1753">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1753">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="2bf7d-1754">Исправлена проблема, из-за которой возникал сбой при просмотре шаблона во время создания нового сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1754">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="2bf7d-1755">Исправлена проблема, из-за которой пользователи не могли использовать общедоступные папки Exchange 2010 после Outlook версии 1911.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1755">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="2bf7d-1756">Исправлена проблема с отключенной кнопкой "Выбрать категорию" в календаре группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1756">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="2bf7d-1757">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1757">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2bf7d-1758">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1758">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="2bf7d-1759">Исправлена проблема, из-за которой пользователи не могли поделиться календарем с гостевым пользователем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1759">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="2bf7d-1760">Исправлена проблема, из-за которой элементы календаря, переходящие за полночь, отображались как события на весь день.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1760">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="2bf7d-1761">Исправлена проблема с отсутствием раскрывающегося списка Online Archive в свойствах папки у пользователей с мониторами высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1761">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="2bf7d-1762">Исправлена проблема, из-за которой событие Folder.BeforeItemMove срабатывало неправильно, когда пользователь перемещал элементы между папками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1762">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="2bf7d-1763">Исправлена проблема, из-за которой в Outlook возникал сбой, когда две надстройки добавляли кнопку в одну группу на ленте.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1763">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="2bf7d-1764">Исправлена проблема, из-за которой в работе Outlook возникал сбой при использовании гиперссылок в электронных сообщениях в формате обычного текста.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1764">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="2bf7d-1765">Исправлена проблема, приводившая к неспособности Outlook анализировать длинные имена файлов, закодированные с помощью RFC2231.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1765">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="2bf7d-1766">Исправлена проблема периодических зависаний в Outlook при использовании средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1766">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="2bf7d-1767">Исправлена проблема со сбоями в работе Outlook при наличии конфликтов в контактах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1767">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1768">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1769">Исправлена проблема с открытием файлов с сервера, на котором настроена проверка подлинности на основе форм.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1769">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="2bf7d-1770">Исправлена проблема, приводившая к ошибкам при сохранении файлов PowerPoint с внедренными диаграммами и книгами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1770">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="2bf7d-1771">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1771">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="2bf7d-1772">Исправлена проблема, из-за которой слайды не располагались по центру после изменения масштаба с помощью колесика мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1772">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="2bf7d-1773">Исправлена проблема, из-за которой сочетания клавиш и средства проверки орфографии не работают должным образом при использовании клавиатуры на английском языке для Швейцарии (QWERTZ).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1773">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="2bf7d-1774">Исправлена проблема, при которой закрытая пользователем область примечаний автоматически открывалась снова.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1774">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="2bf7d-1775">Исправлена проблема, из-за которой редактор слайдов одного слайда перекрывал следующий слайд.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1775">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-1776">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1776">Project</span></span>

- <span data-ttu-id="2bf7d-1777">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1777">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="2bf7d-1778">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1778">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="2bf7d-1779">Исправлена проблема, из-за которой Project аварийно завершал работу после нажатия кнопки "Параметры".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1779">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="2bf7d-1780">Исправлена проблема, препятствовавшая удалению или переназначению задач, утративших связи после удаления родительского плана.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1780">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="2bf7d-1781">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1781">Visio</span></span>

- <span data-ttu-id="2bf7d-1782">Исправлена регрессия в зависимом коде.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1782">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="2bf7d-1783">Теперь отрисовка изображений происходит службах Visio, работающих в SharePoint локально.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1783">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1784">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1784">Word</span></span>

- <span data-ttu-id="2bf7d-1785">Исправлена проблема несоответствия метки времени в панелях примечаний установленному в системе местному времени.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1785">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="2bf7d-1786">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1786">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="2bf7d-1787">Исправлена проблема, из-за которой не отображался текст, скопированный и вставленный в область примечаний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1787">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="2bf7d-1788">Исправлена проблема, из-за которой гиперссылки в примечаниях не работали.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1788">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="2bf7d-1789">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1789">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="2bf7d-1790">Исправлена проблема с отсутствием синхронизации примечаний между веб-приложением и классическим приложением.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1790">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="2bf7d-1791">Исправлена проблема, из-за которой выноска маркера примечания казалась размытой при масштабе 100 %.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1791">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="2bf7d-1792">Исправлена проблема, из-за которой при добавлении нового примечания в пустой документ ничего не происходит.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1792">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="2bf7d-1793">Исправлена проблема, из-за которой не работала вставка HTML в WordMail для календаря.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1793">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="2bf7d-1794">Исправлена проблема, из-за которой ответ на примечание в сеансе совместного редактирования иногда приводил к зависанию Word.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1794">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="2bf7d-1795">Исправлена проблема, из-за которой вставка или обновление индекса в документе, содержащем более сотни элементов, приводит к сбою работы приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1795">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="2bf7d-1796">Исправлена проблема, из-за которой включение политики "Двоичные документы и шаблоны Word 2007 и более поздних версий" вызывало сбой в некоторых случаях совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1796">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="2bf7d-1797">Исправлена проблема, из-за которой файлы, в которых есть настраиваемые значения, открывались очень медленно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1797">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="2bf7d-1798">Исправлена проблема, из-за которой файлы с длинными именами путей (больше 32 КБ) не открывались, а соответствующее сообщение об ошибке не отображалось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1798">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-1799">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1799">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1800">Мы изучили и устранили проблему, из-за которой развертывание Office 365 профессиональный плюс с помощью InTune было приостановлено после завершения работы ОС.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1800">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="2bf7d-1801">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1801">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2bf7d-1802">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1802">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-08"></a><span data-ttu-id="2bf7d-1804">Версия 2005: 08 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1804">Version 2005: June 08</span></span>
<span data-ttu-id="2bf7d-1805">*Версия 2005 (сборка 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1805">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1807">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1807">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1808">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1809">Исправлена проблема с диалоговым окном замены шрифтов, в котором в раскрывающемся списке вместо шрифтов, установленных в системе, отображались шрифты, использованные в презентации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1809">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-04"></a><span data-ttu-id="2bf7d-1811">Версия 2005: 04 июня</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1811">Version 2005: June 04</span></span>
<span data-ttu-id="2bf7d-1812">*Версия 2005 (сборка 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1812">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1814">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1814">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-1815">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1815">Access</span></span>

- <span data-ttu-id="2bf7d-1816">**Более высокая точность расширенных типов данных времени и дат.** Представляем новые и улучшенные типы данных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1816">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="2bf7d-1817">Чтобы повысить совместимость синтаксиса с SQL, а также точность и уровень детализации записей, включающих даты и время, мы реализуем новый тип данных DateTime2 в Access.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1817">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="2bf7d-1818">Этот тип данных будет включать больший диапазон дат (с 01.01.0001 по 31.12.9999) и более точное время (в наносекундах, а не секундах), с которыми вы сможете выполнять необходимые вычисления.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1818">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="2bf7d-1819">Чтобы включить новый тип, установите флажок "Новое поле" > "Расширенный формат даты и времени".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1819">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="2bf7d-1820">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1820">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="2bf7d-1821">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1821">Excel</span></span>

- <span data-ttu-id="2bf7d-1822">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1822">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="2bf7d-1823">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1823">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="2bf7d-1824">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1824">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1825">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1825">Outlook</span></span>

- <span data-ttu-id="2bf7d-1826">**Быстрое повторное открытие элементов из предыдущего сеанса Outlook.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1826">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1829">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1829">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1830">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1831">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1831">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-1832">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1832">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1833">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1833">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-29"></a><span data-ttu-id="2bf7d-1835">Версия 2005: 29 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1835">Version 2005: May 29</span></span>
<span data-ttu-id="2bf7d-1836">*Версия 2005 (сборка 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1836">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1838">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1838">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="2bf7d-1839">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1839">Excel</span></span>

- <span data-ttu-id="2bf7d-1840">**Представление листа.** Добавлена возможность сортировки и фильтрации при совместной работе с другими пользователями в классической версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1840">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1841">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1841">Outlook</span></span>

- <span data-ttu-id="2bf7d-1842">**Добавлены кнопки во всплывающие уведомления Outlook.** При использовании Outlook в Windows 10 кнопки быстрых действий теперь отображаются во всплывающих уведомлениях Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1842">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1845">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1845">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="2bf7d-1846">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1846">Outlook</span></span>

- <span data-ttu-id="2bf7d-1847">Исправлена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1847">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="2bf7d-1848">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1848">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-1849">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1849">Office Suite</span></span>

- <span data-ttu-id="2bf7d-p212">Узел Office в Windows завершал работу с ошибкой при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имел значение "0". Внесено изменение, устранившее проблему.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p212">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-21"></a><span data-ttu-id="2bf7d-1853">Версия 2005: 21 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1853">Version 2005: May 21</span></span>
<span data-ttu-id="2bf7d-1854">*Версия 2005 (сборка 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1854">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1858">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1858">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1859">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1859">Excel</span></span>

- <span data-ttu-id="2bf7d-1860">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1860">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="2bf7d-1861">В некоторых случаях при щелчке гиперссылки внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1861">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="2bf7d-1862">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1862">Outlook</span></span>

- <span data-ttu-id="2bf7d-1863">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1863">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="2bf7d-1864">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1864">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-14"></a><span data-ttu-id="2bf7d-1866">Версия 2005: 14 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1866">Version 2005: May 14</span></span>
<span data-ttu-id="2bf7d-1867">*Версия 2005 (сборка 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1867">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1869">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1869">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1870">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1870">Excel</span></span>

- <span data-ttu-id="2bf7d-1871">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1871">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1872">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1872">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1873">**Переключатель не нужен: наушники вам в помощь.** Используйте наушники Surface для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1873">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="2bf7d-1874">Важно! Чтобы использовать жесты для управления презентациями, необходимо связать наушники Surface с приложением Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1874">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="2bf7d-1875">Инструкции о начале работы с приложением Surface Audio на Windows 10 находятся здесь.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1875">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="2bf7d-1876">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1876">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="2bf7d-1877">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1877">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1878">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1878">Word</span></span>

- <span data-ttu-id="2bf7d-1879">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1879">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1882">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1882">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2bf7d-1883">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1883">Excel</span></span>

- <span data-ttu-id="2bf7d-1884">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1884">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="2bf7d-1885">Исправлена проблема, из-за которой в таблице данных диаграммы неправильно отображались значения оси дат.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1885">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="2bf7d-1886">Исправлена проблема, из-за которой разрывы страниц не удавалось отключить после перехода в режим макета страницы или страничный режим.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1886">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="2bf7d-1887">Исправлена проблема, из-за которой стили линий диаграммы могли пропадать после скрытия и повторного отображения столбцов с рядами данных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1887">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="2bf7d-1888">Исправлена проблема, из-за которой вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1888">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2bf7d-1889">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1889">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2bf7d-1890">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1890">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2bf7d-1891">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1891">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2bf7d-1892">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1892">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2bf7d-1893">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1893">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2bf7d-1894">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1894">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="2bf7d-1895">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1895">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="2bf7d-1896">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1896">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="2bf7d-1897">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1897">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="2bf7d-1898">Исправлена проблема, из-за которой пользовательское форматирование в сводных диаграммах не сохранялось при включенном параметре "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1898">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="2bf7d-1899">Исправлена проблема, из-за которой пользовательское форматирование одной точки данных в сводной диаграмме не сохранялось, если был выбран параметр "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1899">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="2bf7d-1900">Это исправление устраняет проблему, из-за которой символ "@", отправленный в CSV-файл, приводил к преобразованию строки после символа "@" в формулу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1900">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="2bf7d-1901">Исправлена проблема, из-за которой десятичные значения в функции ПОСЛЕДОВ округлялись неправильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1901">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="2bf7d-1902">OneNote</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1902">OneNote</span></span>

- <span data-ttu-id="2bf7d-1903">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1903">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1904">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1904">Outlook</span></span>

- <span data-ttu-id="2bf7d-1905">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1905">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="2bf7d-1906">Устранена проблема, из-за которой была отключена кнопка "Классифицировать" для календарей группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1906">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="2bf7d-1907">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1907">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="2bf7d-1908">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1908">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="2bf7d-1909">Исправлена проблема, приводившая к сбою загрузки очень длинных безопасных ссылок (из-за усечения), при переходе по ним в классическом клиенте Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1909">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="2bf7d-1910">Исправлена проблема, из-за которой папки Outlook с именами, содержащими двухбайтовые знаки (DBCS), периодически исчезали при синхронизации с сервером.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1910">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="2bf7d-1911">Чтобы это происходило, Outlook должен быть настроен с использованием учетной записи IMAP и работать в системе, языком которой выбран японский.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1911">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="2bf7d-1912">Решена проблема, из-за которой правила удаления, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, стали недействительными.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1912">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="2bf7d-1913">Исправлена проблема, которая приводила к удалению вложений при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1913">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="2bf7d-1914">Исправлена проблему, из-за которой в собраниях, с моменты которых прошло более двух месяцев, не отображалась тема собрания в Помощнике по планированию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1914">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="2bf7d-1915">Устранена проблема, из-за которой пользователи видели текст сообщения неполностью при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1915">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2bf7d-1916">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1916">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1917">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-1918">Исправлена следующая проблема: если пользователь создавал комментарий, не публикуя его, и закрывал область комментариев, затем открывал новое окно, просматривал несколько слайдов, закрывал окно и повторно открывал область комментариев в исходной презентации, черновик комментария был недоступен.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1918">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="2bf7d-1919">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1919">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-1920">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1920">Project</span></span>

- <span data-ttu-id="2bf7d-1921">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1921">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="2bf7d-1922">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1922">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="2bf7d-1923">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1923">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2bf7d-1924">Исправлена проблема, из-за которой при подключении Project к Project Web App и использовании запятой в качестве десятичного разделителя метод добавления объектов TaskDependencies завершался сбоем, если добавлен параметр Lag.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1924">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-1925">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1925">Word</span></span>

- <span data-ttu-id="2bf7d-1926">Исправлена проблема, из-за которой иногда не удавалось вставить комментарии в документ в режиме совместной работы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1926">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="2bf7d-1927">Это изменение исправляет ошибку, из-за которой карточка "Люди" мерцала при щелчке по @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1927">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="2bf7d-p215">При включении параметра "Показывать закладки" закладки не показывались. Проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p215">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>

- <span data-ttu-id="2bf7d-p216">Исправлена следующая проблема: пользователю, закрывавшему документ с черновиком комментариев, предлагалось подтвердить закрытие без сохранения черновика комментариев, но если пользователь выбирал вариант "Отмена", документ закрывался вместо того, чтобы остаться открытым.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p216">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="2bf7d-1932">Исправлена проблема, возникающая при копировании и вставке заголовков.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1932">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="2bf7d-1933">Исправлена проблема, из-за которой при переводе опубликованного комментария возникала ошибка "Сбой вставки переведенного текста".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1933">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="2bf7d-1934">Это изменение устраняет проблему, из-за которой при включении параметра "Показывать коды полей вместо их значений" текст с гиперссылками может не отображаться.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1934">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="2bf7d-p217">В веб-представлении или иммерсивном средстве чтения щелчок по подсказке приводил к прокручиванию в верхнюю часть представления, хотя она уже была просмотрена. Эта проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p217">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>

- <span data-ttu-id="2bf7d-1937">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1937">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-1938">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1938">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1939">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1939">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="2bf7d-1940">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1940">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="2bf7d-1941">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1941">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="2bf7d-1942">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1942">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2bf7d-1943">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1943">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-11"></a><span data-ttu-id="2bf7d-1945">Версия 2004: 11 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1945">Version 2004: May 11</span></span>
<span data-ttu-id="2bf7d-1946">*Версия 2004 (сборка 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1946">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1948">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1948">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-1949">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1949">Excel</span></span>

- <span data-ttu-id="2bf7d-1950">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1950">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-1951">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1951">Outlook</span></span>

- <span data-ttu-id="2bf7d-1952">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1952">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="2bf7d-1953">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1953">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="2bf7d-1954">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1954">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="2bf7d-1955">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1955">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="2bf7d-1956">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1956">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-1957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1957">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-p220">**Доклады с анимированными изображениями GIF.** Анимированные изображения GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими. [Подробнее](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p220">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.  [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-1960">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1960">Word</span></span>

- <span data-ttu-id="2bf7d-1961">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1961">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1964">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1964">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1965">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1965">Outlook</span></span>

- <span data-ttu-id="2bf7d-1966">Устранена проблема, из-за которой у пользователей возникали сбои при отображении всплывающих уведомлений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1966">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-04"></a><span data-ttu-id="2bf7d-1968">Версия 2004: 04 мая</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1968">Version 2004: May 04</span></span>
<span data-ttu-id="2bf7d-1969">*Версия 2004 (сборка 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1969">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1971">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1971">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1972">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1972">Outlook</span></span>

- <span data-ttu-id="2bf7d-1973">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1973">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="2bf7d-1974">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1974">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="2bf7d-1975">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1975">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="2bf7d-1976">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1976">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1979">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1979">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2bf7d-1980">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1980">Office Suite</span></span>

- <span data-ttu-id="2bf7d-1981">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1981">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-29"></a><span data-ttu-id="2bf7d-1983">Версия 2004: 29 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1983">Version 2004: April 29</span></span>
<span data-ttu-id="2bf7d-1984">*Версия 2004 (сборка 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1984">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-1986">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1986">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1987">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1987">Outlook</span></span>

- <span data-ttu-id="2bf7d-1988">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1988">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1991">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1991">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1992">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1992">Outlook</span></span>

- <span data-ttu-id="2bf7d-1993">Исправлена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1993">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-25"></a><span data-ttu-id="2bf7d-1995">Версия 2004: 25 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1995">Version 2004: April 25</span></span>
<span data-ttu-id="2bf7d-1996">*Версия 2004 (сборка 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1996">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-1998">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1998">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-1999">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-1999">Outlook</span></span>

- <span data-ttu-id="2bf7d-2000">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2000">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-2001">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2001">Project</span></span>

- <span data-ttu-id="2bf7d-2002">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2002">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-2003">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2003">Office Suite</span></span>

- <span data-ttu-id="2bf7d-2004">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2004">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-21"></a><span data-ttu-id="2bf7d-2006">Версия 2004: 21 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2006">Version 2004: April 21</span></span>
<span data-ttu-id="2bf7d-2007">*Версия 2004 (сборка 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2007">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2009">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2009">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-2010">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2010">Outlook</span></span>

- <span data-ttu-id="2bf7d-2011">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2011">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2bf7d-2012">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2012">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-15"></a><span data-ttu-id="2bf7d-2014">Версия 2004: 15 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2014">Version 2004: April 15</span></span>
<span data-ttu-id="2bf7d-2015">*Версия 2004 (сборка 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2015">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2017">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2017">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2018">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2018">Excel</span></span>

- <span data-ttu-id="2bf7d-2019">**Поддержка коннектора Facebook заканчивается:** Начиная с апреля 2020 года Excel больше не будет поддерживать подключения к внешним данным, которые используют коннектор Facebook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2019">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2020">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2020">Outlook</span></span>

- <span data-ttu-id="2bf7d-2021">**Новая опция, позволяющая отключить предложения @ упоминания при составлении писем в Outlook:** Считаете ли вы средство @ упоминания более раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2021">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="2bf7d-2022">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2022">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2023">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2023">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2024">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2024">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2025">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2025">Word</span></span>

- <span data-ttu-id="2bf7d-2026">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2026">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="2bf7d-2027">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2027">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2030">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2030">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-2031">Доступ</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2031">Access</span></span>

- <span data-ttu-id="2bf7d-2032">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2032">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="2bf7d-2033">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2033">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="2bf7d-2034">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2034">Excel</span></span>

- <span data-ttu-id="2bf7d-2035">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2035">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="2bf7d-2036">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2036">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2bf7d-2037">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2037">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2bf7d-2038">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2038">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2bf7d-2039">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2039">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="2bf7d-2040">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2040">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="2bf7d-2041">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2041">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="2bf7d-2042">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2042">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="2bf7d-2043">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2043">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="2bf7d-2044">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2044">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="2bf7d-2045">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2045">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2046">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2046">Outlook</span></span>

- <span data-ttu-id="2bf7d-2047">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2047">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="2bf7d-2048">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2048">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="2bf7d-2049">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2049">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="2bf7d-2050">Устранена проблема, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2050">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2bf7d-2051">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2051">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2bf7d-2052">Устранена проблема, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2052">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="2bf7d-2053">Устранена проблема, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2053">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="2bf7d-2054">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2054">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="2bf7d-2055">Устранена проблема, из-за которой кнопка «Сохранить в облаке» отсутствовала в инструментах вложений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2055">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2bf7d-2056">Устранена проблема, из-за которой пользователи не могли добавлять подпись при ответе на сообщение с цифровыми правами из окна инспектора, когда у пользователя нет разрешения Владельца на сообщение, на которое он отвечает.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2056">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="2bf7d-2057">Устранена проблема, из-за которой пользователи не могли добавлять дополнительные вложения из веб-сайта в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2057">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="2bf7d-2058">Устранена проблема, из-за которой дата «последнего изменения» в файле обновлялась при добавлении вложения в сообщение или при сохранении вложения из сообщения путем его перетаскивания (в отличие от меню).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2058">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="2bf7d-2059">Устранена проблема, из-за которой при вводе в расширенной области поиска не удавалось запустить поиск, вместо этого требовалось, чтобы пользователи нажимали кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2059">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="2bf7d-2060">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2060">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="2bf7d-2061">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2061">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2062">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2062">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2063">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2063">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="2bf7d-2064">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2064">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="2bf7d-2065">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2065">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="2bf7d-2066">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2066">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-2067">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2067">Project</span></span>

- <span data-ttu-id="2bf7d-2068">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2068">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2bf7d-2069">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2069">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2bf7d-2070">Исправлена ошибка, из-за которой событие Visual Basic Applications (VBA) ProjectBeforeTaskChange не срабатывало, когда пользователь нажимал кнопку «Деактивировать», найденную на ленте задач в группе планирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2070">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="2bf7d-2071">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2071">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="2bf7d-2072">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2072">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="2bf7d-2073">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2073">This behavior has been fixed.</span></span>

- <span data-ttu-id="2bf7d-2074">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2074">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="2bf7d-2075">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2075">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="2bf7d-2076">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2076">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="2bf7d-2077">Исправлена ошибка, из-за которой при печати временной шкалы с использованием календаря хиджры месяц пропускался или дублировался в представлении печати.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2077">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="2bf7d-2078">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2078">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="2bf7d-2079">Исправлена ошибка, из-за которой, если выполняется CustomFieldValueListGetItem 'и таблица поиска для настраиваемого поля не существует, создается пустая таблица поиска, хотя это не должно быть.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2079">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="2bf7d-2080">Когда данные редактора или преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2080">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="2bf7d-2081">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2081">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2082">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2082">Word</span></span>

- <span data-ttu-id="2bf7d-2083">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2083">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="2bf7d-2084">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2084">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="2bf7d-2085">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2085">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="2bf7d-2086">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2086">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="2bf7d-2087">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2087">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="2bf7d-2088">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2088">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="2bf7d-2089">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2089">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="2bf7d-2090">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2090">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="2bf7d-2091">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2091">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="2bf7d-2092">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2092">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="2bf7d-2093">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2093">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="2bf7d-2094">Мы исправили проблему, из-за которой выравнивание слова в документе зашифровывается при попытке изменить его после печати с использованием Quick Print.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2094">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2bf7d-2095">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2095">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2bf7d-2096">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2096">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="2bf7d-2097">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2097">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-14"></a><span data-ttu-id="2bf7d-2099">Версия 2003: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2099">Version 2003: April 14</span></span>
<span data-ttu-id="2bf7d-2100">*Версия 2003 (сборка 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2100">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="2bf7d-2101">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2101">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

- <span data-ttu-id="2bf7d-2103">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2103">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-09"></a><span data-ttu-id="2bf7d-2105">Версия 2003: 9 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2105">Version 2003: April 09</span></span>
<span data-ttu-id="2bf7d-2106">*Версия 2003 (сборка 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2106">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2108">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2108">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2109">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2109">Excel</span></span>

- <span data-ttu-id="2bf7d-2110">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2110">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2bf7d-2111">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2111">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2112">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2112">Outlook</span></span>

- <span data-ttu-id="2bf7d-2113">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2113">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2bf7d-2114">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2114">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2115">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2115">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2116">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2116">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2bf7d-2117">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2117">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2118">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2118">Word</span></span>

- <span data-ttu-id="2bf7d-2119">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2119">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2bf7d-2120">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2120">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-03"></a><span data-ttu-id="2bf7d-2124">Версия 2003: 3 апреля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2124">Version 2003: April 03</span></span>
<span data-ttu-id="2bf7d-2125">*Версия 2003 (сборка 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2125">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2127">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2127">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2128">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2128">Excel</span></span>

- <span data-ttu-id="2bf7d-2129">В некоторых случаях при использовании приложения VBA не работала оценка определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2129">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2130">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2130">Outlook</span></span>

- <span data-ttu-id="2bf7d-2131">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2131">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-2132">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2132">Project</span></span>

- <span data-ttu-id="2bf7d-2133">При изменении данных предшественника или последователя в представлении формы возникало дополнительное событие ProjectBeforeTaskChangeevent.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2133">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2134">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2134">Word</span></span>

- <span data-ttu-id="2bf7d-2135">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2135">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-31"></a><span data-ttu-id="2bf7d-2137">Версия 2003: 31 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2137">Version 2003: March 31</span></span>
<span data-ttu-id="2bf7d-2138">*Версия 2003 (сборка 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2138">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2140">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2140">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-2141">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2141">Access</span></span>

- <span data-ttu-id="2bf7d-2142">**Область задач "Добавление таблиц":** новая область задач Access "Добавление таблиц" наконец доступна!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2142">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="2bf7d-2143">Эта функция позволяет легко выбирать несколько таблиц, которые нужно добавить или удалить в окне запроса, не переходя к диалоговому окну "Отображение таблиц" для запросов и представления связей.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2143">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="2bf7d-2144">Она также включает новую вкладку "Ссылки" для отображения связанных таблиц, поле поиска для фильтрации текущего списка, действие перетаскивания и многое другое!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2144">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2147">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2147">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2bf7d-2148">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2148">Project</span></span>

- <span data-ttu-id="2bf7d-2149"><span style="display:inline !important;">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-2149"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-25"></a><span data-ttu-id="2bf7d-2151">Версия 2003: 25 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2151">Version 2003: March 25</span></span>
<span data-ttu-id="2bf7d-2152">*Версия 2003 (сборка 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2152">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="2bf7d-2153">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2153">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="2bf7d-2154">Версия 2003: 23 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2154">Version 2003: March 23</span></span>
<span data-ttu-id="2bf7d-2155">*Версия 2003 (сборка 12624,20296)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2155">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="2bf7d-2156">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2156">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="2bf7d-2157">Версия 2003: 21 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2157">Version 2003: March 21</span></span>
<span data-ttu-id="2bf7d-2158">*Версия 2003 (сборка 12624,20276)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2158">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2160">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2160">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-2161">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2161">Outlook</span></span>

- <span data-ttu-id="2bf7d-2162">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2162">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="2bf7d-2163">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2163">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="2bf7d-2164">**Визуальное обновление календаря:** в прошлом году мы представили вам обновленную почту, а в этом году настала очередь календаря!</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2164">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="2bf7d-2165">Обновления свежие, но знакомые, поэтому, как опытный пользователь Outlook, вы можете сразу же подключиться и стать более продуктивным.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2165">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2166">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2166">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2167">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2167">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-16"></a><span data-ttu-id="2bf7d-2169">Версия 2003: 16 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2169">Version 2003: March 16</span></span>
<span data-ttu-id="2bf7d-2170">*Версия 2003 (сборка 12624,20224)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2170">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2172">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2172">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2173">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2173">Excel</span></span>

- <span data-ttu-id="2bf7d-2174">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2174">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2175">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2175">Outlook</span></span>

- <span data-ttu-id="2bf7d-2176">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2176">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2177">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2178">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2178">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2179">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2179">Word</span></span>

- <span data-ttu-id="2bf7d-2180">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2180">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-2181">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2181">Office Suite</span></span>

- <span data-ttu-id="2bf7d-2182">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2182">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="2bf7d-2183">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2183">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2186">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2186">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2187">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2187">Excel</span></span>

- <span data-ttu-id="2bf7d-2188">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2188">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2189">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2189">Outlook</span></span>

- <span data-ttu-id="2bf7d-2190">Устранена проблема, из-за которой пользователи могли видеть процесс Outlook, задерживающийся в диспетчере задач после выхода.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2190">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-10"></a><span data-ttu-id="2bf7d-2192">Версия 2003: 10 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2192">Version 2003: March 10</span></span>
<span data-ttu-id="2bf7d-2193">*Версия 2003 (сборка 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2193">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="2bf7d-2194">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2194">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)
### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2196">Обновления компонентов</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2196">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2197">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2197">Excel</span></span>
- <span data-ttu-id="2bf7d-2198">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2198">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2bf7d-2199">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2199">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2200">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2200">PowerPoint</span></span>
- <span data-ttu-id="2bf7d-2201">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2201">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2bf7d-2202">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2202">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="2bf7d-2203">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2203">Word</span></span>
- <span data-ttu-id="2bf7d-2204">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2204">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2bf7d-2205">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2205">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2206">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2206">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2207">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2207">Excel</span></span>

- <span data-ttu-id="2bf7d-2208">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2208">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2bf7d-2209">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2209">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="2bf7d-2210">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2210">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="2bf7d-2211">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2211">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2bf7d-2212">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2212">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="2bf7d-2213">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2213">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="2bf7d-2214">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2214">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="2bf7d-2215">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2215">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2bf7d-2216">Это изменение исправляет ошибку во время выполнения в объектной модели и потенциальный сбой приложения (Excel, Word), если надстройки запрашивают элементы узла в документах или листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2216">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="2bf7d-2217">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2217">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="2bf7d-2218">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2218">Outlook</span></span>

- <span data-ttu-id="2bf7d-2219">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не сохранялось на сервере Exchange Server и возникал конфликт.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2219">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="2bf7d-2220">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2220">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="2bf7d-2221">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2221">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="2bf7d-2222">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2222">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="2bf7d-2223">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2223">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="2bf7d-2224">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2224">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="2bf7d-2225">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря &quot;Параметры доступности&quot;.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2225">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="2bf7d-2226">Исправлена проблема, которая могла привести к появлению оповещения &quot;К сожалению, не удалось открыть элемент&quot; при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2226">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="2bf7d-2227">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2227">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="2bf7d-2228">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2228">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="2bf7d-2229">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2229">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="2bf7d-2230">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2230">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2231">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2232">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2232">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="2bf7d-2233">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2233">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="2bf7d-2234">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2234">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2bf7d-2235">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2235">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="2bf7d-2236">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2236">Project</span></span>

- <span data-ttu-id="2bf7d-2237">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2237">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="2bf7d-2238">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2238">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2bf7d-2239">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2239">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="2bf7d-2240">Visio</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2240">Visio</span></span>

- <span data-ttu-id="2bf7d-p238">В разделе "Данные фигуры" области сведений о фигуре выводились противоречивые сведения о файла при открытии в классической версии Visio. Проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p238">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop. It has now been fixed.</span></span>

- <span data-ttu-id="2bf7d-2243">Точечные рисунки, импортированные в версиях до 2016, не отображались из-за некоторых проверок безопасности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2243">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="2bf7d-2244">Эта проблема исправлена в подписке на Visio.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2244">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2245">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2245">Word</span></span>

- <span data-ttu-id="2bf7d-2246">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2246">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="2bf7d-2247">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2247">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="2bf7d-2248">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2248">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2bf7d-p240">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега. Проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p240">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

- <span data-ttu-id="2bf7d-2251">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2251">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="2bf7d-2252">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2252">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="2bf7d-2253">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2253">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="2bf7d-2254">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2254">Office Suite</span></span>

- <span data-ttu-id="2bf7d-2255">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2255">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="2bf7d-2256">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2256">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="2bf7d-2257">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2257">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="2bf7d-2258">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2258">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="2bf7d-2259">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2259">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-05"></a><span data-ttu-id="2bf7d-2261">Версия 2002: 5 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2261">Version 2002: March 05</span></span>
<span data-ttu-id="2bf7d-2262">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2262">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="2bf7d-2263">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2263">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="2bf7d-2264">Версия 2002: 4 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2264">Version 2002: March 04</span></span>
<span data-ttu-id="2bf7d-2265">*Версия 2002 (сборка 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2265">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2267">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2267">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="2bf7d-2268">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2268">Project</span></span>
- <span data-ttu-id="2bf7d-2269">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2269">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-2270">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2270">Office Suite</span></span>
- <span data-ttu-id="2bf7d-2271">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2271">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-01"></a><span data-ttu-id="2bf7d-2273">Версия 2002: 1 марта</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2273">Version 2002: March 01</span></span>
<span data-ttu-id="2bf7d-2274">*Версия 2002 (сборка 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2274">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2275">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2275">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-2276">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2276">Outlook</span></span>

- <span data-ttu-id="2bf7d-2277">Исправлена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2277">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-24"></a><span data-ttu-id="2bf7d-2279">Версия 2002: 24 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2279">Version 2002: February 24</span></span>
<span data-ttu-id="2bf7d-2280">*Версия 2002 (сборка 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2280">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="2bf7d-2281">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2281">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="2bf7d-2282">Версия 2002: 22 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2282">Version 2002: February 22</span></span>
<span data-ttu-id="2bf7d-2283">*Версия 2002 (сборка 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2283">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="2bf7d-2284">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2284">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="2bf7d-2285">Версия 2002: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2285">Version 2002: February 21</span></span>
<span data-ttu-id="2bf7d-2286">*Версия 2002 (сборка 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2286">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2288">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2288">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-2289">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2289">Access</span></span>

- <span data-ttu-id="2bf7d-2290">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2290">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="2bf7d-2291">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2291">Search and replace text in SQL View.</span></span> <span data-ttu-id="2bf7d-2292">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2292">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2293">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2293">Outlook</span></span>

- <span data-ttu-id="2bf7d-2294">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2294">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="2bf7d-2295">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2295">Outlook now detects this and helps you get connected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2298">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2298">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2bf7d-2299">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2299">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="2bf7d-2300">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-2300">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="2bf7d-2301">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2301">Outlook</span></span>

- <span data-ttu-id="2bf7d-2302">Исправлена проблема, из-за которой запятые в поле месторасположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2302">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="2bf7d-2303">Исправлена проблема, которая могла приводить к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2303">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="2bf7d-2304">Исправлена проблема, из-за которой приложение Outlook неожиданно синхронизировало всю почту, даже если ползунок синхронизация настроен на меньшее значение.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2304">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="2bf7d-2305">Исправлена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке &quot;От&quot; отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2305">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="2bf7d-2306"><span style="display:inline !important;">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span></span><span class="sxs-lookup"><span data-stu-id="2bf7d-2306"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-18"></a><span data-ttu-id="2bf7d-2308">Версия 2002: 18 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2308">Version 2002: February 18</span></span>
<span data-ttu-id="2bf7d-2309">*Версия 2002 (сборка 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2309">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="2bf7d-2310">Версия 2002:11 февраля</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2310">Version 2002: February 11</span></span>
<span data-ttu-id="2bf7d-2311">*Версия 2002 (сборка 12527,20092)*</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2311">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="2bf7d-2312">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2312">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2bf7d-2314">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2314">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2bf7d-2315">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2315">Outlook</span></span>

- <span data-ttu-id="2bf7d-2316">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2316">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="2bf7d-2317">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2317">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="2bf7d-2318">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2318">Word</span></span>

- <span data-ttu-id="2bf7d-2319">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2319">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2bf7d-2320">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2320">Office Suite</span></span>

- <span data-ttu-id="2bf7d-2321">**Более понятные значки строки состояния:** значки строки состояния стали понятнее.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2321">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2bf7d-2324">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2324">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2bf7d-2325">Access</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2325">Access</span></span>

- <span data-ttu-id="2bf7d-2326">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2326">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2bf7d-2327">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2327">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2bf7d-p246">Это обновление исправляет проблему, из-за которой при использовании объекта ADODB.Recorder в коде VB необоснованно появлялось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-p246">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2bf7d-2330">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2330">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="2bf7d-2331">Excel</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2331">Excel</span></span>

- <span data-ttu-id="2bf7d-2332">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2332">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="2bf7d-2333">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2333">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="2bf7d-2334">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2334">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="2bf7d-2335">Outlook</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2335">Outlook</span></span>

- <span data-ttu-id="2bf7d-2336">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2336">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="2bf7d-2337">Папки, сохраненные в разделе "Избранное" в области навигации слева, могут периодически исчезать.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2337">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="2bf7d-2338">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2338">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="2bf7d-2339">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2339">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2bf7d-2340">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2340">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="2bf7d-2341">Исправлена проблема, из-за которой срок действия почты в соответствии с политикой хранения будет иметь две метки.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2341">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="2bf7d-2342">Один показывает, что срок действия письма истекает через один день, а другой - что срок его действия истекает через два дня.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2342">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="2bf7d-2343">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2343">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2bf7d-2344">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2344">PowerPoint</span></span>

- <span data-ttu-id="2bf7d-2345">Исправлена проблема, из-за которой рукописные фрагменты могли не отображаться полностью или пропускаться при использовании анимации рукописного ввода в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2345">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="2bf7d-2346">Исправлена ошибка, из-за которой после закрытия файла PowerPoint не сразу удалял его из коллекции презентаций, если были запущены какие-либо обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2346">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="2bf7d-2347">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2347">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="2bf7d-2348">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2348">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="2bf7d-2349">Project</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2349">Project</span></span>

- <span data-ttu-id="2bf7d-2350">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2350">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="2bf7d-2351">Word</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2351">Word</span></span>

- <span data-ttu-id="2bf7d-2352">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2352">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="2bf7d-2353">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2353">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="2bf7d-2354">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2354">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="2bf7d-2355">Исправлена ошибка, из-за которой форматирование курсива терялось после редактирования комментария, выделения курсивом текста и последующей публикации.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2355">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="2bf7d-2356">Исправлена проблема, из-за которой подсказки примечаний не были видны в режиме чтения с помощью инвертированного цвета страницы.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2356">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="2bf7d-2357">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2357">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="2bf7d-2358">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2358">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="2bf7d-2359">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2359">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="2bf7d-2360">Исправлена ошибка, из-за которой команды комментария (Редактировать комментарий, Ответить на комментарий, Удалить комментарий, Разрешить комментарий) в контекстном меню комментариев не отображались.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2360">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2bf7d-2361">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2361">Office Suite</span></span>

- <span data-ttu-id="2bf7d-2362">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2362">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="2bf7d-2363">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="2bf7d-2363">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)
