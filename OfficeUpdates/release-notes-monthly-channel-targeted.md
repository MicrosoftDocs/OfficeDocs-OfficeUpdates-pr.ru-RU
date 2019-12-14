---
title: Заметки о выпуске для канала Monthly Channel (Targeted)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с поздним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: e7fc9ff0ba68aca9d73873c7c299fed4e7668236
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023624"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="ea77f-103">Заметки о выпуске для канала Office Monthly Channel (Targeted)</span><span class="sxs-lookup"><span data-stu-id="ea77f-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="ea77f-104">Эта статья содержит заметки о выпуске для сборок Monthly Channel (Targeted) приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows.</span><span class="sxs-lookup"><span data-stu-id="ea77f-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="ea77f-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="ea77f-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="ea77f-106">Обратите внимание, что мы часто выпускаем функции (а иногда даже исправления) для Monthly Channel (Targeted) по истечении определенного времени.</span><span class="sxs-lookup"><span data-stu-id="ea77f-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="ea77f-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="ea77f-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="ea77f-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="ea77f-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="ea77f-109">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="ea77f-110">Microsoft Teams для существующих установок Office 365 профессиональный плюс — с конца июня Microsoft Teams будет добавляться в существующие установки Office 365 профессиональный плюс (и Office 365 бизнес) при обновлении этих установок.</span><span class="sxs-lookup"><span data-stu-id="ea77f-110">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="ea77f-111">Дата добавления приложения Teams зависит от используемого канала обновления.</span><span class="sxs-lookup"><span data-stu-id="ea77f-111">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="ea77f-112">Дополнительные сведения см. в статье [Развертывание Microsoft Teams с Office 365 профессиональный плюс](https://docs.microsoft.com/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="ea77f-112">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-december-12"></a><span data-ttu-id="ea77f-116">Версия 1912: 12 декабря</span><span class="sxs-lookup"><span data-stu-id="ea77f-116">Version 1912: December 06</span></span>
<span data-ttu-id="ea77f-117">*Версия 1912 (сборка 12325.20172)*</span><span class="sxs-lookup"><span data-stu-id="ea77f-117">*Version 1912 (Build 12325.20012)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ea77f-119">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ea77f-119">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ea77f-120">Excel</span><span class="sxs-lookup"><span data-stu-id="ea77f-120">Excel</span></span>

- <span data-ttu-id="ea77f-121">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="ea77f-121">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="ea77f-122">Редактирование формул динамического массива в ячейке может привести к выравниванию текста за границами ячейки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-122">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell</span></span>

- <span data-ttu-id="ea77f-123">Функция "Текст в столбец" может не работать для некоторых вариантов локализации.</span><span class="sxs-lookup"><span data-stu-id="ea77f-123">Text to Column functionality may fail for some localizations</span></span>

- <span data-ttu-id="ea77f-124">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="ea77f-124">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="ea77f-125">Пользователи могут столкнуться с ошибкой при доступе к скрытому именованному диапазону.</span><span class="sxs-lookup"><span data-stu-id="ea77f-125">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="ea77f-126">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="ea77f-126">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="ea77f-127">Отключение аппаратного ускорения графики при использовании разрешения 4K может приводить к задержке отображения ячеек при прокрутке.</span><span class="sxs-lookup"><span data-stu-id="ea77f-127">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>

- <span data-ttu-id="ea77f-128">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-128">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="onenote"></a><span data-ttu-id="ea77f-129">OneNote</span><span class="sxs-lookup"><span data-stu-id="ea77f-129">OneNote</span></span>

- <span data-ttu-id="ea77f-130">Приложение OneNote может не открываться при использовании надстройки "Заметки к собранию" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="ea77f-130">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="ea77f-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="ea77f-131">Outlook</span></span>

- <span data-ttu-id="ea77f-132">Периодические сбои при работе с содержимым разных папок.</span><span class="sxs-lookup"><span data-stu-id="ea77f-132">Intermittent crash involving cross folder content</span></span>

- <span data-ttu-id="ea77f-133">Иногда изменяются размеры изображений, вставленных в сообщения электронной почты Outlook.</span><span class="sxs-lookup"><span data-stu-id="ea77f-133">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

- <span data-ttu-id="ea77f-134">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="ea77f-134">Added the ability to enforce S/MIME configuration via group policy</span></span>

- <span data-ttu-id="ea77f-135">Встроенные изображения могут отображаться в размере меньше предполагаемого.</span><span class="sxs-lookup"><span data-stu-id="ea77f-135">Embedded images may appear smaller than expected</span></span>

- <span data-ttu-id="ea77f-136">Метки политики хранения могут отображать срок хранения в круглых скобках.</span><span class="sxs-lookup"><span data-stu-id="ea77f-136">Retention policy labels may display the retention time period in parenthesis.</span></span>

- <span data-ttu-id="ea77f-137">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="ea77f-137">Addresses an issue that caused Policy tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="ea77f-138">В карточках контактов может появляться пустое место при использовании японского языкового пакета.</span><span class="sxs-lookup"><span data-stu-id="ea77f-138">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>

- <span data-ttu-id="ea77f-139">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-139">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ea77f-140">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ea77f-140">PowerPoint</span></span>

- <span data-ttu-id="ea77f-141">Курсор может исчезнуть после перемещения фокуса с текста.</span><span class="sxs-lookup"><span data-stu-id="ea77f-141">Cursor may disappear after moving focus from text</span></span>

- <span data-ttu-id="ea77f-142">Безопасные ссылки, ведущие из одного приложения Office в другое, могут не запускать связанное приложение.</span><span class="sxs-lookup"><span data-stu-id="ea77f-142">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="ea77f-143">В некоторых случаях прокрутка на сенсорных устройствах не работает.</span><span class="sxs-lookup"><span data-stu-id="ea77f-143">In some cases, scrolling with touch devices will not work.</span></span>

- <span data-ttu-id="ea77f-144">Если на слайде пользователя в облачном файле имеется два (или более) видеоролика, видеоизображения отображаются правильно, но когда пользователь щелкает каждое из них для воспроизведения, видеоконтент оказывается одинаковым.</span><span class="sxs-lookup"><span data-stu-id="ea77f-144">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>

- <span data-ttu-id="ea77f-145">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="ea77f-145">Margin dropdown menu may not render correctly.</span></span>

### <a name="project"></a><span data-ttu-id="ea77f-146">Project</span><span class="sxs-lookup"><span data-stu-id="ea77f-146">Project</span></span>

- <span data-ttu-id="ea77f-147">Если используется темный режим при переходе в панель инспектора в задаче, содержащей ресурс с превышением доступности, вы не сможете прочесть таблицу.</span><span class="sxs-lookup"><span data-stu-id="ea77f-147">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>

- <span data-ttu-id="ea77f-148">У пользователей может возникать ошибка лицензирования.</span><span class="sxs-lookup"><span data-stu-id="ea77f-148">Users may experience an error regarding licensing</span></span>

- <span data-ttu-id="ea77f-149">Возможна установка неверной даты кнопкой "Сегодня" в средстве выбора даты.</span><span class="sxs-lookup"><span data-stu-id="ea77f-149">The Today button in the date picker may sometimes set the incorrect date</span></span>

- <span data-ttu-id="ea77f-150">Приложение Project может аварийно завершать работу при использовании функции сравнения проектов.</span><span class="sxs-lookup"><span data-stu-id="ea77f-150">Project may crash when you use the Compare Projects feature.</span></span>

- <span data-ttu-id="ea77f-151">Настройка трудозатрат для задач без заданий округляется до одного дня.</span><span class="sxs-lookup"><span data-stu-id="ea77f-151">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="ea77f-152">Word</span><span class="sxs-lookup"><span data-stu-id="ea77f-152">Word</span></span>

- <span data-ttu-id="ea77f-153">При выборе маркера примечаний теперь должна отображаться современная область примечаний, если она скрыта в переключателе области.</span><span class="sxs-lookup"><span data-stu-id="ea77f-153">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher</span></span>

- <span data-ttu-id="ea77f-154">Иногда щелчок правой кнопкой мыши не выделяет все слово.</span><span class="sxs-lookup"><span data-stu-id="ea77f-154">Right-clicking can sometimes not result in selecting the whole word</span></span>

- <span data-ttu-id="ea77f-155">Безопасные ссылки, ведущие из одного приложения Office в другое, могут не запускать связанное приложение.</span><span class="sxs-lookup"><span data-stu-id="ea77f-155">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="ea77f-156">Диспетчер стандартных блоков может отображать неправильное оповещение: &quot;Были изменены стили, стандартные блоки&quot;.</span><span class="sxs-lookup"><span data-stu-id="ea77f-156">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

- <span data-ttu-id="ea77f-157">В некоторых темах иногда сложно определить выбранное примечание.</span><span class="sxs-lookup"><span data-stu-id="ea77f-157">Some themes may make it difficult to determine which comment is selected</span></span>

- <span data-ttu-id="ea77f-158">Курсор может оставаться активным в объекте после преобразования в предлагаемый формат.</span><span class="sxs-lookup"><span data-stu-id="ea77f-158">The cursor may remain active within an object after converting to a suggested format</span></span>

- <span data-ttu-id="ea77f-159">В некоторых ситуациях изображения в сообщениях могут быть неправильно масштабированы.</span><span class="sxs-lookup"><span data-stu-id="ea77f-159">Images in messages may be incorrectly scaled in some scenarios</span></span>

- <span data-ttu-id="ea77f-160">Область примечаний иногда перезагружается при использовании команд копирования и вставки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-160">Comment pane sometimes gets reloaded when using copy/paste.</span></span>

- <span data-ttu-id="ea77f-161">Примечания иногда вставляются в неправильном порядке.</span><span class="sxs-lookup"><span data-stu-id="ea77f-161">Comments are sometimes not pasted in the correct order.</span></span>

- <span data-ttu-id="ea77f-162">При упоминании пользователя в карточке примечания может отображаться формат JSON.</span><span class="sxs-lookup"><span data-stu-id="ea77f-162">At-mentioning a user in a comment card may show JSON.</span></span>

- <span data-ttu-id="ea77f-163">Раскрывающееся меню полей может отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="ea77f-163">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="ea77f-164">Изменение границы разделенного экрана может приводить к дополнительному разделению экрана.</span><span class="sxs-lookup"><span data-stu-id="ea77f-164">Resizing a split screen border may introduce an additional split screen.</span></span>

- <span data-ttu-id="ea77f-165">При применении к существующим документам шаблона, состоящего из многоуровневого списка с пользовательскими стилями, стили могут не сохраняться при определенных условиях.</span><span class="sxs-lookup"><span data-stu-id="ea77f-165">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>

- <span data-ttu-id="ea77f-166">Может не работать сохранение файла после слияния при определенных условиях.</span><span class="sxs-lookup"><span data-stu-id="ea77f-166">Saving a file after doing a mail merge may not work under certain conditions.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ea77f-167">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ea77f-167">Office Suite</span></span>

- <span data-ttu-id="ea77f-168">Вставка диаграммы из Excel в PowerPoint может уменьшать размер диаграммы.</span><span class="sxs-lookup"><span data-stu-id="ea77f-168">Pasting a chart from Excel to PowerPoint can reduce the size of the chart</span></span>

- <span data-ttu-id="ea77f-169">При ответе на примечание возможно вертикальное расширение текстового поля за край области.</span><span class="sxs-lookup"><span data-stu-id="ea77f-169">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane</span></span>

- <span data-ttu-id="ea77f-170">В продуктах на японском языке имя и фамилия пользователя учетной записи могут отображаться в неправильном порядке.</span><span class="sxs-lookup"><span data-stu-id="ea77f-170">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>

- <span data-ttu-id="ea77f-171">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="ea77f-171">Fixed an issue in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="ea77f-172">При наведении указателя мыши на примечание может появляться рамка вокруг примечания.</span><span class="sxs-lookup"><span data-stu-id="ea77f-172">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

- <span data-ttu-id="ea77f-173">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="ea77f-173">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-december-10"></a><span data-ttu-id="ea77f-175">Версия 1911: 10 декабря</span><span class="sxs-lookup"><span data-stu-id="ea77f-175">Version 1911: December 10</span></span>
<span data-ttu-id="ea77f-176">*Версия 1911 (сборка 12228.20364)*</span><span class="sxs-lookup"><span data-stu-id="ea77f-176">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="ea77f-177">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ea77f-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ea77f-179">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ea77f-179">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ea77f-180">Excel</span><span class="sxs-lookup"><span data-stu-id="ea77f-180">Excel</span></span>

- <span data-ttu-id="ea77f-181">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-181">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="ea77f-182">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="ea77f-182">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="ea77f-183">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ea77f-183">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

### <a name="outlook"></a><span data-ttu-id="ea77f-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="ea77f-184">Outlook</span></span>

- <span data-ttu-id="ea77f-185">**Политика именования групп.** Политика именования групп позволяет ИТ-администратору стандартизировать имена групп, созданных пользователями в организации, а также управлять ими.</span><span class="sxs-lookup"><span data-stu-id="ea77f-185">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="ea77f-186">Администратор может требовать добавления специального префикса и суффикса к имени группы при ее создании и может запретить использование определенных слов.</span><span class="sxs-lookup"><span data-stu-id="ea77f-186">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="ea77f-187">Это позволяет уменьшить использование недопустимых слов в названиях групп, а также управлять отображением групп в каталоге.</span><span class="sxs-lookup"><span data-stu-id="ea77f-187">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="ea77f-188">Политика именования также помогает организациям развертывать сайты групп для их классификации по отделам.</span><span class="sxs-lookup"><span data-stu-id="ea77f-188">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ea77f-189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ea77f-189">PowerPoint</span></span>

- <span data-ttu-id="ea77f-190">**Воспроизведение рукописного ввода.** При использовании рукописного ввода на слайдах примените анимацию воспроизведения, чтобы воспроизводить процесс рукописного ввода во время слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="ea77f-190">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="ea77f-191">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ea77f-191">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="ea77f-192">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-192">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="ea77f-193">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="ea77f-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

### <a name="word"></a><span data-ttu-id="ea77f-194">Word</span><span class="sxs-lookup"><span data-stu-id="ea77f-194">Word</span></span>

- <span data-ttu-id="ea77f-195">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="ea77f-195">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="ea77f-196">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-196">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="ea77f-197">**Создание более удобных для чтения PDF-документов.** Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="ea77f-197">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="ea77f-198">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ea77f-198">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

## <a name="resolved-issues"></a><span data-ttu-id="ea77f-199">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ea77f-199">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ea77f-200">Excel</span><span class="sxs-lookup"><span data-stu-id="ea77f-200">Excel</span></span>

- <span data-ttu-id="ea77f-201">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-201">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="ea77f-202">Мы исправили контекстное меню для сводных диаграмм для включения опции «Показать сведения».</span><span class="sxs-lookup"><span data-stu-id="ea77f-202">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="ea77f-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="ea77f-203">Outlook</span></span>

- <span data-ttu-id="ea77f-204">Исправлена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="ea77f-204">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-november-20"></a><span data-ttu-id="ea77f-206">Версия 1911: 20 ноября</span><span class="sxs-lookup"><span data-stu-id="ea77f-206">Version 1911: November 20</span></span>
<span data-ttu-id="ea77f-207">*Версия 1911 (сборка 12228.20250)*</span><span class="sxs-lookup"><span data-stu-id="ea77f-207">*Version 1911 (Build 12228.20250)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ea77f-209">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ea77f-209">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ea77f-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="ea77f-210">Outlook</span></span>

- <span data-ttu-id="ea77f-211">**Дополнительные параметры электронной почты группы.** Эта функция позволяет группам пользователей настраивать сообщения или события, получаемые и отслеживаемые в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="ea77f-211">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-november-15"></a><span data-ttu-id="ea77f-213">Версия 1911: 15 ноября</span><span class="sxs-lookup"><span data-stu-id="ea77f-213">Version 1911: November 15</span></span>
<span data-ttu-id="ea77f-214">*Версия 1911 (сборка 12228.20206)*</span><span class="sxs-lookup"><span data-stu-id="ea77f-214">*Version 1911 (Build 12228.20206)*</span></span>

## <a name="version-1911-november-12"></a><span data-ttu-id="ea77f-215">Версия 1911: 12 ноября</span><span class="sxs-lookup"><span data-stu-id="ea77f-215">Version 1911: November 12</span></span>
<span data-ttu-id="ea77f-216">*Версия 1911 (сборка 12228.20120)*</span><span class="sxs-lookup"><span data-stu-id="ea77f-216">*Version 1911 (Build 12228.20120)*</span></span>

<span data-ttu-id="ea77f-217">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ea77f-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ea77f-219">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ea77f-219">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ea77f-220">Excel</span><span class="sxs-lookup"><span data-stu-id="ea77f-220">Excel</span></span>

- <span data-ttu-id="ea77f-221">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="ea77f-221">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="ea77f-222">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ea77f-222">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="ea77f-223">Outlook</span><span class="sxs-lookup"><span data-stu-id="ea77f-223">Outlook</span></span>

- <span data-ttu-id="ea77f-224">**Отправка писем со специальными возможностями пользователям, которым они нужны.** Outlook отображает подсказку, помогающую обеспечить доступность контента при отправке пользователю, который предпочитает контент с поддержкой специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-224">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ea77f-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ea77f-225">PowerPoint</span></span>

- <span data-ttu-id="ea77f-226">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="ea77f-226">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="visio"></a><span data-ttu-id="ea77f-227">Visio</span><span class="sxs-lookup"><span data-stu-id="ea77f-227">Visio</span></span>

- <span data-ttu-id="ea77f-228">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="ea77f-228">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="ea77f-229">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ea77f-229">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="ea77f-230">Word</span><span class="sxs-lookup"><span data-stu-id="ea77f-230">Word</span></span>

- <span data-ttu-id="ea77f-231">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="ea77f-231">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ea77f-232">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ea77f-232">Office Suite</span></span>

- <span data-ttu-id="ea77f-233">**Центр отправки заменяется интерфейсом "Файлы, требующие внимания".** Центр отправки заменяется интерфейсом "Файлы, требующие внимания", доступным в приложениях Office в разделе "Файл" > "Открыть".</span><span class="sxs-lookup"><span data-stu-id="ea77f-233">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="ea77f-234">Этот новый интерфейс более современный, интегрированный и менее навязчивый по сравнению с Центром отправки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-234">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ea77f-237">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ea77f-237">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ea77f-238">Access</span><span class="sxs-lookup"><span data-stu-id="ea77f-238">Access</span></span>

- <span data-ttu-id="ea77f-239">Число записей может быть неверным.</span><span class="sxs-lookup"><span data-stu-id="ea77f-239">The record count could be incorrect.</span></span>

### <a name="excel"></a><span data-ttu-id="ea77f-240">Excel</span><span class="sxs-lookup"><span data-stu-id="ea77f-240">Excel</span></span>

- <span data-ttu-id="ea77f-241">Исправлена проблема, из-за которой удаление листов, содержащих спарклайны со ссылками на данные других листов, могло привести к обозначению файла как поврежденного при повторном открытии.</span><span class="sxs-lookup"><span data-stu-id="ea77f-241">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="ea77f-242">Изменения размеров диаграммы могут не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="ea77f-242">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="ea77f-243">Флажки могут отображаться неправильно.</span><span class="sxs-lookup"><span data-stu-id="ea77f-243">Checkboxes could not render correctly.</span></span>
- <span data-ttu-id="ea77f-244">В диалоговых окнах "Выбор источника данных" не учитывается регистр для некоторых полей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-244">Select Data Source dialogs were not case sensitive for some fields.</span></span>
- <span data-ttu-id="ea77f-245">Некоторые функции VBA возвращают ошибку в новых типах диаграмм.</span><span class="sxs-lookup"><span data-stu-id="ea77f-245">Some VBA functions would return an error on new chart.</span></span>
- <span data-ttu-id="ea77f-246">Пользователям не удается сохранять записи в формате книги Excel в Office 365.</span><span class="sxs-lookup"><span data-stu-id="ea77f-246">Users could be prevented from saving in Office 365 Excel Workbook format.</span></span>
- <span data-ttu-id="ea77f-247">Исправлена проблема, из-за которой флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-247">Resolved an issue where check box controls could shrink when using autofit to adjust row height.</span></span>
- <span data-ttu-id="ea77f-248">Устранена проблема, из-за которой можно было получить неверный результат при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="ea77f-248">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="ea77f-249">Исправлена проблема, из-за которой мог происходить сбой программы Excel при изменении защищенного файла из ненадежного сетевого ресурса.</span><span class="sxs-lookup"><span data-stu-id="ea77f-249">Resolved an issue where Excel may fail when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="ea77f-250">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="ea77f-250">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="ea77f-251">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="ea77f-251">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>
- <span data-ttu-id="ea77f-252">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="ea77f-252">We significantly improved the performance of deleting columns with merged cells.</span></span>

### <a name="onenote"></a><span data-ttu-id="ea77f-253">OneNote</span><span class="sxs-lookup"><span data-stu-id="ea77f-253">OneNote</span></span>

- <span data-ttu-id="ea77f-254">Обнаружена проблема, которая может влиять на синхронизацию локального ресурса с облачным.</span><span class="sxs-lookup"><span data-stu-id="ea77f-254">Identified an issue which could affect syncing from a local resource to a cloud resource.</span></span>

### <a name="outlook"></a><span data-ttu-id="ea77f-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="ea77f-255">Outlook</span></span>

- <span data-ttu-id="ea77f-256">Средство поиска помещений может отображать значение &quot;Нет&quot; для доступных помещений.</span><span class="sxs-lookup"><span data-stu-id="ea77f-256">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="ea77f-257">Обнаружена проблема, из-за которой поле поиска может исчезать, если лента настроена на автоматическое скрытие.</span><span class="sxs-lookup"><span data-stu-id="ea77f-257">Identified an issue where the search box could disappear when the ribbon is set to hide automatically.</span></span>
- <span data-ttu-id="ea77f-258">Обнаружена проблема, которая может вызывать нарушение цифровых подписей при подписании сообщения, содержащего вложение с цифровой подписью.</span><span class="sxs-lookup"><span data-stu-id="ea77f-258">Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment.</span></span>
- <span data-ttu-id="ea77f-259">Перенаправленная электронная почта может лишиться внедренных изображений.</span><span class="sxs-lookup"><span data-stu-id="ea77f-259">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="ea77f-260">Пользователи не могут создавать профили Outlook со строгим ограничением клиента.</span><span class="sxs-lookup"><span data-stu-id="ea77f-260">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>
- <span data-ttu-id="ea77f-261">Обнаружена проблема, из-за которой длинные имена файлов усекались после перетаскивания в текст сообщения.</span><span class="sxs-lookup"><span data-stu-id="ea77f-261">Identified an issue where long filenames were truncated after draging and droping to the message body.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ea77f-262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ea77f-262">PowerPoint</span></span>

- <span data-ttu-id="ea77f-263">Изменения размеров диаграммы могут не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="ea77f-263">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="ea77f-264">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="ea77f-264">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="ea77f-265">Обнаружена проблема, из-за которой пропорции при предварительном просмотре слайда блокировались или разблокировались неправильно.</span><span class="sxs-lookup"><span data-stu-id="ea77f-265">Identified an issue where aspect ratio for the slide preview was not being properly locked/unlocked.</span></span>

### <a name="project"></a><span data-ttu-id="ea77f-266">Project</span><span class="sxs-lookup"><span data-stu-id="ea77f-266">Project</span></span>

- <span data-ttu-id="ea77f-267">Обнаружена проблема, из-за которой примечания могут не сохраняться, если вводятся при выполнении задач обновления.</span><span class="sxs-lookup"><span data-stu-id="ea77f-267">Identified an issue where notes might not persist if entered while doing update tasks.</span></span>
- <span data-ttu-id="ea77f-268">Пользователь не может отметить задачу как завершенную, и ее выполнение остается на уровне 99 %.</span><span class="sxs-lookup"><span data-stu-id="ea77f-268">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="ea77f-269">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="ea77f-269">Overallocations are not resolved by leveling.</span></span>
- <span data-ttu-id="ea77f-270">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="ea77f-270">Identified an issue where users could get several messages when opening a read-only project.</span></span>
- <span data-ttu-id="ea77f-271">Обнаружена проблема, из-за которой файл может блокироваться пользователем, но в сообщении об ошибке не отображается имя пользователя.</span><span class="sxs-lookup"><span data-stu-id="ea77f-271">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message.</span></span>

### <a name="publisher"></a><span data-ttu-id="ea77f-272">Publisher</span><span class="sxs-lookup"><span data-stu-id="ea77f-272">Publisher</span></span>

- <span data-ttu-id="ea77f-273">Фигуры могут отображаться за пределами границы рисунка.</span><span class="sxs-lookup"><span data-stu-id="ea77f-273">Shapes could appear outside of the graphics border.</span></span>

### <a name="word"></a><span data-ttu-id="ea77f-274">Word</span><span class="sxs-lookup"><span data-stu-id="ea77f-274">Word</span></span>

- <span data-ttu-id="ea77f-275">Предложения проверки правописания не отображаются в контекстных меню.</span><span class="sxs-lookup"><span data-stu-id="ea77f-275">Proofing suggestions are not displaying in contextual menus.</span></span>
- <span data-ttu-id="ea77f-276">Изменения размеров диаграммы могут не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="ea77f-276">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="ea77f-277">Фигуры могут отображаться за пределами границы рисунка.</span><span class="sxs-lookup"><span data-stu-id="ea77f-277">Shapes could appear outside of the graphics border.</span></span>
- <span data-ttu-id="ea77f-278">Выявлена проблема с просмотром примечаний при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="ea77f-278">Identified an issue when viewing comments while using a screen reader.</span></span>
- <span data-ttu-id="ea77f-279">Обнаружена проблема, из-за которой некоторые замечания неправильно определялись как орфографические или грамматические замечания.</span><span class="sxs-lookup"><span data-stu-id="ea77f-279">Identified an issue where some critiques were misidentified as being spelling or grammar critiques.</span></span>
- <span data-ttu-id="ea77f-280">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="ea77f-280">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="ea77f-281">При использовании автозамены в языковой паре корейский-английский могут отображаться некорректные символы.</span><span class="sxs-lookup"><span data-stu-id="ea77f-281">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="ea77f-282">Поиск из области навигации может завершаться неудачей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-282">Searching from the Navigation pane may fail.</span></span>
- <span data-ttu-id="ea77f-283">Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="ea77f-283">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="ea77f-284">Политики содержимого применяются к комментариям некорректно.</span><span class="sxs-lookup"><span data-stu-id="ea77f-284">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="ea77f-285">Могут применяться метки менее строгих политик, когда приоритет должна иметь метка более строгой политики.</span><span class="sxs-lookup"><span data-stu-id="ea77f-285">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="ea77f-286">Открытие устаревших документов с последующим переходом на вкладку "Сведения" может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="ea77f-286">Opening legacy documents and then going to the Info tab can cause a failure.</span></span>
- <span data-ttu-id="ea77f-287">Обнаружена проблема, из-за которой фокус иногда не перемещается в диалоговое окно создания примечания.</span><span class="sxs-lookup"><span data-stu-id="ea77f-287">Identified an issue where a new comment dialog could sometimes not obtain focus.</span></span>
- <span data-ttu-id="ea77f-288">Не удается открыть карточку контакта после применения форматирования к @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="ea77f-288">A contact card could be prevented from opening after apply formatting to an @ mention.</span></span>
- <span data-ttu-id="ea77f-289">Выделение текста может оказаться трудной задачей.</span><span class="sxs-lookup"><span data-stu-id="ea77f-289">Highlighting text could be challenging.</span></span>
- <span data-ttu-id="ea77f-290">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ea77f-290">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="ea77f-291">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="ea77f-291">This issue affects users that create a new file and bring up the "Save as" option after clicking on the Save icon or pressing Ctrl + S.</span></span>
- <span data-ttu-id="ea77f-292">Старые комментарии, написанные темным текстом, не видны в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="ea77f-292">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="ea77f-293">Пользователю не удается перейти к отдельному элементу в редакторе.</span><span class="sxs-lookup"><span data-stu-id="ea77f-293">A user could be prevented from navigating to an individual item in the editor.</span></span>
- <span data-ttu-id="ea77f-294">Грамматические и орфографические ошибки могут не выделяться.</span><span class="sxs-lookup"><span data-stu-id="ea77f-294">Grammar or spelling errors might not be highlighted.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ea77f-295">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ea77f-295">Office Suite</span></span>

- <span data-ttu-id="ea77f-296">Некоторые рисунки могут не отображаться в предварительном просмотре или в слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="ea77f-296">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="ea77f-297">Исправлена проблема, из-за которой обновление могло блокироваться неверным сообщением об ошибке "Выполняется другая установка".</span><span class="sxs-lookup"><span data-stu-id="ea77f-297">We fixed an issue where an upgrade could be prevented by a incorrect error message of "Another install in progress".</span></span>
- <span data-ttu-id="ea77f-298">Символы катаканы могут неправильно отображаться в вертикальной надписи.</span><span class="sxs-lookup"><span data-stu-id="ea77f-298">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="ea77f-299">Попытка сохранить файл в сетевой папке, с которой потеряна связь, может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="ea77f-299">Attempting to save a file to a disconnected network share may result in a filure.</span></span>
- <span data-ttu-id="ea77f-300">Проблема с производительностью при использовании фигур в Windows 7.</span><span class="sxs-lookup"><span data-stu-id="ea77f-300">Performance issue when using Shapes on Windows 7.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

