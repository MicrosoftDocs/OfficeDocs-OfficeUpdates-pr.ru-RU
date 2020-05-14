---
title: Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft 365
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft 365, предназначенные для ИТ-специалистов
ms.openlocfilehash: 91538ad859fe5dc3d45a73d0798ff21708f6178b
ms.sourcegitcommit: 18f8f5d6dcd9743005ae2ba87c8e9e2d9edfe8c4
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/13/2020
ms.locfileid: "44211709"
---
# <a name="release-notes-for-microsoft-365-apps-security-updates"></a><span data-ttu-id="e1c3a-103">Заметки о выпусках для обновлений системы безопасности в приложениях Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="e1c3a-103">Release notes for Microsoft 365 Apps Security Updates</span></span>

<span data-ttu-id="e1c3a-104">Эти заметки о выпусках содержат сведения об исправлениях безопасности, которые включены в обновления для приложений Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-104">These release notes provide information about security fixes that are included in updates to Microsoft 365 Apps.</span></span>

<span data-ttu-id="e1c3a-105">Эти сведения относятся к приложениям Microsoft 365 для предприятий, Microsoft 365 для бизнеса и версиям классических приложений Project и Visio, включающих подписки.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="e1c3a-106">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="e1c3a-107">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="e1c3a-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="e1c3a-108">Office 365 профессиональный плюс с версии 2004 переименовывается в "Приложения Microsoft 365 для предприятий".</span><span class="sxs-lookup"><span data-stu-id="e1c3a-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="e1c3a-109"> Дополнительные сведения см. в  [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span><span class="sxs-lookup"><span data-stu-id="e1c3a-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="e1c3a-110"> В этой документации чаще всего используется обозначение "Приложения Microsoft 365".</span><span class="sxs-lookup"><span data-stu-id="e1c3a-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (НЕ УДАЛЯТЬ СТРОКУ ВЫШЕ, она используется для интервала)  

## <a name="may-12-2020"></a><span data-ttu-id="e1c3a-112">12 мая 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-112">May 12, 2020</span></span>
<span data-ttu-id="e1c3a-113">Monthly Channel: версия 2004 (сборка 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-113">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="e1c3a-114">Monthly Enterprise Channel: версия 2003 (сборка 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-114">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="e1c3a-115">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-115">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="e1c3a-116">Semi-Annual Channel: версия 1908 (сборка 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-116">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="e1c3a-117">Semi-Annual Channel: версия 1902 (сборка 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-117">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="e1c3a-118">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-118">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="e1c3a-120">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-120">Excel</span></span>

-   [<span data-ttu-id="e1c3a-121">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="e1c3a-121">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0901)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="april-14-2020"></a><span data-ttu-id="e1c3a-123">14 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-123">April 14, 2020</span></span>
<span data-ttu-id="e1c3a-124">Monthly Channel: версия 2003 (сборка 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-124">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="e1c3a-125">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-125">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="e1c3a-126">Semi-Annual Channel: версия 1908 (сборка 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-126">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="e1c3a-127">Semi-Annual Channel: версия 1902 (сборка 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-127">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="e1c3a-128">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-128">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="e1c3a-130">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-130">Excel</span></span>

-   [<span data-ttu-id="e1c3a-131">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="e1c3a-131">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="e1c3a-132">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="e1c3a-132">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="e1c3a-133">Word</span><span class="sxs-lookup"><span data-stu-id="e1c3a-133">Word</span></span>

-   [<span data-ttu-id="e1c3a-134">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="e1c3a-134">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-135">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-135">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-136">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="e1c3a-136">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="e1c3a-137">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="e1c3a-137">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="e1c3a-138">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="e1c3a-138">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0961)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="march-10-2020"></a><span data-ttu-id="e1c3a-140">10 марта 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-140">March 10, 2020</span></span>
<span data-ttu-id="e1c3a-141">Ежемесячный канал: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-141">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="e1c3a-142">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-142">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="e1c3a-143">Semi-Annual Channel: версия 1908 (сборка 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-143">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="e1c3a-144">Semi-Annual Channel: версия 1902 (сборка 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-144">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="e1c3a-145">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-145">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)



### <a name="word"></a><span data-ttu-id="e1c3a-147">Word</span><span class="sxs-lookup"><span data-stu-id="e1c3a-147">Word</span></span>

-   [<span data-ttu-id="e1c3a-148">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="e1c3a-148">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="e1c3a-149">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="e1c3a-149">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="e1c3a-150">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="e1c3a-150">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="e1c3a-151">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="e1c3a-151">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0851)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="february-11-2020"></a><span data-ttu-id="e1c3a-153">11 февраля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-153">February 11, 2020</span></span>
<span data-ttu-id="e1c3a-154">Месячный канал: версия 2001 (сборка 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-154">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="e1c3a-155">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-155">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="e1c3a-156">Semi-Annual Channel: версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-156">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="e1c3a-157">Semi-Annual Channel: версия 1902 (сборка 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-157">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="e1c3a-158">Semi-Annual Channel: версия 1808 (сборка 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-158">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="e1c3a-160">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-160">Excel</span></span>

-   [<span data-ttu-id="e1c3a-161">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="e1c3a-161">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="e1c3a-162">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1c3a-162">Outlook</span></span>

-   [<span data-ttu-id="e1c3a-163">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="e1c3a-163">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-164">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-164">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-165">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="e1c3a-165">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0697)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="january-14-2020"></a><span data-ttu-id="e1c3a-167">14 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-167">January 14, 2020</span></span>
<span data-ttu-id="e1c3a-168">Monthly Channel: версия 1912 (сборка 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-168">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="e1c3a-169">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-169">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="e1c3a-170">Semi-Annual Channel: версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-170">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="e1c3a-171">Semi-Annual Channel: версия 1902 (сборка 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-171">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="e1c3a-172">Semi-Annual Channel: версия 1808 (сборка 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-172">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="e1c3a-174">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-174">Excel</span></span>

-   [<span data-ttu-id="e1c3a-175">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="e1c3a-175">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="e1c3a-176">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="e1c3a-176">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="e1c3a-177">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="e1c3a-177">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-178">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-178">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-179">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="e1c3a-179">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0652)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, КОНЕЦ СОДЕРЖИМОГО)



## <a name="december-10-2019"></a><span data-ttu-id="e1c3a-181">10 декабря 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-181">December 10, 2019</span></span>
<span data-ttu-id="e1c3a-182">Monthly Channel: версия 1911 (сборка 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-182">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="e1c3a-183">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-183">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="e1c3a-184">Semi-Annual Channel: версия 1902 (сборка 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-184">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="e1c3a-185">Semi-Annual Channel: версия 1808 (сборка 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-185">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-186">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-186">Excel</span></span>

-   [<span data-ttu-id="e1c3a-187">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="e1c3a-187">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="e1c3a-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1c3a-188">PowerPoint</span></span>

-   [<span data-ttu-id="e1c3a-189">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="e1c3a-189">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="e1c3a-190">Word</span><span class="sxs-lookup"><span data-stu-id="e1c3a-190">Word</span></span>

-   [<span data-ttu-id="e1c3a-191">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="e1c3a-191">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-192">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-192">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-193">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="e1c3a-193">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="e1c3a-194">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="e1c3a-194">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="e1c3a-195">12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-195">November 12, 2019</span></span>
<span data-ttu-id="e1c3a-196">Monthly Channel: версия 1910 (сборка 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-196">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="e1c3a-197">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-197">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="e1c3a-198">Semi-Annual Channel: версия 1902 (сборка 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-198">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="e1c3a-199">Semi-Annual Channel: версия 1808 (сборка 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-199">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-200">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-200">Excel</span></span>

-   [<span data-ttu-id="e1c3a-201">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="e1c3a-201">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="e1c3a-202">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="e1c3a-202">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-203">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-203">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-204">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="e1c3a-204">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="e1c3a-205">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="e1c3a-205">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="e1c3a-206">08 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-206">October 08, 2019</span></span>
<span data-ttu-id="e1c3a-207">Monthly Channel: версия 1909 (сборка 12026.20320) </span><span class="sxs-lookup"><span data-stu-id="e1c3a-207">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="e1c3a-208">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-208">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="e1c3a-209">Semi-Annual Channel: версия 1902 (сборка 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-209">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="e1c3a-210">Semi-Annual Channel: версия 1808 (сборка 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-210">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-211">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-211">Excel</span></span>

-   [<span data-ttu-id="e1c3a-212">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="e1c3a-212">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="e1c3a-213">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="e1c3a-213">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="e1c3a-214">10 сентября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-214">September 10, 2019</span></span>
<span data-ttu-id="e1c3a-215">Monthly Channel: версия 1908 (сборка 11929.20300) </span><span class="sxs-lookup"><span data-stu-id="e1c3a-215">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="e1c3a-216">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-216">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="e1c3a-217">Semi-Annual Channel: версия 1902 (сборка 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-217">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="e1c3a-218">Semi-Annual Channel: версия 1808 (сборка 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-218">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-219">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-219">Excel</span></span>

-   [<span data-ttu-id="e1c3a-220">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="e1c3a-220">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="e1c3a-221">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="e1c3a-221">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-222">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-222">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-223">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="e1c3a-223">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="e1c3a-224">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="e1c3a-224">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="e1c3a-225">13 августа 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-225">August 13, 2019</span></span>
<span data-ttu-id="e1c3a-226">Monthly Channel: версия 1907 (сборка 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-226">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="e1c3a-227">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-227">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="e1c3a-228">Semi-Annual Channel: версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-228">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="e1c3a-229">Semi-Annual Channel: версия 1808 (сборка 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-229">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="e1c3a-230">Semi-Annual Channel: версия 1803 (сборка 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-230">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="e1c3a-231">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1c3a-231">Outlook</span></span>

-   [<span data-ttu-id="e1c3a-232">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="e1c3a-232">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="e1c3a-233">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="e1c3a-233">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="e1c3a-234">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="e1c3a-234">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="e1c3a-235">Word</span><span class="sxs-lookup"><span data-stu-id="e1c3a-235">Word</span></span>

-   [<span data-ttu-id="e1c3a-236">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="e1c3a-236">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="e1c3a-237">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="e1c3a-237">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-238">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-238">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-239">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="e1c3a-239">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="e1c3a-240">09 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-240">July 09, 2019</span></span>
<span data-ttu-id="e1c3a-241">Monthly Channel: версия 1906 (сборка 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-241">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="e1c3a-242">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-242">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="e1c3a-243">Semi-Annual Channel: версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-243">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="e1c3a-244">Semi-Annual Channel: версия 1808 (сборка 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-244">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="e1c3a-245">Semi-Annual Channel: версия 1803 (сборка 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-245">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="e1c3a-246">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-246">Excel</span></span>

-   [<span data-ttu-id="e1c3a-247">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="e1c3a-247">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="e1c3a-248">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="e1c3a-248">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="e1c3a-249">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="e1c3a-249">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="e1c3a-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1c3a-250">Outlook</span></span>

-   [<span data-ttu-id="e1c3a-251">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="e1c3a-251">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="e1c3a-252">Skype для бизнеса</span><span class="sxs-lookup"><span data-stu-id="e1c3a-252">Skype for Business</span></span>

-   [<span data-ttu-id="e1c3a-253">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="e1c3a-253">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-254">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-254">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-255">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="e1c3a-255">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="e1c3a-256">11 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-256">June 11, 2019</span></span>
<span data-ttu-id="e1c3a-257">Monthly Channel: версия 1905 (сборка 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-257">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="e1c3a-258">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-258">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="e1c3a-259">Semi-Annual Channel: версия 1808 (сборка 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-259">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="e1c3a-260">Semi-Annual Channel: версия 1803 (сборка 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-260">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="e1c3a-261">Word</span><span class="sxs-lookup"><span data-stu-id="e1c3a-261">Word</span></span>

-   [<span data-ttu-id="e1c3a-262">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="e1c3a-262">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="e1c3a-263">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="e1c3a-263">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="e1c3a-264">14 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-264">May 14, 2019</span></span>
<span data-ttu-id="e1c3a-265">Monthly Channel: версия 1904 (сборка 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-265">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="e1c3a-266">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-266">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="e1c3a-267">Semi-Annual Channel: версия 1808 (сборка 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-267">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="e1c3a-268">Semi-Annual Channel: версия 1803 (сборка 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-268">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="e1c3a-269">Word</span><span class="sxs-lookup"><span data-stu-id="e1c3a-269">Word</span></span>

-   [<span data-ttu-id="e1c3a-270">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="e1c3a-270">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-271">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-271">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-272">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="e1c3a-272">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="e1c3a-273">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="e1c3a-273">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="e1c3a-274">9 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-274">April 09, 2019</span></span>
<span data-ttu-id="e1c3a-275">Monthly Channel: версия 1903 (сборка 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-275">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="e1c3a-276">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-276">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="e1c3a-277">Semi-Annual Channel: версия 1808 (сборка 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-277">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="e1c3a-278">Semi-Annual Channel: версия 1803 (сборка 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-278">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-279">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-279">Excel</span></span>

-   [<span data-ttu-id="e1c3a-280">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="e1c3a-280">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-281">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-281">Office Suite</span></span>

-   [<span data-ttu-id="e1c3a-282">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="e1c3a-282">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="e1c3a-283">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="e1c3a-283">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="e1c3a-284">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="e1c3a-284">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="e1c3a-285">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="e1c3a-285">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="e1c3a-286">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="e1c3a-286">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="e1c3a-287">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="e1c3a-287">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="e1c3a-288">12 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-288">March 12, 2019</span></span>
<span data-ttu-id="e1c3a-289">В этом месяце ни для одного канала нет обновлений системы безопасности.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-289">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="e1c3a-290">12 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-290">February 12, 2019</span></span>
<span data-ttu-id="e1c3a-291">Monthly Channel: версия 1901 (сборка 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-291">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="e1c3a-292">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-292">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="e1c3a-293">Semi-Annual Channel: версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-293">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="e1c3a-294">Semi-Annual Channel: версия 1803 (сборка 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-294">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="e1c3a-295">Semi-Annual Channel: версия 1708 (сборка 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-295">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="e1c3a-296">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-296">Excel</span></span>

-   [<span data-ttu-id="e1c3a-297">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="e1c3a-297">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="e1c3a-298">Набор Office</span><span class="sxs-lookup"><span data-stu-id="e1c3a-298">Office suite</span></span>

-   [<span data-ttu-id="e1c3a-299">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="e1c3a-299">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="e1c3a-300">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="e1c3a-300">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="e1c3a-301">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="e1c3a-301">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="e1c3a-302">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="e1c3a-302">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="e1c3a-303">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="e1c3a-303">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="e1c3a-304">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="e1c3a-304">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="e1c3a-305">8 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-305">January 8, 2019</span></span>

<span data-ttu-id="e1c3a-306">Monthly Channel: версия 1812 (сборка 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-306">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="e1c3a-307">Semi-Annual Targeted Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-307">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="e1c3a-308">Semi-Annual Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-308">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="e1c3a-309">Semi-Annual Channel: версия 1803 (сборка 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-309">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="e1c3a-310">Semi-Annual Channel: версия 1708 (сборка 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-310">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="e1c3a-311">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1c3a-311">Outlook</span></span>
-   [<span data-ttu-id="e1c3a-312">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="e1c3a-312">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="e1c3a-313">Word. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="e1c3a-313">Word: Security updates</span></span> 
-   [<span data-ttu-id="e1c3a-314">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="e1c3a-314">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="e1c3a-315">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="e1c3a-315">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="e1c3a-316">Набор Office. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="e1c3a-316">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="e1c3a-317">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="e1c3a-317">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="e1c3a-318">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="e1c3a-318">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="e1c3a-319">11 декабря 2018 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-319">December 11, 2018</span></span>
<span data-ttu-id="e1c3a-320">Monthly Channel: версия 1811 (сборка 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-320">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="e1c3a-321">Semi-Annual Channel: версия 1803 (сборка 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-321">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="e1c3a-322">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-322">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-323">Excel</span><span class="sxs-lookup"><span data-stu-id="e1c3a-323">Excel</span></span>

-   [<span data-ttu-id="e1c3a-324">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="e1c3a-324">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="e1c3a-325">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="e1c3a-325">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="e1c3a-326">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="e1c3a-326">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="e1c3a-327">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="e1c3a-327">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="e1c3a-328">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1c3a-328">Outlook</span></span>

-   [<span data-ttu-id="e1c3a-329">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="e1c3a-329">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="e1c3a-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1c3a-330">PowerPoint</span></span>

-   [<span data-ttu-id="e1c3a-331">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="e1c3a-331">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="e1c3a-332">13 ноября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-332">November 13, 2018</span></span>
<span data-ttu-id="e1c3a-333">Monthly Channel: версия 1810 (сборка 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-333">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="e1c3a-334">Semi-Annual Channel: версия 1803 (сборка 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-334">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="e1c3a-335">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="e1c3a-335">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="e1c3a-336">Excel.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-336">Excel:</span></span>

-   [<span data-ttu-id="e1c3a-337">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="e1c3a-337">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="e1c3a-338">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="e1c3a-338">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="e1c3a-339">Outlook.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-339">Outlook:</span></span>

-   [<span data-ttu-id="e1c3a-340">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="e1c3a-340">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="e1c3a-341">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="e1c3a-341">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="e1c3a-342">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="e1c3a-342">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="e1c3a-343">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="e1c3a-343">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="e1c3a-344">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="e1c3a-344">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="e1c3a-345">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="e1c3a-345">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="e1c3a-346">Project.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-346">Project:</span></span>

-   [<span data-ttu-id="e1c3a-347">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="e1c3a-347">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="e1c3a-348">Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-348">Skype for Business:</span></span>

-   [<span data-ttu-id="e1c3a-349">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="e1c3a-349">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="e1c3a-350">Word.</span><span class="sxs-lookup"><span data-stu-id="e1c3a-350">Word:</span></span>

-   [<span data-ttu-id="e1c3a-351">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="e1c3a-351">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8573)
