---
title: Известные проблемы с Office 365 профессиональный плюс
ms.author: anankani
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Сведения об известных проблемах с Office 365 профессиональный плюс
ms.openlocfilehash: f93d43233c448cdc1100fe82e255acbb1fd344f3
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169848"
---
# <a name="microsoft-365-apps-known-issues"></a><span data-ttu-id="7b42a-103">Известные проблемы с Приложениями Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="7b42a-103">Microsoft 365 Apps Known Issues</span></span>

<span data-ttu-id="7b42a-104">Этот раздел об известных проблемах содержит информацию об обновлениях, не связанных с безопасностью, которые включены в Monthly Channel, Semi-Annual Channel (Targeted) и Semi-Annual Channel в 2019 г. для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="7b42a-104">These known issues provide information about non-security updates that are included in Monthly Channel, Semi-Annual Channel (Targeted), and Semi-Annual Channel  updates in 2019 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!NOTE]
>- <span data-ttu-id="7b42a-105">Этот список не является полным.</span><span class="sxs-lookup"><span data-stu-id="7b42a-105">This list is not comprehensive.</span></span>
>- <span data-ttu-id="7b42a-106">Если у вас возникла проблема в канале, который не является разрешенным, скоро она будет устранена.</span><span class="sxs-lookup"><span data-stu-id="7b42a-106">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="7b42a-107">Подробнее</span><span class="sxs-lookup"><span data-stu-id="7b42a-107">Learn more</span></span>](/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="7b42a-108">Устраненные проблемы также описываются на страницах соответствующих каналов.</span><span class="sxs-lookup"><span data-stu-id="7b42a-108">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="7b42a-109">Последнее обновление: 12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7b42a-109">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="7b42a-110">Excel</span><span class="sxs-lookup"><span data-stu-id="7b42a-110">Excel</span></span>

- <span data-ttu-id="7b42a-111">Флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки</span><span class="sxs-lookup"><span data-stu-id="7b42a-111">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="7b42a-112">**Исследование**: Monthly Channel, SACT</span><span class="sxs-lookup"><span data-stu-id="7b42a-112">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="7b42a-113">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="7b42a-113">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="7b42a-114">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-114">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="7b42a-115">Пользователям не удается сохранять записи в формате книги Excel в Office 365</span><span class="sxs-lookup"><span data-stu-id="7b42a-115">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="7b42a-116">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="7b42a-117">Проблема низкой производительности при нажатии кнопки "цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="7b42a-117">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="7b42a-118">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="7b42a-119">Значительное повышение производительности при удалении столбцов с объединенными ячейками</span><span class="sxs-lookup"><span data-stu-id="7b42a-119">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="7b42a-120">**Исследование**: SACT</span><span class="sxs-lookup"><span data-stu-id="7b42a-120">**Investigating**: SACT</span></span><br><span data-ttu-id="7b42a-121">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-121">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-122">Получение неверных результатов при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="7b42a-122">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="7b42a-123">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="7b42a-123">**Investigating**: Monthly</span></span>

- <span data-ttu-id="7b42a-124">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм</span><span class="sxs-lookup"><span data-stu-id="7b42a-124">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="7b42a-125">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-125">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="7b42a-126">Обнаружена проблема со вставкой файлов в качестве объектов из OneDrive.</span><span class="sxs-lookup"><span data-stu-id="7b42a-126">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="7b42a-127">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-127">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-128">Обнаружена ошибка, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущей версии Office.</span><span class="sxs-lookup"><span data-stu-id="7b42a-128">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="7b42a-129">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="7b42a-129">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="7b42a-130">Обнаружена проблема, вызывавшая задержки отображения введенных значений после удаления диапазона.</span><span class="sxs-lookup"><span data-stu-id="7b42a-130">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="7b42a-131">**Решение**: SAC, версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="7b42a-131">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="7b42a-132">Обнаружена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="7b42a-132">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="7b42a-133">**Исследование**: SACT</span><span class="sxs-lookup"><span data-stu-id="7b42a-133">**Investigating**: SACT</span></span> <br><span data-ttu-id="7b42a-134">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-135">Обнаружена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="7b42a-135">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="7b42a-136">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="7b42a-136">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="7b42a-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="7b42a-137">Outlook</span></span>

- <span data-ttu-id="7b42a-138">Обнаружена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="7b42a-138">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="7b42a-139">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-139">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="7b42a-140">Обнаружена проблема, которая могла приводить к утечке памяти.</span><span class="sxs-lookup"><span data-stu-id="7b42a-140">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="7b42a-141">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20388), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="7b42a-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="7b42a-142">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="7b42a-142">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="7b42a-143">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="7b42a-144">Обнаружена проблема, из-за которой иногда мог возникать сбой при получении пользователем сообщения "Пропущенная беседа" из Skype.</span><span class="sxs-lookup"><span data-stu-id="7b42a-144">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="7b42a-145">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-145">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-146">Обнаружена проблема, из-за которой у пользователей возникала общая ошибка "Не удается выполнить операцию" при открытии вложения на компьютере с включенным параметром DisableBGSave.</span><span class="sxs-lookup"><span data-stu-id="7b42a-146">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="7b42a-147">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-148">Обнаружена проблема, связанная со ссылками CID: не удавалось разорвать изображения (изображения сообщений Outlook).</span><span class="sxs-lookup"><span data-stu-id="7b42a-148">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="7b42a-149">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-149">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="7b42a-150">Обнаружена проблема, из-за которой могло неправильно возникать сообщение об ошибке при попытке отправить письмо, зашифрованное с помощью S/MIME.</span><span class="sxs-lookup"><span data-stu-id="7b42a-150">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="7b42a-151">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7b42a-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7b42a-152">PowerPoint</span></span>

- <span data-ttu-id="7b42a-153">Символы катаканы могут неправильно отображаться в вертикальной надписи.</span><span class="sxs-lookup"><span data-stu-id="7b42a-153">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="7b42a-154">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="7b42a-154">**Investigating**: Monthly</span></span>

- <span data-ttu-id="7b42a-155">Обнаружена проблема, не позволявшая создавать гиперссылку при вставке текста с гиперссылкой.</span><span class="sxs-lookup"><span data-stu-id="7b42a-155">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="7b42a-156">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-156">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-157">Обнаружена проблема, из-за которой могли повреждаться объекты TextRange после вставки текста в колонтитулы или заполнители номеров страниц слайдов в образце слайдов и макете слайда.</span><span class="sxs-lookup"><span data-stu-id="7b42a-157">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="7b42a-158">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="7b42a-159">Обнаружена проблема с быстродействием Win7, при которой коллекция фигур для вставки с ленты во всех приложениях отображается примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="7b42a-159">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="7b42a-160">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20396), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="7b42a-160">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="7b42a-161">Project</span><span class="sxs-lookup"><span data-stu-id="7b42a-161">Project</span></span>

- <span data-ttu-id="7b42a-162">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="7b42a-162">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="7b42a-163">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="7b42a-163">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="7b42a-164">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-164">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="7b42a-165">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="7b42a-165">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="7b42a-166">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="7b42a-166">**Investigating**: Monthly</span></span>

- <span data-ttu-id="7b42a-167">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="7b42a-167">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="7b42a-168">**Решение**: Monthly Channel версия 1910 (12130.20344), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7b42a-168">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="7b42a-169">Word</span><span class="sxs-lookup"><span data-stu-id="7b42a-169">Word</span></span>

- <span data-ttu-id="7b42a-170">Поиск из области навигации может завершаться неудачей.</span><span class="sxs-lookup"><span data-stu-id="7b42a-170">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="7b42a-171">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="7b42a-171">**Investigating**: Monthly</span></span>

- <span data-ttu-id="7b42a-172">Обнаружена проблема со вставкой файлов в качестве объектов из OneDrive.</span><span class="sxs-lookup"><span data-stu-id="7b42a-172">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="7b42a-173">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="7b42a-173">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="7b42a-174">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7b42a-174">Office Suite</span></span>
- <span data-ttu-id="7b42a-175">Попытках сохранить файл в отключенной сетевой папке может привести к проблемам **Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="7b42a-175">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="7b42a-176">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="7b42a-176">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>