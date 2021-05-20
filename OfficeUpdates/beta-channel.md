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
ms.openlocfilehash: 289486b3abf7736825f15311524a1d87295ed78e
ms.sourcegitcommit: 830bba63e278d32baeaaaa5323e3fd25cf6b7c24
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52563345"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="556ca-103">Заметки о выпуске для бета-канала</span><span class="sxs-lookup"><span data-stu-id="556ca-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="556ca-104">Эта статья содержит заметки о выпуске для сборок бета-канала приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows.</span><span class="sxs-lookup"><span data-stu-id="556ca-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="556ca-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="556ca-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="556ca-106">Обратите внимание, что развертывание возможностей (а иногда даже исправлений) в бета-канале зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="556ca-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="556ca-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="556ca-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="556ca-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="556ca-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="556ca-p102">Мы вносим ряд изменений в каналы обновления приложений Microsoft 365, в том числе добавляем канал обновления (Ежемесячный корпоративный канал) и переименовываем существующие каналы обновления. Дополнительные сведения см. в [этой статье](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="556ca-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="556ca-111">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок.</span><span class="sxs-lookup"><span data-stu-id="556ca-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="556ca-112">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="556ca-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2106-may-14"></a><span data-ttu-id="556ca-115">Версия 2106: 14 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-115">Version 2106: May 14</span></span>
<span data-ttu-id="556ca-116">*Версия 2106 (сборка 14107.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-116">*Version 2106 (Build 14107.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-118">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-118">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-119">Outlook</span></span>

- <span data-ttu-id="556ca-120">Исправлена проблема, из-за которой сообщения с действиями либо постоянно обновлялись, либо возвращались к заголовкам после скачивания при запуске в режиме "Загружать только заголовки".</span><span class="sxs-lookup"><span data-stu-id="556ca-120">We fixed an issue that caused users to see actionable messages either constantly refreshing or reverting back to headers after download when running in Download Headers Only mode.</span></span>


- <span data-ttu-id="556ca-121">Исправлена проблема, из-за которой средство выбора людей в Outlook разворачивалось вверх, а не вниз для пользователей с бессрочной лицензией.</span><span class="sxs-lookup"><span data-stu-id="556ca-121">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


- <span data-ttu-id="556ca-122">Исправлена проблема, из-за которой пользователи личных доменов видели предупреждающее сообщение о разрешениях при вставке ссылки в сообщение электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-122">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-123">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-123">Word</span></span>

- <span data-ttu-id="556ca-124">Исправлена проблема, из-за которой нажатие сочетаний клавиш, например CTRL+SHIFT+@, не приводило к появлению символа с диакритическим знаком (в данном случае — "å").</span><span class="sxs-lookup"><span data-stu-id="556ca-124">We fixed an issue where pressing key combinations such as ctrl + shift + @ would not produce the expected accented character( in this case, 'å').</span></span>


- <span data-ttu-id="556ca-125">Исправлена проблема, связанная со сжатием изображений.</span><span class="sxs-lookup"><span data-stu-id="556ca-125">We fixed an issue related to image compression.</span></span>


- <span data-ttu-id="556ca-126">Исправлена проблема, из-за которой не удавалось скопировать почтовое вложение в приложение, отличное от Word, если имя файла включало символы DBCS.</span><span class="sxs-lookup"><span data-stu-id="556ca-126">We fixed an issue where copying a mail attachment to an application other than Word would fail if the filename included DBCS characters.</span></span>


- <span data-ttu-id="556ca-127">Исправлена проблема, из-за которой Word иногда отображал границу вокруг текста, которая не нужна.</span><span class="sxs-lookup"><span data-stu-id="556ca-127">We fixed an issue where Word sometimes displayed a border around text that should have not been there.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-128">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-128">Office Suite</span></span>

- <span data-ttu-id="556ca-129">Исправлена проблема, из-за которой в OneDrive отображалось сообщение об ошибке слияния, когда конфликт слияния отсутствовал.</span><span class="sxs-lookup"><span data-stu-id="556ca-129">We fixed an issue where OneDrive would display a merge error message when there was indeed no merge conflict.</span></span>


- <span data-ttu-id="556ca-130">Исправлена проблема, связанная с z-порядком объектов SVG при преобразовании в фигуры.</span><span class="sxs-lookup"><span data-stu-id="556ca-130">We fixed an issue related to z-order of SVG objects when converted to shapes.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2106-may-07"></a><span data-ttu-id="556ca-132">Версия 2106: 07 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-132">Version 2106: May 07</span></span>
<span data-ttu-id="556ca-133">*Версия 2106 (Сборка 14029.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-133">*Version 2106 (Build 14029.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-135">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-136">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-136">Excel</span></span>

- <span data-ttu-id="556ca-137">Исправлена проблема, из-за которой диспетчеру имен не удавалось открывать книги с большим количеством скрытых имен.</span><span class="sxs-lookup"><span data-stu-id="556ca-137">We fixed an issue that prevented the Name Manager from opening books with a large number of hidden names.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-138">Outlook</span></span>

- <span data-ttu-id="556ca-139">Исправлена проблема, из-за которой пользователи видели копии всех отправленных элементов в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="556ca-139">We fixed an issue that caused users to see copies of all of their sent items appearing in their Outbox folder.</span></span>


- <span data-ttu-id="556ca-140">Исправлена проблема, из-за которой Outlook неожиданно закрывался при использовании чтения вслух с другими версиями Windows.</span><span class="sxs-lookup"><span data-stu-id="556ca-140">We fixed an issue that caused Outlook closed unexpectedly when using read aloud with other versions of Windows.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-141">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-141">Word</span></span>

- <span data-ttu-id="556ca-142">Исправлена проблема, из-за которой Word неожиданно закрывался при использовании чтения вслух с другими версиями Windows.</span><span class="sxs-lookup"><span data-stu-id="556ca-142">We fixed an issue that caused Word closed unexpectedly when using read aloud with other versions of Windows.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-april-30"></a><span data-ttu-id="556ca-144">Версия 2105: 30 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-144">Version 2105: April 30</span></span>
<span data-ttu-id="556ca-145">*Версия 2105 (сборка 14026.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-145">*Version 2105 (Build 14026.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-147">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-147">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-148">Outlook</span></span>

- <span data-ttu-id="556ca-149">**Средство проверки доступности посылает напоминание при отправке сообщений в большие списки рассылки или внешним пользователям:** Мы добавили функцию автоматического напоминания с помощью подсказки о возможных нарушениях доступности при отправке сообщения широкой аудитории, внешним пользователям и т. д. Эти параметры доступны в разделе специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="556ca-149">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span>

### <a name="visio"></a><span data-ttu-id="556ca-150">Visio</span><span class="sxs-lookup"><span data-stu-id="556ca-150">Visio</span></span>

- <span data-ttu-id="556ca-151">**Трафареты и фигуры AWS:** мы добавили трафареты с новейшими фигурами AWS, которые помогут вам создавать схемы.</span><span class="sxs-lookup"><span data-stu-id="556ca-151">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="556ca-152">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-152">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)

### <a name="word"></a><span data-ttu-id="556ca-153">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-153">Word</span></span>

- <span data-ttu-id="556ca-154">**Цели создания текстов:** цели создания текстов в WinWord</span><span class="sxs-lookup"><span data-stu-id="556ca-154">**Writing Goals:** Writing Goals for WinWord</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-157">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-157">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-158">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-158">Excel</span></span>

- <span data-ttu-id="556ca-159">Исправлена проблема, из-за которой Excel неожиданно закрывался при перемещении по комментариям в области комментариев.</span><span class="sxs-lookup"><span data-stu-id="556ca-159">We fixed an issue that cause Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="556ca-160">Исправлена проблема, из-за которой форматирование даты отображалось неправильно в некоторых языках при использовании надстроек.</span><span class="sxs-lookup"><span data-stu-id="556ca-160">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="556ca-161">Исправлена проблема, которая в определенных ситуациях могла привести к неожиданному закрытию Excel при использовании специальной вставки с форматами.</span><span class="sxs-lookup"><span data-stu-id="556ca-161">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-162">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-162">Project</span></span>

- <span data-ttu-id="556ca-163">Исправлена проблема, из-за которой изменения, внесенные с помощью мастеров планирования, не всегда регистрировались событиями изменений.</span><span class="sxs-lookup"><span data-stu-id="556ca-163">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="556ca-164">Исправлена проблема, из-за которой пользователи не могли удалять проекты из пула ресурсов.</span><span class="sxs-lookup"><span data-stu-id="556ca-164">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-165">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-165">Word</span></span>

- <span data-ttu-id="556ca-166">Исправлена проблема, из-за которой форматирование текста остается прежним после удаления гиперссылки.</span><span class="sxs-lookup"><span data-stu-id="556ca-166">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="556ca-167">Исправлена проблема, из-за которой комментарии не отображались после фильтрации по людям.</span><span class="sxs-lookup"><span data-stu-id="556ca-167">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="556ca-168">Исправлена проблема, из-за которой Word не удавалось выполнить слияние почты с базой данных Access.</span><span class="sxs-lookup"><span data-stu-id="556ca-168">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="556ca-169">Исправлена проблема, которая позволяла свернуть поля в документе, содержащем несколько столбцов.</span><span class="sxs-lookup"><span data-stu-id="556ca-169">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="556ca-170">Исправлена проблема, вызывавшая неправильное изображение некоторых символов в ячейках таблицы при наличии в документе комментариев.</span><span class="sxs-lookup"><span data-stu-id="556ca-170">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="556ca-171">Исправлена проблема, из-за которой формат файла менялся при сохранении документов с включенной надстройкой AIP.</span><span class="sxs-lookup"><span data-stu-id="556ca-171">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="556ca-172">Исправлена проблема, из-за которой Word зависал при попытке редактировать поля.</span><span class="sxs-lookup"><span data-stu-id="556ca-172">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="556ca-173">Исправлена проблема, из-за которой пользователям не предлагалось сохранять документы при использовании команды (а не сочетания клавиш CTRL+S).</span><span class="sxs-lookup"><span data-stu-id="556ca-173">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="556ca-174">Исправлена проблема, из-за которой метка конфиденциальности исчезала из файла в Word после отправки файла в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="556ca-174">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-175">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-175">Office Suite</span></span>

- <span data-ttu-id="556ca-176">Исправлена проблема, из-за которой кнопка диктовки приобретала неправильное выравнивание при добавлении комментариев в документ.</span><span class="sxs-lookup"><span data-stu-id="556ca-176">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="556ca-177">Исправлена проблема, из-за которой при использовании режима высокой контрастности в течение продолжительного периода времени Outlook неожиданно закрывался.</span><span class="sxs-lookup"><span data-stu-id="556ca-177">We fixed an issue where using High Contrast mode for extended periods of time would cause Outlook to close unexpectedly.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-april-23"></a><span data-ttu-id="556ca-179">Версия 2105: 23 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-179">Version 2105: April 23</span></span>
<span data-ttu-id="556ca-180">*Версия 2105 (сборка 14014.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-180">*Version 2105 (Build 14014.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-182">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-182">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-183">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-183">Excel</span></span>

- <span data-ttu-id="556ca-184">**Импорт данных из динамических массивов.** Теперь вы можете импортировать, формировать и обновлять данные из динамических массивов в текущей книге.</span><span class="sxs-lookup"><span data-stu-id="556ca-184">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="556ca-185">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-185">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-188">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-188">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-189">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-189">Excel</span></span>

- <span data-ttu-id="556ca-p105">Исправлена проблема, приводившая к тому, что файлы, сохраненные в более поздней версии Excel, неправильно загружались в более ранних версиях Excel из-за таких функций, как IFERROR и XLOOKUP, добавленных в Excel начиная с версии Office 2007.</span><span class="sxs-lookup"><span data-stu-id="556ca-p105">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel fail to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="556ca-192">Исправлена проблема, из-за которой некоторые файлы иногда не открывались в защищенном просмотре.</span><span class="sxs-lookup"><span data-stu-id="556ca-192">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="556ca-193">Исправлена проблема, из-за которой в строке состояния не указывалось состояние готовности для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="556ca-193">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-194">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-194">Outlook</span></span>

- <span data-ttu-id="556ca-195">Исправлена проблема, вызывавшая сбой разрешения имен при отправке от имени другого пользователя и разрешении в адресной книге, не являющейся глобальным списком адресов.</span><span class="sxs-lookup"><span data-stu-id="556ca-195">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-196">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-196">Word</span></span>

- <span data-ttu-id="556ca-197">Исправлена проблема, из-за которой замещающий текст обрезался в примечаниях при использовании языков с написанием справа налево.</span><span class="sxs-lookup"><span data-stu-id="556ca-197">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-198">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-198">Office Suite</span></span>

- <span data-ttu-id="556ca-199">Исправлена проблема, из-за которой гиперссылки, включая цифры, прерывались при составлении сообщения в Outlook на языке с написанием справа налево.</span><span class="sxs-lookup"><span data-stu-id="556ca-199">We fixed an issue where hyperlinks including digits would be broken when composing a message in Outlook in a right-to-left language.</span></span>


- <span data-ttu-id="556ca-200">Исправлена проблема, из-за которой элементы SVG отображались неправильно.</span><span class="sxs-lookup"><span data-stu-id="556ca-200">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-april-16"></a><span data-ttu-id="556ca-202">Версия 2105: 16 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-202">Version 2105: April 16</span></span>
<span data-ttu-id="556ca-203">*Версия 2105 (сборка 14007.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-203">*Version 2105 (Build 14007.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-205">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-205">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-206">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-206">Excel</span></span>

- <span data-ttu-id="556ca-207">Исправлена проблема, вызывавшая сбой Excel при использовании 32-разрядной версии Office в 64-разрядной версии Windows.</span><span class="sxs-lookup"><span data-stu-id="556ca-207">We fixed an issue that caused Excel to crash when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="556ca-208">Исправлена проблема, из-за которой экранный диктор неправильно читал свойства двух кнопок на вкладке "Колонтитулы" диалогового окна "Параметры страницы".</span><span class="sxs-lookup"><span data-stu-id="556ca-208">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-209">PowerPoint</span></span>

- <span data-ttu-id="556ca-210">Исправлена проблема со связанным рисунками.</span><span class="sxs-lookup"><span data-stu-id="556ca-210">We fixed an issue related to linked pictures.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2105-april-09"></a><span data-ttu-id="556ca-212">Версия 2105: 9 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-212">Version 2105: April 09</span></span>
<span data-ttu-id="556ca-213">*Версия 2105 (сборка 14002.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-213">*Version 2105 (Build 14002.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-215">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-215">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-216">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-216">Excel</span></span>

- <span data-ttu-id="556ca-217">**Лента специальных возможностей.** Все инструменты, необходимые для создания контента со специальными возможностями, доступны в одном месте — на ленте специальных возможностей!</span><span class="sxs-lookup"><span data-stu-id="556ca-217">**Accessibility ribbon:** Find all of the tools you need to create accessible content in one place - the Accessibility ribbon!</span></span>

### <a name="word"></a><span data-ttu-id="556ca-218">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-218">Word</span></span>

- <span data-ttu-id="556ca-219">**Проверка правописания теперь доступна для выделенного текста в документе.** Благодаря этим изменениям теперь можно проверять правописание и другие интеллектуальные рекомендации по стилю только для выделенного текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-219">**Proofing is now available for selected text within the Document:** With these changes you can now review spelling, grammar and other intelligent writing suggestions for just the selected text.</span></span> <span data-ttu-id="556ca-220">Кроме того, вы можете просматривать рекомендации для всего документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-220">Additionally you can also review suggestions for the whole document.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-april-02"></a><span data-ttu-id="556ca-222">Версия 2104: 2 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-222">Version 2104: April 02</span></span>
<span data-ttu-id="556ca-223">*Версия 2104 (сборка 13929.20016)*</span><span class="sxs-lookup"><span data-stu-id="556ca-223">*Version 2104 (Build 13929.20016)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-225">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-225">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-226">Outlook</span></span>

- <span data-ttu-id="556ca-227">**Предлагаемые ответы в Outlook для Windows.** Когда вы получаете сообщение электронной почты, позволяющее ответить кратко, Outlook может предложить три ответа, которыми можно воспользоваться всего несколькими щелчками мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-227">**Suggested Replies in Outlook for Windows:** When you receive an email message that can be answered by a short response, Outlook can suggest three responses you can use to reply with just a couple of clicks.</span></span>

- <span data-ttu-id="556ca-228">**Включение улучшений общего календаря.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="556ca-228">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="556ca-229">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="556ca-229">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-232">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-233">Доступ</span><span class="sxs-lookup"><span data-stu-id="556ca-233">Access</span></span>

- <span data-ttu-id="556ca-234">Исправлена проблема, из-за которой невозможно было завершить работу до разблокировки указателя, когда внешнее приложение запрашивало интерфейс со специальными возможностями.</span><span class="sxs-lookup"><span data-stu-id="556ca-234">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-235">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-235">Word</span></span>

- <span data-ttu-id="556ca-p108">Из-за этой ошибки определенные политики не учитывались в Office (группа шаблонов была видна на домашней странице, когда они должны были быть отключены).</span><span class="sxs-lookup"><span data-stu-id="556ca-p108">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="556ca-238">Исправлена проблема с автосохранением.</span><span class="sxs-lookup"><span data-stu-id="556ca-238">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="556ca-239">Исправлена ошибка в методе Application.OnTime, из-за которой он мог запускаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="556ca-239">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-march-26"></a><span data-ttu-id="556ca-241">Версия 2104: 26 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-241">Version 2104: March 26</span></span>
<span data-ttu-id="556ca-242">*Версия 2104 (сборка 13919.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-242">*Version 2104 (Build 13919.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-244">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-244">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-245">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-245">Outlook</span></span>

- <span data-ttu-id="556ca-246">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при синхронизации изменений в иерархии папок.</span><span class="sxs-lookup"><span data-stu-id="556ca-246">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-247">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-247">Word</span></span>

- <span data-ttu-id="556ca-248">Исправлена проблема, из-за которой при копировании и вставке стиль вставленного текста отличался.</span><span class="sxs-lookup"><span data-stu-id="556ca-248">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-249">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-249">Office Suite</span></span>

- <span data-ttu-id="556ca-250">Исправлена проблема с производительностью, связанная с итерацией текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-250">Fixed a performance issue related to iteration of text.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-march-19"></a><span data-ttu-id="556ca-252">Версия 2104: 19 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-252">Version 2104: March 19</span></span>
<span data-ttu-id="556ca-253">*Версия 2104 (сборка 13913.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-253">*Version 2104 (Build 13913.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-255">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-255">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-256">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-256">Access</span></span>

- <span data-ttu-id="556ca-257">Это изменение исправляет проблему, из-за которой в некоторых случаях при выполнении запроса к серверу SQL Server могло возникать сообщение об ошибке, указывающее на "недопустимое состояние курсора".</span><span class="sxs-lookup"><span data-stu-id="556ca-257">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="556ca-258">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-258">Excel</span></span>

- <span data-ttu-id="556ca-259">Исправлена проблема, не позволявшая вставлять формулы на защищенном листе.</span><span class="sxs-lookup"><span data-stu-id="556ca-259">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-260">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-260">Project</span></span>

- <span data-ttu-id="556ca-261">Исправлена проблема, из-за которой при использовании формата даты W4/4 в средстве выбора даты мог отображаться неправильный день и год.</span><span class="sxs-lookup"><span data-stu-id="556ca-261">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-262">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-262">Office Suite</span></span>

- <span data-ttu-id="556ca-263">Исправлена проблема с поддержкой GDI+ LineJoinMiterClipped в Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-263">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2104-march-12"></a><span data-ttu-id="556ca-265">Версия 2104: 12 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-265">Version 2104: March 12</span></span>
<span data-ttu-id="556ca-266">*Версия 2104 (сборка 13906.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-266">*Version 2104 (Build 13906.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-268">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-268">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="556ca-269">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-269">PowerPoint</span></span>

- <span data-ttu-id="556ca-270">**Вставка видео Flipgrid в PowerPoint.** PowerPoint теперь поддерживает вставку видео Flipgrid на слайды.</span><span class="sxs-lookup"><span data-stu-id="556ca-270">**Insert Flipgrid videos in PowerPoint:** PowerPoint will now support insertion of Flipgrid videos in slides.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-273">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-273">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-274">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-274">Excel</span></span>

- <span data-ttu-id="556ca-275">Исправлена проблема, из-за которой гиперссылки, созданные с помощью функции ГИПЕРССЫЛКА, не работали, если файл был сохранен в формате PDF.</span><span class="sxs-lookup"><span data-stu-id="556ca-275">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-276">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-276">Word</span></span>

- <span data-ttu-id="556ca-277">Исправлена проблема с комментариями во время совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="556ca-277">We fixed an issue with comments during coauthoring.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-march-05"></a><span data-ttu-id="556ca-279">Версия 2103: 5 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-279">Version 2103: March 05</span></span>
<span data-ttu-id="556ca-280">*Версия 2103 (сборка 13901.20036)*</span><span class="sxs-lookup"><span data-stu-id="556ca-280">*Version 2103 (Build 13901.20036)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-282">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-282">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-283">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-283">Excel</span></span>

- <span data-ttu-id="556ca-284">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="556ca-284">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="556ca-285">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="556ca-285">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="556ca-286">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="556ca-286">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-287">PowerPoint</span></span>

- <span data-ttu-id="556ca-288">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="556ca-288">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="556ca-289">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="556ca-289">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="556ca-290">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="556ca-290">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="556ca-291">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-291">Word</span></span>

- <span data-ttu-id="556ca-292">**Автосохранение и совместное редактирование конфиденциальных зашифрованных документов:** не жертвуйте производительностью ради безопасности.</span><span class="sxs-lookup"><span data-stu-id="556ca-292">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="556ca-293">При использовании Microsoft Information Protection документы, зашифрованные с помощью меток конфиденциальности, теперь можно автоматически сохранять и совместно редактировать с другими пользователями в режиме реального времени, как и незашифрованные документы.</span><span class="sxs-lookup"><span data-stu-id="556ca-293">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="556ca-294">Требуется согласие клиента (дополнительные сведения: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="556ca-294">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-297">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-297">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-298">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-298">Excel</span></span>

- <span data-ttu-id="556ca-299">Исправлена проблема, из-за которой шрифт неожиданно менялся при использовании знака умножения или деления с японским шрифтом.</span><span class="sxs-lookup"><span data-stu-id="556ca-299">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="556ca-300">Теперь продолжится использование того же шрифта, если он поддерживает символ.</span><span class="sxs-lookup"><span data-stu-id="556ca-300">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="556ca-301">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="556ca-301">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="556ca-302">Исправлена проблема, из-за которой неожиданно отображались некоторые заметки при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="556ca-302">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-303">Outlook</span></span>

- <span data-ttu-id="556ca-304">Исправлена проблема, из-за которой символы, отличные от ASCII, некорректно экспортировались в CSV-файл.</span><span class="sxs-lookup"><span data-stu-id="556ca-304">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="556ca-305">Исправлена проблема, из-за которой пользователи не могли найти группу контактов с помощью проверки имен при создании сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-305">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-306">PowerPoint</span></span>

- <span data-ttu-id="556ca-307">Исправлена проблема, из-за которой стрелки на графиках отображались неправильно в режиме слайд-шоу PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-307">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-308">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-308">Word</span></span>

- <span data-ttu-id="556ca-309">Исправлена проблема, из-за которой открытие файла, защищенного с помощью метки Microsoft Information Protection (MIP), могло зависать на неопределенное время, если пользователь не вошел в систему с удостоверением, имеющим доступ к защищенной метке MIP.</span><span class="sxs-lookup"><span data-stu-id="556ca-309">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="556ca-310">Открытие будет принудительно отменено, чтобы отобразить запрос на вход. Только после этого получится открыть файл.</span><span class="sxs-lookup"><span data-stu-id="556ca-310">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="556ca-311">Устранение этой проблемы возможно путем отображения запроса на вход во время открытия или загрузки.</span><span class="sxs-lookup"><span data-stu-id="556ca-311">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="556ca-312">Исправлена проблема при использовании диктофона в новой версии комментирования Word. Теперь кнопка диктофона правильно включается и отключается в карточке комментария.</span><span class="sxs-lookup"><span data-stu-id="556ca-312">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="556ca-313">Исправлена проблема, из-за которой при диктовке в документе между словами не вставлялись пробелы.</span><span class="sxs-lookup"><span data-stu-id="556ca-313">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="556ca-314">Исправлена проблема при публикации многострочных комментариев, введенных справа налево, из-за которой вторая и последующие строки выравнивались по левому краю, а не по правому.</span><span class="sxs-lookup"><span data-stu-id="556ca-314">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="556ca-315">Исправлена проблема, из-за которой проверка орфографии переключалась между двумя разными контекстными меню проверки орфографии.</span><span class="sxs-lookup"><span data-stu-id="556ca-315">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="556ca-316">Исправлена проблема, из-за которой в столбцах мог быть перекрывающийся текст.</span><span class="sxs-lookup"><span data-stu-id="556ca-316">We fixed an issue where columns might have overlapping text.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-february-26"></a><span data-ttu-id="556ca-318">Версия 2103: 26 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-318">Version 2103: February 26</span></span>
<span data-ttu-id="556ca-319">*Версия 2103 (сборка 13819.20006)*</span><span class="sxs-lookup"><span data-stu-id="556ca-319">*Version 2103 (Build 13819.20006)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-321">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-321">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-322">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-322">Excel</span></span>

- <span data-ttu-id="556ca-323">Исправлена проблема, не позволявшая пользователям экспортировать книгу Excel в PDF-файл.</span><span class="sxs-lookup"><span data-stu-id="556ca-323">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="556ca-324">Исправлена проблема потери некоторого форматирования при копировании листа во время совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="556ca-324">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-325">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-325">Outlook</span></span>

- <span data-ttu-id="556ca-326">Исправлена проблема, из-за которой дублировались вложения при удалении защиты DRM.</span><span class="sxs-lookup"><span data-stu-id="556ca-326">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-327">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-327">Project</span></span>

- <span data-ttu-id="556ca-328">Исправлена проблема, из-за которой при сохранении проекта из веб-приложения Project в локальный файл могли неправильно создаваться разбиения задач.</span><span class="sxs-lookup"><span data-stu-id="556ca-328">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="556ca-329">Это могло происходить при использовании календаря задач с нестандартным рабочим временем.</span><span class="sxs-lookup"><span data-stu-id="556ca-329">This would happen if a task calendar with non-standard working times was being used.</span></span>


- <span data-ttu-id="556ca-330">Исправлена проблема, из-за которой при вырезании суммарной задачи не появлялось предупреждение об удалении подзадач, если столбец индикатора отсутствовал в первом столбце.</span><span class="sxs-lookup"><span data-stu-id="556ca-330">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="556ca-331">Исправлена проблема, из-за которой в создаваемом назначении могли применяться неправильные единицы доступности ресурса, если пользователь выбирал функцию "Добавление себя в задачу" в своем расписании.</span><span class="sxs-lookup"><span data-stu-id="556ca-331">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-332">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-332">Word</span></span>

- <span data-ttu-id="556ca-333">Исправлена проблема с выравниванием нескольких комментариев.</span><span class="sxs-lookup"><span data-stu-id="556ca-333">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="556ca-334">Исправлена проблема с сочетаниями клавиш области задач "Прочесть вслух".</span><span class="sxs-lookup"><span data-stu-id="556ca-334">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-335">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-335">Office Suite</span></span>

- <span data-ttu-id="556ca-336">Места в OneDrive теперь фильтруются в соответствии с настройками групповой политики.</span><span class="sxs-lookup"><span data-stu-id="556ca-336">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="556ca-337">Исправлена проблема, связанная с отсутствием отклика при загрузке изображений EMF.</span><span class="sxs-lookup"><span data-stu-id="556ca-337">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-february-19"></a><span data-ttu-id="556ca-339">Версия 2103: 19 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-339">Version 2103: February 19</span></span>
<span data-ttu-id="556ca-340">*Версия 2103 (сборка 13811.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-340">*Version 2103 (Build 13811.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-342">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-342">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-343">Outlook</span></span>

- <span data-ttu-id="556ca-344">Исправлена проблема, из-за которой дублировались вложения при удалении защиты DRM.</span><span class="sxs-lookup"><span data-stu-id="556ca-344">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-345">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-345">Project</span></span>

- <span data-ttu-id="556ca-346">Исправлена проблема, из-за которой при вырезании суммарной задачи не появлялось предупреждение об удалении подзадач, если столбец индикатора отсутствовал в первом столбце.</span><span class="sxs-lookup"><span data-stu-id="556ca-346">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="556ca-347">Исправлена проблема, из-за которой в создаваемом назначении могли применяться неправильные единицы доступности ресурса, если пользователь выбирал функцию "Добавление себя в задачу" в своем расписании.</span><span class="sxs-lookup"><span data-stu-id="556ca-347">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-348">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-348">Word</span></span>

- <span data-ttu-id="556ca-349">Исправлена проблема с сочетаниями клавиш области задач "Прочесть вслух".</span><span class="sxs-lookup"><span data-stu-id="556ca-349">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2103-february-12"></a><span data-ttu-id="556ca-351">Версия 2103: 12 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-351">Version 2103: February 12</span></span>
<span data-ttu-id="556ca-352">*Версия 2103 (сборка 13806.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-352">*Version 2103 (Build 13806.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-354">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-354">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-355">Outlook</span></span>

- <span data-ttu-id="556ca-356">**Создание предложений (Кому\Копия\СК) на основе Поиска (Майкрософт):** добавление пользователей в строку "Кому"\"Копия" теперь выполняется на платформе Поиска (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="556ca-356">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>

- <span data-ttu-id="556ca-357">**Диктовка доступна на большем количестве языков.** Теперь диктовка поддерживает семь новых языков: хинди, русский, польский, португальский (Португалия), корейский, тайский и китайский (Тайвань).</span><span class="sxs-lookup"><span data-stu-id="556ca-357">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="556ca-358">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-358">Word</span></span>

- <span data-ttu-id="556ca-359">**Диктовка доступна на большем количестве языков.** Теперь диктовка поддерживает семь новых языков: хинди, русский, польский, португальский (Португалия), корейский, тайский и китайский (Тайвань).</span><span class="sxs-lookup"><span data-stu-id="556ca-359">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-362">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-362">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-363">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-363">Excel</span></span>

- <span data-ttu-id="556ca-364">Устранена проблема, из-за которой Excel иногда неожиданно закрывался при попытке показать карточку типов данных, поскольку не мог получить изображение.</span><span class="sxs-lookup"><span data-stu-id="556ca-364">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-365">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-365">PowerPoint</span></span>

- <span data-ttu-id="556ca-366">Устранена проблема с повторением анимаций и звуковыми закладками.</span><span class="sxs-lookup"><span data-stu-id="556ca-366">Fixes an issue with looping animations and audio bookmarks.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-367">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-367">Project</span></span>

- <span data-ttu-id="556ca-368">Устранена проблема, из-за которой задача, выполненная на 100%, могла вернуться к выполнению на 99%.</span><span class="sxs-lookup"><span data-stu-id="556ca-368">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>

- <span data-ttu-id="556ca-369">Устранена проблема, из-за которой Project иногда неожиданно закрывался при запуске JAWS и переходе в диалоговое окно сведений о задаче.</span><span class="sxs-lookup"><span data-stu-id="556ca-369">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-370">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-370">Word</span></span>

- <span data-ttu-id="556ca-371">Устранена проблема с автосохранением.</span><span class="sxs-lookup"><span data-stu-id="556ca-371">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="556ca-372">Устранена проблема с разрешением конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="556ca-372">We fixed an issue in resolving conflicts while in coauthoring.</span></span>




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-february-05"></a><span data-ttu-id="556ca-374">Версия 2102: 5 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-374">Version 2102: February 05</span></span>
<span data-ttu-id="556ca-375">*Версия 2102 (сборка 13801.20004)*</span><span class="sxs-lookup"><span data-stu-id="556ca-375">*Version 2102 (Build 13801.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-377">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-377">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-378">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-378">Access</span></span>

- <span data-ttu-id="556ca-379">Теперь выбранные вкладки будут отображаться четче в Access.</span><span class="sxs-lookup"><span data-stu-id="556ca-379">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="556ca-380">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-380">Excel</span></span>

- <span data-ttu-id="556ca-381">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="556ca-381">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="556ca-382">Устранена проблема, из-за которой при нажатии клавиши ВВОД на определенных клавиатурах для Android вместо перехода к следующей ячейке добавлялась новая строка.</span><span class="sxs-lookup"><span data-stu-id="556ca-382">We fixed an issue where pressing Enter with certain keyboards on Android would add a new line rather than moving to the next cell.</span></span>


- <span data-ttu-id="556ca-383">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="556ca-383">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-384">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-384">Outlook</span></span>

- <span data-ttu-id="556ca-385">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="556ca-385">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-386">PowerPoint</span></span>

- <span data-ttu-id="556ca-387">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="556ca-387">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-388">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-388">Word</span></span>

- <span data-ttu-id="556ca-389">Устранена проблема, из-за которой изображения сохраняли свои пропорции во время операции обрезки.</span><span class="sxs-lookup"><span data-stu-id="556ca-389">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="556ca-390">Устранена проблема, из-за которой примечание может быть обрезано с ссылками.</span><span class="sxs-lookup"><span data-stu-id="556ca-390">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="556ca-391">Устранена проблема с режимом обработки конфликтов при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="556ca-391">We fixed an issue with conflict mode when coauthoring.</span></span>


- <span data-ttu-id="556ca-392">Устранена проблема с сохранением в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="556ca-392">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="556ca-393">Устранена проблема с экспортом документов Word в PDF.</span><span class="sxs-lookup"><span data-stu-id="556ca-393">We fixed an issue in exporting Word document to PDF.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-394">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-394">Office Suite</span></span>

- <span data-ttu-id="556ca-395">Устранена проблема, из-за которой в некоторых случаях в Office отображались метки конфиденциальности для одной учетной записи, в которую был выполнен вход, тогда как нужно было для другой.</span><span class="sxs-lookup"><span data-stu-id="556ca-395">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-january-29"></a><span data-ttu-id="556ca-397">Версия 2102: 29 января</span><span class="sxs-lookup"><span data-stu-id="556ca-397">Version 2102: January 29</span></span>
<span data-ttu-id="556ca-398">*Версия 2102 (сборка 13721.20008)*</span><span class="sxs-lookup"><span data-stu-id="556ca-398">*Version 2102 (Build 13721.20008)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-400">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-400">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-401">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-401">Excel</span></span>

- <span data-ttu-id="556ca-402">Исправлена проблема, из-за которой приложение Excel неожиданно завершало работу при добавлении имени в диалоговом окне "Присвоение имени".</span><span class="sxs-lookup"><span data-stu-id="556ca-402">We fixed a problem where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-403">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-403">Outlook</span></span>

- <span data-ttu-id="556ca-404">Исправлена проблема, из-за которой значок шифрования не отображался для сообщений, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="556ca-404">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-405">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-405">Project</span></span>

- <span data-ttu-id="556ca-406">Исправлена проблема, из-за которой из центра проектов не удавалось открыть проекты с длинными именами на кириллице.</span><span class="sxs-lookup"><span data-stu-id="556ca-406">Fixed an issue where projects with long Cyrillic names could not be opened through Project Center.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-january-22"></a><span data-ttu-id="556ca-408">Версия 2102: 22 января</span><span class="sxs-lookup"><span data-stu-id="556ca-408">Version 2102: January 22</span></span>
<span data-ttu-id="556ca-409">*Версия 2102 (сборка 13714.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-409">*Version 2102 (Build 13714.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-411">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-411">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-412">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-412">Excel</span></span>

- <span data-ttu-id="556ca-413">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="556ca-413">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="556ca-414">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-414">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="556ca-415">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-415">Outlook</span></span>

- <span data-ttu-id="556ca-416">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="556ca-416">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="556ca-417">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-417">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="556ca-418">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-418">PowerPoint</span></span>

- <span data-ttu-id="556ca-419">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="556ca-419">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="556ca-420">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-420">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a><span data-ttu-id="556ca-421">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-421">Word</span></span>

- <span data-ttu-id="556ca-422">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="556ca-422">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="556ca-423">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-423">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-426">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-426">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-427">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-427">Excel</span></span>

- <span data-ttu-id="556ca-428">Исправляет проблемы, при которых определенные диаграммы, в которых используются несмежные диапазоны ячеек, не будут загружаться при повторном открытии файлов.</span><span class="sxs-lookup"><span data-stu-id="556ca-428">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="556ca-429">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck)</span><span class="sxs-lookup"><span data-stu-id="556ca-429">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-430">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-430">PowerPoint</span></span>

- <span data-ttu-id="556ca-431">Исправлена проблема, связанная с отображением эмодзи в цвете.</span><span class="sxs-lookup"><span data-stu-id="556ca-431">Fixed an issue related to displaying emojis with color.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-432">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-432">Word</span></span>


- <span data-ttu-id="556ca-433">Это позволяет устранить проблему, из-за которой был невозможен ввод в режиме реального времени и восстановление присутствия после потери подключения к Интернету в течение определенного периода времени.</span><span class="sxs-lookup"><span data-stu-id="556ca-433">This fixes an issue that prevented real-time typing and presence from being restored after loosing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="556ca-434">Исправлена проблема с совместным редактированием.</span><span class="sxs-lookup"><span data-stu-id="556ca-434">We fixed an issue with coauthoring.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-january-15"></a><span data-ttu-id="556ca-436">Версия 2102: 15 января</span><span class="sxs-lookup"><span data-stu-id="556ca-436">Version 2102: January 15</span></span>
<span data-ttu-id="556ca-437">*Версия 2102 (сборка 13707.20008)*</span><span class="sxs-lookup"><span data-stu-id="556ca-437">*Version 2102 (Build 13707.20008)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-439">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-439">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-440">Outlook</span></span>

- <span data-ttu-id="556ca-441">**Отправка в Teams.** Поделитесь сообщением или беседой из Outlook с пользователем в Teams или отправьте их в канал Teams.</span><span class="sxs-lookup"><span data-stu-id="556ca-441">**Share to Teams:** Share an email or a conversation from Outlook to a person or channel in Teams.</span></span>

### <a name="visio"></a><span data-ttu-id="556ca-442">Visio</span><span class="sxs-lookup"><span data-stu-id="556ca-442">Visio</span></span>

- <span data-ttu-id="556ca-443">**Готовая графика для схем.** Выберите из большой библиотеки значки, стоковые фотографии, фигуры людей и наклейки, которые можно добавить в документы Visio.</span><span class="sxs-lookup"><span data-stu-id="556ca-443">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="556ca-444">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-444">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-447">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-447">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="556ca-448">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-448">Project</span></span>

- <span data-ttu-id="556ca-449">Устранена проблема, из-за которой сведение базовых затрат выполнялось неправильно, если затратный ресурс был назначен задаче-вехе.</span><span class="sxs-lookup"><span data-stu-id="556ca-449">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-450">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-450">Word</span></span>

- <span data-ttu-id="556ca-451">Устраняется сбой при запуске макроса VBA ExportAsFixedFormat2 с ошибкой "Недопустимое значение презентации (неизвестный участник)".</span><span class="sxs-lookup"><span data-stu-id="556ca-451">Fixing a failure when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2102-january-08"></a><span data-ttu-id="556ca-453">Версия 2102: 8 января</span><span class="sxs-lookup"><span data-stu-id="556ca-453">Version 2102: January 08</span></span>
<span data-ttu-id="556ca-454">*Версия 2102 (сборка 13704.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-454">*Version 2102 (Build 13704.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-456">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-456">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-457">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-457">Outlook</span></span>

- <span data-ttu-id="556ca-458">**Диктофон стал еще лучше.** Создавать содержимое с помощью голосового ввода стало проще благодаря новой панели инструментов диктовки, голосовым командам и поддержке автоматической расстановки знаков препинания</span><span class="sxs-lookup"><span data-stu-id="556ca-458">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>

### <a name="word"></a><span data-ttu-id="556ca-459">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-459">Word</span></span>

- <span data-ttu-id="556ca-460">**Диктофон стал еще лучше.** Создавать содержимое с помощью голосового ввода стало проще благодаря новой панели инструментов диктовки, голосовым командам и поддержке автоматической расстановки знаков препинания</span><span class="sxs-lookup"><span data-stu-id="556ca-460">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-463">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-463">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-464">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-464">Excel</span></span>

- <span data-ttu-id="556ca-465">Исправлена проблема, из-за которой предварительный просмотр внедренного диапазона Excel в PowerPoint показывает неверный размер.</span><span class="sxs-lookup"><span data-stu-id="556ca-465">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-january-01"></a><span data-ttu-id="556ca-467">Версия 2101: 1 января</span><span class="sxs-lookup"><span data-stu-id="556ca-467">Version 2101: January 01</span></span>
<span data-ttu-id="556ca-468">*Версия 2101 (сборка 13624.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-468">*Version 2101 (Build 13624.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-470">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-470">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-471">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-471">Excel</span></span>

- <span data-ttu-id="556ca-472">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="556ca-472">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-473">PowerPoint</span></span>

- <span data-ttu-id="556ca-474">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="556ca-474">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-475">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-475">Word</span></span>

- <span data-ttu-id="556ca-476">**Обязательное присвоение меток.** Пользователям, для которых администраторы настроили политику обязательного присвоения меток, потребуется применять метки к своим документам и письмам.</span><span class="sxs-lookup"><span data-stu-id="556ca-476">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-479">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-479">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="556ca-480">OneNote</span><span class="sxs-lookup"><span data-stu-id="556ca-480">OneNote</span></span>

- <span data-ttu-id="556ca-481">Это исправление устраняет проблему отрисовки, влияющую на OneNote.</span><span class="sxs-lookup"><span data-stu-id="556ca-481">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-482">Outlook</span></span>

- <span data-ttu-id="556ca-483">Это изменение позволяет Outlook использовать параметр Exchange Server, предотвращающий отображение архивного почтового ящика Exchange Online для конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="556ca-483">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-484">PowerPoint</span></span>

- <span data-ttu-id="556ca-485">Это изменение исправляет проблему с объединением фигур при работе с текстом.</span><span class="sxs-lookup"><span data-stu-id="556ca-485">This change addresses an issue with Merge Shapes working with text.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-486">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-486">Word</span></span>

- <span data-ttu-id="556ca-487">Исправление для повышения функциональности современных примечаний. </span><span class="sxs-lookup"><span data-stu-id="556ca-487">Fix to make Modern comments more robust.</span></span>


- <span data-ttu-id="556ca-488">Исправлена проблема при редактировании записи примечания с @упоминанием.</span><span class="sxs-lookup"><span data-stu-id="556ca-488">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="556ca-489">Черновики примечаний исчезают при создании нового экземпляра Word.</span><span class="sxs-lookup"><span data-stu-id="556ca-489">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="556ca-490">Исправлена проблема со встроенными полосами прокрутки в области примечаний.</span><span class="sxs-lookup"><span data-stu-id="556ca-490">Fix and issue with nested scrollbars in the comments pane.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-december-25"></a><span data-ttu-id="556ca-492">Версия 2101: 25 декабря</span><span class="sxs-lookup"><span data-stu-id="556ca-492">Version 2101: December 25</span></span>
<span data-ttu-id="556ca-493">*Версия 2101 (сборка 13617.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-493">*Version 2101 (Build 13617.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-495">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-495">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-496">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-496">Excel</span></span>

- <span data-ttu-id="556ca-497">Обновление, чтобы обеспечить перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word</span><span class="sxs-lookup"><span data-stu-id="556ca-497">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="556ca-498">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="556ca-498">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="556ca-499">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="556ca-499">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-500">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-500">Outlook</span></span>

- <span data-ttu-id="556ca-501">Исправлена проблема, из-за которой пользователи не могли указать, на какой срок нужно разрешить доступ при начале слияния из Word, что приводило к получению избыточных запросов.</span><span class="sxs-lookup"><span data-stu-id="556ca-501">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="556ca-502">Исправлена проблема, из-за которой Outlook неожиданно закрывался у пользователей надстроек на основе Redemption. </span><span class="sxs-lookup"><span data-stu-id="556ca-502">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-503">PowerPoint</span></span>

- <span data-ttu-id="556ca-504">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="556ca-504">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-505">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-505">Word</span></span>

- <span data-ttu-id="556ca-506">Это изменение исправляет проблему, связанную со сменой цветов контура SVG-изображений.</span><span class="sxs-lookup"><span data-stu-id="556ca-506">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="556ca-507">Исправлена проблема, из-за которой поле ответа в карточке примечания располагалось вне экрана.</span><span class="sxs-lookup"><span data-stu-id="556ca-507">Fixes an issue where the reply box on a comment card is off the screen.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-december-18"></a><span data-ttu-id="556ca-509">Версия 2101: 18 декабря</span><span class="sxs-lookup"><span data-stu-id="556ca-509">Version 2101: December 18</span></span>
<span data-ttu-id="556ca-510">*Версия 2101 (сборка 13610.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-510">*Version 2101 (Build 13610.20002)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-512">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-512">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-513">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-513">Excel</span></span>

- <span data-ttu-id="556ca-514">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="556ca-514">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="556ca-515">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="556ca-515">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-516">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-516">Outlook</span></span>

- <span data-ttu-id="556ca-517">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="556ca-517">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="556ca-518">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="556ca-518">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-519">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-519">PowerPoint</span></span>

- <span data-ttu-id="556ca-520">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="556ca-520">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="556ca-521">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="556ca-521">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-522">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-522">Word</span></span>

- <span data-ttu-id="556ca-523">**Отправка данных аудита о присвоении меток конфиденциальности администраторам M365.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, Office отправляет данные аудита на сервер аудита M365 для просмотра администраторами.</span><span class="sxs-lookup"><span data-stu-id="556ca-523">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="556ca-524">Это автоматическая функция (без пользовательского интерфейса), полезная для администраторов.</span><span class="sxs-lookup"><span data-stu-id="556ca-524">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-527">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-528">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-528">Excel</span></span>

- <span data-ttu-id="556ca-529">Улучшена производительность при применении стилей форматирования для сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="556ca-529">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-530">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-530">Outlook</span></span>

- <span data-ttu-id="556ca-531">Устранена проблема, из-за которой пользователи не могли выбрать больше одной категории для поиска.</span><span class="sxs-lookup"><span data-stu-id="556ca-531">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="556ca-532">Устранена проблема, из-за которой время начала для некоторых элементов календаря неожиданно изменялось при копировании события из другой встречи. </span><span class="sxs-lookup"><span data-stu-id="556ca-532">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-533">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-533">Project</span></span>

- <span data-ttu-id="556ca-534">Исправлена проблема, из-за которой отсутствовали изменения при открытии пользователями проектов, сохраненных с измененными сведениями.</span><span class="sxs-lookup"><span data-stu-id="556ca-534">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-535">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-535">Word</span></span>

- <span data-ttu-id="556ca-536">Исправлена проблема с анимацией при вводе текста в нижней части карточки комментария.</span><span class="sxs-lookup"><span data-stu-id="556ca-536">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="556ca-537">Устранена проблема, из-за которой Word зависал при сохранении документа в формате PDF со скрытым текстом.</span><span class="sxs-lookup"><span data-stu-id="556ca-537">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2101-december-11"></a><span data-ttu-id="556ca-539">Версия 2101: 11 декабря</span><span class="sxs-lookup"><span data-stu-id="556ca-539">Version 2101: December 11</span></span>
<span data-ttu-id="556ca-540">*Версия 2101 (сборка 13604.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-540">*Version 2101 (Build 13604.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-542">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-542">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-543">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-543">Outlook</span></span>

- <span data-ttu-id="556ca-544">**Ваши параметры Outlook в облаке.** Выберите свои параметры Outlook для Windows, например автоматические ответы, сортировку почты и конфиденциальность, и получайте их на любом компьютере.</span><span class="sxs-lookup"><span data-stu-id="556ca-544">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-545">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-545">Word</span></span>

- <span data-ttu-id="556ca-546">**Усовершенствована функция совместной работы с помощью современных комментариев.** Добавление примечаний к объектам, @упоминание коллег и завершение цепочек комментариев для повышения удобства совместной работы.</span><span class="sxs-lookup"><span data-stu-id="556ca-546">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="556ca-547">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-547">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br /><span data-ttu-id="556ca-548">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/modern-commenting-in-word)</span><span class="sxs-lookup"><span data-stu-id="556ca-548">See details in [blog post](https://insider.office.com/ru-RU/blog/modern-commenting-in-word)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-551">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-551">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-552">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-552">Excel</span></span>

- <span data-ttu-id="556ca-553">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="556ca-553">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="556ca-554">Исправлена проблема с переключением разделителей после вызова Selection.Parent.Copy.</span><span class="sxs-lookup"><span data-stu-id="556ca-554">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-555">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-555">Outlook</span></span>

- <span data-ttu-id="556ca-556">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="556ca-556">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-557">PowerPoint</span></span>

- <span data-ttu-id="556ca-558">Это изменение исправляет проблему с циклическим воспроизведением фоновых видео в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="556ca-558">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="556ca-559">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="556ca-559">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-560">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-560">Word</span></span>

- <span data-ttu-id="556ca-561">Исправлена проблема с удалением современных примечаний в элементе управления содержимым, который помечен как нередактирумый.</span><span class="sxs-lookup"><span data-stu-id="556ca-561">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-december-04"></a><span data-ttu-id="556ca-563">Версия 2012: 4 декабря</span><span class="sxs-lookup"><span data-stu-id="556ca-563">Version 2012: December 04</span></span>
<span data-ttu-id="556ca-564">*Версия 2012 (сборка 13530.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-564">*Version 2012 (Build 13530.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-566">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-566">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-567">Outlook</span></span>

- <span data-ttu-id="556ca-568">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время начала собрания на 5–10 минут позже по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="556ca-568">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="556ca-569">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-569">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a><span data-ttu-id="556ca-570">Visio</span><span class="sxs-lookup"><span data-stu-id="556ca-570">Visio</span></span>

- <span data-ttu-id="556ca-571">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="556ca-571">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="556ca-572">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-572">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-575">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-575">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-576">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-576">Excel</span></span>

- <span data-ttu-id="556ca-577">Устранена проблема, при которой было затруднено редактирование на языках, требующих использования IME, в режиме перезаписи.</span><span class="sxs-lookup"><span data-stu-id="556ca-577">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="556ca-578">Восстановлена нарушенная ссылка на справочную статью в оповещении, возникающем при отключении автосохранения.</span><span class="sxs-lookup"><span data-stu-id="556ca-578">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="556ca-579">Устранена проблема, вызывавшая неожиданное закрытие Excel при копировании и вставке данных в представлении формулы.</span><span class="sxs-lookup"><span data-stu-id="556ca-579">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-580">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-580">Outlook</span></span>

- <span data-ttu-id="556ca-581">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="556ca-581">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-582">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-582">Project</span></span>

- <span data-ttu-id="556ca-583">Устранена проблема долгого открытия проекта с множеством ресурсов.</span><span class="sxs-lookup"><span data-stu-id="556ca-583">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="556ca-584">Устранена проблема, при которой отдельные проекты могли открываться при наличии проблемы в какой-либо части загрузки файла проекта.</span><span class="sxs-lookup"><span data-stu-id="556ca-584">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-585">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-585">Word</span></span>

- <span data-ttu-id="556ca-586">Вставка в виде обычного текста часто бывает предпочтительнее вставки форматированного текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-586">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="556ca-587">Это исправленное контекстное меню позволяет пользователю выполнять вставку в виде обычного текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-587">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="556ca-588">Иначе пользователю приходилось копировать фрагмент в редактор обычного текста, например "Блокнот", а уже оттуда копировать в нужное приложение.</span><span class="sxs-lookup"><span data-stu-id="556ca-588">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-november-27"></a><span data-ttu-id="556ca-590">Версия 2012: 27 ноября</span><span class="sxs-lookup"><span data-stu-id="556ca-590">Version 2012: November 27</span></span>
<span data-ttu-id="556ca-591">*Версия 2012 (сборка 13519.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-591">*Version 2012 (Build 13519.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-593">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-593">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-594">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-594">Excel</span></span>

- <span data-ttu-id="556ca-595">Исправлена проблема, из-за которой Power Pivot не мог правильно импортировать текстовый файл с разделителями (табуляциями).</span><span class="sxs-lookup"><span data-stu-id="556ca-595">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-596">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-596">Outlook</span></span>

- <span data-ttu-id="556ca-597">Устранена проблема, из-за которой у пользователей возникали ошибки при отправке почты Outlook из приложений, отличных от Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-597">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-598">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-598">PowerPoint</span></span>

- <span data-ttu-id="556ca-599">Это изменение устраняет проблему, связанную с ошибками превышения времени ожидания при анализе рукописного фрагмента.</span><span class="sxs-lookup"><span data-stu-id="556ca-599">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="556ca-600">Это изменение устраняет грамматическую ошибку в пользовательском интерфейсе создания GIF с анимацией.</span><span class="sxs-lookup"><span data-stu-id="556ca-600">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="556ca-601">Устранена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-601">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-602">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-602">Project</span></span>

- <span data-ttu-id="556ca-603">Устранена проблема, из-за которой могли отображаться многочисленные неназначенные задания, связанные с задачей.</span><span class="sxs-lookup"><span data-stu-id="556ca-603">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="556ca-604">Устранена проблема, из-за которой в крупных проектах имя задачи могло вводиться очень медленно.</span><span class="sxs-lookup"><span data-stu-id="556ca-604">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-november-20"></a><span data-ttu-id="556ca-606">Версия 2012: 20 ноября</span><span class="sxs-lookup"><span data-stu-id="556ca-606">Version 2012: November 20</span></span>
<span data-ttu-id="556ca-607">*Версия 2012 (сборка 13512.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-607">*Version 2012 (Build 13512.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-609">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-609">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-610">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-610">Outlook</span></span>

- <span data-ttu-id="556ca-611">**Все собрания по сети.** Упростите планирование собраний по сети с помощью нового параметра, который по умолчанию делает все собрания виртуальными.</span><span class="sxs-lookup"><span data-stu-id="556ca-611">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-612">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-612">PowerPoint</span></span>

- <span data-ttu-id="556ca-613">**Библиотека видео.** Улучшайте свои документы с помощью библиотеки специально отобранных бесплатных видеоматериалов, доступных в приложении</span><span class="sxs-lookup"><span data-stu-id="556ca-613">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-616">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-616">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="556ca-617">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-617">PowerPoint</span></span>

- <span data-ttu-id="556ca-618">Устранена проблема, из-за которой индикатор присутствия неизвестного соавтора не обновлялся полностью при поступлении новой информации об этом соавторе.</span><span class="sxs-lookup"><span data-stu-id="556ca-618">Fixed an issue where the presence indicator for an unknown coauthor does not get completely refreshed, once more information about the coauthor is available.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-619">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-619">Word</span></span>

- <span data-ttu-id="556ca-620">Устранена проблема, из-за которой Word зависал при сохранении документа в формате PDF со скрытым текстом.</span><span class="sxs-lookup"><span data-stu-id="556ca-620">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-november-13"></a><span data-ttu-id="556ca-622">Версия 2012: 13 ноября</span><span class="sxs-lookup"><span data-stu-id="556ca-622">Version 2012: November 13</span></span>
<span data-ttu-id="556ca-623">*Версия 2012 (сборка 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="556ca-623">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-625">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-625">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-626">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-626">Excel</span></span>

- <span data-ttu-id="556ca-627">Исправлена проблема, из-за которой команда "Вставить объект" не отображала соответствующий значок при вставке файла из локальной папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="556ca-627">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-628">Outlook</span></span>

- <span data-ttu-id="556ca-629">Исправлена проблема, из-за которой поле "Кому:" было пустым в отчетах о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="556ca-629">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-630">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-630">PowerPoint</span></span>

- <span data-ttu-id="556ca-631">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="556ca-631">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="556ca-632">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-632">Project</span></span>

- <span data-ttu-id="556ca-633">Исправлена проблема, из-за которой не удавалось удалить зависимости в конечных результатах, если сайт SharePoint, с которым были связаны конечные результаты, больше не существовал.</span><span class="sxs-lookup"><span data-stu-id="556ca-633">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="556ca-634">Исправлена проблема, из-за которой отсутствовали изменения при открытии пользователями проектов, сохраненных с измененными сведениями.</span><span class="sxs-lookup"><span data-stu-id="556ca-634">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-635">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-635">Word</span></span>

- <span data-ttu-id="556ca-636">Исправлена проблема, из-за которой изображения становились размытыми при изменении масштаба.</span><span class="sxs-lookup"><span data-stu-id="556ca-636">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="556ca-637">Исправлена проблема, из-за которой длинные гиперссылки усекались.</span><span class="sxs-lookup"><span data-stu-id="556ca-637">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-november-06"></a><span data-ttu-id="556ca-639">Версия 2012: 6 ноября</span><span class="sxs-lookup"><span data-stu-id="556ca-639">Version 2012: November 06</span></span>
<span data-ttu-id="556ca-640">*Версия 2012 (сборка 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-640">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-642">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-642">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-643">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-643">Excel</span></span>

- <span data-ttu-id="556ca-644">**Отображение нескольких листов одновременно.** Больше не нужно отображать листы по одному. Отображайте несколько скрытых листов одновременно.</span><span class="sxs-lookup"><span data-stu-id="556ca-644">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="556ca-645">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-645">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="556ca-646">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-646">Outlook</span></span>

- <span data-ttu-id="556ca-647">**Одна подпись на всех устройствах.** Ваша подпись хранится в облаке.</span><span class="sxs-lookup"><span data-stu-id="556ca-647">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="556ca-648">Создайте ее один раз и используйте везде, где применяете Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-648">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-651">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-651">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-652">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-652">Excel</span></span>

- <span data-ttu-id="556ca-653">Исправлена проблема, из-за которой некоторые элементы не был локализованы на китайском языке (упрощенное письмо).</span><span class="sxs-lookup"><span data-stu-id="556ca-653">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="556ca-654">Исправлена проблема, из-за которой приложение Excel неожиданно прекращало работу при обновлении.</span><span class="sxs-lookup"><span data-stu-id="556ca-654">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-655">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-655">Outlook</span></span>

- <span data-ttu-id="556ca-656">Исправлена проблема, из-за которой не удавалось добавить вложение в сообщение, открытое из ZIP-файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-656">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-30"></a><span data-ttu-id="556ca-658">Версия 2011: 30 октября</span><span class="sxs-lookup"><span data-stu-id="556ca-658">Version 2011: October 30</span></span>
<span data-ttu-id="556ca-659">*Версия 2011 (сборка 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="556ca-659">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-661">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-661">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-662">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-662">Excel</span></span>

- <span data-ttu-id="556ca-663">**Улучшенные диалоговые окна условного форматирования.** Теперь размеры диалоговых окон условного форматирования можно изменять, и вы можете дублировать правило одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="556ca-663">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="556ca-664">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-664">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-667">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-667">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-668">Доступ</span><span class="sxs-lookup"><span data-stu-id="556ca-668">Access</span></span>

- <span data-ttu-id="556ca-669">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="556ca-669">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="556ca-670">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-670">Excel</span></span>

- <span data-ttu-id="556ca-671">Исправлена проблема с Power Pivot при использовании подключения к базе данных Oracle.</span><span class="sxs-lookup"><span data-stu-id="556ca-671">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="556ca-672">Исправлена проблема с неожиданным прекращением работы Excel, когда запускалось вычисление MTR и обновление объекта групповой политики (например, с помощью удаленного обновления групповой политики).</span><span class="sxs-lookup"><span data-stu-id="556ca-672">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="556ca-673">Это изменение исправляет ошибку, приводившую к сбою в Excel при попытке загрузки файла ATOMSVC.</span><span class="sxs-lookup"><span data-stu-id="556ca-673">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="556ca-674">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="556ca-674">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-675">Outlook</span></span>

- <span data-ttu-id="556ca-676">Исправлена проблема, из-за которой владелец почтового ящика не мог управлять разрешением общего доступа для своего календаря, так как этот параметр был затенен.</span><span class="sxs-lookup"><span data-stu-id="556ca-676">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="556ca-677">Исправлена проблема, из-за которой сохранение шаблонов электронной почты в виде OFT-файлов приводило к изменению китайских иероглифов на вопросительные знаки.</span><span class="sxs-lookup"><span data-stu-id="556ca-677">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="556ca-678">Исправлена проблема, из-за которой приложение Outlook не могло создать сообщение с ограниченным разрешением.</span><span class="sxs-lookup"><span data-stu-id="556ca-678">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="556ca-679">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="556ca-679">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-680">PowerPoint</span></span>

- <span data-ttu-id="556ca-681">Исправлена проблема, из-за которой линии сетки смещались со слайдов при закрытии области конструктора.</span><span class="sxs-lookup"><span data-stu-id="556ca-681">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="556ca-682">Исправлена проблема, из-за которой полоса прокрутки на слайде начинала двигаться самостоятельно после прекращения записи экрана с открытой областью выбора.</span><span class="sxs-lookup"><span data-stu-id="556ca-682">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-683">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-683">Project</span></span>

- <span data-ttu-id="556ca-684">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="556ca-684">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="556ca-685">Исправлена проблема, из-за которой задействование ресурсов выполняло поиск ресурса по имени, а не по GUID, что приводило к проблемам при наличии нескольких ресурсов с одинаковым именем.</span><span class="sxs-lookup"><span data-stu-id="556ca-685">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-686">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-686">Word</span></span>

- <span data-ttu-id="556ca-687">Исправлена проблема, из-за которой щелчок по маркеру примечания не приводил к уменьшению масштаба для отображения карточки примечания в представлении.</span><span class="sxs-lookup"><span data-stu-id="556ca-687">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="556ca-688">Исправлена проблема макета, из-за которой могла смещаться линия между столбцами.</span><span class="sxs-lookup"><span data-stu-id="556ca-688">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="556ca-689">Исправлена проблема, из-за которой казалось, что приложение Word зависает при вставке книги Excel в документ Word.</span><span class="sxs-lookup"><span data-stu-id="556ca-689">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-690">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-690">Office Suite</span></span>

- <span data-ttu-id="556ca-691">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="556ca-691">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-23"></a><span data-ttu-id="556ca-693">Версия 2011: 23 октября</span><span class="sxs-lookup"><span data-stu-id="556ca-693">Version 2011: October 23</span></span>
<span data-ttu-id="556ca-694">*Версия 2011 (сборка 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-694">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-696">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-696">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="556ca-697">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-697">PowerPoint</span></span>

- <span data-ttu-id="556ca-698">**Отрепетируйте презентацию с помощью тренера выступлений.** Получите отзывы, которые помогут удержать аудиторию, в том числе о темпе речи, тоне, словах-заполнителях, деликатных фразах и т. д.</span><span class="sxs-lookup"><span data-stu-id="556ca-698">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="556ca-699">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-699">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-702">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-702">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-703">Доступ</span><span class="sxs-lookup"><span data-stu-id="556ca-703">Access</span></span>

- <span data-ttu-id="556ca-704">Исправлена проблема, из-за которой для некоторых пользователей отображалась ошибка "Недостаточно системных ресурсов", когда они пытались экспортировать запрос из своей синхронизированной папки OneDrive.</span><span class="sxs-lookup"><span data-stu-id="556ca-704">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="556ca-705">Исправлена проблема, из-за которой автоматическое переключение между окнами форм приводило к переключению на другую форму.</span><span class="sxs-lookup"><span data-stu-id="556ca-705">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-706">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-706">Outlook</span></span>

- <span data-ttu-id="556ca-707">Исправлена проблема, из-за которой при вставке URL-адреса, скопированного из расположения собрания, в другое место (например, в браузер) URL-адрес содержал в конце точку с запятой.</span><span class="sxs-lookup"><span data-stu-id="556ca-707">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-708">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-708">PowerPoint</span></span>

- <span data-ttu-id="556ca-709">Исправлена проблема, из-за которой при дублировании слайд-шоу на второй монитор оно могло быть скрыто за другим окном.</span><span class="sxs-lookup"><span data-stu-id="556ca-709">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-710">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-710">Project</span></span>

- <span data-ttu-id="556ca-711">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="556ca-711">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-712">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-712">Word</span></span>

- <span data-ttu-id="556ca-713">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="556ca-713">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="556ca-714">Исправлена проблема печати, из-за которой применялась метка конфиденциальности с подложками.</span><span class="sxs-lookup"><span data-stu-id="556ca-714">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-16"></a><span data-ttu-id="556ca-716">Версия 2011: 16 октября</span><span class="sxs-lookup"><span data-stu-id="556ca-716">Version 2011: October 16</span></span>
<span data-ttu-id="556ca-717">*Версия 2011 (сборка 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-717">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-719">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-719">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-720">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-720">Excel</span></span>

- <span data-ttu-id="556ca-721">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="556ca-721">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="556ca-722">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-722">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="556ca-723">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-723">Outlook</span></span>

- <span data-ttu-id="556ca-724">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="556ca-724">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="556ca-725">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-725">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="556ca-726">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-726">PowerPoint</span></span>

- <span data-ttu-id="556ca-727">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="556ca-727">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="556ca-728">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-728">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="556ca-729">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-729">Word</span></span>

- <span data-ttu-id="556ca-730">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="556ca-730">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="556ca-731">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-731">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-734">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-734">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-735">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-735">Outlook</span></span>

- <span data-ttu-id="556ca-736">Мы исправили проблему, из-за которой пользователи не могли удалять встречи в календаре Групп Microsoft 365 в рамках обычной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="556ca-736">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="556ca-737">Исправлена проблема с невозможностью запуска Outlook при загрузке кэша псевдонимов.</span><span class="sxs-lookup"><span data-stu-id="556ca-737">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-738">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-738">PowerPoint</span></span>

- <span data-ttu-id="556ca-739">Исправлена проблема, из-за которой в значке заполнителя содержимого рядом с "Изображениями" не было всплывающих подсказок.</span><span class="sxs-lookup"><span data-stu-id="556ca-739">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="556ca-740">Исправлена проблема, из-за которой при защищенном просмотре слайд-шоу, демонстрируемого в файле pptsx, можно было сделать снимок экрана документа, защищенного IRM.</span><span class="sxs-lookup"><span data-stu-id="556ca-740">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-october-09"></a><span data-ttu-id="556ca-742">Версия 2011: 9 октября</span><span class="sxs-lookup"><span data-stu-id="556ca-742">Version 2011: October 09</span></span>
<span data-ttu-id="556ca-743">*Версия 2011 (сборка 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-743">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-745">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-745">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-746">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-746">Excel</span></span>

- <span data-ttu-id="556ca-747">**Создание потоков данных Power Platform в запросах:** теперь можно экспортировать запросы в шаблоны Power Query, которые могут использоваться для создания новых потоков данных Power Platform.</span><span class="sxs-lookup"><span data-stu-id="556ca-747">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-748">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-748">PowerPoint</span></span>

- <span data-ttu-id="556ca-749">**Экспорт GIF с анимацией в диапазоне:** можно выбрать диапазон слайдов при экспорте в GIF с анимацией</span><span class="sxs-lookup"><span data-stu-id="556ca-749">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="556ca-750">**Создание GIF-файлов с прозрачным фоном:** при экспорте в GIF с анимацией новый параметр позволит сделать фон прозрачным.</span><span class="sxs-lookup"><span data-stu-id="556ca-750">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-753">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-753">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-754">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-754">Excel</span></span>

- <span data-ttu-id="556ca-755">Устранена проблема, при которой имя файла не изменялось после включения операции SaveAs для надстроек COM.</span><span class="sxs-lookup"><span data-stu-id="556ca-755">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="556ca-756">Устранена проблема, вызывавшая сбой при автоматическом сохранении с неверным или ошибочным сообщением об ошибке, если в модели данных Excel было неверное определение меры.</span><span class="sxs-lookup"><span data-stu-id="556ca-756">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="556ca-757">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-757">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-758">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-758">Outlook</span></span>

- <span data-ttu-id="556ca-p136">Устранена проблема, из-за которой быстрая печать вложенных изображений вызывала ошибку: "Windows не удалось найти изображение. Проверьте его местонахождение и попробуйте еще раз".</span><span class="sxs-lookup"><span data-stu-id="556ca-p136">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="556ca-761">Устранена проблема, из-за которой у некоторых пользователей происходил запуск Outlook в автономном состоянии, пока они вручную не выбирали сетевой режим работы.</span><span class="sxs-lookup"><span data-stu-id="556ca-761">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-762">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-762">PowerPoint</span></span>

- <span data-ttu-id="556ca-763">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-763">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-764">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-764">Project</span></span>

- <span data-ttu-id="556ca-765">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChagne не имело правильного значения в случае изменения задержки в представлении типа "Форма задач".</span><span class="sxs-lookup"><span data-stu-id="556ca-765">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="556ca-766">Устранена проблема, из-за которой после группирования списка задач на сайте проекта нельзя было быстро изменить список задач.</span><span class="sxs-lookup"><span data-stu-id="556ca-766">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="556ca-767">Исправлена проблема, при которой после обновления корпоративного ресурса с помощью CSOM максимальные единицы для ресурса могли быть потеряны.</span><span class="sxs-lookup"><span data-stu-id="556ca-767">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-768">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-768">Word</span></span>

- <span data-ttu-id="556ca-769">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-769">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="556ca-770">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="556ca-770">Office Suite</span></span>

- <span data-ttu-id="556ca-771">Устранена проблема, из-за которой при интерактивном входе в SSO API возвращался код ошибки.</span><span class="sxs-lookup"><span data-stu-id="556ca-771">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-02"></a><span data-ttu-id="556ca-773">Версия 2010: 2 октября</span><span class="sxs-lookup"><span data-stu-id="556ca-773">Version 2010: October 02</span></span>
<span data-ttu-id="556ca-774">*Версия 2010 (сборка 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-774">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-776">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-776">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-777">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-777">Excel</span></span>

- <span data-ttu-id="556ca-778">**Создание типов данных с помощью диалогового окна дополнительных параметров.** В диалоговом окне дополнительных параметров можно вручную выбрать столбцы, объединяющие типы данных, которые вы создаете.</span><span class="sxs-lookup"><span data-stu-id="556ca-778">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-781">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-781">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="556ca-782">OneNote</span><span class="sxs-lookup"><span data-stu-id="556ca-782">OneNote</span></span>

- <span data-ttu-id="556ca-783">Исправлена проблема, из-за которой пользователь не мог выбрать и скопировать URL-адрес записной книжки из текстового поля в разделе "Файл OutSpace > Сведения".</span><span class="sxs-lookup"><span data-stu-id="556ca-783">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-784">Outlook</span></span>

- <span data-ttu-id="556ca-785">Исправлена проблема, из-за которой автоматически созданные сообщения отправлялись пустые, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="556ca-785">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="556ca-786">Исправлена проблема с кэшированием неправильного GUID для папок.</span><span class="sxs-lookup"><span data-stu-id="556ca-786">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="556ca-787">При копировании и вставке адреса электронной почты в поле "получатель" с отображаемым именем адрес электронной почты не всегда распознается правильно и появляется сообщение о недействительном адресе.</span><span class="sxs-lookup"><span data-stu-id="556ca-787">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="556ca-788">Эта проблема устранена, то есть имя и адрес электронной почты распознаются правильно, а предупреждение больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="556ca-788">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="556ca-789">Исправлена проблема, из-за которой общие сетевые папки не возвращали имя родительской папки.</span><span class="sxs-lookup"><span data-stu-id="556ca-789">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="556ca-790">Вместо сбоя они возвращали пустой путь, который ошибочно отправлялся в основную учетную запись.</span><span class="sxs-lookup"><span data-stu-id="556ca-790">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="556ca-791">Исправлена проблема, из-за которой после повторного открытия черновика в области просмотра "Только для чтения" включалось отслеживание изменений.</span><span class="sxs-lookup"><span data-stu-id="556ca-791">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="556ca-792">Исправлена проблема, из-за которой параметр "Сохранить как" был недоступен для классических вложений.</span><span class="sxs-lookup"><span data-stu-id="556ca-792">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="556ca-793">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="556ca-793">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-794">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-794">PowerPoint</span></span>

- <span data-ttu-id="556ca-795">Исправлена проблема, из-за которой PowerPoint не экспортировал маркеры списка в виде прямоугольников при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="556ca-795">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="556ca-796">Исправлена проблема, из-за которой диалоговое окно завершения сеанса отображалось на странице сводки, если вы переходили с последнего слайда к следующему после нажатия кнопки "Завершить сеанс" и до появления сводки.</span><span class="sxs-lookup"><span data-stu-id="556ca-796">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="556ca-797">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-797">Project</span></span>

- <span data-ttu-id="556ca-798">Исправлена проблема, из-за которой Project мог аварийно завершить работу, если вы применяли группу с помощью представления "Использование ресурсов" или "Лист ресурсов", а затем вставляли столбец.</span><span class="sxs-lookup"><span data-stu-id="556ca-798">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="556ca-799">Исправлена проблема, из-за которой могли возникать задержки при переключении представлений и открытии сведений о задаче или проекте при наличии настраиваемых полей с формулами и использовании освоенного объема.</span><span class="sxs-lookup"><span data-stu-id="556ca-799">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="556ca-800">Исправлена проблема, из-за которой метод VBA ConsolidateProjects мог выполнять регистрацию, если вы пытались добавить один проект несколько раз и присвоили параметру AttachToSources значение false.</span><span class="sxs-lookup"><span data-stu-id="556ca-800">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="556ca-801">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="556ca-801">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-25"></a><span data-ttu-id="556ca-803">Версия 2010: 25 сентября</span><span class="sxs-lookup"><span data-stu-id="556ca-803">Version 2010: September 25</span></span>
<span data-ttu-id="556ca-804">*Версия 2010 (сборка 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-804">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-806">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-806">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-807">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-807">Excel</span></span>

- <span data-ttu-id="556ca-808">**Создание типов данных с помощью Power Query:** создание насыщенных типов данных с помощью Power Query из любого источника данных</span><span class="sxs-lookup"><span data-stu-id="556ca-808">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-809">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-809">Outlook</span></span>

- <span data-ttu-id="556ca-810">**Обновления для задач пользовательского интерфейса:** визуальное обновление элементов задач</span><span class="sxs-lookup"><span data-stu-id="556ca-810">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="556ca-811">**Экономия времени при создании сообщений:** в Outlook отображаются предложения по литературной правке, помогающие быстро создавать сообщения.</span><span class="sxs-lookup"><span data-stu-id="556ca-811">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="556ca-812">Чтобы принять предложение, используйте клавишу TAB.</span><span class="sxs-lookup"><span data-stu-id="556ca-812">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-813">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-813">Word</span></span>

- <span data-ttu-id="556ca-814">**Обновление области "Корректор" (Майкрософт) в классическом приложении Word:** мы обновили текущий интерфейс области "Корректор" в классическом приложении Word.</span><span class="sxs-lookup"><span data-stu-id="556ca-814">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-817">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-817">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-818">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-818">Access</span></span>

- <span data-ttu-id="556ca-819">Исправлена проблема, из-за которой не удавалось правильно задать положение полосы прокрутки при загрузке окна запроса или схемы данных, сохраненных во время прокрутки.</span><span class="sxs-lookup"><span data-stu-id="556ca-819">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="556ca-820">Исправлена проблема, из-за которой в области задач "Добавить таблицу" неправильно отображались имена, содержащие '&'.</span><span class="sxs-lookup"><span data-stu-id="556ca-820">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="556ca-821">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-821">Excel</span></span>

- <span data-ttu-id="556ca-822">Исправлена проблема, из-за которой в диаграммах не работал многоуровневый ручной интервал категорий.</span><span class="sxs-lookup"><span data-stu-id="556ca-822">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="556ca-823">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="556ca-823">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="556ca-824">Исправлена проблема, из-за которой при добавлении в таблицу, используемую для проверки данных, не обновлялись параметры для всех листов в книге.</span><span class="sxs-lookup"><span data-stu-id="556ca-824">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="556ca-825">OneNote</span><span class="sxs-lookup"><span data-stu-id="556ca-825">OneNote</span></span>

- <span data-ttu-id="556ca-826">Исправлена проблема, из-за которой OneNote не поддерживал высокую контрастность цветов в полотне для пользовательских тем.</span><span class="sxs-lookup"><span data-stu-id="556ca-826">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="556ca-827">Исправлена проблема, из-за которой при наведении указателя мыши на зеленый цвет в селекторе цветов записной книжки появлялось всплывающее окно "красный мел".</span><span class="sxs-lookup"><span data-stu-id="556ca-827">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="556ca-828">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-828">PowerPoint</span></span>

- <span data-ttu-id="556ca-829">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="556ca-829">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-830">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-830">Word</span></span>

- <span data-ttu-id="556ca-831">Исправлена проблема, из-за которой ссылки на файлы, поддерживающие рабочий процесс, не открывались должным образом.</span><span class="sxs-lookup"><span data-stu-id="556ca-831">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-18"></a><span data-ttu-id="556ca-833">Версия 2010: 18 сентября</span><span class="sxs-lookup"><span data-stu-id="556ca-833">Version 2010: September 18</span></span>
<span data-ttu-id="556ca-834">*Версия 2010 (сборка 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="556ca-834">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-836">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-836">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-837">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-837">Outlook</span></span>

- <span data-ttu-id="556ca-838">**Проверка правописания в сообщениях в Редакторе:** теперь можно использовать рекомендации по грамматике и стилю в письмах для пользователей 64-разрядных версий Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-838">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="556ca-839">Найдите подчеркнутые слова, чтобы увидеть рекомендации Редактора по улучшению текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-839">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="556ca-840">**Преодолейте языковый барьер с помощью встроенного переводчика.** Надстройки для перевода больше не нужны!</span><span class="sxs-lookup"><span data-stu-id="556ca-840">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="556ca-841">В сообщении щелкните правой кнопкой мыши, чтобы перевести определенные слова, фразы или весь текст.</span><span class="sxs-lookup"><span data-stu-id="556ca-841">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-844">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-844">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-845">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-845">Excel</span></span>

- <span data-ttu-id="556ca-846">Исправлена проблема с 2D-диаграммами с картами, когда нельзя было задать цвета для максимального, среднего и минимального значений ряда данных с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="556ca-846">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="556ca-847">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="556ca-847">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="556ca-848">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="556ca-848">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="556ca-849">Исправлена проблема, которая в некоторых случаях приводила к сбою на листе диаграммы при вводе формулы в строке формул.</span><span class="sxs-lookup"><span data-stu-id="556ca-849">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="556ca-850">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-850">Outlook</span></span>

- <span data-ttu-id="556ca-851">При копировании и вставке адреса электронной почты в поле "получатель" с отображаемым именем адрес электронной почты не всегда распознается правильно и появляется сообщение о недействительном адресе.</span><span class="sxs-lookup"><span data-stu-id="556ca-851">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="556ca-852">Эта проблема устранена, то есть имя и адрес электронной почты распознаются правильно, а предупреждение больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="556ca-852">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="556ca-853">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-853">Word</span></span>

- <span data-ttu-id="556ca-854">Исправлена проблема, из-за после прикосновения к исправлению (вставке или удалению) появлялось всплывающее примечание.</span><span class="sxs-lookup"><span data-stu-id="556ca-854">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="556ca-855">Исправлена проблема с удалением выносок примечаний в Word.</span><span class="sxs-lookup"><span data-stu-id="556ca-855">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="556ca-856">Исправлена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-856">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="556ca-857">Исправлена проблема с сохранением документа Word, содержащего ссылку и формулу.</span><span class="sxs-lookup"><span data-stu-id="556ca-857">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-11"></a><span data-ttu-id="556ca-859">Версия 2010: 11 сентября</span><span class="sxs-lookup"><span data-stu-id="556ca-859">Version 2010: September 11</span></span>
<span data-ttu-id="556ca-860">*Версия 2010 (сборка 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-860">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-862">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-862">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="556ca-863">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-863">Access</span></span>

- <span data-ttu-id="556ca-864">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-864">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-865">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-865">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-866">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-866">Excel</span></span>

- <span data-ttu-id="556ca-867">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-867">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-868">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-868">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="556ca-869">OneNote</span><span class="sxs-lookup"><span data-stu-id="556ca-869">OneNote</span></span>

- <span data-ttu-id="556ca-870">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-870">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-871">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-871">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-872">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-872">Outlook</span></span>

- <span data-ttu-id="556ca-873">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-873">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-874">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-874">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-875">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-875">PowerPoint</span></span>

- <span data-ttu-id="556ca-876">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-876">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-877">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-877">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-878">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-878">Project</span></span>

- <span data-ttu-id="556ca-879">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-879">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-880">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-880">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="556ca-881">Publisher</span><span class="sxs-lookup"><span data-stu-id="556ca-881">Publisher</span></span>

- <span data-ttu-id="556ca-882">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-882">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-883">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-883">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="556ca-884">Visio</span><span class="sxs-lookup"><span data-stu-id="556ca-884">Visio</span></span>

- <span data-ttu-id="556ca-885">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-885">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-886">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-886">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-887">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-887">Word</span></span>

- <span data-ttu-id="556ca-888">**Office может отслеживать параметр темного режима в Windows 10.** Windows 10 используется в темном режиме?</span><span class="sxs-lookup"><span data-stu-id="556ca-888">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="556ca-889">Теперь Office может изменять тему, чтобы определять соответствие автоматически. Просто выберите пункт "Использовать параметр системы" в качестве темы Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-889">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-892">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-892">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-893">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-893">Excel</span></span>

- <span data-ttu-id="556ca-894">Исправлена проблема, из-за которой при переключении между листами с большим объемом данных могла возникать заметная задержка, если был включен страничный режим.</span><span class="sxs-lookup"><span data-stu-id="556ca-894">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-895">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-895">Outlook</span></span>

- <span data-ttu-id="556ca-896">Исправлена проблема, из-за которой сообщения электронной почты скрывались после отключения сортировки почты и выполнения сортировки.</span><span class="sxs-lookup"><span data-stu-id="556ca-896">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-897">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-897">PowerPoint</span></span>

- <span data-ttu-id="556ca-898">Исправлена проблема, из-за которой изображение GIF анимировалось только один раз в текстовом редакторе и слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="556ca-898">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-september-04"></a><span data-ttu-id="556ca-900">Версия 2010: 4 сентября</span><span class="sxs-lookup"><span data-stu-id="556ca-900">Version 2010: September 04</span></span>
<span data-ttu-id="556ca-901">*Версия 2010 (сборка 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="556ca-901">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-903">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-903">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-904">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-904">Outlook</span></span>

- <span data-ttu-id="556ca-905">**Закрепление сообщения электронной почты:** эта функция попомгает пользователям следить за письмами, которым нужно уделить внимание или которые следует оставить наверху списка сообщений.</span><span class="sxs-lookup"><span data-stu-id="556ca-905">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="556ca-906">**Получение предложений электронной почты при поиске пользователя:** когда вы вводите условия поиска Outlook, вы получаете в предложениях наиболее подходящую электронную почту.</span><span class="sxs-lookup"><span data-stu-id="556ca-906">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="556ca-907">**Получение предложений электронной почты при поиске пользователя:** когда вы вводите условия поиска Outlook, вы получаете в предложениях наиболее подходящую электронную почту.</span><span class="sxs-lookup"><span data-stu-id="556ca-907">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="556ca-908">**Редактор Microsoft получает обновление для настольных клиентов Word и Outlook:** мы запускаем новую модель "Щелчок для просмотра" для получения предложений по правописанию, грамматике и тонкостям стиля.</span><span class="sxs-lookup"><span data-stu-id="556ca-908">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="556ca-909">Помимо этого, добавляется отдельная карточка для просмотра предложений.</span><span class="sxs-lookup"><span data-stu-id="556ca-909">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-910">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-910">Word</span></span>

- <span data-ttu-id="556ca-911">**Редактор Microsoft получает обновление для настольных клиентов Word и Outlook:** мы запускаем новую модель "Щелчок для просмотра" для получения предложений по правописанию, грамматике и тонкостям стиля.</span><span class="sxs-lookup"><span data-stu-id="556ca-911">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="556ca-912">Помимо этого, добавляется отдельная карточка для просмотра предложений.</span><span class="sxs-lookup"><span data-stu-id="556ca-912">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-915">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-915">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-916">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-916">Excel</span></span>

- <span data-ttu-id="556ca-917">Мы устранили проблему, из-за которой при открытии файла с функцией ПУСТЬ появлялось сообщение: "Обнаружена проблема в содержимом файла "ваш_файл.xlsx".</span><span class="sxs-lookup"><span data-stu-id="556ca-917">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="556ca-918">Хотите восстановить все, что возможно?</span><span class="sxs-lookup"><span data-stu-id="556ca-918">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="556ca-919">Если вы доверяете источнику этой книги, выберите Да".</span><span class="sxs-lookup"><span data-stu-id="556ca-919">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="556ca-920">Исправлена ошибка сбоя, связанного со ссылками на надстройки XLAM и именованными диапазонами.</span><span class="sxs-lookup"><span data-stu-id="556ca-920">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="556ca-921">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="556ca-921">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="556ca-p155">Исправлена проблема, из-за которой при назначении пользователем настраиваемого стиля динамическому массиву появлялась ошибка: "Изменение части массива недопустимо". Это ограничение унаследовано из предыдущей версии и теперь удалено.</span><span class="sxs-lookup"><span data-stu-id="556ca-p155">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="556ca-924">Исправлена проблема с панелью формул Excel, которая не отображалась полностью после отключения от устройства, например с подключении или отклчючении от уадаленного сеанса или при смене монитора.</span><span class="sxs-lookup"><span data-stu-id="556ca-924">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-925">Outlook</span></span>

- <span data-ttu-id="556ca-926">Исправлена проблема, которая обеспечивала включение/отключение параметров входа по умолчанию через групповые политики.</span><span class="sxs-lookup"><span data-stu-id="556ca-926">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="556ca-927">Исправлена проблема, при которой устаревшее имя домена для отправителя сообщения электронной почты с правами помощника или менеджера сохранялось и показывалось при перемещении черновика письма между папками.</span><span class="sxs-lookup"><span data-stu-id="556ca-927">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="556ca-928">Исправлена проблем, при которой у некоторых пользователей Outlook запускался в автономном состоянии, пока они не выбирали сетевой режим работы вручную.</span><span class="sxs-lookup"><span data-stu-id="556ca-928">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="556ca-929">Исправлена проблема, когда при запуске кода VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") после включения однострочной ленты (SLR) выдавалась ошибка среды выполнения.</span><span class="sxs-lookup"><span data-stu-id="556ca-929">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="556ca-930">Исправлена проблема, при которой кнопки "OK" и "Отмена" в диалогах с автоматическими ответами были не видны в системах с высоким разрешением (например, 1750 x 1920), если выбран большой размер текста (например, 175%).</span><span class="sxs-lookup"><span data-stu-id="556ca-930">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="556ca-931">Исправлена проблема, при которой в результате отправки приглашения на собрание из пустой группы контактов в другую группу контактов появлялась ошибка.</span><span class="sxs-lookup"><span data-stu-id="556ca-931">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="556ca-932">Исправлена проблема, которая вызывала сбой при открытии определенных очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-932">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="556ca-933">Исправлена ошибка, при которой в случае, когда требуется, чтобы в групповой политике всегда была активна надстройка, надстройка мониторинга становится недоступной, чтобы не дать пользователям отключить надстройку.</span><span class="sxs-lookup"><span data-stu-id="556ca-933">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-934">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-934">PowerPoint</span></span>

- <span data-ttu-id="556ca-935">Исправлена ошибка, при которой во время слайд-шоу видео не воспроизводились автоматически.</span><span class="sxs-lookup"><span data-stu-id="556ca-935">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="556ca-936">Исправлена ошибка, при которой после загрузки PowerPoint, вставки слайда, открытия и закрытия панели комментариев, слайды в области эскизов отображались с наложением.</span><span class="sxs-lookup"><span data-stu-id="556ca-936">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-937">Проект</span><span class="sxs-lookup"><span data-stu-id="556ca-937">Project</span></span>

- <span data-ttu-id="556ca-938">Исправлена проблема, при которой оставшиеся затраты не подсчитываются правильно, если у ресурса есть несколько таблиц норм затрат.</span><span class="sxs-lookup"><span data-stu-id="556ca-938">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="556ca-939">Исправлена проблема, из-за которой дата окончания проекта не обновляется для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-939">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-940">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-940">Word</span></span>

- <span data-ttu-id="556ca-941">Исправлена проблема, из-за которой при нажатии пользователя на комментарий вокруг комментария отображалась граница.</span><span class="sxs-lookup"><span data-stu-id="556ca-941">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="556ca-942">Исправлена проблема, при которой фокус не переходил на панели комментариев, если масштаб документа был 160% или более, а панель комментариев была не видна.</span><span class="sxs-lookup"><span data-stu-id="556ca-942">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="556ca-943">Исправлена проблема, при которой комментарии для одного документа показывались в других открытых документах после переключения между открытыми документами.</span><span class="sxs-lookup"><span data-stu-id="556ca-943">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="556ca-944">Исправлена проблема, из-за которой при создании черновика комментария и привязки его к линии, на которой уже есть комментарии, то черновик имел неверный порядок по отношению к выделенному комментарию в SideTrack.</span><span class="sxs-lookup"><span data-stu-id="556ca-944">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="556ca-945">Исправлена проблема, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="556ca-945">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="556ca-946">Исправлена проблема с макросом, из-за которой AutoOpen запускался до AutoExec.</span><span class="sxs-lookup"><span data-stu-id="556ca-946">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-28"></a><span data-ttu-id="556ca-948">Версия 2009: 28 августа</span><span class="sxs-lookup"><span data-stu-id="556ca-948">Version 2009: August 28</span></span>
<span data-ttu-id="556ca-949">*Версия 2009 (сборка 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="556ca-949">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-951">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-951">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-952">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-952">Outlook</span></span>

- <span data-ttu-id="556ca-953">Исправлена проблема, из-за которой пользователи могли отправлять содержимое письма, к которому применена политика "Не пересылать", в OneNote, если выбрано несколько сообщений.</span><span class="sxs-lookup"><span data-stu-id="556ca-953">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-954">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-954">PowerPoint</span></span>

- <span data-ttu-id="556ca-955">Исправлена проблема с отключенной функцией вставки видео.</span><span class="sxs-lookup"><span data-stu-id="556ca-955">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-956">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-956">Word</span></span>

- <span data-ttu-id="556ca-957">Исправлена проблема, из-за которой пользователь не мог выйти из колонтитулов при выборе примечания.</span><span class="sxs-lookup"><span data-stu-id="556ca-957">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="556ca-958">Исправлена проблема, не позволявшая пользователям просматривать цепочки примечаний, выходивших за границы ответвления, так как прокрутка в ответвлении не работала.</span><span class="sxs-lookup"><span data-stu-id="556ca-958">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="556ca-959">Исправлена проблема, из-за которой поиск разрешенных примечаний в панели ответвления не работал.</span><span class="sxs-lookup"><span data-stu-id="556ca-959">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-960">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-960">Office Suite</span></span>

- <span data-ttu-id="556ca-961">Исправлена проблема в средстве развертывания Office, из-за которой возникал сбой конфигурации при использовании функции RemoveMSI при наличии продукта "Сообщения об ошибках в приложениях Майкрософт" Office 2007.</span><span class="sxs-lookup"><span data-stu-id="556ca-961">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="556ca-962">Исправлена проблема в диалоговом окне "Сжатие рисунка", из-за которой некоторые выбранные пользователем параметры разрешения не сохранялись.</span><span class="sxs-lookup"><span data-stu-id="556ca-962">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-21"></a><span data-ttu-id="556ca-964">Версия 2009: 21 августа</span><span class="sxs-lookup"><span data-stu-id="556ca-964">Version 2009: August 21</span></span>
<span data-ttu-id="556ca-965">*Версия 2009 (сборка 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-965">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-967">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-967">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-968">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-968">Excel</span></span>

- <span data-ttu-id="556ca-969">**Перо действий в Excel.** Перо для рукописного ввода и быстрого изменения данных</span><span class="sxs-lookup"><span data-stu-id="556ca-969">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-970">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-970">Outlook</span></span>

- <span data-ttu-id="556ca-971">**Удаление беседы владельцем сообщения.** Эта функция позволяет удалять беседы владельцу сообщения.</span><span class="sxs-lookup"><span data-stu-id="556ca-971">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-974">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-974">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-975">Доступ</span><span class="sxs-lookup"><span data-stu-id="556ca-975">Access</span></span>

- <span data-ttu-id="556ca-976">Исправлена проблема, из-за которой подключения к базе данных ODBC не работали со сторонними приложениями.</span><span class="sxs-lookup"><span data-stu-id="556ca-976">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-977">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-977">Excel</span></span>

- <span data-ttu-id="556ca-978">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="556ca-978">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="556ca-979">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="556ca-979">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-980">Outlook</span></span>

- <span data-ttu-id="556ca-981">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-981">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-982">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-982">Word</span></span>

- <span data-ttu-id="556ca-983">Исправлена проблема, из-за которой Word мог аварийно завершить работу после удаления примечаний.</span><span class="sxs-lookup"><span data-stu-id="556ca-983">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="556ca-984">Исправлена проблема, из-за которой иногда маркеры списка отображались в письме неверно.</span><span class="sxs-lookup"><span data-stu-id="556ca-984">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-14"></a><span data-ttu-id="556ca-986">Версия 2009: 14 августа</span><span class="sxs-lookup"><span data-stu-id="556ca-986">Version 2009: August 14</span></span>
<span data-ttu-id="556ca-987">*Версия 2009 (сборка 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-987">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-989">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-989">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-990">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-990">Excel</span></span>

- <span data-ttu-id="556ca-991">Исправлена проблема, из-за которой при вводе имени формулы со скобками и вызове справки с помощью клавиши F1 не отображался раздел справки, относящийся к этой формуле.</span><span class="sxs-lookup"><span data-stu-id="556ca-991">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="556ca-992">Исправлена проблема, из-за которой макросы, назначенные кнопкам, не работали после восстановления более ранней версии файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-992">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-993">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-993">Outlook</span></span>

- <span data-ttu-id="556ca-994">Это изменение исправляет проблему, из-за которой страница "Собрание" продолжала отображаться после того, как пользователь переключал вкладки со страницы "Собрание" на страницу "Помощник по планированию".</span><span class="sxs-lookup"><span data-stu-id="556ca-994">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-995">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-995">Word</span></span>

- <span data-ttu-id="556ca-996">Исправлена проблема, из-за которой неправильно отображался значок маркера.</span><span class="sxs-lookup"><span data-stu-id="556ca-996">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-august-07"></a><span data-ttu-id="556ca-998">Версия 2009: 7 августа</span><span class="sxs-lookup"><span data-stu-id="556ca-998">Version 2009: August 07</span></span>
<span data-ttu-id="556ca-999">*Версия 2009 (сборка 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-999">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1001">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1001">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1002">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1002">Outlook</span></span>

- <span data-ttu-id="556ca-1003">Исправлена проблема, из-за которой атрибуты учетной записи пользователя в Active Directory для "otherTelephone" и "otherHomePhone" не сопоставлялись с соответствующими атрибутами LDAP Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-1003">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1004">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1004">PowerPoint</span></span>

- <span data-ttu-id="556ca-1005">Исправлена проблема, из-за которой при определенных условиях пользователи не видели ленту/заголовок окна.</span><span class="sxs-lookup"><span data-stu-id="556ca-1005">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-31"></a><span data-ttu-id="556ca-1007">Версия 2008: 31 июля</span><span class="sxs-lookup"><span data-stu-id="556ca-1007">Version 2008: July 31</span></span>
<span data-ttu-id="556ca-1008">*Версия 2008 (сборка 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1008">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1010">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1010">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1011">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1011">Excel</span></span>

- <span data-ttu-id="556ca-1012">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1012">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="556ca-1013">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="556ca-1013">No conversion required.</span></span><br /><span data-ttu-id="556ca-1014">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="556ca-1014">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1015">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1015">Outlook</span></span>

- <span data-ttu-id="556ca-1016">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1016">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="556ca-1017">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="556ca-1017">No conversion required.</span></span><br /><span data-ttu-id="556ca-1018">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="556ca-1018">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1019">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1019">PowerPoint</span></span>

- <span data-ttu-id="556ca-1020">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1020">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="556ca-1021">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="556ca-1021">No conversion required.</span></span><br /><span data-ttu-id="556ca-1022">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="556ca-1022">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1023">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1023">Word</span></span>

- <span data-ttu-id="556ca-1024">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1024">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="556ca-1025">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="556ca-1025">No conversion required.</span></span><br /><span data-ttu-id="556ca-1026">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="556ca-1026">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1029">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1029">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1030">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1030">Access</span></span>

- <span data-ttu-id="556ca-1031">Была исправлена проблема, когда при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке «Слишком сложный запрос.»</span><span class="sxs-lookup"><span data-stu-id="556ca-1031">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1032">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1032">Excel</span></span>

- <span data-ttu-id="556ca-1033">Мы исправили проблему, когда при изменении порядка рядов диаграммы соответствующие флажки не были упорядочены по рядам.</span><span class="sxs-lookup"><span data-stu-id="556ca-1033">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="556ca-1034">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="556ca-1034">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1035">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1035">Outlook</span></span>

- <span data-ttu-id="556ca-1036">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="556ca-1036">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="556ca-1037">Исправлена проблема, из-за которой в Outlook некорректно отображались разрывы строк в содержимом файла Markdown.</span><span class="sxs-lookup"><span data-stu-id="556ca-1037">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1038">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1038">PowerPoint</span></span>

- <span data-ttu-id="556ca-1039">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="556ca-1039">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="556ca-1040">Мы исправили проблемы с кнопкой "формы" в PowerPoint, которая не позволяла создавать формы, когда доступ к магазину Office не был разрешен.</span><span class="sxs-lookup"><span data-stu-id="556ca-1040">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1041">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1041">Project</span></span>

- <span data-ttu-id="556ca-1042">Мы исправили проблемы, когда для списка задач SharePoint кнопки ленты на второй вкладке могли быть отключены.</span><span class="sxs-lookup"><span data-stu-id="556ca-1042">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1043">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1043">Word</span></span>

- <span data-ttu-id="556ca-1044">Мы исправили проблему, когда копия изображения с радиальным градиентом не совпадала с оригиналом.</span><span class="sxs-lookup"><span data-stu-id="556ca-1044">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="556ca-1045">Мы исправили проблему, когда при добавлении примечаний для отслеживания изменений, неожиданно открывалась область исправлений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1045">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="556ca-1046">Мы исправили проблему, когда ссылки на документы не вставлялись в поле «Примечания» через «Вставка» -> Раскрывающийся список.</span><span class="sxs-lookup"><span data-stu-id="556ca-1046">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="556ca-1047">Мы исправили проблему, когда после добавления изображения, содержащего гиперссылку, количество гиперссылок в коллекции гиперссылок VBA было наверно подсчитано.</span><span class="sxs-lookup"><span data-stu-id="556ca-1047">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-24"></a><span data-ttu-id="556ca-1049">Версия 2008: 24 июля</span><span class="sxs-lookup"><span data-stu-id="556ca-1049">Version 2008: July 24</span></span>
<span data-ttu-id="556ca-1050">*Версия 2008 (сборка 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1050">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1052">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1052">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1053">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1053">Excel</span></span>

- <span data-ttu-id="556ca-1054">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="556ca-1054">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="556ca-1055">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1055">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1058">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1058">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="556ca-1059">OneNote</span><span class="sxs-lookup"><span data-stu-id="556ca-1059">OneNote</span></span>

- <span data-ttu-id="556ca-1060">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="556ca-1060">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1061">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1061">Word</span></span>

- <span data-ttu-id="556ca-1062">Исправлена проблема, из-за которой замещающий текст в поле "Поиск" переполнялся, если окно приложения было изменено до небольшого размера.</span><span class="sxs-lookup"><span data-stu-id="556ca-1062">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="556ca-1063">Исправлена проблема, из-за которой команда "Определенные пользователи" для отслеживания изменений была отключена.</span><span class="sxs-lookup"><span data-stu-id="556ca-1063">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="556ca-1064">Исправлены случайные зависания при открытии HTML-файлов.</span><span class="sxs-lookup"><span data-stu-id="556ca-1064">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-17"></a><span data-ttu-id="556ca-1066">Версия 2008: 17 июля</span><span class="sxs-lookup"><span data-stu-id="556ca-1066">Version 2008: July 17</span></span>
<span data-ttu-id="556ca-1067">*Версия 2008 (сборка 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1067">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1069">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1069">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1070">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1070">Excel</span></span>

- <span data-ttu-id="556ca-1071">Исправлена проблема, из-за которой каждый раз, когда сводная диаграмма со скрытыми линиями выноски сохранялась и повторно открывалась, линии выноски становились видимыми.</span><span class="sxs-lookup"><span data-stu-id="556ca-1071">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="556ca-1072">Исправлена проблема, из-за которой диаграммы не всегда обновлялись ожидаемым образом, если для книги был включен параметр ForceFullCalculation с помощью VBA.</span><span class="sxs-lookup"><span data-stu-id="556ca-1072">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1073">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1073">Outlook</span></span>

- <span data-ttu-id="556ca-1074">Исправлена проблема с созданием нескольких профилей в Outlook из одного домена электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-1074">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="556ca-1075">Устранена проблема, приводившая к отсутствию значка блокировки в заголовке зашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="556ca-1075">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="556ca-1076">Устранена проблема, приводившая к удалению вложений из сообщений S/MIME при отправке в незашифрованном виде.</span><span class="sxs-lookup"><span data-stu-id="556ca-1076">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="556ca-1077">Устранена проблема, из-за которой сообщения S/MIME в виде обычного текста искажались при отправке.</span><span class="sxs-lookup"><span data-stu-id="556ca-1077">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="556ca-1078">Устранена проблема, из-за которой вложения повреждались при отправке незашифрованных сообщений S/MIME.</span><span class="sxs-lookup"><span data-stu-id="556ca-1078">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="556ca-1079">Устранена проблема, из-за которой пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="556ca-1079">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="556ca-1080">Устранена проблема, из-за которой получатели не могли сохранять сообщения с защищенными правами, даже если отправитель предоставил разрешение на сохранение.</span><span class="sxs-lookup"><span data-stu-id="556ca-1080">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="556ca-1081">Устранена проблема, приводившая к усечению некоторых подписей параметров расширенного поиска на некоторых языках.</span><span class="sxs-lookup"><span data-stu-id="556ca-1081">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1082">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1082">Project</span></span>

- <span data-ttu-id="556ca-1083">Исправлена проблема, из-за которой задачи, перечисленные в представлении доски задач, не синхронизировались с диалоговым окном "Назначение ресурсов".</span><span class="sxs-lookup"><span data-stu-id="556ca-1083">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="556ca-1084">Исправлена проблема, из-за которой при копировании и вставке задачи с несколькими зависимостями не все зависимости копировались правильно.</span><span class="sxs-lookup"><span data-stu-id="556ca-1084">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1085">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1085">Word</span></span>

- <span data-ttu-id="556ca-1086">Исправлена проблема, из-за которой команда "Корректор" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="556ca-1086">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="556ca-1087">Исправлена проблема, из-за которой команда "Показать разметку" отключалась, когда фокус находился в текстовом поле примечания.</span><span class="sxs-lookup"><span data-stu-id="556ca-1087">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="556ca-1088">Исправлена проблема в пользовательском XML, из-за которой состояние примечаний могло исчезать при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-1088">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1089">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1089">Office Suite</span></span>

- <span data-ttu-id="556ca-1090">Исправлена проблема, из-за которой после открытия пользователем нового окна приложения из панели задач и создания пустого документа создавались дополнительные файлы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1090">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="556ca-1091">Исправлена проблема, из-за которой в случае редактирования документа и утраты разрешений пользователь не уведомлялся о необходимости повторной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="556ca-1091">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-july-10"></a><span data-ttu-id="556ca-1093">Версия 2008: 10 июля</span><span class="sxs-lookup"><span data-stu-id="556ca-1093">Version 2008: July 10</span></span>
<span data-ttu-id="556ca-1094">*Версия 2008 (сборка 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1094">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1096">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1096">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1097">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1097">Outlook</span></span>

- <span data-ttu-id="556ca-1098">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если не установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="556ca-1098">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="556ca-1099">Исправлена проблема, из-за которой кнопка печати отображалась в отключенном состоянии даже при наличии у пользователя соответствующих разрешений на печать.</span><span class="sxs-lookup"><span data-stu-id="556ca-1099">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1100">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1100">Project</span></span>

- <span data-ttu-id="556ca-1101">Исправлена проблема, из-за которой при попытке сохранить файл PDF или XPS из Project в библиотеке документов SharePoint ничего не происходило.</span><span class="sxs-lookup"><span data-stu-id="556ca-1101">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1102">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1102">Word</span></span>

- <span data-ttu-id="556ca-1103">Исправлена проблема, из-за которой Word переставал отвечать на запросы после вставки текста и изображения в поле примечаний.</span><span class="sxs-lookup"><span data-stu-id="556ca-1103">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="556ca-1104">Исправлена проблема, из-за которой кнопка "Создать примечание" отключалась после удаления последнего примечания.</span><span class="sxs-lookup"><span data-stu-id="556ca-1104">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-03"></a><span data-ttu-id="556ca-1106">Версия 2007: 3 июля</span><span class="sxs-lookup"><span data-stu-id="556ca-1106">Version 2007: July 03</span></span>
<span data-ttu-id="556ca-1107">*Версия 2007 (сборка 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1107">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1109">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1109">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1110">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1110">Outlook</span></span>

- <span data-ttu-id="556ca-1111">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="556ca-1111">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="556ca-1112">**Новая функция "Поиск помещений".** Поиск конференц-залов с учетом различных возможностей. </span><span class="sxs-lookup"><span data-stu-id="556ca-1112">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1115">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1116">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1116">Excel</span></span>

- <span data-ttu-id="556ca-1117">Устранена проблема, связанная с тем, что таблицы моделей данных, созданные в некоторых версиях Excel, не отображались в представлении "Предварительный просмотр таблицы" даже при отсутствии изменений запроса, связанного с таблицей.</span><span class="sxs-lookup"><span data-stu-id="556ca-1117">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="556ca-1118">Устранена проблема, из-за которой переставали работать формулы при отключении параметра "Игнорировать тип ссылки" в диалоговом окне "Задать имя \ Применение имен".</span><span class="sxs-lookup"><span data-stu-id="556ca-1118">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="556ca-1119">Исправлена проблема, из-за которой очистка расширенного фильтра данных могла привести к потере форматирования таблицы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1119">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="556ca-1120">Исправлена проблема, из-за которой в подписи к документу вместо имени внедренного PDF-документа отображался весь путь к нему.</span><span class="sxs-lookup"><span data-stu-id="556ca-1120">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="556ca-1121">Исправлена проблема, из-за которой мог произойти сбой после отключения облачного соединителя Wolfram с последующим сохранением и повторным открытием книги Excel.</span><span class="sxs-lookup"><span data-stu-id="556ca-1121">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="556ca-1122">Исправлена проблема, вызывавшая сбой в результате загрузки Excel при включенной надстройке "Поиск решения".</span><span class="sxs-lookup"><span data-stu-id="556ca-1122">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1123">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1123">Outlook</span></span>

- <span data-ttu-id="556ca-1124">Исправлена проблема, вызывавшая зависание приложения Outlook, когда в строке "Кому" было указано более 130 получателей. Кроме того, мы повысили производительность отрисовки текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-1124">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="556ca-1125">Исправлена проблема, из-за которой в области To Do для событий длительностью более двух дней указывалось одинаковое время окончания для всех последующих дней.</span><span class="sxs-lookup"><span data-stu-id="556ca-1125">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="556ca-1126">Исправлена проблема, из-за которой у пользователей Outlook после использования общих календарей на несколько минут переставал обновляться список сообщений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1126">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1127">PowerPoint</span></span>

- <span data-ttu-id="556ca-1128">Исправлена проблема, из-за которой при вставке HTML в область текста на слайде производилась вставка в текстовое поле, созданное в верхней части слайда.</span><span class="sxs-lookup"><span data-stu-id="556ca-1128">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="556ca-1129">Исправлена проблема, из-за которой возникало необработанное исключение при выделении всех слайдов в режиме докладчика и выходе из режима докладчика с помощью клавиш ALT+TAB, возврате в слайд-шоу и щелчке по команде "Завершить слайд-шоу".</span><span class="sxs-lookup"><span data-stu-id="556ca-1129">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1130">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1130">Project</span></span>

- <span data-ttu-id="556ca-1131">Исправлена проблема, из-за которой мог возникнуть сбой при открытии определенных XML-файлов.</span><span class="sxs-lookup"><span data-stu-id="556ca-1131">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="556ca-1132">Исправлена проблема, из-за которой не удавалось открыть файл Project из библиотеки документов SharePoint, если библиотека находилась в современном режиме.</span><span class="sxs-lookup"><span data-stu-id="556ca-1132">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="556ca-1133">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="556ca-1133">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1134">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1134">Word</span></span>

- <span data-ttu-id="556ca-1135">Исправлена проблема в режиме совместного редактирования: теперь при возникновении конфликта объединения изменений при том, что пользователь уже выбрал отмену изменений, вариант сохранения или отмены изменений больше не отображается.</span><span class="sxs-lookup"><span data-stu-id="556ca-1135">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="556ca-1136">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-1136">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-26"></a><span data-ttu-id="556ca-1138">Версия 2007: 26 июня</span><span class="sxs-lookup"><span data-stu-id="556ca-1138">Version 2007: June 26</span></span>
<span data-ttu-id="556ca-1139">*Версия 2007 (сборка 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1139">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1141">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1141">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1142">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1142">Access</span></span>

- <span data-ttu-id="556ca-1143">Исправлена проблема, из-за которой диспетчер связанных таблиц запрашивал первичный ключ при обновлении связанной таблицы SQL.</span><span class="sxs-lookup"><span data-stu-id="556ca-1143">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="556ca-1144">Исправлена проблема, из-за которой запросы в редакторе запросов не отображались при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="556ca-1144">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="556ca-1145">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="556ca-1145">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1146">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1146">Outlook</span></span>

- <span data-ttu-id="556ca-1147">Исправлена проблема, из-за которой пользователи не могли "отправить как" или "отправить от имени" группы рассылки.</span><span class="sxs-lookup"><span data-stu-id="556ca-1147">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="556ca-1148">Исправлена проблема, из-за которой вставка изображения в текст сообщения с последующим сохранением сообщения в виде черновика приводила к изменению размера изображения.</span><span class="sxs-lookup"><span data-stu-id="556ca-1148">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="556ca-1149">Исправлена проблема, из-за которой кодировка текста отчета о недоставке изменялась с Юникода на ASCII после изменения темы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1149">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1150">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1150">Project</span></span>

- <span data-ttu-id="556ca-1151">Исправлена проблема, из-за которой ссылки планировщика Project в средах GCC были отключены.</span><span class="sxs-lookup"><span data-stu-id="556ca-1151">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1152">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1152">Office Suite</span></span>

- <span data-ttu-id="556ca-1153">Исправлена проблема, из-за которой текст, вставленный в изображение в формате SVG, был неудобочитаемым после добавления в файл Word, Excel или PowerPoint, сохранения и закрытия файла, а затем его повторного открытия.</span><span class="sxs-lookup"><span data-stu-id="556ca-1153">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-19"></a><span data-ttu-id="556ca-1155">Версия 2007: 19 июня</span><span class="sxs-lookup"><span data-stu-id="556ca-1155">Version 2007: June 19</span></span>
<span data-ttu-id="556ca-1156">*Версия 2007 (сборка 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1156">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1158">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1158">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1159">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1159">Excel</span></span>

- <span data-ttu-id="556ca-1160">Исправлена проблема, из-за которой CustomUI XML для настраиваемой вкладки ленты удалялся при сохранении книги в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="556ca-1160">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="556ca-1161">Исправлена проблема, из-за которой книги были доступны только для чтения, если файл рекомендовался только для чтения.</span><span class="sxs-lookup"><span data-stu-id="556ca-1161">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1162">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1162">Outlook</span></span>

- <span data-ttu-id="556ca-1163">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="556ca-1163">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="556ca-p161">Исправлена проблема, из-за которой при закрытии ранее сохраненной встречи выводилось следующее сообщение об ошибке: "Не удалось сохранить элемент, так как он был изменен другим пользователем или в другом окне. Хотите сохранить копию элемента в папке по умолчанию?"</span><span class="sxs-lookup"><span data-stu-id="556ca-p161">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="556ca-1166">Исправлена проблема, из-за которой даты в мини-календаре не выделялись полужирным шрифтом для пользователей в Японии.</span><span class="sxs-lookup"><span data-stu-id="556ca-1166">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="556ca-1167">Исправлена проблема, препятствовавшая отображению точного времени в напоминаниях календаря для собраний, до наступления которых осталось меньше недели.</span><span class="sxs-lookup"><span data-stu-id="556ca-1167">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1168">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1168">PowerPoint</span></span>

- <span data-ttu-id="556ca-1169">Исправлена проблема, из-за которой в галерее совместного редактирования не обновлялся цветовой индикатор присутствия пользователя во время совместного редактирования в реальном времени.</span><span class="sxs-lookup"><span data-stu-id="556ca-1169">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1170">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1170">Project</span></span>

- <span data-ttu-id="556ca-1171">Исправлена проблема, из-за которой процент выполнения задачи был менее 100 %, если задачи с фиксированной длительностью выполнены на 100 %, но не указано фактическое окончание.</span><span class="sxs-lookup"><span data-stu-id="556ca-1171">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1172">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1172">Word</span></span>

- <span data-ttu-id="556ca-1173">Исправлена проблема, из-за которой цвет гиперссылки HTML отображался неправильно.</span><span class="sxs-lookup"><span data-stu-id="556ca-1173">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1174">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1174">Office Suite</span></span>

- <span data-ttu-id="556ca-1175">Исправлена проблема, из-за которой URL-адреса, отличные от HTTP или HTTPS, не отображались в списке недавно использовавшихся.</span><span class="sxs-lookup"><span data-stu-id="556ca-1175">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-june-12"></a><span data-ttu-id="556ca-1177">Версия 2007: 12 июня</span><span class="sxs-lookup"><span data-stu-id="556ca-1177">Version 2007: June 12</span></span>
<span data-ttu-id="556ca-1178">*Версия 2007 (сборка 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1178">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1180">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1180">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1181">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1181">Excel</span></span>

- <span data-ttu-id="556ca-1182">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 E5/A5 или Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="556ca-1182">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="556ca-1183">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="556ca-1183">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="556ca-1184">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="556ca-1184">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="556ca-1185">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1185">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="556ca-1186">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="556ca-1186">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1189">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1189">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1190">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1190">Access</span></span>

- <span data-ttu-id="556ca-1191">Устранена проблема, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="556ca-1191">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1192">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1192">Excel</span></span>

- <span data-ttu-id="556ca-1193">Устранена проблема, из-за которой нельзя было правильно отформатировать основные линии сетки лепестковых диаграмм.</span><span class="sxs-lookup"><span data-stu-id="556ca-1193">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1194">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1194">Project</span></span>

- <span data-ttu-id="556ca-1195">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="556ca-1195">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="556ca-1196">Устранена проблема, из-за которой при сбросе или обновлении базового плана могли изменяться показатели расходов или рабочих ресурсов тех или иных этапов бюджета, и базовый план мог содержать неправильные значения статей бюджета.</span><span class="sxs-lookup"><span data-stu-id="556ca-1196">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1197">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1197">Word</span></span>

- <span data-ttu-id="556ca-1198">Исправлена проблема, из-за которой не работала функция очистки форматирования в области примечаний с помощью кнопки "Очистить форматирование" на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1198">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="556ca-1199">Исправлена проблема, из-за которой изменение размера таблицы при скрытой линейке приводило к миганию других приложений, работающих на заднем фоне.</span><span class="sxs-lookup"><span data-stu-id="556ca-1199">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="556ca-1200">Исправлена проблема, из-за которой в режиме совместного редактирования ответы на примечания иногда не отображались в области примечаний, но отображались в области изменений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1200">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="556ca-1201">Исправлена проблема, из-за которой в тех случаях, когда в Word имелся список более чем 50 часто открываемых документов, после сохранения и открытия документа отображался журнал изменений, хотя никаких изменений в документ не вносилось.</span><span class="sxs-lookup"><span data-stu-id="556ca-1201">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-05"></a><span data-ttu-id="556ca-1203">Версия 2006: 5 июня</span><span class="sxs-lookup"><span data-stu-id="556ca-1203">Version 2006: June 05</span></span>
<span data-ttu-id="556ca-1204">*Версия 2006 (сборка 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1204">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1206">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1206">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1207">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1207">Excel</span></span>

- <span data-ttu-id="556ca-1208">**Сортировка и фильтрация при совместной работе в Excel.** Теперь вы можете выполнять сортировку и фильтрацию в файле Excel при совместной работе с другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="556ca-1208">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="556ca-1209">Благодаря этой новой функции вам не будет мешать выполняемая другими пользователями сортировка и фильтрация при совместной работе с документом.</span><span class="sxs-lookup"><span data-stu-id="556ca-1209">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="556ca-1210">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="556ca-1210">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="556ca-1211">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="556ca-1211">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="556ca-1212">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="556ca-1212">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="556ca-1213">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1213">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="556ca-1214">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1214">Outlook</span></span>

- <span data-ttu-id="556ca-1215">**Быстрое повторное открытие элементов из предыдущего сеанса.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-1215">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="556ca-1216">После нормального или аварийного завершения работы Outlook при повторном открытии приложения можно быстро перезапустить его элементы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1216">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="556ca-1217">По умолчанию эта функция включена.</span><span class="sxs-lookup"><span data-stu-id="556ca-1217">This feature is on by default.</span></span> <span data-ttu-id="556ca-1218">Чтобы ее отключить, выберите "Параметры > Общие > Параметры запуска".</span><span class="sxs-lookup"><span data-stu-id="556ca-1218">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1221">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1222">Excel</span></span>

- <span data-ttu-id="556ca-1223">Исправлена проблема с неправильным применением пользовательских значений в осях на схемах.</span><span class="sxs-lookup"><span data-stu-id="556ca-1223">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="556ca-1224">Исправлена проблема с задержками при сохранении файлов с листами, содержащими несколько формул с определенными именами.</span><span class="sxs-lookup"><span data-stu-id="556ca-1224">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1225">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1225">Outlook</span></span>

- <span data-ttu-id="556ca-1226">Исправлена проблема с окном редактора метода ввода (IME), которое перекрывало вводимый с помощью IME базовый текст в случае использования нескольких мониторов с различными разрешениями.</span><span class="sxs-lookup"><span data-stu-id="556ca-1226">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="556ca-1227">Исправлена проблема, из-за которой возникал сбой при просмотре шаблона во время создания нового сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-1227">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="556ca-1228">Исправлена проблема, из-за которой пользователи не могли использовать общедоступные папки Exchange 2010 после Outlook версии 1911.</span><span class="sxs-lookup"><span data-stu-id="556ca-1228">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="556ca-1229">Исправлена проблема с отключенной кнопкой "Выбрать категорию" в календаре группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1229">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="556ca-1230">Исправлена проблема со сбоями в работе Outlook при наличии конфликтов в контактах.</span><span class="sxs-lookup"><span data-stu-id="556ca-1230">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="556ca-1231">Исправлена проблема с отсутствием раскрывающегося списка Online Archive в свойствах папки у пользователей с мониторами высокого разрешения.</span><span class="sxs-lookup"><span data-stu-id="556ca-1231">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="556ca-1232">Исправлена проблема, из-за которой в работе Outlook возникал сбой при использовании гиперссылок в электронных сообщениях в формате обычного текста.</span><span class="sxs-lookup"><span data-stu-id="556ca-1232">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="556ca-1233">Исправлена проблема, приводившая к неспособности Outlook анализировать длинные имена файлов, закодированные с помощью RFC2231.</span><span class="sxs-lookup"><span data-stu-id="556ca-1233">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="556ca-1234">Исправлена проблема периодических зависаний в Outlook при использовании средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="556ca-1234">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1235">PowerPoint</span></span>

- <span data-ttu-id="556ca-1236">Исправлена проблема с открытием файлов с сервера, на котором настроена проверка подлинности на основе форм.</span><span class="sxs-lookup"><span data-stu-id="556ca-1236">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="556ca-1237">Исправлена проблема, приводившая к ошибкам при сохранении файлов PowerPoint с внедренными диаграммами и книгами.</span><span class="sxs-lookup"><span data-stu-id="556ca-1237">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="556ca-1238">Исправлена проблема, при которой закрытая пользователем область примечаний автоматически открывалась снова.</span><span class="sxs-lookup"><span data-stu-id="556ca-1238">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="556ca-1239">Исправлена проблема, из-за которой редактор слайдов одного слайда перекрывал следующий слайд.</span><span class="sxs-lookup"><span data-stu-id="556ca-1239">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1240">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1240">Project</span></span>

- <span data-ttu-id="556ca-1241">Исправлена проблема, препятствовавшая удалению или переназначению задач, утративших связи после удаления родительского плана.</span><span class="sxs-lookup"><span data-stu-id="556ca-1241">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1242">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1242">Word</span></span>

- <span data-ttu-id="556ca-1243">Исправлена проблема несоответствия метки времени в панелях примечаний установленному в системе местному времени.</span><span class="sxs-lookup"><span data-stu-id="556ca-1243">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="556ca-1244">Исправлена проблема с отсутствием синхронизации примечаний между веб-приложением и классическим приложением.</span><span class="sxs-lookup"><span data-stu-id="556ca-1244">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2006-may-29"></a><span data-ttu-id="556ca-1246">Версия 2006: 29 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-1246">Version 2006: May 29</span></span>
<span data-ttu-id="556ca-1247">*Версия 2006 (сборка 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1247">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="556ca-1248">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1248">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1249">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1249">Outlook</span></span>

- <span data-ttu-id="556ca-1250">**Добавлены кнопки во всплывающие уведомления Outlook.** При использовании Outlook в Windows 10 кнопки быстрых действий теперь отображаются во всплывающих уведомлениях Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-1250">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1251">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1251">PowerPoint</span></span>

- <span data-ttu-id="556ca-1252">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="556ca-1252">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="556ca-1253">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="556ca-1253">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1256">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1256">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1257">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1257">Excel</span></span>

- <span data-ttu-id="556ca-1258">Исправлена проблема, из-за которой Excel иногда завершал работу при взаимодействии с OneDrive.</span><span class="sxs-lookup"><span data-stu-id="556ca-1258">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="556ca-1259">Исправлена проблема, из-за которой щелчок по гиперссылке из закладки в одной книге приводил к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="556ca-1259">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="556ca-1260">Исправлена проблема, из-за которой некоторые скопированные и вставленные ссылки диаграмм использовали сопоставленные адреса дисков вместо универсальных адресов.</span><span class="sxs-lookup"><span data-stu-id="556ca-1260">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="556ca-1261">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="556ca-1261">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1262">PowerPoint</span></span>

- <span data-ttu-id="556ca-1263">Исправлена проблема, из-за которой слайды не располагались по центру после изменения масштаба с помощью колесика мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-1263">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1264">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1264">Word</span></span>

- <span data-ttu-id="556ca-1265">Исправлена проблема, из-за которой не отображался текст, скопированный и вставленный в область примечаний.</span><span class="sxs-lookup"><span data-stu-id="556ca-1265">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="556ca-1266">Исправлена проблема, из-за которой выноска маркера примечания казалась размытой при масштабе 100 %.</span><span class="sxs-lookup"><span data-stu-id="556ca-1266">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="556ca-1267">Исправлена проблема, из-за которой включение политики "Двоичные документы и шаблоны Word 2007 и более поздних версий" вызывало сбой в некоторых случаях совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="556ca-1267">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="556ca-1268">Исправлена проблема, из-за которой файлы с длинными именами путей (больше 32 КБ) не открывались, а соответствующее сообщение об ошибке не отображалось.</span><span class="sxs-lookup"><span data-stu-id="556ca-1268">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2006-may-22"></a><span data-ttu-id="556ca-1270">Версия 2006: 22 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-1270">Version 2006: May 22</span></span>
<span data-ttu-id="556ca-1271">*Версия 2006 (сборка 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1271">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1273">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1273">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1274">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1274">Excel</span></span>

- <span data-ttu-id="556ca-1275">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1275">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="556ca-1276">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-1276">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="556ca-1277">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="556ca-1277">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="556ca-1278">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1278">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="556ca-1279">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="556ca-1279">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1280">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1280">PowerPoint</span></span>

- <span data-ttu-id="556ca-1281">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1281">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="556ca-1282">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-1282">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="556ca-1283">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="556ca-1283">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="556ca-1284">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1284">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="556ca-1285">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="556ca-1285">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1286">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1286">Word</span></span>

- <span data-ttu-id="556ca-1287">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1287">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="556ca-1288">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-1288">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="556ca-1289">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="556ca-1289">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="556ca-1290">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1290">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="556ca-1291">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="556ca-1291">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1294">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1294">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1295">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1295">Excel</span></span>

- <span data-ttu-id="556ca-1296">Исправлена проблема, из-за которой появлялось сообщение об ошибке "На эту книгу имеются ссылки из других книг, так что закрыть ее нельзя", так как надстройки загружались в алфавитном, а не в указанном пользователем порядке.</span><span class="sxs-lookup"><span data-stu-id="556ca-1296">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="556ca-1297">Исправлена проблема, из-за которой повреждалась память при управлении шрифтами между Excel и некоторыми сторонними приложениями специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="556ca-1297">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="556ca-1298">Исправлена проблема, из-за которой в Excel возникал сбой, когда надстройки запрашивали элементы хоста на листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="556ca-1298">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1299">Outlook</span></span>

- <span data-ttu-id="556ca-1300">Исправлена проблема, из-за которой событие Folder.BeforeItemMove срабатывало неправильно, когда пользователь перемещал элементы между папками.</span><span class="sxs-lookup"><span data-stu-id="556ca-1300">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="556ca-1301">Исправлена проблема, из-за которой элементы календаря, переходящие за полночь, отображались как события на весь день.</span><span class="sxs-lookup"><span data-stu-id="556ca-1301">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="556ca-1302">Исправлена проблема, из-за которой в Outlook возникал сбой, когда две надстройки добавляли кнопку в одну группу на ленте.</span><span class="sxs-lookup"><span data-stu-id="556ca-1302">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="556ca-1303">Исправлена проблема, из-за которой пользователи не могли поделиться календарем с гостевым пользователем.</span><span class="sxs-lookup"><span data-stu-id="556ca-1303">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1304">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1304">PowerPoint</span></span>

- <span data-ttu-id="556ca-1305">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-1305">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1306">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1306">Project</span></span>

- <span data-ttu-id="556ca-1307">Исправлена проблема, из-за которой Project аварийно завершал работу после нажатия кнопки "Параметры".</span><span class="sxs-lookup"><span data-stu-id="556ca-1307">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1308">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1308">Word</span></span>

- <span data-ttu-id="556ca-1309">Исправлена проблема, из-за которой гиперссылки в примечаниях не работали.</span><span class="sxs-lookup"><span data-stu-id="556ca-1309">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="556ca-1310">Исправлена проблема, из-за которой увеличение и уменьшение масштаба в области презентации приводило к разрыву между индикатором выделения с измененным масштабом и указателем мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-1310">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="556ca-1311">Исправлена проблема, из-за которой не работала вставка HTML в WordMail для календаря.</span><span class="sxs-lookup"><span data-stu-id="556ca-1311">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="556ca-1312">Исправлена проблема, из-за которой ответ на примечание в сеансе совместного редактирования иногда приводил к зависанию Word.</span><span class="sxs-lookup"><span data-stu-id="556ca-1312">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-may-15"></a><span data-ttu-id="556ca-1314">Версия 2006: 15 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-1314">Version 2006: May 15</span></span>
<span data-ttu-id="556ca-1315">*Версия 2006 (сборка 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1315">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1317">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1317">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1318">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1318">Excel</span></span>

- <span data-ttu-id="556ca-1319">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="556ca-1319">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="556ca-1320">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1320">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- <span data-ttu-id="556ca-1321">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="556ca-1321">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1322">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1322">Outlook</span></span>

- <span data-ttu-id="556ca-1323">**Поиск именно того, что нужно.** Сужайте область поиска с помощью таких параметров, как "папка", "отправитель", "дата", "сведения о вложении" и т.д.</span><span class="sxs-lookup"><span data-stu-id="556ca-1323">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1324">PowerPoint</span></span>

- <span data-ttu-id="556ca-1325">**Переключатель не нужен: наушники вам в помощь.** Используйте наушники Surface для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1325">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="556ca-1326">Важно! Чтобы использовать жесты для управления презентациями, необходимо связать наушники Surface с приложением Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="556ca-1326">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="556ca-1327">Инструкции о начале работы с приложением Surface Audio на Windows 10 находятся здесь.</span><span class="sxs-lookup"><span data-stu-id="556ca-1327">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="556ca-1328">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1328">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="556ca-1329">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="556ca-1329">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1330">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1330">Word</span></span>

- <span data-ttu-id="556ca-1331">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="556ca-1331">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1334">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1334">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1335">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1335">Excel</span></span>
- <span data-ttu-id="556ca-1336">Исправлена проблема, из-за которой увеличивалось время производительности для пользователей при удалении ими объединенных столбцов. </span><span class="sxs-lookup"><span data-stu-id="556ca-1336">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="556ca-1337">Исправлена проблема, из-за которой в списке доступных принтеров имена принтеров повторялись.</span><span class="sxs-lookup"><span data-stu-id="556ca-1337">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1338">PowerPoint</span></span>
- <span data-ttu-id="556ca-1339">Исправлена проблема, из-за которой сочетания клавиш и средства проверки орфографии не работают должным образом при использовании клавиатуры на английском языке для Швейцарии (QWERTZ).</span><span class="sxs-lookup"><span data-stu-id="556ca-1339">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1340">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1340">Word</span></span>
- <span data-ttu-id="556ca-1341">Исправлена проблема, из-за которой при добавлении нового примечания в пустой документ ничего не происходит.</span><span class="sxs-lookup"><span data-stu-id="556ca-1341">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="556ca-1342">Исправлена проблема, из-за которой вставка или обновление индекса в документе, содержащем более сотни элементов, приводит к сбою работы приложения.</span><span class="sxs-lookup"><span data-stu-id="556ca-1342">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="556ca-1343">Исправлена проблема, из-за которой файлы, в которых есть настраиваемые значения, открывались очень медленно.</span><span class="sxs-lookup"><span data-stu-id="556ca-1343">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1344">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1344">Office Suite</span></span>
- <span data-ttu-id="556ca-1345">Исправлена проблема в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени библиотеки или пути к библиотеке, рассматривались приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="556ca-1345">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-may-08"></a><span data-ttu-id="556ca-1348">Версия 2006: 8 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-1348">Version 2006: May 08</span></span>
<span data-ttu-id="556ca-1349">*Версия 2006 (сборка 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1349">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1351">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1351">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1352">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1352">Excel</span></span>

- <span data-ttu-id="556ca-1353">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="556ca-1353">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1354">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1354">Outlook</span></span>

- <span data-ttu-id="556ca-1355">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="556ca-1355">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="556ca-1356">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1356">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="556ca-1357">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="556ca-1357">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1358">PowerPoint</span></span>

- <span data-ttu-id="556ca-p173">**Доклады с анимированными изображениями GIF.** Анимированные изображения GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими. [Подробнее](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).</span><span class="sxs-lookup"><span data-stu-id="556ca-p173">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier. [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1361">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1361">Word</span></span>

- <span data-ttu-id="556ca-1362">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="556ca-1362">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1365">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1365">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="556ca-1366">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1366">Office Suite</span></span>

- <span data-ttu-id="556ca-1367">Мы изучили и устранили проблему, из-за которой развертывание Office 365 профессиональный плюс с помощью InTune было приостановлено после завершения работы ОС.</span><span class="sxs-lookup"><span data-stu-id="556ca-1367">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-01"></a><span data-ttu-id="556ca-1369">Версия 2005: 1 мая</span><span class="sxs-lookup"><span data-stu-id="556ca-1369">Version 2005: May 01</span></span>
<span data-ttu-id="556ca-1370">*Версия 2005 (сборка 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1370">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1372">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1372">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1373">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1373">Outlook</span></span>

- <span data-ttu-id="556ca-1374">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-1374">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="556ca-1375">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="556ca-1375">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="556ca-1376">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1376">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1379">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1379">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1380">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1380">Excel</span></span>

- <span data-ttu-id="556ca-1381">Исправлена проблема, из-за которой в таблице данных диаграммы неправильно отображались значения оси дат.</span><span class="sxs-lookup"><span data-stu-id="556ca-1381">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="556ca-1382">Исправлена проблема, из-за которой разрывы страниц не удавалось отключить после перехода в режим макета страницы или страничный режим.</span><span class="sxs-lookup"><span data-stu-id="556ca-1382">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="556ca-1383">Исправлена проблема, из-за которой стили линий диаграммы могли пропадать после скрытия и повторного отображения столбцов с рядами данных.</span><span class="sxs-lookup"><span data-stu-id="556ca-1383">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="556ca-1384">Вставка столбца в отфильтрованный список занимала больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="556ca-1384">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="556ca-1385">Мог возникать сбой при попытке перечислить изменения на новом листе для книги с использованием устаревшего режима "Общая книга".</span><span class="sxs-lookup"><span data-stu-id="556ca-1385">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="556ca-1386">Исправлена проблема, из-за которой пользовательское форматирование в сводных диаграммах не сохранялось при включенном параметре "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="556ca-1386">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="556ca-1387">Исправлена проблема, из-за которой пользовательское форматирование одной точки данных в сводной диаграмме не сохранялось, если был выбран параметр "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="556ca-1387">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="556ca-1388">Это исправление устраняет проблему, из-за которой символ "@", отправленный в CSV-файл, приводил к преобразованию строки после символа "@" в формулу.</span><span class="sxs-lookup"><span data-stu-id="556ca-1388">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="556ca-1389">Исправлена проблема, из-за которой десятичные значения в функции ПОСЛЕДОВ округлялись неправильно.</span><span class="sxs-lookup"><span data-stu-id="556ca-1389">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1390">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1390">Outlook</span></span>

- <span data-ttu-id="556ca-1391">Исправлена проблема, приводившая к сбою загрузки очень длинных безопасных ссылок (из-за усечения), при переходе по ним в классическом клиенте Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-1391">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="556ca-1392">Исправлена проблема, из-за которой папки Outlook с именами, содержащими двухбайтовые знаки (DBCS), периодически исчезали при синхронизации с сервером.</span><span class="sxs-lookup"><span data-stu-id="556ca-1392">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="556ca-1393">Чтобы это происходило, Outlook должен быть настроен с использованием учетной записи IMAP и работать в системе, языком которой выбран японский.</span><span class="sxs-lookup"><span data-stu-id="556ca-1393">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1394">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1394">PowerPoint</span></span>

- <span data-ttu-id="556ca-1395">Исправлена следующая проблема: если пользователь создавал комментарий, не публикуя его, и закрывал область комментариев, затем открывал новое окно, просматривал несколько слайдов, закрывал окно и повторно открывал область комментариев в исходной презентации, черновик комментария был недоступен.</span><span class="sxs-lookup"><span data-stu-id="556ca-1395">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1396">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1396">Project</span></span>

- <span data-ttu-id="556ca-1397">Исправлена проблема, из-за которой при подключении Project к Project Web App и использовании запятой в качестве десятичного разделителя метод добавления объектов TaskDependencies завершался сбоем, если добавлен параметр Lag.</span><span class="sxs-lookup"><span data-stu-id="556ca-1397">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1398">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1398">Word</span></span>

- <span data-ttu-id="556ca-1399">Исправлена проблема, из-за которой иногда не удавалось вставить комментарии в документ в режиме совместной работы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1399">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="556ca-1400">Это изменение исправляет ошибку, из-за которой карточка "Люди" мерцала при щелчке по @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="556ca-1400">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="556ca-p176">Исправлена следующая проблема: пользователю, закрывавшему документ с черновиком комментариев, предлагалось подтвердить закрытие без сохранения черновика комментариев. Если пользователь выбирал вариант "Отмена", документ закрывался вместо того, чтобы остаться открытым.</span><span class="sxs-lookup"><span data-stu-id="556ca-p176">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="556ca-1403">Исправлена проблема, из-за которой при переводе опубликованного комментария возникала ошибка "Сбой вставки переведенного текста".</span><span class="sxs-lookup"><span data-stu-id="556ca-1403">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="556ca-p177">В веб-представлении или иммерсивном средстве чтения щелчок по подсказке приводил к прокручиванию в верхнюю часть представления, хотя она уже была просмотрена. Эта проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="556ca-p177">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>
- <span data-ttu-id="556ca-1406">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-1406">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2005-april-24"></a><span data-ttu-id="556ca-1408">Версия 2005: 24 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-1408">Version 2005: April 24</span></span>
<span data-ttu-id="556ca-1409">*Версия 2005 (сборка 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1409">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1411">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1411">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1412">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1412">Excel</span></span>
- <span data-ttu-id="556ca-1413">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="556ca-1413">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="556ca-1414">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="556ca-1414">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1415">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1415">Outlook</span></span>
- <span data-ttu-id="556ca-1416">Устранена проблема, из-за которой была отключена кнопка "Классифицировать" для календарей группы на ленте Office.</span><span class="sxs-lookup"><span data-stu-id="556ca-1416">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="556ca-1417">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="556ca-1417">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1418">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1418">PowerPoint</span></span>
- <span data-ttu-id="556ca-1419">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-1419">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1420">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1420">Word</span></span>
- <span data-ttu-id="556ca-p178">При включении параметра "Показывать закладки" закладки не показывались. Проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="556ca-p178">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>
- <span data-ttu-id="556ca-1423">Это изменение устраняет проблему, из-за которой при включении параметра "Показывать коды полей вместо их значений" текст с гиперссылками может не отображаться.</span><span class="sxs-lookup"><span data-stu-id="556ca-1423">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2005-april-17"></a><span data-ttu-id="556ca-1425">Версия 2005: 17 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-1425">Version 2005: April 17</span></span>
<span data-ttu-id="556ca-1426">*Версия 2005 (сборка 12810,20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1426">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1428">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1428">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1429">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1429">Excel</span></span>
- <span data-ttu-id="556ca-1430">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="556ca-1430">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="556ca-1431">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="556ca-1431">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="556ca-1432">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="556ca-1432">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="556ca-1433">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="556ca-1433">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="556ca-1434">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="556ca-1434">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="556ca-1435">OneNote</span><span class="sxs-lookup"><span data-stu-id="556ca-1435">OneNote</span></span>
- <span data-ttu-id="556ca-1436">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="556ca-1436">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1437">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1437">Outlook</span></span>
- <span data-ttu-id="556ca-1438">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="556ca-1438">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="556ca-1439">Решает проблему, из-за которой собрания, для которых прошло более 2 месяцев, не отображали тему собрания в Помощнике по планированию.</span><span class="sxs-lookup"><span data-stu-id="556ca-1439">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="556ca-1440">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="556ca-1440">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="556ca-1441">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="556ca-1441">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="556ca-1442">Решена проблема, из-за которой правила удаления, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, стали недействительными.</span><span class="sxs-lookup"><span data-stu-id="556ca-1442">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="556ca-1443">Решает проблему, которая приводила к удалению вложений при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="556ca-1443">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1444">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1444">Project</span></span>
- <span data-ttu-id="556ca-1445">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="556ca-1445">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="556ca-1446">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1446">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="556ca-1447">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="556ca-1447">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


## <a name="version-2004-april-10"></a><span data-ttu-id="556ca-1449">Версия 2004: 10 апреля</span><span class="sxs-lookup"><span data-stu-id="556ca-1449">Version 2004: April 10</span></span>
<span data-ttu-id="556ca-1450">*Версия 2004 (сборка 12730,20024)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1450">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1452">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1452">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1453">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1453">Access</span></span>

- <span data-ttu-id="556ca-1454">**Пропустите диалоговое окно «Показать таблицу», перейдите непосредственно к панели задач и упростите добавление таблиц к отношениям и запросам.:** Добавьте таблицы и запросы, щелкнув четыре вкладки, выбрав несколько имен, выполнив поиск по тексту и перетащив из области задач, которая остается открой пока ты работаешь.</span><span class="sxs-lookup"><span data-stu-id="556ca-1454">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1455">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1455">Excel</span></span>

- <span data-ttu-id="556ca-1456">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="556ca-1456">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="556ca-1457">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="556ca-1457">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1458">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1458">Outlook</span></span>

- <span data-ttu-id="556ca-1459">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="556ca-1459">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="556ca-1460">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="556ca-1460">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="556ca-1461">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-1461">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1462">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1462">PowerPoint</span></span>

- <span data-ttu-id="556ca-1463">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="556ca-1463">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="556ca-1464">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="556ca-1464">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="556ca-1465">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="556ca-1465">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1466">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1466">Word</span></span>

- <span data-ttu-id="556ca-1467">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="556ca-1467">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="556ca-1468">Исследуйте тысячи бесплатных изображений, иконок и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="556ca-1468">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="556ca-1469">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="556ca-1469">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="556ca-1470">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="556ca-1470">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1473">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1473">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1474">Доступ</span><span class="sxs-lookup"><span data-stu-id="556ca-1474">Access</span></span>

- <span data-ttu-id="556ca-1475">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="556ca-1475">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1476">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1476">Excel</span></span>

- <span data-ttu-id="556ca-1477">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="556ca-1477">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="556ca-1478">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="556ca-1478">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="556ca-1479">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1479">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="556ca-1480">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="556ca-1480">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="556ca-1481">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="556ca-1481">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1482">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1482">Outlook</span></span>

- <span data-ttu-id="556ca-1483">Решает проблему, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-1483">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="556ca-1484">Решает проблему, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="556ca-1484">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="556ca-1485">Устраняет проблему, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1485">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="556ca-1486">Решает проблему, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="556ca-1486">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1487">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1487">PowerPoint</span></span>

- <span data-ttu-id="556ca-1488">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1488">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="556ca-1489">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="556ca-1489">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="556ca-1490">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="556ca-1490">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1491">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1491">Project</span></span>

- <span data-ttu-id="556ca-1492">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="556ca-1492">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1493">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1493">Word</span></span>

- <span data-ttu-id="556ca-1494">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="556ca-1494">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="556ca-1495">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="556ca-1495">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="556ca-1496">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1496">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="556ca-1497">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="556ca-1497">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="556ca-1498">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="556ca-1498">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-27"></a><span data-ttu-id="556ca-1500">Версия 2004: 27 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-1500">Version 2004: March 27</span></span>
<span data-ttu-id="556ca-1501">*Версия 2004 (сборка 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1501">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1503">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1503">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1504">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1504">Outlook</span></span>

- <span data-ttu-id="556ca-1505">**Новый параметр, позволяющий отключить предложения для @упоминаний при создании сообщений.** Считаете ли вы средство выбора @упоминаний скорее раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="556ca-1505">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="556ca-1506">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="556ca-1506">Now you can turn it off if you prefer.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1509">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1509">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1510">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1510">Outlook</span></span>
- <span data-ttu-id="556ca-1511">Исправлена проблема, из-за которой кнопка "Сохранить в облаке" отсутствовала в средствах работы с вложениями.</span><span class="sxs-lookup"><span data-stu-id="556ca-1511">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="556ca-1512">Исправлена проблема, из-за которой пользователи не могли добавить подпись при ответе на сообщение c цифровым управлением правами из окна инспектора, если у них не было разрешения владельца на сообщение, на которое они отвечали.</span><span class="sxs-lookup"><span data-stu-id="556ca-1512">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="556ca-1513">Исправлена проблема, из-за которой пользователи не могли добавить дополнительные вложения из расположения в Интернете в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="556ca-1513">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1514">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1514">PowerPoint</span></span>
- <span data-ttu-id="556ca-1515">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="556ca-1515">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1516">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1516">Project</span></span>
- <span data-ttu-id="556ca-1517">Исправлена проблема, из-за которой при выполнении "CustomFieldValueListGetItem" и отсутствии таблицы подстановки для настраиваемого поля создается пустая таблица подстановки, хотя этого быть не должно.</span><span class="sxs-lookup"><span data-stu-id="556ca-1517">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1518">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1518">Word</span></span>
- <span data-ttu-id="556ca-1519">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="556ca-1519">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-20"></a><span data-ttu-id="556ca-1521">Версия 2004: 20 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-1521">Version 2004: March 20</span></span>
<span data-ttu-id="556ca-1522">*Версия 2004 (сборка 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1522">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1524">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1524">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1525">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1525">Outlook</span></span>

- <span data-ttu-id="556ca-1526">**Обновление внешнего вида календаря.** В прошлом году мы обновили интерфейс почты, а сейчас пришло время улучшить внешний вид календаря!</span><span class="sxs-lookup"><span data-stu-id="556ca-1526">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="556ca-1527">Обновления придали интерфейсу свежести, но он остался вполне узнаваемым, поэтому вам, как опытному пользователю Outlook, будет легко освоить его на ходу и сразу повысить свою продуктивность.</span><span class="sxs-lookup"><span data-stu-id="556ca-1527">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="556ca-1528">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1528">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1529">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1529">PowerPoint</span></span>

- <span data-ttu-id="556ca-1530">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="556ca-1530">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1533">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1533">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1534">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1534">Excel</span></span>

- <span data-ttu-id="556ca-1535">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="556ca-1535">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1536">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1536">Outlook</span></span>

- <span data-ttu-id="556ca-1537">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="556ca-1537">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="556ca-1538">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="556ca-1538">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="556ca-1539">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="556ca-1539">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="556ca-1540">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="556ca-1540">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="556ca-1541">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="556ca-1541">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1542">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1542">Project</span></span>

- <span data-ttu-id="556ca-1543">Исправлена проблема, из-за которой событие 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) при нажатии пользователем кнопки "Деактивировать" на ленте задач группировки "Планирование" не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="556ca-1543">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="556ca-1544">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="556ca-1544">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="556ca-1545">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="556ca-1545">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="556ca-1546">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="556ca-1546">This behavior has been fixed.</span></span>

- <span data-ttu-id="556ca-1547">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="556ca-1547">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="556ca-1548">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="556ca-1548">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="556ca-1549">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="556ca-1549">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="556ca-1550">Исправлена проблема, из-за которой при печати временной шкалы с использованием календаря Hijri в представлении для печати пропускался или дублировался месяц.</span><span class="sxs-lookup"><span data-stu-id="556ca-1550">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="556ca-1551">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="556ca-1551">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1552">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1552">Word</span></span>

- <span data-ttu-id="556ca-1553">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="556ca-1553">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="556ca-1554">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="556ca-1554">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="556ca-1555">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1555">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="556ca-1556">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="556ca-1556">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="556ca-1557">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="556ca-1557">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-march-13"></a><span data-ttu-id="556ca-1559">Версия 2004: 13 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-1559">Version 2004: March 13</span></span>
<span data-ttu-id="556ca-1560">*Версия 2004 (сборка 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1560">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1562">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1562">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1563">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1563">Excel</span></span>
- <span data-ttu-id="556ca-1564">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1564">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="556ca-1565">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1565">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="556ca-1566">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1566">PowerPoint</span></span>
- <span data-ttu-id="556ca-1567">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1567">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="556ca-1568">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1568">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="556ca-1569">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1569">Word</span></span>
- <span data-ttu-id="556ca-1570">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="556ca-1570">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="556ca-1571">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1571">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1574">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1574">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="556ca-1575">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1575">Access</span></span>
- <span data-ttu-id="556ca-1576">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="556ca-1576">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1577">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1577">Excel</span></span>
- <span data-ttu-id="556ca-1578">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="556ca-1578">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="556ca-1579">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="556ca-1579">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1580">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1580">Outlook</span></span>
- <span data-ttu-id="556ca-1581">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="556ca-1581">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="556ca-1582">Исправлена проблема, из-за которой не начинался поиск при нажатии клавиши ВВОД в развернутой области поиска, и требовалось вместо этого щелкать кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="556ca-1582">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="556ca-1583">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="556ca-1583">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="556ca-1584">Project</span><span class="sxs-lookup"><span data-stu-id="556ca-1584">Project</span></span>
- <span data-ttu-id="556ca-1585">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="556ca-1585">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="556ca-1586">Исправлена ошибка, из-за которой событие OnUndoOrRedo не срабатывает без предварительного запуска метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="556ca-1586">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1587">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1587">Word</span></span>
- <span data-ttu-id="556ca-1588">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="556ca-1588">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="556ca-1589">Исправлена проблема, из-за которой выравнивание слов в документе сбивалось при попытке редактирования после печати с помощью функции "Быстрая печать".</span><span class="sxs-lookup"><span data-stu-id="556ca-1589">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="556ca-1590">Исправлена проблема с объединением двух документов в один документ.</span><span class="sxs-lookup"><span data-stu-id="556ca-1590">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="556ca-1591">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="556ca-1591">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-06"></a><span data-ttu-id="556ca-1593">Версия 2003: 6 марта</span><span class="sxs-lookup"><span data-stu-id="556ca-1593">Version 2003: March 06</span></span>
<span data-ttu-id="556ca-1594">*Версия 2003 (сборка 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1594">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1596">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1596">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1597">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1597">Outlook</span></span>

- <span data-ttu-id="556ca-1598">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не было сохранено на сервере Exchange Server и возник конфликт.</span><span class="sxs-lookup"><span data-stu-id="556ca-1598">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="556ca-1599">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="556ca-1599">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="556ca-1600">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="556ca-1600">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1601">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1601">PowerPoint</span></span>

- <span data-ttu-id="556ca-1602">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-1602">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="556ca-1603">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1603">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1604">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1604">Word</span></span>

- <span data-ttu-id="556ca-1605">Исправлена проблема с функцией сравнения для документов, защищенных для редактирования.</span><span class="sxs-lookup"><span data-stu-id="556ca-1605">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1606">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1606">Office Suite</span></span>

- <span data-ttu-id="556ca-1607">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1607">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="556ca-1608">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="556ca-1608">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-2003-february-28"></a><span data-ttu-id="556ca-1611">Версия 2003: 28 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-1611">Version 2003: February 28</span></span>
<span data-ttu-id="556ca-1612">*Версия 2003 (сборка 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1612">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1614">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1614">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1615">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1615">Outlook</span></span>

- <span data-ttu-id="556ca-1616">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="556ca-1616">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="556ca-1617">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1617">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="556ca-1618">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1618">PowerPoint</span></span>

- <span data-ttu-id="556ca-1619">**Улучшенный рукописный ввод для работы со схемами.** Создавайте отличные схемы и преобразуйте их в объекты Office, которыми можно управлять. [Подробнее](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="556ca-1619">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1622">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1622">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="556ca-1623">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1623">Excel</span></span>

- <span data-ttu-id="556ca-1624">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="556ca-1624">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1625">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1625">Outlook</span></span>

- <span data-ttu-id="556ca-1626">Исправлена проблема, приводившая к изменению даты "Последнее изменение" в файле при добавлении вложения в письмо или при сохранении вложения из письма путем перетаскивания (а не с помощью меню).</span><span class="sxs-lookup"><span data-stu-id="556ca-1626">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1627">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1627">Word</span></span>

- <span data-ttu-id="556ca-1628">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="556ca-1628">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="556ca-1629">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="556ca-1629">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="556ca-1630">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="556ca-1630">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1631">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1631">Office Suite</span></span>

- <span data-ttu-id="556ca-1632">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="556ca-1632">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-21"></a><span data-ttu-id="556ca-1634">Версия 2003: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-1634">Version 2003: February 21</span></span>
<span data-ttu-id="556ca-1635">*Версия 2003 (сборка 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1635">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1637">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1637">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="556ca-1638">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1638">Office Suite</span></span>

- <span data-ttu-id="556ca-1639">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="556ca-1639">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1642">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1642">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1643">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1643">Excel</span></span>
- <span data-ttu-id="556ca-1644">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="556ca-1644">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="556ca-1645">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="556ca-1645">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="556ca-1646">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="556ca-1646">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="556ca-1647">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="556ca-1647">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="556ca-1648">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="556ca-1648">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1649">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1649">Outlook</span></span>
- <span data-ttu-id="556ca-1650">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="556ca-1650">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="556ca-1651">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="556ca-1651">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="556ca-1652">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="556ca-1652">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1653">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1653">Word</span></span>
- <span data-ttu-id="556ca-1654">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="556ca-1654">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="556ca-p192">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега. Проблема устранена.</span><span class="sxs-lookup"><span data-stu-id="556ca-p192">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1657">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1657">Office Suite</span></span>
- <span data-ttu-id="556ca-1658">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="556ca-1658">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="556ca-1659">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="556ca-1659">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="556ca-1660">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="556ca-1660">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-february-14"></a><span data-ttu-id="556ca-1662">Версия 2003: 14 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-1662">Version 2003: February 14</span></span>
<span data-ttu-id="556ca-1663">*Версия 2003 (сборка 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1663">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1665">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1665">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1666">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1666">Outlook</span></span>

- <span data-ttu-id="556ca-1667">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="556ca-1667">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="556ca-1668">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="556ca-1668">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1669">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1669">Word</span></span>

- <span data-ttu-id="556ca-1670">**Правки от руки в инструментах рисования.** Нажмите "Рисование" и выберите перо Правки от руки, чтобы редактировать документ с помощью пальца или цифрового пера.</span><span class="sxs-lookup"><span data-stu-id="556ca-1670">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="556ca-1671">Подробнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1671">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="556ca-1672">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1672">Office Suite</span></span>

- <span data-ttu-id="556ca-1673">**Более понятные значки строки состояния.** Значки строки состояния стали понятнее</span><span class="sxs-lookup"><span data-stu-id="556ca-1673">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1676">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1676">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="556ca-1677">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1677">Outlook</span></span>

- <span data-ttu-id="556ca-1678">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря "Параметры доступности".</span><span class="sxs-lookup"><span data-stu-id="556ca-1678">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="556ca-1679">Исправлена проблема, которая могла привести к появлению оповещения "К сожалению, не удалось открыть элемент" при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="556ca-1679">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="556ca-1680">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="556ca-1680">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="556ca-1681">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="556ca-1681">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1682">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1682">PowerPoint</span></span>

- <span data-ttu-id="556ca-1683">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="556ca-1683">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1684">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1684">Word</span></span>

- <span data-ttu-id="556ca-1685">Исправлена проблема, из-за которой изображения в документах теряли прозрачность при экспорте в PDF.</span><span class="sxs-lookup"><span data-stu-id="556ca-1685">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-07"></a><span data-ttu-id="556ca-1687">Версия 2002: 7 февраля</span><span class="sxs-lookup"><span data-stu-id="556ca-1687">Version 2002: February 07</span></span>
<span data-ttu-id="556ca-1688">*Версия 2002 (сборка 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="556ca-1688">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="556ca-1690">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="556ca-1690">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1691">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1691">Access</span></span>

- <span data-ttu-id="556ca-1692">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="556ca-1692">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="556ca-1693">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="556ca-1693">Search and replace text in SQL View.</span></span> <span data-ttu-id="556ca-1694">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="556ca-1694">Select multiple tables in the Relationships window.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="556ca-1697">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="556ca-1697">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="556ca-1698">Access</span><span class="sxs-lookup"><span data-stu-id="556ca-1698">Access</span></span>

- <span data-ttu-id="556ca-p197">Это обновление исправляет проблему, из-за которой при использовании объекта ADODB.Recorder в коде VB необоснованно появлялось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="556ca-p197">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="556ca-1701">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="556ca-1701">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="556ca-1702">Excel</span><span class="sxs-lookup"><span data-stu-id="556ca-1702">Excel</span></span>

- <span data-ttu-id="556ca-1703">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="556ca-1703">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="556ca-1704">Outlook</span><span class="sxs-lookup"><span data-stu-id="556ca-1704">Outlook</span></span>

- <span data-ttu-id="556ca-1705">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="556ca-1705">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="556ca-1706">Решена проблема, приводившая к сбоям при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="556ca-1706">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="556ca-1707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="556ca-1707">PowerPoint</span></span>

- <span data-ttu-id="556ca-1708">Исправлена проблема, из-за которой после закрытия файла приложение PowerPoint не удаляет его сразу из коллекции презентаций, если запущены обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="556ca-1708">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="556ca-1709">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="556ca-1709">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="556ca-1710">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="556ca-1710">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="556ca-1711">Word</span><span class="sxs-lookup"><span data-stu-id="556ca-1711">Word</span></span>

- <span data-ttu-id="556ca-1712">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="556ca-1712">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="556ca-1713">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="556ca-1713">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="556ca-1714">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="556ca-1714">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="556ca-1715">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="556ca-1715">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="556ca-1716">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="556ca-1716">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="556ca-1717">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="556ca-1717">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="556ca-1718">Набор Office</span><span class="sxs-lookup"><span data-stu-id="556ca-1718">Office Suite</span></span>

- <span data-ttu-id="556ca-1719">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="556ca-1719">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|DevMain|Insiders| |16.0.14107.20000|version-2106-may-14|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14029.20000|version-2106-may-07|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14026.20000|version-2105-april-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14014.20002|version-2105-april-23|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14007.20002|version-2105-april-16|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14002.20000|version-2105-april-09|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13929.20016|version-2104-april-02|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13919.20002|version-2104-march-26|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13913.20000|version-2104-march-19|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13906.20000|version-2104-march-12|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
