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
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068062"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="a4e8e-103">Известные проблемы с Office 365 профессиональный плюс</span><span class="sxs-lookup"><span data-stu-id="a4e8e-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="a4e8e-104">В этом перечне известных проблем приводятся сведения об обновлениях, не связанных с безопасностью, которые включены в обновления Monthly Channel, SACT и SAC для Office 365 профессиональный плюс в 2019 г., Visio Pro для Office 365, клиента Microsoft Project Online для настольных ПК и Office 365 бизнес.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="a4e8e-105">В таблице далее содержатся краткие сведения о текущих активных проблемах и проблемах, которые уже решены.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="a4e8e-106">Мы будем добавлять в эту таблицу информацию о существенных проблемах, которые мы сейчас изучаем.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="a4e8e-107">Этот список не является полным.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="a4e8e-108">Сентябрь 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-108">September 10, 2019</span></span>

|<span data-ttu-id="a4e8e-109">Описание</span><span class="sxs-lookup"><span data-stu-id="a4e8e-109">Summary</span></span>|<span data-ttu-id="a4e8e-110">Investigating</span><span class="sxs-lookup"><span data-stu-id="a4e8e-110">Investigating</span></span>|<span data-ttu-id="a4e8e-111">Устранено</span><span class="sxs-lookup"><span data-stu-id="a4e8e-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="a4e8e-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="a4e8e-112">**Outlook**</span></span>
<span data-ttu-id="a4e8e-113">Обнаружена проблема, из-за которой файлы могли не сохраняться в WebDAV.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="a4e8e-114">Monthly Channel, версия 1909</span><span class="sxs-lookup"><span data-stu-id="a4e8e-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="a4e8e-115">**Проект**</span><span class="sxs-lookup"><span data-stu-id="a4e8e-115">**Project**</span></span>
<span data-ttu-id="a4e8e-116">Рассмотрим следующий случай.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-116">Consider the following scenario.</span></span> <span data-ttu-id="a4e8e-117">Вы открываете какой-либо проект.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-117">You open a project.</span></span> <span data-ttu-id="a4e8e-118">Вы щелкаете меню "Файл", затем команду "Экспорт" и выбираете кнопку "Создать PDF/XPS".</span><span class="sxs-lookup"><span data-stu-id="a4e8e-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="a4e8e-119">В диалоговом окне "Обзор" вы вводите имя файла и нажимаете кнопку "ОК".</span><span class="sxs-lookup"><span data-stu-id="a4e8e-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="a4e8e-120">И обнаруживаете, что PDF-файл из XPF-файла не создается.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="a4e8e-121">SAC, версия 1902</span><span class="sxs-lookup"><span data-stu-id="a4e8e-121">SAC Version 1902</span></span>||
|<span data-ttu-id="a4e8e-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="a4e8e-122">**Word**</span></span>
<span data-ttu-id="a4e8e-123">Обнаружена проблема, с которой сталкиваются пользователи при открытии файла.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="a4e8e-124">Monthly Channel, версия 1908</span><span class="sxs-lookup"><span data-stu-id="a4e8e-124">Monthly Version 1908</span></span>||
<span data-ttu-id="a4e8e-125">В файлах Office, синхронизированных с помощью модуля синхронизации OneDrive, проверить такие метаданные документов как "Обязательные свойства" и "Тип содержимого" после использования команд "Сохранить" и "Сохранить как" становится невозможно.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="a4e8e-126">SAC, версия 1902</span><span class="sxs-lookup"><span data-stu-id="a4e8e-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="a4e8e-127">Май 2019. ПРИМЕР</span><span class="sxs-lookup"><span data-stu-id="a4e8e-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="a4e8e-128">Описание</span><span class="sxs-lookup"><span data-stu-id="a4e8e-128">Summary</span></span>|<span data-ttu-id="a4e8e-129">Investigating</span><span class="sxs-lookup"><span data-stu-id="a4e8e-129">Investigating</span></span>|<span data-ttu-id="a4e8e-130">Устранено</span><span class="sxs-lookup"><span data-stu-id="a4e8e-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="a4e8e-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="a4e8e-131">**Excel**</span></span>
<span data-ttu-id="a4e8e-132">Пример разрешен для нескольких сборок. — Обнаружена проблема, приводившая для каскадных и воронкообразных диаграмм к нарушению синхронизации с таблицами при вставке или удалении ячеек.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="a4e8e-133">SAC, версия 1902</span><span class="sxs-lookup"><span data-stu-id="a4e8e-133">SAC Version 1902</span></span> <br> <span data-ttu-id="a4e8e-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="a4e8e-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="a4e8e-135">Monthly Channel, версия 1905</span><span class="sxs-lookup"><span data-stu-id="a4e8e-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="a4e8e-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="a4e8e-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="a4e8e-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="a4e8e-137">**Word**</span></span>
<span data-ttu-id="a4e8e-138">Пример разрешен для нескольких сборок, но не для всех. — Обнаружена проблема с производительностью при запуске экспресс-блоков для Свойств документа.</span><span class="sxs-lookup"><span data-stu-id="a4e8e-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="a4e8e-139">SAC, версия 1808</span><span class="sxs-lookup"><span data-stu-id="a4e8e-139">SAC Version 1808</span></span>|<span data-ttu-id="a4e8e-140">SAC, версия 1902</span><span class="sxs-lookup"><span data-stu-id="a4e8e-140">SAC Version 1902</span></span> <br> <span data-ttu-id="a4e8e-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="a4e8e-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="a4e8e-142">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="a4e8e-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
