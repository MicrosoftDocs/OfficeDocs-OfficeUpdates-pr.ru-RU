---
title: Заметки о выпуске обновлений для системы безопасности Microsoft Office
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Заметки о выпуске обновлений для системы безопасности Microsoft Office, предназначенные для ИТ-специалистов
ms.openlocfilehash: c9a4d3af52431016160bc8aa9e5f37200b90966d
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453297"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="2dae9-103">Заметки о выпуске обновлений для системы безопасности Microsoft Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="2dae9-104">Эти заметки о выпуске содержат сведения об исправлениях безопасности, которые входят в обновления для Microsoft Office.</span><span class="sxs-lookup"><span data-stu-id="2dae9-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="2dae9-105">Эта информация применима к Приложениям Microsoft 365 для предприятий, Приложениям Microsoft 365 для бизнеса, розничной версии Office 2016 (C2R) и Office 2019.</span><span class="sxs-lookup"><span data-stu-id="2dae9-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="2dae9-106">Мы вносим ряд изменений в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="2dae9-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2dae9-107">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="2dae9-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="2dae9-108">Office 365 профессиональный плюс с версии 2004 переименовывается в "Приложения Microsoft 365 для предприятий".</span><span class="sxs-lookup"><span data-stu-id="2dae9-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="2dae9-109"> Дополнительные сведения см. в  [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span><span class="sxs-lookup"><span data-stu-id="2dae9-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="2dae9-110"> В этой документации чаще всего используется обозначение "Приложения Microsoft 365".</span><span class="sxs-lookup"><span data-stu-id="2dae9-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (НЕ УДАЛЯТЬ СТРОКУ ВЫШЕ, она используется для интервала)  

## <a name="october-13-2020"></a><span data-ttu-id="2dae9-112">13 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-112">October 13, 2020</span></span>
<span data-ttu-id="2dae9-113">Актуальный канал: версия 2009 (сборка 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="2dae9-113">Current Channel: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="2dae9-114">Ежемесячный канал (корпоративный): версия 2008 (сборка 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="2dae9-114">Monthly Enterprise Channel: Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="2dae9-115">Ежемесячный канал (корпоративный): версия 2007 (сборка 13029.20708)</span><span class="sxs-lookup"><span data-stu-id="2dae9-115">Monthly Enterprise Channel: Version 2007 (Build 13029.20708)</span></span>  
<span data-ttu-id="2dae9-116">Полугодовой канал (предварительная корпоративная версия): версия 2008 (сборка 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="2dae9-116">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="2dae9-117">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="2dae9-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="2dae9-118">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20966)</span><span class="sxs-lookup"><span data-stu-id="2dae9-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20966)</span></span>  
<span data-ttu-id="2dae9-119">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="2dae9-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="2dae9-120">Розничная версия Office 2019: версия 2009 (сборка 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="2dae9-120">Office 2019 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="2dae9-121">Розничная версия Office 2016: версия 2009 (сборка 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="2dae9-121">Office 2016 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="2dae9-122">Корпоративная версия Office 2019: версия 1808 (сборка 10367.20048)</span><span class="sxs-lookup"><span data-stu-id="2dae9-122">Office 2019 Volume Licensed: Version 1808 (Build 10367.20048)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="access"></a><span data-ttu-id="2dae9-124">Access</span><span class="sxs-lookup"><span data-stu-id="2dae9-124">Access</span></span>

-   [<span data-ttu-id="2dae9-125">CVE-2020-16957</span><span class="sxs-lookup"><span data-stu-id="2dae9-125">CVE-2020-16957</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16957)

### <a name="excel"></a><span data-ttu-id="2dae9-126">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-126">Excel</span></span>

-   [<span data-ttu-id="2dae9-127">CVE-2020-16929</span><span class="sxs-lookup"><span data-stu-id="2dae9-127">CVE-2020-16929</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16929)
-   [<span data-ttu-id="2dae9-128">CVE-2020-16931</span><span class="sxs-lookup"><span data-stu-id="2dae9-128">CVE-2020-16931</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16931)
-   [<span data-ttu-id="2dae9-129">CVE-2020-16932</span><span class="sxs-lookup"><span data-stu-id="2dae9-129">CVE-2020-16932</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16932)

### <a name="outlook"></a><span data-ttu-id="2dae9-130">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-130">Outlook</span></span>

-   [<span data-ttu-id="2dae9-131">CVE-2020-16947</span><span class="sxs-lookup"><span data-stu-id="2dae9-131">CVE-2020-16947</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16947)
-   [<span data-ttu-id="2dae9-132">CVE-2020-16949</span><span class="sxs-lookup"><span data-stu-id="2dae9-132">CVE-2020-16949</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16949)

### <a name="word"></a><span data-ttu-id="2dae9-133">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-133">Word</span></span>

-   [<span data-ttu-id="2dae9-134">CVE-2020-16933</span><span class="sxs-lookup"><span data-stu-id="2dae9-134">CVE-2020-16933</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16933)

### <a name="office-suite"></a><span data-ttu-id="2dae9-135">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-135">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-136">CVE-2020-16930</span><span class="sxs-lookup"><span data-stu-id="2dae9-136">CVE-2020-16930</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16930)
-   [<span data-ttu-id="2dae9-137">CVE-2020-16955</span><span class="sxs-lookup"><span data-stu-id="2dae9-137">CVE-2020-16955</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16955)
-   [<span data-ttu-id="2dae9-138">CVE-2020-16928</span><span class="sxs-lookup"><span data-stu-id="2dae9-138">CVE-2020-16928</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16928)
-   [<span data-ttu-id="2dae9-139">CVE-2020-16934</span><span class="sxs-lookup"><span data-stu-id="2dae9-139">CVE-2020-16934</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16934)
-   [<span data-ttu-id="2dae9-140">CVE-2020-16918</span><span class="sxs-lookup"><span data-stu-id="2dae9-140">CVE-2020-16918</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16918)
-   [<span data-ttu-id="2dae9-141">CVE-2020-16954</span><span class="sxs-lookup"><span data-stu-id="2dae9-141">CVE-2020-16954</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-16954)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="september-08-2020"></a><span data-ttu-id="2dae9-143">08 сентября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-143">September 08, 2020</span></span>
<span data-ttu-id="2dae9-144">Актуальный канал: версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="2dae9-144">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="2dae9-145">Ежемесячный канал (корпоративный): версия 2007 (сборка 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="2dae9-145">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="2dae9-146">Ежемесячный канал (корпоративный): версия 2006 (сборка 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="2dae9-146">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="2dae9-147">Полугодовой канал (предварительная корпоративная версия): версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="2dae9-147">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="2dae9-148">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="2dae9-148">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="2dae9-149">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="2dae9-149">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="2dae9-150">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="2dae9-150">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="2dae9-151">Розничная версия Office 2019: версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="2dae9-151">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="2dae9-152">Розничная версия Office 2016: версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="2dae9-152">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="2dae9-153">Корпоративная версия Office 2019: версия 1808 (сборка 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="2dae9-153">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-155">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-155">Excel</span></span>

-   [<span data-ttu-id="2dae9-156">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="2dae9-156">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="2dae9-157">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="2dae9-157">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="2dae9-158">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="2dae9-158">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="2dae9-159">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="2dae9-159">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="2dae9-160">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-160">Word</span></span>

-   [<span data-ttu-id="2dae9-161">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="2dae9-161">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="2dae9-162">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="2dae9-162">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="2dae9-163">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-163">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-164">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="2dae9-164">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1193)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="august-11-2020"></a><span data-ttu-id="2dae9-166">11 августа 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-166">August 11, 2020</span></span>
<span data-ttu-id="2dae9-167">Актуальный канал: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="2dae9-167">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="2dae9-168">Ежемесячный канал (корпоративный): версия 2006 (сборка 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="2dae9-168">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="2dae9-169">Ежемесячный канал (корпоративный): версия 2005 (сборка 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="2dae9-169">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="2dae9-170">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="2dae9-170">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="2dae9-171">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="2dae9-171">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="2dae9-172">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="2dae9-172">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="2dae9-173">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="2dae9-173">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="2dae9-174">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="2dae9-174">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="2dae9-175">Розничная версия Office 2019: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="2dae9-175">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="2dae9-176">Розничная версия Office 2016: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="2dae9-176">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="2dae9-177">Корпоративная версия Office 2019: версия 1808 (сборка 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="2dae9-177">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="access"></a><span data-ttu-id="2dae9-179">Доступ</span><span class="sxs-lookup"><span data-stu-id="2dae9-179">Access</span></span>

-   [<span data-ttu-id="2dae9-180">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="2dae9-180">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="2dae9-181">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-181">Excel</span></span>

-   [<span data-ttu-id="2dae9-182">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="2dae9-182">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="2dae9-183">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="2dae9-183">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="2dae9-184">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="2dae9-184">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="2dae9-185">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="2dae9-185">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="2dae9-186">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="2dae9-186">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="2dae9-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-187">Outlook</span></span>

-   [<span data-ttu-id="2dae9-188">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="2dae9-188">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="2dae9-189">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="2dae9-189">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="2dae9-190">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-190">Word</span></span>

-   [<span data-ttu-id="2dae9-191">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="2dae9-191">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="2dae9-192">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="2dae9-192">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="2dae9-193">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="2dae9-193">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="2dae9-194">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-194">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-195">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="2dae9-195">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="2dae9-196">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="2dae9-196">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1563)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="july-14-2020"></a><span data-ttu-id="2dae9-198">14 июля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-198">July 14, 2020</span></span>
<span data-ttu-id="2dae9-199">Актуальный канал: версия 2006 (сборка 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="2dae9-199">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="2dae9-200">Ежемесячный канал (корпоративный)l: версия 2005 (сборка 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="2dae9-200">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="2dae9-201">Ежемесячный канал (корпоративный): версия 2004 (сборка 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="2dae9-201">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="2dae9-202">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="2dae9-202">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="2dae9-203">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="2dae9-203">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="2dae9-204">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="2dae9-204">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="2dae9-205">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="2dae9-205">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="2dae9-206">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="2dae9-206">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-208">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-208">Excel</span></span>

-   [<span data-ttu-id="2dae9-209">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="2dae9-209">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="2dae9-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-210">Outlook</span></span>

-   [<span data-ttu-id="2dae9-211">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="2dae9-211">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="2dae9-212">Project</span><span class="sxs-lookup"><span data-stu-id="2dae9-212">Project</span></span>

-   [<span data-ttu-id="2dae9-213">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="2dae9-213">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="2dae9-214">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-214">Word</span></span>

-   [<span data-ttu-id="2dae9-215">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="2dae9-215">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="2dae9-216">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="2dae9-216">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="2dae9-217">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="2dae9-217">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="2dae9-218">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="2dae9-218">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="2dae9-219">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-219">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-220">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="2dae9-220">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1458)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="june-09-2020"></a><span data-ttu-id="2dae9-222">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-222">June 09, 2020</span></span>
<span data-ttu-id="2dae9-223">Актуальный канал: версия 2005 (сборка 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="2dae9-223">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="2dae9-224">Ежемесячный канал (корпоративный): версия 2004 (сборка 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="2dae9-224">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="2dae9-225">Ежемесячный канал (корпоративный): версия 2003 (сборка 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="2dae9-225">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="2dae9-226">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="2dae9-226">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="2dae9-227">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="2dae9-227">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="2dae9-228">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="2dae9-228">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="2dae9-229">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="2dae9-229">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-231">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-231">Excel</span></span>

-   [<span data-ttu-id="2dae9-232">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="2dae9-232">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="2dae9-233">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="2dae9-233">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="2dae9-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-234">Outlook</span></span>

-   [<span data-ttu-id="2dae9-235">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="2dae9-235">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="2dae9-236">Project</span><span class="sxs-lookup"><span data-stu-id="2dae9-236">Project</span></span>

-   [<span data-ttu-id="2dae9-237">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="2dae9-237">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="2dae9-238">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-238">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-239">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="2dae9-239">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1321)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="may-12-2020"></a><span data-ttu-id="2dae9-241">12 мая 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-241">May 12, 2020</span></span>
<span data-ttu-id="2dae9-242">Monthly Channel: версия 2004 (сборка 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="2dae9-242">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="2dae9-243">Monthly Enterprise Channel: версия 2003 (сборка 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="2dae9-243">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="2dae9-244">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="2dae9-244">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="2dae9-245">Semi-Annual Channel: версия 1908 (сборка 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="2dae9-245">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="2dae9-246">Semi-Annual Channel: версия 1902 (сборка 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="2dae9-246">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="2dae9-247">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="2dae9-247">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-249">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-249">Excel</span></span>

-   [<span data-ttu-id="2dae9-250">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="2dae9-250">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0901)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="april-14-2020"></a><span data-ttu-id="2dae9-252">14 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-252">April 14, 2020</span></span>
<span data-ttu-id="2dae9-253">Monthly Channel: версия 2003 (сборка 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="2dae9-253">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="2dae9-254">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="2dae9-254">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="2dae9-255">Semi-Annual Channel: версия 1908 (сборка 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="2dae9-255">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="2dae9-256">Semi-Annual Channel: версия 1902 (сборка 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="2dae9-256">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="2dae9-257">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="2dae9-257">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-259">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-259">Excel</span></span>

-   [<span data-ttu-id="2dae9-260">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="2dae9-260">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="2dae9-261">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="2dae9-261">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="2dae9-262">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-262">Word</span></span>

-   [<span data-ttu-id="2dae9-263">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="2dae9-263">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="2dae9-264">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-264">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-265">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="2dae9-265">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="2dae9-266">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="2dae9-266">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="2dae9-267">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="2dae9-267">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0961)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="march-10-2020"></a><span data-ttu-id="2dae9-269">10 марта 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-269">March 10, 2020</span></span>
<span data-ttu-id="2dae9-270">Ежемесячный канал: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="2dae9-270">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="2dae9-271">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="2dae9-271">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="2dae9-272">Semi-Annual Channel: версия 1908 (сборка 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="2dae9-272">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="2dae9-273">Semi-Annual Channel: версия 1902 (сборка 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="2dae9-273">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="2dae9-274">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="2dae9-274">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)



### <a name="word"></a><span data-ttu-id="2dae9-276">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-276">Word</span></span>

-   [<span data-ttu-id="2dae9-277">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="2dae9-277">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="2dae9-278">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="2dae9-278">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="2dae9-279">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="2dae9-279">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="2dae9-280">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="2dae9-280">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0851)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="february-11-2020"></a><span data-ttu-id="2dae9-282">11 февраля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-282">February 11, 2020</span></span>
<span data-ttu-id="2dae9-283">Месячный канал: версия 2001 (сборка 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="2dae9-283">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="2dae9-284">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="2dae9-284">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="2dae9-285">Semi-Annual Channel: версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="2dae9-285">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="2dae9-286">Semi-Annual Channel: версия 1902 (сборка 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="2dae9-286">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="2dae9-287">Semi-Annual Channel: версия 1808 (сборка 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="2dae9-287">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-289">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-289">Excel</span></span>

-   [<span data-ttu-id="2dae9-290">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="2dae9-290">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="2dae9-291">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-291">Outlook</span></span>

-   [<span data-ttu-id="2dae9-292">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="2dae9-292">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="2dae9-293">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-293">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-294">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="2dae9-294">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0697)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="january-14-2020"></a><span data-ttu-id="2dae9-296">14 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-296">January 14, 2020</span></span>
<span data-ttu-id="2dae9-297">Monthly Channel: версия 1912 (сборка 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="2dae9-297">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="2dae9-298">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="2dae9-298">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="2dae9-299">Semi-Annual Channel: версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="2dae9-299">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="2dae9-300">Semi-Annual Channel: версия 1902 (сборка 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="2dae9-300">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="2dae9-301">Semi-Annual Channel: версия 1808 (сборка 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="2dae9-301">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="2dae9-303">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-303">Excel</span></span>

-   [<span data-ttu-id="2dae9-304">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="2dae9-304">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="2dae9-305">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="2dae9-305">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="2dae9-306">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="2dae9-306">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="2dae9-307">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-307">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-308">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="2dae9-308">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0652)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, КОНЕЦ СОДЕРЖИМОГО)



## <a name="december-10-2019"></a><span data-ttu-id="2dae9-310">10 декабря 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-310">December 10, 2019</span></span>
<span data-ttu-id="2dae9-311">Monthly Channel: версия 1911 (сборка 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="2dae9-311">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="2dae9-312">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="2dae9-312">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="2dae9-313">Semi-Annual Channel: версия 1902 (сборка 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="2dae9-313">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="2dae9-314">Semi-Annual Channel: версия 1808 (сборка 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="2dae9-314">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-315">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-315">Excel</span></span>

-   [<span data-ttu-id="2dae9-316">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="2dae9-316">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="2dae9-317">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dae9-317">PowerPoint</span></span>

-   [<span data-ttu-id="2dae9-318">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="2dae9-318">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="2dae9-319">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-319">Word</span></span>

-   [<span data-ttu-id="2dae9-320">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="2dae9-320">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="2dae9-321">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-321">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-322">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="2dae9-322">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="2dae9-323">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="2dae9-323">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="2dae9-324">12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-324">November 12, 2019</span></span>
<span data-ttu-id="2dae9-325">Monthly Channel: версия 1910 (сборка 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="2dae9-325">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="2dae9-326">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="2dae9-326">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="2dae9-327">Semi-Annual Channel: версия 1902 (сборка 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="2dae9-327">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="2dae9-328">Semi-Annual Channel: версия 1808 (сборка 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="2dae9-328">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-329">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-329">Excel</span></span>

-   [<span data-ttu-id="2dae9-330">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="2dae9-330">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="2dae9-331">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="2dae9-331">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="2dae9-332">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-332">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-333">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="2dae9-333">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="2dae9-334">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="2dae9-334">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="2dae9-335">08 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-335">October 08, 2019</span></span>
<span data-ttu-id="2dae9-336">Monthly Channel: версия 1909 (сборка 12026.20320) </span><span class="sxs-lookup"><span data-stu-id="2dae9-336">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="2dae9-337">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="2dae9-337">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="2dae9-338">Semi-Annual Channel: версия 1902 (сборка 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="2dae9-338">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="2dae9-339">Semi-Annual Channel: версия 1808 (сборка 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="2dae9-339">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-340">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-340">Excel</span></span>

-   [<span data-ttu-id="2dae9-341">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="2dae9-341">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="2dae9-342">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="2dae9-342">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="2dae9-343">10 сентября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-343">September 10, 2019</span></span>
<span data-ttu-id="2dae9-344">Monthly Channel: версия 1908 (сборка 11929.20300) </span><span class="sxs-lookup"><span data-stu-id="2dae9-344">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="2dae9-345">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="2dae9-345">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="2dae9-346">Semi-Annual Channel: версия 1902 (сборка 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="2dae9-346">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="2dae9-347">Semi-Annual Channel: версия 1808 (сборка 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="2dae9-347">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-348">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-348">Excel</span></span>

-   [<span data-ttu-id="2dae9-349">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="2dae9-349">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="2dae9-350">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="2dae9-350">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="2dae9-351">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-351">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-352">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="2dae9-352">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="2dae9-353">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="2dae9-353">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="2dae9-354">13 августа 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-354">August 13, 2019</span></span>
<span data-ttu-id="2dae9-355">Monthly Channel: версия 1907 (сборка 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="2dae9-355">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="2dae9-356">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="2dae9-356">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="2dae9-357">Semi-Annual Channel: версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="2dae9-357">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="2dae9-358">Semi-Annual Channel: версия 1808 (сборка 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="2dae9-358">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="2dae9-359">Semi-Annual Channel: версия 1803 (сборка 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="2dae9-359">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="2dae9-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-360">Outlook</span></span>

-   [<span data-ttu-id="2dae9-361">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="2dae9-361">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="2dae9-362">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="2dae9-362">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="2dae9-363">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="2dae9-363">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="2dae9-364">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-364">Word</span></span>

-   [<span data-ttu-id="2dae9-365">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="2dae9-365">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="2dae9-366">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="2dae9-366">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="2dae9-367">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-367">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-368">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="2dae9-368">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="2dae9-369">09 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-369">July 09, 2019</span></span>
<span data-ttu-id="2dae9-370">Monthly Channel: версия 1906 (сборка 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="2dae9-370">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="2dae9-371">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="2dae9-371">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="2dae9-372">Semi-Annual Channel: версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="2dae9-372">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="2dae9-373">Semi-Annual Channel: версия 1808 (сборка 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="2dae9-373">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="2dae9-374">Semi-Annual Channel: версия 1803 (сборка 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="2dae9-374">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="2dae9-375">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-375">Excel</span></span>

-   [<span data-ttu-id="2dae9-376">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="2dae9-376">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="2dae9-377">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="2dae9-377">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="2dae9-378">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="2dae9-378">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="2dae9-379">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-379">Outlook</span></span>

-   [<span data-ttu-id="2dae9-380">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="2dae9-380">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="2dae9-381">Skype для бизнеса</span><span class="sxs-lookup"><span data-stu-id="2dae9-381">Skype for Business</span></span>

-   [<span data-ttu-id="2dae9-382">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="2dae9-382">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="2dae9-383">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-383">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-384">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="2dae9-384">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="2dae9-385">11 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-385">June 11, 2019</span></span>
<span data-ttu-id="2dae9-386">Monthly Channel: версия 1905 (сборка 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="2dae9-386">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="2dae9-387">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="2dae9-387">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="2dae9-388">Semi-Annual Channel: версия 1808 (сборка 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="2dae9-388">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="2dae9-389">Semi-Annual Channel: версия 1803 (сборка 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="2dae9-389">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="2dae9-390">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-390">Word</span></span>

-   [<span data-ttu-id="2dae9-391">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="2dae9-391">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="2dae9-392">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="2dae9-392">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="2dae9-393">14 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-393">May 14, 2019</span></span>
<span data-ttu-id="2dae9-394">Monthly Channel: версия 1904 (сборка 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="2dae9-394">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="2dae9-395">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="2dae9-395">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="2dae9-396">Semi-Annual Channel: версия 1808 (сборка 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="2dae9-396">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="2dae9-397">Semi-Annual Channel: версия 1803 (сборка 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="2dae9-397">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="2dae9-398">Word</span><span class="sxs-lookup"><span data-stu-id="2dae9-398">Word</span></span>

-   [<span data-ttu-id="2dae9-399">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="2dae9-399">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="2dae9-400">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-400">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-401">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="2dae9-401">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="2dae9-402">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="2dae9-402">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="2dae9-403">9 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-403">April 09, 2019</span></span>
<span data-ttu-id="2dae9-404">Monthly Channel: версия 1903 (сборка 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="2dae9-404">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="2dae9-405">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="2dae9-405">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="2dae9-406">Semi-Annual Channel: версия 1808 (сборка 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="2dae9-406">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="2dae9-407">Semi-Annual Channel: версия 1803 (сборка 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="2dae9-407">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-408">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-408">Excel</span></span>

-   [<span data-ttu-id="2dae9-409">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="2dae9-409">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="2dae9-410">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-410">Office Suite</span></span>

-   [<span data-ttu-id="2dae9-411">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="2dae9-411">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="2dae9-412">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="2dae9-412">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="2dae9-413">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="2dae9-413">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="2dae9-414">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="2dae9-414">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="2dae9-415">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="2dae9-415">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="2dae9-416">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="2dae9-416">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="2dae9-417">12 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-417">March 12, 2019</span></span>
<span data-ttu-id="2dae9-418">В этом месяце ни для одного канала нет обновлений системы безопасности.</span><span class="sxs-lookup"><span data-stu-id="2dae9-418">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="2dae9-419">12 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-419">February 12, 2019</span></span>
<span data-ttu-id="2dae9-420">Monthly Channel: версия 1901 (сборка 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="2dae9-420">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="2dae9-421">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="2dae9-421">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="2dae9-422">Semi-Annual Channel: версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="2dae9-422">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="2dae9-423">Semi-Annual Channel: версия 1803 (сборка 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="2dae9-423">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="2dae9-424">Semi-Annual Channel: версия 1708 (сборка 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="2dae9-424">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="2dae9-425">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-425">Excel</span></span>

-   [<span data-ttu-id="2dae9-426">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="2dae9-426">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="2dae9-427">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dae9-427">Office suite</span></span>

-   [<span data-ttu-id="2dae9-428">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="2dae9-428">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="2dae9-429">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="2dae9-429">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="2dae9-430">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="2dae9-430">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="2dae9-431">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="2dae9-431">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="2dae9-432">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="2dae9-432">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="2dae9-433">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="2dae9-433">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="2dae9-434">8 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-434">January 8, 2019</span></span>

<span data-ttu-id="2dae9-435">Monthly Channel: версия 1812 (сборка 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="2dae9-435">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="2dae9-436">Semi-Annual Targeted Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="2dae9-436">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="2dae9-437">Semi-Annual Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="2dae9-437">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="2dae9-438">Semi-Annual Channel: версия 1803 (сборка 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="2dae9-438">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="2dae9-439">Semi-Annual Channel: версия 1708 (сборка 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="2dae9-439">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="2dae9-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-440">Outlook</span></span>
-   [<span data-ttu-id="2dae9-441">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="2dae9-441">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="2dae9-442">Word. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="2dae9-442">Word: Security updates</span></span> 
-   [<span data-ttu-id="2dae9-443">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="2dae9-443">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="2dae9-444">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="2dae9-444">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="2dae9-445">Набор Office. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="2dae9-445">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="2dae9-446">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="2dae9-446">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="2dae9-447">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="2dae9-447">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="2dae9-448">11 декабря 2018 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-448">December 11, 2018</span></span>
<span data-ttu-id="2dae9-449">Monthly Channel: версия 1811 (сборка 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="2dae9-449">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="2dae9-450">Semi-Annual Channel: версия 1803 (сборка 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="2dae9-450">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="2dae9-451">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="2dae9-451">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-452">Excel</span><span class="sxs-lookup"><span data-stu-id="2dae9-452">Excel</span></span>

-   [<span data-ttu-id="2dae9-453">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="2dae9-453">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="2dae9-454">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="2dae9-454">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="2dae9-455">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="2dae9-455">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="2dae9-456">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="2dae9-456">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="2dae9-457">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dae9-457">Outlook</span></span>

-   [<span data-ttu-id="2dae9-458">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="2dae9-458">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="2dae9-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dae9-459">PowerPoint</span></span>

-   [<span data-ttu-id="2dae9-460">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="2dae9-460">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="2dae9-461">13 ноября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="2dae9-461">November 13, 2018</span></span>
<span data-ttu-id="2dae9-462">Monthly Channel: версия 1810 (сборка 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="2dae9-462">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="2dae9-463">Semi-Annual Channel: версия 1803 (сборка 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="2dae9-463">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="2dae9-464">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="2dae9-464">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="2dae9-465">Excel.</span><span class="sxs-lookup"><span data-stu-id="2dae9-465">Excel:</span></span>

-   [<span data-ttu-id="2dae9-466">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="2dae9-466">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="2dae9-467">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="2dae9-467">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="2dae9-468">Outlook.</span><span class="sxs-lookup"><span data-stu-id="2dae9-468">Outlook:</span></span>

-   [<span data-ttu-id="2dae9-469">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="2dae9-469">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="2dae9-470">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="2dae9-470">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="2dae9-471">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="2dae9-471">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="2dae9-472">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="2dae9-472">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="2dae9-473">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="2dae9-473">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="2dae9-474">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="2dae9-474">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="2dae9-475">Project.</span><span class="sxs-lookup"><span data-stu-id="2dae9-475">Project:</span></span>

-   [<span data-ttu-id="2dae9-476">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="2dae9-476">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="2dae9-477">Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="2dae9-477">Skype for Business:</span></span>

-   [<span data-ttu-id="2dae9-478">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="2dae9-478">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="2dae9-479">Word.</span><span class="sxs-lookup"><span data-stu-id="2dae9-479">Word:</span></span>

-   [<span data-ttu-id="2dae9-480">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="2dae9-480">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8573)
