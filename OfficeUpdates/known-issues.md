---
title: Известные проблемы с Office 365 профессиональный плюс
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Сведения об известных проблемах с Office 365 профессиональный плюс
ms.openlocfilehash: 73cd91d43e09900d81418427dab1da01d89f227b
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023554"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="bf973-103">Известные проблемы с Office 365 профессиональный плюс</span><span class="sxs-lookup"><span data-stu-id="bf973-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="bf973-104">В этом перечне известных проблем приводятся сведения об обновлениях, не связанных с безопасностью, которые включены в обновления Monthly Channel, SACT и SAC для Office 365 профессиональный плюс в 2019 г., Visio Pro для Office 365, клиента Microsoft Project Online для настольных ПК и Office 365 бизнес.</span><span class="sxs-lookup"><span data-stu-id="bf973-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="bf973-105">В таблице далее содержатся краткие сведения о текущих активных проблемах и проблемах, которые уже решены.</span><span class="sxs-lookup"><span data-stu-id="bf973-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="bf973-106">Мы будем добавлять в эту таблицу информацию о существенных проблемах, которые мы сейчас изучаем.</span><span class="sxs-lookup"><span data-stu-id="bf973-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="bf973-107">Этот список не является полным.</span><span class="sxs-lookup"><span data-stu-id="bf973-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="bf973-108">Если у вас возникла проблема в канале, который не является разрешенным, скоро она будет устранена.</span><span class="sxs-lookup"><span data-stu-id="bf973-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="bf973-109">Подробнее</span><span class="sxs-lookup"><span data-stu-id="bf973-109">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="bf973-110">Устраненные проблемы также описываются на страницах соответствующих каналов.</span><span class="sxs-lookup"><span data-stu-id="bf973-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="bf973-111">Последнее обновление: 12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="bf973-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="bf973-112">Excel</span><span class="sxs-lookup"><span data-stu-id="bf973-112">Excel</span></span>

- <span data-ttu-id="bf973-113">Флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки</span><span class="sxs-lookup"><span data-stu-id="bf973-113">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="bf973-114">**Исследование**: Monthly Channel, SACT</span><span class="sxs-lookup"><span data-stu-id="bf973-114">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="bf973-115">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="bf973-115">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="bf973-116">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="bf973-117">Пользователям не удается сохранять записи в формате книги Excel в Office 365</span><span class="sxs-lookup"><span data-stu-id="bf973-117">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="bf973-118">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="bf973-119">Проблема низкой производительности при нажатии кнопки "цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="bf973-119">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="bf973-120">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-120">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="bf973-121">Значительное повышение производительности при удалении столбцов с объединенными ячейками</span><span class="sxs-lookup"><span data-stu-id="bf973-121">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="bf973-122">**Исследование**: SACT</span><span class="sxs-lookup"><span data-stu-id="bf973-122">**Investigating**: SACT</span></span><br><span data-ttu-id="bf973-123">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-123">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-124">Получение неверных результатов при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="bf973-124">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="bf973-125">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="bf973-125">**Investigating**: Monthly</span></span>

- <span data-ttu-id="bf973-126">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм</span><span class="sxs-lookup"><span data-stu-id="bf973-126">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="bf973-127">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-127">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="bf973-128">Обнаружена проблема со вставкой файлов в качестве объектов из OneDrive.</span><span class="sxs-lookup"><span data-stu-id="bf973-128">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="bf973-129">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-129">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-130">Обнаружена ошибка, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущей версии Office.</span><span class="sxs-lookup"><span data-stu-id="bf973-130">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="bf973-131">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="bf973-131">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="bf973-132">Обнаружена проблема, вызывавшая задержки отображения введенных значений после удаления диапазона.</span><span class="sxs-lookup"><span data-stu-id="bf973-132">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="bf973-133">**Решение**: SAC, версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="bf973-133">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="bf973-134">Обнаружена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="bf973-134">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="bf973-135">**Исследование**: SACT</span><span class="sxs-lookup"><span data-stu-id="bf973-135">**Investigating**: SACT</span></span> <br><span data-ttu-id="bf973-136">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-136">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-137">Обнаружена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="bf973-137">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="bf973-138">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="bf973-138">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="bf973-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="bf973-139">Outlook</span></span>

- <span data-ttu-id="bf973-140">Обнаружена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="bf973-140">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="bf973-141">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="bf973-142">Обнаружена проблема, которая могла приводить к утечке памяти.</span><span class="sxs-lookup"><span data-stu-id="bf973-142">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="bf973-143">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20388), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="bf973-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="bf973-144">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="bf973-144">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="bf973-145">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="bf973-146">Обнаружена проблема, из-за которой иногда мог возникать сбой при получении пользователем сообщения "Пропущенная беседа" из Skype.</span><span class="sxs-lookup"><span data-stu-id="bf973-146">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="bf973-147">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-148">Обнаружена проблема, из-за которой у пользователей возникала общая ошибка "Не удается выполнить операцию" при открытии вложения на компьютере с включенным параметром DisableBGSave.</span><span class="sxs-lookup"><span data-stu-id="bf973-148">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="bf973-149">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-149">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-150">Обнаружена проблема, связанная со ссылками CID: не удавалось разорвать изображения (изображения сообщений Outlook).</span><span class="sxs-lookup"><span data-stu-id="bf973-150">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="bf973-151">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-151">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="bf973-152">Обнаружена проблема, из-за которой могло неправильно возникать сообщение об ошибке при попытке отправить письмо, зашифрованное с помощью S/MIME.</span><span class="sxs-lookup"><span data-stu-id="bf973-152">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="bf973-153">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-153">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="bf973-154">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bf973-154">PowerPoint</span></span>

- <span data-ttu-id="bf973-155">Символы катаканы могут неправильно отображаться в вертикальной надписи.</span><span class="sxs-lookup"><span data-stu-id="bf973-155">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="bf973-156">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="bf973-156">**Investigating**: Monthly</span></span>

- <span data-ttu-id="bf973-157">Обнаружена проблема, не позволявшая создавать гиперссылку при вставке текста с гиперссылкой.</span><span class="sxs-lookup"><span data-stu-id="bf973-157">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="bf973-158">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-159">Обнаружена проблема, из-за которой могли повреждаться объекты TextRange после вставки текста в колонтитулы или заполнители номеров страниц слайдов в образце слайдов и макете слайда.</span><span class="sxs-lookup"><span data-stu-id="bf973-159">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="bf973-160">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-160">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="bf973-161">Обнаружена проблема с быстродействием Win7, при которой коллекция фигур для вставки с ленты во всех приложениях отображается примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="bf973-161">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="bf973-162">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20396), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="bf973-162">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="bf973-163">Project</span><span class="sxs-lookup"><span data-stu-id="bf973-163">Project</span></span>

- <span data-ttu-id="bf973-164">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="bf973-164">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="bf973-165">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="bf973-165">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="bf973-166">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-166">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="bf973-167">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="bf973-167">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="bf973-168">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="bf973-168">**Investigating**: Monthly</span></span>

- <span data-ttu-id="bf973-169">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="bf973-169">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="bf973-170">**Решение**: Monthly Channel версия 1910 (12130.20344), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="bf973-170">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="bf973-171">Word</span><span class="sxs-lookup"><span data-stu-id="bf973-171">Word</span></span>

- <span data-ttu-id="bf973-172">Поиск из области навигации может завершаться неудачей.</span><span class="sxs-lookup"><span data-stu-id="bf973-172">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="bf973-173">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="bf973-173">**Investigating**: Monthly</span></span>

- <span data-ttu-id="bf973-174">Обнаружена проблема со вставкой файлов в качестве объектов из OneDrive.</span><span class="sxs-lookup"><span data-stu-id="bf973-174">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="bf973-175">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="bf973-175">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="bf973-176">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="bf973-176">Office Suite</span></span>
- <span data-ttu-id="bf973-177">Попытках сохранить файл в отключенной сетевой папке может привести к проблемам **Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="bf973-177">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="bf973-178">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="bf973-178">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
