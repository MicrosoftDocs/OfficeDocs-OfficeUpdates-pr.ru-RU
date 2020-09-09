---
title: Заметки о выпуске обновлений для системы безопасности Microsoft Office
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Заметки о выпуске обновлений для системы безопасности Microsoft Office, предназначенные для ИТ-специалистов
ms.openlocfilehash: ae1402e77905e221cbcd0a6736ad3fb4ba4d507b
ms.sourcegitcommit: db30154a1be72ca2b3b41f4dcc8ce6986834f6da
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/09/2020
ms.locfileid: "47413087"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="d50e9-103">Заметки о выпуске обновлений для системы безопасности Microsoft Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="d50e9-104">Эти заметки о выпуске содержат сведения об исправлениях безопасности, которые входят в обновления для Microsoft Office.</span><span class="sxs-lookup"><span data-stu-id="d50e9-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="d50e9-105">Эта информация применима к Приложениям Microsoft 365 для предприятий, Приложениям Microsoft 365 для бизнеса, розничной версии Office 2016 (C2R) и Office 2019.</span><span class="sxs-lookup"><span data-stu-id="d50e9-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="d50e9-106">Мы вносим ряд изменений в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="d50e9-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="d50e9-107">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="d50e9-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="d50e9-108">Office 365 профессиональный плюс с версии 2004 переименовывается в "Приложения Microsoft 365 для предприятий".</span><span class="sxs-lookup"><span data-stu-id="d50e9-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="d50e9-109"> Дополнительные сведения см. в  [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span><span class="sxs-lookup"><span data-stu-id="d50e9-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="d50e9-110"> В этой документации чаще всего используется обозначение "Приложения Microsoft 365".</span><span class="sxs-lookup"><span data-stu-id="d50e9-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (НЕ УДАЛЯТЬ СТРОКУ ВЫШЕ, она используется для интервала)  

## <a name="september-08-2020"></a><span data-ttu-id="d50e9-112">08 сентября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-112">September 08, 2020</span></span>
<span data-ttu-id="d50e9-113">Ежемесячный канал (корпоративный): версия 2007 (сборка 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="d50e9-113">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="d50e9-114">Ежемесячный канал (корпоративный): версия 2006 (сборка 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="d50e9-114">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="d50e9-115">Полугодовой канал (предварительная корпоративная версия): версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="d50e9-115">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="d50e9-116">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="d50e9-116">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="d50e9-117">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="d50e9-117">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="d50e9-118">Корпоративная версия Office 2019: версия 1808 (сборка 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="d50e9-118">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-120">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-120">Excel</span></span>

-   [<span data-ttu-id="d50e9-121">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="d50e9-121">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="d50e9-122">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="d50e9-122">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="d50e9-123">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="d50e9-123">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="d50e9-124">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="d50e9-124">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="d50e9-125">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-125">Word</span></span>

-   [<span data-ttu-id="d50e9-126">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="d50e9-126">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="d50e9-127">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="d50e9-127">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1218)
-   [<span data-ttu-id="d50e9-128">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="d50e9-128">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1445)

### <a name="office-suite"></a><span data-ttu-id="d50e9-129">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-129">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-130">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="d50e9-130">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1458)
-   [<span data-ttu-id="d50e9-131">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="d50e9-131">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1193)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="august-11-2020"></a><span data-ttu-id="d50e9-133">11 августа 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-133">August 11, 2020</span></span>
<span data-ttu-id="d50e9-134">Актуальный канал: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="d50e9-134">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="d50e9-135">Ежемесячный канал (корпоративный): версия 2006 (сборка 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="d50e9-135">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="d50e9-136">Ежемесячный канал (корпоративный): версия 2005 (сборка 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="d50e9-136">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="d50e9-137">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="d50e9-137">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="d50e9-138">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="d50e9-138">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="d50e9-139">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="d50e9-139">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="d50e9-140">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="d50e9-140">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="d50e9-141">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="d50e9-141">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="d50e9-142">Розничная версия Office 2019: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="d50e9-142">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="d50e9-143">Розничная версия Office 2016: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="d50e9-143">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="d50e9-144">Корпоративная версия Office 2019: версия 1808 (сборка 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="d50e9-144">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="access"></a><span data-ttu-id="d50e9-146">Доступ</span><span class="sxs-lookup"><span data-stu-id="d50e9-146">Access</span></span>

-   [<span data-ttu-id="d50e9-147">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="d50e9-147">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="d50e9-148">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-148">Excel</span></span>

-   [<span data-ttu-id="d50e9-149">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="d50e9-149">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="d50e9-150">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="d50e9-150">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="d50e9-151">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="d50e9-151">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="d50e9-152">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="d50e9-152">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="d50e9-153">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="d50e9-153">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="d50e9-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-154">Outlook</span></span>

-   [<span data-ttu-id="d50e9-155">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="d50e9-155">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="d50e9-156">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="d50e9-156">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="d50e9-157">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-157">Word</span></span>

-   [<span data-ttu-id="d50e9-158">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="d50e9-158">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="d50e9-159">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="d50e9-159">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="d50e9-160">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="d50e9-160">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="d50e9-161">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-161">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-162">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="d50e9-162">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="d50e9-163">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="d50e9-163">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1563)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="july-14-2020"></a><span data-ttu-id="d50e9-165">14 июля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-165">July 14, 2020</span></span>
<span data-ttu-id="d50e9-166">Актуальный канал: версия 2006 (сборка 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="d50e9-166">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="d50e9-167">Ежемесячный канал (корпоративный)l: версия 2005 (сборка 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="d50e9-167">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="d50e9-168">Ежемесячный канал (корпоративный): версия 2004 (сборка 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="d50e9-168">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="d50e9-169">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="d50e9-169">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="d50e9-170">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="d50e9-170">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="d50e9-171">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="d50e9-171">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="d50e9-172">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="d50e9-172">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="d50e9-173">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="d50e9-173">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-175">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-175">Excel</span></span>

-   [<span data-ttu-id="d50e9-176">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="d50e9-176">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="d50e9-177">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-177">Outlook</span></span>

-   [<span data-ttu-id="d50e9-178">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="d50e9-178">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="d50e9-179">Project</span><span class="sxs-lookup"><span data-stu-id="d50e9-179">Project</span></span>

-   [<span data-ttu-id="d50e9-180">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="d50e9-180">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="d50e9-181">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-181">Word</span></span>

-   [<span data-ttu-id="d50e9-182">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="d50e9-182">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="d50e9-183">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="d50e9-183">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="d50e9-184">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="d50e9-184">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="d50e9-185">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="d50e9-185">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="d50e9-186">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-186">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-187">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="d50e9-187">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1458)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="june-09-2020"></a><span data-ttu-id="d50e9-189">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-189">June 09, 2020</span></span>
<span data-ttu-id="d50e9-190">Актуальный канал: версия 2005 (сборка 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="d50e9-190">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="d50e9-191">Ежемесячный канал (корпоративный): версия 2004 (сборка 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="d50e9-191">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="d50e9-192">Ежемесячный канал (корпоративный): версия 2003 (сборка 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="d50e9-192">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="d50e9-193">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="d50e9-193">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="d50e9-194">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="d50e9-194">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="d50e9-195">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="d50e9-195">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="d50e9-196">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="d50e9-196">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-198">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-198">Excel</span></span>

-   [<span data-ttu-id="d50e9-199">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="d50e9-199">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="d50e9-200">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="d50e9-200">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="d50e9-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-201">Outlook</span></span>

-   [<span data-ttu-id="d50e9-202">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="d50e9-202">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="d50e9-203">Project</span><span class="sxs-lookup"><span data-stu-id="d50e9-203">Project</span></span>

-   [<span data-ttu-id="d50e9-204">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="d50e9-204">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="d50e9-205">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-205">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-206">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="d50e9-206">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1321)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="may-12-2020"></a><span data-ttu-id="d50e9-208">12 мая 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-208">May 12, 2020</span></span>
<span data-ttu-id="d50e9-209">Monthly Channel: версия 2004 (сборка 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="d50e9-209">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="d50e9-210">Monthly Enterprise Channel: версия 2003 (сборка 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="d50e9-210">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="d50e9-211">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="d50e9-211">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="d50e9-212">Semi-Annual Channel: версия 1908 (сборка 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="d50e9-212">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="d50e9-213">Semi-Annual Channel: версия 1902 (сборка 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="d50e9-213">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="d50e9-214">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="d50e9-214">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-216">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-216">Excel</span></span>

-   [<span data-ttu-id="d50e9-217">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="d50e9-217">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0901)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="april-14-2020"></a><span data-ttu-id="d50e9-219">14 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-219">April 14, 2020</span></span>
<span data-ttu-id="d50e9-220">Monthly Channel: версия 2003 (сборка 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="d50e9-220">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="d50e9-221">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="d50e9-221">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="d50e9-222">Semi-Annual Channel: версия 1908 (сборка 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="d50e9-222">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="d50e9-223">Semi-Annual Channel: версия 1902 (сборка 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="d50e9-223">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="d50e9-224">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="d50e9-224">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-226">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-226">Excel</span></span>

-   [<span data-ttu-id="d50e9-227">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="d50e9-227">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="d50e9-228">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="d50e9-228">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="d50e9-229">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-229">Word</span></span>

-   [<span data-ttu-id="d50e9-230">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="d50e9-230">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="d50e9-231">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-231">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-232">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="d50e9-232">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="d50e9-233">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="d50e9-233">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="d50e9-234">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="d50e9-234">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0961)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="march-10-2020"></a><span data-ttu-id="d50e9-236">10 марта 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-236">March 10, 2020</span></span>
<span data-ttu-id="d50e9-237">Ежемесячный канал: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="d50e9-237">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="d50e9-238">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="d50e9-238">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="d50e9-239">Semi-Annual Channel: версия 1908 (сборка 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="d50e9-239">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="d50e9-240">Semi-Annual Channel: версия 1902 (сборка 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="d50e9-240">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="d50e9-241">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="d50e9-241">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)



### <a name="word"></a><span data-ttu-id="d50e9-243">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-243">Word</span></span>

-   [<span data-ttu-id="d50e9-244">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="d50e9-244">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="d50e9-245">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="d50e9-245">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="d50e9-246">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="d50e9-246">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="d50e9-247">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="d50e9-247">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0851)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="february-11-2020"></a><span data-ttu-id="d50e9-249">11 февраля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-249">February 11, 2020</span></span>
<span data-ttu-id="d50e9-250">Месячный канал: версия 2001 (сборка 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="d50e9-250">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="d50e9-251">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="d50e9-251">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="d50e9-252">Semi-Annual Channel: версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="d50e9-252">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="d50e9-253">Semi-Annual Channel: версия 1902 (сборка 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="d50e9-253">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="d50e9-254">Semi-Annual Channel: версия 1808 (сборка 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="d50e9-254">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-256">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-256">Excel</span></span>

-   [<span data-ttu-id="d50e9-257">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="d50e9-257">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="d50e9-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-258">Outlook</span></span>

-   [<span data-ttu-id="d50e9-259">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="d50e9-259">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="d50e9-260">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-260">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-261">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="d50e9-261">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0697)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="january-14-2020"></a><span data-ttu-id="d50e9-263">14 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-263">January 14, 2020</span></span>
<span data-ttu-id="d50e9-264">Monthly Channel: версия 1912 (сборка 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="d50e9-264">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="d50e9-265">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="d50e9-265">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="d50e9-266">Semi-Annual Channel: версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="d50e9-266">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="d50e9-267">Semi-Annual Channel: версия 1902 (сборка 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="d50e9-267">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="d50e9-268">Semi-Annual Channel: версия 1808 (сборка 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="d50e9-268">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="d50e9-270">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-270">Excel</span></span>

-   [<span data-ttu-id="d50e9-271">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="d50e9-271">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="d50e9-272">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="d50e9-272">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="d50e9-273">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="d50e9-273">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="d50e9-274">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-274">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-275">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="d50e9-275">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0652)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, КОНЕЦ СОДЕРЖИМОГО)



## <a name="december-10-2019"></a><span data-ttu-id="d50e9-277">10 декабря 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-277">December 10, 2019</span></span>
<span data-ttu-id="d50e9-278">Monthly Channel: версия 1911 (сборка 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="d50e9-278">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="d50e9-279">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="d50e9-279">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="d50e9-280">Semi-Annual Channel: версия 1902 (сборка 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="d50e9-280">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="d50e9-281">Semi-Annual Channel: версия 1808 (сборка 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="d50e9-281">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-282">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-282">Excel</span></span>

-   [<span data-ttu-id="d50e9-283">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="d50e9-283">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="d50e9-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d50e9-284">PowerPoint</span></span>

-   [<span data-ttu-id="d50e9-285">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="d50e9-285">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="d50e9-286">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-286">Word</span></span>

-   [<span data-ttu-id="d50e9-287">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="d50e9-287">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="d50e9-288">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-288">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-289">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="d50e9-289">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="d50e9-290">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="d50e9-290">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="d50e9-291">12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-291">November 12, 2019</span></span>
<span data-ttu-id="d50e9-292">Monthly Channel: версия 1910 (сборка 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="d50e9-292">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="d50e9-293">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="d50e9-293">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="d50e9-294">Semi-Annual Channel: версия 1902 (сборка 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="d50e9-294">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="d50e9-295">Semi-Annual Channel: версия 1808 (сборка 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="d50e9-295">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-296">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-296">Excel</span></span>

-   [<span data-ttu-id="d50e9-297">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="d50e9-297">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="d50e9-298">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="d50e9-298">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="d50e9-299">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-299">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-300">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="d50e9-300">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="d50e9-301">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="d50e9-301">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="d50e9-302">08 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-302">October 08, 2019</span></span>
<span data-ttu-id="d50e9-303">Monthly Channel: версия 1909 (сборка 12026.20320) </span><span class="sxs-lookup"><span data-stu-id="d50e9-303">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="d50e9-304">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="d50e9-304">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="d50e9-305">Semi-Annual Channel: версия 1902 (сборка 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="d50e9-305">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="d50e9-306">Semi-Annual Channel: версия 1808 (сборка 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="d50e9-306">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-307">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-307">Excel</span></span>

-   [<span data-ttu-id="d50e9-308">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="d50e9-308">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="d50e9-309">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="d50e9-309">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="d50e9-310">10 сентября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-310">September 10, 2019</span></span>
<span data-ttu-id="d50e9-311">Monthly Channel: версия 1908 (сборка 11929.20300) </span><span class="sxs-lookup"><span data-stu-id="d50e9-311">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="d50e9-312">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="d50e9-312">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="d50e9-313">Semi-Annual Channel: версия 1902 (сборка 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="d50e9-313">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="d50e9-314">Semi-Annual Channel: версия 1808 (сборка 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="d50e9-314">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-315">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-315">Excel</span></span>

-   [<span data-ttu-id="d50e9-316">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="d50e9-316">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="d50e9-317">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="d50e9-317">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="d50e9-318">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-318">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-319">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="d50e9-319">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="d50e9-320">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="d50e9-320">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="d50e9-321">13 августа 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-321">August 13, 2019</span></span>
<span data-ttu-id="d50e9-322">Monthly Channel: версия 1907 (сборка 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="d50e9-322">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="d50e9-323">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="d50e9-323">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="d50e9-324">Semi-Annual Channel: версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="d50e9-324">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="d50e9-325">Semi-Annual Channel: версия 1808 (сборка 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="d50e9-325">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="d50e9-326">Semi-Annual Channel: версия 1803 (сборка 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="d50e9-326">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="d50e9-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-327">Outlook</span></span>

-   [<span data-ttu-id="d50e9-328">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="d50e9-328">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="d50e9-329">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="d50e9-329">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="d50e9-330">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="d50e9-330">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="d50e9-331">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-331">Word</span></span>

-   [<span data-ttu-id="d50e9-332">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="d50e9-332">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="d50e9-333">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="d50e9-333">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="d50e9-334">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-334">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-335">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="d50e9-335">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="d50e9-336">09 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-336">July 09, 2019</span></span>
<span data-ttu-id="d50e9-337">Monthly Channel: версия 1906 (сборка 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="d50e9-337">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="d50e9-338">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="d50e9-338">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="d50e9-339">Semi-Annual Channel: версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="d50e9-339">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="d50e9-340">Semi-Annual Channel: версия 1808 (сборка 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="d50e9-340">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="d50e9-341">Semi-Annual Channel: версия 1803 (сборка 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="d50e9-341">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="d50e9-342">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-342">Excel</span></span>

-   [<span data-ttu-id="d50e9-343">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="d50e9-343">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="d50e9-344">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="d50e9-344">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="d50e9-345">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="d50e9-345">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="d50e9-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-346">Outlook</span></span>

-   [<span data-ttu-id="d50e9-347">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="d50e9-347">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="d50e9-348">Skype для бизнеса</span><span class="sxs-lookup"><span data-stu-id="d50e9-348">Skype for Business</span></span>

-   [<span data-ttu-id="d50e9-349">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="d50e9-349">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="d50e9-350">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-350">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-351">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="d50e9-351">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="d50e9-352">11 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-352">June 11, 2019</span></span>
<span data-ttu-id="d50e9-353">Monthly Channel: версия 1905 (сборка 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="d50e9-353">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="d50e9-354">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="d50e9-354">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="d50e9-355">Semi-Annual Channel: версия 1808 (сборка 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="d50e9-355">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="d50e9-356">Semi-Annual Channel: версия 1803 (сборка 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="d50e9-356">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="d50e9-357">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-357">Word</span></span>

-   [<span data-ttu-id="d50e9-358">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="d50e9-358">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="d50e9-359">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="d50e9-359">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="d50e9-360">14 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-360">May 14, 2019</span></span>
<span data-ttu-id="d50e9-361">Monthly Channel: версия 1904 (сборка 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="d50e9-361">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="d50e9-362">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="d50e9-362">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="d50e9-363">Semi-Annual Channel: версия 1808 (сборка 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="d50e9-363">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="d50e9-364">Semi-Annual Channel: версия 1803 (сборка 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="d50e9-364">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="d50e9-365">Word</span><span class="sxs-lookup"><span data-stu-id="d50e9-365">Word</span></span>

-   [<span data-ttu-id="d50e9-366">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="d50e9-366">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="d50e9-367">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-367">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-368">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="d50e9-368">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="d50e9-369">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="d50e9-369">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="d50e9-370">9 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-370">April 09, 2019</span></span>
<span data-ttu-id="d50e9-371">Monthly Channel: версия 1903 (сборка 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="d50e9-371">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="d50e9-372">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="d50e9-372">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="d50e9-373">Semi-Annual Channel: версия 1808 (сборка 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="d50e9-373">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="d50e9-374">Semi-Annual Channel: версия 1803 (сборка 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="d50e9-374">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-375">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-375">Excel</span></span>

-   [<span data-ttu-id="d50e9-376">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="d50e9-376">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="d50e9-377">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-377">Office Suite</span></span>

-   [<span data-ttu-id="d50e9-378">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="d50e9-378">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="d50e9-379">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="d50e9-379">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="d50e9-380">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="d50e9-380">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="d50e9-381">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="d50e9-381">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="d50e9-382">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="d50e9-382">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="d50e9-383">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="d50e9-383">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="d50e9-384">12 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-384">March 12, 2019</span></span>
<span data-ttu-id="d50e9-385">В этом месяце ни для одного канала нет обновлений системы безопасности.</span><span class="sxs-lookup"><span data-stu-id="d50e9-385">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="d50e9-386">12 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-386">February 12, 2019</span></span>
<span data-ttu-id="d50e9-387">Monthly Channel: версия 1901 (сборка 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="d50e9-387">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="d50e9-388">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="d50e9-388">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="d50e9-389">Semi-Annual Channel: версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="d50e9-389">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="d50e9-390">Semi-Annual Channel: версия 1803 (сборка 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="d50e9-390">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="d50e9-391">Semi-Annual Channel: версия 1708 (сборка 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="d50e9-391">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="d50e9-392">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-392">Excel</span></span>

-   [<span data-ttu-id="d50e9-393">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="d50e9-393">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="d50e9-394">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d50e9-394">Office suite</span></span>

-   [<span data-ttu-id="d50e9-395">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="d50e9-395">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="d50e9-396">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="d50e9-396">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="d50e9-397">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="d50e9-397">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="d50e9-398">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="d50e9-398">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="d50e9-399">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="d50e9-399">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="d50e9-400">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="d50e9-400">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="d50e9-401">8 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-401">January 8, 2019</span></span>

<span data-ttu-id="d50e9-402">Monthly Channel: версия 1812 (сборка 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="d50e9-402">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="d50e9-403">Semi-Annual Targeted Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="d50e9-403">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="d50e9-404">Semi-Annual Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="d50e9-404">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="d50e9-405">Semi-Annual Channel: версия 1803 (сборка 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="d50e9-405">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="d50e9-406">Semi-Annual Channel: версия 1708 (сборка 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="d50e9-406">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="d50e9-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-407">Outlook</span></span>
-   [<span data-ttu-id="d50e9-408">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="d50e9-408">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="d50e9-409">Word. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="d50e9-409">Word: Security updates</span></span> 
-   [<span data-ttu-id="d50e9-410">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="d50e9-410">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="d50e9-411">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="d50e9-411">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="d50e9-412">Набор Office. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="d50e9-412">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="d50e9-413">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="d50e9-413">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="d50e9-414">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="d50e9-414">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="d50e9-415">11 декабря 2018 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-415">December 11, 2018</span></span>
<span data-ttu-id="d50e9-416">Monthly Channel: версия 1811 (сборка 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="d50e9-416">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="d50e9-417">Semi-Annual Channel: версия 1803 (сборка 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="d50e9-417">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="d50e9-418">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="d50e9-418">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-419">Excel</span><span class="sxs-lookup"><span data-stu-id="d50e9-419">Excel</span></span>

-   [<span data-ttu-id="d50e9-420">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="d50e9-420">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="d50e9-421">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="d50e9-421">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="d50e9-422">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="d50e9-422">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="d50e9-423">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="d50e9-423">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="d50e9-424">Outlook</span><span class="sxs-lookup"><span data-stu-id="d50e9-424">Outlook</span></span>

-   [<span data-ttu-id="d50e9-425">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="d50e9-425">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="d50e9-426">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d50e9-426">PowerPoint</span></span>

-   [<span data-ttu-id="d50e9-427">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="d50e9-427">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="d50e9-428">13 ноября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="d50e9-428">November 13, 2018</span></span>
<span data-ttu-id="d50e9-429">Monthly Channel: версия 1810 (сборка 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="d50e9-429">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="d50e9-430">Semi-Annual Channel: версия 1803 (сборка 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="d50e9-430">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="d50e9-431">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="d50e9-431">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="d50e9-432">Excel.</span><span class="sxs-lookup"><span data-stu-id="d50e9-432">Excel:</span></span>

-   [<span data-ttu-id="d50e9-433">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="d50e9-433">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="d50e9-434">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="d50e9-434">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="d50e9-435">Outlook.</span><span class="sxs-lookup"><span data-stu-id="d50e9-435">Outlook:</span></span>

-   [<span data-ttu-id="d50e9-436">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="d50e9-436">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="d50e9-437">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="d50e9-437">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="d50e9-438">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="d50e9-438">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="d50e9-439">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="d50e9-439">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="d50e9-440">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="d50e9-440">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="d50e9-441">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="d50e9-441">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="d50e9-442">Project.</span><span class="sxs-lookup"><span data-stu-id="d50e9-442">Project:</span></span>

-   [<span data-ttu-id="d50e9-443">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="d50e9-443">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="d50e9-444">Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="d50e9-444">Skype for Business:</span></span>

-   [<span data-ttu-id="d50e9-445">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="d50e9-445">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="d50e9-446">Word.</span><span class="sxs-lookup"><span data-stu-id="d50e9-446">Word:</span></span>

-   [<span data-ttu-id="d50e9-447">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="d50e9-447">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8573)
