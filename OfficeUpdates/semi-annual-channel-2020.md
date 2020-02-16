---
title: Заметки о выпусках Semi-Annual Channel в 2020 г.
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Заметки о выпусках Semi-Annual Channel для Office 365 профессиональный плюс в 2020 г. для ИТ-специалистов
ms.openlocfilehash: 974a5db6f3bfba2bb20cd75f4e35a2777ea94ca8
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978587"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="57875-103">Заметки о выпусках Semi-Annual Channel в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="57875-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="57875-104">В этих заметках о выпусках содержатся сведения о новых функциях и обновлениях, не связанных с безопасностью, включенных в обновления Semi-Annual Channel для Office 365 профессиональный плюс в 2020 г., Visio Pro для Office 365, классический клиент Project Online и Office 365 бизнес.</span><span class="sxs-lookup"><span data-stu-id="57875-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates to Office 365 ProPlus in 2020, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
>
>- <span data-ttu-id="57875-105">Мы часто выпускаем функции (а иногда даже исправления) для Semi-Annual Channel по истечении определенного времени.</span><span class="sxs-lookup"><span data-stu-id="57875-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel over a period of time.</span></span> <span data-ttu-id="57875-106">Если у вас пока нет каких-либо из перечисленных ниже возможностей, они скоро появятся.</span><span class="sxs-lookup"><span data-stu-id="57875-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="57875-107">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="57875-108">OneNote 2016 не включается по умолчанию, если пользователь, для которого применяется Semi-Annual Channel, скачивает Office 365 с портала Office и устанавливает в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="57875-108">OneNote 2016 will not be included by default when a user on the Semi-Annual Channel downloads and installs Office 365 on Windows 10 from the Office Portal.</span></span>


## <a name="version-1908-february-11"></a><span data-ttu-id="57875-109">Версия 1908: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="57875-109">Version 1908: February 11</span></span>
<span data-ttu-id="57875-110">*Версия 1908 (сборка 11929,20606)*</span><span class="sxs-lookup"><span data-stu-id="57875-110">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="57875-111">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="57875-111">Security updates listed [here](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="57875-113">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="57875-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="57875-114">Excel</span><span class="sxs-lookup"><span data-stu-id="57875-114">Excel</span></span>

- <span data-ttu-id="57875-115">Это обновление устраняет проблему, которая приводила к возникновению ошибки при использовании VBA для добавления изображения в верхний или нижний колонтитул диаграммы.</span><span class="sxs-lookup"><span data-stu-id="57875-115">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="57875-116">Исправлена ошибка, из-за которой граница элемента управления Group Box не отображалась в предварительном просмотре или при печати.</span><span class="sxs-lookup"><span data-stu-id="57875-116">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="57875-117">Пользователи могут столкнуться с ошибкой при сохранении изменений, если используются некоторые наборы символов не из английского языка.</span><span class="sxs-lookup"><span data-stu-id="57875-117">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="57875-118">Исправлена ошибка, из-за которой размер файла изображений в заголовках диаграммы увеличивался при сохранении книги, содержащей диаграмму.</span><span class="sxs-lookup"><span data-stu-id="57875-118">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="57875-119">Исправлена ошибка, приводившая к повреждению символов DBCS в книгах с перекрестными ссылками из-за синхронизации диапазонов выбора с книгой с перекрестными ссылками.</span><span class="sxs-lookup"><span data-stu-id="57875-119">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="57875-120">Устранена проблема, из-за которой элементы управления флажками могли уменьшаться при использовании автоподбора для настройки высоты строки.</span><span class="sxs-lookup"><span data-stu-id="57875-120">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="57875-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="57875-121">Outlook</span></span>

- <span data-ttu-id="57875-122">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="57875-122">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="57875-123">В ней рассматриваются проблемы, которые приводят к возникновению сбоев синхронизации при обработке сообщений о конфликтах.</span><span class="sxs-lookup"><span data-stu-id="57875-123">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="57875-124">Эта проблема связана с проблемой, из-за которой пользователи могут зависнуть на экране загружаемого профиля при запуске Outlook.</span><span class="sxs-lookup"><span data-stu-id="57875-124">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="57875-125">Устранена проблема, из-за которой пользователи видели периодические сбои при смене представлений.</span><span class="sxs-lookup"><span data-stu-id="57875-125">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="57875-126">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="57875-126">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="57875-127">[Здесь](https://support.microsoft.com/ru-RU/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) — это отдельная статья базы знаний, в которой эта статья описана в предыдущих версиях.</span><span class="sxs-lookup"><span data-stu-id="57875-127">[Here](https://support.microsoft.com/ru-RU/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="57875-128">Устраняет проблему, из-за которой пользователи столкнулись с проблемами, связанными с общими папками календаря, которые синхронизируются с PST-ФАЙЛОМ, при котором при попытке взаимодействовать с этими папками возникает ошибка.</span><span class="sxs-lookup"><span data-stu-id="57875-128">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="57875-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="57875-129">PowerPoint</span></span>

- <span data-ttu-id="57875-130">Улучшен сценарий копирования-вставки. Копирование фигуры в слайде PowerPoint и вставка его в другой слайд в цикле может произойти сбой за исключением.</span><span class="sxs-lookup"><span data-stu-id="57875-130">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="57875-131">Исправлена проблема, которая приводила к снижению производительности между пользователями совместной работы.</span><span class="sxs-lookup"><span data-stu-id="57875-131">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="57875-132">Исправлена проблема, которая могла возникнуть, когда открываемый файл постепенно содержит слайд с более чем одним встроенным медиапотоком.</span><span class="sxs-lookup"><span data-stu-id="57875-132">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="57875-133">Мы исправили проблему, из-за которой панель предупреждений системы безопасности могла не отображаться для ненадежных надстроек при первом запуске PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="57875-133">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="57875-134">Project</span><span class="sxs-lookup"><span data-stu-id="57875-134">Project</span></span>

- <span data-ttu-id="57875-135">Исправлена ошибка, из-за которой фактическая работа в расписании и плане проекта могла отличаться из-за того, что календари ресурсов не обновлялись при изменении базового календаря.</span><span class="sxs-lookup"><span data-stu-id="57875-135">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="57875-136">Word</span><span class="sxs-lookup"><span data-stu-id="57875-136">Word</span></span>

- <span data-ttu-id="57875-137">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="57875-137">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="57875-138">Набор Office</span><span class="sxs-lookup"><span data-stu-id="57875-138">Office Suite</span></span>

- <span data-ttu-id="57875-139">Это изменение касается правильной визуализации изображений после открытия поврежденного файла.</span><span class="sxs-lookup"><span data-stu-id="57875-139">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-february-11"></a><span data-ttu-id="57875-141">Версия 1902: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="57875-141">Version 1902: February 11</span></span>
<span data-ttu-id="57875-142">*Версия 1902 (сборка 11328,20526)*</span><span class="sxs-lookup"><span data-stu-id="57875-142">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="57875-143">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="57875-143">Security updates listed [here](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="57875-145">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="57875-145">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="57875-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="57875-146">Outlook</span></span>

- <span data-ttu-id="57875-147">Решает проблему, из-за которой пользователи сталкивались с алгоритмом шифрования, не поддерживаются ошибки при отправке зашифрованных писем.</span><span class="sxs-lookup"><span data-stu-id="57875-147">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="57875-148">Word</span><span class="sxs-lookup"><span data-stu-id="57875-148">Word</span></span>

- <span data-ttu-id="57875-149">Исправлен сбой в Word при удалении от устаревшего API.</span><span class="sxs-lookup"><span data-stu-id="57875-149">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

## <a name="version-1808-february-11"></a><span data-ttu-id="57875-152">Версия 1808: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="57875-152">Version 1808: February 11</span></span>
<span data-ttu-id="57875-153">*Версия 1808 (сборка 10730,20438)*</span><span class="sxs-lookup"><span data-stu-id="57875-153">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="57875-154">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="57875-154">Security updates listed [here](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-14"></a><span data-ttu-id="57875-156">Версия 1908: 14 января</span><span class="sxs-lookup"><span data-stu-id="57875-156">Version 1908: January 14</span></span>
<span data-ttu-id="57875-157">*Версия 1908 (сборка 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="57875-157">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="57875-158">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="57875-158">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="57875-160">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="57875-160">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="57875-161">Access</span><span class="sxs-lookup"><span data-stu-id="57875-161">Access</span></span>

- <span data-ttu-id="57875-162">**Отслеживание объектов базы данных.** Не теряйте из виду активную вкладку, легко перетаскивайте вкладки для изменения их порядка и закрывайте объекты базы данных одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="57875-162">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="57875-163">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="57875-163">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="57875-164">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="57875-164">Switching between them has never been easier.</span></span> [<span data-ttu-id="57875-165">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-165">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="57875-166">**Изменение масштаба стало удобнее.** Увеличивайте поле масштаба и меняйте шрифт — все эти параметры сохранятся.</span><span class="sxs-lookup"><span data-stu-id="57875-166">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="57875-167">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-167">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="57875-168">Excel</span><span class="sxs-lookup"><span data-stu-id="57875-168">Excel</span></span>

- <span data-ttu-id="57875-169">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="57875-169">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="57875-170">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="57875-170">Switching between them has never been easier.</span></span> [<span data-ttu-id="57875-171">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-171">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="57875-172">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="57875-172">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="57875-173">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="57875-173">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="57875-174">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="57875-174">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="57875-175">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="57875-175">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="57875-176">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="57875-176">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="57875-177">**Добавление живых красок в таблицы.** Вставляйте в книгу анимированные трехмерные изображения, чтобы показать, как бьется сердце, вращается планета или рычит тираннозавр.</span><span class="sxs-lookup"><span data-stu-id="57875-177">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="57875-178">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-178">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="57875-p109">**Узнайте больше о своих данных.** Новая кнопка "Идеи" позволяет находить закономерности в данных и предлагает интеллектуальные, индивидуальные решения на их основе. [Подробнее](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="57875-p109">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="57875-181">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="57875-181">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="57875-182">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="57875-182">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="57875-183">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-183">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="57875-184">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="57875-184">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="57875-185">Также можно легко находить функции, столбцы и параметры.</span><span class="sxs-lookup"><span data-stu-id="57875-185">Easily discover functions, columns, and parameters, too.</span></span>

### <a name="outlook"></a><span data-ttu-id="57875-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="57875-186">Outlook</span></span>

- <span data-ttu-id="57875-187">**Мы обновили интерфейс Outlook для вас.** Упрощенный интерфейс, ранее доступный для предпросмотра с помощью функции "Ожидается в ближайшее время", чтобы вы могли сосредоточиться на самом важном.</span><span class="sxs-lookup"><span data-stu-id="57875-187">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="57875-188">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-188">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="57875-189">**Упрощенная лента с возможностью настройки.** Наслаждайтесь одной упрощенной строкой, содержащей наиболее часто используемые кнопки.</span><span class="sxs-lookup"><span data-stu-id="57875-189">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="57875-190">Легко переключайтесь между классическим и упрощенным представлением, а также закрепляйте и открепляйте команды.</span><span class="sxs-lookup"><span data-stu-id="57875-190">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="57875-191">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-191">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="57875-192">**Продолжение работы при перемещении сообщений.** Outlook теперь перемещает сообщения в фоновом режиме, чтобы вы могли продолжать работу во время перемещения большого количества сообщений между папками.</span><span class="sxs-lookup"><span data-stu-id="57875-192">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="57875-193">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время окончания собрания на 5–10 минут раньше по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="57875-193">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="57875-194">**Выбор избранного действия.** Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="57875-194">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="57875-195">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="57875-195">How about Archive or Mark as Read?</span></span> <span data-ttu-id="57875-196">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="57875-196">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="57875-p115">**Все смогут понять, что вы имели в виду.** Если текста или статических изображений недостаточно, воспользуйтесь файлами GIF с анимацией, чтобы донести свою идею. [Подробнее](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="57875-p115">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="57875-199">**Самостоятельно выбирайте свободный или компактный макет.** С помощью компактных интервалов можно выбрать дополнительное пространство между элементами или более сжатый макет, чтобы увидеть больше элементов.</span><span class="sxs-lookup"><span data-stu-id="57875-199">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="57875-200">**Быстрое добавление учетных записей.** Благодаря улучшениям в настройке учетных записей теперь еще проще добавлять учетные записи Outlook.com и Gmail, использующие 2-факторную проверку подлинности в Outlook.</span><span class="sxs-lookup"><span data-stu-id="57875-200">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="57875-201">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-201">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="57875-202">**Забудьте об ограничениях синхронизации.** Улучшения Outlook устраняют ограничение для папок, позволяя синхронизировать общие почтовые ящики.</span><span class="sxs-lookup"><span data-stu-id="57875-202">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="57875-203">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="57875-203">PowerPoint</span></span>

- <span data-ttu-id="57875-204">**Улучшенное изменение формы.** Назовите свои фигуры, чтобы лучше управлять их трансформацией.</span><span class="sxs-lookup"><span data-stu-id="57875-204">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="57875-205">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-205">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="57875-206">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="57875-206">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="57875-207">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="57875-207">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="57875-208">**Расширение доступа к содержимому.** Нужно сделать презентации доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="57875-208">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="57875-209">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="57875-209">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="57875-210">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="57875-210">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="57875-211">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="57875-211">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="57875-212">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="57875-212">Switching between them has never been easier.</span></span> [<span data-ttu-id="57875-213">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-213">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="57875-214">**Новое расположение для видео из Интернета.** Сохраняйте видео в Microsoft Stream, чтобы его могли просматривать все пользователи организации.</span><span class="sxs-lookup"><span data-stu-id="57875-214">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="57875-215">Вставьте ссылку на видео и наслаждайтесь мультимедийной презентацией, размер которой составляет лишь часть от размера файла.</span><span class="sxs-lookup"><span data-stu-id="57875-215">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="57875-216">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-216">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="57875-217">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="57875-217">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="57875-p122">**Тест или опрос для аудитории.** Добавьте на слайд тест или опрос. Набор Office соберет и сохранит все ответы. [Подробнее](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="57875-p122">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="57875-p123">**Вставлять видео из Интернета стало еще проще.** Хотите разместить на своем слайде видео из Vimeo или YouTube? Вам потребуется лишь ссылка на страницу с видео. [Подробнее](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="57875-p123">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

### <a name="project"></a><span data-ttu-id="57875-224">Project</span><span class="sxs-lookup"><span data-stu-id="57875-224">Project</span></span>

- <span data-ttu-id="57875-225">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном месте.</span><span class="sxs-lookup"><span data-stu-id="57875-225">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="57875-226">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="57875-226">Switching between them has never been easier.</span></span> [<span data-ttu-id="57875-227">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-227">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="57875-228">Visio</span><span class="sxs-lookup"><span data-stu-id="57875-228">Visio</span></span>

- <span data-ttu-id="57875-229">**Экспорт схем процессов в Word.** Автоматически добавляйте содержимое схем, например фигуры и метаданные, в документ Word.</span><span class="sxs-lookup"><span data-stu-id="57875-229">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="57875-230">Затем настройте документ для создания руководств по обработке и использованию.</span><span class="sxs-lookup"><span data-stu-id="57875-230">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="57875-231">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-231">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="57875-232">**Переосмысление блок-схем данных.** Замечательные новые макеты для блок-схем визуализатора данных просты, лаконичны и удобны для понимания.</span><span class="sxs-lookup"><span data-stu-id="57875-232">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="57875-233">Для выбора перейдите на вкладку "Конструктор".</span><span class="sxs-lookup"><span data-stu-id="57875-233">Click the Design tab for options.</span></span>

- <span data-ttu-id="57875-234">**Встроенные наборы элементов Azure.** Разрабатывайте облачное приложение или планируйте архитектуру с помощью множества наборов элементов Azure.</span><span class="sxs-lookup"><span data-stu-id="57875-234">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="57875-235">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-235">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="57875-p128">**Попрощайтесь с неработающими ссылками Excel.** Не удается найти книгу Excel, связанную со схемой визуализатора данных? Свяжите ее повторно и продолжайте работу. [Подробнее](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="57875-p128">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="57875-239">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="57875-239">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="57875-240">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="57875-240">Switching between them has never been easier.</span></span> [<span data-ttu-id="57875-241">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-241">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="57875-242">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="57875-242">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="57875-243">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-243">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="57875-244">Word</span><span class="sxs-lookup"><span data-stu-id="57875-244">Word</span></span>

- <span data-ttu-id="57875-245">**Поддержка дополнительных цветов страниц в режиме средств обучения.** Теперь средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="57875-245">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="57875-246">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="57875-246">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="57875-p132">**Естественное редактирование с помощью Правок от руки.** Разделяйте и объединяйте слова, добавляйте новые строки и вставляйте текст одним движением пера. [Подробнее](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="57875-p132">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="57875-p133">**Преобразуйте статические документы.** Преобразуйте документы в интерактивные веб-страницы, которые прекрасно выглядят на любом устройстве и которыми легко делиться. [Подробнее](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="57875-p133">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="57875-251">**Расширение доступа к содержимому.** Нужно сделать документы доступными для людей с ограниченными возможностями?</span><span class="sxs-lookup"><span data-stu-id="57875-251">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="57875-252">Доверьте это средству проверки читаемости, которое не будет вас отвлекать.</span><span class="sxs-lookup"><span data-stu-id="57875-252">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="57875-253">Проверьте, как это работает, выбрав пункт меню Рецензирование > Проверка читаемости, и получайте требующие вашего внимания уведомления в строке состояния.</span><span class="sxs-lookup"><span data-stu-id="57875-253">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="57875-254">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="57875-254">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="57875-255">Просто воспользуйтесь полем поиска на странице "Файл" > "Главная", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="57875-255">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="57875-256">**Удобное переключение.** Новый диспетчер учетных записей отображает все ваши рабочие и личные учетные записи Office 365 в одном расположении.</span><span class="sxs-lookup"><span data-stu-id="57875-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="57875-257">Переключаться между ними стало еще проще.</span><span class="sxs-lookup"><span data-stu-id="57875-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="57875-258">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="57875-259">**Попрощайтесь со отвлекающими моментами.** Любимая функция пользователей Mac появляется в Windows.</span><span class="sxs-lookup"><span data-stu-id="57875-259">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="57875-260">Хотите, чтобы вас ничего не отвлекало от работы? Переключитесь в режим фокусировки в меню "Вид".</span><span class="sxs-lookup"><span data-stu-id="57875-260">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="57875-261">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-261">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="57875-p138">**Улучшение восприятия с помощью выделения строк.** Перемещайтесь по документу построчно, ни на что не отвлекаясь. Настройте выделение одной, трех или пяти строк одновременно. [Подробнее](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="57875-p138">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="57875-265">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="57875-265">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="57875-266">**Привлечение внимания с помощью \@@упоминаний.** Добавляйте @упоминания в комментарии, чтобы сообщить коллегам о том, что нужно их участие.</span><span class="sxs-lookup"><span data-stu-id="57875-266">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="57875-267">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-267">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="office-suite"></a><span data-ttu-id="57875-268">Набор Office</span><span class="sxs-lookup"><span data-stu-id="57875-268">Office Suite</span></span>

- <span data-ttu-id="57875-269">**Быстрый поиск файла.** Ищете файл, с которым недавно работали?</span><span class="sxs-lookup"><span data-stu-id="57875-269">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="57875-270">Просто воспользуйтесь полем поиска на вкладке "Файл" > "Открыть", чтобы найти нужный файл.</span><span class="sxs-lookup"><span data-stu-id="57875-270">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="57875-271">**Сохранение изменений по мере внесения.** Отправляйте свои файлы в OneDrive, чтобы обеспечить автоматическое сохранение всех обновлений.</span><span class="sxs-lookup"><span data-stu-id="57875-271">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="57875-272">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="57875-272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="57875-273">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-273">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="57875-274">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="57875-274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="57875-275">**Установка Microsoft Teams.** Microsoft Teams по умолчанию устанавливается для существующих экземпляров Office 365 профессиональный плюс.</span><span class="sxs-lookup"><span data-stu-id="57875-275">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="57875-276">Подробнее</span><span class="sxs-lookup"><span data-stu-id="57875-276">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="57875-279">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="57875-279">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="57875-280">Access</span><span class="sxs-lookup"><span data-stu-id="57875-280">Access</span></span>

- <span data-ttu-id="57875-281">Это обновление исправляет проблему, из-за которой агрегатная функция, например, Sum, может обрезать результат до целого значения.</span><span class="sxs-lookup"><span data-stu-id="57875-281">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="57875-282">Это обновление исправляет проблему, из-за которой запрос на объединение, включающий ссылки на удаленные таблицы (например, таблицы SQL Server), может приводить к закрытию и перезапуску Access.</span><span class="sxs-lookup"><span data-stu-id="57875-282">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="57875-283">Это обновление исправляет проблему в Microsoft Access, которая может приводить к ошибке &quot;Запрос поврежден&quot; при выполнении запроса на обновление или использовании оператора UPDATE в SQL.</span><span class="sxs-lookup"><span data-stu-id="57875-283">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="57875-284">Excel</span><span class="sxs-lookup"><span data-stu-id="57875-284">Excel</span></span>

- <span data-ttu-id="57875-285">На нидерландском языке подсказка клавиш для заголовка документа изменена на сочетание ALT+G.</span><span class="sxs-lookup"><span data-stu-id="57875-285">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="57875-286">Устранена проблема в Excel, из-за которой при выполнении макросов, присвоенных фигурам или элементам управления формы, выводятся неправильные сообщения об ошибке или эти макросы работают в неправильном целевом диапазоне.</span><span class="sxs-lookup"><span data-stu-id="57875-286">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="57875-287">Решена проблема, при которой содержимое диалогового окна "Поиск и замена" изменялось, если курсор находился в нем после нахождения первого элемента.</span><span class="sxs-lookup"><span data-stu-id="57875-287">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="57875-288">Исправлена проблема, из-за которой изменение способа сортировки сводной таблицы и ее обновление в сеансе совместного редактирования с другими пользователями могло приводить к сбою.</span><span class="sxs-lookup"><span data-stu-id="57875-288">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="57875-289">Исправлена проблема, при которой для фильтра сводной таблицы OLAP было задано значение, удаленное из куба.</span><span class="sxs-lookup"><span data-stu-id="57875-289">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="57875-290">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм.</span><span class="sxs-lookup"><span data-stu-id="57875-290">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="57875-291">Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="57875-291">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="57875-292">Устранена проблема, приводившая к нарушению синхронизации каскадных и воронкообразных диаграмм с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="57875-292">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="57875-293">Исправлена проблема с конфликтом слияния в Excel, из-за которой пользователям предлагалось повторно открыть книгу, чтобы внести изменения.</span><span class="sxs-lookup"><span data-stu-id="57875-293">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="57875-294">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="57875-294">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="57875-295">Исправлена проблема, которая была причиной ошибки времени выполнения макроса при активации свернутых окон.</span><span class="sxs-lookup"><span data-stu-id="57875-295">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="57875-296">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="57875-296">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="57875-297">Устранена проблема, из-за которой вырезание и вставка в таблице не выполняются при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="57875-297">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="57875-298">Решена проблема, вызывавшая прерывание совместного редактирования при изменении настраиваемых свойств с помощью макросов.</span><span class="sxs-lookup"><span data-stu-id="57875-298">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="57875-299">Существовала проблема, не позволявшая выбирать элементы из поля со списком в форме WPF (Windows Presentation Foundation), открытом надстройкой.</span><span class="sxs-lookup"><span data-stu-id="57875-299">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="57875-300">Решена проблема, из-за которой мог происходить сбой при поиске последних файлов с неоткрытой книгой.</span><span class="sxs-lookup"><span data-stu-id="57875-300">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="57875-301">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="57875-301">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="57875-302">Значительно повышена производительность при удалении столбцов с объединенными ячейками.</span><span class="sxs-lookup"><span data-stu-id="57875-302">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="57875-303">Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="57875-303">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="57875-304">Исправлена проблема, из-за которой функция Lookup может возвращать ошибку.</span><span class="sxs-lookup"><span data-stu-id="57875-304">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="57875-305">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office.</span><span class="sxs-lookup"><span data-stu-id="57875-305">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="57875-306">Проблема низкой производительности при нажатии кнопки "Цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="57875-306">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="57875-307">Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати.</span><span class="sxs-lookup"><span data-stu-id="57875-307">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="57875-308">При изменении защищенного файла из ненадежного сетевого ресурса могут возникать проблемы в Excel.</span><span class="sxs-lookup"><span data-stu-id="57875-308">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="57875-309">Значительно повышена производительность фильтрации по цвету.</span><span class="sxs-lookup"><span data-stu-id="57875-309">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="57875-310">Устранена проблема, мешавшая вставке гиперссылок в некоторых защищенных листах.</span><span class="sxs-lookup"><span data-stu-id="57875-310">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="57875-311">Поддерживается отображение более 16 надстроек при просмотре в диспетчере надстроек.</span><span class="sxs-lookup"><span data-stu-id="57875-311">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="57875-312">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="57875-312">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="57875-313">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="57875-313">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="57875-314">Это обновление устраняет ошибку, из-за которой документы Office могут не отправляться в OneDrive для бизнеса и приходит сообщение "Не удалось выполнить отправку".</span><span class="sxs-lookup"><span data-stu-id="57875-314">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="57875-315">Устранена проблема в функции "Идеи" для Excel, приводившая к ошибке при загрузке надстройки путем нажатия на кнопку "Идеи" в клиенте Win32.</span><span class="sxs-lookup"><span data-stu-id="57875-315">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="57875-316">Outlook</span><span class="sxs-lookup"><span data-stu-id="57875-316">Outlook</span></span>

- <span data-ttu-id="57875-317">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="57875-317">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="57875-318">Исправлена проблема, из-за которой обновление в почтовых ящиках пользователей обычной проверки подлинности до современной приводило к привязыванию неправильной учетной записи к профилю Outlook.</span><span class="sxs-lookup"><span data-stu-id="57875-318">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="57875-319">Исправлена проблема, которая была причиной доступа веб-надстроек к сообщениям с управляемыми цифровыми правами, когда это не предполагалось.</span><span class="sxs-lookup"><span data-stu-id="57875-319">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="57875-320">Исправлена проблема, из-за которой URL-адреса не открывались при простом наведении на некоторые безопасные ссылки.</span><span class="sxs-lookup"><span data-stu-id="57875-320">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="57875-321">Обновлена логика блокировки вложений в Outlook, чтобы также блокировать вложения Python.</span><span class="sxs-lookup"><span data-stu-id="57875-321">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="57875-322">Исправлена проблема, из-за которой у подмножества пользователей POP3 сообщения электронной почты выводятся в виде обычного текста, независимо от настроек.</span><span class="sxs-lookup"><span data-stu-id="57875-322">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="57875-323">Это исправление восстановит сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="57875-323">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="57875-324">Решена проблема, из-за которой возникала ошибка доступа при копировании элементов из основного календаря в календарь группы.</span><span class="sxs-lookup"><span data-stu-id="57875-324">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="57875-325">Исправлена проблема, из-за которой пользователям были недоступны предложения расположений при использовании средства чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="57875-325">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="57875-326">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="57875-326">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="57875-327">Решена проблема, вызывавшая утечку памяти при очень продолжительном сеансе Outlook.</span><span class="sxs-lookup"><span data-stu-id="57875-327">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="57875-328">Исправлена проблема, из-за которой при открытии диалогового окна "Правила" появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="57875-328">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="57875-329">Решена проблема, вызывавшая сбой в Outlook при взаимодействии пользователей с определенными безопасными ссылками.</span><span class="sxs-lookup"><span data-stu-id="57875-329">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="57875-330">Исправлена проблема, из-за которой менеджеры не могли установить, ответил ли участник на предоставленное приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="57875-330">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="57875-331">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="57875-331">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="57875-332">Исправлена проблема, приводившая к отображению для пользователей пустого окна сообщения с кнопкой "ОК" при обращении в службу поддержки в контексте создания учетной записи.</span><span class="sxs-lookup"><span data-stu-id="57875-332">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="57875-333">Это изменение позволяет администраторам включать политику, предпочитающую указанную учетную запись электронной почты в запросах проверки подлинности службы автообнаружения вместо имени участника-пользователя (UPN).</span><span class="sxs-lookup"><span data-stu-id="57875-333">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="57875-334">По умолчанию при автообнаружении предпочтение отдается UPN учетной записи (при наличии).</span><span class="sxs-lookup"><span data-stu-id="57875-334">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="57875-335">Исправлена проблема, вызывавшая сбой поиска в современных группах.</span><span class="sxs-lookup"><span data-stu-id="57875-335">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="57875-336">Исправлена проблема, приводившая к зависанию пользователей Outlook в состоянии "Требуется пароль" в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="57875-336">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="57875-337">Исправлена проблема, из-за которой пользователям предлагались помещения для собраний, проводимых в период времени, когда эти помещения недоступны.</span><span class="sxs-lookup"><span data-stu-id="57875-337">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="57875-338">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="57875-338">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="57875-339">Исправлена проблема для неанглоязычных пользователей, из-за которой строка темы в почте отображалась очень маленькой.</span><span class="sxs-lookup"><span data-stu-id="57875-339">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="57875-340">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="57875-340">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="57875-341">Исправлена проблема, приводившая к сбою при попытке пользователей создать правило на основе сообщения о пропущенной беседе.</span><span class="sxs-lookup"><span data-stu-id="57875-341">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="57875-342">Исправлена проблема с выбором алгоритма SMIME.</span><span class="sxs-lookup"><span data-stu-id="57875-342">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="57875-343">Исправлена проблема, из-за которой подсказки политики не отображались при использовании другого отправителя.</span><span class="sxs-lookup"><span data-stu-id="57875-343">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="57875-344">Исправлена проблема, из-за которой наблюдалась утечка памяти в процессе Outlook.</span><span class="sxs-lookup"><span data-stu-id="57875-344">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="57875-345">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="57875-345">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="57875-346">Устранена проблема, которая приводила к периодическому сбою поиска в текущей папке.</span><span class="sxs-lookup"><span data-stu-id="57875-346">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="57875-347">Исправлена проблема, из-за которой некоторые пользователи сталкивались с ошибками проверки подлинности при попытке получить свои облачные параметры для Outlook.</span><span class="sxs-lookup"><span data-stu-id="57875-347">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="57875-348">Решена проблема, вызывавшая зависание интерфейса отзывов о поиске. </span><span class="sxs-lookup"><span data-stu-id="57875-348">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="57875-349">Решена проблема, из-за которой происходил сбой при обработке некоторых ответов автообнаружения.</span><span class="sxs-lookup"><span data-stu-id="57875-349">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="57875-350">Исправлена проблема, вызывавшая периодические сбои при обновлении сведений о присутствии.</span><span class="sxs-lookup"><span data-stu-id="57875-350">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="57875-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="57875-351">PowerPoint</span></span>

- <span data-ttu-id="57875-352">Устранена проблема, из-за которой некоторые надстройки создавали непредвиденные ошибки вокруг фигур в диаграммах.</span><span class="sxs-lookup"><span data-stu-id="57875-352">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="57875-353">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="57875-353">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="57875-354">Это изменение восстанавливает доступное имя для элементов управления видео в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="57875-354">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="57875-355">Исправлена проблема, из-за которой мог блокироваться запуск некоторых анимаций.</span><span class="sxs-lookup"><span data-stu-id="57875-355">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="57875-356">Исправлена проблема, из-за которой при копировании слайда из одной презентации в другую могли появляться дубликаты образцов.</span><span class="sxs-lookup"><span data-stu-id="57875-356">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="57875-357">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="57875-357">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="57875-358">Исправление проблем с надежностью. Устранена проблема, из-за которой надстройка стороннего поставщика могла вызывать сбой PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="57875-358">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="57875-359">Исправлена проблема, из-за которой не удавалось правильно повернуть полуширинные знаки катаканы при использовании вертикальных текстовых полей в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="57875-359">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="57875-360">Project</span><span class="sxs-lookup"><span data-stu-id="57875-360">Project</span></span>

- <span data-ttu-id="57875-361">Исправлена проблема, чтобы разрешить пользователям в Windows 7 открывать проекты из Project Web App и сайтов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="57875-361">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="57875-362">Обнаружена проблема, из-за которой пользователи могли получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="57875-362">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="57875-363">Команда "Выровнять все" не устраняет должным образом превышение доступности ресурсов.</span><span class="sxs-lookup"><span data-stu-id="57875-363">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="57875-364">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="57875-364">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="57875-365">Visio</span><span class="sxs-lookup"><span data-stu-id="57875-365">Visio</span></span>

- <span data-ttu-id="57875-366">Экспорт в формате SVG из Visio не работал для различных фигур.</span><span class="sxs-lookup"><span data-stu-id="57875-366">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="57875-367">Word</span><span class="sxs-lookup"><span data-stu-id="57875-367">Word</span></span>

- <span data-ttu-id="57875-368">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="57875-368">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="57875-369">Ссылки cid: теперь связь с изображениями из сообщений Outlook может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="57875-369">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="57875-370">Исправлена проблема, из-за которой могли возникать проблемы с масштабированием при печати на принтерах Deskjet.</span><span class="sxs-lookup"><span data-stu-id="57875-370">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="57875-371">Исправлена проблема с отслеживанием изменений, которые иногда переходят в режим бесконечного цикла. </span><span class="sxs-lookup"><span data-stu-id="57875-371">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="57875-372">Исправлены различные проблемы, из-за которых приложение может зависнуть при завершении работы.</span><span class="sxs-lookup"><span data-stu-id="57875-372">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="57875-373">Также исправлены некоторые ошибки, связанные с надстройками.</span><span class="sxs-lookup"><span data-stu-id="57875-373">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="57875-374">Набор Office</span><span class="sxs-lookup"><span data-stu-id="57875-374">Office Suite</span></span>

- <span data-ttu-id="57875-375">Исправлена проблема с неправильным определением названия новой эры "Рэйва" в хирагана и кандзи как выражения с опечаткой или грамматической ошибкой.</span><span class="sxs-lookup"><span data-stu-id="57875-375">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="57875-376">Исправлена проблема, из-за которой пользователи получали сообщение "Не удалось предоставить общий доступ" при попытке поделиться файлами, хранящимися в SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="57875-376">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="57875-377">Исправлена проблема, которая могла приводить к потере данных в сеансах, включающих как совместное редактирование, так и редактирование в автономном режиме в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="57875-377">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="57875-378">Исправлена проблема, из-за которой мог произойти сбой при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="57875-378">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="57875-379">Исправление позволяет пользователям PowerPoint избежать ошибки при попытке онлайн-презентации.</span><span class="sxs-lookup"><span data-stu-id="57875-379">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="57875-380">В некоторых случаях файл SharePoint, сохраненный с помощью модуля синхронизации, отображал состояние "Сохранено", но в действительности изменения не сохранялись. Это приводило к потере данных.</span><span class="sxs-lookup"><span data-stu-id="57875-380">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="57875-381">Решена проблема, из-за которой пользователям не удается сохранять документы Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="57875-381">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="57875-382">Эта проблема возникает у пользователей, создающих файл и использующих параметр "Сохранить как диалоговое окно", после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="57875-382">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="57875-383">Устранена проблема с быстродействием Win7, из-за которой вставленная коллекция фигур с ленты во всех приложениях отображалась примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="57875-383">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="57875-384">Исправлена ошибка, из-за которой сведения о специальных возможностях не отображались в области сведений представления Backstage.</span><span class="sxs-lookup"><span data-stu-id="57875-384">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="57875-385">Повышена надежность процесса обновления Office в отношении целостности реестра.</span><span class="sxs-lookup"><span data-stu-id="57875-385">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="57875-386">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="57875-386">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="57875-387">Исправлена проблема, из-за которой сообщения об обновлениях Office отображаются на языке, отличном от ожидаемого.</span><span class="sxs-lookup"><span data-stu-id="57875-387">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="57875-388">В дальнейшем сообщения об обновлениях Office будут соответствовать языку интерфейса Windows.</span><span class="sxs-lookup"><span data-stu-id="57875-388">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="57875-389">Исправлена проблема, из-за которой обновление в некоторых случаях не применялось, если пользователь не являлся администратором, а системная учетная запись не была подключена к сети.</span><span class="sxs-lookup"><span data-stu-id="57875-389">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="57875-390">При определенных обстоятельствах ярлыки Office могут исчезнуть после обновления.</span><span class="sxs-lookup"><span data-stu-id="57875-390">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="57875-391">Это обновление повышает надежность при публикации ярлыков Office.</span><span class="sxs-lookup"><span data-stu-id="57875-391">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="57875-392">Исправлена проблема, из-за которой обновления могли неожиданно блокироваться в сетях с лимитным тарифным планом.</span><span class="sxs-lookup"><span data-stu-id="57875-392">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="57875-393">Исправление ошибки с параметром крайнего срока обновления в GPO и средстве ODT, из-за которой относительный крайний срок соблюдается только при его первой настройке. Это исправление позволяет применять относительный крайний срок для последующих обновлений.</span><span class="sxs-lookup"><span data-stu-id="57875-393">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="57875-394">Повышена надежность при скачивании обновлений Office путем продолжения скачивания, которое ранее могло прерываться.</span><span class="sxs-lookup"><span data-stu-id="57875-394">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="57875-395">Устранены проблемы, связанные со свойством автоподбора размера текстовых полей и фигур в сторонних подключаемых модулях.</span><span class="sxs-lookup"><span data-stu-id="57875-395">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="57875-396">Исправлена проблема, из-за которой крупные представления в виде дерева приводили к сбою.</span><span class="sxs-lookup"><span data-stu-id="57875-396">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="57875-397">Чтобы защитить пользователей Office, обновления Microsoft Office теперь подписываются исключительно с использованием алгоритма SHA-2.</span><span class="sxs-lookup"><span data-stu-id="57875-397">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1902-january-14"></a><span data-ttu-id="57875-399">Версия 1902: 14 января</span><span class="sxs-lookup"><span data-stu-id="57875-399">Version 1902: January 14</span></span>
<span data-ttu-id="57875-400">*Версия 1902 (сборка 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="57875-400">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="57875-401">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="57875-401">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="57875-403">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="57875-403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="57875-404">Excel</span><span class="sxs-lookup"><span data-stu-id="57875-404">Excel</span></span>

- <span data-ttu-id="57875-405">Исправлена проблема, из-за которой настройка ленты не загружалась при открытии внедренной книги.</span><span class="sxs-lookup"><span data-stu-id="57875-405">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="57875-406">Outlook</span><span class="sxs-lookup"><span data-stu-id="57875-406">Outlook</span></span>

- <span data-ttu-id="57875-407">Исправлена проблема, из-за которой при отправке зашифрованного сообщения электронной почты появлялась ошибка "Алгоритм шифрования не поддерживается".</span><span class="sxs-lookup"><span data-stu-id="57875-407">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="57875-408">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="57875-408">PowerPoint</span></span>

- <span data-ttu-id="57875-409">Файлы с новыми современными примечаниями отображают желтое предупреждение, если открываются в неподдерживаемой версии</span><span class="sxs-lookup"><span data-stu-id="57875-409">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="57875-410">Word</span><span class="sxs-lookup"><span data-stu-id="57875-410">Word</span></span>

- <span data-ttu-id="57875-411">Это изменение позволит повысить производительность при открытии документов в Word.</span><span class="sxs-lookup"><span data-stu-id="57875-411">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1808-january-14"></a><span data-ttu-id="57875-413">Версия 1808: 14 января</span><span class="sxs-lookup"><span data-stu-id="57875-413">Version 1808: January 14</span></span>
<span data-ttu-id="57875-414">*Версия 1808 (сборка 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="57875-414">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="57875-415">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="57875-415">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="57875-417">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="57875-417">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>