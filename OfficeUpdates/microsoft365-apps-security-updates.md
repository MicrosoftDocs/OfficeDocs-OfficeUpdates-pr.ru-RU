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
ms.openlocfilehash: f8fc5a41e72074071de05ced6857e2ba1f5e7e21
ms.sourcegitcommit: 931b78282277a0d12779c6b4cae33181b4568c34
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/09/2020
ms.locfileid: "47420698"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="7f68e-103">Заметки о выпуске обновлений для системы безопасности Microsoft Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="7f68e-104">Эти заметки о выпуске содержат сведения об исправлениях безопасности, которые входят в обновления для Microsoft Office.</span><span class="sxs-lookup"><span data-stu-id="7f68e-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="7f68e-105">Эта информация применима к Приложениям Microsoft 365 для предприятий, Приложениям Microsoft 365 для бизнеса, розничной версии Office 2016 (C2R) и Office 2019.</span><span class="sxs-lookup"><span data-stu-id="7f68e-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="7f68e-106">Мы вносим ряд изменений в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="7f68e-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="7f68e-107">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="7f68e-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="7f68e-108">Office 365 профессиональный плюс с версии 2004 переименовывается в "Приложения Microsoft 365 для предприятий".</span><span class="sxs-lookup"><span data-stu-id="7f68e-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="7f68e-109"> Дополнительные сведения см. в  [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span><span class="sxs-lookup"><span data-stu-id="7f68e-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="7f68e-110"> В этой документации чаще всего используется обозначение "Приложения Microsoft 365".</span><span class="sxs-lookup"><span data-stu-id="7f68e-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (НЕ УДАЛЯТЬ СТРОКУ ВЫШЕ, она используется для интервала)  

## <a name="september-08-2020"></a><span data-ttu-id="7f68e-112">08 сентября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-112">September 08, 2020</span></span>
<span data-ttu-id="7f68e-113">Актуальный канал: версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="7f68e-113">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="7f68e-114">Ежемесячный канал (корпоративный): версия 2007 (сборка 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="7f68e-114">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="7f68e-115">Ежемесячный канал (корпоративный): версия 2006 (сборка 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="7f68e-115">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="7f68e-116">Полугодовой канал (предварительная корпоративная версия): версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="7f68e-116">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="7f68e-117">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="7f68e-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="7f68e-118">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="7f68e-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="7f68e-119">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="7f68e-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="7f68e-120">Розничная версия Office 2019: версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="7f68e-120">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="7f68e-121">Розничная версия Office 2016: версия 2008 (сборка 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="7f68e-121">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="7f68e-122">Корпоративная версия Office 2019: версия 1808 (сборка 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="7f68e-122">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-124">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-124">Excel</span></span>

-   [<span data-ttu-id="7f68e-125">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="7f68e-125">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="7f68e-126">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="7f68e-126">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="7f68e-127">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="7f68e-127">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="7f68e-128">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="7f68e-128">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="7f68e-129">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-129">Word</span></span>

-   [<span data-ttu-id="7f68e-130">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="7f68e-130">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="7f68e-131">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="7f68e-131">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="7f68e-132">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-132">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-133">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="7f68e-133">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1193)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="august-11-2020"></a><span data-ttu-id="7f68e-135">11 августа 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-135">August 11, 2020</span></span>
<span data-ttu-id="7f68e-136">Актуальный канал: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="7f68e-136">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="7f68e-137">Ежемесячный канал (корпоративный): версия 2006 (сборка 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="7f68e-137">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="7f68e-138">Ежемесячный канал (корпоративный): версия 2005 (сборка 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="7f68e-138">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="7f68e-139">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="7f68e-139">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="7f68e-140">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="7f68e-140">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="7f68e-141">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="7f68e-141">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="7f68e-142">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="7f68e-142">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="7f68e-143">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="7f68e-143">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="7f68e-144">Розничная версия Office 2019: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="7f68e-144">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="7f68e-145">Розничная версия Office 2016: версия 2007 (сборка 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="7f68e-145">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="7f68e-146">Корпоративная версия Office 2019: версия 1808 (сборка 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="7f68e-146">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="access"></a><span data-ttu-id="7f68e-148">Доступ</span><span class="sxs-lookup"><span data-stu-id="7f68e-148">Access</span></span>

-   [<span data-ttu-id="7f68e-149">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="7f68e-149">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="7f68e-150">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-150">Excel</span></span>

-   [<span data-ttu-id="7f68e-151">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="7f68e-151">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="7f68e-152">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="7f68e-152">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="7f68e-153">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="7f68e-153">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="7f68e-154">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="7f68e-154">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="7f68e-155">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="7f68e-155">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="7f68e-156">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-156">Outlook</span></span>

-   [<span data-ttu-id="7f68e-157">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="7f68e-157">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="7f68e-158">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="7f68e-158">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="7f68e-159">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-159">Word</span></span>

-   [<span data-ttu-id="7f68e-160">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="7f68e-160">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="7f68e-161">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="7f68e-161">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="7f68e-162">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="7f68e-162">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="7f68e-163">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-163">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-164">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="7f68e-164">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="7f68e-165">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="7f68e-165">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1563)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="july-14-2020"></a><span data-ttu-id="7f68e-167">14 июля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-167">July 14, 2020</span></span>
<span data-ttu-id="7f68e-168">Актуальный канал: версия 2006 (сборка 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="7f68e-168">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="7f68e-169">Ежемесячный канал (корпоративный)l: версия 2005 (сборка 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="7f68e-169">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="7f68e-170">Ежемесячный канал (корпоративный): версия 2004 (сборка 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="7f68e-170">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="7f68e-171">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="7f68e-171">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="7f68e-172">Полугодовой канал (корпоративный): версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="7f68e-172">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="7f68e-173">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="7f68e-173">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="7f68e-174">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="7f68e-174">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="7f68e-175">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="7f68e-175">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-177">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-177">Excel</span></span>

-   [<span data-ttu-id="7f68e-178">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="7f68e-178">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="7f68e-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-179">Outlook</span></span>

-   [<span data-ttu-id="7f68e-180">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="7f68e-180">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="7f68e-181">Project</span><span class="sxs-lookup"><span data-stu-id="7f68e-181">Project</span></span>

-   [<span data-ttu-id="7f68e-182">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="7f68e-182">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="7f68e-183">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-183">Word</span></span>

-   [<span data-ttu-id="7f68e-184">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="7f68e-184">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="7f68e-185">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="7f68e-185">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="7f68e-186">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="7f68e-186">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="7f68e-187">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="7f68e-187">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="7f68e-188">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-188">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-189">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="7f68e-189">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1458)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="june-09-2020"></a><span data-ttu-id="7f68e-191">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-191">June 09, 2020</span></span>
<span data-ttu-id="7f68e-192">Актуальный канал: версия 2005 (сборка 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="7f68e-192">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="7f68e-193">Ежемесячный канал (корпоративный): версия 2004 (сборка 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="7f68e-193">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="7f68e-194">Ежемесячный канал (корпоративный): версия 2003 (сборка 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="7f68e-194">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="7f68e-195">Полугодовой канал (предварительная корпоративная версия): версия 2002 (сборка 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="7f68e-195">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="7f68e-196">Полугодовой канал (корпоративный): версия 1908 (сборка 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="7f68e-196">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="7f68e-197">Полугодовой канал (корпоративный): версия 1902 (сборка 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="7f68e-197">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="7f68e-198">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="7f68e-198">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-200">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-200">Excel</span></span>

-   [<span data-ttu-id="7f68e-201">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="7f68e-201">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="7f68e-202">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="7f68e-202">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="7f68e-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-203">Outlook</span></span>

-   [<span data-ttu-id="7f68e-204">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="7f68e-204">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="7f68e-205">Project</span><span class="sxs-lookup"><span data-stu-id="7f68e-205">Project</span></span>

-   [<span data-ttu-id="7f68e-206">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="7f68e-206">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="7f68e-207">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-207">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-208">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="7f68e-208">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-1321)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="may-12-2020"></a><span data-ttu-id="7f68e-210">12 мая 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-210">May 12, 2020</span></span>
<span data-ttu-id="7f68e-211">Monthly Channel: версия 2004 (сборка 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="7f68e-211">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="7f68e-212">Monthly Enterprise Channel: версия 2003 (сборка 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="7f68e-212">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="7f68e-213">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="7f68e-213">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="7f68e-214">Semi-Annual Channel: версия 1908 (сборка 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="7f68e-214">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="7f68e-215">Semi-Annual Channel: версия 1902 (сборка 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="7f68e-215">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="7f68e-216">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="7f68e-216">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-218">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-218">Excel</span></span>

-   [<span data-ttu-id="7f68e-219">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="7f68e-219">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0901)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="april-14-2020"></a><span data-ttu-id="7f68e-221">14 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-221">April 14, 2020</span></span>
<span data-ttu-id="7f68e-222">Monthly Channel: версия 2003 (сборка 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="7f68e-222">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="7f68e-223">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="7f68e-223">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="7f68e-224">Semi-Annual Channel: версия 1908 (сборка 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="7f68e-224">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="7f68e-225">Semi-Annual Channel: версия 1902 (сборка 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="7f68e-225">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="7f68e-226">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="7f68e-226">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-228">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-228">Excel</span></span>

-   [<span data-ttu-id="7f68e-229">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="7f68e-229">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="7f68e-230">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="7f68e-230">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="7f68e-231">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-231">Word</span></span>

-   [<span data-ttu-id="7f68e-232">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="7f68e-232">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="7f68e-233">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-233">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-234">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="7f68e-234">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="7f68e-235">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="7f68e-235">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="7f68e-236">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="7f68e-236">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0961)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="march-10-2020"></a><span data-ttu-id="7f68e-238">10 марта 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-238">March 10, 2020</span></span>
<span data-ttu-id="7f68e-239">Ежемесячный канал: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="7f68e-239">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="7f68e-240">Semi-Annual Channel (Targeted): версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="7f68e-240">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="7f68e-241">Semi-Annual Channel: версия 1908 (сборка 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="7f68e-241">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="7f68e-242">Semi-Annual Channel: версия 1902 (сборка 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="7f68e-242">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="7f68e-243">Приложения Microsoft 365 в Windows 7: версия 2002 (сборка 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="7f68e-243">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)



### <a name="word"></a><span data-ttu-id="7f68e-245">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-245">Word</span></span>

-   [<span data-ttu-id="7f68e-246">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="7f68e-246">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="7f68e-247">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="7f68e-247">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="7f68e-248">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="7f68e-248">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="7f68e-249">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="7f68e-249">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0851)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="february-11-2020"></a><span data-ttu-id="7f68e-251">11 февраля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-251">February 11, 2020</span></span>
<span data-ttu-id="7f68e-252">Месячный канал: версия 2001 (сборка 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="7f68e-252">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="7f68e-253">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="7f68e-253">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="7f68e-254">Semi-Annual Channel: версия 1908 (сборка 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="7f68e-254">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="7f68e-255">Semi-Annual Channel: версия 1902 (сборка 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="7f68e-255">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="7f68e-256">Semi-Annual Channel: версия 1808 (сборка 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="7f68e-256">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-258">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-258">Excel</span></span>

-   [<span data-ttu-id="7f68e-259">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="7f68e-259">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="7f68e-260">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-260">Outlook</span></span>

-   [<span data-ttu-id="7f68e-261">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="7f68e-261">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="7f68e-262">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-262">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-263">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="7f68e-263">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0697)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ КОНЕЦ СОДЕРЖИМОГО)



## <a name="january-14-2020"></a><span data-ttu-id="7f68e-265">14 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-265">January 14, 2020</span></span>
<span data-ttu-id="7f68e-266">Monthly Channel: версия 1912 (сборка 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="7f68e-266">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="7f68e-267">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="7f68e-267">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="7f68e-268">Semi-Annual Channel: версия 1908 (сборка 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="7f68e-268">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="7f68e-269">Semi-Annual Channel: версия 1902 (сборка 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="7f68e-269">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="7f68e-270">Semi-Annual Channel: версия 1808 (сборка 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="7f68e-270">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, НАЧАЛО СОДЕРЖИМОГО)


### <a name="excel"></a><span data-ttu-id="7f68e-272">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-272">Excel</span></span>

-   [<span data-ttu-id="7f68e-273">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="7f68e-273">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="7f68e-274">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="7f68e-274">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="7f68e-275">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="7f68e-275">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="7f68e-276">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-276">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-277">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="7f68e-277">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2020-0652)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О БЕЗОПАСНОСТИ, КОНЕЦ СОДЕРЖИМОГО)



## <a name="december-10-2019"></a><span data-ttu-id="7f68e-279">10 декабря 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-279">December 10, 2019</span></span>
<span data-ttu-id="7f68e-280">Monthly Channel: версия 1911 (сборка 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="7f68e-280">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="7f68e-281">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="7f68e-281">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="7f68e-282">Semi-Annual Channel: версия 1902 (сборка 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="7f68e-282">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="7f68e-283">Semi-Annual Channel: версия 1808 (сборка 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="7f68e-283">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-284">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-284">Excel</span></span>

-   [<span data-ttu-id="7f68e-285">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="7f68e-285">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="7f68e-286">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7f68e-286">PowerPoint</span></span>

-   [<span data-ttu-id="7f68e-287">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="7f68e-287">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="7f68e-288">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-288">Word</span></span>

-   [<span data-ttu-id="7f68e-289">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="7f68e-289">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="7f68e-290">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-290">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-291">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="7f68e-291">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="7f68e-292">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="7f68e-292">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="7f68e-293">12 ноября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-293">November 12, 2019</span></span>
<span data-ttu-id="7f68e-294">Monthly Channel: версия 1910 (сборка 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="7f68e-294">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="7f68e-295">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="7f68e-295">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="7f68e-296">Semi-Annual Channel: версия 1902 (сборка 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="7f68e-296">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="7f68e-297">Semi-Annual Channel: версия 1808 (сборка 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="7f68e-297">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-298">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-298">Excel</span></span>

-   [<span data-ttu-id="7f68e-299">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="7f68e-299">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="7f68e-300">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="7f68e-300">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="7f68e-301">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-301">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-302">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="7f68e-302">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="7f68e-303">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="7f68e-303">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="7f68e-304">08 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-304">October 08, 2019</span></span>
<span data-ttu-id="7f68e-305">Monthly Channel: версия 1909 (сборка 12026.20320) </span><span class="sxs-lookup"><span data-stu-id="7f68e-305">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="7f68e-306">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="7f68e-306">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="7f68e-307">Semi-Annual Channel: версия 1902 (сборка 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="7f68e-307">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="7f68e-308">Semi-Annual Channel: версия 1808 (сборка 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="7f68e-308">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-309">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-309">Excel</span></span>

-   [<span data-ttu-id="7f68e-310">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="7f68e-310">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="7f68e-311">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="7f68e-311">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="7f68e-312">10 сентября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-312">September 10, 2019</span></span>
<span data-ttu-id="7f68e-313">Monthly Channel: версия 1908 (сборка 11929.20300) </span><span class="sxs-lookup"><span data-stu-id="7f68e-313">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="7f68e-314">Semi-Annual Channel (Targeted): версия 1908 (сборка 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="7f68e-314">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="7f68e-315">Semi-Annual Channel: версия 1902 (сборка 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="7f68e-315">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="7f68e-316">Semi-Annual Channel: версия 1808 (сборка 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="7f68e-316">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-317">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-317">Excel</span></span>

-   [<span data-ttu-id="7f68e-318">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="7f68e-318">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="7f68e-319">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="7f68e-319">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="7f68e-320">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-320">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-321">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="7f68e-321">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="7f68e-322">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="7f68e-322">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="7f68e-323">13 августа 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-323">August 13, 2019</span></span>
<span data-ttu-id="7f68e-324">Monthly Channel: версия 1907 (сборка 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="7f68e-324">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="7f68e-325">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="7f68e-325">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="7f68e-326">Semi-Annual Channel: версия 1902 (сборка 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="7f68e-326">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="7f68e-327">Semi-Annual Channel: версия 1808 (сборка 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="7f68e-327">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="7f68e-328">Semi-Annual Channel: версия 1803 (сборка 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="7f68e-328">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="7f68e-329">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-329">Outlook</span></span>

-   [<span data-ttu-id="7f68e-330">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="7f68e-330">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="7f68e-331">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="7f68e-331">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="7f68e-332">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="7f68e-332">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="7f68e-333">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-333">Word</span></span>

-   [<span data-ttu-id="7f68e-334">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="7f68e-334">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="7f68e-335">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="7f68e-335">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="7f68e-336">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-336">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-337">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="7f68e-337">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="7f68e-338">09 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-338">July 09, 2019</span></span>
<span data-ttu-id="7f68e-339">Monthly Channel: версия 1906 (сборка 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="7f68e-339">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="7f68e-340">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="7f68e-340">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="7f68e-341">Semi-Annual Channel: версия 1902 (сборка 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="7f68e-341">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="7f68e-342">Semi-Annual Channel: версия 1808 (сборка 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="7f68e-342">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="7f68e-343">Semi-Annual Channel: версия 1803 (сборка 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="7f68e-343">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="7f68e-344">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-344">Excel</span></span>

-   [<span data-ttu-id="7f68e-345">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="7f68e-345">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="7f68e-346">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="7f68e-346">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="7f68e-347">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="7f68e-347">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="7f68e-348">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-348">Outlook</span></span>

-   [<span data-ttu-id="7f68e-349">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="7f68e-349">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="7f68e-350">Skype для бизнеса</span><span class="sxs-lookup"><span data-stu-id="7f68e-350">Skype for Business</span></span>

-   [<span data-ttu-id="7f68e-351">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="7f68e-351">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="7f68e-352">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-352">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-353">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="7f68e-353">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="7f68e-354">11 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-354">June 11, 2019</span></span>
<span data-ttu-id="7f68e-355">Monthly Channel: версия 1905 (сборка 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="7f68e-355">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="7f68e-356">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="7f68e-356">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="7f68e-357">Semi-Annual Channel: версия 1808 (сборка 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="7f68e-357">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="7f68e-358">Semi-Annual Channel: версия 1803 (сборка 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="7f68e-358">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="7f68e-359">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-359">Word</span></span>

-   [<span data-ttu-id="7f68e-360">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="7f68e-360">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="7f68e-361">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="7f68e-361">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="7f68e-362">14 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-362">May 14, 2019</span></span>
<span data-ttu-id="7f68e-363">Monthly Channel: версия 1904 (сборка 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="7f68e-363">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="7f68e-364">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="7f68e-364">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="7f68e-365">Semi-Annual Channel: версия 1808 (сборка 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="7f68e-365">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="7f68e-366">Semi-Annual Channel: версия 1803 (сборка 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="7f68e-366">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="7f68e-367">Word</span><span class="sxs-lookup"><span data-stu-id="7f68e-367">Word</span></span>

-   [<span data-ttu-id="7f68e-368">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="7f68e-368">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="7f68e-369">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-369">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-370">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="7f68e-370">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="7f68e-371">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="7f68e-371">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="7f68e-372">9 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-372">April 09, 2019</span></span>
<span data-ttu-id="7f68e-373">Monthly Channel: версия 1903 (сборка 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="7f68e-373">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="7f68e-374">Semi-Annual Channel (Targeted): версия 1902 (сборка 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="7f68e-374">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="7f68e-375">Semi-Annual Channel: версия 1808 (сборка 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="7f68e-375">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="7f68e-376">Semi-Annual Channel: версия 1803 (сборка 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="7f68e-376">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-377">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-377">Excel</span></span>

-   [<span data-ttu-id="7f68e-378">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="7f68e-378">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="7f68e-379">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-379">Office Suite</span></span>

-   [<span data-ttu-id="7f68e-380">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="7f68e-380">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="7f68e-381">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="7f68e-381">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="7f68e-382">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="7f68e-382">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="7f68e-383">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="7f68e-383">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="7f68e-384">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="7f68e-384">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="7f68e-385">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="7f68e-385">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="7f68e-386">12 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-386">March 12, 2019</span></span>
<span data-ttu-id="7f68e-387">В этом месяце ни для одного канала нет обновлений системы безопасности.</span><span class="sxs-lookup"><span data-stu-id="7f68e-387">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="7f68e-388">12 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-388">February 12, 2019</span></span>
<span data-ttu-id="7f68e-389">Monthly Channel: версия 1901 (сборка 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="7f68e-389">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="7f68e-390">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="7f68e-390">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="7f68e-391">Semi-Annual Channel: версия 1808 (сборка 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="7f68e-391">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="7f68e-392">Semi-Annual Channel: версия 1803 (сборка 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="7f68e-392">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="7f68e-393">Semi-Annual Channel: версия 1708 (сборка 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="7f68e-393">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="7f68e-394">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-394">Excel</span></span>

-   [<span data-ttu-id="7f68e-395">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="7f68e-395">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="7f68e-396">Набор Office</span><span class="sxs-lookup"><span data-stu-id="7f68e-396">Office suite</span></span>

-   [<span data-ttu-id="7f68e-397">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="7f68e-397">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="7f68e-398">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="7f68e-398">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="7f68e-399">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="7f68e-399">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="7f68e-400">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="7f68e-400">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="7f68e-401">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="7f68e-401">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="7f68e-402">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="7f68e-402">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="7f68e-403">8 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-403">January 8, 2019</span></span>

<span data-ttu-id="7f68e-404">Monthly Channel: версия 1812 (сборка 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="7f68e-404">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="7f68e-405">Semi-Annual Targeted Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="7f68e-405">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="7f68e-406">Semi-Annual Channel: версия 1808 (сборка 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="7f68e-406">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="7f68e-407">Semi-Annual Channel: версия 1803 (сборка 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="7f68e-407">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="7f68e-408">Semi-Annual Channel: версия 1708 (сборка 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="7f68e-408">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="7f68e-409">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-409">Outlook</span></span>
-   [<span data-ttu-id="7f68e-410">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="7f68e-410">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="7f68e-411">Word. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="7f68e-411">Word: Security updates</span></span> 
-   [<span data-ttu-id="7f68e-412">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="7f68e-412">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="7f68e-413">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="7f68e-413">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="7f68e-414">Набор Office. Обновления для системы безопасности</span><span class="sxs-lookup"><span data-stu-id="7f68e-414">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="7f68e-415">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="7f68e-415">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="7f68e-416">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="7f68e-416">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="7f68e-417">11 декабря 2018 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-417">December 11, 2018</span></span>
<span data-ttu-id="7f68e-418">Monthly Channel: версия 1811 (сборка 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="7f68e-418">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="7f68e-419">Semi-Annual Channel: версия 1803 (сборка 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="7f68e-419">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="7f68e-420">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="7f68e-420">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-421">Excel</span><span class="sxs-lookup"><span data-stu-id="7f68e-421">Excel</span></span>

-   [<span data-ttu-id="7f68e-422">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="7f68e-422">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="7f68e-423">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="7f68e-423">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="7f68e-424">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="7f68e-424">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="7f68e-425">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="7f68e-425">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="7f68e-426">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f68e-426">Outlook</span></span>

-   [<span data-ttu-id="7f68e-427">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="7f68e-427">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="7f68e-428">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7f68e-428">PowerPoint</span></span>

-   [<span data-ttu-id="7f68e-429">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="7f68e-429">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="7f68e-430">13 ноября 2018 г.</span><span class="sxs-lookup"><span data-stu-id="7f68e-430">November 13, 2018</span></span>
<span data-ttu-id="7f68e-431">Monthly Channel: версия 1810 (сборка 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="7f68e-431">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="7f68e-432">Semi-Annual Channel: версия 1803 (сборка 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="7f68e-432">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="7f68e-433">Semi-Annual Channel (Targeted): версия 1808 (сборка 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="7f68e-433">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="7f68e-434">Excel.</span><span class="sxs-lookup"><span data-stu-id="7f68e-434">Excel:</span></span>

-   [<span data-ttu-id="7f68e-435">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="7f68e-435">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="7f68e-436">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="7f68e-436">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="7f68e-437">Outlook.</span><span class="sxs-lookup"><span data-stu-id="7f68e-437">Outlook:</span></span>

-   [<span data-ttu-id="7f68e-438">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="7f68e-438">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="7f68e-439">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="7f68e-439">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="7f68e-440">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="7f68e-440">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="7f68e-441">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="7f68e-441">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="7f68e-442">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="7f68e-442">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="7f68e-443">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="7f68e-443">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="7f68e-444">Project.</span><span class="sxs-lookup"><span data-stu-id="7f68e-444">Project:</span></span>

-   [<span data-ttu-id="7f68e-445">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="7f68e-445">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="7f68e-446">Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="7f68e-446">Skype for Business:</span></span>

-   [<span data-ttu-id="7f68e-447">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="7f68e-447">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="7f68e-448">Word.</span><span class="sxs-lookup"><span data-stu-id="7f68e-448">Word:</span></span>

-   [<span data-ttu-id="7f68e-449">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="7f68e-449">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ru-RU/security-guidance/advisory/CVE-2018-8573)
