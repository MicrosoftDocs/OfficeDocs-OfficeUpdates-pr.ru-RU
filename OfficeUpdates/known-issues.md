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
ms.openlocfilehash: 721c9a600b079b3214fa798a39a8ed728c89de93
ms.sourcegitcommit: 7c1759a0e733ade767da00175afc1c43e8d07e3a
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/15/2019
ms.locfileid: "38640828"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="8a59d-103">Известные проблемы с Office 365 профессиональный плюс</span><span class="sxs-lookup"><span data-stu-id="8a59d-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="8a59d-104">В этом перечне известных проблем приводятся сведения об обновлениях, не связанных с безопасностью, которые включены в обновления Monthly Channel, SACT и SAC для Office 365 профессиональный плюс в 2019 г., Visio Pro для Office 365, клиента Microsoft Project Online для настольных ПК и Office 365 бизнес.</span><span class="sxs-lookup"><span data-stu-id="8a59d-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="8a59d-105">В таблице далее содержатся краткие сведения о текущих активных проблемах и проблемах, которые уже решены.</span><span class="sxs-lookup"><span data-stu-id="8a59d-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="8a59d-106">Мы будем добавлять в эту таблицу информацию о существенных проблемах, которые мы сейчас изучаем.</span><span class="sxs-lookup"><span data-stu-id="8a59d-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="8a59d-107">Этот список не является полным.</span><span class="sxs-lookup"><span data-stu-id="8a59d-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="8a59d-108">Если у вас возникла проблема в канале, который не является разрешенным, скоро она будет устранена.</span><span class="sxs-lookup"><span data-stu-id="8a59d-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="8a59d-109">Подробнее</span><span class="sxs-lookup"><span data-stu-id="8a59d-109">Learn more</span></span>](https://docs.microsoft.com/ru-RU/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="8a59d-110">Устраненные проблемы также описываются на страницах соответствующих каналов.</span><span class="sxs-lookup"><span data-stu-id="8a59d-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="8a59d-111">Последнее обновление: 12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="8a59d-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="8a59d-112">Excel</span><span class="sxs-lookup"><span data-stu-id="8a59d-112">Excel</span></span>

- <span data-ttu-id="8a59d-113">Флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки</span><span class="sxs-lookup"><span data-stu-id="8a59d-113">Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="8a59d-114">**Исследование**: Monthly Channel, SACT</span><span class="sxs-lookup"><span data-stu-id="8a59d-114">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="8a59d-115">Проблема производительности асинхронных пользовательских функций, из-за которой они выполнялись синхронно.</span><span class="sxs-lookup"><span data-stu-id="8a59d-115">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="8a59d-116">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="8a59d-117">Пользователям не удается сохранять записи в формате книги Excel в Office 365</span><span class="sxs-lookup"><span data-stu-id="8a59d-117">Users could be prevented from saving in Office 365 Excel Workbook format.</span></span><br><br><span data-ttu-id="8a59d-118">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="8a59d-119">Проблема низкой производительности при нажатии кнопки "цвет шрифта", если в файле широко используется условное форматирование.</span><span class="sxs-lookup"><span data-stu-id="8a59d-119">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="8a59d-120">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-120">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="8a59d-121">Значительное повышение производительности при удалении столбцов с объединенными ячейками</span><span class="sxs-lookup"><span data-stu-id="8a59d-121">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="8a59d-122">**Исследование**: SACT</span><span class="sxs-lookup"><span data-stu-id="8a59d-122">**Investigating**: SACT</span></span><br><span data-ttu-id="8a59d-123">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-123">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-124">Получение неверных результатов при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="8a59d-124">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="8a59d-125">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="8a59d-125">**Investigating**: Monthly</span></span>

- <span data-ttu-id="8a59d-126">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм</span><span class="sxs-lookup"><span data-stu-id="8a59d-126">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="8a59d-127">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-127">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="8a59d-128">Обнаружена проблема со вставкой файлов в качестве объектов из OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8a59d-128">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="8a59d-129">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-129">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-130">Обнаружена ошибка, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущей версии Office.</span><span class="sxs-lookup"><span data-stu-id="8a59d-130">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="8a59d-131">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="8a59d-131">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="8a59d-132">Обнаружена проблема, вызывавшая задержки отображения введенных значений после удаления диапазона.</span><span class="sxs-lookup"><span data-stu-id="8a59d-132">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="8a59d-133">**Решение**: SAC, версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="8a59d-133">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="8a59d-134">Обнаружена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки.</span><span class="sxs-lookup"><span data-stu-id="8a59d-134">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="8a59d-135">**Исследование**: SACT</span><span class="sxs-lookup"><span data-stu-id="8a59d-135">**Investigating**: SACT</span></span> <br><span data-ttu-id="8a59d-136">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-136">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-137">Обнаружена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов.</span><span class="sxs-lookup"><span data-stu-id="8a59d-137">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="8a59d-138">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="8a59d-138">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="8a59d-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a59d-139">Outlook</span></span>

- <span data-ttu-id="8a59d-140">Обнаружена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="8a59d-140">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="8a59d-141">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="8a59d-142">Обнаружена проблема, которая могла приводить к утечке памяти.</span><span class="sxs-lookup"><span data-stu-id="8a59d-142">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="8a59d-143">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20388), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="8a59d-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="8a59d-144">Решена проблема, из-за которой у некоторых пользователей дублировались специальные папки при добавлении дополнительной учетной записи Exchange.</span><span class="sxs-lookup"><span data-stu-id="8a59d-144">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="8a59d-145">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="8a59d-146">Обнаружена проблема, из-за которой иногда мог возникать сбой при получении пользователем сообщения "Пропущенная беседа" из Skype.</span><span class="sxs-lookup"><span data-stu-id="8a59d-146">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="8a59d-147">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-148">Обнаружена проблема, из-за которой у пользователей возникала общая ошибка "Не удается выполнить операцию" при открытии вложения на компьютере с включенным параметром DisableBGSave.</span><span class="sxs-lookup"><span data-stu-id="8a59d-148">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="8a59d-149">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-149">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-150">Обнаружена проблема, связанная со ссылками CID: не удавалось разорвать изображения (изображения сообщений Outlook).</span><span class="sxs-lookup"><span data-stu-id="8a59d-150">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="8a59d-151">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-151">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="8a59d-152">Обнаружена проблема, из-за которой могло неправильно возникать сообщение об ошибке при попытке отправить письмо, зашифрованное с помощью S/MIME.</span><span class="sxs-lookup"><span data-stu-id="8a59d-152">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="8a59d-153">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-153">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a59d-154">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a59d-154">PowerPoint</span></span>

- <span data-ttu-id="8a59d-155">Символы катаканы могут неправильно отображаться в вертикальной надписи.</span><span class="sxs-lookup"><span data-stu-id="8a59d-155">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="8a59d-156">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="8a59d-156">**Investigating**: Monthly</span></span>

- <span data-ttu-id="8a59d-157">Обнаружена проблема, не позволявшая создавать гиперссылку при вставке текста с гиперссылкой.</span><span class="sxs-lookup"><span data-stu-id="8a59d-157">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="8a59d-158">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-159">Обнаружена проблема, из-за которой могли повреждаться объекты TextRange после вставки текста в колонтитулы или заполнители номеров страниц слайдов в образце слайдов и макете слайда.</span><span class="sxs-lookup"><span data-stu-id="8a59d-159">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="8a59d-160">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-160">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="8a59d-161">Обнаружена проблема с быстродействием Win7, при которой коллекция фигур для вставки с ленты во всех приложениях отображается примерно через 4 секунды.</span><span class="sxs-lookup"><span data-stu-id="8a59d-161">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="8a59d-162">**Решение**: Monthly Channel версия 1910 (12130.20272), SACT версия 1908 (11929.20396), SAC версия 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="8a59d-162">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="8a59d-163">Project</span><span class="sxs-lookup"><span data-stu-id="8a59d-163">Project</span></span>

- <span data-ttu-id="8a59d-164">При назначении задачи с нулевым объемом работы может быть невозможно пометить ее как завершенную, она всегда отображается завершенной на 99 %.</span><span class="sxs-lookup"><span data-stu-id="8a59d-164">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="8a59d-165">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="8a59d-165">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="8a59d-166">**Решение**: SACT, версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-166">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="8a59d-167">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="8a59d-167">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="8a59d-168">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="8a59d-168">**Investigating**: Monthly</span></span>

- <span data-ttu-id="8a59d-169">Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения.</span><span class="sxs-lookup"><span data-stu-id="8a59d-169">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="8a59d-170">**Решение**: Monthly Channel версия 1910 (12130.20344), SACT версия 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="8a59d-170">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="8a59d-171">Word</span><span class="sxs-lookup"><span data-stu-id="8a59d-171">Word</span></span>

- <span data-ttu-id="8a59d-172">Поиск из области навигации может завершаться неудачей.</span><span class="sxs-lookup"><span data-stu-id="8a59d-172">Searching from the Navigation pane may fail.</span></span><br><br>
<span data-ttu-id="8a59d-173">**Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="8a59d-173">**Investigating**: Monthly</span></span>

- <span data-ttu-id="8a59d-174">Обнаружена проблема со вставкой файлов в качестве объектов из OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8a59d-174">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="8a59d-175">**Решение**: Monthly Channel, версия 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="8a59d-175">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="8a59d-176">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="8a59d-176">Office Suite</span></span>
- <span data-ttu-id="8a59d-177">Попытках сохранить файл в отключенной сетевой папке может привести к проблемам **Исследование**: Monthly Channel</span><span class="sxs-lookup"><span data-stu-id="8a59d-177">Attempting to save a file to a disconnected network share may result in a filure.</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="8a59d-178">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="8a59d-178">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
